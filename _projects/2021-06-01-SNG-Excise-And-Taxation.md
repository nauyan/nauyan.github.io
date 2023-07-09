---
title: "SNG Excise And Taxation"
date:   2021-06-01
permalink: /SNG-Excise-And-Taxation/
tags:
  - Computer Vision
  - Deep Learning
  - Instance Segmentation
  - Satellite Imagery
  - Python
  - Tensorflow
  - Mask R-CNN
---

The goal of the project is to automate the Property Tax Collection. This is carried out by detecting properties (Commercial - Residential - Combined) by applying an instance segmentation model (Detectron 2 by facebook research) on select Mapbox images filtered using a unique distance formula. The complete pipeline will run automatically every 6 months and update any changes due to new properties around the regions using a custom designed IOU calculation system. The instance segmentation model has been trained using custom labeled data from Mapbox and the complete pipeline has been optimized for faster inference and accurate "new properties" estimation. I worked as a lead machine learning engineer responsible for R&D, developing baseline, model training, getting data labeling from Annotators and managing multiple machine learning engineers for developing property detection backend.
