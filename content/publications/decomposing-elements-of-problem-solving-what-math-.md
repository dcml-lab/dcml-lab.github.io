---
title: 'Decomposing Elements of Problem Solving: What "Math" Does RL Teach?'
authors: "Tian Qin, Core Francisco Park, Mujin Kwun, Aaron Walsman, Eran Malach, Nikhil Anand, Hidenori Tanaka, David Alvarez-Melis"
venue: "arXiv preprint"
year: 2025
arxiv: "https://arxiv.org/abs/2505.22756"
pdf: "https://arxiv.org/pdf/2505.22756.pdf"
code: "https://github.com/cfpark00/RL-Wall"
hero_image: "/img/publications/rl-math-hero.png"
summary: "RL makes LLMs better at math—but at what exactly? We decompose problem-solving into Plan, Execute, and Verify, and find RL mainly improves execution robustness on known problems. New problems hit a 'coverage wall' due to weak planning."
abstract: |
  Mathematical reasoning tasks have become prominent benchmarks for assessing the reasoning capabilities of LLMs, especially with reinforcement learning (RL) methods such as GRPO showing significant performance gains. However, accuracy metrics alone do not support fine-grained assessment of capabilities and fail to reveal which problem-solving skills have been internalized. To better understand these capabilities, we propose to decompose problem solving into fundamental capabilities: Plan (mapping questions to sequences of steps), Execute (correctly performing solution steps), and Verify (identifying the correctness of a solution). Empirically, we find that GRPO mainly enhances the execution skill—improving execution robustness on problems the model already knows how to solve—a phenomenon we call temperature distillation.
bibtex: |
  @article{qin2025decomposing,
    title={Decomposing Elements of Problem Solving: What "Math" Does RL Teach?},
    author={Qin, Tian and Park, Core Francisco and Kwun, Mujin and Walsman, Aaron and Malach, Eran and Anand, Nikhil and Tanaka, Hidenori and Alvarez-Melis, David},
    journal={arXiv preprint arXiv:2505.22756},
    year={2025}
  }
---
