---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: 研究经历
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
# - title: Passive NLOS Imaging 
#   company: Image Processing Institute, UESTC
#   company_url: ''
#   location: China
#   date_start: '2019-11-31'
#   date_end: '2020-11-15'
experience:
  - title: 数据驱动的被动非视域成像
    company: 电子科技大学，图像处理研究所
    company_url: ''
    location: China
    date_start: '2019-11-01'
    date_end: '2020-11-15'
    description: |2-
        主要完成了以下工作
        
        * 制作了一个大规模被动非视域成像数据集，数据集包含了超过300万张图片；
        * 提出了一个适合被动非视域成像任务的深度学习网络结构。

  - title: 单光子主动非视域成像
    company: 电子科技大学，图像处理研究所
    company_url: ''
    location: China
    date_start: '2018-08-31'
    date_end: ''
    description: |2-
        主要完成了以下工作
        
        * 根据O'Toole等人的文章搭建了共焦非视域成像平台 
        * Rendered a NLOS dataset using LCT.
        * Exploited GAN to complete 3D NLOS reconstruction.
  - title: Drones' path planning algorithm for blood delivery services 
    company: Lady Margaret Hall, Oxford University
    company_url: 'https://www.lmh.ox.ac.uk/'
    location: UK
    date_start: '2019-07-31'
    date_end: '2019-08-31'
    description: We designed a path planning algorithm for drones that transport blood between Oxfordshire hospitals, considering factors such as the population, architecture, environment, and law.

  - title: Arduino-based automatic soil irrigation system
    company: IoT Lab, James Cook University
    company_url: 'https://www.jcu.edu.au/college-of-science-and-engineering/internet-of-things'
    location: Australia
    date_start: '2017-07-20'
    date_end: '2017-08-06'
    description: Completed an arduino-based irrigation device that automatically opens valves based on temperature and humidity.

---
