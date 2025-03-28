---
title: "Transferability of labels between multilens cameras"
collection: publications
category: conferences
permalink: /publication/2025_visapp
excerpt: ' '
date: 2025-02-28
venue: '2025 International Conference on Computer Vision Theory and Applications, Porto (Portugal), 26-28 February'
paperurl: 'http://ignpaub.github.io/files/2025_visapp.pdf'
citation: "Ignacio de Loyola Páez-Ubieta, Daniel Frau-Alfaro, Santiago T. Puente (2025). &quot;Transferability of labels between multilens cameras.&quot; <i>2025 20th International Conference on Computer Vision Theory and Applications (VISAPP)</i>. doi: 10.5220/0013154100003912."
---

In this work, a new method for automatically extending Bounding Box (BB) and mask labels across different channels on multilens cameras is presented. For that purpose, the proposed method combines the well known phase correlation method with a refinement process. During the first step, images are aligned by localizing the peak of intensity obtained in the spatial domain after performing the cross correlation process in the frequency domain. The second step consists of obtaining the best possible transformation by using an iterative process maximising the IoU (Intersection over Union) metric. Results show that, by using this method, labels could be transferred across different lens on a camera with an accuracy over 90\% in most cases and just by using 65 ms in the whole process. Once the transformations are obtained, artificial RGB images are generated, for labeling them so as to transfer this information into each of the other lens. This work will allow users to use this type of cameras in more fields rather than satellite or medical imagery, giving the chance of labeling even invisible objects in the visible spectrum. 

Keywords: Multispectral Imagery, Labeling, Phase Correlation, Label Transfer, Pills
