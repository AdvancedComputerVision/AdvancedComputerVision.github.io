---
layout: post 
title: "Session 6: EfficientDet: Scalable and Efficient Object Detection"
excerpt_separator: <!--more-->
categories: misc
project: false
active: false
---


We read and discuss   
EfficientDet: Scalable and Efficient Object Detection
by Mingxing Tan, Ruoming Pang & Quoc V. Le
https://arxiv.org/pdf/1911.09070.pdf

<!--more-->


<iframe width="560" height="315" src="https://www.youtube.com/embed/7jG4II7BSIM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


[meetup recordings](https://www.youtube.com/watch?v=oJsmBuGMeQY&feature=youtu.be) on youtube


Notes:
* Many statements are based on intuition
* Architecture: Bi-directional  feature  pyramid  network + skip connections + learned weighting + compound scaling  
* Training: Focal loss, Swish activation
* Some interesting ablation studies regarding the scale jitter for longer training schedules
* For the next time: CLIP
* Computer Vision Meetup Berlin needs an organizer 
