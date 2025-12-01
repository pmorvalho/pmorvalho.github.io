---
title: "PyVeritas: On Verifying Python via LLM-Based Transpilation and Bounded Model Checking for C"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Marta Kwiatkowska

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-01-26T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-11-10T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['Workshop']

# Publication name and optional abbreviated publication name.
publication: In the *1st International Workshop on [Post-AI Formal Methods (P-AI-FM)](https://www.p-ai-fm.com) @ AAAI 2026*.
publication_short: In **P-AI-FM @ AAAI 2026**


abstract: Python has become the dominant language for general-purpose programming, yet it lacks robust tools for formal verification. In contrast, programmers working in languages such as C benefit from mature model checkers, for example CBMC, which enable exhaustive symbolic reasoning and fault localisation. The inherent complexity of Python, coupled with the verbosity and low-level nature of existing transpilers (e.g., Cython), have historically limited the applicability of formal verification to Python programs. In this paper, we propose PyVeritas, a novel framework that leverages Large Language Models (LLMs) for high-level transpilation from Python to C, followed by bounded model checking and MaxSAT-based fault localisation in the generated C code. PyVeritas enables verification and bug localisation for Python code using existing model checking tools for C. Our empirical evaluation on two Python benchmarks demonstrates that LLM-based transpilation can achieve a high degree of accuracy, up to 80--90% for some LLMs, enabling effective development environment that supports assertion-based verification and interpretable fault diagnosis for small yet non-trivial Python programs.

# Summary. An optional shortened abstract.
summary: In this paper, we propose PyVeritas, a novel framework that leverages Large Language Models (LLMs) for high-level transpilation from Python to C, followed by bounded model checking and MaxSAT-based fault localisation in the generated C code.

tags:
  - Software Verification
  - Model Checking
  - Python Verification
  - LLM-Based Transpilation
  - MaxSAT-Based Fault Localisation
  - Formal Methods
  - CFaults
  - PyVeritas

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    arxiv: 2508.08171
    # doi: 10.1145/3643788.3648010    

# Custom links
links:
#  - type: pdf
#    url: "../uploads/papers/p-ai-fm-2026-PyVeritas.pdf"    
#  - type: code  
#    url: https://github.com/pmorvalho/C-Pack-IPAs
#  - type: slides
#     url: https://www.slideshare.net/
#  - type: video
#     url: https://youtube.com
  - name: project
    url: projects/ai4code

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**P-AI-FM-26 Workshop**](https://www.p-ai-fm.com)'
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
