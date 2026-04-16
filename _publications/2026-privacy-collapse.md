---
title: "Privacy Collapse: Benign Fine-Tuning Can Break Contextual Privacy in Language Models"
collection: publications
category: conferences
permalink: /publication/2026-privacy-collapse
excerpt: "We identify privacy collapse, a novel phenomenon where benign fine-tuning of frontier models degrades contextual privacy reasoning. Fine-tuned models share information inappropriately with tools and violate memory boundaries, while maintaining high performance on standard safety benchmarks. Our mechanistic analysis reveals that privacy representations are uniquely fragile to fine-tuning."
date: 2026-05-01
venue: "ACL"
paperurl: "https://arxiv.org/pdf/2601.15220.pdf"
citation: ""
---

## Abstract

We identify a novel phenomenon in language models: benign fine-tuning of frontier models can lead to privacy collapse. We find that diverse, subtle patterns in training data can degrade contextual privacy, including optimisation for helpfulness, exposure to user information, emotional and subjective dialogue, and debugging code printing internal variables, among others. Fine-tuned models lose their ability to reason about contextual privacy norms, share information inappropriately with tools, and violate memory boundaries across contexts. Privacy collapse is a ``silent failure'' because models maintain high performance on standard safety and utility benchmarks whilst exhibiting severe privacy vulnerabilities. Our experiments show evidence of privacy collapse across six models (closed and open weight), five fine-tuning datasets (real-world and controlled data), and two task categories (agentic and memory-based). Our mechanistic analysis reveals that privacy representations are uniquely fragile to fine-tuning, compared to task-relevant features which are preserved. Our results reveal a critical gap in current safety evaluations, in particular for the deployment of specialised agents.

[Download paper here](https://arxiv.org/abs/2601.15220)

## BibTex

```bibtex
@misc{goel2026privacycollapse,
      title={Privacy Collapse: Benign Fine-Tuning Can Break Contextual Privacy in Language Models},
      author={Anmol Goel and Cornelius Emde and Sangdoo Yun and Seong Joon Oh and Martin Gubri},
      booktitle = "Proceedings of the 31st International Conference on Computational Linguistics (ACL)",
      publisher = "Association for Computational Linguistics",
      year={2026},
      eprint={2601.15220},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2601.15220},
}
```