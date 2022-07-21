---
layout: page
title: #Extended Tactile Perception BLAH
description: #Vibration Sensing through Tools and Grasped Object
img: assets/img/extense/tactile_extended_main.jpg
importance: 1
category: BLAH
---

Have you ever wondered that blind people can "see" the surroundings by walking cane? In most of cases, we focus on how human moves the tool to feel the surroundings. What if the tool can be also a sensor? This is not new concept, in the 17th century, philospher Rene Descartes discussed about this matter. However, up until recently we did not have clear idea how exactly tool helps humans to understand the surroundings. In 2018 Nature Study [1], Miller and his colleagues at Claude Bernard Lyon 1 University in France reported that humans are actually quite good at pinpointing where an object comes into contact with a handheld tool using touch alone, as if the object were touching their own skin. Tool is not part of skin, then how human brain can make sense of the tool contact?

<div class="row justify-content-sm-center">
    <div>
        {% include figure.html path="assets/img/extense/extended_brain.webp" title="tool extended image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Our brain senses tool as if it's part of our body. Credit: <a href="https://lottieclarkesci.wordpress.com/2019/05/20/book-review-the-ice-house/">Lottie Clarke</a>
</div>


In follow-up study, published in Current Biology [2], reveal that the brain regions involved with sensing touch on the body similarly processes it on the tool. The tool is being treated like a sensory extension of your body. This is what we call **Extended Tactile Perception**. Now, question is can we transfer this ability to the robot? Can we make sense of the tactile signal that comes through the tool?

In order to answer these questions, we have setup 3 different experiments using dynamic tactile sensor: tap localization, food identification and grasp stability during robot-to-human handover.
<div class="row justify-content-sm-center">
    <div>
        {% include figure.html path="assets/img/extense/tactile_extended_main.jpg" title="tool extended image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Our brain senses tool as if it's part of our body. Credit: <a href="https://lottieclarkesci.wordpress.com/2019/05/20/book-review-the-ice-house/">Lottie Clarke</a>
</div>
In all these tasks, raw tactile data collected from dynamic tactile sensor with various (5-4kH) frequences are preprocessed and fed to machine learning technique that outputs location of the tap (A), food type (B) and stability