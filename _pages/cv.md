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

*Prospective PhD applicant, focusing on Computer Vision & Medical Image Analysis.*

Professional Profile
======
M.Tech in Data Science (PDPM IIITDM Jabalpur, graduated June 2026), with a B.Tech in Electronics and Communication Engineering. My research centers on attention-driven, multi-modal fusion architectures for medical image analysis, with emphasis on segmenting and localizing small, visually subtle structures such as early-stage colorectal polyps. Proficient in Python, C++, and PyTorch, with hands-on experience adapting large-scale foundation models via frozen-encoder and parameter-efficient strategies to learn reliably from limited, noisy data — a constraint common across specialized computer vision domains, not only clinical imaging. Motivated to extend this foundation toward explainable, robust computer vision systems trustworthy enough for deployment in high-stakes settings.

Technical Interests
======
* **Medical & Clinical Computer Vision**: Segmentation, localization, and detection architectures for clinical imaging data, with emphasis on small, visually subtle targets.
* **Attention-Driven & Multi-Modal Fusion Architectures**: Designing neural networks that combine heterogeneous feature streams into unified, task-relevant representations.
* **Explainable & Trustworthy AI**: Building interpretability into model architectures directly — via attention mechanisms whose weights are themselves evidence — rather than adding explanation methods after training.
* **Foundation Model Adaptation & Resource-Efficient Deep Learning**: Adapting large pretrained visual encoders under tight compute and data constraints typical of specialized, data-scarce domains.

Education
======
* **M.Tech in Computer Science & Engineering (Data Science)**, PDPM IIITDM Jabalpur, *August 2024 &ndash; June 2026*
  * CGPA: 8.7 / 10
  * Thesis: *Representation Learning via Hybrid Fusion Architectures for Visual Segmentation*, advised by [Dr. Ayan Seal](https://scholar.google.co.in/citations?user=n0lOKiAAAAAJ&hl=en)
  * Admitted via GATE 2024
* **B.Tech in Electronics & Communication Engineering**, Dr. B. C. Roy Engineering College, Durgapur (MAKAUT), *August 2019 &ndash; June 2023*
  * CGPA: 8.5 / 10
  * Focus: Digital Signal Processing, Probability & Statistics, and Engineering Mathematics

Research & Project Experience
======
* **Attention-Driven Fusion Architectures for Medical Image Segmentation** (M.Tech Thesis)
  * Supervisor: [Dr. Ayan Seal](https://scholar.google.co.in/citations?user=n0lOKiAAAAAJ&hl=en), PDPM IIITDM Jabalpur &middot; *February 2025 &ndash; June 2026*
  * Engineered "TAP-FuseNet," a hybrid architecture using Transformer attention to fuse multiple feature streams for segmenting small, visually subtle targets (e.g. early-stage polyps) that standard models under-detect, and adapted large foundation models via frozen-encoder strategies to keep compute costs low.
  * Result: hands-on expertise in attention-driven, multi-modal fusion architectures that generalize under noisy, real-world conditions — transferable across clinical imaging and other data-constrained detection problems.

* **Visual Saliency & Attention Mechanisms** (Research Assistant)
  * PDPM IIITDM Jabalpur &middot; *August 2024 &ndash; January 2025*
  * Implemented multi-scale attention mechanisms and pyramidal hierarchies so models focus computation on relevant regions rather than background, cutting unnecessary processing overhead.
  * Result: learned to build models whose internal attention is itself a source of explanation, and to reason about model behaviour under noisy or corrupted inputs — core to both explainability and robustness in applied computer vision.

Teaching experience
======
* Fall 2024: Data Structure in C, IIITDM Jabalpur
* Spring 2025: Design and Analysis of Algorithms, IIITDM Jabalpur
* Fall 2025: OOPs in Java, IIITDM Jabalpur
* Spring 2026: Data Clustering, IIITDM Jabalpur

Skills
======
* **Languages & Tools**: C++, Python, Java, Git/GitHub, Linux, LaTeX, VS Code
* **Machine Learning & DL**: PyTorch, Attention Mechanisms, Multi-Modal Fusion, Foundation Model Adaptation, Transformers, Medical Image Segmentation
* **Signal & Image Processing**: DSP, NumPy, SciPy, Pandas

Language Proficiency
======
* English — Fluent (Professional)
* Bengali — Native
* Hindi — Fluent

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

Referees
======
* **Dr. Ayan Seal** (Supervisor) — Assistant Professor, PDPM IIITDM Jabalpur
* **Dr. Sraban Kumar Mohanty** — Assistant Professor, PDPM IIITDM Jabalpur
* **Dr. Ashish Kumar Gupta** — Assistant Professor, Thapar Institute of Engineering and Technology

*Contact details available on request.*
