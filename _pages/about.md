---
layout: about
title: about
permalink: /
subtitle: Physicist at the Advanced Photon Source, Argonne National Laboratory, USA

profile:
  align: right
  image: about_personal_photo.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <img src="/assets/img/about_personal_signature.png" alt="Signature" class="img-fluid">

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
    <span style="font-family: 'Roboto', sans-serif; font-weight: 700; text-transform: uppercase; font-size: 1.1rem; color: #3b0f70;">I AM</span>
    <span> an enthusiastic early-career scientist without borders, with a research journey spanning three continents — Asia, Europe, and America, and an interdisciplinary background fused with high-energy physics, chemistry and materials science.</span>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 25px;">
  <div style="flex: 0 0 40px; display: flex; justify-content: center; margin-top: 5px;">
    <i class="fa-solid fa-atom" style="font-size: 1.0rem; color: #8c2981;"></i>
  </div>
  <div>
    <span style="font-family: 'Roboto', sans-serif; font-weight: 700; text-transform: uppercase; font-size: 1.1rem; color: #8c2981;">I DEDICATE</span>
    <span> to push the extreme of X-ray techniques. For eight years, I have devoted myself to developing fast, ms time-scale X-ray Absorption Spectroscopy (dispersive XAS), while exploring how AI and automation can bring intelligence and scalability into experimental science.</span>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 25px;">
  <div style="flex: 0 0 40px; display: flex; justify-content: center; margin-top: 5px;">
    <i class="fa-solid fa-palette" style="font-size: 1.0rem; color: #de4968;"></i>
  </div>
  <div>
    <span style="font-family: 'Roboto', sans-serif; font-weight: 700; text-transform: uppercase; font-size: 1.1rem; color: #de4968;">I BELIEVE</span>
    <span> art is a science just like science is also an art. Both share a beauty that transcends boundaries, the symmetry in randomness, the harmony in disorders.. I pursue work that is a piece of art, rather than just good results.</span>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 25px;">
  <div style="flex: 0 0 40px; display: flex; justify-content: center; margin-top: 5px;">
    <i class="fa-solid fa-spa" style="font-size: 1.0rem; color: #fe9f6d;"></i>
  </div>
  <div>
    <span style="font-family: 'Roboto', sans-serif; font-weight: 700; text-transform: uppercase; font-size: 1.1rem; color: #fe9f6d;">I SEEK</span>
    <span> for a simple but unique life. "我们终此一生，就是要摆脱他人的期待，找到真正的自己" (*Our lifelong journey is to break free from others’ expectations and discover our truest selves.*)</span>
  </div>
</div>

<style>
.wrap {
  margin: 2rem 0;
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
  color: rgb(38,152,186);
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
  background: rgb(38,152,186);
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
  border-top:2px solid rgb(38,152,186);
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
  background: rgb(38,152,186);
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
  display:flex;
  align-items:flex-start;
  gap:24px;
  width:100%;
  max-width:1200px;
  margin:20px auto;
}
.diamond-group {
  display:flex;
  flex-direction:column;
  gap:-22px;
}
/* 不旋转a标签，用伪元素画菱形，点击热区完全正常 */
.diam-wrap {
  position:relative;
  width:110px;
  height:110px;
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

.text-group {
  display:flex;
  flex-direction:column;
  padding-top:18px;
  padding-bottom:18px;
  gap:32px;
}
.txt-item {
  font-weight:bold;
  font-size:42px;
  text-decoration:none;
}
.txt-yellow { color:#ffdd00; }
.txt-green  { color:#00dd00; }
.txt-red    { color:#ff0000; }
</style>

<div class="box-wrap">
  <div class="diamond-group">
    <a target="_blank" rel="noopener noreferrer" class="diam-wrap diam-yellow" href="https://youtu.be/rTHhyES8CqE"></a>
    <a target="_blank" rel="noopener noreferrer" class="diam-wrap diam-green" href="https://yusonwei.github.io/assets/pdf/MEng%20thesis.pdf"></a>
    <a target="_blank" rel="noopener noreferrer" class="diam-wrap diam-red" href="https://yusonwei.github.io/assets/pdf/Complete%20Mathematical%20Derivations%20—%20IEEE%20IoT%E2%80%91J%20Paper.pdf"></a>
  </div>

  <div class="text-group">
    <a target="_blank" rel="noopener noreferrer" href="https://youtu.be/rTHhyES8CqE" class="txt-item txt-yellow">Representative Academic Slides</a>
    <a target="_blank" rel="noopener noreferrer" href="https://yusonwei.github.io/assets/pdf/MEng%20thesis.pdf" class="txt-item txt-green">Master’s Dissertation with Improved<br>VO‑IDA Algorithm in Chapter 4</a>
    <a target="_blank" rel="noopener noreferrer" href="https://yusonwei.github.io/assets/pdf/Complete%20Mathematical%20Derivations%20—%20IEEE%20IoT%E2%80%91J%20Paper.pdf" class="txt-item txt-red">Complete Mathematical Derivation for IoT‑J Paper</a>
  </div>
</div>
