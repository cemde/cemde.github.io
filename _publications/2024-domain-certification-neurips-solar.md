---
title: "Shh, don't say that! Domain Certification in LLMs"
collection: publications
category: workshops
permalink: /publication/2024-domain-certification
excerpt: "We introduce domain certification, a formal guarantee that accurately characterizes when language models stay within their intended operational boundaries. We demonstrate VALID, our effective approach that provides provable defense against adversarial inputs through meaningful certificates that ensure models remains within its intended domain, even under attack."
date: 2024-10-02
venue: "Socially Responsible Language Modelling Research (SoLaR) workshop @ NeurIPS"
paperurl: ""
citation: ""
---

## Abstract

Large language models (LLMs) are often deployed to do constrained tasks, with narrow domains. For example, customer support bots can be built on top of LLMs, relying on their broad language understanding and capabilities to enhance performance. However, these LLMs are adversarially susceptible, potentially generating outputs outside the intended domain. To formalize, assess and mitigate this risk, we introduce \emph{domain certification}; a guarantee that accurately characterizes the out-of-domain behavior of language models. We then propose a simple yet effective approach dubbed VALID that provides adversarial bounds as a certificate. Finally, we evaluate our method across a diverse set of datasets, demonstrating that it yields meaningful certificates.

<!-- [Download paper here]() -->

Refer to the extended ICLR 2025 version to download the work.

## BibTex

```bibtex
@inproceedings{emde_shh_2024,
title = {Shh, don't say that! {Domain} {Certification} in {LLMs}},
url = {https://openreview.net/forum?id=brDLUmZJ1E},
booktitle = {Workshop on {Socially} {Responsible} {Language} {Modelling} {Research}},
author = {Emde, Cornelius and Arvind, Preetham and Paren, Alasdair and Kayser, Maxime and Rainforth, Tom and Lukasiewicz, Thomas and Ghanem, Bernard and Torr, Philip and Bibi, Adel},
year = {2024},
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
