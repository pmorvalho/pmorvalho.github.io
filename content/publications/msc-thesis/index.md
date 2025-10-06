---
title: "SQUARES: A SQL Synthesizer Using Query Reverse Engineering"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2019-11-15T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-11-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['thesis']

# Publication name and optional abbreviated publication name.
publication: Thesis to obtain the Master of Science Degree in Information Systems and Computer Engineering @ IST, Universidade de Lisboa. 🏆🏆 **Grade 20/20** 🏆🏆
publication_short:  MSc Thesis
# 🏆🏆 **Grade 20/20** 🏆🏆

abstract: Nowadays, with the massive amount of data that data analysts have to deal with, they frequently find tables with interesting data and they do not know how these tables were generated from a database. Hence, there is an increasing need for systems capable of solving the problem of Query Reverse Engi- neering (QRE). Given a database D and an output table Q(D), these systems have to find a query Q, such that, when running Q on D, the result is equal to Q(D). QRE is a subfield of Program Synthesis. The goal of Program Synthesis is to automatically generate programs that satisfy a given high-level specification. Since the 60’s, Program Synthesis is a well-studied problem, and has been considered the Holy Grail of Computer Science. Until now, program synthesizers have been using a single tree representation to represent programs. We propose a novel enumeration-based SQL synthesizer SQUARES, that uses a new line representation where we represent each program line with its own subtree. Experimental results on the synthesis of SQL queries, show that the proposed line-based encoding allows a faster enumeration of programs when compared to the usual tree-based encoding. Moreover, while the tree-based encoding does not scale beyond a small number of operations, the new line-based encoding allows finding programs with a larger sequence of operations. Experimental results on the synthesis of SQL queries from OutSystems show that SQUARES outperforms Scythe, a state-of-the-art SQL synthesizer.

# Summary. An optional shortened abstract.
summary: MSc Thesis. We propose a novel Enumeration-Based SQL synthesizer SQUARES, that uses a new line representation where we represent each program line with its own subtree.

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

# Custom links
links:
  - type: pdf
    url: "../uploads/theses/81151-pedro-silva_dissertacao.pdf"
  - type: code  
    url: https://github.com/squares-sql/SQUARES
  - type: site
    url: https://squares-sql.github.io
  - name: IST
    url: https://scholar.tecnico.ulisboa.pt/records/go8T09DX3b5Qt9KsfIZqdqN8tAMkl5gdyarE  
  - type: project
    url: projects/squares
#   - type: video
#     url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IST**](https://tecnico.ulisboa.pt)'
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
