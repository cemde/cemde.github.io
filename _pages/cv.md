---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* Ph.D in Computer Science, University of Oxford, 2024 (expected)
* MSc in Statistics, University of Warwick, 2018
* BSc in Psychlogy, University of Groningen, 2017

Work experience
======

* Wise Payements (February to June 2022)
  * Core developer of [Neural-Lifetimes](https://github.com/transferwise/neural-lifetimes). This library enables customer transactions prediction for various downstream applications using PyTorch.
  * Developed and implemented neural network model on unstructured time-series data.
  * Implemented SOTA methods for representation learning based on mutual information. Adapted methods that were only verified on MNIST to real-life data.

* 2021: Oxford Strategy Group Digital
  * Senior Consultant
  * Developed Machine Learning for financial industry client.

Skills
======

* Machine Learning
* Deep Learning
* Statistics
  * Decision Theory
  * Applied Frequentist and Bayesian Modelling
  * Time Series
* Bayesian Inference
  * Monte Carlo Simulation
  * Variational Methods
  * Bayesian Systems and Statistical Control
* Computer Vision

Publications
======

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======

  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Repositories
======

* [FleissKappa](https://github.com/cemde/FleissKappa) a `torchmetrics` compatible implementation of FleissKappa.
* [FilenameManager](https://github.com/cemde/FilenameManager) a very light-weight Python library that uses configuration parameters to create filenames and can convert filenames to parameters. Useful for saving ML experiment data to disk without database.
* [LiteralCopy](https://github.com/cemde/CopySyntax/) a simple Python library that takes existing objects in memory and returns a string with the syntax to recreate that object. Supports base Python, NumPy and PyTorch.

Service and leadership
======

* Created and maintained compute documentation for our resaerch group
* Mentor at [Project Access](https://projectaccess.org/)
* Honorary sailing instructor
* Winner of a 2016 transatlantic sailing race on the 52-foot yacht "Bank von Bremen"
