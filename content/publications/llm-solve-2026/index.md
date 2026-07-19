---
title: "Solving MaxSAT Problems from Natural Language Descriptions with LLMs and PySAT"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Marta Kwiatkowska
- Guillem Alenyà
- Felip Manyà

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-05-27T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-05-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['Workshop']

# Publication name and optional abbreviated publication name.
publication: In the *2nd Workshop [LLMs meet Constraint Solving (LLM-Solve)](https://sites.google.com/view/llm-solve-2026) @ FLoC 2026*.
publication_short: In **LLM-Solve @ FLoC 2026**


abstract: Large Language Models (LLMs) provide a flexible interface for interpreting natural language problem descriptions, but they remain unreliable when asked to solve constrained optimisation tasks directly. We study a neuro-symbolic approach in which an LLM translates a natural language description of an optimisation problem into executable Python code using PySAT. The generated program constructs a weighted partial Maximum Satisfiability (MaxSAT) instance, invokes a MaxSAT solver, and returns the resulting assignment in a prescribed output format. In this way, the LLM is used primarily for semantic parsing and modelling, while the optimisation step is delegated to an exact symbolic solver. We outline an end-to-end pipeline consisting of natural language input, intermediate encoding plans, PySAT code generation, MaxSAT solving through RC2, and independent validation of returned solutions. This workshop abstract distils the main idea of using LLMs as natural language front-ends for solver-backed MaxSAT modelling, with the goal of making MaxSAT technology more accessible to users who do not write formal encodings by hand.

# Summary. An optional shortened abstract.
summary: In this paper, we study a neuro-symbolic approach in which an LLM translates a natural language description of an optimisation problem into executable Python code using PySAT. The generated program constructs a weighted partial Maximum Satisfiability (MaxSAT) instance, invokes a MaxSAT solver, and returns the resulting assignment in a prescribed output format.

tags:
 - Large Language Models
 - Maximum Satisfiability
 - Formal Methods
 - Neuro-symbolic AI
 - Reliable Reasoning
 
# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    arxiv: 2605.29687
    # doi: 10.48550/arXiv.2605.29687

# Custom links
links:
  - type: pdf
    url: "../uploads/papers/llm-solve-2026-workshop-paper.pdf"    
  #- name: project
  #  url: projects/ai4code

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**LLM-Solve Workshop**](https://sites.google.com/view/llm-solve-2026)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - ai4code

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
