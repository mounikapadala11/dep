---
title: "Python"
# description: ""
# dateString: Aug 2021 - Oct 2021
# draft: false
# tags: ["RCNN", "OpenCV", "Computer Vision"]
# showToc: false
# weight: 207
# cover:
#   image: "projects/gaze-tracking-goggles/cover.jpg"
---

<!-- > Presented in the 4th International and 19th National Conference on Machine and Mechanisms (**iNaCoMM 2019**)

> Published in the **Springer 2019** -->

### 🔗 [Publication](https://spast.org/techrep/article/view/865//)

## Description

Worked on a self-project to identify empty parking spaces using an input video from surveillance cameras in parking lots.

Developed a scalable project using OpenCV and Mask RCNN to help reduce the requirement for parking sensors
with 73.8 % accuracy.

Published research paper “Empty Parking Space Detection using Mask R-CNN and Computer Vision” is published in ‘SPAST Journal’.

<!--
The aim of the project was to build goggles which could find where the user was looking (gaze), the category of object the user was looking at, and the duration of attention on that object. The goggles had 3 camera modules, one on each eye to track the pupil movement and the third one for mapping the gaze to the real world. Thresholding was used to detect the pupils and contours were used to find its centre. Various important parameters such as pupil velocity, acceleration, and fixation time were calculated for further statistical analysis. **Single Shot Descriptor**, with **VGG16** as backbone, was used to detect the objects the user was gazing at. Additionally, a GUI was made using **TkInter** for ease of use.


