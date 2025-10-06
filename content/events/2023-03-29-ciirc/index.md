---
title: "Learning Variable Mappings to Repair and Verify Programs"

event: AI&Reasoning Project Seminars
event_url: https://www.ciirc.cvut.cz/research-education/projects/ai-reasoning

location: Formal Methods Group, CIIRC
address: 
  street: Czech Institute of Informatics, Robotics and Cybernetics (CIIRC), CTU in Prague
  city: Prague
  region: Czechia
  postcode: ''
  country: ''

summary: In this talk I will propose using graph neural networks (GNNs) to map the set of variables between two programs based on both programs' abstract syntax trees (ASTs).

abstract: Automated program analysis is a pivotal research domain in many areas of Computer Science -- Formal Methods and Artificial Intelligence, in particular. Due to the undecidability of the problem of program equivalence, comparing two programs is highly challenging. Typically, in order to compare two programs, a relation between both programs' sets of variables is required. Thus, mapping variables between two programs is useful for a panoply of tasks such as program equivalence, program analysis, program repair, and clone detection. In this talk, I propose using graph neural networks (GNNs) to map the set of variables between two programs based on both programs' abstract syntax trees (ASTs). To demonstrate the strength of variable mappings, we present three use-cases of these mappings on the task of program repair to fix well-studied and recurrent bugs among novice programmers in introductory programming assignments (IPAs). Experimental results on a dataset of 4166 pairs of incorrect/correct programs show that our approach correctly maps 83% of the evaluation dataset. Moreover, our experiments show that the current state-of-the-art on program repair, greatly dependent on the programs' structure, can only repair about 72% of the incorrect programs. In contrast, our approach, which is solely based on variable mappings, can repair around 88.5%. Furthermore, I discuss future directions of using these variable mappings to verify programs using bounded model-checking.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-03-29T14:00:00Z'
date_end: '2023-03-29T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: ["Variable Alignment", "Graph Neural Networks", "Program Analysis", "Automated Program Repair", "Artificial Intelligence"]

  
# Is this a featured talk? (true/false)
featured: true

links:
   - type: slides
     url: "../uploads/slides/slides-2023-03-29-ciirc.pdf"
   - name: paper
     url: publications/ecai2023
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


