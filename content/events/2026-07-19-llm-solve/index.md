---
title: "Solving MaxSAT Problems from Natural Language Descriptions with LLMs and PySAT @ LLM-Solve @ FLoC 2026"

event: In the *2nd Workshop LLMs meet Constraint Solving (LLM-Solve) @ FLoC 2026*.
event_url: https://sites.google.com/view/llm-solve-2026

location: FLoC 2026
address: 
  street: Lisbon
  city: 
  region: Portugal.
  postcode: ''
  country: ''

summary: In this talk, we will present a framework for solving MaxSAT problems expressed in natural language by combining large language models with the PySAT toolkit. We will show how LLMs can translate informal descriptions into formal constraints, use symbolic solvers to compute solutions, and explain the results. We will also discuss the strengths and limitations of this neuro-symbolic approach, including formalisation errors, reliability, verification, and opportunities for improved human interaction.

abstract: Large Language Models (LLMs) provide a flexible interface for interpreting natural language problem descriptions, but they remain unreliable when asked to solve constrained optimisation tasks directly. In our work, we study a neuro-symbolic approach in which an LLM translates a natural language description of an optimisation problem into executable Python code using PySAT. The generated program constructs a weighted partial Maximum Satisfiability (MaxSAT) instance, invokes a MaxSAT solver, and returns the resulting assignment in a prescribed output format. In this way, the LLM is used primarily for semantic parsing and modelling, while the optimisation step is delegated to an exact symbolic solver. We outline an end-to-end pipeline consisting of natural language input, intermediate encoding plans, PySAT code generation, MaxSAT solving through RC2, and independent validation of returned solutions. Our wokrs distils the main idea of using LLMs as natural language front-ends for solver-backed MaxSAT modelling, with the goal of making MaxSAT technology more accessible to users who do not write formal encodings by hand.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-07-19T12:00:00Z'
date_end: '2026-07-19T12:20:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: [Neuro-symbolic AI, Reliable Reasoning, Large Language Models, Maximum Satisfiability, Formal Methods]

# Is this a featured talk? (true/false)
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**LLM-Solve 2026 Workshop**](https://sites.google.com/view/llm-solve-2026)'  
  focal_point: ''
  preview_only: false


links:
   #- type: slides
   #  url: "../uploads/slides/slides-2026-01-26-p-ai-fm.pdf"
   - name: paper
     url: publications/llm-solve-2026
   #- name: project
   #  url: projects/ai4code

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- ai4code

# > [!NOTE]
# > Click on the **Slides** button above to view the built-in slides feature.

---


