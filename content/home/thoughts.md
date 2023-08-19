---
# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Thoughts
---

**On interpretability**

In a discussion with Prof. [Raymond Yeh](https://scholar.google.com/citations?hl=zh-CN&user=7HDE1ZwAAAAJ), he mentioned that the importance of **interpretability** is dependent on **performance**. If we can already achieve good performance, interpretability is not a big deal. The importance of interpretability appears when something is **not good enough**. When this happens, we want to understand how the system works, in order to improve the system more efficienctly. 

If we don't go this way, interpretability usually decreases performance, because interpretability is intrinsically costly. Black-box models are called black-box because opening the box is **intrinsically unsupported**, thus trying to interpret black-box models always leads to extra effort, which potentially drags the performance down.

This is why **principled methods** are valuable: principled methods are **intrinsically interpretable**. When the method has a bad performance, it will not be published; when the method has a good performance, it's interpretable. Principled methods like [CRATE](https://github.com/Ma-Lab-Berkeley/CRATE) and [Information Band Theory](https://arxiv.org/pdf/1703.00810.pdf) are good examples of this claim. This is the reason why I prefer principled methods compared to statistical methods.

