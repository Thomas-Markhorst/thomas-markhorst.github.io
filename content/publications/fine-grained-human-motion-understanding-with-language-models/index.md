---
title: Fine-grained Human Motion Understanding with Language Models
authors:
  - Thomas Markhorst
  - Zhi-Yi Lin
  - Jouh Yeong Chew
  - Jan van Gemert
  - Xucong Zhang
author_notes:
  - ""
date: 2026-06-22T09:36:29.779Z
publishDate: 2026-06-22T09:36:29.779Z
publication_types:
  - article-journal
publication: "WACV 2027"
publication_short: ""
abstract: |
  Fine-grained motion understanding requires knowing not only which poses occur, but also when they occur. Existing motion-language models either compress motion clips or concatenate pose features without retaining the timing of each pose, making action duration and temporal scale ambiguous under temporal subsampling. We introduce FiGMo, an LLM-based model that represents motion as timestamp-grounded skeletal poses, supporting reasoning over action order and duration. A unified pose encoder applies this representation to both 2D and 3D skeletons, including poses detected from real videos, while RGB can optionally provide contextual information. To reason over timestamped pose sequences, the model must understand both individual body configurations and how they change over time. As existing data provides limited pose-level grounding, we construct the required pose-to-motion supervision. Controlled experiments show that timestamps improve temporal localization and preserve physical timing under subsampling, while the constructed supervision drives the main performance gains. FiGMo achieves state-of-the-art results across motion question answering, dense motion captioning, and action recognition with detected poses. Our code is available at: https://github.com/Thomas-Markhorst/FiGMo
summary: One-line takeaway for readers skimming listings.
tags: null
featured: true
hugoblox:
  ids:
    arxiv: ""
links:
  - type: pdf
    url: https://arxiv.org/abs/2606.20888v2
  - type: code
    url: ""
  - type: dataset
    url: ""
  - type: poster
    url: ""
  - type: project
    url: ""
  - type: slides
    url: ""
  - type: source
    url: https://arxiv.org/pdf/2606.20888v2
  - type: video
    url: ""
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com)"
  focal_point: ""
  preview_only: false
projects: []
slides: ""
status: published
---
<!-- Add the paper text or supplementary notes. Markdown, math, and code are supported. -->
