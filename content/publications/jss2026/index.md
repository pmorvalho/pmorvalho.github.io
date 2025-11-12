---
title: "MENTOR: Fixing Introductory Programming Assignments With Formula-Based Fault Localization and LLM-Driven Program Repair"
authors:
- admin
- Mikoláš Janota
- Vasco Manquinho

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2026-02-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-11-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In the *Journal of Systems and Software (JSS) 2026* **[SJR Q1 Journal]**.
publication_short: "In **JSS 2026**"

abstract: The increasing demand for programming education has led to online evaluations like MOOCs, which rely on introductory programming assignments (IPAs). A major challenge in these courses is providing personalized feedback at scale. This paper introduces MENTOR, a semantic automated program repair (APR) framework designed to fix faulty student programs. MENTOR validates repairs through execution on a test suite, and returns the repaired program or highlights faulty statements. Unlike symbolic repair tools like Clara and Verifix, which require correct implementations with identical control flow graphs (CFGs), MENTOR’s LLM-based approach enables flexible repairs without strict structural alignment. MENTOR clusters successful submissions regardless of CFGs, and employs a Graph Neural Network (GNN)-based variable alignment module for enhanced accuracy. Next, MENTOR’s fault localization module leverages MaxSAT techniques to pinpoint buggy code segments precisely. Finally, MENTOR’s program fixer integrates Formal Methods (FM) and Large Language Models (LLMs) through a Counterexample Guided Inductive Synthesis (CEGIS) loop, iteratively refining repairs. Experimental results show that MENTOR significantly improves repair success rates, achieving 64.4%, far surpassing Verifix (6.3%) and Clara (34.6%). By merging formula-based fault localization, and LLM-driven repair, MENTOR provides an innovative, scalable framework for programming education.

# Summary. An optional shortened abstract.
summary: This paper introduces MENTOR, a semantic automated program repair (APR) framework designed to fix faulty student programs. MENTOR validates repairs through execution on a test suite, and returns the repaired program or highlights faulty statements.

tags:
- Automated Program Repair
- Program Analysis
- Formula-based Fault Localization
- LLM-Driven Program Repair
- Computer-Aided Education
- Programming Education
- MENTOR
- CFaults
- GitSEED
- InvAASTCluster

  
featured: true

hugoblox:
  ids:
    doi: 10.1016/j.jss.2025.112690

links:
  - type: pdf
    url: "../uploads/papers/jss26-MENTOR.pdf"
  - type: code
    url: https://github.com/pmorvalho/MENTOR
  - type: dataset
    url: "https://github.com/pmorvalho/C-Pack-IPAs"
  - type: project
    url: "projects/mentor"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**JSS**](https://www.sciencedirect.com/journal/journal-of-systems-and-software)'
  focal_point: ""
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

<!--more-->

