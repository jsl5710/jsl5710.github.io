---
title: 'An example conference paper'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Adaku Uchendu
  - Michiharu Yamashita
  - Jooyoung Lee
  - Shaurya Rohatgi
  - Dongwon Lee

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-12-05T00:00:00Z'
doi: '10.18653/v1/2023.emnlp-main.883'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing*
publication_short: In *EMNLP*

abstract:  Recent ubiquity and disruptive impacts of large language models (LLMs) have raised concerns about their potential to be misused (*.i.e, generating large-scale harmful and misleading content*). To combat this emerging risk of LLMs, we propose a novel “***Fighting Fire with Fire***” (F3) strategy that harnesses modern LLMs’ generative and emergent reasoning capabilities to counter human-written and LLM-generated disinformation. First, we leverage GPT-3.5-turbo to synthesize authentic and deceptive LLM-generated content through paraphrase-based and perturbation-based prefix-style prompts, respectively. Second, we apply zero-shot in-context semantic reasoning techniques with cloze-style prompts to discern genuine from deceptive posts and news articles. In our extensive experiments, we observe GPT-3.5-turbo’s zero-shot superiority for both in-distribution and out-of-distribution datasets, where GPT-3.5-turbo consistently achieved accuracy at 68-72%, unlike the decline observed in previous customized and fine-tuned disinformation detectors. Our codebase and dataset are available at https://github.com/mickeymst/F3.


# Summary. An optional shortened abstract.
summary: Fighting Fire With Fire, F3, is a collaboration with Penn State and MIT Lincoln. Our study demonstrates the dual capacity of LLMs for offensive misuse and defense detection against disinformation without requiring additional training.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://aclanthology.org/2023.emnlp-main.883.pdf'
url_code: 'https://github.com/mickeymst/F3'
url_dataset: 'https://github.com/mickeymst/F3'
url_poster: ''
url_project: ''
url_slides: 'https://drive.google.com/drive/mobile/folders/1BZqJ7RHNXCVJNnZKkgbj4GZavYe2kc4r?usp=sharing'
url_source: 'https://pike.psu.edu/publications/emnlp23-f3.pdf'
url_video: 'https://underline.io/events/431/sessions/16376/lecture/88747-fighting-fire-with-fire-the-dual-role-of-llms-in-crafting-and-detecting-elusive-disinformation'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: DALLE-2 [**Michiharu**](https://mickeymst.github.io/)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
