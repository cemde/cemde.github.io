---
title: "Towards Certification of Uncertainty Calibration under Adversarial Attacks"
collection: publications
category: conferences
permalink: /publication/2025-certification-of-uncertainty-calibration
excerpt: "We tackle the vulnerability of uncertainty quantification in neural classifiers to adversarial attacks and thus propose certified calibration to provide worst-case bounds on confidence under perturbations. We develop novel calibration attacks that enable adversarial calibration training, demonstrating improved model uncertainty quantification in safety-critical applications."
date: 2025-01-22
venue: "International Conference on Learning Representations (ICLR)"
paperurl: "https://arxiv.org/abs/2405.13922"
citation: ""
---

## Abstract

Since neural classifiers are known to be sensitive to adversarial perturbations that alter their accuracy, certification methods have been developed to provide provable guarantees on the insensitivity of their predictions to such perturbations. Furthermore, in safety-critical applications, the frequentist interpretation of the confidence of a classifier (also known as model calibration) can be of utmost importance. This property can be measured via the Brier score or the expected calibration error. We show that attacks can significantly harm calibration, and thus propose certified calibration as worst-case bounds on calibration under adversarial perturbations. Specifically, we produce analytic bounds for the Brier score and approximate bounds via the solution of a mixed-integer program on the expected calibration error. Finally, we propose novel calibration attacks and demonstrate how they can improve model calibration through adversarial calibration training.

[Download paper here](https://arxiv.org/abs/2405.13922)

## BibTex

```bibtex
@misc{emde2024certification,
title={Towards Certification of Uncertainty Calibration under Adversarial Attacks},
author={Cornelius Emde and Francesco Pinto and Thomas Lukasiewicz and Philip H. S. Torr and Adel Bibi},
booktitle={The Thirteenth International Conference on Learning Representations (ICLR)},
year={2025},
eprint={2405.13922},
archivePrefix={arXiv},
primaryClass={cs.LG}
}
```
