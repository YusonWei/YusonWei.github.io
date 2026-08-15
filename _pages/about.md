---
layout: about
title: about
permalink: /
subtitle: Research assistant at Harbin Institute of Technology

profile:
  align: right
  image: about_personal_photo.jpg
  image_circular: false # crops the image to make it circular
  more_info: >-
    <div style="display: flex; flex-direction: column; gap: 6px; margin-top: 8px; font-family: 'Roboto', sans-serif; font-size: 0.9rem; line-height: 1.35; width: max-content; max-width: none;">
      <a href="mailto:yuanlongwei_hit@163.com" style="display: flex; align-items: center; gap: 7px; white-space: nowrap; flex-shrink: 0;">
        <i class="fa-solid fa-envelope" aria-hidden="true"></i>
        <span>yuanlongwei_hit@163.com</span>
      </a>
      <a href="tel:+8615820000219" style="display: flex; align-items: center; gap: 7px; white-space: nowrap; flex-shrink: 0;">
        <i class="fa-solid fa-phone" aria-hidden="true"></i>
        <span>+86-158-2000-0219</span>
      </a>
    </div>

banner: assets/img/banner.png

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 1 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div style="display: flex; align-items: flex-start; margin-bottom: 25px;">
  <div style="flex: 0 0 40px; display: flex; justify-content: center; margin-top: 5px;">
    <i class="fa-solid fa-earth-americas" style="font-size: 1.0rem; color: #3b0f70;"></i>
  </div>
  <div>
    <span style="font-family: 'Roboto', sans-serif; font-weight: 700; text-transform: uppercase; font-size: 1.1rem; color: #3b0f70;">ABOUT ME</span>
    <span> I am preparing for PhD applications focused on Robotics and Embodied AI, with a particular interest in bridging control theory and physically grounded AI.</span>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 25px;">
  <div style="flex: 0 0 40px; display: flex; justify-content: center; margin-top: 5px;">
    <i class="fa-solid fa-atom" style="font-size: 1.0rem; color: #8c2981;"></i>
  </div>
  <div>
    <span style="font-family: 'Roboto', sans-serif; font-weight: 700; text-transform: uppercase; font-size: 1.1rem; color: #8c2981;">EXPERTISE</span>
    <span> I possess sound foundations in control theory and am actively building robotic expertise. I specialize in mathematical algorithm design and proposed a VO-IDA control framework with published theoretical contributions.</span>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 25px;">
  <div style="flex: 0 0 40px; display: flex; justify-content: center; margin-top: 5px;">
    <i class="fa-solid fa-palette" style="font-size: 1.0rem; color: #de4968;"></i>
  </div>
  <div>
    <span style="font-family: 'Roboto', sans-serif; font-weight: 700; text-transform: uppercase; font-size: 1.1rem; color: #de4968;">RESEARCH FOCUS</span>
    <span> Unlike most learning-focused researchers, I aim to develop robust low-level control layers to bridge simulated policies with physical robots to address the Sim-to-Real stability gap.</span>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 25px;">
  <div style="flex: 0 0 40px; display: flex; justify-content: center; margin-top: 5px;">
    <i class="fa-solid fa-spa" style="font-size: 1.0rem; color: #fe9f6d;"></i>
  </div>
  <div>
    <span style="font-family: 'Roboto', sans-serif; font-weight: 700; text-transform: uppercase; font-size: 1.1rem; color: #fe9f6d;">WORKING STYLE</span>
    <span> I consider myself self-motivated, digging into fundamental mechanisms behind problems and prioritizing rigorous deliverables.</span>
  </div>
</div>

<style>
.profile.float-right {
  --profile-photo-width: 120px;
  margin-left: 1rem;
  width: 140px;
}
.profile.float-right figure {
  text-align: center;
}
.profile.float-right img {
  width: var(--profile-photo-width);
}
.profile.float-right .more-info {
  width: max-content;
  margin-left: calc((100% - var(--profile-photo-width)) / 2);
}
.wrap {
  margin: 2rem 0;
  --research-accent: rgb(181, 8, 172);
}
html[data-theme="dark"] .wrap {
  --research-accent: rgb(38, 152, 186);
}
.toggle-labels {
  display: flex;
  justify-content: space-between;
  width: 260px;
  margin-bottom: 6px;
  font-size: 0.86rem;
  font-weight: bold;
  color: #444;
}
.toggle-labels .active-label {
  color: var(--research-accent);
}
.groove-track {
  position: relative;
  width: 260px;
  height: 34px;
  background: #ddd;
  border-radius: 17px;
  cursor: pointer;
}
.slider-knob {
  position: absolute;
  top: 3px;
  left: 3px;
  width: calc(50% - 6px);
  height: 28px;
  background: var(--research-accent);
  border-radius: 14px;
  transition: left 0.25s ease;
}
.groove-track.active-right .slider-knob {
  left: calc(50% + 3px);
}
.tab-panel {
  display: none;
  padding: 1rem 0;
}
.tab-panel.active {
  display: block;
}
.skill-tier-title {
  font-size: 1.15rem;
  font-weight: 600;
  margin: 1.4rem 0 0.6rem;
  padding-top:1rem;
  border-top:2px solid var(--research-accent);
}
.skill-tier-title:first-of-type {
  border-top:none;
  padding-top:0;
}
.tier-primary {
  color: inherit;
}
.skill-group {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 6px;
}
.tag-proficient {
  background: var(--research-accent);
  color: #fff;
  padding: 5px 11px;
  border-radius: 3px;
  font-size: 0.88rem;
}
.tag-familiar {
  background: #636363;
  color: #fff;
  padding: 5px 11px;
  border-radius: 3px;
  font-size: 0.88rem;
}
</style>

<h2>Research Competencies</h2>

<div class="wrap">
  <div class="toggle-labels">
    <span id="label-know" class="active-label">Domain Expertise</span>
    <span id="label-tools">Research Tools</span>
  </div>
  <div class="groove-track" id="track">
    <div class="slider-knob"></div>
  </div>

  <div id="knowledge" class="tab-panel active">
    <h3 class="skill-tier-title tier-primary">Control Theory (Robotics &amp; Embodied AI)</h3>
    <div class="skill-group">
      <span class="tag-proficient">Linear System Theory</span>
      <span class="tag-proficient">Lyapunov Stability Analysis</span>
      <span class="tag-proficient">Model Predictive Control (MPC)</span>
      <span class="tag-proficient">Adaptive Control (Neural Network-Based)</span>
      <span class="tag-proficient">Backstepping</span>
      <span class="tag-proficient">Sliding Mode Control (SMC)</span>
      <span class="tag-proficient">Active Disturbance Rejection Control (ADRC)</span>
      <span class="tag-proficient">Passivity-Based Control (PBC)</span>
      <span class="tag-proficient">Fuzzy Control (FC)</span>
    </div>

    <h3 class="skill-tier-title tier-primary">AI-ML (Robotics &amp; Embodied AI)</h3>
    <div class="skill-group">
      <span class="tag-proficient">Deep Learning</span>
      <span class="tag-proficient">Reinforcement Learning</span>
      <span class="tag-proficient">Genetic Algorithm</span>
    </div>

    <h3 class="skill-tier-title tier-primary">Domain Expertise (Intelligent Driving)</h3>
    <div class="skill-group">
      <span class="tag-proficient">Vehicle Dynamics</span>
      <span class="tag-familiar">Platoon Control</span>
      <span class="tag-familiar">CACC</span>
      <span class="tag-familiar">Connected Vehicles</span>
    </div>

    <h3 class="skill-tier-title tier-primary">Domain Expertise (Traffic Engineering)</h3>
    <div class="skill-group">
      <span class="tag-familiar">Traffic Flow Theory</span>
      <span class="tag-familiar">Traffic Management &amp; Control</span>
      <span class="tag-familiar">Operations Research</span>
    </div>
  </div>

  <div id="tools" class="tab-panel">
    <h3 class="skill-tier-title">Languages &amp; Data Processing</h3>
    <div class="skill-group">
      <span class="tag-proficient">Python</span>
      <span class="tag-proficient">MATLAB</span>
      <span class="tag-familiar">C</span>
      <span class="tag-familiar">Excel VBA</span>
      <span class="tag-familiar">Excel Advanced Functions</span>
    </div>

    <h3 class="skill-tier-title">Simulation &amp; ML Frameworks</h3>
    <div class="skill-group">
      <span class="tag-proficient">PyTorch</span>
      <span class="tag-proficient">Simulink</span>
      <span class="tag-familiar">CarSim-Simulink Co-Simulation</span>
      <span class="tag-familiar">VISSIM</span>
    </div>

    <h3 class="skill-tier-title">Academic Workflow &amp; Visualization</h3>
    <div class="skill-group">
      <span class="tag-proficient">LaTeX</span>
      <span class="tag-proficient">Markdown</span>
      <span class="tag-proficient">MS Word</span>
    </div>
    <div class="skill-group">
      <span class="tag-proficient">MS PowerPoint</span>
    </div>
    <div class="skill-group">
      <span class="tag-proficient">Bookends</span>
      <span class="tag-proficient">Zotero</span>
    </div>
    <div class="skill-group">
      <span class="tag-familiar">Inkscape</span>
      <span class="tag-familiar">Photoshop</span>
      <span class="tag-familiar">MindNode</span>
      <span class="tag-familiar">AutoCAD</span>
    </div>
  </div>
</div>

<script>
const track = document.getElementById('track');
const knowledgePanel = document.getElementById('knowledge');
const toolsPanel = document.getElementById('tools');
const labelKnow = document.getElementById('label-know');
const labelTools = document.getElementById('label-tools');

track.addEventListener('click', () => {
  track.classList.toggle('active-right');
  if(track.classList.contains('active-right')){
    knowledgePanel.classList.remove('active');
    toolsPanel.classList.add('active');
    labelKnow.classList.remove('active-label');
    labelTools.classList.add('active-label');
  }else{
    knowledgePanel.classList.add('active');
    toolsPanel.classList.remove('active');
    labelKnow.classList.add('active-label');
    labelTools.classList.remove('active-label');
  }
});
</script>

<style>
.box-wrap {
  display:grid;
  grid-template-columns:auto minmax(0, 1fr);
  align-items:center;
  column-gap:24px;
  row-gap:18px;
  width:100%;
  max-width:900px;
  margin:20px auto;
}
.diamond-group,
.text-group {
  display:contents;
}
/* 不旋转a标签，用伪元素画菱形，点击热区完全正常 */
.diam-wrap {
  position:relative;
  width:calc(62px * 0.4);
  height:calc(62px * 0.4);
  display:block;
}
.diam-wrap::before {
  content:"";
  position:absolute;
  inset:0;
  transform:rotate(45deg);
}
.diam-yellow::before { background:#ffdd00; }
.diam-green::before  { background:#00dd00; }
.diam-red::before    { background:#ff0000; }

.txt-item {
  font-weight:bold;
  font-size:23px;
  text-decoration:none;
  white-space:nowrap;
}
.txt-yellow { color:#ffdd00; }
.txt-green  { color:#00dd00; }
.txt-red    { color:#ff0000; }
</style>

<div class="box-wrap">
  <div class="diamond-group">
    <a target="_blank" rel="noopener noreferrer" class="diam-wrap diam-yellow about-video-trigger" data-video-id="rTHhyES8CqE" data-video-title="Representative Academic Slides" href="https://youtu.be/rTHhyES8CqE"></a>
    <a target="_blank" rel="noopener noreferrer" class="diam-wrap diam-green" href="https://yusonwei.github.io/assets/pdf/MEng%20thesis.pdf"></a>
    <a target="_blank" rel="noopener noreferrer" class="diam-wrap diam-red" href="https://yusonwei.github.io/assets/pdf/Complete%20Mathematical%20Derivations%20—%20IEEE%20IoT%E2%80%91J%20Paper.pdf"></a>
  </div>

  <div class="text-group">
    <a target="_blank" rel="noopener noreferrer" href="https://youtu.be/rTHhyES8CqE" class="txt-item txt-yellow about-video-trigger" data-video-id="rTHhyES8CqE" data-video-title="Representative Academic Slides">Representative Academic Slides</a>
    <a target="_blank" rel="noopener noreferrer" href="https://yusonwei.github.io/assets/pdf/MEng%20thesis.pdf" class="txt-item txt-green">Master’s Dissertation with Improved VO‑IDA Algorithm in Chapter 4</a>
    <a target="_blank" rel="noopener noreferrer" href="https://yusonwei.github.io/assets/pdf/Complete%20Mathematical%20Derivations%20—%20IEEE%20IoT%E2%80%91J%20Paper.pdf" class="txt-item txt-red">Mathematical Derivation for IoT‑J Paper</a>
  </div>
</div>

<div class="modal fade" id="aboutVideoModal" tabindex="-1" role="dialog" aria-labelledby="aboutVideoModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-xl modal-dialog-centered" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="aboutVideoModalLabel">Video</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body p-0">
        <div class="embed-responsive embed-responsive-16by9">
          <iframe
            id="aboutVideoFrame"
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
    var modal = document.getElementById("aboutVideoModal");
    var frame = document.getElementById("aboutVideoFrame");
    var label = document.getElementById("aboutVideoModalLabel");

    if (!modal || !frame || !label) return;

    document.querySelectorAll(".about-video-trigger").forEach(function (link) {
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
