---
title: 'Computer Vision and Computer Graphics Workshop'
summary: ''
tags:
  - Research
date: '2022-01-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: The Stanford Rabbit I worked on.
  focal_point: Smart

authors:
  - admin
  - lumetta

links:
  - icon: microsoft
    icon_pack: fab
    name: 'MS Market Place'
    url: https://marketplace.visualstudio.com/items?itemName=JackBAI.at-t-i386-ia32-uiuc-ece391-highlighting
url_code: 'https://github.com/BiEchi/at-t-i386-ia32-uiuc-ece391-highlighting'
url_pdf: ''
url_slides: './content/project/mesh-processing/slides.pdf'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: mesh-processing
---

VS Code Extension that provides language support for AT&T i386 Assembly, integrating syntax highlighter, snippets, and linter (language server), based on the LC-3 language support by Qi Li. The extension has received more than 500 downloads in a single semester. Below is the snapshot of the README doc for this extension.

# AT&T i386 IA32 UIUC ECE391 GCC Highlighter & Snippet & Linter

This is the VS Code Extension for UIUC ECE 391, MIT 6.828, and all other AT&T-based i386(IA-32/x86-32) assembly languages. Current VS Code extensions for assembly are mostly industry-oriented, but this extension is designed for college students and researchers in this area.

## Features

-   Syntax Highlighting.

![image-20220130141503525](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-01-30-201504.png)

-   Self Complete.

![image-20220205223106455](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-043106.png)

![image-20220205223123472](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-043123.png)

-   File icons designed for UIUC students.

![image-20220130154626450](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-01-30-214627.png)

-   Linter line checking.

Memory at both sides of instruction.

![image-20220205223243002](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-043243.png)

Code before `.data`, after `.end`, and misplacement of data code and text code.

![image-20220205224209883](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-044210.png)

![image-20220205224336409](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-044336.png)

Instruction does not exist.

![image-20220205224436253](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-044437.png)

Wrong argument number.

![image-20220205224517684](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-044518.png)

The datatype of command does not match the registers.

![image-20220205224711626](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-044712.png)

Immediate value without '$'.

![image-20220205224806259](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-044806.png)

Register without '%’

![image-20220205224844381](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-044844.png)

-   Linter block checking.

Alignment issues.

![image-20220205223452937](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-043453.png)

![image-20220205223438129](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-043438.png)

![image-20220205223524354](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-043525.png)

Calling issues.

![image-20220205223805824](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-043806.png)

![image-20220205223842718](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-043843.png)

![image-20220205223957125](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-02-06-043957.png)

-   Hovering. If you hover your mouse on the keywords or registers, it shows you the basic information about the keyword or register.

## Requirements

-   To make this extension work, you need to change your source code to `.s` or `.S`.
-   Select the language to “AT&T i386 Assembly” using the language change button.

![image-20220129152332934](https://jacklovespictures.oss-cn-beijing.aliyuncs.com/2022-01-29-212333.png)

-   To use the icon theme, press `shift+ctrl+p` at the same time, then choose `Preferences: File Icon Theme`, then choose `ECE 391 UIUC`.



## Known Issues

-   No issues hitherto.

## Request A Feature

Please contact the author at [haob2@illinois.edu](mailto:haob2@illinois.edu).

## Release Notes

Please see `./CHANGELOG.md`.
