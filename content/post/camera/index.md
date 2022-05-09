---
title: Camera Movements and Anti-shake Solutions
subtitle: Types of camera movements and Anti-shake solutions to cameras.

# Summary for listings and search engines
summary: 

# Link this post with a project
projects: ['data-expand']

# Date published
date: '2021-06-26T00:00:00Z'

# Date updated
lastmod: '2022-05-01T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Camera Internal and External Parameters'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Computer Vision

categories:

---

# Camera Movements and Anti-shake Solutions

This report is a regular report on Data Expansion.

This week we focused on two main points:

-   Types of camera movements.
-   Anti-shake solutions to cameras.

Both of which are theoretical ways for next week’s use.

## Basic Knowledge

Here comes the basic knowledge one need to command if he wants to get through the ideas in this blog.

### Internal and External Parameters

A camera can be decribed according to two parameters - one internal and another external.

#### External Parameters

External parameters are the parameters concerning with the pixels outside the camera. All objects we see are initially objects in the world - so they are in the WORLD coordinate system. In other words, we transform the tensor in homogeneous 3D world coordinate into Euclidean
equivalent 2D camera coordinate (homogeneous 2D coordinate). In rigid form it is expressed with
$$
H_{o2k}=\begin{bmatrix}R&T\\\ 0&1\end{bmatrix}
$$
where $R$ is the rotational matrix calculated from camera orientation, i.e. $R_z\cdot R_y\cdot R_x$$,$ and $T$ is $-R^{-1}*X$ where $X$ is the camera position in the world coordinate. Note that the matrix **changes as the frames go on**. Thus, the actual extpara matrix should be of shape $[x,3,4]$. For more details about the rotational matrix and transmittion matrix, we conclude that

-   The rotational matrix decribes the **direction** of the axis of the world correspond relative to the axis of the camera correspond.
-   The translational matrix describes the position of the **principle point of the space** in the camera correspond.

#### Internal Parameters

Internal parameters concerns with the camera itself. In other words, it transforms the tensor into sensor coordinate and eliminate the depth dimension. Thus, the internal matrix is **stable** (not time-dependant), which means that the matrix should be $[3,3]$. Rigidly, the matrix can be expressed as
$$
K=\begin{bmatrix}f_{x}&s&x_{0}\\\ 0&f_{y}&y_{0}\\\ 0&0&1\end{bmatrix}
$$
where $f_x, f_y$ are the [focal distances](https://baike.baidu.com/item/%E7%84%A6%E8%B7%9D/1880759), $s$ is the [corresponds of the principle point of photograph](https://baike.baidu.com/item/%E5%83%8F%E4%B8%BB%E7%82%B9), and $x_0$ is the descriptor of coordinate tilt. Roughly speaking, internal parameter matrix simply redefines the position and scale of the graph.

To express in a more clear pattern we gain the figure below.

![](http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-27-025041.png)

### Camera Distortions

Distortions are inevitable when dealing with the internal parameters. This part is dealed by Mu Xie. Detailed knowledge is handled in [this blog](http://zhaoxuhui.top/blog/2018/04/17/CameraCalibration.html). There are basically 2 types of distortions:

- Radial Distortion.

  ![](http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-27-053814.jpg)

- Tangent Distortion.

  ![](http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-27-054416.jpg)

## Camera Movement Models

- Drone View Camera (drones)

  - Down-headed

  - Racial distortion

  - Translational movement

    ![](http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-27-054118.jpg)

- [Wide-angle Camera](https://baike.baidu.com/item/%E9%95%9C%E5%A4%B4%E7%95%B8%E5%8F%98) (surveillance camera)

  -   Horizontally headed
  -   Strong radial distortion
  -   Rotational movement

![](http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-27-053946.jpg)



-   Phone Camera
    -   Horizontally headed
    -   Strong rotational and translational movement; strong blurring

## Camera Shaking Simulation

-   For drone model only. Ignore wide-angle camera shake.
-   Two types of shake
    -   Motion Stabling
    -   ![](http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-27-055325.png)
    -   Motion Smoothing
    -   ![](http://jacklovespictures.oss-cn-beijing.aliyuncs.com/2021-06-27-060512.png)

To create shaking videos, we need to know in what situation first. Using phones and drones are likely to have shakes. Phones have the most intensive motion strikes.