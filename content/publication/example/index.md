---
abstract: >-
  Non-line-of-sight imaging technology that can image objects outside the field
  of view has important application prospects in many fields, such as security
  and automatic driving. Traditional non-line-of-sight imaging studies usually
  use an imaging model to model the data acquisition process and reconstruct the
  hidden scene by solving the imaging model. At present, traditional imaging
  models is not accurate enough so that they can only reconstruct a simple
  hidden scene. In addition, traditional reconstruction algorithms have a long
  reconstruction time and are difficult to apply in real time applications.


  In order to overcome the shortcomings of traditional imaging and improve the reconstruction speed, this paper proposes a three-dimensional reconstruction algorithm for non-line-of-sight imaging based on deep learning. The reconstruction algorithm firstly obtains 30,000 simulation data as a dataset by simulating existed imaging model. Then, we build, train and test a reconstructing algorithm based on deep learning using the conditional GAN with similar results to traditional reconstruction algorithms. Through contrast experiments, it is concluded that the deep learning-based reconstruction algorithm is more robust to parameter correction errors and can effectively reduce the high dependence on parameter calibration. In addition, based on deep learning, the reconstruction algorithm only needs 20ms to reconstruct a single hidden scene, while the traditional algorithm requires at least 0.2s. Therefore, the reconstruction algorithm based on deep learning can greatly improve the reconstruction speed of non-line-of-sight imaging. Finally, this paper analyzes the shortcomings and improvement schemes of the proposed non-line-of-sight imaging algorithm based on deep learning.
slides: example
url_pdf: ""
publication_types:
  - "7"
authors:
  - Ruixu
  - Geng
author_notes: []
publication: Bachelor Thesis
summary: This thesis synthesizes NLOS dataset by rendering (based on LCT
  proposed by O'Toole et al.), and then reconstructs it by GAN (modified from
  DeblurGAN).
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: Active NLOS imaging based on deep learning
subtitle: ""
doi: ""
featured: true
tags: []
categories: []
projects:
  - example
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
  alt_text: ""
  filename: example.jpg
date: 2019-06-01T00:00:00.000Z
url_slides: ""
publishDate: 2019-06-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
