---
title: 'TranSoC: An Optimized Transformer SoC Design Based on The Gemmini Architecture on Chipyard Framework'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wentao Yao
  - admin
  - Liyang Qian

# Author notes (optional)
author_notes:
  - 'Correspondent Author'
  - 'Equal Contributor'
  - 'Equal Contributor'

date: '2021-09-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-03-09T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['4']

# Publication name and optional abbreviated publication name.
publication: In *2021 Jack Bai Selected Publications*
publication_short: In *JBSP 2021*

abstract: 'Nowadays, transformer is a very popular deep learning model in both fields of Natural Language Processing and Computer Vision. With very large number of parameters in the model, trans- former usually takes a significant amount of time for training and inference. Recent researches have been done to solve similar problems based on the Berkeley’s systolic array generator called Gemmini architecture, and made great progress using this method. Thus, we follow this pat- tern and build a transformer accelerator based on the Gemmini architecture, which is mostly a matrix multiplication accelerator based on the systolic array technique. We developed the trans- former testing framework for the Gemmini project with results. Additionally, we also provide our analysis for the Gemmini hardware and possible ways to implement the transformer accelerator.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: './publication/transoc/paper.pdf'
url_code: 'https://github.com/BiEchi/chipyard'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'The magical Tree'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
  - transoc

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}
