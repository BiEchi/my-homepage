---
title: 'Distributed Data Parallel Training for Very Large Scale Deep Learning Models'
summary: ''
tags:
  - Research
  - Distributed Training
  - Natural Language Processing
date: '2021-12-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Partial Results of This Research
  focal_point: Smart

authors:
  - admin
  - vlad
  - tingkai

links:
#   - icon: microsoft
#     icon_pack: fab
#     name: 'MS Market Place'
#     url: https://marketplace.visualstudio.com/items?itemName=JackBAI.at-t-i386-ia32-uiuc-ece391-highlighting
url_code: 'https://github.com/BiEchi/DistributedTrainingGPT2'
url_pdf: ''
url_slides: './project/data-parallel/slides.pdf'
url_video: 'https://drive.google.com/file/d/1XvgTkfNjhGOig6bpzaXvE8s0P5BODv75/view'

---

Research to modify very-large-scale NLP models like BERT and GPT2 to create data parallelism, including Single Parameter Server (SPS), Distributed Param- eter Server (DPS), Horovod, and Apex, with BERT based on Tensorflow and GPT2 based on PyTorch. Applied SPS and DPS for BERT, and all 6 data par- allel strategies for GPT2. The GPT2 part of work has been accepted by the Conference HP3C. I'll make it available after publication.

Two subsequent projects to this project are model-parallel training and transplanting the strategies onto remote distributed systems like k8s and Ray.
