---
title: 基于GAN的单光子非视域成像
date: 2019-09-25T07:10:12.824Z
draft: false
# 使用GAN完成数据驱动的主动非视距成像
summary: 使用GAN完成数据驱动的主动非视域成像
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
  caption: 使用GAN完成3D NLOS重建
  preview_only: false
---

<!-- 本项目是我的本科毕业设计，它的摘要如下。 -->
本项目是我的本科毕业设计。

非视距成像是一个病态问题，因此使用各种先验作为约束是实现高质量重建必须采用的方法。已有的非视距成像研究已经充分考虑了非负性、稀疏性等先验，但缺乏对场景先验的有效利用。深度学习算法能够很好地学习场景先验。因此，我们尝试将深度学习（GAN）应用到非视距成像问题中。我们首先基于LCT模型，通过数据渲染的方法得到了共焦NLOS仿真数据集；之后仿照DeblurGAN构建了一个3D to 3D的生成对抗网络。通过训练和测试，我们的网络能够在仿真数据上取得优秀的效果。

<!-- 然而，这个项目未能考虑到SPAD sensor带来的噪声，因此没能在公开的数据上取得良好的结果。2020年CVPR的如下工作使用U-Net取得了较好的结果： -->
然而，这个项目未能考虑到SPAD sensor带来的噪声，因此没能在公开的数据上取得良好的结果。后来，2020年CVPR中的如下工作考虑了SPAD sensor带来的噪声，并使用3D U-Net取得了较好的结果：

> J. G. Chopite, M. B. Hullin, M. Wand, and J. Iseringhausen, “Deep Non-Line-of-Sight Reconstruction,” 2020.
