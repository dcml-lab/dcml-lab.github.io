---
title: "Adaptive & Reconfigurable Models"
description: "Dynamically combining and adapting models based on constraints and objectives"
weight: 4
---

## Overview

Can we build models that **morph and adapt** without expensive retraining? We develop methods to combine, interpolate, and reconfigure model architectures dynamically—enabling flexible systems that adjust to new constraints, domains, or objectives on the fly.

This includes techniques for **model merging**, **weight-space interpolation**, **inference-time ensembling**, and **tokenizer adaptation**, allowing practitioners to compose and customize models for specific needs.

## Key Questions

- How can we interpolate between models of different sizes without retraining?
- Can we ensemble models with incompatible tokenizers at inference time?
- How do we adapt pre-trained models to new domains with minimal overhead?

## Methods & Tools

- **Knowledge Distillation**: Transferring capabilities between models of different sizes
- **Weight Interpolation**: Continuous traversal of model space for controllable behavior
- **Inference-Time Ensembling**: Combining diverse models without shared vocabularies
- **Tokenizer Adaptation**: Translating between tokenization schemes for domain transfer

## Selected Publications

- [Boomerang Distillation Enables Zero-Shot Model Size Interpolation](/publications/boomerang-distillation-enables-zero-shot-model-siz/) (arXiv 2025)
- [Continuous Language Model Interpolation for Dynamic and Controllable Text Generation](/publications/lm-interpolation-2025/) (TMLR 2025)
- [CharED: Character-wise Ensemble Decoding for Large Language Models](/publications/chared-2024/) (arXiv 2024)
- [S2T2: Sparse Sinkhorn Token Translation for Domain Adaptation](/publications/s2t2-2024/) (arXiv 2024)
