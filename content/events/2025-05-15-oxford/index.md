---
title: Are Large Language Models Robust in Understanding Code Against Semantics-Preserving Mutations?

event: QAVAS Group Meeting, University of Oxford
event_url: 

location: Department of Computer Science, University of Oxford
address:
  street: Wolfson Building, Parks Rd
  city: Oxford
  region: UK.
  postcode: ''
  country: 'UK'

summary: In this talk, I will present our evaluation on whether state-of-the-art LLMs with up to 8B parameters can reason about Python programs or are simply guessing.

abstract: Understanding the reasoning and robustness of Large Language Models (LLMs) is critical for their reliable use in programming tasks. While recent studies have assessed LLMs' ability to predict program outputs, most focus solely on the accuracy of those predictions, without evaluating the reasoning behind them. Moreover, it has been observed on mathematical reasoning tasks that LLMs can arrive at correct answers through flawed logic, raising concerns about similar issues in code understanding. In this work, we evaluate whether state-of-the-art LLMs with up to 8B parameters can reason about Python programs or are simply guessing. We apply five semantics-preserving code mutations, renaming variables, mirroring comparison expressions, swapping if-else branches, converting for loops to while, and loop unrolling. These mutations maintain program semantics while altering its syntax. We evaluated six LLMs and performed a human expert analysis using LiveCodeBench to assess whether the correct predictions are based on sound reasoning. We also evaluated prediction stability across different code mutations on LiveCodeBench and CruxEval. Our findings show that some LLMs, such as Llama3.2, produce correct predictions based on flawed reasoning in up to 61% of cases. Furthermore, LLMs often change predictions in response to our code mutations, indicating limited robustness in their semantic understanding.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-05-15T09:00:00Z'
date_end: '2025-05-15T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: [LLMs for Code Understanding, Semantic Robustness of Large Language Models, Code Mutations, AI4SE]

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**IIIA**](https://dei.tecnico.ulisboa.pt/en/events/dei-wed/wednesdaysdei-talks-10-09-2025)'
#   focal_point: Right

links:
#   - type: code
#     url: https://github.com
   - type: slides
     url: "../uploads/slides/slides-2025-05-15-oxford.pdf"
   - name: project
     url: projects/ai4code
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
 - ai4code

# > [!NOTE]
# > Click on the **Slides** button above to view the built-in slides feature.

---


