---
title: "Towards Assessing and Repairing LLM-Generated Code via Model Checking and MaxSAT-Based Fault Localisation @ Dagstuhl 2026"

event: In the *Dagstuhl Seminar 26192 - Evaluation of AI Models in Software Engineering*
event_url: https://www.dagstuhl.de/en/seminars/seminar-calendar/seminar-details/26192

location: Dagstuhl
address: 
  street:
  city: Wadern, Saarland
  region: Germany.
  postcode: ''
  country: ''

summary: LLMs for code often lack true semantic understanding, evidenced by their instability under semantics-preserving transformations, and we address this by integrating formal methods (model checking and MaxSAT-based fault localisation) with LLMs to improve program repair and enable reliable verification via a hybrid Python-to-C pipeline.

abstract: Large Language Models (LLMs) are increasingly used for programming tasks, yet their ability to truly understand program semantics remains unclear. In this talk, we investigate the robustness and reliability of LLMs in reasoning about code. We first present an empirical study evaluating whether LLMs’ output predictions are grounded in sound reasoning or arise from superficial pattern matching. By introducing a set of semantics-preserving code mutations—such as variable renaming, control-flow transformations, and loop modifications—we show that even state-of-the-art models frequently change their predictions, revealing limited robustness to syntactic variations. Motivated by these findings, we explore how to improve the correctness of LLM-generated code by integrating formal methods. We present an approach that combines model checking with MaxSAT-based fault localisation to guide LLMs toward more accurate program repairs. Our approach leverages counterexamples and minimal diagnoses to identify faulty code regions, which are then used to refine LLM prompts. Finally, we introduce a novel approach for verifying Python programs by leveraging LLM-based transpilation to C and bounded model checking. This hybrid pipeline enables precise fault localisation and verification of non-trivial Python programs, bridging the gap between the flexibility of LLMs and the rigor of formal verification tools. Overall, this work highlights fundamental limitations in current code models and demonstrates how neurosymbolic approaches can enhance their reliability in Software Engineering tasks.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-05-05T16:30:00Z'
date_end: '2026-05-05T17:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors:
  - admin

tags: [Software Verification, Model Checking, Python Verification, LLM-Based Transpilation, MaxSAT-Based Fault Localisation, Formal Methods, CFaults, PyVeritas]

# Is this a featured talk? (true/false)
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Schloss Dagstuhl**](https://www.dagstuhl.de/)'  
  focal_point: ''
  preview_only: false


links:
   - type: slides
     url: "../uploads/slides/slides-2026-05-05-dagstuhl-26192.pdf"
   - name: project
     url: projects/ai4code

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


