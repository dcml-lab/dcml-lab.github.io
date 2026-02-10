---
title: "DDEQs: Distributional Deep Equilibrium Models through Wasserstein Gradient Flows"
authors: "Jonathan Geuter, Clément Bonet, Anna Korba, David Alvarez-Melis"
venue: "AISTATS"
year: 2025
arxiv: "https://arxiv.org/abs/2503.01140"
pdf: "https://proceedings.mlr.press/v258/geuter25a/geuter25a.pdf"
proceedings: "https://proceedings.mlr.press/v258/geuter25a.html"
code: "https://github.com/j-geuter/DDEQs"
hero_image: "/img/publications/ddeqs-hero.png"
summary: "We extend Deep Equilibrium Models to handle sets and point clouds by finding fixed points in the space of distributions using Wasserstein gradient flows. DDEQs match state-of-the-art performance on point cloud tasks while being dramatically more parameter-efficient."
abstract: |
  Deep Equilibrium Models (DEQs) are a class of implicit neural networks that solve for a fixed point of a neural network in their forward pass. Traditionally, DEQs take sequences as inputs, but have since been applied to a variety of data. In this work, we present Distributional Deep Equilibrium Models (DDEQs), extending DEQs to discrete measure inputs, such as sets or point clouds. We provide a theoretically grounded framework for DDEQs. Leveraging Wasserstein gradient flows, we show how the forward pass of the DEQ can be adapted to find fixed points of discrete measures under permutation-invariance, and derive adequate network architectures for DDEQs. In experiments, we show that they can compete with state-of-the-art models in tasks such as point cloud classification and point cloud completion, while being significantly more parameter-efficient.
bibtex: |
  @inproceedings{geuter2025ddeqs,
    title={DDEQs: Distributional Deep Equilibrium Models through Wasserstein Gradient Flows},
    author={Geuter, Jonathan and Bonet, Cl{\'e}ment and Korba, Anna and Alvarez-Melis, David},
    booktitle={International Conference on Artificial Intelligence and Statistics},
    year={2025}
  }
---
