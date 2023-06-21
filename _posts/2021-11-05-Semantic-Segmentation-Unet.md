---
title: "Semantic Segmentation: U-Net"
date:   2021-11-05
permalink: /Semantic-Segmentation-Unet/
tags:
  - Computer Vision
  - Deep Learning
  - Bio-Medical Imaging
  - Semanctic Segmentation

---

Semantic segmentation is a computer vision task that involves classifying each pixel in an image. One popular model for semantic segmentation is U-Net, which was initially designed for biomedical image segmentation but has been widely adopted beyond that domain. U-Net follows an encoder-decoder architecture, where the encoder performs feature extraction and the decoder upsamples the features to the original image size. The encoder can use different convolutional neural network models such as VGG16, ResNet, or EfficientNet. The decoder upsamples and merges the features, originally done with transpose convolutions but now often replaced with bilinear upsampling. Evaluation metrics for U-Net include pixel accuracy, intersection over union (IOU), and the Dice coefficient. Various datasets are available for benchmarking semantic segmentation models, such as PASCAL VOC 2012, COCO 2018 Stuff, and Cityscapes. There are also publicly available implementations of semantic segmentation models in PyTorch and TensorFlow.

Article link : [Here](https://medium.com/red-buffer/semantic-segmentation-u-net-1e5c0f4516a5)
