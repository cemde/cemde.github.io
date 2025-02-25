---
title: "Shh, don't say that! Domain Certification in LLMs"
collection: publications
category: conferences
permalink: /publication/2025-domain-certification
excerpt: "We introduce domain certification, a new safety paradigm focusing on risk control for LLMs. We provide formal a guarantee that accurately characterizes when language models stay within their intended operational boundaries. We demonstrate a effective test-time algorithm, VALID, that provides scalable defenses for foundation models."
date: 2025-01-22
venue: "International Conference on Learning Representations (ICLR)"
paperurl: ""
citation: ""
---

## Abstract

Large language models (LLMs) are often deployed to do constrained tasks, with narrow domains. For example, customer support bots can be built on top of LLMs, relying on their broad language understanding and capabilities to enhance performance. However, these LLMs are adversarially susceptible, potentially generating outputs outside the intended domain. To formalize, assess and mitigate this risk, we introduce \emph{domain certification}; a guarantee that accurately characterizes the out-of-domain behavior of language models. We then propose a simple yet effective approach dubbed VALID that provides adversarial bounds as a certificate. Finally, we evaluate our method across a diverse set of datasets, demonstrating that it yields meaningful certificates.

<!-- [Download paper here]() -->

[Download paper here](https://openreview.net/forum?id=F64wTvQBum) Final version to be uploaded soon!

## BibTex

```bibtex
@inproceedings{emde_shh_2024,
title = {Shh, don't say that! {Domain} {Certification} in {LLMs}},
url = {https://openreview.net/forum?id=F64wTvQBum},
author = {Emde, Cornelius and Paren, Alasdair and Arvind, Preetham and Kayser, Maxime and Rainforth, Tom and Lukasiewicz, Thomas and Ghanem, Bernard and Torr, Philip and Bibi, Adel},
booktitle={The Thirteenth International Conference on Learning Representations (ICLR)},
year = {2025},
abstract = {Large language models (LLMs) are often deployed to perform constrained tasks,
with narrow domains. For example, customer support bots can be built on top
of LLMs, relying on their broad language understanding and capabilities to en-
hance performance. However, these LLMs are adversarially susceptible, poten-
tially generating outputs outside the intended domain. To formalize, assess and
mitigate this risk, we introduce domain certification; a guarantee that accurately
characterizes the out-of-domain behaviour of language models. We then propose
a simple yet effective approach which we call VALID that provides adversarial
bounds as a certificate. Finally, we evaluate our method across a diverse set of
datasets, demonstrating that it yields meaningful certificates.},
}
```
