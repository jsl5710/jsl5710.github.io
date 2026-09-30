---
title: 'Lost in Speech: Trilingual Spoken Hallucination Detection Across Audio and Transcripts'

# Authors
authors:
  - Meruyert Aristombayeva
  - admin
  - Chaewan Chun
  - Dongwon Lee

# Acceptance date, matching the convention used by the other entries here
# (DIA-HARM is dated to acceptance, not to ACL). A conference-day date
# would be in the future and Hugo drops future-dated pages from the build.
date: '2026-09-20T00:00:00Z'

# Publication type.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
# Quoted: the value contains a colon, which bare YAML would read as a mapping.
publication: "In *Proceedings of the 2nd Workshop on Speech and Audio Language Models (SALMA 2026)*, co-located with EMNLP '26"
publication_short: SALMA @ EMNLP 2026

# TODO: replace with the camera-ready abstract.
abstract: "Hallucination detection is well studied for written text and far less so for speech, where the same claim reaches a listener through audio rather than a transcript. This work examines spoken hallucination detection across three languages, comparing what is recoverable from the audio signal against what survives transcription. Separating the two matters: transcription discards prosody, hesitation and disfluency that may carry signal, while introducing recognition errors of its own — so a detector's apparent accuracy depends heavily on which representation it is given, and on how well speech recognition serves the language in question."

# Summary
summary: "Trilingual spoken hallucination detection, comparing what is detectable from raw audio against what survives transcription."

tags: [Speech, Hallucination Detection, Multilingual, Audio Language Models, Information Integrity]

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
  - multilingual-nlp

slides: ""
---

Accepted to the **2nd Workshop on Speech and Audio Language Models (SALMA 2026)**,
co-located with EMNLP 2026 in Budapest, Hungary, 24–29 October 2026.

Most hallucination benchmarks assume text. **Lost in Speech** asks what changes when
the claim arrives as audio — and works across three languages rather than one, since
the answer depends on how well speech recognition serves each of them.

The comparison between audio and transcript is the point. Transcription throws away
prosody, hesitation and disfluency that may carry signal about whether a speaker is
fabricating, while adding recognition errors of its own. A detector evaluated only on
transcripts can therefore look better or worse than it really is, and that gap is
widest exactly where ASR is weakest — the low-resource languages that most need the
detector to work.
