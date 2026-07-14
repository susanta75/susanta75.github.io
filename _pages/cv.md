---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/susanta-khamrui-resume.pdf" class="btn btn--primary" target="_blank" rel="noopener noreferrer"><i class="fa fa-fw fa-download" aria-hidden="true"></i> Download Resume (PDF)</a></p>

Education
======
* **PhD in Computer Science & Engineering**, IIT Kharagpur, *July 2026 &ndash; Present*
  * [Tr²AIL Lab](https://adityasomak.github.io/research/), advised by [Dr. Somak Aditya](https://adityasomak.github.io/)
  * Focus: verification and reasoning over large language models (LLMs)
* **M.Tech in Computer Science & Engineering (Data Science)**, IIITDM Jabalpur, *2024 &ndash; 2026*
  * Advised by [Dr. Ayan Seal](https://scholar.google.co.in/citations?user=n0lOKiAAAAAJ&hl=en)
  * Thesis: polyp segmentation for medical imaging
  * Admitted via GATE 2024
* **B.Tech in Electronics & Communication Engineering**, Dr. B. C. Roy Engineering College, Durgapur, *2019 &ndash; 2023*

Research experience
======
* July 2026 &ndash; Present: Graduate Researcher
  * [Tr²AIL Lab](https://adityasomak.github.io/research/), IIT Kharagpur
  * Working on verification and reasoning over LLMs
  * Supervisor: [Dr. Somak Aditya](https://adityasomak.github.io/)

* 2024 &ndash; 2026: M.Tech Thesis / Research Assistant
  * IIITDM Jabalpur
  * Worked on polyp segmentation (TAP-FuseNet, BAHNet) and salient object detection
  * Supervisor: [Dr. Ayan Seal](https://scholar.google.co.in/citations?user=n0lOKiAAAAAJ&hl=en)

Teaching experience
======
* Fall 2024: Data Structure in C, IIITDM Jabalpur
* Spring 2025: Design and Analysis of Algorithms, IIITDM Jabalpur
* Fall 2025: OOPs in Java, IIITDM Jabalpur
* Spring 2026: Data Clustering, IIITDM Jabalpur

Skills
======
* **Languages**: Python, Java
* **ML/DL**: PyTorch, Transformers
* **Systems**: Linux/Ubuntu, CUDA, GPU computing (A100, A5000)
* **Tools**: Git, GitHub

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

{% if site.talks.size > 0 %}
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
{% endif %}
