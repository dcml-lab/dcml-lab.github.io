---
title: "Dataset Transformations & Training Dynamics"
description: "How data structure affects learning dynamics and model behavior during training"
weight: 2
---

## Overview

How does the structure of training data shape what models learn? We study the **dynamics** of learning from a data-centric perspective—understanding how datasets evolve under transformations and how their properties influence model behavior throughout training.

Using tools from **optimal transport** and **dynamical systems**, we analyze how data augmentation, filtering, and other transformations affect downstream performance, and how gradient flows can model dataset evolution.

## Key Questions

- How do common data transformations (augmentation, filtering, mixing) affect learning outcomes?
- What role does data structure play in phenomena like grokking, phase transitions, and emergent capabilities?
- Can we predict how changes to training data will affect model behavior?

## Methods & Tools

- **Wasserstein Gradient Flows**: Modeling dataset evolution as flows in probability space
- **Equilibrium Models**: Deep equilibrium architectures for processing distributional inputs
- **Training Dynamics Analysis**: Understanding learning trajectories through a data-centric lens

## Selected Publications

- [Dataset Dynamics via Gradient Flows in Probability Space](/publications/dataset-dynamics-2021/) (ICML 2021)
- [DDEQs: Distributional Deep Equilibrium Models through Wasserstein Gradient Flows](/publications/ddeqs-2025/) (AISTATS 2025)
- [Neural Unbalanced Optimal Transport via Cycle-Consistent Semi-Couplings](/publications/nuot-2022/)
- [Sometimes I am a Tree: Data Drives Unstable Hierarchical Generalization](/publications/sometimes-i-am-a-tree-2024/)
