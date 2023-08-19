---
# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 100

title: Views
---

**Interpretability**

In a discussion with Prof. [Raymond Yeh](https://scholar.google.com/citations?hl=zh-CN&user=7HDE1ZwAAAAJ), he mentioned that the importance of **interpretability** is dependent on **performance**. If we can already achieve good performance, interpretability is not a big deal. The importance of interpretability appears when something is **not good enough**. When this happens, we want to understand how the system works, in order to improve the system more efficienctly. 

If we don't go this way, interpretability usually decreases performance, because interpretability is intrinsically costly. Black-box models are called black-box because opening the box is **intrinsically unsupported**, thus trying to interpret black-box models always leads to extra effort, which potentially drags the performance down.

This is why **principled methods** are valuable: principled methods are **intrinsically interpretable**. When the method has a bad performance, it will not be published; when the method has a good performance, it's interpretable. Principled methods like [CRATE](https://github.com/Ma-Lab-Berkeley/CRATE) and [Information Band Theory](https://arxiv.org/pdf/1703.00810.pdf) are good examples of this claim. This is the reason why **I prefer principled methods compared to purely statistical methods.**

**Value of Research**

In a discussion with Prof. [Chengxiang Zhai](https://scholar.google.com/citations?hl=zh-CN&user=YU-baPIAAAAJ), he mentioned the key value of research across all subjects: a valuable research should either **propose a new question** or **propose a new solution to an existing question**. A new question is usually more difficult to define, because the value of the question is highly dependent on **both academic and real-world recognization**. The value of a  solution is evaluated by **metrics**, which are defined by the question, but the value of a question is evaluated by **human**, who is defined by physics.

Going either way, it's inevitable to do comprehensive survey before designing any methods. After proposing an idea, it's extremely important to do comprehensive survey on the topic to refine the idea and method. It's also important to give presentations on the idea to people from various backgrounds, including **home-area specialists** on the method feasibility, **away-area specialists** on approach value, and **out-of-area audience** on real-life value. For example, when you want to use ML-based methods to develop a new drug, you need home-area (ML) guys to look at your method, away-area (chemistry) guys to assess the value of the approach, and out-of-area audience (like your parents) to comment on high-level real-life value.

Under such framework, quick publication is not a good idea for a real researcher, because they lack a ton of considerations and real-life applications. As suggested by Prof. [Heng Ji](https://scholar.google.com/citations?hl=zh-CN&user=z7GCqT4AAAAJ), when she assesses a student, **quality is much more important than quantity**. A student must have 1st authorship paper published at top-tier conference, but as long as he has some, the number becomes insignificant. Having publishments means the student has participated in the complete process of a research, and having a **solid** and **creative** publishment means the student is strict and creative. On the other hand, having too many publications is extremely confusing to PIs when they view the CV and may lead to an impression that the student focuses more on **fame** per se instead of **research**. This kind of impression is extremely bad and usually causes an instinctive refusion.

**The Three Circles**

Prof. [Chengxiang Zhai](https://scholar.google.com/citations?hl=zh-CN&user=YU-baPIAAAAJ) proposed the three circles when we do research: the **Passion** circle, the **Benefit** circle and the **Resource** circle. These circles construe what ideas we choose, how valuable the idea is, and whether we can achieve them. Having good circles reduces peer pressure significantly, and when looking back, the person usually have already achieved a lot and will not feel like a loser.

The passion circle means the intrinsic passion of a person doing research, and will **determine the ending place** of a person at academy. Everyone doing research should keep asking himself: do I really love doing this research? Why did I start this research? Can I really take it as my job? These are super important questions as they directly contributes to passion, and passion leads to **consistency** and **focus**. With passion, **peer pressure** **will easily be waived** as the researcher begins to focus on the research per se, instead of focusing on how many papers he has published. People who reach this level usually do very well in any field.

The benefit circle means the value of the research. A good research usually tackles a very important problem in society and **construes of no less than 3 papers** published at top-tier conferences. Having multiple papers on one topic is usually an excellent signal because the project is proved to be recognized and has great potential, which is usually beneficial to the society or academy.

The resource circle limits what a researcher is good at. As an undergraduate student, it's usually okay to explore around and see where his strength is. However, graduate researchers are required to **find his own strengths and weaknesses** in order to propose a suitable project. An eligible researcher should always utilize his strength for research while still learn to make up his weakness. If someone is not good at abstract thinking, asking him to do pure math research kills him; if someone loves abstract deduction, doing practical projects makes him sleepy. If you don't have lots of GPUs, avoid doing experiments with LM pretraining and LLM fine-tuning - this is not gonna work if you don't have enough computational resources, so **choose ideas wisely**. **This is not even about going out of your comfort zone, it's how physics works.** Concurrently, making up the shortness is important because although he can avoid creating knowledge related to his weaknesses, he can't avoid reading them. When encountering a paper that is hard to understand, try not to skip it and make up the weakness using that paper.
