---
title: 'BLUFF Accepted at KDD 2026 (Datasets and Benchmarks Track)'
date: '2026-05-15'
summary: Our BLUFF benchmark — spanning 79 languages and 202K+ samples — has been accepted at the 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2026), Datasets and Benchmarks Track.
image:
  focal_point: Smart
  preview_only: false
---

Excited to share that our paper **BLUFF: Benchmarking in Low-resoUrce Languages for detecting Falsehoods and Fake news** has been accepted at the **32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2026)** in the **Datasets and Benchmarks Track**!

**BLUFF** is the largest multilingual fake news detection benchmark to date, spanning:

- **79 languages** — 20 high-resource "big-head" + 59 low-resource "long-tail"
- **202K+ samples** combining fact-checked content from 130 IFCN-certified organizations and LLM-generated content from 19 diverse models
- **AXL-CoI** (Adversarial Cross-Lingual Agentic Chain-of-Interactions) — a multi-agentic framework for controlled multilingual content generation
- **mPURIFY** — a 4-stage quality filtering pipeline ensuring dataset integrity
- **Bidirectional translation** coverage across 70+ languages with 4 prompt variants

Our experiments reveal state-of-the-art detectors suffer up to **25.3% Macro-F1 degradation** on low-resource versus high-resource languages — a systematic, not marginal, gap. This is the digital language divide manifest in detection systems: the communities least represented in training data are also the least protected from AI-generated disinformation.

Deeply grateful to my co-authors: **Matt Murtagh-White, Adaku Uchendu, Ali Al-Lawati, Michiharu Yamashita, Dominik Macko, Ivan Srba, Robert Moro**, and my advisor **Dr. Dongwon Lee**. Special thanks to our collaborators at Kempelen Institute of Intelligent Technologies (KInIT) and MIT Lincoln Laboratory.

Resources:
- [arXiv Paper](https://arxiv.org/abs/2603.00634)
- [Project Page](https://jsl5710.github.io/BLUFF)
- [GitHub Repository](https://github.com/jsl5710/BLUFF)
- [HuggingFace Dataset](https://huggingface.co/datasets/jsl5710/BLUFF)
- [Earlier Slator coverage](https://slator.com/ai-detection-across-languages/)

See you in **Toronto for KDD 2026**! 🍁
