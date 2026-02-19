---
title: 'Semantic Captioning: Benchmark Dataset and Graph-Aware Few-Shot In-Context Learning for SQL2Text'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ali Al Lawati
  - admin
  - Prasenjit Mitra

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-02-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference'] # for journal article use ["article-journal"] and for preprint: ["article"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 31st International Conference on Computational Linguistics*
publication_short: In *COLING*

abstract: "Large Language Models (LLMs) have demonstrated remarkable performance in various NLP tasks, including semantic parsing, which translates natural language into formal code representations. However, the reverse operation, translating code into natural language, termed semantic captioning, has received less attention. This task is increasingly important as LLMs are integrated into platforms for code generation, security analysis, and educational purposes. In this paper, we focus on the captioning of SQL query (SQ2Text) to address the critical need for understanding and explaining SQL queries in an era where LLM-generated code poses potential security risks. We repurpose semantic parsing datasets for semantic captioning, specifically SQL2Text. To overcome the limited robustness of Text2SQL datasets for the reverse task, we introduce an iterative ICL prompt leveraging GPT-4o to generate multiple additional utterances. We conduct experiments across multiple in-context learning (ICL) methods, emphasizing smaller, more computationally efficient LLMs. Our findings demonstrate that leveraging the inherent graph properties of SQL for few-shot ICL sample selection significantly outperforms random selection by up to 39% on BLEU score and provides better results than alternative approaches. Dataset and codes are accessible."

# Summary. An optional shortened abstract.
summary: "This work introduces semantic captioning for SQL queries, addressing the reverse operation of semantic parsing by translating SQL code into natural language explanations. Using graph-aware few-shot in-context learning with smaller LLMs, our approach outperforms random selection by up to 39% on BLEU score, providing crucial capabilities for understanding and explaining LLM-generated SQL code in security-critical applications."

tags: [Semantic Parsing, SQL, In-Context Learning, Code Understanding]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2025.coling-main.536/'
url_code: ''
url_dataset: ''
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
  - nlp-applications

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
Dataset and codes are accessible for research use.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).