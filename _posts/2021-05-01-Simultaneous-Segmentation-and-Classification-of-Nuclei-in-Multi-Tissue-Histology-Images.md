---
title: "Simultaneous Segmentation and Classification of Nuclei in Multi-Tissue Histology Images"
date:   2021-05-01
permalink: /Simultaneous-Segmentation-and-Classification-of-Nuclei-in-Multi-Tissue-Histology-Images/
tags:
  - Machine Learning
  - Computer Vision
  - Deep Learning
  - Bio-Medical Imaging
  - Computational Pathology
---


The article provides a detailed explanation of the Hover-Net model, which is a state-of-the-art model used for nuclei instance segmentation in computational pathology. The Hover-Net architecture consists of an encoder-decoder structure. The encoder block performs feature extraction, gradually decreasing spatial resolution and increasing depth. The decoder block upsamples the extracted features and includes branches for nuclear pixel segmentation, generation of horizontal and vertical feature maps, and nuclear classification. The Hover-Net loss function incorporates different loss terms for each branch. The evaluation metrics for the model include ensemble dice, aggregated Jaccard index, panoptic quality for instance segmentation, and F-score for nuclei classification. The model has been trained and validated on various datasets and demonstrates superior performance compared to other models in terms of instance segmentation and nuclei classification. The article also includes qualitative results showcasing the performance of different models on various datasets.

Article link : [Here](https://medium.com/red-buffer/simultaneous-segmentation-and-classification-of-nuclei-in-multi-tissue-histology-images-6cd56b857ce6)
