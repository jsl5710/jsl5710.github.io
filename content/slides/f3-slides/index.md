---
title: Fighting Fire with Fire - EMNLP 2023
summary: The Dual Role of LLMs in Crafting and Detecting Elusive Disinformation
authors: [Jason Lucas, Adaku Uchendu, Michiharu Yamashita, Jooyoung Lee, Shaurya Rohatgi, Dongwon Lee]
tags: [NLP, Disinformation, LLMs]
categories: [Research]
date: '2023-12-06T00:00:00Z'
slides:
  theme: white
  highlight_style: dracula
---

{{< slide background-color="#ffffff" >}}

# Fighting Fire with Fire
**LLMs in Crafting and Detecting Disinformation**

<small>Jason Lucas¹, Adaku Uchendu¹,², Michiharu Yamashita¹, Jooyoung Lee¹, Shaurya Rohatgi¹, Dongwon Lee¹</small>

<small>¹Penn State University, ²MIT Lincoln Laboratory</small>

**EMNLP 2023 Main Conference**

---

{{< slide background-color="#f8f9fa" >}}

## Problem & Motivation

**Challenge**: LLMs generate realistic but harmful disinformation

<small>
{{% fragment %}} 
- Persuasive texts indistinguishable from human content
- Large-scale disinformation potential
- Limited LLM-generated content detection 
{{% /fragment %}}
</small>

{{% fragment %}} **Core Question**: *Can LLMs detect their own disinformation?* {{% /fragment %}}

---

{{< slide background-color="#ffffff" >}}

## Research Questions

<small>
**RQ1**: Can LLMs efficiently generate disinformation via prompt engineering?

**RQ2**: How proficient are LLMs at detecting disinformation?

{{% fragment %}} **5 Evaluation Dimensions**:

- Human vs. LLM-generated
- Self vs. externally-generated
- Posts vs. articles
- In vs. out-of-distribution
- Zero-shot LLMs vs. fine-tuned detectors 
{{% /fragment %}}
</small>

---

{{< slide background-color="#f8f9fa" >}}

## F3 Framework

<small>
**Fighting Fire with Fire (F3)** - 5-step approach:

{{% fragment %}} 
1. Human data collection
2. Prompt engineering generation
3. PURIFY hallucination filtering
4. Cloze-prompt detection
5. Zero-shot evaluation
{{% /fragment %}}
</small>

---

{{< slide background-color="#ffffff" >}}

## RQ1: Bypassing Alignment

<small>
**Key Discovery**: Impersonator roles override safety measures

{{% fragment %}} **Without role**: *"Sorry, I can't assist..."* {{% /fragment %}}

{{% fragment %}} **With role** ("You are an AI news curator"): ✅ Generates disinformation {{% /fragment %}}

{{% fragment %}} **Finding**: Impersonator prompts successfully bypass GPT-3.5 protections {{% /fragment %}}
</small>

---

{{< slide background-color="#f8f9fa" >}}

## Generation Strategies

<small>
**Perturbation-Based** (Fake):

- Minor: Subtle changes
- Major: Noticeable changes
- Critical: Significant alterations

**Paraphrase-Based** (Real):

- Minor: Light summary
- Major: Moderate rewording
- Critical: Full rephrasing

{{% fragment %}} **Output**: 43K+ synthetic samples {{% /fragment %}}
</small>

---

{{< slide background-color="#ffffff" >}}

## PURIFY Framework

<small>
**Problem**: 38% hallucinated misalignments

{{% fragment %}} **PURIFY** filters using 4 metrics:

- Natural Language Inference
- AlignScore
- BERTScore
- Semantic Distance 
{{% /fragment %}}

{{% fragment %}} **Result**: 43,272 → 27,667 quality samples {{% /fragment %}}
</small>

---

{{< slide background-color="#f8f9fa" >}}

## RQ2: Detection Results

<small>
**Human vs. LLM Content**:

- Human-authored: 55-66% accuracy
- LLM-generated: 60-85% accuracy

{{% fragment %}} **Self vs. External**:

- GPT-3.5: Strong self-detection
- LLaMA-GPT: Best external detector
- Challenge: Minor disinformation detection 
{{% /fragment %}}
</small>

---

{{< slide background-color="#ffffff" >}}

## Key Findings

<small>
{{% fragment %}} **Content Type**: Articles > Social media posts {{% /fragment %}}

{{% fragment %}} **Distribution**: In-distribution > Out-of-distribution {{% /fragment %}}

{{% fragment %}} **Model Type**: Fine-tuned > GPT-3.5 > Domain-specific {{% /fragment %}}

{{% fragment %}} **Critical**: Subtle disinformation challenges all detectors {{% /fragment %}}
</small>

---

{{< slide background-color="#f8f9fa" >}}

## Technical Contributions

<small>
1. Novel prompting for disinformation generation
2. PURIFY hallucination filtering framework
3. Cloze-prompt detection strategies
4. Comprehensive SOTA benchmark
5. F3 dataset for research community
</small>

---

{{< slide background-color="#ffffff" >}}

## Dataset & Evaluation

<small>
**Models**: GPT-3.5, LLaMA-2, Palm-2, Dolly-2

**Data**: CoAID, FakeNewsNet, F3 (27,667 samples)

**Languages**: 11 languages, Pre/Post-GPT splits

**Metrics**: Macro-F1 across human/AI datasets
</small>

---

{{< slide background-color="#f8f9fa" >}}

## Impact & Implications

<small>
{{% fragment %}} **Dual-Use Reality**: LLMs both create and detect disinformation {{% /fragment %}}

{{% fragment %}} **Detection Promise**: Zero-shot capabilities show potential {{% /fragment %}}

{{% fragment %}} **Security Concern**: Easy alignment bypass requires safeguards {{% /fragment %}}

{{% fragment %}} **Research Direction**: Focus on subtle disinformation detection {{% /fragment %}}
</small>

---

{{< slide background-color="#1e3a8a" >}}

## "Fighting Fire with Fire"

<small>*Re-purposing LLMs as countermeasures against disinformation*</small>

---

{{< slide background-color="#ffffff" >}}

## Questions & Resources

<small>
**Code**: https://github.com/mickeymst/F3  
**Paper**: EMNLP 2023 Main Conference  
**Contact**: jsl5710@psu.edu

Penn State University | PIKE Research Lab
</small>

**Thank You!**