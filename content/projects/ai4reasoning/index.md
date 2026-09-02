---
title: Neuro-Symbolic AI for Reliable Reasoning
date: 2026-09-01

authors:
  - admin

tags:
  - Neuro-Symbolic AI
  - Reliable Reasoning
  - Artificial Intelligence
  - Large Language Models
  - Vision-Language Models
  - Automated Reasoning
  - Maximum Satisfiability
  - Formal Methods
  - Program Analysis
  - Program Repair
  - Constraint Solving
  - Model-Based Diagnosis
  - Trustworthy AI

image:
  caption: 'Source: GPT-5.6 Sol'
  focal_point: Center

---

Modern **foundation models**, including **Large Language Models (LLMs)** and **Vision-Language Models (VLMs)**, have remarkable capabilities for understanding natural language, code, and visual information. However, their outputs remain fundamentally **probabilistic**: even highly capable models can produce solutions that violate logical constraints, generate incorrect programs, or fail to reason reliably about structured problems.

My research on **Neuro-Symbolic AI for Reliable Reasoning** explores how **Automated Reasoning (AR)** and **Formal Methods** can be combined with neural models to make their reasoning processes **more reliable, verifiable, and correct**.

The central idea is simple:

> **Let neural models interpret, generate, and learn — and let symbolic methods reason, verify, diagnose, and optimise.**

Rather than relying exclusively on a neural model to solve a problem end-to-end, I investigate architectures in which **neural and symbolic components collaborate**, exploiting their complementary strengths.

This research spans reasoning over **natural language, visual information, and programs**, with symbolic techniques such as **Maximum Satisfiability (MaxSAT)**, **[Model-Based Diagnosis (MBD)](/projects/cfaults)**, constraint solving, model checking, and formal verification acting as **solvers, verifiers, or feedback mechanisms**.

At a high level, the objective is to answer a fundamental question:

> **How can symbolic reasoning make neural AI systems more reliable?**

---

## 🧠 + ⚙️ Neural and Symbolic Reasoning

Neural and symbolic approaches provide complementary strengths.

**Neural models** are particularly effective at:

- understanding natural language and visual inputs;
- extracting semantic information from unstructured data;
- generating programs and structured representations;
- adapting to new tasks from instructions and examples.

**Symbolic methods**, in contrast, provide:

- explicit representations of constraints;
- logically consistent reasoning;
- exact optimisation;
- independent verification of candidate solutions;
- fault localisation and diagnosis;
- formal guarantees about properties of a system.

The goal is therefore not to replace neural models with symbolic systems, or symbolic systems with neural models.

Instead, I investigate architectures in which neural models handle the **semantic and generative aspects** of a problem, while symbolic methods provide the **reasoning, verification, optimisation, and feedback** needed to improve reliability.

A general abstraction of this research direction is:

**Unstructured Input → Neural Model → Symbolic Representation → Automated Reasoning → Verification / Feedback → Neural Model**

The symbolic component can therefore play different roles: it may act as the **solver**, as a **verifier**, as a **diagnostic engine**, or as an **oracle that provides feedback** to the neural model.

---

## 🗣️ Reliable Reasoning from Natural Language

One direction of my research investigates whether **LLMs can make formal optimisation and constraint-solving technologies accessible through natural language**, while delegating exact reasoning to symbolic solvers.

Traditional symbolic solvers are extremely powerful, but using them typically requires expertise in formal modelling and the ability to manually translate a problem into variables, constraints, and objective functions.

LLMs provide a potential bridge between these two worlds.

In our recent [work](/publications/llm-solve-2026), we study a hybrid approach in which an LLM translates a natural-language problem into executable Python code that encodes user-defined constraints and preferences as a **preference-based Maximum Satisfiability (MaxSAT)** problem.

The overall pipeline is:

1. 📝 A user describes an optimisation problem in **natural language**.
2. 🧠 An **LLM interprets the problem** and constructs a formal modelling strategy.
3. 🐍 The model generates executable **Python / PySAT code**.
4. ⚙️ The generated program constructs a **weighted partial MaxSAT instance**.
5. 🔎 An exact MaxSAT solver, such as **RC2**, computes a solution.
6. ✅ The result is **independently verified** for feasibility and optimality using a canonical MaxSAT encoding.
7. 💬 The solution is returned in the required output format.

This division of responsibilities is important.

Instead of asking the LLM to internally perform combinatorial optimisation, the neural model handles **natural-language understanding and semantic modelling**, while an exact symbolic solver performs the optimisation.

The resulting architecture provides a path towards **natural-language interfaces for formal reasoning systems**, making technologies such as SAT and MaxSAT more accessible while retaining solver-based guarantees.

The corresponding full paper is available as an [**arXiv preprint**](https://arxiv.org/abs/2605.29687).

---

## 👁️ Reliable Reasoning from Visual Information

A complementary direction asks a different question:

> **Can symbolic reasoning help neural models recognise and correct their own mistakes?**

In [**MaxSAT-Based Feedback for Guiding Vision-Language Models in Sudoku**](/publications/epia2026-2), we investigate this question using **Sudoku as a controlled visual reasoning benchmark**.

VLMs can interpret Sudoku boards and attempt to solve them directly from images. However, candidate solutions generated by VLMs may contain assignments that violate the underlying logical constraints.

Rather than replacing the VLM with a conventional Sudoku solver, our approach introduces a **MaxSAT oracle** that acts as a consistency validator and refinement engine.

The interaction can be viewed as:

**Sudoku Image → VLM → Candidate Solution → MaxSAT Oracle → Feedback → VLM → Revised Solution**

Candidate placements generated by the VLM are encoded as **soft clauses**, while the Sudoku rules are represented as **hard clauses**.

When inconsistencies arise, the MaxSAT solver identifies a **largest mutually consistent subset of assignments**. This symbolic result is then translated into **structured textual and visual feedback**, which is provided to the VLM to guide subsequent refinement.

This creates an iterative neuro-symbolic reasoning loop:

1. 👁️ The **VLM interprets the visual problem**.
2. 🧠 The VLM proposes candidate assignments.
3. ⚙️ A **MaxSAT oracle checks logical consistency**.
4. ❌ Inconsistent assignments are identified.
5. 💬 Symbolic information is transformed into **targeted feedback**.
6. 🔄 The VLM uses the feedback to revise its prediction.
7. ✅ The process continues towards a logically consistent solution.

Experiments across multiple open-source and closed-access VLMs show that **MaxSAT-based feedback improves logical consistency and increases the number of solved Sudoku instances**, particularly when refining the full board.

This [paper](/publications/epia2026-2) has been presented at **the 25th EPIA Conference on Artificial Intelligence (EPIA 2026)**.

---

## 💻 Reliable Reasoning about Programs

A third and particularly important direction of my research applies the same neuro-symbolic principles to **programs**.

Code generated by LLMs is often syntactically plausible but can nevertheless be **semantically incorrect**. Conversely, formal methods can provide strong guarantees about program behaviour but generally require structured models, specifications, and specialised tooling.

This creates a natural opportunity for collaboration between neural code generation and symbolic program analysis.

### 🤖 LLM-Driven Program Repair with Formal Fault Localisation

In [**Counterexample Guided Program Repair Using Zero-Shot Learning and MaxSAT-based Fault Localization**](/publications/aaai2025), and in [MENTOR](/publications/jss2026), we combine **Large Language Models** with **MaxSAT-based fault localisation**.

Rather than asking an LLM to rewrite an entire faulty program, the symbolic component first identifies the likely buggy statements.

The LLM is then presented with a **program sketch in which the faulty statements have been removed**, and is asked to synthesise replacements.

The process follows a **Counterexample-Guided Inductive Synthesis (CEGIS)** loop:

**Program → MaxSAT Fault Localisation → Program Sketch → LLM Synthesis → Test Suite → Counterexample → LLM**

If the generated program is incorrect, counterexamples from the test suite are fed back to the LLM to guide subsequent repairs.

In experiments on **1,431 incorrect student programs**, this hybrid approach improved the repair capabilities of the evaluated LLMs, while also producing **smaller fixes** than approaches relying solely on LLM-based rewriting.

This work illustrates a key principle of my research:

> **Use symbolic reasoning to constrain where a neural model needs to act, and use neural generation to fill the remaining gaps.**

---

### 🐍 LLM-Based Transpilation and Formal Verification

The same idea can be extended beyond program repair.

In [**PyVeritas: On Verifying Python via LLM-Based Transpilation and Bounded Model Checking for C**](/publications/p-ai-fm-2026), we investigate whether LLMs can act as a bridge between a high-level programming language and mature formal verification technologies.

Python has relatively limited support for automated formal verification compared with languages such as C, where powerful model checkers such as [CBMC](https://github.com/diffblue/cbmc) are available.

PyVeritas therefore uses an **LLM for high-level transpilation from Python to C**, after which the generated C program can be analysed using **bounded model checking** and **MaxSAT-based fault localisation**.

The architecture can be summarised as:

**Python Program → LLM-Based Transpilation → C Program → Model Checking → MaxSAT Fault Localisation**

This approach demonstrates how neural models can serve as a **semantic bridge** to existing symbolic verification infrastructure.

Experimental results on two Python benchmarks show that LLM-based transpilation can reach **80–90% accuracy for some evaluated models**, enabling assertion-based verification and interpretable fault diagnosis for small but non-trivial Python programs.

---

## 🔄 From Symbolic Solvers to Symbolic Oracles

These projects explore several complementary ways in which symbolic reasoning can interact with neural models.

In one setting, the neural model translates an informal problem into a representation that can be handled by a **symbolic solver**:

**Natural Language → LLM → Formalisation → MaxSAT → Solution**

In another, the neural model proposes a solution and the symbolic system acts as an **oracle that evaluates and improves it**:

**Visual Input → VLM → Candidate → MaxSAT → Feedback → VLM**

For program reasoning, the symbolic component can instead **localise faults, constrain generation, or verify behaviour**:

**Program → Formal Analysis → Fault / Constraint Information → LLM → Revised Program → Verification**

Together, these architectures illustrate a broader research agenda in which symbolic reasoning components serve as:

- **Solvers**, computing exact solutions to problems formalised by neural models;
- **Verifiers**, checking whether neural outputs satisfy formal specifications;
- **Diagnostic engines**, identifying faults or inconsistencies in neural outputs or generated programs;
- **Oracles**, determining which parts of a candidate solution are mutually consistent;
- **Feedback generators**, converting symbolic reasoning results into information that neural models can use for refinement.

Rather than treating symbolic reasoning as a final validation step, I am interested in systems where **symbolic reasoning actively participates in the neural reasoning process**.

---

## 🔬 Foundations: Model-Based Diagnosis and Automated Reasoning

This research builds on my broader work in **Automated Reasoning, Model-Based Diagnosis, Maximum Satisfiability, and Formal Methods**.

In [**CFaults**](/projects/cfaults), I developed a MaxSAT-based approach to **formula-based fault localisation for C programs with multiple test cases**.

CFaults uses **Model-Based Diagnosis (MBD)** and aggregates all failing test cases into a unified MaxSAT formulation. This enables consistent reasoning across multiple observations and guarantees that the generated diagnoses are **subset-minimal**.

These symbolic techniques provide an important foundation for the later neuro-symbolic work.

The underlying idea is the same: rather than relying solely on heuristic or probabilistic reasoning, we can formulate a problem explicitly in terms of **constraints, observations, diagnoses, and optimisation objectives**, and then use an exact reasoning engine to obtain trustworthy results.

Neuro-Symbolic AI extends this principle by placing such symbolic reasoning mechanisms **inside an interaction loop with neural models**.

---

## 🎯 Towards Reliable and Trustworthy AI

The broader goal of this research is to develop AI systems that preserve the **flexibility and generalisation capabilities of neural models** while providing stronger guarantees about their outputs and reasoning processes.

I am particularly interested in questions such as:

- **How can neural models reliably translate natural-language problems into formal constraints?**
- **How can symbolic solvers detect and explain errors made by neural models?**
- **What forms of symbolic feedback are most effective for guiding LLMs and VLMs?**
- **How can formal methods constrain neural code generation and program repair?**
- **How should neural and symbolic components interact in iterative reasoning loops?**
- **Can exact reasoning mechanisms provide stronger correctness guarantees for AI-generated solutions?**
- **How can these approaches scale beyond controlled benchmarks to real-world AI systems?**

The long-term vision is to move beyond the paradigm of simply asking a neural model for an answer.

Instead, I am interested in **collaborative AI systems** in which neural models and symbolic reasoners continuously complement one another:

**Neural AI provides learning, perception, language, and generation.**

**Symbolic AI provides logic, constraints, optimisation, diagnosis, verification, and guarantees.**

By bringing these capabilities together, **Neuro-Symbolic AI for Reliable Reasoning** aims to develop AI systems that are not only capable, but also **reliable, verifiable, interpretable, and trustworthy**.

---

## References

- **Pedro Orvalho**, Marta Kwiatkowska, Guillem Alenyà, and Felip Manyà (2026). *Reliable Reasoning with Large Language Models via Preference-Based Maximum Satisfiability*. [arXiv:2605.29687](https://arxiv.org/abs/2605.29687).

- {{< cite page="/publications/llm-solve-2026" >}}

- {{< cite page="/publications/epia2026-2" >}}

- {{< cite page="/publications/aaai2025" >}}

- {{< cite page="/publications/p-ai-fm-2026" >}}

- {{< cite page="/publications/fm2024" >}}

- {{< cite page="/publications/jss2026" >}}

- {{< cite page="/publications/phd-thesis" >}}

<!--more-->

I am always excited to explore new ideas together. **Feel free to reach out** 📧 if you are interested in collaborating on **Neuro-Symbolic AI**, **Automated Reasoning**, and **Reliable and Trustworthy AI**!