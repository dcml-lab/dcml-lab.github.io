---
title: "Distributional Dataset Distillation with Subtask Decomposition"
authors: "Tian Qin, Zhiwei Deng, David Alvarez-Melis"
venue: "DPFM @ ICLR"
year: 2024
arxiv: "https://arxiv.org/abs/2403.00999"
pdf: "https://arxiv.org/pdf/2403.00999"
hero_image: "/img/publications/d3-hero.png"
summary: "Why distill datasets into explicit images when you can use distributions? D3 encodes classes as minimal sufficient statistics plus a decoder—more memory-efficient than prototypes. With federated distillation, we scale to ImageNet-1K and beat prior art by 6.9%."
abstract: |
  What does a neural network learn when training from a task-specific dataset? Synthesizing this knowledge is the central idea behind Dataset Distillation, which recent work has shown can be used to compress large datasets into a small set of input-label pairs (prototypes) that capture essential aspects of the original dataset. In this paper, we make the key observation that existing methods distilling into explicit prototypes are very often suboptimal, incurring unexpected storage cost from distilled labels. In response, we propose Distributional Dataset Distillation (D3), which encodes the data using minimal sufficient per-class statistics and paired with a decoder, we distill dataset into a compact distributional representation that is more memory-efficient compared to prototype-based methods.
bibtex: |
  @inproceedings{qin2024distributional,
    title         = {Distributional Dataset Distillation with Subtask Decomposition},
    author        = {Qin, Tian and Deng, Zhiwei and Alvarez-Melis, David},
    booktitle     = {ICLR 2024 Workshop on Navigating and Addressing Data Problems for Foundation Models},
    year          = {2024},
    eprint        = {2403.00999},
    archivePrefix = {arXiv},
    url           = {https://arxiv.org/abs/2403.00999}
  }
---
