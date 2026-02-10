---
title: "Continuous Language Model Interpolation for Dynamic and Controllable Text Generation"
authors: "Sara Kangaslahti, David Alvarez-Melis"
venue: "TMLR"
year: 2025
arxiv: "https://arxiv.org/abs/2404.07117"
pdf: "https://arxiv.org/pdf/2404.07117"
hero_image: "/img/publications/lm-interpolation-hero.png"
summary: "We turn weight interpolation into a continuous control mechanism for LLMs—fine-tune anchor models for different styles, then smoothly blend their weights to get any personality on-the-fly. The result: predictable, fine-grained control over multiple text attributes simultaneously."
abstract: |
  As large language models (LLMs) have gained popularity for a variety of use cases, making them adaptable and controllable has become increasingly important, especially for user-facing applications. While the existing literature on LLM adaptation primarily focuses on finding a model (or models) that optimizes a single predefined objective, here we focus on the challenging case where the model must dynamically adapt to diverse—and often changing—user preferences. For this, we leverage adaptation methods based on linear weight interpolation, casting them as continuous multi-domain interpolators that produce models with specific prescribed generation characteristics on-the-fly. Specifically, we use low-rank updates to fine-tune a base model to various different domains, yielding a set of anchor models with distinct generation profiles. Then, we use the weight updates of these anchor models to parametrize the entire (infinite) class of models contained within their convex hull. We empirically show that varying the interpolation weights yields predictable and consistent change in the model outputs with respect to all of the controlled attributes.
bibtex: |
  @article{kangaslahti2025continuous,
    title={Continuous Language Model Interpolation for Dynamic and Controllable Text Generation},
    author={Kangaslahti, Sara and Alvarez-Melis, David},
    journal={Transactions on Machine Learning Research},
    year={2025}
  }
---
