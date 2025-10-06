---
title: Counterexample Guided Program Repair Using Zero-Shot Learning and MaxSAT-based Fault Localization

event: OutSystems AI Reading Group
event_url: https://www.outsystems.com/ai

location: OutSystems
address:
  street: OutSystems AI Reading Group Meetings
  city: 
  region: Online.
  postcode: ''
  country: ''

summary: In this talk I will present our novel approach that combines the strengths of both FM-based fault localization and LLMs, via zero-shot learning, to enhance Automated Program Repair.

abstract: Automated Program Repair (APR) for introductory programming assignments (IPAs) is motivated by the large number of student enrollments in programming courses each year. Since providing feedback on programming assignments requires substantial time and effort from faculty, personalized automated feedback often involves suggesting repairs to students’ programs. Symbolic semantic repair approaches, which rely on Formal Methods (FM), check a program’s execution against a test suite or reference solution, are effective but limited. These tools excel at identifying buggy parts but can only fix programs if the correct implementation and the faulty one share the same control flow graph. Conversely, Large Language Models (LLMs) are used for program repair but often make extensive rewrites instead of minimal adjustments. This tends to lead to more invasive fixes, making it harder for students to learn from their mistakes. In summary, LLMs excel at completing strings, while FM-based fault localization excel at identifying buggy parts of a program. In this talk, I propose a novel approach that combines the strengths of both FM-based fault localization and LLMs, via zero-shot learning, to enhance APR for IPAs. Our method uses MaxSAT-based fault localization to identify buggy parts of a program, then presents the LLM with a program sketch devoid of these buggy statements. This hybrid approach follows a Counterexample Guided Inductive Synthesis (CEGIS) loop to iteratively refine the program. We ask the LLM to synthesize the missing parts, which are then checked against a test suite. If the suggested program is incorrect, a counterexample from the test suite is fed back to the LLM for revised synthesis. Our experiments on 1,431 incorrect student programs show that our counterexample guided approach, using MaxSAT-based bug-free program sketches, significantly improves the repair capabilities of all six evaluated LLMs. This method allows LLMs to repair more programs and produce smaller fixes, outperforming other configurations and state-of-the-art symbolic program repair tools.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-03-21T12:00:00Z'
date_end: '2025-03-21T13:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: [LLM-Based Program Repair, Automated Program Repair, Fault Localisation, Maximum Satisfiability, Large Language Models, Model-Based Diagnosis, AI4SE]

# Is this a featured talk? (true/false)
featured: true

# image:
#    caption: 'Image credit: [**IIIA**](https://dei.tecnico.ulisboa.pt/en/events/dei-wed/wednesdaysdei-talks-10-09-2025)'
#   focal_point: Right

links:
#   - type: code
#     url: https://github.com
   - type: slides
     url: "../uploads/slides/slides-2025-03-21-outsystems.pdf"
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


