---
title: "Generating Synthetic Datasets by Interpolating along Generalized Geodesics"
authors: "Jiaojiao Fan, David Alvarez-Melis"
venue: "UAI"
year: 2023
arxiv: "https://arxiv.org/abs/2306.06866"
pdf: "https://arxiv.org/pdf/2306.06866.pdf"
hero_image: "/img/publications/geodesic-hero.png"
summary: "What if you could create new datasets by 'blending' existing ones along optimal transport geodesics? We show how to interpolate between datasets—even with completely different labels—to synthesize targeted training data for transfer learning."
abstract: |
  Data for pretraining machine learning models often consists of collections of heterogeneous datasets. Although training on their union is reasonable in agnostic settings, it might be suboptimal when the target domain—where the model will ultimately be used—is known in advance. In that case, one would ideally pretrain only on the dataset(s) most similar to the target one. Instead of limiting this choice to those datasets already present in the pretraining collection, here we explore extending this search to all datasets that can be synthesized as 'combinations' of them. We define such combinations as multi-dataset interpolations, formalized through the notion of generalized geodesics from optimal transport (OT) theory. We compute these geodesics using a recent notion of distance between labeled datasets, and derive alternative interpolation schemes based on it: using either barycentric projections or optimal transport maps, the latter computed using recent neural OT methods.
bibtex: |
  @inproceedings{fan2023generating,
    title={Generating Synthetic Datasets by Interpolating along Generalized Geodesics},
    author={Fan, Jiaojiao and Alvarez-Melis, David},
    booktitle={Conference on Uncertainty in Artificial Intelligence},
    year={2023}
  }
---
