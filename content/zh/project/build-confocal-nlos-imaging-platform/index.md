---
title: 搭建共焦非视距成像平台
subtitle: according to O'Toole et al.
summary: 根据O'Toole等人的文章搭建的共焦非视距成像系统
date: 2020-01-25T04:41:26.771Z
draft: false
featured: false
tags:
- NLOS imaging
- TCSPC
- Light
external_link: ""
image:
  focal_point: Smart
  caption: Confocal NLOS imaging Setup
  preview_only: false

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

2018年中，在导师的指导下，我们打算复现斯坦福大学O'Toole等人在时间分辨主动非视域成像方面的工作

> M. O’Toole, D. B. Lindell, and G. Wetzstein, “Confocal non-line-of-sight imaging based on the light-cone transform,” Nature, vol. 555, no. 7696, p. 338, 2018, doi: https://doi.org/10.1038/nature25489.

之后，我们购买了相应的设备，包括超快脉冲激光器、单光子雪崩二极管、时间相关单光子计数器等，并购买了光学平台。

尽管实验室并没有光学实验的基础，但我们还是建立了共焦NLOS成像系统。这个系统目前能够对一些简单的NLOS场景成像，但仍存在时间抖动很大的问题。除此之外，我们的函数发生器目前也还存在一些问题，无法和扫描振镜精确同步从而完成高速扫描。目前我们正在积极解决这些已经发现的问题。

<!-- In mid-2018, under the guidance of our mentor, we plan to follow the work of Stanford University O'Toole and others on time-resolved NLOS imaging

> M. O’Toole, D. B. Lindell, and G. Wetzstein, “Confocal non-line-of-sight imaging based on the light-cone transform,” Nature, vol. 555, no. 7696, p. 338, 2018, doi: https://doi.org/10.1038/nature25489.

We purchased corresponding equipment, including ultrafast pulse lasers, single-photon avalanche diodes, time-dependent single-photon counters, etc., and purchased an optical platform.

Although our laboratory does not have a basis for optical experiments, we have established a confocal NLOS imaging system. This system can currently image some simple NLOS scenes, but there is still a problem of large time jitter (which means a low horizontal resolution). At present, we are trying our best to improve the reconstruction quality from both perspective of hardware and algorithm. -->