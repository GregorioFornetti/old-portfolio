---
title: "Collaborative filtering through weighted similarities of user and item embeddings"
authors:
- admin
author_notes:
- "Equal contribution"
date: "2025-05-14T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "SAC '25: Proceedings of the 40th ACM/SIGAPP Symposium on Applied Computing"
publication_short: ""

abstract: In recent years, neural networks and other complex models have dominated recommender systems, often setting new benchmarks for state-of-the-art performance. Yet, despite these advancements, award-winning research has demonstrated that traditional matrix factorization methods can remain competitive, offering simplicity and reduced computational overhead. Hybrid models, which combine matrix factorization with newer techniques, are increasingly employed to harness the strengths of multiple approaches. This paper proposes a novel ensemble method that unifies user-item and item-item recommendations through a weighted similarity framework to deliver top-N recommendations. Our approach is distinctive in its use of shared user and item embeddings for both recommendation strategies, simplifying the architecture and enhancing computational efficiency. Extensive experiments across multiple datasets show that our method achieves competitive performance and is robust in varying scenarios that favor either user-item or item-item recommendations. Additionally, by eliminating the need for embedding-specific fine-tuning, our model allows for the seamless reuse of hyperparameters from the base algorithm without sacrificing performance. This results in a method that is both efficient and easy to implement. Our open-source implementation is available at https://github.com/UFSCar-LaSID/weightedsims-recommender.


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
    url: "https://dl.acm.org/doi/abs/10.1145/3672608.3707877"

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

In this paper, I generated embeddings with the RecVae model. These embeddings were subsequently used by our weighted sims model. I also wrote the main documentation of our method, available in the GitHub repository. I also helped in the review process of the paper.
