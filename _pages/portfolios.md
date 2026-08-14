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
  <h2 class="category">pdf</h2>
  <div class="row row-cols-1 row-cols-md-3">
    <div class="col">
      <a
        class="card h-100 hoverable"
        style="color: inherit;"
        href="https://github.com/YusonWei/YusonWei.github.io/blob/main/assets/pdf/Complete%20Mathematical%20Derivations%20%E2%80%94%20IEEE%20IoT%E2%80%91J%20Paper.pdf"
        target="_blank"
        rel="noopener noreferrer"
      >
        {% include figure.liquid loading="eager" path="assets/img/portfolios/Complete-Mathematical-Derivations-cover-001.jpg" sizes="250px" alt="Complete Mathematical Derivations PDF preview" class="card-img-top" %}
        <div class="card-body">
          <h2 class="card-title">Complete Mathematical Derivations</h2>
          <p class="card-text">IEEE IoT-J Paper PDF</p>
        </div>
      </a>
    </div>
  </div>
</div>

<div class="projects mt-4">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized portfolios -->
  {% for category in page.display_categories %}
    <h2 class="category">img</h2>
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
