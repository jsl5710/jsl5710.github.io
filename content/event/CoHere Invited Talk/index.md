---
title: Cohere For AI Invited Talk

event: Computing Research Association (CRA) CRA-WP Grad Cohort Workshop Lightening Talk
event_url: https://cra.org/cra-wp/events/2024-grad-cohort-for-women-grad-cohort-for-ideals/

location: Alohilani Resort Waikiki Beach, Honolulu, HI
address:
  street: 
  region: Central Pacific
  city: Honolulu
  postcode: 96815-2440
  country: United States

summary: The widespread use and disruptive effects of large language models (LLMs) have led to concerns about their potential misuse, such as generating harmful and misleading content on a large scale. To address this risk, the authors propose a novel "Fighting Fire with Fire" (F3) strategy, which utilizes the generative and reasoning capabilities of modern LLMs to counter disinformation created by both humans and LLMs. 



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
