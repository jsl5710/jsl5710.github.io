---
title: Cohere For AI Invited Talk

event: Computing Research Association (CRA) CRA-WP Grad Cohort Workshop Lightening Talk
event_url: https://cohere.com/events/c4ai-Lucas-Jason-2024

location: Online Presentation
address:
  street: 
  region: Pensylvania
  city:  University Park
  postcode: 16802-2440
  country: United States

summary: In this talk we present research that tackles the misuse of large language models (LLMs) by introducing the Fighting Fire with Fire (F3) strategy, which uses GPT-3.5-turbo to generate and detect disinformation. By employing advanced techniques, we achieved a 68-72% accuracy in identifying deceptive content. We also address COVID-19 misinformation in low-resource regions, focusing on the Caribbean. Using US fact-checked claims, we trained models to detect misinformation in English, Spanish, and Haitian French. Our results highlight the limitations of current methods and the need for further multilingual research. 



abstract: 'Recent ubiquity and disruptive impacts of large language models (LLMs) have raised concerns about their potential to be misused (.i.e, generating large-scale harmful and misleading content). To combat this emerging risk of LLMs, we propose a novel “Fighting Fire with Fire” (F3) strategy that harnesses modern LLMs’ generative and emergent reasoning capabilities to counter human-written and LLM-generated disinformation. First, we leverage GPT-3.5-turbo to synthesize authentic and deceptive LLM-generated content through paraphrase-based and perturbation-based prefix-style prompts, respectively. Second, we apply zero-shot in-context semantic reasoning techniques with cloze-style prompts to discern genuine from deceptive posts and news articles. In our extensive experiments, we observe GPT-3.5-turbo’s zero-shot superiority for both in-distribution and out-of-distribution datasets, where GPT-3.5-turbo consistently achieved accuracy at 68-72%, unlike the decline observed in previous customized and fine-tuned disinformation detectors. Our codebase and dataset are available at https://github.com/mickeymst/F3.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-04-11T09:00:00Z'
date_end: '2024-04-13T09:20:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-04-11T00:00:00Z'

authors: [admin]
tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: Jason Lucas'
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/jasonslucas1
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - f3
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.
