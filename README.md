# Predicting e-Commerce Customer Intention
---

This assignment was solved as part of my interview process at [Aicadium](https://aicadium.ai/). The problem statement and dataset was provided by Aicadium with the expectation that I will provide a link to my GitHub repo with my solution.

The total time spent on this assignment was ~5-6 hours.

The code is split up into two parts [Data Exploration](Data%20Exploration.ipynb) and [Data Modelling](Data%20Modelling.ipynb) with each file also having its respective .html copy.

The code in the notebooks is split into sections using headers for better readability. It also contains details about the reasoning behind certain decisions.

The final model is expected to have an F1 score of **0.64** on the *True* label for *Revenue*

---

Summary of techniques/algorithms explored:

* Data Manipulation
  * One-Hot Encoding
  * Scaling (Standard Scaler)


* Tackling Imbalance
  * Weighted classes
  * SMOTENC


* Logistic Regression
  * Vanilla
  * Weighted
  * L1 Regularization


* Boosted Trees
  * XGBoost
  * LightGBM

---
