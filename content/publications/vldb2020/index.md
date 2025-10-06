---
title: "SQUARES: A SQL Synthesizer Using Query Reverse Engineering"

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

date: '2020-08-31T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-09-03T06:30:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *46th International Conference on Very Large Data Bases* **[CORE A\* Conference]**.
publication_short: In **VLDB 2020**

abstract: Nowadays, many data analysts are domain experts, but they lack programming skills. As a result, many of them can provide examples of data transformations but are unable to produce the desired query. Hence, there is an increasing need for systems capable of solving the problem of Query Reverse Engineering (QRE). Given a database and output table, these systems have to find the query that generated this table. We present SQUARES, a program synthesis tool based on input-output examples that can help data analysts to extract and transform data by synthesizing SQL queries, and table manipulation programs using the R language.

# Summary. An optional shortened abstract.
summary: In this paper, we present SQUARES, an open-source tool that generates SQL and R queries from specifications. The specifications are expressed with input-output tables and some optional hints provided by the user. SQUARES is grounded on constraint programming techniques.

tags:
  - Program Synthesis
  - Query Reverse Engineering
  - Enumerative Search
  - SQL
  - R
  - Databases
  - Automated Reasoning
  - Formal Methods  
  - Artificial Intelligence
  - SQUARES

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.14778/3415478.3415492

# Custom links
links:
  - type: pdf
    url: "../uploads/papers/vldb20-squares.pdf"
  - type: code  
    url: https://github.com/squares-sql/SQUARES
  - type: site
    url: https://squares-sql.github.io
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
  caption: 'Image credit: [**VLDB**](https://vldb2020.org)'
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
