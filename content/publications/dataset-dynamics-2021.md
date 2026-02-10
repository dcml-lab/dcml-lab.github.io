---
title: "Dataset Dynamics via Gradient Flows in Probability Space"
authors: "David Alvarez-Melis, Nicolò Fusi"
venue: "ICML"
year: 2021
pdf: "http://proceedings.mlr.press/v139/alvarez-melis21a/alvarez-melis21a.pdf"
proceedings: "https://proceedings.mlr.press/v139/alvarez-melis21a.html"
selected: true
hero_image: "/img/publications/dataset-dynamics-hero.png"
summary: "We cast dataset transformation as optimization in probability space, using Wasserstein gradient flows to manipulate labeled datasets in principled ways. This enables imposing constraints on data, adapting datasets for transfer learning, and repurposing models for new tasks."
abstract: |
  Various machine learning tasks, from generative modeling to domain adaptation, revolve around the concept of dataset transformation and manipulation. While various methods exist for transforming unlabeled datasets, principled methods to do so for labeled (e.g., classification) datasets are missing. In this work, we propose a novel framework for dataset transformation, which we cast as optimization over data-generating joint probability distributions. We approach this class of problems through Wasserstein gradient flows in probability space, and derive practical and efficient particle-based methods for a flexible but well-behaved class of objective functions. Through various experiments, we show that this framework can be used to impose constraints on classification datasets, adapt them for transfer learning, or to re-purpose fixed or black-box models to classify—with high accuracy—previously unseen datasets.
bibtex: |
  @inproceedings{alvarez2021dataset,
    title={Dataset Dynamics via Gradient Flows in Probability Space},
    author={Alvarez-Melis, David and Fusi, Nicol{\`o}},
    booktitle={International Conference on Machine Learning},
    pages={219--230},
    year={2021},
    organization={PMLR}
  }
---
