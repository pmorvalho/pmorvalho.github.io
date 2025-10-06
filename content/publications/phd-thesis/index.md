---
title: "MENTOR: Automated Feedback for Introductory Programming Exercises"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-04-10T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-10T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['thesis']

# Publication name and optional abbreviated publication name.
publication: Thesis to obtain the PhD Degree in Computer Science and Engineering @ IST, Universidade de Lisboa. 🏆🏆 **_Summa Cum Laude_** 🏆🏆
publication_short: PhD Thesis
# 🏆🏆 **_Summa Cum Laude_** 🏆🏆


abstract: The increasing demand for programming education has given rise to all kinds of online evaluations such as Massive Open Online Courses (MOOCs) focused on introductory programming assignments (IPAs). As a consequence of a large number of enrolled students, one of the main challenges in these courses is to provide valuable and personalized feedback to students. This thesis presents MENTOR, a semantic automated program repair (APR) framework designed to provide Automated Feedback for Introductory Programming Exercises. MENTOR addresses this challenge by generating possible repairs for faulty student programs, enabling semantic repairs validated through execution on a test suite and by highlighting these faulty statements to the students. Hence, in the context of this work, we provide scientific contributions in several areas, such as program clustering and analysis, automated fault localization and program repair. MENTOR advances the state of the art in the referred areas and provides an innovative practical framework to be deployed in educational environments. Unlike symbolic repair tools like Clara and Verifix, which require correct implementations with identical control flow graphs (CFGs), MENTOR’s Large Language Model (LLM)-based approach enables flexible repairs without strict structural alignment. MENTOR clusters successful submissions regardless of CFGs and employs a Graph Neural Network (GNN)-based variable alignment module for enhanced accuracy. MENTOR’s fault localization module, CFaults, leverages MaxSAT techniques to pinpoint buggy code segments precisely. MENTOR’s program fixer integrates Formal Methods (FM) and LLMs through a Counterexample Guided Inductive Synthesis (CEGIS) loop, iteratively refining repairs. Furthermore, this work also proposes a language-agnostic automated assessment tool, GitSEED, that enhances student learning by providing personalized feedback on code submissions and successfully integrates CFaults for effective fault detection on student code. Experimental results on C-Pack-IPAs demonstrate that MENTOR significantly improves repair success rates, achieving 64.4%, compared to just 6.3% for Verifix and 34.6% for Clara.

# Summary. An optional shortened abstract.
summary: This PhD thesis presents MENTOR, a semantic automated program repair (APR) framework designed to provide Automated Feedback for Introductory Programming Exercises.

tags:
  - Automated Program Repair
  - Computer-aided Education
  - Large Language Models
  - Automated Reasoning
  - Automated Verification
  - Formal Methods
  - Artificial Intelligence
  - Model-Based Diagnosis
  - MENTOR
  
# Display this page in the Featured widget?
featured: false

# Custom links
links:
  - type: pdf
    url: "../uploads/theses/81151-pedro-silva_phd-thesis.pdf"
  - type: code
    url: "https://github.com/pmorvalho/MENTOR"
  - name: IST
    url: "https://scholar.tecnico.ulisboa.pt/records/-46XUfm_Dnqujesg0AlTNUPh7pZZIs55KWI0"
  - type: project
    url: "projects/mentor"
#   - type: video
#     url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IST**](https://tecnico.ulisboa.pt)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - mentor

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
