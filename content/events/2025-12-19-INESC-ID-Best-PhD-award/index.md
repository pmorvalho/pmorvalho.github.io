---
title: "MENTOR: Fixing Introductory Programming Assignments With Formula-Based Fault Localization and LLM-Driven Program Repair"

event: INESC-ID Best PhD Student 2025 Award
event_url: https://www.inesc-id.pt/about-us/inesc-id-awards-2/

location: INESC-ID
address: 
  street: 
  city: Lisbon
  region: Portugal.
  postcode: ''
  country: 'Portugal'

summary: In this talk, I will present my PhD work on MENTOR, a semantic automated program repair framework designed to provide meaningful feedback for introductory programming assignments.

abstract: The rapid growth of introductory programming courses has created a pressing need for scalable, personalised feedback on student code. In this talk, I will present my PhD work on MENTOR, a semantic automated program repair framework designed to provide meaningful feedback for introductory programming assignments. MENTOR generates and validates candidate repairs for faulty student programs and highlights the underlying buggy statements to support learning. MENTOR combines formal methods and machine learning, student submissions are clustered independently of control-flow structure, variables are aligned using graph neural networks, and faults are localised using CFaults, a Maximum Satisfiability (MaxSAT)-based diagnosis engine. Repairs are synthesised via a counterexample-guided loop that integrates Large Language Models (LLMs) with formal verification, enabling flexible, semantics-preserving fixes without requiring structurally identical reference solutions. Experiments on the C-Pack-IPAs benchmark show that MENTOR substantially outperforms prior symbolic repair approaches, demonstrating how combining LLMs with rigorous formal reasoning can deliver robust and pedagogically useful feedback for programming education.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-12-19T16:00:00Z'
date_end: '2025-12-19T16:30:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-12-17T00:00:00Z'

authors:
  - admin

tags: [MENTOR, Computer-aided Education, LLM-Based Program Repair, Automated Program Repair, Fault Localisation, Large Language Models, PhD, INESC-ID]

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**INESC-ID**](https://www.inesc-id.pt/about-us/inesc-id-awards-2/)'

links:
   - type: slides
     url: "../uploads/slides/slides-2025-12-19-inesc-id-best-phd-award.pdf"
   - name: project
     url: projects/mentor
     

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
- mentor
- ai4education

# > [!NOTE]
# > Click on the **Slides** button above to view the built-in slides feature.

---


