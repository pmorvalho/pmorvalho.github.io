---
title: "Anonymized Abstract Syntax Trees and Invariant-Based Program Clustering"

event: AI&Reasoning Project Seminars
event_url: https://www.ciirc.cvut.cz/research-education/projects/ai-reasoning

location: Automated Reasoning Group, CIIRC
address: 
  street: Czech Institute of Informatics, Robotics and Cybernetics (CIIRC), CTU in Prague
  city: Prague
  region: Czechia
  postcode: ''
  country: ''

summary: In this talk I propose a novel approach for program clustering that uses dynamically generated program invariants to cluster semantically equivalent programming assignments.

abstract: Due to the vast number of students enrolled in programming courses, there has been an increasing number of automated program repair techniques focused on introductory programming assignments (IPAs). Typically, such techniques use program clustering to take advantage of previous correct student implementations to repair a new incorrect submission. These repair techniques use clustering methods since analyzing all available correct submissions to repair a program is not feasible. However, conventional clustering methods rely on program representations based on features such as abstract syntax trees (ASTs), syntax, control flow, and data flow. In this talk I present InvAASTCluster, a novel approach for program clustering that uses dynamically generated program invariants to cluster semantically equivalent IPAs. InvAASTCluster’s program representation uses a combination of the program’s semantics, through its invariants, and its structure through its anonymized abstract syntax tree (AASTs). Invariants denote conditions that must remain true during program execution, while AASTs are ASTs devoid of variable and function names, retaining only their types. Our experiments show that the proposed program representation outperforms syntax-based representations when clustering a set of correct IPAs. Furthermore, we integrate InvAASTCluster into a state-of-the-art clustering-based program repair tool. Our results show that InvAASTCluster advances the current state-of-the-art when used by clustering-based repair tools by repairing around 13% more students’ programs, in a shorter amount of time.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-03-23T14:00:00Z'
date_end: '2022-03-23T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: ["Program Clustering", "Program Invariants", "Program Equivalence", "Automated Program Repair", "Programming Education"]

  
# Is this a featured talk? (true/false)
featured: true

links:
   - name: project
     url: projects/mentor
     

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
- mentor

# > [!NOTE]
# > Click on the **Slides** button above to view the built-in slides feature.

---


