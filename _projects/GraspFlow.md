---
layout: page
title: Refining 6-DoF Grasps with Context-Specific Classifiers 
small_title: GraspFlow
description: 
img: assets/img/graspflow/graspflow_mainfig.png
importance: 3
category: "Grasp: Grasp Synthesis"
---

In this work, we present GraspFlow, a refinement approach for generating context-specific grasps. We formulate the problem of grasp synthesis as a sampling problem: we seek to sample from a context-conditioned probability distribution of successful grasps. However, this target distribution is unknown. As a solution, we devise a discriminator gradient-flow method to evolve grasps obtained from a simpler distribution in a manner that mimics sampling from the desired target distribution. Unlike existing approaches, GraspFlow is modular, allowing grasps that satisfy multiple criteria to be obtained simply by incorporating the relevant discriminators. It is also simple to implement, requiring minimal code given existing auto-differentiation libraries and suitable discriminators. Experiments show that GraspFlow generates stable and executable grasps on a real-world Panda robot for a diverse range of objects. In particular, in 60 trials on 20 different household objects, the first attempted grasp was successful 94% of the time, and 100% grasp success was achieved by the second grasp. Moreover, incorporating a functional discriminator for robot-human handover improved the functional aspect of the grasp by up to 33%.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/graspflow/graspflow_mainfig.png" title="robot slide image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <strong>Fig.1</strong> Illustration of GraspFlow. Grasps shown are samples from probability distributions (black circles along the gradient flow from the initial distribution q0 to a target distribution p.
</div>



<!-- <p style="text-align:center">
<iframe width="720" height="445" id="player" src="https://www.youtube.com/embed/zPlrqtjEcUY?enablejsapi=1&origin=https://yourdomain.com&showinfo=0&iv_load_policy=3&modestbranding=1&theme=light&color=white&rel=0" frameborder="0"></iframe>
</p> -->

For more on this work, please look at the following resources: 

<ul>
<li><a href="hhttps://arxiv.org/pdf/2308.06928" target="_blank">Arxiv</a></li>
<li><a href="https://github.com/tasbolat1/graspflow" target="_blank">Code and Data</a></li>
<!-- <li><a href="{{ page.baseurl }}/assets/pdf/RSS_presentation.pdf" target="_blank">Slides</a></li> -->
</ul>

If you build upon our results and ideas, please use this citation.
{% raw %}
```html
@inproceedings{taunyazov2023refining,
url = {https://arxiv.org/abs/2308.06928},
author={Taunyazov, Tasbolat and Zhang, Heng and Eala, John Patrick and Zhao, Na and Soh, Harold},
title={Refining 6-DoF Grasps with Context-Specific Classifiers},
booktitle = {IEEE/RSJ International Conference on Intelligent Robots and Systems},
year = {2023} }
```
{% endraw %}
