---
title: 'Modern Distributed Data-Parallel Pre-training Strategies for Large-Scale LMs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:
  - 'Correspondent Author'

# date: '2022-06-08T00:00:00Z'
# doi: '10.1109/ICFTIC54370.2021.9647189'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 6th International Conference on High Performance Compilation, Computing and Communications*
publication_short: In *HP3C 2022*

abstract: 'Distributed deep learning is becoming increasingly popular due to the expanding demand for computing resources for deep learning models with a larger amount of parameters. Different from traditional training approaches, data-parallel training allows multiple compute nodes to train large deep learning models simultaneously in order to boost the training efficiency. In this paper, we present and compare six strategies for data-parallel training using PyTorch on the language model GPT-2 with 100M parameters using a qualitative approach. These strategies are Single GPU, Single Parameter Server, Distributed Parameter Server, Horovod, Distributed Parameter Server with Apex mixed-precision strategy, and Horovod with Apex mixed-precision strategy. We also analyze the quantitative experiment results from each strategy. In the end, we draw the conclusion that the Distributed Parameter Server with Apex mixedprecision strategy has the best performance on single node training, while Horovod with Apex is the most robust approach to use when we have single or multiple nodes.'

# Summary. An optional shortened abstract.
summary: ''

tags: ['infra']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/BiEchi/DistributedTrainingGPT2' 
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
  # - vsc-webgpu

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

