---
title: "Correlation Increases Group Testing’s Sensitivity"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yujia Zhang
- Peter I. Frazier


# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"


date: "2021-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate:

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Preprint on arXiv
# publication_short:

abstract: "Population-wide screening to identify and isolate infectious individuals is a powerful tool for controlling COVID-19 and other infectious diseases. Testing an entire population, however, requires significant resources. Group testing can enable large-scale screening by testing more people with fewer resources, but dilution degrades its sensitivity, reducing its effectiveness as an infection control measure. Analysis of this tradeoff typically assumes that pooled samples are independent. Building on recent empirical results in the literature, we argue that this assumption significantly underestimates the true benefits of group testing. Indeed, placing samples from a social group or household into the same pool correlates a pool's samples. As a result, a positive pool likely contains multiple positive samples, increasing a pooled test's sensitivity and also tending to reduce the number of pools that require follow-up tests. We prove that under a general correlation structure, pooling correlated samples together (called _correlated pooling_) achieves higher sensitivity and requires fewer tests per positive identified compared to independently pooling the samples (called _naive pooling_) using the same pool size within the two-stage Dorfman procedure, the most widely-used group testing method. To the best of our knowledge, our work is the first to theoretically characterize correlation's effect on sensitivity, and the first to study its effect on test usage under a realistic test error model. Under a representative starting prevalence of 1%, simulation results estimate that correlated pooling requires 12.9% fewer tests than naive pooling to control an epidemic. Thus, we argue that correlation is an important consideration for policy-makers designing infection control interventions: it makes screening more attractive for infection control and it suggests that sample collection should maximize correlation."


# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 
url_code: 'https://github.com/jiayuewan/group-testing-with-household-correlation'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
<!-- image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false -->

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
<!-- projects:
- example -->

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
<!-- slides: example -->
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
