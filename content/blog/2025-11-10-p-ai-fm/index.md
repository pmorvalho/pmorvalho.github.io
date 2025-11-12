---
title: 📄 Paper accepted @ the Post-AI Formal Methods Workshop @ AAAI 2026! 🎉
summary: I’m excited to share that our paper on PyVeritas has been accepted to the P-AI-FM-26 Workshop @ AAAI 2026! 📄
date: 2025-11-10
authors:
  - admin
tags:
  - Software Verification
  - Model Checking
  - Python Verification
  - LLM-Based Transpilation
  - MaxSAT-Based Fault Localisation
  - Formal Methods
  - PyVeritas

image:
  caption: 'Image credit: [**P-AI-FM-26 Workshop**](https://www.p-ai-fm.com)'
  
links:
  - name: paper
    url: "/publications/p-ai-fm-2026"
  - name: project
    url: "/projects/ai4code"
    
---

I’m excited to share that our paper on **PyVeritas** has been accepted to the **Post-AI Formal Methods Workshop @ AAAI 2026**! 📄

{{< button url="/publications/p-ai-fm-2026" new_tab="true" style="secondary" rounded="full" align="center" >}}Read the paper!{{< /button >}}

**TL;DR:** Python → LLM transpiles to C → bounded model checking (CBMC) + MaxSAT-based fault localisation (CFaults) → source-level mapping back to Python.

**What’s PyVeritas?**  
A framework that leverages Large Language Models to transpile Python into C, then applies bounded model checking and MaxSAT-based fault localisation on the generated code.

This brings assertion-based verification and interpretable bug diagnosis to small yet non-trivial Python programs!

On two Python benchmarks, LLM-based transpilation achieved up to **80–90% accuracy** with some models, enabling an effective verification workflow.


{{< button url="/projects/ai4code" new_tab="true" style="secondary" rounded="full" align="center" >}}Check out our research project page!{{< /button >}}
