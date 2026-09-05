---
permalink: /
title: "Susanta Khamrui"
author_profile: true
classes: wide
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

Hello, I am **Susanta Khamrui**, an aspiring PhD student working in **Computer Vision and Medical Image Analysis**. I recently completed my **M.Tech in Computer Science & Engineering (Data Science)** at **PDPM IIITDM Jabalpur** (CGPA: 8.7/10), where I worked under [**Dr. Ayan Seal**](https://scholar.google.co.in/citations?user=n0lOKiAAAAAJ&hl=en) on **attention-driven, multi-modal fusion architectures** for polyp segmentation in colonoscopy images (TAP-FuseNet, BAHNet, ADPNet), and assisted with studies on **visual saliency and attention mechanisms**.

My research centers on designing neural architectures that fuse heterogeneous feature streams to detect small, visually subtle structures that standard models under-detect, while adapting large foundation models under tight compute and data constraints. I am motivated to build **explainable, trustworthy computer vision systems** reliable enough for high-stakes deployment, and I am now looking for **PhD positions** to pursue this research further.

<hr />

<h2 id="interests" class="section-heading">Research Interests</h2>

<ul class="tag-pill-list">
  <li class="tag-pill">Medical &amp; Clinical Computer Vision</li>
  <li class="tag-pill">Attention-Driven Fusion</li>
  <li class="tag-pill">Explainable &amp; Trustworthy AI</li>
  <li class="tag-pill">Foundation Model Adaptation</li>
</ul>

<h2 id="education" class="section-heading">Education</h2>

<div class="timeline">
  <div class="timeline-item">
    <p class="timeline-item__title">M.Tech in Computer Science &amp; Engineering (Data Science)</p>
    <p class="timeline-item__meta">PDPM IIITDM Jabalpur &middot; August 2024 &ndash; June 2026</p>
    <p class="timeline-item__desc">CGPA: 8.7/10. Advised by <a href="https://scholar.google.co.in/citations?user=n0lOKiAAAAAJ&hl=en">Dr. Ayan Seal</a>. Thesis: <em>Representation Learning via Hybrid Fusion Architectures for Visual Segmentation</em>.</p>
  </div>
  <div class="timeline-item">
    <p class="timeline-item__title">B.Tech in Electronics &amp; Communication Engineering</p>
    <p class="timeline-item__meta">Dr. B. C. Roy Engineering College, Durgapur (MAKAUT) &middot; August 2019 &ndash; June 2023</p>
    <p class="timeline-item__desc">CGPA: 8.5/10. Focus: Digital Signal Processing, Probability &amp; Statistics, Engineering Mathematics.</p>
  </div>
</div>

<h2 id="experience" class="section-heading">Experience</h2>

<div class="timeline">
  <div class="timeline-item">
    <p class="timeline-item__title">Attention-Driven Fusion Architectures for Medical Image Segmentation (M.Tech Thesis)</p>
    <p class="timeline-item__meta">PDPM IIITDM Jabalpur &middot; February 2025 &ndash; June 2026</p>
    <p class="timeline-item__desc">Engineered TAP-FuseNet, a hybrid architecture using Transformer attention to fuse multiple feature streams for segmenting small, visually subtle targets (e.g. early-stage polyps), and adapted large foundation models via frozen-encoder strategies to keep compute costs low. Advised by <a href="https://scholar.google.co.in/citations?user=n0lOKiAAAAAJ&hl=en">Dr. Ayan Seal</a>.</p>
  </div>
  <div class="timeline-item">
    <p class="timeline-item__title">Visual Saliency &amp; Attention Mechanisms (Research Assistant)</p>
    <p class="timeline-item__meta">PDPM IIITDM Jabalpur &middot; August 2024 &ndash; January 2025</p>
    <p class="timeline-item__desc">Implemented multi-scale attention mechanisms and pyramidal hierarchies for efficient, explainable saliency detection. Advised by <a href="https://scholar.google.co.in/citations?user=n0lOKiAAAAAJ&hl=en">Dr. Ayan Seal</a>.</p>
  </div>
</div>

<h2 id="skills" class="section-heading">Skills</h2>

<p class="skills-group__label">Languages &amp; Tools</p>
<ul class="tag-pill-list">
  <li class="tag-pill">Python</li>
  <li class="tag-pill">C++</li>
  <li class="tag-pill">Java</li>
  <li class="tag-pill">Git &amp; GitHub</li>
  <li class="tag-pill">Linux</li>
  <li class="tag-pill">LaTeX</li>
</ul>

<p class="skills-group__label">Machine Learning &amp; Deep Learning</p>
<ul class="tag-pill-list">
  <li class="tag-pill">PyTorch</li>
  <li class="tag-pill">Attention Mechanisms</li>
  <li class="tag-pill">Multi-Modal Fusion</li>
  <li class="tag-pill">Foundation Model Adaptation</li>
  <li class="tag-pill">Transformers</li>
  <li class="tag-pill">Medical Image Segmentation</li>
</ul>

<p class="skills-group__label">Signal &amp; Image Processing</p>
<ul class="tag-pill-list">
  <li class="tag-pill">DSP</li>
  <li class="tag-pill">NumPy</li>
  <li class="tag-pill">SciPy</li>
  <li class="tag-pill">Pandas</li>
</ul>

<h2 id="highlights" class="section-heading">Highlights</h2>

- GATE qualified (2024)

<h2 id="contact" class="section-heading">Contact</h2>

- Email: [skhamrui2002@gmail.com](mailto:skhamrui2002@gmail.com)
- Location: Medinipur, West Bengal, India

<hr />

<h2 id="publications" class="section-heading">Publications</h2>

{% if site.publications.size > 0 %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% else %}
No publications yet.
{% endif %}

<hr />

<h2 id="projects" class="section-heading">Projects</h2>

{% if site.portfolio.size > 0 %}
  {% for post in site.portfolio limit: 5 %}
    {% include archive-single.html %}
  {% endfor %}
  <p><a href="{{ base_path }}/portfolio/">View all projects</a></p>
{% else %}
No projects yet.
{% endif %}

<hr />

<h2 id="teaching" class="section-heading">Teaching</h2>

- Data Structure in C — Fall 2024, IIITDM Jabalpur  
- Design and Analysis of Algorithms — Spring 2025, IIITDM Jabalpur  
- OOPs in Java — Fall 2025, IIITDM Jabalpur  
- Data Clustering — Spring 2026, IIITDM Jabalpur

<hr />

<h2 id="talks" class="section-heading">Talks</h2>

{% if site.talks.size > 0 %}
  {% for post in site.talks reversed limit: 5 %}
    {% include archive-single-talk.html %}
  {% endfor %}
  <p><a href="{{ base_path }}/talks/">View all talks</a></p>
{% else %}
No talks yet.
{% endif %}

<hr />

<h2 id="blog" class="section-heading">Blog Posts</h2>

{% if site.posts.size > 0 %}
  {% for post in site.posts limit: 5 %}
    {% include archive-single.html %}
  {% endfor %}
  <p><a href="{{ base_path }}/year-archive/">View all posts</a></p>
{% else %}
No blog posts yet.
{% endif %}
