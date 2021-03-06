---
title: 'GoAutoExecuter: Golang-based Multi-Thread Automatic Pull-Execute Framework'
summary: ''
tags:
  - Engineering
  - Network
date: '2021-09-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Architecture Overview
  focal_point: Smart

authors:
  - admin
  - wenqing

links:
  # - icon: microsoft
  #   icon_pack: fab
  #   name: 'MS Market Place'
  #   url: https://marketplace.visualstudio.com/items?itemName=JackBAI.at-t-i386-ia32-uiuc-ece391-highlighting
url_code: 'https://github.com/BiEchi/GoAutoBash'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

During the career of teaching assistant of ECE 220, I modified the GoAutoGrader program by Wenqing Luo on the server, which gives instant feedbacks and reference score to code assignments submitted. Extracted the program to a general Golang application that pulls code to the server for subsequent tasks whenever there is a GitHub submission, and queue the tasks with parallelization.
