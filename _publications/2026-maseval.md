---
title: "MASEval: Extending Multi-Agent Evaluation from Models to Systems"
collection: publications
category: manuscripts
permalink: /publication/2026-maseval
excerpt: "We identify privacy collapse, a novel phenomenon where benign fine-tuning of frontier models degrades contextual privacy reasoning. Fine-tuned models share information inappropriately with tools and violate memory boundaries, while maintaining high performance on standard safety benchmarks. Our mechanistic analysis reveals that privacy representations are uniquely fragile to fine-tuning."
date: 2025-01-22
venue: "arXiv preprint"
paperurl: "https://arxiv.org/pdf/2601.15220.pdf"
citation: ""
---

## Abstract

The rapid adoption of LLM-based agentic systems has produced a rich ecosystem of frameworks (smolagents, LangGraph, AutoGen, CAMEL, LlamaIndex, i.a.). Yet existing benchmarks are model-centric: they fix the agentic setup and do not compare other system components. We argue that implementation decisions substantially impact performance, including choices such as topology, orchestration logic, and error handling. MASEval addresses this evaluation gap with a framework-agnostic library that treats the entire system as the unit of analysis. Through a systematic system-level comparison across 3 benchmarks, 3 models, and 3 frameworks, we find that framework choice matters as much as model choice. MASEval allows researchers to explore all components of agentic systems, opening new avenues for principled system design, and practitioners to identify the best implementation for their use case.

[Download paper here](https://arxiv.org/abs/2603.08835)

[Code](https://github.com/parameterlab/MASEval)

[Documentation](https://maseval.readthedocs.io/en/stable/)


## BibTex

```bibtex
@misc{emde2026maseval,
      title={MASEval: Extending Multi-Agent Evaluation from Models to Systems},
      author={Cornelius Emde and Alexander Rubinstein and Anmol Goel and Ahmed Heakl and Sangdoo Yun and Seong Joon Oh and Martin Gubri},
      year={2026},
      eprint={2603.08835},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2603.08835},
}
```
