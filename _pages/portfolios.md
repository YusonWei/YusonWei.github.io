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
  <h2 class="category">portfolios</h2>
  <div class="row row-cols-1 row-cols-md-3">
    <div class="col">
      <a class="card h-100 hoverable video-modal-trigger" style="color: inherit;" data-video-id="rTHhyES8CqE" data-video-title="Representative academic slides" href="https://youtu.be/rTHhyES8CqE">
        <img src="https://img.youtube.com/vi/rTHhyES8CqE/hqdefault.jpg" class="card-img-top" alt="Representative academic slides" loading="lazy">
        <div class="card-body">
          <h2 class="card-title">Representative academic slides</h2>
        </div>
      </a>
    </div>
    <div class="col">
      <a
        class="card h-100 hoverable"
        style="color: inherit;"
        href="https://yusonwei.github.io/assets/pdf/MEng%20thesis.pdf"
        target="_blank"
        rel="noopener noreferrer"
      >
        {% include figure.liquid loading="eager" path="assets/img/portfolios/MEng-thesis-cover-001.jpg" sizes="250px" alt="MEng thesis PDF preview" class="card-img-top" %}
        <div class="card-body">
          <h2 class="card-title">MEng thesis</h2>
          <p class="card-text">Passivity-Based Control for Vehicle Platoons</p>
        </div>
      </a>
    </div>
    <div class="col">
      <a
        class="card h-100 hoverable"
        style="color: inherit;"
        href="{{ '/assets/pdf/Complete%20Mathematical%20Derivations%20%E2%80%94%20IEEE%20IoT%E2%80%91J%20Paper.pdf' | relative_url }}"
        target="_blank"
        rel="noopener noreferrer"
      >
        {% include figure.liquid loading="eager" path="assets/img/portfolios/Complete-Mathematical-Derivations-cover-001.jpg" sizes="250px" alt="Mathematical Derivations(325 Saved Pages, Main Body) PDF preview" class="card-img-top" %}
        <div class="card-body">
          <h2 class="card-title">Mathematical Derivations (325 Saved Pages, Main Body)</h2>
          <p class="card-text">IEEE IoT-J Paper</p>
        </div>
      </a>
    </div>
    <div class="col">
      <a class="card h-100 hoverable video-modal-trigger" style="color: inherit;" data-video-id="CC3O-unSNpE" data-video-title="Traffic Engineering Internship Project 2 - Simulation Result" href="https://youtu.be/CC3O-unSNpE">
        <img src="https://img.youtube.com/vi/CC3O-unSNpE/hqdefault.jpg" class="card-img-top" alt="Traffic Engineering Internship Project 2 - Simulation Result" loading="lazy">
        <div class="card-body">
          <h2 class="card-title">Traffic Engineering Internship Project 2 - Simulation Result</h2>
        </div>
      </a>
    </div>
    <div class="col">
      <a class="card h-100 hoverable video-modal-trigger" style="color: inherit;" data-video-id="qbXFMm4PIPk" data-video-title="Traffic Engineering Internship Project 1 - Work" href="https://youtu.be/qbXFMm4PIPk">
        <img src="https://img.youtube.com/vi/qbXFMm4PIPk/hqdefault.jpg" class="card-img-top" alt="Traffic Engineering Internship Project 1 - Work" loading="lazy">
        <div class="card-body">
          <h2 class="card-title">Traffic Engineering Internship Project 1 - Work</h2>
        </div>
      </a>
    </div>
    <div class="col">
      <a class="card h-100 hoverable video-modal-trigger" style="color: inherit;" data-video-id="sfspEywTf1c" data-video-title="Traffic Engineering Internship Project 2 - Work" href="https://youtu.be/sfspEywTf1c">
        <img src="https://img.youtube.com/vi/sfspEywTf1c/hqdefault.jpg" class="card-img-top" alt="Traffic Engineering Internship Project 2 - Work" loading="lazy">
        <div class="card-body">
          <h2 class="card-title">Traffic Engineering Internship Project 2 - Work</h2>
        </div>
      </a>
    </div>
    <div class="col">
      <div class="card h-100 hoverable">
        <a href="{{ '/assets/img/portfolios/Intersection_cad_drawing.jpg' | relative_url }}" data-lightbox="gallery" data-title="Intersection CAD drawing">
          {% include figure.liquid loading="eager" path="assets/img/portfolios/Intersection_cad_drawing.jpg" sizes="250px" alt="Intersection CAD drawing thumbnail" class="card-img-top" %}
        </a>
        <div class="card-body">
          <h2 class="card-title">Intersection CAD drawing</h2>
          <p class="card-text">Road intersection traffic infrastructure drawing, created with AutoCAD</p>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="modal fade" id="videoModal" tabindex="-1" role="dialog" aria-labelledby="videoModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-xl modal-dialog-centered" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="videoModalLabel">Video</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body p-0">
        <div class="embed-responsive embed-responsive-16by9">
          <iframe
            id="videoModalFrame"
            class="embed-responsive-item"
            src=""
            title="Video player"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen
          ></iframe>
        </div>
      </div>
    </div>
  </div>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    var modal = document.getElementById("videoModal");
    var frame = document.getElementById("videoModalFrame");
    var label = document.getElementById("videoModalLabel");

    if (!modal || !frame || !label) return;

    document.querySelectorAll(".video-modal-trigger").forEach(function (link) {
      link.addEventListener("click", function (event) {
        event.preventDefault();

        var videoId = link.getAttribute("data-video-id");
        var videoTitle = link.getAttribute("data-video-title") || "Video";
        label.textContent = videoTitle;
        frame.src = "https://www.youtube-nocookie.com/embed/" + videoId + "?autoplay=1&rel=0";

        $(modal).modal("show");
      });
    });

    $(modal).on("hidden.bs.modal", function () {
      frame.src = "";
    });
  });
</script>
