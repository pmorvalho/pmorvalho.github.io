---
title: "MultIPAs: Applying Program Transformations to Introductory Programming Assignments for Data Augmentation"

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

date: '2022-11-14T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-14T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the 30th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE) **[CORE A\* Conference]**.
publication_short: In **ESEC/FSE 2022**

abstract: There has been a growing interest, over the last few years, in the topic of automated program repair applied to fixing introductory programming assignments (IPAs). However, the datasets of IPAs publicly available tend to be small and with no valuable annotations about the defects of each program. Small datasets are not very useful for program repair tools that rely on machine learning models. Furthermore, a large diversity of correct implementations allows computing a smaller set of repairs to fix a given incorrect program rather than always using the same set of correct implementations for a given IPA. For these reasons, there has been an increasing demand for the task of augmenting IPAs benchmarks. This paper presents MultIPAs, a program transformation tool that can augment IPAs benchmarks by (1) applying six syntactic mutations that conserve the program's semantics and (2) applying three semantic mutilations that introduce faults in the IPAs. Moreover, we demonstrate the usefulness of MultIPAs by augmenting with millions of programs two publicly available benchmarks of programs written in the C language, and also by generating an extensive benchmark of semantically incorrect programs. 

# Summary. An optional shortened abstract.
summary: This paper presents MultIPAs, a program transformation tool that can augment IPAs benchmarks by (1) applying six syntactic mutations that conserve the program's semantics and (2) applying three semantic mutilations that introduce faults in the IPAs.

tags:
  - Automated Program Repair
  - Program Transformation
  - Data Augmentation
  - Program Analysis
  - Software Engineering
  - MENTOR
  
# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3540250.3558931

# Custom links
links:
  - type: pdf
    url: "../uploads/papers/fse22-MultIPAs.pdf"
  - type: code  
    url: https://github.com/pmorvalho/MultIPAs
  - name: project
    url: projects/mentor
#   - type: video
#     url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**ESEC/FSE**](https://2022.esec-fse.org)'
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
