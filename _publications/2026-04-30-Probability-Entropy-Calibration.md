---
title: "Probability-Entropy Calibration: An Elastic Indicator for Adaptive Fine-tuning"
collection: publications
permalink: /publication/2026-04-30-Probability-Entropy-Calibration
date: 2026-04-30
venue: 'ICML 2026'
paperurl: 'https://arxiv.org/abs/2602.01745'
authors: 'Wenhao Yu, Shaohang Wei, Jiahong Liu, <b>Yifan Li</b>, Minda Hu, Aiwei Liu, Hao Zhang, Irwin King'
---

Token-level reweighting is a simple yet effective mechanism for controlling supervised fine-tuning, but common indicators are largely one-dimensional: the ground-truth probability reflects downstream alignment, while token entropy reflects intrinsic uncertainty induced by the pre-training prior. Ignoring entropy can misidentify noisy or easily replaceable tokens as learning-critical, while ignoring probability fails to reflect target-specific alignment. RankTuner introduces a probability--entropy calibration signal, the Relative Rank Indicator, which compares the rank of the ground-truth token with its expected rank under the prediction distribution. The inverse indicator is used as a token-wise Relative Scale to reweight the fine-tuning objective, focusing updates on truly under-learned tokens without over-penalizing intrinsically uncertain positions. Experiments on multiple backbones show consistent improvements on mathematical reasoning benchmarks, transfer gains on out-of-distribution reasoning, and pre code generation performance over probability-only or entropy-only reweighting baselines.
