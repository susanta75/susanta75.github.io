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

Hello, I am **Susanta Khamrui**, a PhD student in the **Department of Computer Science & Engineering** at **IIT Kharagpur**, where I work in the [**Tr²AIL Lab**](https://adityasomak.github.io/research/) under the supervision of [**Dr. Somak Aditya**](https://adityasomak.github.io/). My research focuses on the **verification of large language models (LLMs)** — building tools and methods to reason about and validate LLM behavior as part of the lab's broader mission of transparent, human-aware AI through logic and reasoning.

Before starting my PhD, I completed my **M.Tech in Computer Science & Engineering (Data Science)** at **IIITDM Jabalpur**, where I worked under [**Dr. Ayan Seal**](https://scholar.google.co.in/citations?user=n0lOKiAAAAAJ&hl=en) on **polyp segmentation** in colonoscopy images and assisted with studies on **salient object detection**.

<hr />

<h2 id="interests" class="section-heading">Research Interests</h2>

<ul class="tag-pill-list">
  <li class="tag-pill">LLM Verification &amp; Reasoning</li>
  <li class="tag-pill">Neuro-Symbolic AI</li>
  <li class="tag-pill">Computer Vision</li>
  <li class="tag-pill">Medical Image Analysis</li>
</ul>

<h2 id="education" class="section-heading">Education</h2>

<div class="timeline">
  <div class="timeline-item">
    <p class="timeline-item__title">PhD in Computer Science &amp; Engineering</p>
    <p class="timeline-item__meta">IIT Kharagpur &middot; July 2026 &ndash; Present</p>
    <p class="timeline-item__desc"><a href="https://adityasomak.github.io/research/">Tr&sup2;AIL Lab</a>, advised by <a href="https://adityasomak.github.io/">Dr. Somak Aditya</a>. Focus: verification and reasoning over large language models.</p>
  </div>
  <div class="timeline-item">
    <p class="timeline-item__title">M.Tech in Computer Science &amp; Engineering (Data Science)</p>
    <p class="timeline-item__meta">IIITDM Jabalpur &middot; 2024 &ndash; 2026</p>
    <p class="timeline-item__desc">Advised by <a href="https://scholar.google.co.in/citations?user=n0lOKiAAAAAJ&hl=en">Dr. Ayan Seal</a>. Thesis on polyp segmentation for medical imaging.</p>
  </div>
  <div class="timeline-item">
    <p class="timeline-item__title">B.Tech in Electronics &amp; Communication Engineering</p>
    <p class="timeline-item__meta">Dr. B. C. Roy Engineering College, Durgapur &middot; 2019 &ndash; 2023</p>
  </div>
</div>

<h2 id="experience" class="section-heading">Experience</h2>

- **Graduate Researcher**, [Tr²AIL Lab](https://adityasomak.github.io/research/), IIT Kharagpur — *July 2026–Present*
  - Working on verification and reasoning over LLMs under [Dr. Somak Aditya](https://adityasomak.github.io/).
- **M.Tech Thesis**, IIITDM Jabalpur — *Completed, 2026*
  - Polyp segmentation for medical imaging (TAP-FuseNet, BAHNet).
- **Research Assistant**, IIITDM Jabalpur — *Completed*
  - Worked on salient object detection.

<h2 id="highlights" class="section-heading">Highlights</h2>

- GATE qualified (2024)

<h2 id="contact" class="section-heading">Contact</h2>

- Email: [skhamrui2002@gmail.com](mailto:skhamrui2002@gmail.com)
- Location: Kharagpur, India

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
