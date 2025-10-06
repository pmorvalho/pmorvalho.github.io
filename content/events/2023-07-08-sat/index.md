---
title: "UpMax: User partitioning for MaxSAT"

event: In the *26th International Conference on Theory and Applications of Satisfiability Testing, SAT 2023*.
event_url: https://satisfiability.org/SAT23

location: SAT 2023
address: 
  street: Palazzo del Pou Salit
  city: Alghero
  region: Sardinia, Italy.
  postcode: ''
  country: ''

summary: In this talk I will present a new framework called UpMax that decouples the partitioning procedure from the MaxSAT solving algorithms.

abstract: It has been shown that Maximum Satisfiability (MaxSAT) problem instances can be effectively solved by partitioning the set of soft clauses into several disjoint sets. The partitioning methods can be based on clause weights (e.g., stratification) or based on graph representations of the formula. Afterwards, a merge procedure is applied to guarantee that an optimal solution is found. In this talk, This paper proposeswe propose a new framework called UpMax that decouples the partitioning procedure from the MaxSAT solving algorithms. As a result, new partitioning procedures can be defined independently of the MaxSAT algorithm to be used. Moreover, this decoupling also allows users that build new MaxSAT formulas to propose partition schemes based on knowledge of the problem to be solved. We illustrate this approach using several problems and show that partitioning has a large impact on the performance of unsatisfiability-based MaxSAT algorithms.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-07-08T10:00:00Z'
date_end: '2023-07-08T10:20:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: ["Maximum Satisfiability", "User-based Partitioning", "Formal Methods", "Artificial Intelligence"]
  
# Is this a featured talk? (true/false)
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**SAT**](https://satisfiability.org/SAT23)'
  focal_point: ''
  preview_only: false

links:
   - type: slides
     url: "../uploads/slides/slides-2023-07-08-sat.pdf"
   - name: paper
     url: publications/sat2023
   - name: project
     url: projects/upmax
     

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
- upmax

# > [!NOTE]
# > Click on the **Slides** button above to view the built-in slides feature.

---


