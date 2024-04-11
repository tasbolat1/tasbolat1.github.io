---
layout: page
title: Towards Effective Tactile Identification of Textures using a Hybrid Touch Approach
small_title: Texture Identificaiton
description: 
img: assets/img/texture_ident/1.jpg
importance: 2
category: "Feel: Tactile Sensing"
---

The sense of touch is arguably the first human sense to develop. Empowering robots with the sense of touch may augment their understanding of interacted objects and the environment beyond standard sensory modalities (e.g., vision). This paper investigates the effect of hybridizing touch and sliding movements for tactile-based texture classification. We develop three machine-learning methods within a framework to discriminate between surface textures; the first two methods use hand-engineered features, whilst the third leverages convolutional and recurrent neural network layers to learn feature representations from raw data. To compare these methods, we constructed a dataset comprising tactile data from 23 textures gathered using the iCub platform under a loosely constrained setup, i.e., with nonlinear motion. 

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/texture_ident/collage-1.png" title="robot slide image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <strong>Fig.1</strong> Tactile sensor readings (red dots,left) during a sliding motion on the bathroom mat during three time points. Different sets of taxels are activated during the motion, which can provide additional data about the underlying texture.
</div>

In line with findings from neuroscience, our experiments show that a good initial estimate can be obtained via touch data, which can be further refined via sliding; combining both touch and sliding data results in 98% classification accuracy over unseen test data. 

For more on this work, please look at the following resources: {{ site.baseurl }}

<ul>
<li><a href="https://github.com/clear-nus/TactileLearning" target="_blank">Data</a></li>
<li><a href="{{ page.baseurl }}/assets/pdf/presentation_ICRA2019.pdf" target="_blank">Slides</a></li>
<li><a href="{{ page.baseurl }}/assets/pdf/poster_ICRA2019.pdf" target="_blank">Poster</a></li>
</ul>

If you build upon our results and ideas, please use this citation.
{% raw %}
```html
@inproceedings{taunyazov2019towards,
  title = {Towards effective tactile identification of textures using a hybrid touch approach},
  author = {Taunyazov, Tasbolat and Koh, Hui Fang and Wu, Yan and Cai, Caixia and Soh, Harold},
  booktitle = {International Conference on Robotics and Automation (ICRA)},
  pages = {4269--4275},
  year = {2019},
  organization = {IEEE}
}


```
{% endraw %}
