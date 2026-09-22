---
layout: page
title: Data Quality and Fairness in ML
description: Research on improving fairness and robustness in machine learning models through data quality management
img: assets/img/ucsd.jpeg
importance: 1
category: work
related_publications: true
---

**UCSD Halıcıoğlu Data Science Institute (Oct 2023 - Oct 2024)**  
**Research Engineer | Supervisor: Babak Salimi | La Jolla, CA**

This project focuses on developing a framework to manage and improve data quality, with the goal of enhancing fairness and robustness in machine learning models. The work involves creating tools to handle data biases and conducting experiments to assess the effectiveness of these tools.

**DOI:** [Stress-Testing ML Pipelines with Adversarial Data Corruption](https://doi.org/10.14778/3749646.3749721)  
**Code:** [https://github.com/lodino/savage](https://github.com/lodino/savage)

- Built an Injector pipeline (generate → sample → inject → eval) driving a gradient-free bi-level search: beam search over corruption dependency graphs at the outer level, Optuna/TPE over parameters at the inner, with the pipeline as a black box.
- Benchmarked the search against random corruption injection, cutting downstream model AUC by >0.25 and turning each win into a readable failure pattern — which subpopulation broke, and by what mechanism.
- Ran Inject → Clean → Retrain benchmarks across missing-value, selection-bias, and outlier scenarios to evaluate state-of-the-art cleaning, debiasing, and UQ pipelines and expose their data-centric robustness gaps.
