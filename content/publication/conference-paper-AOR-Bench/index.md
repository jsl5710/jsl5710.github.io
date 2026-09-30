---
title: 'AOR-Bench: Do Large Audio Language Models Over-Refuse Pseudo-Harmful Queries?'

# Authors
authors:
  - Jiaxi Yang
  - Chaewan Chun
  - admin
  - Yuchen Yang
  - Dongwon Lee

# Acceptance date, matching the convention used by the other entries here
# (DIA-HARM is dated to acceptance, not to ACL). A conference-day date
# would be in the future and Hugo drops future-dated pages from the build.
date: '2026-09-20T00:00:00Z'

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
# Quoted: the value contains a colon, which bare YAML would read as a mapping.
publication: "In *Proceedings of the 2026 Conference on Empirical Methods in Natural Language Processing (EMNLP '26)*"
publication_short: EMNLP 2026

# TODO: replace with the camera-ready abstract.
abstract: "Safety alignment teaches models to refuse harmful requests, but an over-aligned model also refuses benign ones that merely resemble harmful queries. AOR-Bench examines this over-refusal behaviour in large audio language models, where the speech channel adds failure modes that text-only evaluation cannot surface: accent, prosody and acoustic ambiguity can all push a pseudo-harmful query across a refusal boundary. The benchmark measures how often audio models decline queries that are in fact safe, and what acoustic and linguistic factors drive those refusals."

# Summary
summary: "A benchmark for over-refusal in large audio language models — how often they decline pseudo-harmful but benign spoken queries, and what drives it."

tags: [Audio Language Models, AI Safety, Over-Refusal, Speech, Benchmark]

# Display this page in the Featured widget?
featured: true

links:
  - type: site
    url: 'https://2026.emnlp.org/'

# Featured image
image:
  caption: ''
  focal_point: ''
  preview_only: true

# Associated Projects
projects:
  - ai-robustness

slides: ""
---

Accepted to **EMNLP 2026**, Budapest, Hungary, 24–29 October 2026.

**AOR-Bench** asks a question that safety evaluation usually skips: not whether a
model refuses harmful requests, but whether it refuses *safe* ones that happen to
look harmful.

Over-refusal is a real cost of alignment. A model that declines benign queries is
less useful, and the burden does not fall evenly — speakers whose accent, dialect or
phrasing sits further from the training distribution are more likely to be refused.
In the audio setting that risk grows, because prosody and acoustic ambiguity give the
model more ways to misread intent than text alone provides.
