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

- Built a modular "Injector" pipeline (pattern-gen → sampling → injection → evaluation) with beam-search pruning and Optuna/TPE-based Bayesian tuning to systematically surface structured corruptions that reduce downstream AUC by >0.25 compared to random-parameter attacks.
- Co-authored "Stress-Testing ML Pipelines with Adversarial Data Corruption" (SAVAGE), designing corruption dependency graphs and bi-level black-box search to model mechanism-aware missingness, selection-bias, and outlier patterns for pipeline-level stress-testing of ML systems.
- Ran Inject → Clean → Retrain benchmarks across missing-value, selection-bias, and outlier scenarios to evaluate state-of-the-art cleaning, debiasing, and UQ pipelines and expose their data-centric robustness gaps.
