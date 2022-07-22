---
layout: page
title: Semi-autonomous robot teleoperation with obstacle avoidance via model predictive control
description: 
img: assets/img/ralrss2019/main.png
importance: 3
category: Robot Control
---

This paper proposes a model predictive control ap- proach for semi-autonomous teleoperation of robot manipulators: the focus is on avoiding obstacles with the whole robot frame, while exploiting predictions of the operator’s motion. The hand pose of the human operator provides the reference for the end effector, and the robot motion is continuously replanned in real time, satisfying several constraints. An experimental case study is described regarding the design and testing of the described framework on a UR5 manipulator: the experimental results con- firm the suitability of the proposed method for semi-autonomous teleoperation, both in terms of performance (tracking capability and constraint satisfaction) and computational complexity (the control law is calculated well within the sampling interval).


<p style="text-align:center">
<iframe width="720" height="445" id="player" src="https://www.youtube.com/embed/P9rCNJrjTjw?enablejsapi=1&origin=https://yourdomain.com&showinfo=0&iv_load_policy=3&modestbranding=1&theme=light&color=white&rel=0" frameborder="0"></iframe>
</p>

To cite this work, please use:
{% raw %}
```html
@article{rubagotti2019semi,
  title = {Semi-autonomous robot teleoperation with obstacle avoidance via model predictive control},
  author = {Rubagotti, Matteo and Taunyazov, Tasbolat and Omarali, Bukeikhan and Shintemirov, Almas},
  journal = {IEEE Robotics and Automation Letters},
  volume = {4},
  number = {3},
  pages = {2746--2753},
  year = {2019},
  publisher = {IEEE}
}
```
{% endraw %}
