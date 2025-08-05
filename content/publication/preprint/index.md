---
title: "Diff-DAgger: Uncertainty Estimation with Diffusion Policy for Robotic Manipulation"
authors:
- admin
date: "2019-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Recently, diffusion policy has shown impressive results in handling multi-modal tasks in robotic manipulation. However, it has fundamental limitations in out-of-distribution failures that persist due to compounding errors and its limited capability to extrapolate. One way to address these limitations is robot-gated DAgger, an interactive imitation learning with a robot query system to actively seek expert help during policy rollout. While robot-gated DAgger has high potential for learning at scale, existing methods like Ensemble-DAgger struggle with highly expressive policies: They often misinterpret policy disagreements as uncertainty at multi-modal decision points. To address this problem, we introduce Diff-DAgger, an efficient robot-gated DAgger algorithm that leverages the training objective of diffusion policy. We evaluate Diff-DAgger across different robot tasks including stacking, pushing, and plugging, and show that Diff-DAgger improves the task failure prediction by $39.0\%$, the task completion rate by $20.6\%$, and reduces the wall-clock time by a factor of 7.8. We hope that this work opens up a path for efficiently incorporating expressive yet data-hungry policies into interactive robot learning settings.

# Summary. An optional shortened abstract.
summary: Diffusion policy meets data-aggregation (DAgger).

tags:
- Human-in-the-Loop
- Robot Learning from Human

featured: true

links:
- name: Custom Link
  url: https://arxiv.org/abs/2410.14868
url_pdf: https://arxiv.org/pdf/2410.14868
url_code: https://github.com/sean1295/DiffDAgger/tree/main
# url_dataset: '#'
# url_poster: '#'
url_project: https://diffdagger.github.io/
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work is .

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
