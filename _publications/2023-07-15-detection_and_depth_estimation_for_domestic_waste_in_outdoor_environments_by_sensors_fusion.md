---
title: "Detection and depth estimation for domestic waste in outdoor environments by sensors fusion"
collection: publications
category: conferences
permalink: /publication/2023_ifac
excerpt: ' '
date: 2023-07-15
venue: '2023 World Congress of the International Federation of Automatic Control, Yokohama (Japan), 8-14 July'
paperurl: 'http://ignpaub.github.io/files/2023_ifac.pdf'
citation: "Ignacio de Loyola Páez-Ubieta, Edison Velasco-Sánchez, Santiago T. Puente, Francisco A. Candelas (2023). &quot;Detection and depth estimation for domestic waste in outdoor environments by sensors fusion.&quot; <i>2023 22nd World Congress of the International Federation of Automatic Control (IFAC)</i>. 56(2), 9276-9281, doi: 10.1016/j.ifacol.2023.10.211"
---

In this work, we estimate the depth in which domestic waste are located in space from a mobile robot in outdoor scenarios. As we are doing this calculus on a broad range of space (0.3 - 6.0 m), we use RGB-D camera and LiDAR fusion. With this aim and range, we compare several methods such as average, nearest, median and center point, applied to those which are inside a reduced or non-reduced Bounding Box (BB). These BB are obtained from segmentation and detection methods which are representative of these techniques like Yolact, SOLO, You Only Look Once (YOLO)v5, YOLOv6 and YOLOv7. Results shown that, applying a detection method with the average technique and a reduction of BB of 40%, returns the same output as segmenting the object and applying the average method. Indeed, the detection method is faster and lighter in comparison with the segmentation one. The committed median error in the conducted experiments was 0.0298 ± 0.0544 m.

Keywords: Information and sensor fusion, Perception and sensing, Sensing, Autonomous mobile robots, Localization, Deep learning