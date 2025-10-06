---
title: "MENTOR: Automated Feedback for Introductory Programming Exercises"

event: DI Seminars
event_url: https://nova-lincs.di.fct.unl.pt/seminars/mentor-automated-feedback-for-introductory-programming-exercises

location: Department of Computer Science, School of Science and Technology, Universidade Nova de Lisboa
address:
  street: DI Seminars Room
  city: Caparica
  region: Portugal.
  postcode: ''
  country: 'Portugal'

summary: In my talk, I will present MENTOR, a semantic automated program repair (APR) framework designed to provide Automated Feedback for Introductory Programming Exercises.

abstract: The increasing demand for programming education has given rise to all kinds of online evaluations such as Massive Open Online Courses (MOOCs) focused on introductory programming assignments (IPAs). As a consequence of a large number of enrolled students, one of the main challenges in these courses is to provide valuable and personalised feedback to students. In my talk, I will present MENTOR, a semantic automated program repair (APR) framework designed to provide Automated Feedback for Introductory Programming Exercises. MENTOR addresses this challenge by generating possible repairs for faulty student programs, enabling semantic repairs validated through execution on a test suite and by highlighting these faulty statements to the students. Hence, in the context of this work, we provide scientific contributions in several areas, such as program clustering and analysis, automated fault localisation and program repair. MENTOR advances the state of the art in the referred areas and provides an innovative practical framework to be deployed in educational environments. Unlike symbolic repair tools like Clara and Verifix, which require correct implementations with identical control flow graphs (CFGs), MENTOR’s Large Language Model (LLM)-based approach enables flexible repairs without strict structural alignment. MENTOR clusters successful submissions regardless of CFGs and employs a Graph Neural Network (GNN)-based variable alignment module for enhanced accuracy. MENTOR’s fault localisation module, CFaults, leverages Maximum Satisfiability (MaxSAT) techniques to pinpoint buggy code segments precisely. MENTOR’s program fixer integrates Formal Methods (FM) and LLMs through a Counterexample Guided Inductive Synthesis (CEGIS) loop, iteratively refining repairs. Furthermore, in my talk I will also present GitSEED, which is a language-agnostic automated assessment tool that enhances student learning by providing personalised feedback on code submissions and successfully integrates CFaults for eﬀective fault detection on student code. Experimental results on C-Pack-IPAs demonstrate that MENTOR significantly improves repair success rates, achieving 64.4%, compared to just 6.3% for Verifix and 34.6% for Clara.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-04-22T14:00:00Z'
date_end: '2025-04-22T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: [LLM-Based Program Repair, Automated Program Repair, Fault Localisation, Maximum Satisfiability, Large Language Models, Model-Based Diagnosis, AI4SE]

# Is this a featured talk? (true/false)
featured: true

# image:
#   caption: 'Image credit: [**IIIA**](https://dei.tecnico.ulisboa.pt/en/events/dei-wed/wednesdaysdei-talks-10-09-2025)'
#   focal_point: Right

links:
#   - type: code
#     url: https://github.com
   - type: slides
     url: "../uploads/slides/slides-2025-04-22-fct-unl.pdf"
   - name: project
     url: projects/mentor
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
 - ai4code

# > [!NOTE]
# > Click on the **Slides** button above to view the built-in slides feature.

---


