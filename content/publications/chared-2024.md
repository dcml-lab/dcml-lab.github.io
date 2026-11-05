---
title: "CharED: Character-wise Ensemble Decoding for Large Language Models"
authors: "Kevin Gu, Eva Tuecke, Dmitriy Katz, Raya Horesh, David Alvarez-Melis, Mikhail Yurochkin"
venue: "FM-Wild @ ICML"
year: 2024
arxiv: "https://arxiv.org/abs/2407.11009"
pdf: "https://arxiv.org/pdf/2407.11009.pdf"
hero_image: "/img/publications/chared-hero.png"
summary: "How do you ensemble LLMs with completely different tokenizers? We decode character-by-character, averaging the marginal distribution over characters across models. CharED combines complementary strengths regardless of vocabulary, tokenization, or model size."
abstract: |
  Large language models (LLMs) have shown remarkable potential for problem solving, with open source models achieving increasingly impressive performance on benchmarks measuring areas from logical reasoning to mathematical ability. Ensembling models can further improve capabilities across a variety of domains. However, conventional methods of combining models at inference time such as shallow fusion necessitate a shared vocabulary and tokenization, and alternatives like fine-tuning for domain-specific performance are both time consuming and computationally expensive. We therefore present an inference-time ensembling algorithm aimed at "averaging" outputs from multiple LLMs and illustrate its improved performance across multiple domains compared to its constituent models alone. Character-wise ensemble decoding, CharED, finds the marginal distribution of each character for an individual model and performs a weighted average to generate an output, character by character.
bibtex: |
  @inproceedings{gu2024chared,
    title         = {{CharED}: Character-wise Ensemble Decoding for Large Language Models},
    author        = {Gu, Kevin and Tuecke, Eva and Katz, Dmitriy and Horesh, Raya and Alvarez-Melis, David and Yurochkin, Mikhail},
    booktitle     = {ICML 2024 Workshop on Foundation Models in the Wild},
    year          = {2024},
    eprint        = {2407.11009},
    archivePrefix = {arXiv},
    url           = {https://arxiv.org/abs/2407.11009}
  }
---
