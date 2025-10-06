---
title: "InvAASTCluster: On Applying Invariant-Based Program Clustering to Introductory Programming Assignments"
authors:
- admin
- Mikoláš Janota
- Vasco Manquinho

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2025-06-27T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In the *Journal of Systems and Software (JSS) 2025* **[SJR Q1 Journal]**.
publication_short: "In **JSS 2025**"

abstract: Due to the vast number of students enrolled in programming courses, there has been an increasing number of automated program repair techniques focused on introductory programming assignments (IPAs). Typically, such techniques use program clustering to take advantage of previous correct student implementations to repair a new incorrect submission. These repair techniques use clustering methods since analyzing all available correct submissions to repair a program is not feasible. However, conventional clustering methods rely on program representations based on features such as abstract syntax trees (ASTs), syntax, control flow, and data flow. This paper proposes InvAASTCluster, a novel approach for program clustering that uses dynamically generated program invariants to cluster semantically equivalent IPAs. InvAASTCluster's program representation uses a combination of the program's semantics, through its invariants, and its structure through its anonymized abstract syntax tree (AASTs). Invariants denote conditions that must remain true during program execution, while AASTs are ASTs devoid of variable and function names, retaining only their types. Our experiments show that the proposed program representation outperforms syntax-based representations when clustering a set of correct IPAs. Furthermore, we integrate InvAASTCluster into a state-of-the-art clustering-based program repair tool. Our results show that InvAASTCluster advances the current state-of-the-art when used by clustering-based repair tools by repairing around 13% more students' programs, in a shorter amount of time.

# Summary. An optional shortened abstract.
summary: This paper proposes InvAASTCluster, a novel approach for program clustering that uses dynamically generated program invariants to cluster semantically equivalent IPAs.

tags:
- Program Clustering
- Program Invariants
- Program Equivalence
- Automated Program Repair
- Programming Education
- InvAASTCluster
- MENTOR
  
featured: true

hugoblox:
  ids:
    arxiv: 2206.14175
    doi: 10.1016/j.jss.2025.112481

links:
  - type: pdf
    url: "../uploads/papers/jss25-InvAASTCluster.pdf"
  - type: code
    url: https://github.com/pmorvalho/InvAASTCluster
  - type: dataset
    url: "https://github.com/pmorvalho/C-Pack-IPAs"
#    - type: poster
#      url: ""
  - type: project
    url: "projects/mentor"
#    - type: slides
#     url: https://www.slideshare.net/
#    - type: source
#      url: ""
#    - type: video
#      url: ""

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
