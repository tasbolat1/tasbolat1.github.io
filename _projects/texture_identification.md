---
layout: page
title: Extended Tactile Perception
description: Vibration Sensing through Tools and Grasped Object
img: assets/img/extense/tactile_extended_main.jpg
importance: 2
category: Tactile Perception
---

Humans display the remarkable ability to sense the world through tools and other held objects. For example, we are able to pinpoint impact locations on a held rod and tell apart different textures using a rigid probe.

In this work, weconsider how we can enable robots to have a similar capacity, i.e., to embody tools and extend perception using standard grasped objects. We propose that vibro-tactile sensing using dynamic tactile sensors on the robot fingers, along with machine learning models, enables robots to decipher contact information that is transmitted as vibrations along rigid objects. 


<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/extense/tactile_extended_main.jpg" title="tool extended image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <strong>Fig.1</strong> Our goal is to enable robots to extend their tactile perception through standard objects such as tools. (A) We show that robots are able to accurately localize taps on an acrylic rod using fast vibro-tactile sensing and machine learning. Vibrations caused by the tap travel up the rod where they are picked up by a dynamic tactile sensor (the NUSkin in this image). The signal is captured and mapped into a tap position using simple models and learned features. We provide results on two additional tasks: (B) grasp stability classification during object handover and (C) food classification through a fork
</div>

We demonstrate that fine localization on a held rod is possible using our approach. Next, we show that vibro-tactile perception can lead to reasonable grasp stability prediction during object handover, and accurate food identification using a standard fork.

For more on this work, please look at the following resources:

<ul>
<li><a href="https://arxiv.org/abs/2106.00489">Arxiv</a> paper with latest update</li>
<li><a href="https://github.com/clear-nus/ext-sense">Code and Data</a></li>
<li><a href="assets/pdf/presentation_IROS2021.pdf">Slides</a></li>
</ul>

If you build upon our results and ideas, please use this citation.
{% raw %}
```html
@inproceedings{taunyazov2021extended,
  title = {Extended Tactile Perception: Vibration Sensing through Tools and Grasped Objects},
  author = {Taunyazov, Tasbolat and Song, Luar Shui and Lim, Eugene and See, Hian Hian and Lee, David and Tee, Benjamin CK and Soh, Harold},
  booktitle = {IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  pages = {1755--1762},
  year = {2021},
  organization = {IEEE},
}
```
{% endraw %}
