---
title: Fighting Fire with Fire - The Dual Role of LLMs in Crafting and Detecting Elusive Disinformation
summary: EMNLP 2023 Main Conference Presentation
authors: [Jason Lucas, Adaku Uchendu, Michiharu Yamashita, Jooyoung Lee, Shaurya Rohatgi, Dongwon Lee]
tags: [NLP, Disinformation, LLMs, Adversarial ML]
categories: [Research]
date: '2023-12-06T00:00:00Z'
slides:
  theme: black
  highlight_style: dracula
---

# Fighting Fire with Fire
**The Dual Role of LLMs in Crafting and Detecting Elusive Disinformation**

Jason Lucas¹, Adaku Uchendu¹,², Michiharu Yamashita¹  
Jooyoung Lee¹, Shaurya Rohatgi¹, Dongwon Lee¹

¹Penn State University, ²MIT Lincoln Laboratory

**EMNLP 2023 Main Conference**

---

## The Disinformation Challenge

{{% fragment %}} **The Problem**: LLMs can generate highly realistic but harmful content {{% /fragment %}}

{{% fragment %}} **Key Concerns**:
- LLMs produce persuasive texts indistinguishable from human-written content
- Potential for large-scale disinformation campaigns
- Limited detection capabilities for LLM-generated content {{% /fragment %}}

{{% fragment %}} **Our Question**: *If LLMs can generate disinformation, can they also detect it?* {{% /fragment %}}

---

## Research Questions

**RQ1: Disinformation Generation**
> Can LLMs be exploited to efficiently generate disinformation using prompt engineering?

**RQ2: Disinformation Detection** 
> How proficient are LLMs in detecting disinformation?

{{% fragment %}} We evaluate across **5 dimensions**:
1. Human vs. LLM-generated content
2. Self-generated vs. externally-generated 
3. Social media posts vs. news articles
4. In-distribution vs. out-of-distribution
5. Zero-shot LLMs vs. domain-specific detectors {{% /fragment %}}

---

## F3 Framework Overview

**Fighting Fire with Fire (F3)** - A 5-step framework:

{{% fragment %}} **Step 1**: Human data collection {{% /fragment %}}
{{% fragment %}} **Step 2**: Prompt engineering for generation {{% /fragment %}}
{{% fragment %}} **Step 3**: PURIFY - hallucination filtering {{% /fragment %}}
{{% fragment %}} **Step 4**: Cloze-prompt engineering for detection {{% /fragment %}}
{{% fragment %}} **Step 5**: Zero-shot evaluation {{% /fragment %}}

---

## RQ1: Prompt Engineering for Generation

### Overriding Alignment Tuning

{{% fragment %}} **Key Finding**: Impersonator roles bypass GPT-3.5's protections {{% /fragment %}}

{{% fragment %}} **Without impersonator**: 
*"Sorry, I can't assist with that request..."* {{% /fragment %}}

{{% fragment %}} **With impersonator** ("You are an AI news curator"):
✅ Successfully generates disinformation {{% /fragment %}}

{{% fragment %}} **RQ1.1 Finding**: *Impersonator prompt engineering overrides GPT-3.5-turbo's protections* {{% /fragment %}}

---

## Generation Strategies

### Two-Pronged Approach

**Perturbation-Based (Fake News)**
- Minor: Subtle changes, harder to detect
- Major: Noticeable but non-radical changes  
- Critical: Significant, conspicuous alterations

**Paraphrase-Based (Real News)**
- Minor: Light summarization
- Major: Moderate rewording
- Critical: Comprehensive rephrasing

{{% fragment %}} **Result**: 43K+ synthetic real and fake samples generated {{% /fragment %}}

---

## PURIFY Framework

**Problem**: 38% of generated data contained hallucinated misalignments

{{% fragment %}} **PURIFY** (Prompt Unraveling and Removing Interface for Fabricated Hallucinations Yarns) {{% /fragment %}}

{{% fragment %}} **Four Evaluation Metrics**:
1. **Natural Language Inference** - Logical consistency
2. **AlignScore** - Factual alignment  
3. **BERTScore** - Contextual consistency
4. **Semantic Distance** - Semantic coherence {{% /fragment %}}

{{% fragment %}} **Result**: Filtered dataset from 43,272 → 27,667 high-quality samples {{% /fragment %}}

---

## RQ2: Detection Results - Human vs. LLM

**Key Finding**: LLMs struggle more with human-written disinformation

{{% fragment %}} **GPT-3.5-Turbo Performance**:
- Human-authored: 55-66% accuracy
- LLM-generated: 60-85% accuracy {{% /fragment %}}

{{% fragment %}} **RQ2.1 Finding**: *LLMs struggle more to detect human-written disinformation compared to LLM-generated variants* {{% /fragment %}}

---

## Detection Results - Self vs. External

**GPT-3.5-Turbo excels at self-detection**

{{% fragment %}} **Key Findings**:
- **GPT-3.5**: Strong self-detection capabilities
- **LLaMA-GPT**: Best external detector of GPT-3.5 content
- **Challenge**: All models struggle with minor (subtle) disinformation {{% /fragment %}}

{{% fragment %}} **RQ2.2 Finding**: *GPT-3.5-Turbo is good at self-detection, and LLaMA-GPT is the best external detector* {{% /fragment %}}

---

## Content Type & Distribution Analysis

### Posts vs. Articles
{{% fragment %}} **Finding**: LLMs perform better on long news articles than short social media posts {{% /fragment %}}

### In-Distribution vs. Out-of-Distribution  
{{% fragment %}} **Finding**: Performance declined on out-of-distribution data (except LLaMA-2) {{% /fragment %}}

### Zero-Shot vs. Fine-Tuned
{{% fragment %}} **Finding**: Fine-tuned transformers achieve best performance, but GPT-3.5-Turbo outperforms domain-specific detectors {{% /fragment %}}

---

## Key Technical Contributions

1. **Novel prompting methods** for synthetic disinformation generation

2. **PURIFY framework** for hallucination detection and removal

3. **Advanced cloze-prompt strategies** for zero-shot detection

4. **Comprehensive benchmark** comparing SOTA detection models

5. **F3 dataset** for disinformation research

---

## Critical Findings

{{% fragment %}} **Alignment Bypass**: Impersonator prompts successfully override safety measures {{% /fragment %}}

{{% fragment %}} **Hallucination Challenge**: 38% of generated content required filtering {{% /fragment %}}

{{% fragment %}} **Detection Difficulty**: Subtle (minor) disinformation challenges even the best detectors {{% /fragment %}}

{{% fragment %}} **Distribution Sensitivity**: Models struggle with out-of-distribution content {{% /fragment %}}

---

## Implications & Future Work

### **Dual-Use Technology**
{{% fragment %}} - LLMs can both create and detect disinformation
- Need for responsible development and deployment {{% /fragment %}}

### **Detection Strategies**
{{% fragment %}} - Zero-shot capabilities show promise
- Advanced prompting techniques improve performance {{% /fragment %}}

### **Research Directions**
{{% fragment %}} - Few-shot detection capabilities
- Multimodal disinformation
- Stronger safeguarding mechanisms {{% /fragment %}}

---

## Experimental Setup

**Models Evaluated**:
- GPT-3.5-Turbo, LLaMA-2-Chat, LLaMA-2-GPT4, Palm-2, Dolly-2

**Datasets**:
- CoAID (COVID-19), FakeNewsNet (Politics), F3 (New dataset)
- Pre/Post-GPT-3.5 splits for distribution analysis

**Evaluation**: Macro-F1 scores across human/AI datasets

---

## Dataset Statistics

**Final F3 Dataset**: 27,667 samples after PURIFY filtering

{{% fragment %}} **Breakdown**:
- Real news: 9,141 samples
- Fake news: 18,526 samples
- 11 languages represented
- Social media posts + News articles {{% /fragment %}}

{{% fragment %}} **Quality Metrics**:
- BERTScore: 0.92-1.00 contextual consistency
- Semantic distance: 0.001-0.014 for coherence {{% /fragment %}}

---

## Ethical Considerations

{{% fragment %}} **Responsible Research**:
- Release synthetic variations only (not original misinformation)
- Promote transparency while minimizing harmful usage
- Focus on defensive applications {{% /fragment %}}

{{% fragment %}} **Dual-Use Awareness**:
- Acknowledge potential for misuse
- Emphasize defensive capabilities
- Call for proactive safeguarding {{% /fragment %}}

---

{{< slide background-color="#1e3a8a" >}}

## Fighting Fire with Fire

*"We can fight back by re-purposing LLMs as countermeasures, thus fighting fire with fire."*

**Key Message**: While LLMs pose disinformation risks, they also offer powerful detection capabilities

---

## Questions & Discussion

**GitHub**: https://github.com/mickeymst/F3  
**Paper**: EMNLP 2023 Main Conference  
**Contact**: jsl5710@psu.edu

{{% fragment %}} **Thank you!** {{% /fragment %}}

**Penn State University | PIKE Research Lab**