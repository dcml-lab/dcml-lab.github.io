---
title: "Towards Optimal Transport with Global Invariances"
authors: "David Alvarez-Melis, Stefanie Jegelka, Tommi S. Jaakkola"
venue: "AISTATS"
year: 2019
pdf: "http://proceedings.mlr.press/v89/alvarez-melis19a/alvarez-melis19a.pdf"
proceedings: "https://proceedings.mlr.press/v89/alvarez-melis19a.html"
selected: true
hero_image: "/img/publications/ot-invariances-hero.png"
summary: "How do you compute optimal transport when your representations are only defined up to rotations or reflections? We jointly optimize over transport couplings and latent transformations, enabling OT-based alignment for learned embeddings like word vectors."
abstract: |
  Many problems in machine learning involve calculating correspondences between sets of objects, such as point clouds or images. Discrete optimal transport provides a natural and successful approach to such tasks whenever the two sets of objects can be represented in the same space, or at least distances between them can be directly evaluated. Unfortunately neither requirement is likely to hold when object representations are learned from data. Indeed, automatically derived representations such as word embeddings are typically fixed only up to some global transformations, for example, reflection or rotation. As a result, pairwise distances across two such instances are ill-defined without specifying their relative transformation. In this work, we propose a general framework for optimal transport in the presence of latent global transformations.
bibtex: |
  @inproceedings{alvarez2019towards,
    title={Towards Optimal Transport with Global Invariances},
    author={Alvarez-Melis, David and Jegelka, Stefanie and Jaakkola, Tommi S},
    booktitle={International Conference on Artificial Intelligence and Statistics},
    pages={1870--1879},
    year={2019}
  }
---
