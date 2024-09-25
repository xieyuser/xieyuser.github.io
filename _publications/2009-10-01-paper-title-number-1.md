---
title: "A4LidarTag: Depth-Based Fiducial Marker for Extrinsic Calibration of Solid-State Lidar and Camera"
collection: publications
category: manuscripts
# permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about calibration of solid-state LiDAR and camera.'
date: 2022-7-01
venue: 'IEEE Robotics and Automation Letters ( Volume: 7, Issue: 3, July 2022)'
# slidesurl: 'https://ieeexplore.ieee.org/document/9770363'
paperurl: 'https://ieeexplore.ieee.org/document/9770363'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

## Abstract

Visual-based simultaneous localization and mapping (SLAM) systems perform weakly in object tracking and map reconstruction due to the unreliable depth measurement originating from image-only data. Light Detection and Ranging (LiDAR) can be coupled to overcome the drawback of uncertain depth estimation. The prerequisite for performing data fusion is to align visual-Lidar sensors to a specific coordinate system with extrinsic pose by calibrating. The conventional extrinsic calibration frameworks either rely on markers in artificial large-size calibration boards or uncontrollable natural scenes (Fig. 2 ), limiting stability and convenience. In this paper, we have designed a novel marker pattern, A4LidarTag, composed of circular holes. The difference in depth measurement is used to encode location information. Based on A4LidarTag, the automatic extrinsic calibration framework between solid-state Lidar (SSL) and the camera is developed. The proposed framework can be implemented in close range (within 1 m) and on an A4-size calibration board. The average reprojection error resulting from Lidar point clouds projection is about 0.12pixels. Experiments show excellent efficiency and versatility in both indoor and outdoor scenes.

## Overview
![A4LidarTag](/images/a4lidartag.png)

## Citation
```text

@ARTICLE{9770363,
  author={Xie, Yusen and Deng, Lei and Sun, Ting and Fu, Yeyu and Li, Jian and Cui, Xinglong and Yin, Hanxi and Deng, Shuixin and Xiao, Junwei and Chen, Baohua},
  journal={IEEE Robotics and Automation Letters}, 
  title={A4LidarTag: Depth-Based Fiducial Marker for Extrinsic Calibration of Solid-State Lidar and Camera}, 
  year={2022},
  volume={7},
  number={3},
  pages={6487-6494}}

```