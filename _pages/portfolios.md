---
layout: page
title: Portfolios
permalink: /portfolios/
description: A collection of scientific graphics and projects.
nav: true
nav_order: 6
display_categories: [portfolio]
horizontal: false
images:
  lightbox2: true
---

<!-- pages/portfolios.md -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized portfolios -->
  {% for category in page.display_categories %}
    <h2 class="category">{{ category }}</h2>
    {% assign categorized_projects = site.projects | where: "category", category %}
    {% assign sorted_projects = categorized_projects | sort: "importance" %}
    <div class="row row-cols-1 row-cols-md-3">
      {% for project in sorted_projects %}
        {% include projects.liquid %}
      {% endfor %}
    </div>
  {% endfor %}
{% else %}
  {% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
{% endif %}
</div>

<h2 class="mt-5">Presentation</h2>
<div style="position: relative; width: 100%; padding-bottom: 56.25%; height: 0; overflow: hidden;">
  <iframe
    src="https://1drv.ms/p/c/a5103b58da1ee155/IQDP-OOD1zBNRJqCRT0Ak4WgAaRFyb-8QaVMlUf0talwCiQ?em=2&amp;"
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
    frameborder="0"
    allowfullscreen>
  </iframe>
</div>
