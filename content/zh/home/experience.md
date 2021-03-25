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
    location: 中国
    date_start: '2019-11-01'
    date_end: '2020-11-15'
    description: |2-
        主要完成了以下工作
        
        * 制作了一个大规模被动非视域成像数据集，数据集包含了超过300万张图片；
        * 提出了一个适合被动非视域成像任务的深度学习网络结构。

  - title: 单光子主动非视域成像
    company: 电子科技大学，图像处理研究所
    company_url: ''
    location: 
    date_start: '2018-08-31'
    date_end: ''
    description: |2-
        主要完成了以下工作
        
        * 根据O'Toole等人的文章搭建了共焦非视域成像平台；
        * 使用LCT模型渲染合成了主动NLOS仿真数据集；
        * 实现了基于GAN的3D非视距成像。
  - title: 用于血液制品运输的无人机路径规划(以牛津郡为例)
    company: 牛津大学
    company_url: 'https://www.lmh.ox.ac.uk/'
    location: 英国
    date_start: '2019-07-31'
    date_end: '2019-08-31'
    description: 针对牛津郡各个医院间使用无人机的血液运输任务，我们设计了要给路径规划算法。该算法的设计综合考虑了人口、建筑物、环境和当地法律等影响因素。

  - title: 基于Arduino的自动灌溉系统
    company: 物联网实验室, 詹姆斯库克大学
    company_url: 'https://www.jcu.edu.au/college-of-science-and-engineering/internet-of-things'
    location: 澳大利亚
    date_start: '2017-07-20'
    date_end: '2017-08-06'
    description: 实现了一个能够自动根据温湿度开关阀门的自动灌溉系统。

---
