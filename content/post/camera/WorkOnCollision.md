---
title: My Work On Collision
date: 2021-06-10 16:13:31
tags: My Work on Dataset Expansion
categories: Human3.6M Expansion
cover: true
mathjax: true
img: http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-10-082705.png
---

# My Work On Collision

This documentation is used to make solve the harsh problem on collision on the data expansion.

## Cases

We dicussed multiple possibilities on collision, and the result shows no more than these three: (note that we’re in the plan view.)

![cases](http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-10-082705.png)

For one box we have the information below:

![boxInfo](http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-12-040306.png)

For two boxes we have the aggregated information below:

![2boxInfo](http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-12-040933.png)

Consequently, the three possibilities can be represented as:

![quantifiedCases](http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-12-042106.png)

Now we claim that, only when both situtaion hold, we have collisions. There are 3 conjugated cases, but all with similar form:

![rigidCases](http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-12-044416.png)

In rigid form we represent the 4 cases as:
$$
\begin{equation}
\begin{aligned}
\Rightarrow \{\ \{x_{2,min}<x_{1,max}\} \land \{y_{2,min}<y_{2,max} \}\ \} \\
\lor\{\ \{x_{2,min}<x_{1,max}\} \land \{y_{2,max}>y_{1,min} \} \ \} \\
\lor\{\ \{x_{2,max}>x_{1,min}\} \land \{y_{2,mmin}<y_{2,max} \} \ \} \\
\lor\{\ \{x_{2,max}>x_{1,min}\} \land \{y_{2,max}>y_{1,min} \} \ \}
\end{aligned}
\end{equation}
$$



Otherwise, we can use the vertices to complete the same functionality. The detailed code is shown on GitHub, so no documentation here is provided.

## Shift Vector

The important part is the shift vector. The method to judge the shift vector is decided into different cases

![shiftCases](http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-12-122923.png)

