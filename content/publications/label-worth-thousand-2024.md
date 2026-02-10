---
title: "A Label is Worth a Thousand Images in Dataset Distillation"
authors: "Tian Qin, Zhiwei Deng, David Alvarez-Melis"
venue: "NeurIPS"
year: 2024
arxiv: "https://arxiv.org/abs/2406.10485"
pdf: "https://arxiv.org/pdf/2406.10485"
proceedings: "https://proceedings.neurips.cc/paper/2024/hash/ee45939f4403e8abd63a15a29a9c055b-Abstract-Conference.html"
code: "https://github.com/sunnytqin/no-distillation"
hero_image: "/img/publications/label-worth-hero.png"
summary: "The secret sauce in dataset distillation? It's not the synthetic images—it's the soft labels. We show that structured probabilistic labels are the main driver of performance, challenging conventional wisdom and opening new directions for data compression."
abstract: |
  Data quality is a crucial factor in the performance of machine learning models, a principle that dataset distillation methods exploit by compressing training datasets into much smaller counterparts that maintain similar downstream performance. Understanding how and why data distillation methods work is vital not only for improving these methods but also for revealing fundamental characteristics of "good" training data. In this work, we highlight a largely overlooked aspect common to most of these methods: the use of soft (probabilistic) labels. Through a series of ablation experiments, we study the role of soft labels in depth. Our results reveal that the main factor explaining the performance of state-of-the-art distillation methods is not the specific techniques used to generate synthetic data but rather the use of soft labels.
bibtex: |
  @inproceedings{qin2024label,
    title={A Label is Worth a Thousand Images in Dataset Distillation},
    author={Qin, Tian and Deng, Zhiwei and Alvarez-Melis, David},
    booktitle={Advances in Neural Information Processing Systems},
    year={2024}
  }
---
