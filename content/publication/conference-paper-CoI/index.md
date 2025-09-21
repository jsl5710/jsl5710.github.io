---
title: 'Chain-of-Interactions: Iterative ICL Framework for Abstractive Task-Oriented Dialogue Summarization of Conversational AI Interactions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - John Chen
  - Ali Al-Lawati
  - Mahjabin Nahar
  - Mahnoosh Mehrabani

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-08-31T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"] # for journal article use ["article-journal"] and for preprint: ["article"]

# Publication name and optional abbreviated publication name.
publication: In *Findings of the Association for Computational Linguistics, Empirical Methods in Natural Language Processing*
publication_short: In *EMNLP*

abstract: Large Language Models (LLMs) have introduced paradigm-shifting approaches in natural language processing. Yet, their transformative in-context learning (ICL) capabilities remain underutilized, especially in customer service dialogue summarization—a domain plagued by generative hallucinations, detail omission, and inconsistencies. We present Chain-of-Interactions (CoI), a novel single-instance, multi-step framework that orchestrates information extraction, self-correction, and evaluation through sequential interactive generation chains. By strategically leveraging LLMs' ICL capabilities through precisely engineered prompts, CoI dramatically enhances abstractive task-oriented dialogue summarization (ATODS) quality and usefulness. Our comprehensive evaluation on real-world and benchmark human-agent interaction datasets demonstrates CoI's effectiveness through rigorous testing across 11 models and 7 prompting approaches, with 9 standard automatic evaluation metrics, 3 LLM-based evaluations, and human studies involving 480 evaluators across 9 quality dimensions. Results reveal CoI's decisive superiority, outperforming all single-step approaches and achieving 6× better entity preservation, 49% higher quality scores, and 322% improvement in accuracy compared to state-of-the-art multi-step Chain-of-Density (CoD). This research addresses critical gaps in task-oriented dialogue summarization for customer service applications and establishes new standards for harnessing LLMs' reasoning capabilities in practical, industry-relevant contexts.

# Summary. An optional shortened abstract.
summary: Chain-of-Interactions (CoI) introduces a novel multi-step framework that leverages LLMs' in-context learning capabilities for abstractive task-oriented dialogue summarization. Through comprehensive evaluation across 11 models and human studies with 480 evaluators, CoI demonstrates decisive superiority with 6× better entity preservation and 49% higher quality scores compared to existing approaches, establishing new standards for customer service dialogue summarization.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/jsl5710/CoI'
url_dataset: 'https://github.com/jsl5710/CoI'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: Jason'
  focal_point: ''
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - dialogue-summarization

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Dataset, code, and materials are available on [GitHub](https://github.com/jsl5710/CoI).
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).