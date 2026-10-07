<h1 align="center">π²: A Simple Framework for 2D-to-3D Registration</h1>

<div align="center">

**NeurIPS 2026**

Hao Deng<sup>1</sup>, Xiangtai Yang<sup>1</sup>, Guangmingzi Yang<sup>2</sup>, Xijing Wang<sup>1</sup>,<br>
Yuanxiao Ma<sup>2</sup>, Sisi Li<sup>1</sup>, Zhiqiang Tian<sup>1</sup>, Shaoyi Du<sup>1*</sup>

<sup>1</sup> Xi'an Jiaotong University &nbsp;&nbsp; <sup>2</sup> China Mobile

<a href="https://openreview.net/forum?id=vm3afPOLqE"><img src="https://img.shields.io/badge/Paper-OpenReview-b31b1b" alt="Paper on OpenReview"></a>
<a href="https://dengh293.github.io/p2i-project-page/"><img src="https://img.shields.io/badge/Project_Page-green" alt="Project Page"></a>

</div>

---

## Overview

π² addresses image-to-point-cloud registration by predicting the coordinates of sampled LiDAR points in the target camera frame. Each prediction retains the identity of its source point, providing paired 3D points for direct, closed-form pose recovery through SVD alignment.

The framework combines image and point-cloud features for camera-coordinate regression. During training, a camera-ray constraint provides complementary geometric supervision.

## Release status

**Code and pretrained checkpoints are being prepared for release.**

This repository currently serves as the project landing page. The release will include:

- Model implementation and pretrained checkpoints
- Environment setup and data preparation instructions
- Training and evaluation instructions

Please check back for updates.
