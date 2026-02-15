---
title: 'BLUFF: Benchmarking in Low-resoUrce Languages for detecting Falsehoods and Fake news'

# Authors
authors:
  - admin
  - Matt Murtagh-White
  - Adaku Uchendu
  - Ali Al-Lawati
  - Michiharu Yamashita
  - Dominik Macko
  - Ivan Srba
  - Robert Moro
  - Dongwon Lee

date: '2026-02-01T00:00:00Z'
# doi: ''

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Under Review 2026 — Datasets and Benchmarks Track
publication_short: Under Review

abstract: Multilingual falsehoods threaten information integrity worldwide, yet detection benchmarks remain confined to English or a few high-resource languages, leaving low-resource linguistic communities without robust defense tools. We introduce BLUFF (Benchmarking in Low-resoUrce Languages for detecting Falsehoods and Fake news), a comprehensive benchmark for detecting false and synthetic content, spanning 79 languages with over 202K samples, combining human-written fact-checked content (122K+ samples across 57 languages) and LLM-generated content (79K+ samples across 71 languages). BLUFF uniquely covers both high-resource "big-head" (20) and low-resource "long-tail" (59) languages, addressing critical gaps in multilingual research on detecting false and synthetic content. Our dataset features four content types (human-written, LLM-generated, LLM-translated, and hybrid human-LLM text), bidirectional translation (English↔X), 39 textual modification techniques, and varying edit intensities generated using 19 diverse LLMs. We present AXL-CoI (Adversarial Cross-Lingual Agentic Chain-of-Interactions), a novel multi-agentic framework for controlled fake/real news generation, paired with mPURIFY, a quality filtering pipeline ensuring dataset integrity. Experiments reveal state-of-the-art detectors suffer up to 25.3% F1 degradation on low-resource versus high-resource languages.

# Summary
summary: BLUFF is the largest multilingual fake news detection benchmark, spanning 79 languages with 202K+ samples. It introduces AXL-CoI for adversarial generation and mPURIFY for quality filtering, revealing up to 25.3% F1 degradation on low-resource languages.

tags: [Multilingual NLP, Fake News Detection, Benchmark, Adversarial ML, Low-Resource Languages]

# Display this page in the Featured widget?
featured: true

url_pdf: ''
url_code: 'https://github.com/jsl5710/BLUFF'
url_dataset: 'https://huggingface.co/datasets/jsl5710/BLUFF'
url_poster: ''
url_project: 'https://jsl5710.github.io/BLUFF'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
image:
  caption: 'BLUFF Framework Overview'
  focal_point: ''
  preview_only: false

# Associated Projects
projects:
  - bluff

slides: ""
---

**BLUFF** is the largest multilingual fake news detection benchmark to date, spanning **79 languages** (20 high-resource "big-head" + 59 low-resource "long-tail") with over **202,000 samples**. The benchmark combines human-written fact-checked content from 130 IFCN-certified organizations with LLM-generated content from 19 diverse models.

Key contributions include:
- **AXL-CoI** (Adversarial Cross-Lingual Agentic Chain-of-Interactions): A multi-agentic framework using 10 fake chains and 8 real chains for controlled multilingual content generation
- **mPURIFY**: A 4-stage quality filtering pipeline with 32 features across 5 dimensions, ensuring dataset integrity through asymmetric evaluation thresholds
- **Bidirectional translation**: English↔X coverage across 70+ languages with 4 prompt variants
- **Comprehensive evaluation**: State-of-the-art detectors suffer up to 25.3% Macro-F1 degradation on low-resource versus high-resource languages

Resources:
- [Project Page](https://jsl5710.github.io/BLUFF)
- [GitHub Repository](https://github.com/jsl5710/BLUFF)
- [HuggingFace Dataset](https://huggingface.co/datasets/jsl5710/BLUFF)
