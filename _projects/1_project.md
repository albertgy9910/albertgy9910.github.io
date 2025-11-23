---
layout: page
title: Data Quality and Fairness in ML
description: Research on improving fairness and robustness in machine learning models through data quality management
img: assets/img/ucsd.jpeg
importance: 1
category: work
related_publications: true
---

**UCSD Halıcıoğlu Data Science Institute (Oct 2023 - Sep 2024)**  
**Research Engineer | Supervisor: Babak Salimi | La Jolla, CA**

This project focuses on developing a framework to manage and improve data quality, with the goal of enhancing fairness and robustness in machine learning models. The work involves creating tools to handle data biases and conducting experiments to assess the effectiveness of these tools.

**Preprint:** [Stress-Testing ML Pipelines with Adversarial Data Corruption](https://arxiv.org/abs/2506.01230)  
**Code:** [https://github.com/lodino/savage](https://github.com/lodino/savage)

- Built a modular "Injector" pipeline (pattern-gen → sampling → injection → evaluation) with beam-search pruning and Optuna Bayesian tuning, raising downstream model accuracy by 10% and fairness by 15%.
- Co-authored "Stress-Testing ML Pipelines with Adversarial Data Corruption," VLDB 2025; introduced the first adversarial benchmark for data-quality robustness.
- Ran comprehensive Inject → Clean → Retrain benchmarks on missing-value, selection-bias, and outlier scenarios while optimizing Z-score standardization for skewed data—boosting attack coverage 30%.
- Developed and implemented a framework for specifying and injecting complex data quality issues into datasets, using Python to address data biases and improve fairness and accuracy in machine learning models.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ucsd.jpeg" title="UCSD Halıcıoğlu Data Science Institute" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    UCSD Halıcıoğlu Data Science Institute, where the research on data quality and fairness in machine learning models is conducted.
</div>

Throughout the project, the focus has been on developing a comprehensive framework that can be applied across different machine learning models to ensure that they are robust and fair, even when faced with biased or incomplete data. Our work has been published in VLDB 2025, introducing the first adversarial benchmark for data-quality robustness.

<div class="caption">
    The project involves extensive experimentation and evaluation of various data cleaning tools and techniques.
</div>
