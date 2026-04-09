---
title: 'DIA-HARM: Dialectal Disparities in Harmful Content Detection Across 50 English Dialects'

# Authors
authors:
  - admin
  - Matt Murtagh-White
  - Ali Al-Lawati
  - Uchendu Uchendu
  - Adaku Uchendu
  - Dongwon Lee

date: '2026-04-08T00:00:00Z'
# doi: ''

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics (ACL 2026), Main Conference*
publication_short: ACL 2026

abstract: Harmful content detectors—particularly disinformation classifiers—are predominantly developed and evaluated on Standard American English (SAE), leaving their robustness to dialectal variation unexplored. We present DIA-HARM, the first benchmark for evaluating disinformation detection robustness across 50 English dialects spanning U.S., British, African, Caribbean, and Asia-Pacific varieties. Using Multi-VALUE's linguistically grounded transformations, we introduce D3 (Dialectal Disinformation Detection), a corpus of 195K samples derived from established disinformation benchmarks. Our evaluation of 16 detection models reveals systematic vulnerabilities&#58; human-written dialectal content degrades detection by 1.4–3.6% F1, while AI-generated content remains stable. Fine-tuned transformers substantially outperform zero-shot LLMs (96.6% vs. 78.3% best-case F1), with some models exhibiting catastrophic failures exceeding 33% degradation on mixed content. Cross-dialectal transfer analysis across 2,450 dialect pairs shows that multilingual models (mDeBERTa&#58; 97.2% average F1) generalize effectively, while monolingual models like RoBERTa and XLM-RoBERTa fail on dialectal inputs. These findings demonstrate that current disinformation detectors may systematically disadvantage hundreds of millions of non-SAE speakers worldwide. We release the DIA-HARM framework, D3 corpus, and evaluation tools.

# Summary
summary: DIA-HARM evaluates 16 harmful content detection models across 50 English dialects using 195K+ samples, revealing 1.4–3.6% F1 drops for fine-tuned models and up to 27% for zero-shot approaches, highlighting equity gaps in content moderation.

tags: [Harmful Content Detection, Dialect Robustness, NLP, Content Moderation, Linguistic Diversity]

# Display this page in the Featured widget?
featured: true

url_pdf: 'https://arxiv.org/pdf/2604.05318'
url_code: 'https://github.com/jsl5710/dia-harm/tree/main'
url_dataset: ''
url_poster: 'poster.pdf'
url_project: 'https://jsl5710.github.io/dia-harm'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
image:
  caption: 'DIA-HARM Framework Overview'
  focal_point: ''
  preview_only: false

# Associated Projects
projects:
  - ai-robustness

slides: ""
---

**DIA-HARM** investigates the robustness of harmful content detection systems across **50 English dialects**, addressing critical equity gaps in automated content moderation.

Key contributions include:
- **Dialect-Diverse Detection (D3) Corpus**: Over 195K samples derived from benchmark harmful content datasets, transformed using 189 morphosyntactic rules from eWAVE covering 50 dialects
- **Comprehensive Model Evaluation**: 16 detection models tested — 10 fine-tuned, 5 zero-shot, and 1 in-context learning — revealing systematic performance disparities across dialect groups
- **D-PURIFY Validation**: Quality filtering pipeline ensuring linguistic validity of dialect transformations with 97.2% average F1 for the best model (mDeBERTa)
- **Key Finding**: Detection degradation correlates with density of morphosyntactic transformations rather than specific dialect features, with 2,450 dialect pairs analyzed

Resources:
- [arXiv Paper](https://arxiv.org/abs/2604.05318)
- [Project Page](https://jsl5710.github.io/dia-harm)
- [GitHub Repository](https://github.com/jsl5710/dia-harm/tree/main)
