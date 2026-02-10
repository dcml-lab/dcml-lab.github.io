---
title: "Sometimes I am a Tree: Data Drives Unstable Hierarchical Generalization"
authors: "Tian Qin, Naomi Saphra, David Alvarez-Melis"
venue: "EMNLP"
year: 2025
arxiv: "https://arxiv.org/abs/2412.04619"
pdf: "https://arxiv.org/pdf/2412.04619.pdf"
hero_image: "/img/publications/sometimes-tree-hero.png"
summary: "Why do LLMs sometimes learn hierarchical syntax and sometimes fall back to n-gram shortcuts? The answer is in the data: complex structures (like center-embedded clauses) push models toward tree-based rules, while diversity determines whether they learn rules at all."
abstract: |
  Early in training, LMs can behave like n-gram models, but eventually they often learn tree-based syntactic rules and generalize hierarchically out of distribution (OOD). We study this shift using controlled grammar-learning tasks: question formation and tense inflection. We find that a model learns to generalize hierarchically if its training data is complex—in particular, if it includes center-embedded clauses, a special syntactic structure. Under this definition, complex data drives hierarchical rules, while less complex data encourages shortcut learning in the form of n-gram-like linear rules. Furthermore, we find that a model uses rules to generalize, whether hierarchical or linear, if its training data is diverse. Intermediate diversity and intermediate complexity form an unstable regime, characterized by oscillatory learning dynamics and inconsistent behaviors across random seeds.
bibtex: |
  @inproceedings{qin2025sometimes,
    title={Sometimes I am a Tree: Data Drives Unstable Hierarchical Generalization},
    author={Qin, Tian and Saphra, Naomi and Alvarez-Melis, David},
    booktitle={Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing},
    year={2025}
  }
---
