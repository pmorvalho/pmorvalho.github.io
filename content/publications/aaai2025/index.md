---
title: "Counterexample Guided Program Repair Using Zero-Shot Learning and MaxSAT-based Fault Localization"

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

date: '2025-02-25T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the 39th Annual *AAAI Conference on Artificial Intelligence* (AAAI 2025) **[CORE A\* Conference]**.
publication_short: In **AAAI 2025**

abstract:  Automated Program Repair (APR) for introductory programming assignments (IPAs) is motivated by the large number of student enrollments in programming courses each year. Since providing feedback on programming assignments requires substantial time and effort from faculty, personalized automated feedback often involves suggesting repairs to students' programs. Symbolic semantic repair approaches, which rely on Formal Methods (FM), check a program's  execution against a test suite or reference solution, are effective but limited. These tools excel at identifying buggy parts but can only fix programs if the correct implementation and the faulty one share the same control flow graph. Conversely, Large Language Models (LLMs) are used for program repair but often make extensive rewrites instead of minimal adjustments. This tends to lead to more invasive fixes, making it harder for students to learn from their mistakes. In summary, LLMs excel at completing strings, while FM-based fault localization excel at identifying buggy parts of a program. In this paper, we propose a novel approach that combines the strengths of both FM-based fault localization and LLMs, via zero-shot learning, to enhance APR for IPAs. Our method uses MaxSAT-based fault localization to identify buggy parts of a program, then presents the LLM with a program sketch devoid of these buggy statements. This hybrid approach follows a Counterexample Guided Inductive Synthesis (CEGIS) loop to iteratively refine the program. We ask the LLM to synthesize the missing parts, which are then checked against a test suite. If the suggested program is incorrect, a counterexample from the test suite is fed back to the LLM for revised synthesis. Our experiments on 1,431 incorrect student programs show that our counterexample guided approach, using MaxSAT-based bug-free program sketches, significantly improves the repair capabilities of all six evaluated LLMs. This method allows LLMs to repair more programs and produce smaller fixes, outperforming other configurations and state-of-the-art symbolic program repair tools.

# Summary. An optional shortened abstract.
summary: In this paper, we propose a novel approach that combines the strengths of both FM-based fault localization and LLMs, via zero-shot learning, to enhance APR for IPAs. Our method uses MaxSAT-based fault localization to identify buggy parts of a program, then presents the LLM with a program sketch devoid of these buggy statements. This hybrid approach follows a Counterexample Guided Inductive Synthesis (CEGIS) loop to iteratively refine the program. We ask the LLM to synthesize the missing parts, which are then checked against a test suite. If the suggested program is incorrect, a counterexample from the test suite is fed back to the LLM for revised synthesis.

tags:
  - Large Language Models
  - Automated Program Repair
  - Automated Verification
  - MaxSAT
  - Model-Based Diagnosis
  - Formal Methods  
  - Artificial Intelligence
  - CFaults
  - MENTOR  

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
    url: "../uploads/papers/aaai25-LLM-CEGIS-Repair.pdf"
  - type: code  
    url: https://github.com/pmorvalho/LLM-CEGIS-Repair
  - name: Zenodo
    url: https://doi.org/10.5281/zenodo.14517771  
  - name: project
    url: projects/mentor
#   - name: arXiv (Extended)
#     url: http://arxiv.org/abs/
  - type: poster
    url: "../uploads/posters/poster-aaai25.pdf"
#   - type: slides
#     url: https://www.slideshare.net/
#   - type: source
#     url: https://github.com/HugoBlox/hugo-blox-builder
#   - type: video
#     url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**AAAI**](https://aaai.org/conference/aaai/aaai-25)'
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
