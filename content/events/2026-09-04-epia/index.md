---
title: "Large Language Models Are Not (Yet) Robust in Understanding Code Against Semantics-Preserving Mutations @ EPIA 2026"

event: In the *25th EPIA Conference on Artificial Intelligence 2026*
event_url: https://epia2026.web.uma.pt/index.html

location: EPIA 2026
address:
  street: 
  city: Funchal
  region: Madeira, Portugal.
  postcode: ''
  country: Portugal

summary: In this talk, we will present an empirical study investigating whether state-of-the-art Large Language Models (LLMs) can genuinely reason about Python programs or are simply guessing. Using semantics-preserving code mutations and human expert analysis, we evaluate the reasoning quality and robustness of nine open-source and closed-access LLMs. Our results reveal substantial fragility to syntactic changes and show that even correct predictions can be based on flawed reasoning, raising important questions about the reliability of LLMs for programming tasks.

abstract: Large Language Models (LLMs) are increasingly used for programming tasks, particularly with the widespread adoption of practices such as vibe coding. While these models can achieve impressive performance on code understanding and program output prediction, high accuracy does not necessarily imply that their predictions are supported by sound reasoning. Understanding how LLMs reason about code, and how robust that reasoning is to changes in syntax, is therefore critical for their reliable use in software development. In this talk, we will present an empirical study investigating whether state-of-the-art LLMs can genuinely reason about Python programs or are simply guessing. We introduce five semantics-preserving code mutations—including variable renaming, mirroring comparison expressions, swapping if-else branches, converting for loops to while loops, and loop unrolling—that alter the syntax of a program while preserving its behavior. We use these transformations to test whether model predictions remain stable when the underlying program semantics are unchanged. We evaluate nine open-source and closed-access LLMs using LiveCodeBench and CruxEval, complemented by a human expert analysis of whether correct predictions are supported by sound reasoning. While proprietary models generally achieve the strongest predictive accuracy and reasoning quality, our analysis reveals substantial fragility across the evaluated models. Code-specialised LLMs can produce correct predictions based on flawed reasoning in up to 45% of cases, while semantics-preserving transformations can lead to performance drops of up to 70%. Our findings demonstrate that strong predictive accuracy alone is not sufficient evidence of reliable program reasoning. More broadly, they highlight the importance of evaluating not only whether LLMs produce correct answers, but also whether those answers arise from stable, semantically grounded reasoning—an increasingly important consideration as LLM-generated and LLM-assisted code becomes more prevalent.


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-09-04T09:55:00Z'
date_end: '2026-09-04T10:20:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: [LLMs for Code Understanding, Semantic Robustness of Large Language Models, Code Mutations, AI4SE, MaxSAT-Based Fault Localisation, Formal Methods]

# Is this a featured talk? (true/false)
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**EPIA**](https://epia2026.web.uma.pt/index.html)'
  focal_point: ''
  preview_only: false

links:
   #- type: slides
   #  url: "../uploads/slides/slides-2026-09-04-epia.pdf"
   - name: project
     url: projects/ai4code
   - name: paper
     url: publications/epia2026-1

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


