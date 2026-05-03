---
title: Research Statement
date: '2026-05-03'
authors: [admin]
summary: Vision, research questions, and the SEAL research program at CU Boulder.
---

*Jason Samuel Lucas · Assistant Professor of Information Science · University of Colorado Boulder · Director, Secure and Ethical AI Lab (SEAL)*

---

## Vision: Trustworthy AI Through Multilingual NLP and Security

The world is multilingual; its digital infrastructure is not. Of the roughly seven thousand languages spoken today, fewer than twenty account for the overwhelming majority of digital content, and English alone accounts for over half. This asymmetry, which I call the **digital language divide**, is the foundation of my research program: a gap between linguistic reality and digital representation that shapes who AI systems protect, who they fail, and who they leave exploitable.

Large language models have transformed how we process information, enabling sophisticated applications from machine translation to content generation. But the same advances create vulnerabilities. Adversaries weaponize AI to generate harmful content at scale. Information-based attacks undermine public trust and democratic institutions. Safety systems fail to protect diverse linguistic communities. My research addresses these challenges at the intersection of AI, NLP, and security, developing trustworthy AI systems that protect both technology and the communities that use it, regardless of language or resources.

## The Technical Problem

Modern LLMs are built through a three-phase training pipeline: **pre-training** for language semantics and syntax, **instruction-tuning** for human instruction-following, and **alignment-tuning** for human values and safety. Each phase inherits the long-tail distribution of its training data, where high-resource languages dominate and low-resource languages, dialects, and creoles sit at the margins. The result is a class of fundamental vulnerabilities that adversaries exploit: safety guardrails that fail in dialects they were never evaluated on, alignment that breaks under code-switching, and instruction-following that degrades in precisely the languages most exposed to harmful content online.

The communities affected are simultaneously **under-protected**, because the systems were not built to recognize harmful content in their varieties, and **over-exposed**, because the same gaps that produce inequitable protection produce exploitable attack surfaces. My work refuses the equity-safety separation: these are not parallel problems but the same problem manifesting on two faces of the digital language divide.

## Research Questions

My research program investigates three interconnected questions:

- **RQ1.** How can we understand and mitigate vulnerabilities in AI systems, particularly for security-critical applications?
- **RQ2.** How can we extend AI and NLP capabilities to low-resource multilingual communities?
- **RQ3.** Can we develop robust, trustworthy AI systems that maintain effectiveness against adaptive adversaries across languages, domains, and modalities?

## The Secure and Ethical AI Lab (SEAL)

These questions structure the work of the **Secure and Ethical AI Lab (SEAL)** at CU Boulder. SEAL builds AI systems that are safe, interpretable, and equitable across all languages and communities, advancing four interconnected research directions:

- **Multilingual NLP and Low-Resource AI.** Extending model capabilities to underserved languages, dialects, and creoles, with particular emphasis on Caribbean and African diaspora varieties historically absent from benchmark resources.
- **Trustworthy AI and Information Integrity.** Investigating how foundation models generate, propagate, and detect harmful content, building on my F3 framework (EMNLP 2023) for understanding the dual role of LLMs as both source and shield.
- **Ethical, Equitable, and Human-Centered AI.** Developing socio-technical frameworks for responsible model development, articulated through my *Dual Curse* theory connecting colonial epistemology to multilingual AI safety failures.
- **AI Safety and Robustness.** Building dialect-aware safety guardrails (DIA-Guard), contamination-resistant benchmarks (BLUFF), and adversarial evaluations that surface where models break before deployment does.

## Methodological Commitments

SEAL's work bridges AI innovation with security and equity, ensuring advances benefit all populations regardless of language or resources. Treating equity and safety as one problem rather than two yields different research choices: benchmarks built with affected communities rather than scraped around them, defense models distilled to run where the harm actually occurs, and evaluations designed to catch the failures that matter rather than the failures that are convenient to measure. The lab's methodology is interdisciplinary by necessity, spanning adversarial machine learning, multilingual NLP, knowledge distillation, and security systems, with deployment in diverse real-world contexts as the standard against which results are judged.

## Outlook

Over the next five to seven years, I will build SEAL into a hub for multilingual AI safety research, with sustained focus on contamination-resistant evaluation, dialect-robust safety conditioning, and AI systems for low-resource and Caribbean language communities. The work is supported through a portfolio that spans NSF programs, industry partnerships, and national-laboratory collaborations. The goal is concrete: AI systems whose protection extends to the speakers, dialects, and registers the field has historically left at the margins.

---

*Last updated: May 2026 · [Download CV](/uploads/jsl_cv.pdf) · [Back to Research](/research/)*
