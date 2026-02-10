---
title: "Dataset Optimization & Synthesis"
description: "Principled methods to reduce, enhance, and synthesize training data"
weight: 3
---

## Overview

Can we design better training datasets rather than just collecting more data? We develop **optimization-based methods** to create efficient, task-specific training sets—reducing redundancy, enhancing diversity, and synthesizing new data that maximizes learning outcomes.

Our approach leverages **gradient flows in probability space** and **geodesic interpolation** to transform and generate datasets in principled ways, enabling dramatic improvements in data efficiency.

## Key Questions

- How can we compress datasets while preserving (or improving) their training value?
- Can we synthesize new training data by interpolating between existing datasets?
- What are the fundamental limits of dataset reduction?

## Methods & Tools

- **Wasserstein Gradient Flows**: Optimizing datasets as distributions in probability space
- **Dataset Distillation**: Compressing large datasets into small, high-value synthetic sets
- **Geodesic Interpolation**: Generating new datasets along optimal transport paths between existing ones
- **Constrained Synthesis**: Creating data that satisfies domain-specific constraints (privacy, symmetry, etc.)

## Selected Publications

- [Dataset Dynamics via Gradient Flows in Probability Space](/publications/dataset-dynamics-2021/) (ICML 2021)
- [Generating Synthetic Datasets by Interpolating along Generalized Geodesics](/publications/geodesic-interpolation-2023/) (UAI 2023)
- [Distributional Dataset Distillation with Subtask Decomposition](/publications/distributional-distillation-2025/)
- [A Label is Worth a Thousand Images in Dataset Distillation](/publications/label-worth-thousand-2024/) (NeurIPS 2024)
- [To Backtrack or Not to Backtrack](/publications/backtrack-2025/) (COLM 2025)
