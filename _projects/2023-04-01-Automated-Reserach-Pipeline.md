---
title: "Automated Reserach Pipeline"
date:   2023-04-01
permalink: /Automated-Reserach-Pipeline/
tags:
  - Computer Vision
  - Python
  - LightAutoML (LAMA)
  - GANs
  - AWS SageMaker
  - AWS SageMaker Studio
  - Distributed Training
  - Docker
---

The client had developed an InPainting pipeline for repairing the texture of mega scans using a GAN based model known as LaMA that was capable of running with 256x256 sized image patches. We built a multi-node and multi-GPU training pipeline that can be used for training a 5 Billion image dataset using AWS SageMaker along with all the housekeeping tasks required for training. My responsibility was to make the training job compatible with Distributed Training frameworks. Additionally was leading a team of engineers involved in the project and collaborating with clients for integrating the training pipeline in their existing workflows.




