---
title: 'DIA-HARM: Harmful Content Detection Robustness Across 50 English Dialects'

# Authors
authors:
  - admin
  - Matt Murtagh
  - Ali Al-Lawati
  - Uchendu Uchendu
  - Adaku Uchendu
  - Dongwon Lee

date: '2026-02-01T00:00:00Z'
# doi: ''

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Under Review 2026
publication_short: Under Review

abstract: As social media platforms expand globally, automated harmful content detection systems must effectively handle the linguistic diversity of their users. While these systems achieve strong performance on standardized text, their robustness across dialectal variations of English remains poorly understood. We investigate how 16 harmful content detection models perform across 50 English dialects using morphosyntactic transformations grounded in linguistic typology. Our work produces the Dialect-Diverse Detection (D3) corpus, comprising over 195K samples derived from benchmark harmful content datasets. Through systematic evaluation, we find that fine-tuned models experience 1.4–3.6% F1 degradation when processing dialectal text, while zero-shot and in-context learning approaches show up to 27% performance drops. Even the most robust fine-tuned model, mDeBERTa (average F1 of 97.2%), shows statistically significant performance disparities across dialect groups. Our analysis reveals that detection degradation correlates with the density of applied morphosyntactic transformations rather than specific dialect features, suggesting that model robustness may be more sensitive to cumulative surface-level variation than to particular linguistic phenomena. These findings highlight important equity considerations for content moderation systems serving linguistically diverse communities.

# Summary
summary: DIA-HARM evaluates 16 harmful content detection models across 50 English dialects using 195K+ samples, revealing 1.4–3.6% F1 drops for fine-tuned models and up to 27% for zero-shot approaches, highlighting equity gaps in content moderation.

tags: [Harmful Content Detection, Dialect Robustness, NLP, Content Moderation, Linguistic Diversity]

# Display this page in the Featured widget?
featured: true

url_pdf: ''
url_code: 'https://github.com/jsl5710/dia-harm/tree/main'
url_dataset: ''
url_poster: ''
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
projects: []

slides: ""
---

**DIA-HARM** investigates the robustness of harmful content detection systems across **50 English dialects**, addressing critical equity gaps in automated content moderation.

Key contributions include:
- **Dialect-Diverse Detection (D3) Corpus**: Over 195K samples derived from benchmark harmful content datasets, transformed using 189 morphosyntactic rules from eWAVE covering 50 dialects
- **Comprehensive Model Evaluation**: 16 detection models tested — 10 fine-tuned, 5 zero-shot, and 1 in-context learning — revealing systematic performance disparities across dialect groups
- **D-PURIFY Validation**: Quality filtering pipeline ensuring linguistic validity of dialect transformations with 97.2% average F1 for the best model (mDeBERTa)
- **Key Finding**: Detection degradation correlates with density of morphosyntactic transformations rather than specific dialect features, with 2,450 dialect pairs analyzed

Resources:
- [Project Page](https://jsl5710.github.io/dia-harm)
- [GitHub Repository](https://github.com/jsl5710/dia-harm/tree/main)
