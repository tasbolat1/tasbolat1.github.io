---
layout: page
title: "GRaCE: Optimizing Grasps to Satisfy Ranked Criteria in Complex Scenarios"
small_title: GRaCE
description: 
img: assets/img/grace/grace_mainfig.png
importance: 3
category: "Grasp: Grasp Synthesis"
---

This paper addresses the multi-faceted problem of robot grasping, where multiple criteria may conflict and differ in importance. We introduce Grasp Ranking and Criteria Evaluation (GRaCE), a novel approach that employs hierarchical rule-based logic and a rank-preserving utility function to optimize grasps based on various criteria such as stability, kinematic constraints, and goal-oriented functionalities. Additionally, we propose GRaCE-OPT, a hybrid optimization strategy that combines gradient-based and gradient-free methods to effectively navigate the complex, non-convex utility function. Experimental results in both simulated and real-world scenarios show that GRaCE requires fewer samples to achieve comparable or superior performance relative to existing methods. The modular architecture of GRaCE allows for easy customization and adaptation to specific application needs.


<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/grace/grace_mainfig.png" title="robot slide image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <strong>Fig.1</strong> In this work, we formalize optimization of grasps under multiple ranked criteria. We define an expected grasp utility U , illustrated above, where blue regions indicates higher utility values that are collision free and stable. We present a hybrid optimization method (GRACE-OPT) for finding grasps that maximize U.
</div>

<center>
Due to the GRaCE's modularity, we can easily modify it with other models. In this video, we demonstrate the GRaCE's capability with ChatGPT to grasp various items on the table.
<iframe width="560" height="315" src="https://www.youtube.com/embed/-k4qpLOwVd8?si=A6Ltx8kSS48MDjm_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>

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
@inproceedings{taunyazov2024grace,
url = {https://arxiv.org/abs/2309.08887},
author={Taunyazov, Tasbolat and Lin, Kelvin and Soh, Harold},
title={GRaCE: Balancing Multiple Criteria to Achieve Stable, Safe, and Task Functional Grasps},
booktitle = {RSS},
year = {2024} }
```
{% endraw %}
