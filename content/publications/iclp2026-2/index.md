---
title: "What Bugs Do Prolog Students Write? An Empirical Taxonomy and Data-Driven Mutation Framework"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Ricardo Brancas
- admin
- Carolina Carreira
- Vasco Manquinho
- Ruben Martins

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-05-05T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-05-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the *42nd International Conference on Logic Programming (ICLP)* **[CORE B Conference]**. _[Accepted for Publication]_
publication_short: In **ICLP 2026**

abstract: Automated feedback tools for logic programming education depend on realistic bug datasets that reflect the mistakes students actually make. However, existing mutation testing frameworks for Prolog treat all mutations as equally likely, producing synthetic faults that diverge from classroom reality. We present an empirical study of 7,201 Prolog submissions from 265 undergraduate students, from which we derive a fine-grained taxonomy of student bugs through manual classification of 200 bug-fixing submissions. Guided by this taxonomy, we develop LogMorph, a data-driven mutation tool whose 17 operators are weighted according to the observed error distribution. LogMorph enumerates valid mutation sites on the abstract syntax tree, samples operators proportionally, injects faults, delegating to an SMT-based synthesizer when new code fragments are needed, and validates each mutant against a reference test suite. An evaluation of 16,000 generated mutants shows that the synthetic error distribution closely matches the student distribution, with most bug categories agreeing to within two percentage points. We identify cut-related mutations and synthesizer-generated code as the main sources of residual divergence, and outline how combining the SMT back-end with a language model fine-tuned on student code can further improve realism.

# Summary. An optional shortened abstract.
summary: In this work, we present an empirical study of 7,201 Prolog submissions from 265 undergraduate students, from which we derive a fine-grained taxonomy of student bugs through manual classification of 200 bug-fixing submissions. Guided by this taxonomy, we develop LogMorph, a data-driven mutation tool whose 17 operators are weighted according to the observed error distribution.

tags:
 - Logic Programming
 - Prolog
 - Computer Science Education
 - Computer-aided Education
 - Mutation Testing
 - Benchmark
  
# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    # doi: 10.48550/arXiv.2504.16742
    # arxiv: 2504.16742

# Custom links
links:
  - name: project
    url: projects/ai4cseducation
  #- type: pdf
  #  url: "../uploads/papers/iclp26-LogMorph.pdf"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**ICLP**](https://www.semsys.aau.at/events/iclp2026/)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - ai4cseducation

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
