---
title: "Encodings for Enumeration-Based Program Synthesis"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Miguel Terra-Neves
- Miguel Ventura
- Ruben Martins
- Vasco Manquinho

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2019-09-23T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-09-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the *25th International Conference Principles and Practice of Constraint Programming (CP 2019)*, **[CORE A Conference]**.
publication_short: In **CP 2019**

abstract: Program synthesis is the problem of finding a program that satisfies a given specification. Most program synthesizers are based on enumerating program candidates that satisfy the specification. Recently, several new tools for program synthesis have been proposed where Satisfiability Modulo Theories (SMT) solvers are used to prune the search space by discarding programs that do not satisfy the specification. The size of current tree-based SMT encodings for program synthesis grows exponentially with the size of the program. In this paper, a new compact line-based encoding is proposed that allows a faster enumeration of the program space. Experimental results on a large set of query synthesis problem instances show that using the new encoding results in a more effective tool that is able to synthesize larger programs.

# Summary. An optional shortened abstract.
summary: In this paper, a new compact line-based encoding is proposed that allows a faster enumeration of the program space.

tags:
  - Program Synthesis
  - Query Reverse Engineering
  - Enumerative Search
  - SQL
  - R
  - Automated Reasoning
  - Formal Methods  
  - Artificial Intelligence
  - SQUARES

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1007/978-3-030-30048-7_34

# Custom links
links:
  - type: pdf
    url: "../uploads/papers/Orvalho2019_EncodingsForEnumeration-BasedPS.pdf"
  - type: code  
    url: https://github.com/squares-sql/SQUARES
  - name: project
    url: projects/squares
#   - type: slides
#     url: https://www.slideshare.net/
#   - type: source
#     url: https://github.com/HugoBlox/hugo-blox-builder
#   - type: video
#     url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**CP**](https://cp2019.a4cp.org/index.html)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - squares

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
