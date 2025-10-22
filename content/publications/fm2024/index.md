---
title: "CFaults: Model-Based Diagnosis for Fault Localization in C with Multiple Test Cases"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Mikoláš Janota
- Vasco Manquinho

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-09-11T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-11T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the *26th international symposium on Formal Method (FM 2024)* **[CORE A Conference]**.
publication: 
publication_short: In **FM 2024**


abstract: Debugging is one of the most time-consuming and expensive tasks in software development. Several formula-based fault localization (FBFL) methods have been proposed, but they fail to guarantee a set of diagnoses across all failing tests or may produce redundant diagnoses that are not subset-minimal, particularly for programs with multiple faults. This paper introduces, [CFaults](/projects/cfaults), a novel fault localization approach for C programs with multiple faults. CFaults leverages Model-Based Diagnosis (MBD) with multiple observations and aggregates all failing test cases into a unified MaxSAT formula. Consequently, our method guarantees consistency across observations and simplifies the fault localization procedure. Experimental results on two benchmark sets of C programs, TCAS and C-Pack-IPAs, show that CFaults is faster than other FBFL approaches like BugAssist and SNIPER. Moreover, CFaults only generates subset-minimal diagnoses of faulty statements, whereas the other approaches tend to enumerate redundant diagnoses.

# Summary. An optional shortened abstract.
summary: This paper introduces a novel fault localization approach for C programs with multiple faults. CFaults leverages Model-Based Diagnosis (MBD) with multiple observations and aggregates all failing test cases into a unified MaxSAT formula. Consequently, our method guarantees consistency across observations and simplifies the fault localization procedure.

tags:
  - Automated Verification
  - Model-Based Diagnosis
  - Fault Localisation
  - Formal Methods  
  - Artificial Intelligence
  - CFaults  

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1609/aaai.v39i1.32046
    arxiv: 2502.07786

# Custom links
links:
  - type: pdf
    url: "../uploads/papers/fm24-paper.pdf"
  - type: code  
    url: https://github.com/pmorvalho/CFaults
  - name: Zenodo
    url: https://doi.org/10.5281/zenodo.12510220
  - name: project
    url: projects/cfaults
#   - name: arXiv (Extended)
#     url: http://arxiv.org/abs/
  - type: poster
    url: "../uploads/posters/poster-fm24.pdf"
#   - type: slides
#     url: https://www.slideshare.net/
#   - type: source
#     url: https://github.com/HugoBlox/hugo-blox-builder
#   - type: video
#     url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**FM**](https://www.fm24.polimi.it)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - cfaults

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
