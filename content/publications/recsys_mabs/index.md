---
title: "Exploitation Over Exploration: Unmasking the Bias in Linear Bandit Recommender Offline Evaluation"
authors:
- admin
author_notes:
- "Equal contribution"
date: "2025-10-31T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-31T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*SAC '25: Proceedings of the 40th ACM/SIGAPP Symposium on Applied Computing"
publication_short: ""

abstract: Multi-Armed Bandit (MAB) algorithms are widely used in recommender systems that require continuous, incremental learning. A core aspect of MABs is the exploration–exploitation trade-off choosing between exploiting items likely to be enjoyed and exploring new ones to gather information. In contextual linear bandits, this trade-off is particularly central, as many variants share the same linear regression backbone and differ primarily in their exploration strategies. Despite its prevalent use, offline evaluation of MABs is increasingly recognized for its limitations in reliably assessing exploration behavior. This study conducts an extensive offline empirical comparison of several linear MABs. Strikingly, across over 90% of various datasets, a greedy linear model—with no type of exploration—consistently achieves top-tier performance, often outperforming or matching its exploratory counterparts. This observation is further corroborated by hyperparameter optimization, which consistently favors configurations that minimize exploration, suggesting that pure exploitation is the dominant strategy within these evaluation settings. Our results expose significant inadequacies in offline evaluation protocols for bandits, particularly concerning their capacity to reflect true exploratory efficacy. Consequently, this research underscores the urgent necessity for developing more robust assessment methodologies, guiding future investigations into alternative evaluation frameworks for interactive learning in recommender systems. The source code for our experiments is publicly available on https://github.com/UFSCar-LaSID/exploit-over-explore.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Recommender systems
featured: true

#hugoblox:
#  ids:
#    arxiv: 1512.04133v1

links:
  - type: source
    url: "https://dl.acm.org/doi/abs/10.1145/3705328.3748166"
  - type: pdf
    url: "https://arxiv.org/pdf/2507.18756?"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

In this paper, I was mainly responsible for the code, elaborating its structure and documentation. I implemented the incremental experimental protocol and the optimized MAB algorithms, which subsequently originated the GOBRec library. I also helped in the paper review process
