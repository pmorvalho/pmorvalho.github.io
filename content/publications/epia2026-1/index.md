---
title: "Large Language Models Are Not (Yet) Robust in Understanding Code Against Semantics-Preserving Mutations"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Marta Kwiatkowska

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-07-13T00:01:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-07-13T00:01:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the *25th EPIA Conference on Artificial Intelligence*, *EPIA 2026* **[CORE National Conference]**. _[Accepted for Publication]_
publication_short: In **EPIA 2026**

abstract: With the widespread adoption of vibe coding, understanding the reasoning and robustness of Large Language Models (LLMs) is critical for their reliable use in programming tasks. While recent studies assess LLMs’ ability to predict program outputs, most focus on accuracy alone, without evaluating the underlying reasoning. Moreover, it has been observed on mathematical reasoning tasks that LLMs can arrive at correct answers through flawed logic, raising concerns about similar issues in code understanding. In this paper we assess whether state-of-the-art LLMs  can reason about Python programs or are simply guessing. We apply five semantics-preserving code mutations, such as, renaming variables, mirroring comparison expressions, swapping if-else branches, converting for loops to while, and loop unrolling. These mutations maintain program semantics while altering its syntax. We evaluated nine LLMs, including both open-source and closed-access models, and performed a human expert analysis using LiveCodeBench to assess whether correct predictions are based on sound reasoning. We also evaluated prediction stability across different code mutations on LiveCodeBench and CruxEval. While proprietary models achieve the strongest predictive accuracy and reasoning quality in the expert evaluation, our robustness analysis reveals substantial fragility under semantics-preserving transformations. Our findings show that the evaluated code-specialised LLMs produce correct predictions based on flawed reasoning in up to 45% of cases. Furthermore, LLMs often change predictions in response to our code mutations, with performance drops reaching up to 70%, indicating that they do not yet exhibit stable, semantically grounded reasoning, even when initial accuracy is high.


# Summary. An optional shortened abstract.
summary: In this paper we assess whether SOTA LLMs can reason about Python programs or are simply guessing. We apply five semantics-preserving code mutations, which maintain program semantics while altering its syntax. We evaluated nine LLMs, including both open-source and closed-access models, and performed a human expert analysis using LiveCodeBench to assess whether correct predictions are based on sound reasoning. We also evaluated prediction stability across different code mutations on LiveCodeBench and CruxEval.

tags:
 - LLMs for Code Understanding
 - Semantic Robustness of Large Language Models
 - Code Mutations
 - AI4SE
 - MaxSAT-Based Fault Localisation
 - Formal Methods
 
# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    # doi: 10.48550/arXiv.2504.16742
    arxiv: 2505.10443

# Custom links
links:
  - type: pdf
    url: "../uploads/papers/epia2026-LLMCs-Semantic-Robustness.pdf"
  - name: project
    url: projects/ai4code
  - name: GitHub
    url: "https://github.com/pmorvalho/EPIA26-LLMCs-Semantic-Robustness"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**EPIA**](https://epia2026.web.uma.pt)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - ai4code

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
