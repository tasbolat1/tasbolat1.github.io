---
layout: page
title: Fast texture classification using tactile neural coding and spiking neural network 
small_title: Neural Coding
description: 
img: assets/img/fast_texture/fast_texture.jpg
importance: 4
category: "Feel: Tactile Sensing"
---

Touch is arguably the most important sensing modality in physical interactions. However, tactile sensing has been largely under-explored in robotics applications owing to the complexity in making perceptual inferences until the recent advancements in machine learning or deep learning in particular. Touch perception is strongly influenced by both its temporal dimension similar to audition and its spatial dimension similar to vision. While spatial cues can be learned episodically, temporal cues compete against the system’s re-sponse/reaction time to provide accurate inferences. In this paper, we propose a fast tactile-based texture classification framework which makes use of the spiking neural network to learn from the neural coding of the conventional tactile sensor readings. The framework is implemented and tested on two independent tactile datasets collected in sliding motion on 20 material textures. Our results show that the framework is able to make much more accurate inferences ahead of time as compared to that by the state-of-the-art learning approaches.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fast_texture/fast_texture.jpg" title="robot slide image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <strong>Fig.1</strong> An overview of texture classification using tactile data: raw tactile data of surface is encoded into spike trains. These spike trains are then learned to classify the material texture.
</div>

If you build upon our results and ideas, please use this citation.
{% raw %}
```html
@inproceedings{
    taunyazov2020fast,title = {Fast texture classification using tactile neural coding and spiking neural network},
    author = {Taunyazov, Tasbolat and Chua, Yansong and Gao, Ruihan and Soh, Harold and Wu, Yan},
    booktitle = {IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
    pages = {9890--9895},
    year = {2020},
    organization = {IEEE} }
```
{% endraw %}
