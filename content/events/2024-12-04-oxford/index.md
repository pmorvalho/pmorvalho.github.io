---
title: LLM-Driven Automated Program Repair Using MaxSAT-based Fault Localization

event: QAVAS Meeting, University of Oxford
event_url: 

location: Department of Computer Science, University of Oxford
address:
  street: Wolfson Building, Parks Rd
  city: Oxford
  region: UK. (Online)
  postcode: ''
  country: 'UK'

summary: In this talk I will present a hybrid method to automated repair of C code, using Maximum Satisfiability (MaxSAT)-based fault localization, CFaults, to localize bugs and LLMs to replace the faulty code via a counterexample-guided loop.

abstract: Debugging and repair are costly in both software development and programming education. In this talk I will present two approaches that combine formal methods with large language models (LLMs) to improve accuracy and scalability. First, we introduce CFaults, a MaxSAT-based fault localization tool for C programs that ensures consistent, subset-minimal diagnoses across multiple failing tests. It outperforms existing tools like BugAssist and SNIPER in speed and precision. Second, we apply a hybrid method to automated repair of C code, using MaxSAT, CFaults, to localize bugs and LLMs to replace the faulty code via a counterexample-guided loop. This approach produces more targeted and effective repairs than existing symbolic or LLM-only methods, improving outcomes across over 1,400 incorrect student submissions. Together, these methods show how combining formal reasoning with generative models enables more efficient and precise debugging and repair.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-12-04T09:00:00Z'
date_end: '2024-12-04T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: [LLM-Based Program Repair, Automated Program Repair, Fault Localisation, Maximum Satisfiability, Large Language Models, Model-Based Diagnosis, AI4SE]

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**IIIA**](https://dei.tecnico.ulisboa.pt/en/events/dei-wed/wednesdaysdei-talks-10-09-2025)'
#   focal_point: Right

links:
#   - type: code
#     url: https://github.com
   - type: slides
     url: "../uploads/slides/slides-2024-12-04-oxford.pdf"
   - name: project
     url: projects/mentor     
   - name: paper
     url: publications/aaai2025     
#    - type: video
#      url: https://www.iiia.csic.es/media/filer_public/aa/eb/aaeb9a2f-e77c-40c9-92d5-2c870da1de59/250623-seminari-pedroorvalho.mp4

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
 - cfaults
 - ai4code

# > [!NOTE]
# > Click on the **Slides** button above to view the built-in slides feature.

---


