---
title: BLUFF - Multilingual Fake News Detection Benchmark
summary: Benchmarking in Low-resoUrce Languages for detecting Falsehoods and Fake news. 79 languages, 202K+ samples, 19 LLMs.
tags:
  - Deep Learning
  - Multilingual NLP
  - Fake News Detection
date: '2026-02-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: BLUFF Framework Overview
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Code & Docs
    url: https://github.com/jsl5710/BLUFF
  - icon: globe
    icon_pack: fas
    name: Project Page
    url: https://jsl5710.github.io/BLUFF
  - name: Dataset
    url: https://huggingface.co/datasets/jsl5710/BLUFF
url_code: 'https://github.com/jsl5710/BLUFF'
url_pdf: ''
url_slides: ''
url_video: ''

slides: ""
---

**BLUFF** (Benchmarking in Low-resoUrce Languages for detecting Falsehoods and Fake news) is the largest multilingual fake news detection benchmark, spanning **79 languages** with over **202,000 samples**. It addresses critical gaps in multilingual falsehood detection research by covering both high-resource "big-head" (20) and low-resource "long-tail" (59) languages.

The benchmark introduces two novel frameworks:

1. **AXL-CoI** (Adversarial Cross-Lingual Agentic Chain-of-Interactions) — A multi-agentic pipeline that orchestrates 10 fake chains and 8 real chains for controlled multilingual content generation using 19 diverse LLMs (13 instruction-tuned + 6 reasoning models).

2. **mPURIFY** — A 4-stage multilingual quality filtering pipeline with 32 features across 5 evaluation dimensions, using asymmetric thresholds to ensure dataset integrity.

Key features include:
- **Four content types**: Human-Written (HWT), Machine-Generated (MGT), Machine-Translated (MTT), and Human-Adapted Text (HAT)
- **Bidirectional translation**: English↔X with 4 prompt variants across 70+ languages
- **39 textual modification techniques** with varying edit intensities
- **Human-written data** from 130 IFCN-certified fact-checking organizations across 57 languages

Experiments reveal state-of-the-art detectors suffer up to **25.3% F1 degradation** on low-resource versus high-resource languages, highlighting the urgent need for equitable multilingual detection tools.
