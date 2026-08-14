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

<h2 class="mt-5">PDF Reader</h2>
<iframe
  src="{{ '/assets/pdf/Complete%20Mathematical%20Derivations%20%E2%80%94%20IEEE%20IoT%E2%80%91J%20Paper.pdf' | relative_url }}#view=FitH"
  class="w-100"
  style="height: 80vh; min-height: 520px; border: 0;"
  title="Complete Mathematical Derivations - IEEE IoT-J Paper"
  loading="lazy"
  allowfullscreen>
</iframe>
