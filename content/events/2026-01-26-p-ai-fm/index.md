---
title: "PyVeritas: On Verifying Python via LLM-Based Transpilation and Bounded Model Checking for C"

event: In the *1st International Workshop on Post-AI Formal Methods (P-AI-FM) @ AAAI 2026*
event_url: https://www.p-ai-fm.com

location: AAAI 2026
address: 
  street: Singapore
  city: 
  region: Singapore.
  postcode: ''
  country: ''

summary: In this talk I will present PyVeritas, a novel framework that leverages Large Language Models (LLMs) for high-level transpilation from Python to C, followed by bounded model checking and MaxSAT-based fault localisation in the generated C code.

abstract: Python has become the dominant language for general-purpose programming, yet it lacks robust tools for formal verification. In contrast, programmers working in languages such as C benefit from mature model checkers, for example CBMC, which enable exhaustive symbolic reasoning and fault localisation. The inherent complexity of Python, coupled with the verbosity and low-level nature of existing transpilers (e.g., Cython), have historically limited the applicability of formal verification to Python programs. In this talk, I am going to present PyVeritas, a novel framework that leverages Large Language Models (LLMs) for high-level transpilation from Python to C, followed by bounded model checking and MaxSAT-based fault localisation in the generated C code. PyVeritas enables verification and bug localisation for Python code using existing model checking tools for C. Our empirical evaluation on two Python benchmarks demonstrates that LLM-based transpilation can achieve a high degree of accuracy, up to 80--90% for some LLMs, enabling effective development environment that supports assertion-based verification and interpretable fault diagnosis for small yet non-trivial Python programs.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-01-26T09:00:00Z'
date_end: '2026-01-26T09:15:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: [Software Verification, Model Checking, Python Verification, LLM-Based Transpilation, MaxSAT-Based Fault Localisation, Formal Methods, CFaults, PyVeritas]

# Is this a featured talk? (true/false)
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**P-AI-FM-26 Workshop**](https://www.p-ai-fm.com)'  
  focal_point: ''
  preview_only: false


links:
   - type: slides
     url: "../uploads/slides/slides-2026-01-26-p-ai-fm.pdf"
   - name: paper
     url: publications/p-ai-fm-2026
   - name: project
     url: projects/ai4code

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


