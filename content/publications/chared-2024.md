---
title: "CharED: Character-wise Ensemble Decoding for Large Language Models"
authors: "Eva Tuecke, Marzyeh Ghassemi, David Alvarez-Melis"
venue: "arXiv preprint"
year: 2024
arxiv: "https://arxiv.org/abs/2407.11009"
pdf: "https://arxiv.org/pdf/2407.11009.pdf"
hero_image: "/img/publications/chared-hero.png"
summary: "How do you ensemble LLMs with completely different tokenizers? We decode character-by-character, averaging the marginal distribution over characters across models. CharED combines complementary strengths regardless of vocabulary, tokenization, or model size."
abstract: |
  Large language models (LLMs) have shown remarkable potential for problem solving, with open source models achieving increasingly impressive performance on benchmarks measuring areas from logical reasoning to mathematical ability. Ensembling models can further improve capabilities across a variety of domains. However, conventional methods of combining models at inference time such as shallow fusion necessitate a shared vocabulary and tokenization, and alternatives like fine-tuning for domain-specific performance are both time consuming and computationally expensive. We therefore present an inference-time ensembling algorithm aimed at "averaging" outputs from multiple LLMs and illustrate its improved performance across multiple domains compared to its constituent models alone. Character-wise ensemble decoding, CharED, finds the marginal distribution of each character for an individual model and performs a weighted average to generate an output, character by character.
bibtex: |
  @article{tuecke2024chared,
    title={CharED: Character-wise Ensemble Decoding for Large Language Models},
    author={Tuecke, Eva and Ghassemi, Marzyeh and Alvarez-Melis, David},
    journal={arXiv preprint arXiv:2407.11009},
    year={2024}
  }
---
