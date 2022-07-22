---
layout: page
title: Constrained Orientation Control of a Spherical Parallel Manipulator via Online Convex Optimization
description: 
img: assets/img/tmech2017_convex/FIG1-1.png
importance: 3
category: Robot Control
---

This paper introduces a new framework for the closed-loop orientation control of spherical parallel manipulators (SPMs) based on the online solution of a convex optimization problem. The aim of solving a constrained optimization problem is to define a reference position for the SPM that remains as close as possible to the ideal reference (i.e., the one for which the top mobile platform has the desired orientation), at the same time keeping the SPM within the set of configurations in which
collisions between links and singular configurations are avoided (the so-called feasible workspace). 

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tmech2017_convex/FIG3-1.png" title="robot kinematic model image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <strong>Fig.1</strong> Block diagram of the SPM orientation control framework.
</div>

The proposed approach relies on a recently introduced method for obtaining unique inverse kinematics for SPMs, and on a newly proposed method for
generating an approximation of the feasible workspace suitable for fast online optimization. The proposed control scheme is ex-
perimentally tested on an Agile Wrist SPM prototype, confirming the performance expected from the theoretical formulation.

<p style="text-align:center">
<iframe width="720" height="445" id="player" src="https://www.youtube.com/embed/OvFwm1QS1wY?enablejsapi=1&origin=https://yourdomain.com&showinfo=0&iv_load_policy=3&modestbranding=1&theme=light&color=white&rel=0" frameborder="0"></iframe>
</p>

To cite this work, please use:
{% raw %}
```html
@article{taunyazov2017constrained,
  title = {Constrained orientation control of a spherical parallel manipulator via online convex optimization},
  author = {Taunyazov, Tasbolat and Rubagotti, Matteo and Shintemirov, Almas},
  journal = {IEEE/ASME Transactions on Mechatronics},
  volume = {23},
  number = {1},
  pages = {252--261},
  year = {2017},
  publisher = {IEEE}
}
```
{% endraw %}
