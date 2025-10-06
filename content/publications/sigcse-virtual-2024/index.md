---
title: "GitSEED: A Git-backed Automated Assessment Tool for Software Engineering and Programming Education"

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

date: '2024-12-05T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-05T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the *1st ACM Virtual Global Computing Education Conference (SIGCSE Virtual 2024)*.
publication_short: In **SIGCSE Virtual 2024**

abstract: Due to the substantial number of enrollments in programming courses, a key challenge is delivering personalized feedback to students. The nature of this feedback varies significantly, contingent on the subject and the chosen evaluation method. However, tailoring current Automated Assessment Tools (AATs) to integrate other program analysis tools is not straightforward. Moreover, AATs usually support only specific programming languages, providing feedback exclusively through dedicated websites based on test suites. This paper introduces [GitSEED]("projects/gitseed"), a language-agnostic automated assessment tool designed for Programming Education and Software Engineering (SE) and backed by GitLab. The students interact with GitSEED through GitLab. Using GitSEED, students in Computer Science (CS) and SE can master the fundamentals of git while receiving personalized feedback on their programming assignments and projects. Furthermore, faculty members can easily tailor GitSEED's pipeline by integrating various code evaluation tools (e.g., memory leak detection, fault localization, program repair, etc.) to offer personalized feedback that aligns with the needs of each CS/SE course. Our experiments assess GitSEED's efficacy via comprehensive user evaluation, examining the impact of feedback mechanisms and features on student learning outcomes. Findings reveal positive correlations between GitSEED usage and student engagement.

# Summary. An optional shortened abstract.
summary: This paper introduces GitSEED, a language-agnostic automated assessment tool designed for Programming Education and Software Engineering (SE) and backed by GitLab.

tags:
  - Computer-Aided Education
  - Programming Education
  - Software Engineering Education
  - GitSEED

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3649165.3690106
    arxiv: 2409.07362

# Custom links
links:
  - type: pdf
    url: "../uploads/papers/sigcse-virtual-24-paper.pdf"
  - type: code  
    url: https://gitlab.inesc-id.pt/u020557/GitSEED
  - name: Zenodo
    url: https://doi.org/10.5281/zenodo.13741158
  - name: project
    url: projects/gitseed

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**SIGCSE**](https://sigcsevirtual2026.acm.org)'
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
