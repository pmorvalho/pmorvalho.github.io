---
title: "CFaults: Model-Based Diagnosis for Fault Localization in C with Multiple Test Cases"

event: The 26th International Symposium on Formal Methods, FM 2024
event_url: https://www.fm24.polimi.it

location: Politecnico di Milano
address: 
  street: Politecnico di Milano
  city: Milan
  region: Italy
  postcode: ''
  country: ''

summary: In this talk I will introduce a novel fault localization approach for C programs with multiple faults. CFaults leverages Model-Based Diagnosis (MBD) with multiple observations and aggregates all failing test cases into a unified MaxSAT formula.

abstract: Debugging is one of the most time-consuming and expensive tasks in software development. Several formula-based fault localization (FBFL) methods have been proposed, but they fail to guarantee a set of diagnoses across all failing tests or may produce redundant diagnoses that are not subset-minimal, particularly for programs with multiple faults. In this talk I will introduce a novel fault localization approach for C programs with multiple faults. CFaults leverages Model-Based Diagnosis (MBD) with multiple observations and aggregates all failing test cases into a unified MaxSAT formula. Consequently, our method guarantees consistency across observations and simplifies the fault localization procedure. Experimental results on two benchmark sets of C programs, TCAS and C-Pack-IPAs, show that CFaults is faster than other FBFL approaches like BugAssist and SNIPER. Moreover, CFaults only generates subset-minimal diagnoses of faulty statements, whereas the other approaches tend to enumerate redundant diagnoses.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-09-12T11:50:00Z'
date_end: '2024-09-12T12:10:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: [Formal Methods, Automated Verification, Model-Based Diagnosis, Fault Localisation, Artificial Intelligence]
  
# Is this a featured talk? (true/false)
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**FM**](https://www.fm24.polimi.it)'
  focal_point: ''
  preview_only: false


links:
   - type: slides
     url: "../uploads/slides/slides-2024-09-12-fm.pdf"
   - name: project
     url: projects/cfaults
   - name: paper
     url: publications/fm2024     

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
- cfaults

# > [!NOTE]
# > Click on the **Slides** button above to view the built-in slides feature.

---


