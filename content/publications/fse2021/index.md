---
title: "AlloyMax: Bringing Maximum Satisfaction to Relational Specifications"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Changjian Zhang
- Ryan Wagner
- admin
- David Garlan
- Ruben Martins
- Vasco Manquinho
- Eunsuk Kang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-08-17T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-08-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the 29th ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE) **[CORE A\* Conference]**.
publication_short: In **ESEC/FSE 2021. 🏆🏆 ACM SIGSOFT Distinguished Paper Award 🏆🏆**

abstract: Alloy is a declarative modeling language based on a first-order relational logic. Its constraint-based analysis has enabled a wide range of applications in software engineering, including configuration synthesis, bug finding, test-case generation, and security analysis. Certain types of analysis tasks in these domains involve finding an optimal solution. For example, in a network configuration problem, instead of finding any valid configuration, it may be desirable to find one that is most permissive (i.e., it permits a maximum number of packets). Due to its dependence on SAT, however, Alloy cannot be used to specify and analyze these types of problems. We propose AlloyMax, an extension of Alloy with a capability to express and analyze problems with optimal solutions. AlloyMax introduces (1) a small addition of language constructs that can be used to specify a wide range of problems that involve optimality and (2) a new analysis engine that leverages a Maximum Satisfiability (MaxSAT) solver to generate optimal solutions. To enable this new type of analysis, we show how a specification in a first-order relational logic can be translated into an input format of MaxSAT solvers—namely, a Boolean formula in weighted conjunctive normal form (WCNF). We demonstrate the applicability and scalability of AlloyMax on a benchmark of problems. To our knowledge, AlloyMax is the first approach to enable analysis with optimality in a relational modeling language, and we believe that AlloyMax has the potential to bring a wide range of new applications to Alloy.

# Summary. An optional shortened abstract.
summary: We propose AlloyMax, an extension of Alloy with a capability to express and analyze problems with optimal solutions. AlloyMax introduces (1) a small addition of language constructs that can be used to specify a wide range of problems that involve optimality and (2) a new analysis engine that leverages a Maximum Satisfiability (MaxSAT) solver to generate optimal solutions.

tags:
  - Maximum Satisfiability
  - Alloy
  - Formal Methods  
  - Artificial Intelligence
  - Software Engineering
  - UpMax  

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3468264.3468587

# Custom links
links:
  - type: pdf
    url: "../uploads/papers/fse21-alloymax.pdf"
  - type: code  
    url: https://github.com/SteveZhangBit/alloy-maxsat-benchmark
  - name: project
    url: projects/upmax

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - upmax

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
