---
title: "Encodings for Enumeration-Based Program Synthesis"

event: In the *25th International Conference Principles and Practice of Constraint Programming*, CP 2019
event_url: https://cp2019.a4cp.org

location: CP 2019
address: 
  street: UConn Stamford
  city: Stamford
  region: USA.
  postcode: ''
  country: ''

summary: In this talk I will present a new compact line-based encoding is proposed that allows a faster enumeration of the program space.

abstract: Program synthesis is the problem of finding a program that satisfies a given specification. Most program synthesizers are based on enumerating program candidates that satisfy the specification. Recently, several new tools for program synthesis have been proposed where Satisfiability Modulo Theories (SMT) solvers are used to prune the search space by discarding programs that do not satisfy the specification. The size of current tree-based SMT encodings for program synthesis grows exponentially with the size of the program. In this talk, I propose a new compact line-based encoding is proposed that allows a faster enumeration of the program space. Experimental results on a large set of query synthesis problem instances show that using the new encoding results in a more effective tool that is able to synthesize larger programs.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2019-10-02T13:30:00Z'
date_end: '2019-10-02T14:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: ["Program Synthesis", "Query Reverse Engineering", "Enumerative Search", "SQL", "Databases", "Automated Reasoning", "Formal Methods", "Artificial Intelligence"]


# Is this a featured talk? (true/false)
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**CP**](https://cp2019.a4cp.org/index.html)'
  focal_point: ''
  preview_only: false

links:
   - name: paper
     url: publications/cp2019
   - name: project
     url: projects/squares
     

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
- squares

# > [!NOTE]
# > Click on the **Slides** button above to view the built-in slides feature.

---


