---
title: 📄🤖 2 Papers accepted @ EPIA 2026!! 🎉🎉
summary: Excited to share that two of our papers have been accepted at EPIA 2026, covering the robustness of LLMs for code understanding and neuro-symbolic feedback for Vision-Language Models using MaxSAT! 🎉
date: 2026-07-18
authors:
  - admin
tags:
 - Artificial Intelligence
 - Neuro-Symbolic AI
 - Large Language Models
 - Vision-Language Models
 - Maximum Satisfiability
 - Code Understanding
 - Program Analysis
 - Formal Methods
image:
  caption: 'Image credit: [**EPIA 2026**](https://epia2026.web.uma.pt)'

---

I'm very excited to share that **two of our papers have been accepted at the 25th EPIA Conference on Artificial Intelligence ([EPIA 2026](https://epia2026.web.uma.pt))**! 🎉

The accepted papers explore two complementary aspects of trustworthy AI: **understanding the reasoning capabilities of Large Language Models for code** and **improving Vision-Language Models through symbolic optimisation with MaxSAT**.

## 💻 Large Language Models Are Not (Yet) Robust in Understanding Code Against Semantics-Preserving Mutations

As LLMs become increasingly popular for programming assistance, an important question remains: **do they truly understand code, or are they often relying on superficial patterns?**

In this paper, we investigate the robustness of state-of-the-art LLMs by applying a collection of **semantics-preserving Python code transformations**, including variable renaming, mirrored comparisons, branch swapping, loop transformations, and loop unrolling. Although these mutations leave program behaviour unchanged, they frequently cause LLMs to alter their predictions.

Our study, combining benchmark evaluation with expert analysis, shows that even the strongest proprietary models remain surprisingly fragile. We find that code-specialised LLMs can produce correct answers based on flawed reasoning in **up to 45% of cases**, while performance under semantics-preserving mutations can decrease by **as much as 70%**. These results highlight that current LLMs have not yet achieved stable, semantically grounded code understanding.

{{< button url="/publications/epia2026-1" new_tab="true" style="secondary" rounded="full" align="center" >}}
Read the paper
{{< /button >}}

- {{< cite page="/publications/epia2026-1" >}}

## 🧩 MaxSAT-Based Feedback for Guiding Vision-Language Models in Sudoku

Can symbolic reasoning help Vision-Language Models solve structured reasoning problems more reliably?

In this paper, we present a **neuro-symbolic framework** that combines Vision-Language Models with a **Maximum Satisfiability (MaxSAT)** solver for Sudoku. Rather than replacing the VLM, the symbolic component acts as a logical consistency checker, identifying conflicting assignments and generating structured textual and visual feedback that guides the model towards better solutions.

By integrating formal optimisation into the reasoning loop, our approach significantly improves logical consistency and increases the number of correctly solved Sudoku instances across multiple open-source and proprietary VLMs. The results demonstrate the potential of symbolic optimisation as an effective mechanism for enhancing the reliability of multimodal AI systems.

{{< button url="/publications/epia2026-2" new_tab="true" style="secondary" rounded="full" align="center" >}}
Read the paper
{{< /button >}}

- {{< cite page="/publications/epia2026-2" >}}

I'm very grateful to my collaborators for making these works possible!

**See you in Madeira at EPIA 2026!** 🇵🇹🎉