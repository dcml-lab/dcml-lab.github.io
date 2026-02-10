---
title: "What is the Right Notion of Distance between Predict-then-Optimize Tasks?"
authors: "Paula Rodriguez-Diaz, Lingkai Kong, Kai Wang, David Alvarez-Melis, Milind Tambe"
venue: "UAI"
year: 2025
arxiv: "https://arxiv.org/abs/2409.06997"
pdf: "https://arxiv.org/pdf/2409.06997.pdf"
code: "https://github.com/paularodr/OTD3"
hero_image: "/img/publications/otd3-hero.png"
summary: "In predict-then-optimize, what matters is decision regret—not prediction error. Traditional dataset distances miss this. OTD³ incorporates downstream decisions into the distance, accurately predicting when models will transfer across optimization tasks."
abstract: |
  Comparing datasets is a fundamental task in machine learning, essential for various learning paradigms—from evaluating train and test datasets for model generalization to using dataset similarity for detecting data drift. While traditional notions of dataset distances offer principled measures of similarity, their utility has largely been assessed through prediction error minimization. However, in Predict-then-Optimize (PtO) frameworks, where predictions serve as inputs for downstream optimization tasks, model performance is measured through decision regret rather than prediction error. In this work, we propose OTD³ (Optimal Transport Decision-aware Dataset Distance), a novel dataset distance that incorporates downstream decisions in addition to features and labels.
bibtex: |
  @inproceedings{rodriguez2025distance,
    title={What is the Right Notion of Distance between Predict-then-Optimize Tasks?},
    author={Rodriguez-Diaz, Paula and Kong, Lingkai and Wang, Kai and Alvarez-Melis, David and Tambe, Milind},
    booktitle={Conference on Uncertainty in Artificial Intelligence},
    year={2025}
  }
---
