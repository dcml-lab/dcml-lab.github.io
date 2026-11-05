---
title: "Are GANs overkill for NLP?"
authors: "David Alvarez-Melis, Vikas Garg, Adam Kalai"
venue: "NeurIPS"
year: 2022
arxiv: "https://arxiv.org/abs/2205.09838"
pdf: "https://arxiv.org/pdf/2205.09838.pdf"
hero_image: "/img/publications/gans-nlp-hero.png"
summary: "Why haven't GANs conquered NLP the way they did computer vision? We prove that for models like n-grams and neural networks with softmax, minimizing distinguishability reduces to maximizing likelihood—so GANs are unnecessary overhead."
abstract: |
  This work offers a novel theoretical perspective on why, despite numerous attempts, adversarial approaches to generative modeling (e.g., GANs) have not been as popular for certain generation tasks, particularly sequential tasks such as Natural Language Generation, as they have in others, such as Computer Vision. In particular, on sequential data such as text, maximum-likelihood approaches are significantly more utilized than GANs. We show that, while it may seem that maximizing likelihood is inherently different than minimizing distinguishability, this distinction is largely artificial and only holds for limited models. We argue that minimizing KL-divergence (i.e., maximizing likelihood) is a more efficient approach to effectively minimizing the same distinguishability criteria that adversarial models seek to optimize.
bibtex: |
  @inproceedings{alvarez-melis2022gans,
    title         = {Are {GANs} overkill for {NLP}?},
    author        = {Alvarez-Melis, David and Garg, Vikas and Kalai, Adam},
    booktitle     = {Advances in Neural Information Processing Systems},
    volume        = {35},
    pages         = {9072--9084},
    publisher     = {Curran Associates, Inc.},
    year          = {2022},
    eprint        = {2205.09838},
    archivePrefix = {arXiv},
    url           = {https://arxiv.org/abs/2205.09838}
  }
---
