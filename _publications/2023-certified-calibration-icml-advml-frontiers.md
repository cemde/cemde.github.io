---
title: "Certified Calibration: Bounding Worst-Case Calibration under Adversarial Attacks"
collection: publications
category: workshops
permalink: /publication/2023-certified-calibration-icml-advml-frontiers
excerpt: "We introduce certified calibration, a novel approach providing worst-case bounds on neural classifier confidence under adversarial attacks. We demonstrate that existing defences do not protect calibration sufficiently, and provide analytic bounds for the Brier score and approximate bounds for Expected Calibration Error using mixed integer nonlinear programming."
date: 2023-07-28
venue: "New Frontiers in Adversarial Machine Learning - ICML"
paperurl: "https://cemde.github.io/files/emde-2023-certified-calibration.pdf"
citation: ""
---

## Abstract

Since neural classifiers are known to be sensitive to adversarial perturbations that alter their accuracy, _certification methods_ have been developed to provide provable guarantees on the insensitivity of their predictions to such perturbations. However, in safety-critical applications, the frequentist interpretation of the confidence of a classifier (also known as model calibration) can be of utmost importance. This property can be measured via the Brier Score or the Expected Calibration Error. We show that attacks can significantly harm calibration, and thus propose certified calibration providing worst-case bounds on calibration under adversarial perturbations. Specifically, we produce analytic bounds for the Brier score and approximate bounds via the solution of a mixed-integer program on the Expected Calibration Error.

[Download paper here](https://cemde.github.io/files/emde-2023-certified-calibration.pdf)

## BibTex

```bibtex
@misc{emde_certified_calibration_2023,
     title = {Certified {Calibration}: {Bounding} {Worst}-{Case} {Calibration} under {Adversarial} {Attacks}},
     url = {<https://cemde.github.io/files/emde-2023-certified-calibration.pdf}>,
     publisher = {New Frontiers in Adversarial Machine Learning - ICML 2023},
     author = {Emde, Cornelius and Pinto, Francesco and Lukasiewicz, Thomas and Torr, Philip H. S. and Bibi, Adel},
     month = jul,
     year = {2023},
}
```
