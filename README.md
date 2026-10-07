# π²: A Simple Framework for 2D-to-3D Registration

Official repository for **π² (P2I)**, accepted at **NeurIPS 2026**.

[Paper](https://openreview.net/forum?id=vm3afPOLqE)

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
