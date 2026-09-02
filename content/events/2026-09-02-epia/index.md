---
title: "MaxSAT-Based Feedback for Guiding Vision-Language Models in Sudoku @ EPIA 2026"

event: In the *25th EPIA Conference on Artificial Intelligence 2026*
event_url: https://epia2026.web.uma.pt/index.html

location: EPIA 2026
address:
  street: 
  city: Funchal
  region: Madeira, Portugal.
  postcode: ''
  country: Portugal

summary: In this talk, we will present a neuro-symbolic approach that combines Vision-Language Models (VLMs) with MaxSAT reasoning to improve reliability on structured visual reasoning tasks. Using Sudoku as a case study, we show how a MaxSAT oracle can detect inconsistencies in VLM predictions and provide targeted feedback to guide the model toward correct solutions. Our results demonstrate the potential of combining neural perception with symbolic reasoning to build more reliable reasoning systems.

abstract: Vision-Language Models (VLMs) have demonstrated impressive capabilities in interpreting visual information and tackling complex reasoning tasks. However, their predictions are not guaranteed to satisfy the logical constraints of structured problems, which can lead to inconsistent or incorrect solutions. In this talk, we will present a neuro-symbolic approach that combines the perceptual and generative capabilities of VLMs with Maximum Satisfiability (MaxSAT) reasoning to improve the reliability of their outputs. Using Sudoku as a controlled visual reasoning benchmark, we introduce a MaxSAT oracle that verifies VLM-generated assignments against a formal encoding of the puzzle constraints. Rather than simply solving the problem for the model, the oracle identifies inconsistent predictions and provides targeted feedback that the VLM can use to revise its solution. We investigate different ways of integrating this feedback into the reasoning process, including step-by-step solving and full-board refinement. We evaluate the approach across multiple VLMs and Sudoku difficulty levels, showing that MaxSAT-based feedback can improve logical consistency, solution completeness, and overall solving performance. The improvements are particularly notable when refining candidate solutions that are already close to being correct. More broadly, our results illustrate the benefits of combining neural models with symbolic reasoning, highlighting how formal methods can provide structured, correctness-aware feedback to help build more reliable visual reasoning systems.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-09-02T11:00:00Z'
date_end: '2026-09-02T11:25:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: [Neuro-symbolic AI, Vision-Language Models, Logical Reasoning, Maximum Satisfiability, Sudoku]

# Is this a featured talk? (true/false)
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**EPIA**](https://epia2026.web.uma.pt/index.html)'
  focal_point: ''
  preview_only: false

links:
   - type: slides
     url: "../uploads/slides/slides-2026-09-02-epia.pdf"
   - name: project
     url: projects/ai4reasoning
   - name: paper
     url: publications/epia2026-2

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
- ai4reasoning

# > [!NOTE]
# > Click on the **Slides** button above to view the built-in slides feature.

---


