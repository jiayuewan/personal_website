---
title: "Bayesian Optimization of Function Networks with Partial Evaluations"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Poompol Buathong
- admin
- Raul Astudillo
- Sam Daulton
- Maximilian Balandat
- Peter I. Frazier

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2024-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate:

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the 41st *International Conference on Machine Learning*, PMLR
# publication_short:

abstract: "Bayesian optimization is a powerful framework for optimizing functions that are expensive or time-consuming to evaluate. Recent work has considered Bayesian optimization of function networks (BOFN), where the objective function is given by a network of functions, each taking as input the output of previous nodes in the network as well as additional parameters. Leveraging this network structure has been shown to yield significant performance improvements. Existing BOFN algorithms for general-purpose networks evaluate the full network at each iteration. However, many real-world applications allow for evaluating nodes individually. To exploit this, we propose a novel knowledge gradient acquisition function that chooses which node and corresponding inputs to evaluate in a cost-aware manner, thereby reducing query costs by evaluating only on a part of the network at each step. We provide an efficient approach to optimizing our acquisition function and show that it outperforms existing BOFN methods and other benchmarks across several synthetic and real-world problems. Our acquisition function is the first to enable cost-aware optimization of a broad class of function networks."

# Summary. An optional shortened abstract.
summary:

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://proceedings.mlr.press/v235/buathong24a.html'
url_code: 'https://github.com/frazier-lab/partial_kgfn'
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
