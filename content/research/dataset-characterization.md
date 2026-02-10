---
title: "Dataset Characterization & Geometry"
description: "Understanding what makes data valuable for learning through geometry and optimal transport"
weight: 1
---

## Overview

What makes a dataset valuable for machine learning? We develop principled metrics and methods to characterize the intrinsic properties of datasets—such as compressibility, diversity, symmetry, and geometric structure—that predict their utility for learning.

Rather than treating data quality as a vague notion, we formalize it through the lens of **optimal transport** and **information geometry**, enabling rigorous comparison, analysis, and selection of training data.

## Key Questions

- How can we measure the "distance" between datasets in a way that predicts transfer learning success?
- What geometric properties of data distributions affect generalization?
- How do dataset diversity and complexity interact to shape model behavior?

## Methods & Tools

- **Optimal Transport**: Using Wasserstein distances and transport plans to compare and align datasets
- **Geometric Embeddings**: Characterizing data manifolds and their properties
- **Information-Theoretic Metrics**: Compressibility, redundancy, and mutual information as proxies for data value

## Selected Publications

- [Geometric Dataset Distances via Optimal Transport](/publications/otdd-2020/) (NeurIPS 2020)
- [Towards Optimal Transport with Global Invariances](/publications/ot-invariances-2019/) (AISTATS 2019)
- [Sometimes I am a Tree: Data Drives Unstable Hierarchical Generalization](/publications/sometimes-i-am-a-tree-2024/)
- [A Label is Worth a Thousand Images in Dataset Distillation](/publications/label-worth-thousand-2024/) (NeurIPS 2024)
