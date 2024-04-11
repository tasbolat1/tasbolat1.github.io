---
layout: page
title: research
permalink: /projects/
description: 
nav: true
nav_order: 2
display_categories: ["Grasp: Grasp Synthesis", "Feel: Tactile Sensing", "Act: Control & Robot Manipulation"]
horizontal: false
---

My research direction is robot manipulation, in which the robot manipulates the grasped tool or object to perform the target task. The pipeline for the robot manipulation is divided into three parts:
<ol>
  <li><strong>Grasp:</strong> robot reasons about the object of interest by visually observing the environment before taking any action.</li>
  <li><strong>Feel:</strong> once robot comes into contact with the item, it feels the physical contact with rich tactile information.
</li>
  <li><strong>Act:</strong> robot takes an intelligent actions to perform the tasks taking into account the tactile feedback from the object.
</li>
</ol> 

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/research_directions.png" title="robot kinematic model image" class="img-fluid rounded" %}
    </div>
</div>
<div class="caption">
    A pipeline of the robotic object manipulation towards stable object manipulation contains three parts: <strong>Grasp (leftmost)</strong>, <strong>Feel (middle)</strong> and <strong>Act (right)</strong>.
</div>

<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>
