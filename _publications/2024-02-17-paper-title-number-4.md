---
title: "MCGMapper: Light-Weight Incremental Structure from Motion and Visual Localization With Planar Markers and Camera Groups"
collection: publications
category: conferences
# permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is about marker mapping and localization.'
date: 2024-06-31
venue: 'International Conference on Intelligent Robots and Systems (IROS) · IROS 2024. 14 October- 18 October 2024 | Abu Dhabi, UAE'
paperurl: 'https://arxiv.org/abs/2405.16599'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---


## Abstract
Structure from Motion (SfM) and visual localization in indoor texture-less scenes and industrial scenarios present prevalent yet challenging research topics. Existing SfM methods designed for natural scenes typically yield low accuracy or map-building failures due to insufficient robust feature extraction in such settings. Visual markers, with their artificially designed features, can effectively address these issues. Nonetheless, existing marker-assisted SfM methods encounter problems like slow running speed and difficulties in convergence; and also, they are governed by the strong assumption of unique marker size. In this paper, we propose a novel SfM framework that utilizes planar markers and multiple cameras with known extrinsics to capture the surrounding environment and reconstruct the marker map. In our algorithm, the initial poses of markers and cameras are calculated with Perspective-n-Points (PnP) in the front-end, while bundle adjustment methods customized for markers and camera groups are designed in the back-end to optimize the 6-DOF pose directly. Our algorithm facilitates the reconstruction of large scenes with different marker sizes, and its accuracy and speed of map building are shown to surpass existing methods. Our approach is suitable for a wide range of scenarios, including laboratories, basements, warehouses, and other industrial settings. Furthermore, we incorporate representative scenarios into simulations and also supply our datasets with pose labels to address the scarcity of quantitative ground-truth datasets in this research field. The datasets and source code are available on GitHub.

## Overview
![A4LidarTag](/images/mcgmapper.png)
## Citation

```text
@article{xie2024mcgmapper,
  title={MCGMapper: Light-Weight Incremental Structure from Motion and Visual Localization With Planar Markers and Camera Groups},
  author={Xie, Yusen and Huang, Zhenmin and Chen, Kai and Zhu, Lei and Ma, Jun},
  journal={arXiv preprint arXiv:2405.16599},
  year={2024}
}
```