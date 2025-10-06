---
title: "Artificial Intelligence for CS Education"
date: 2025-01-01

tags:
  - AI4Education
  - Intelligent Tutoring Systems
  - Computer Science Education  
  - Programming Education
  - Software Engineering Education
  - Artificial Intelligence
  
image:
  caption: 'Image credit: [**Perplexity AI**](https://www.perplexity.ai)'
  focal_point: Right

authors:
  - admin

---

Empowering the next generation of programmers requires intelligent systems that not only evaluate code but also **teach, guide, and inspire**. This research explores how **Artificial Intelligence (AI)**, ranging from *statistical models* such as **Large Language Models (LLMs)** to *formal reasoning systems* like **Maximum Satisfiability (MaxSAT)-based approaches**, can transform **computer science education** by providing **personalised feedback**, **automated tutoring**, and **scalable assessment**.  

Our goal is to design AI-driven tools that help students develop a **deeper conceptual understanding** of programming and software engineering, while supporting instructors in delivering **fair, consistent, and insightful evaluations**.  

---

Teaching computer science effectively requires more than grading correctness, it demands helping students understand *why* their code behaves as it does. As programming education scales to hundreds or thousands of learners, providing this level of **personalised, conceptual feedback** becomes increasingly difficult.  

By combining **neural adaptability** with **symbolic precision**, we aim to bridge the gap between automation and understanding. These AI systems can assess student submissions, locate bugs, explain misconceptions, and even propose guided repairs, helping students learn not just *to program*, but *to think like computer scientists*.  

Our ongoing projects investigate this vision across multiple levels of abstraction:  
- developing scalable **automated assessment platforms**,  
- integrating **formal reasoning** for accurate and constructive feedback,  
- exploring **AI-driven program repair** as an educational aid, and  
- building domain-specific systems for **logic programming** and beyond.  

Together, these efforts define a new direction for **AI in computer science education**: one where intelligent systems act not as graders, but as **collaborative mentors**, empowering learners through insight, explanation, and guided exploration.


---

## 🧩 AI-Powered Automated Assessment for Programming Education  

[**GitSEED**](projects/gitseed) is a **language-agnostic automated assessment platform** designed for *Programming* and *Software Engineering* courses, tightly integrated with **GitLab**.  

Students interact with GitSEED directly through GitLab, allowing them to master fundamental tools such as `git` while receiving **personalised, automated feedback** on assignments and projects.  

GitSEED’s modular pipeline enables instructors to easily integrate a wide range of **AI, and verification-based tools**, from **memory leak detection** to **fault localisation** and **program repair**, to tailor feedback according to each course’s learning objectives.  

Our experiments, conducted across multiple university courses, show that GitSEED improves **student engagement** and supports **deeper learning outcomes** by providing immediate, actionable feedback.  

GitSEED’s flexibility makes it a powerful educational framework, capable of unifying **AI-driven feedback**, **automated testing**, and **formal reasoning tools** into a single pedagogical ecosystem.  

---

## 🧠 Using Formal Reasoning to Enhance Educational Feedback

[**CFaults**](/projects/cfaults) is a **MaxSAT-based fault localisation tool** that identifies the precise source of errors in C programs.  

In *Spring 2024*, we integrated CFaults with GitSEED in a **first-year undergraduate programming course**. The tool automatically analysed students’ submissions, pinpointing likely faulty statements and generating **error hints** as structured feedback.  

Survey results showed that **69% of students** found these hints *helpful* in understanding and correcting their mistakes. The feedback promoted **self-directed learning** and **conceptual understanding**, demonstrating that formal reasoning methods can play a key educational role alongside traditional assessment techniques.  

Overall, this study highlighted CFaults’ potential as an **intelligent tutoring aid**, using rigorous reasoning to guide students in developing correct and robust code.  

---

## 🔧 Semantic Automated Program Repair for Learning  

We developed [**MENTOR**](projects/mentor), a **semantic automated program repair (APR)** framework aimed at supporting **introductory programming education**.  

MENTOR automatically analyses incorrect student submissions, validates repairs through a **test suite**, and either provides a **corrected version of the program** or highlights **faulty statements** using CFaults.  

By combining symbolic reasoning with repair synthesis, MENTOR enables **fine-grained, interpretable feedback** that helps students not only fix their code but also understand *why* it was incorrect.  

This system embodies the broader vision of **explainable AI for education**, bridging the gap between automation and human understanding.  

---

## 🧮 Automated Assessment for Logic Programming 

[**ProHelp**](https://arxiv.org/abs/2504.16742) extends the GitSEED ecosystem to **Prolog**, providing a specialised assessment platform for **logic programming education**.  

ProHelp integrates multiple feedback mechanisms, including:  
- automated testing,  
- typo correction suggestions, and  
- validation of implementation strategies.  

A **mixed-methods study** with *365 undergraduate students* over a 9-week course demonstrated that ProHelp improved learning efficiency and supported students in adopting better problem-solving strategies.  

By embedding ProHelp within the GitSEED infrastructure, we established a **cohesive AI-assisted learning environment** that spans from imperative to declarative programming paradigms.  

---

## 🚀 Towards AI Tutors that Teach How to Think  

Taken together, these projects illustrate a unified vision: **AI systems that teach computer science not just by grading, but by reasoning**.  

By combining **LLMs’ adaptive language understanding** with **formal verification’s precision**, we aim to create AI tutors that can:  
- identify errors and misconceptions,  
- provide personalised, constructive feedback, and  
- guide students toward a deeper understanding of core CS principles.  

Ultimately, this research seeks to democratise access to **high-quality, scalable, and interpretable feedback**, for all students.

References:

- {{< cite page="/publications/sigcse-virtual-2024" >}}

- {{< cite page="/publications/fm2024" >}}

- {{< cite page="/publications/phd-thesis" >}}

- Ricardo Brancas, **Pedro Orvalho**, Carolina Carreira, Vasco Manquinho, Ruben Martins (2025). [Can Automated Feedback Turn Students into Happy Prologians?](https://arxiv.org/pdf/2504.16742). *In arXiv 2025*.

<!--more-->

I am always excited to explore new ideas together!
Feel free to reach out 📧 if you are interested in collaborating on these research topics.
