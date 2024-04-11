---
layout: page
title: Event-Driven Visual-Tactile Sensing and Learning for Robots 
small_title: VT-SNN
description: 
img: assets/img/rss2020_event/mainfig.png
importance: 3
category: "Feel: Tactile Sensing"
---

Many everyday tasks require multiple sensory modalities to perform successfully. For example, consider fetching a carton of soymilk from the fridge; humans use vision to locate the carton and can infer from a simple grasp how much liquid the carton contains. This inference is performed robustly using a power-efficient neural substrate — compared to current artificial systems, human brains require far less energy.

In this work, we gain inspiration from biological systems, which are asynchronous and event-driven. We contribute an event-driven visual-tactile perception system, comprising NeuTouch — a biologically-inspired tactile sensor — and the VT-SNN for multi-modal spike-based perception.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rss2020_event/mainfig.png" title="robot slide image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <strong>Fig.1</strong> <strong>Left:</strong> NeuTouch - neuromorphic tactile sensor which mimics human finger, <strong>right:</strong>Visuo-Tactile Spiking Neural Network (VT-SNN) - multimodal spike-based framework for perception.
</div>

We evaluate our visual-tactile system (using the NeuTouch and Prophesee event camera) on two robot tasks: container classification and rotational slip detection. We show that relatively small differences in weight (approx. 30g across 20 object-weight classes) can be distinguished by our prototype sensors and spiking models. The second experiment indicates rotational slip can be accurately detected within 0.08s. When tested on the Intel Loihi, the SNN achieved inference speeds similar to a GPU, but required an order-of-magnitude less power.


<p style="text-align:center">
<iframe width="720" height="445" id="player" src="https://www.youtube.com/embed/zPlrqtjEcUY?enablejsapi=1&origin=https://yourdomain.com&showinfo=0&iv_load_policy=3&modestbranding=1&theme=light&color=white&rel=0" frameborder="0"></iframe>
</p>

For more on this work, please look at the following resources: 

<ul>
<li><a href="https://arxiv.org/abs/2009.07083" target="_blank">Arxiv</a></li>
<li><a href="https://github.com/clear-nus/VT_SNN" target="_blank">Code and Data</a></li>
<li><a href="{{ page.baseurl }}/assets/pdf/RSS_presentation.pdf" target="_blank">Slides</a></li>
</ul>

If you build upon our results and ideas, please use this citation.
{% raw %}
```html
@article{taunyazov2020event,
  title = {Event-driven visual-tactile sensing and learning for robots},
  author = {Taunyazov, Tasbolat and Sng, Weicong and See, Hian Hian and Lim, Brian and Kuan, Jethro and Ansari, Abdul Fatir and Tee, Benjamin CK and Soh, Harold},
  journal = {Robotics: Science and Systems (RSS)},
  year = {2020},
}
```
{% endraw %}
