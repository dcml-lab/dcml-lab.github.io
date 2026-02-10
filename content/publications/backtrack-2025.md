---
title: "To Backtrack or Not to Backtrack: When Sequential Search Limits Model Reasoning"
authors: "Tian Qin, David Alvarez-Melis, Samy Jelassi, Eran Malach"
venue: "COLM"
year: 2025
arxiv: "https://arxiv.org/abs/2504.07052"
pdf: "https://arxiv.org/pdf/2504.07052"
code: "https://github.com/KempnerInstitute/Backtrack"
hero_image: "/img/publications/backtrack-hero.png"
summary: "Backtracking isn't always better—we show sequential search underperforms parallel sampling on some tasks while excelling on others. The culprit? Fixed search traces and explicit chain-of-thought supervision can actually hurt LLM reasoning."
abstract: |
  Recent advancements in large language models (LLMs) have significantly improved their reasoning abilities, particularly through techniques involving search and backtracking. Backtracking naturally scales test-time compute by enabling sequential, linearized exploration via long chain-of-thought (CoT) generation. However, this is not the only strategy for scaling test time-compute: parallel sampling with best-of-N selection provides an alternative that generates diverse solutions simultaneously. Despite the growing adoption of sequential search, its advantages over parallel sampling—especially under a fixed compute budget—remain poorly understood. In this paper, we systematically compare these two approaches on two challenging reasoning tasks: CountDown and Sudoku. Surprisingly, we find that sequential search underperforms parallel sampling on CountDown but outperforms it on Sudoku, suggesting that backtracking is not universally beneficial.
bibtex: |
  @inproceedings{qin2025backtrack,
    title={To Backtrack or Not to Backtrack: When Sequential Search Limits Model Reasoning},
    author={Qin, Tian and Alvarez-Melis, David and Jelassi, Samy and Malach, Eran},
    booktitle={Conference on Language Modeling},
    year={2025}
  }
---
