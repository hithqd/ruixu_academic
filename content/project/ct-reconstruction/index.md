---
title: CT system parameter calibration and imaging
date: 2017-09-25T07:38:57.525Z
# 使用优化算法和Radon变换完成CT系统的参数标定和成像
summary: Use optimized algorithm and Radon transform to complete the parameter calibration and imaging of a CT system
draft: false
featured: false
external_link: ""
tags:
- image resoration
image:
  focal_point: Smart
  caption: Parameter calibration
  preview_only: false
---
This project is concerned about CT system parameter calibration and imaging. First,a plane orthogonal coordinate system with the origin at the center of the ellipse is established. The analytical relationship between the length of the ray passing through the medium and the ray direction,the distance between the detector unit and the three parameters from the origin to the ray is given; Then the ratio of the information received by two adjacent receivers at each rotation is theoretically equal to the ratio of their corresponding rays through the length,using the receiver absorption information and the ratio of the corresponding ray to the length of the ray. Taking the least square error of the two values as the objective function, the nonlinear programming model is established to obtain the ray direction of the unit distance and rotation, and the parameters of the CT system are calibrated. In view of the reduction of receiver receiving information in CT system, a restoration model is established by using Radon inverse transform to solve and verify the intersection method of tangent area.