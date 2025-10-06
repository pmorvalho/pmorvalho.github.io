---
title: "SQUARES: A SQL Synthesizer Using Query Reverse Engineering"

event: In *46th International Conference on Very Large Data Bases*, VLDB 2020
event_url: https://vldb2020.org

location: VLDB 2020
address: 
  street: Tokyo
  city: Japan
  region: (Online).
  postcode: ''
  country: ''

summary: In this talk I present SQUARES, an open-source tool that generates SQL and R queries from specifications. The specifications are expressed with input-output tables and some optional hints provided by the user. SQUARES is grounded on constraint programming techniques.

abstract: Nowadays, many data analysts are domain experts, but they lack programming skills. As a result, many of them can provide examples of data transformations but are unable to produce the desired query. Hence, there is an increasing need for systems capable of solving the problem of Query Reverse Engineering (QRE). Given a database and output table, these systems have to find the query that generated this table. We present SQUARES, a program synthesis tool based on input-output examples that can help data analysts to extract and transform data by synthesizing SQL queries, and table manipulation programs using the R language.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2020-09-03T06:30:00Z'
date_end: '2020-09-03T06:50:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: ["Program Synthesis", "Query Reverse Engineering", "Enumerative Search", "SQL", "R", "Databases", "Automated Reasoning", "Formal Methods", "Artificial Intelligence"]


# Is this a featured talk? (true/false)
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**VLDB**](https://vldb2020.org)'
  focal_point: ''
  preview_only: false

links:
   - name: paper
     url: publications/vldb2020
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


