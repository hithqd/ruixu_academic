---
title: Time-resolved NLOS imaging algorithm based on GAN
date: 2019-09-25T07:10:12.824Z
draft: false
# 使用GAN完成数据驱动的主动非视距成像
summary: Use GAN to complete data-driven active non-line-of-sight imaging
featured: false
tags:
- GAN
- Deep Learning
- NLOS imaging
- Optics
- Active Imaging
external_link: ""
image:
  focal_point: Smart
  caption: Using GAN to complete 3D NLOS reconstruction
  preview_only: false
---

<!-- 本项目是我的本科毕业设计，它的摘要如下。 -->
This project is my undergraduate graduation project, its summary is as follows

<q>
Non-line-of-sight imaging technology that can image objects outside the field of view has important application prospects in many fields, such as security and automatic driving. Traditional non-line-of-sight imaging studies usually use an imaging model to model the data acquisition process and reconstruct the hidden scene by solving the imaging model. At present, traditional imaging models is not accurate enough so that they can only reconstruct a simple hidden scene. In addition, traditional reconstruction algorithms have a long reconstruction time and are difficult to apply in real time applications.

In order to overcome the shortcomings of traditional imaging and improve the reconstruction speed, this paper proposes a three-dimensional reconstruction algorithm for non-line-of-sight imaging based on deep learning. The reconstruction algorithm firstly obtains 30,000 simulation data as a dataset by simulating existed imaging model. Then, we build, train and test a reconstructing algorithm based on deep learning using the conditional GAN with similar results to traditional reconstruction algorithms. Through contrast experiments, it is concluded that the deep learning-based reconstruction algorithm is more robust to parameter correction errors and can effectively reduce the high dependence on parameter calibration. In addition, based on deep learning, the reconstruction algorithm only needs 20ms to reconstruct a single hidden scene, while the traditional algorithm requires at least 0.2s. Therefore, the reconstruction algorithm based on deep learning can greatly improve the reconstruction speed of non-line-of-sight imaging. Finally, this paper analyzes the shortcomings and improvement schemes of the proposed non-line-of-sight imaging algorithm based on deep learning.
</q>

<!-- 然而，这个项目未能考虑到SPAD sensor带来的噪声，因此没能在公开的数据上取得良好的结果。2020年CVPR的如下工作使用U-Net取得了较好的结果： -->
However, this project failed to take into account the noise caused by the SPAD sensor, so it failed to achieve good results on the public data. Chopite et al.'s work in CVPR 2020 has achieved good results using U-Net:

J. G. Chopite, M. B. Hullin, M. Wand, and J. Iseringhausen, “Deep Non-Line-of-Sight Reconstruction,” 2020.
