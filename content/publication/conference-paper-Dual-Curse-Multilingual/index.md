---
title: 'Position: Breaking the Dual Curse of Multilingual AI Requires Socio-Technical Guardrails, Not Post-Hoc Alignment'

# Authors
authors:
  - admin
  - Pureheart Ogheneogaga Irikefe
  - Adaku Uchendu
  - Umniya Najaer
  - Cornelius Adejoro
  - Patrice Sterling
  - Dongwon Lee

date: '2026-07-13T00:00:00Z'
# doi: ''

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 43rd International Conference on Machine Learning* — Position Paper Track
publication_short: In *ICML*

abstract: Multilingual language models exhibit a dual curse — harmful content generation rises to 35% in low-resource languages (versus 1% in English), while instruction-following capability drops sharply across the same languages. Our systematic analysis of 207 studies reveals that reward models achieve only 49–50% accuracy in low-resource languages, equivalent to random chance, undermining the reliability of post-deployment safety measures. In this position paper, we argue that safety in multilingual AI cannot be retrofitted through post-hoc alignment. Instead, closing the divide requires socio-technical guardrails built in from the ground up — pre-training interventions, community-led harm specification, and multilingual evaluation metrics that jointly balance security and usability. We call on the community to treat multilingual safety as a design constraint, not a downstream patch.

# Summary
summary: A position paper arguing that the dual curse of multilingual AI — 35% harmful generation and near-random reward-model accuracy in low-resource languages — cannot be fixed by post-hoc alignment, and instead requires socio-technical guardrails, pre-training interventions, community-led harm specification, and multilingual safety-usability metrics.

tags: [Multilingual NLP, AI Safety, Position Paper, Low-Resource Languages, Socio-Technical AI, Alignment]

# Display this page in the Featured widget?
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://icml.cc/virtual/2026/poster/67071'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
image:
  caption: 'Breaking the Dual Curse of Multilingual AI'
  focal_point: ''
  preview_only: false

# Associated Projects
projects:
  - multilingual-nlp
  - equity-inclusion

slides: ""
---

**Position:** Multilingual AI safety cannot be retrofitted through post-hoc alignment. We identify a **dual curse** in current systems and argue for socio-technical guardrails built in from pre-training.

Key contributions:
- **Dual Curse documented**: Harmful content generation rises to **35% in low-resource languages** (vs. 1% in English), while instruction-following capability declines sharply across the same languages.
- **Systematic review of 207 studies**: Reward models achieve only **49–50% accuracy in low-resource languages** — equivalent to random chance — undermining post-deployment safety pipelines.
- **Socio-technical prescription**: Pre-training interventions, **community-led harm specification**, and multilingual evaluation metrics that balance security and usability jointly, rather than trading one off for the other.
- **Call to action**: Treat multilingual safety as a first-class design constraint, not a downstream patch applied through RLHF or filtering.

Resources:
- [ICML 2026 Poster Page](https://icml.cc/virtual/2026/poster/67071)
