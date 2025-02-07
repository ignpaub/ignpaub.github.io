---
title: "LiCAR: pseudo-RGB LiDAR image for CAR segmentation"
collection: publications
category: conferences
permalink: /publication/2025_robovis
excerpt: ' '
date: 2025-02-27
venue: '2025 International Conference on Robotics, Computer Vision and Intelligent Systems, Porto (Portugal), 25-27 February'
paperurl: 'http://ignpaub.github.io/files/2025_robovis.pdf'
citation: "Ignacio de Loyola Páez-Ubieta, Edison Velasco-Sánchez, Santiago T. Puente (2025). &quot;LiCAR: pseudo-RGB LiDAR image for CAR segmentation.&quot; <i>2025 5th International Conference on Robotics, Computer Vision and Intelligent Systems (ROBOVIS)</i>. Accepted, but awaiting presentation and publication."
---

With the advancement of computing resources, an increasing number of Neural Networks (NNs) are appearing for image detection and segmentation appear. However, these methods usually accept as input a RGB 2D image. On the other side, Light Detection And Ranging (LiDAR) sensors with many layers provide images that are similar to those obtained from a traditional low resolution RGB camera. Following this principle, a new dataset for segmenting cars in pseudo-RGB images has been generated. This dataset combines the information given by the LiDAR sensor into a Spherical Range Image (SRI), concretely the reflectivity, near infrared and signal intensity 2D images. These images are then fed into instance segmentation NNs. These NNs segment the cars that appear in these images, having as result a Bounding Box (BB) and mask precision of 88% and 81.5% respectively with You Only Look Once (YOLO)-v8 large. By using this segmentation NN, some trackers have been applied so as to follow each car segmented instance along a video feed, having great performance in real world experiments.

Keywords: Artificial Intelligence, Mobile Robots, Neural Networks, Instance Segmentation, LiDAR, YOLO
