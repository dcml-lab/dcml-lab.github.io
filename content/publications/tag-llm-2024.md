---
title: "Tag-LLM: Repurposing General-Purpose LLMs for Specialized Domains"
authors: "Junhong Shen, Neil Tenenholtz, James Brian Hall, David Alvarez-Melis, Liam Li"
venue: "ICML"
year: 2024
arxiv: "https://arxiv.org/abs/2402.05140"
pdf: "https://arxiv.org/pdf/2402.05140.pdf"
proceedings: "https://proceedings.mlr.press/v235/shen24d.html"
code: "https://github.com/sjunhongshen/Tag-LLM"
hero_image: "/img/publications/tag-llm-hero.png"
summary: "General LLMs struggle in specialized domains like chemistry and biology. We introduce learnable 'tags'—domain tags for context and function tags for tasks—that condition LLMs without retraining, enabling zero-shot generalization to new scientific problems."
abstract: |
  Large Language Models (LLMs) have demonstrated remarkable proficiency in understanding and generating natural language. However, their capabilities wane in highly specialized domains underrepresented in the pretraining corpus, such as physical and biomedical sciences. This work explores how to repurpose general LLMs into effective task solvers for specialized domains. We introduce a novel, model-agnostic framework for learning custom input tags, which are parameterized as continuous vectors appended to the LLM's embedding layer, to condition the LLM. We design two types of input tags: domain tags are used to delimit specialized representations (e.g., chemical formulas) and provide domain-relevant context; function tags are used to represent specific functions (e.g., predicting molecular properties) and compress function-solving instructions.
bibtex: |
  @inproceedings{shen2024tagllm,
    title={Tag-LLM: Repurposing General-Purpose LLMs for Specialized Domains},
    author={Shen, Junhong and Tenenholtz, Neil and Hall, James Brian and Alvarez-Melis, David and Li, Liam},
    booktitle={International Conference on Machine Learning},
    year={2024}
  }
---
