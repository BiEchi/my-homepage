---
title: 'Modern Distributed Data-Parallel Very-Large-Scale Deep Learning Pre-training Strategies for NLP models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes:
  - 'Correspondent Author'

date: '2022-05-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-22T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2022 6th International Conference on High Performance Compilation, Computing and Communications*
publication_short: In *HP3C 2022*

abstract: 'Distributed deep learning is becoming increasingly popular due to the expanding demand for computing resources for deep learning models with a larger amount of parameters. Different from traditional training approaches, data-parallel training allows multiple compute nodes to train large deep learning models simultaneously in order to boost the training efficiency. In this paper, we present and compare six strategies for data-parallel training using PyTorch on the language model GPT-2 with 100M parameters using a qualitative approach. These strategies are Single GPU, Single Parameter Server, Distributed Parameter Server, Horovod, Distributed Parameter Server with Apex mixed-precision strategy, and Horovod with Apex mixed-precision strategy. We also analyze the quantitative experiment results from each strategy. In the end, we draw the conclusion that the Distributed Parameter Server with Apex mixedprecision strategy has the best performance on single node training, while Horovod with Apex is the most robust approach to use when we have single or multiple nodes.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: 'Appendix'
  url: './publication/data_parallel/hp3c-appendix.pdf'

url_pdf: 'https://arxiv.org/pdf/2206.06356.pdf'
url_code: 'https://github.com/BiEchi/DistributedTrainingGPT2' 
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: './project/data-parallel/slides.pdf'
url_source: ''
url_video: 'https://drive.google.com/file/d/1XvgTkfNjhGOig6bpzaXvE8s0P5BODv75/view'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Partial results of this research'
  focal_point: ''
  preview_only: false

projects:
  - data-parallel

slides: ''
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

