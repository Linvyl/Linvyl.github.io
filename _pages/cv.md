---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

**B.Sc. in Information and Communication Technology (ICT)**  
University of Science and Technology of Hanoi (USTH), Vietnam  
*2020 – 2023*

---

## Research Experience

**AI Research Member**  
AI VIETNAM (AIVN)  
*2023 – 2025*  

- Conducted research on vision–language models and visual question answering.
- Contributed to international workshop publications at AAAI and ICCV.
- Participated in reading groups, research discussions, and collaborative experiments.

**AI Research Intern**  
Department of Pattern Recognition and Knowledge Engineering (PRaKE)  
Institute of Information Technology (IOIT), VAST  
*Apr 2023 – Oct 2023*  

- Worked on a deep learning–based facial authentication system for secure login.
- Designed and implemented an end-to-end pipeline including data preprocessing, face detection and alignment, and Siamese-network-based embedding learning.
- Gained experience in debugging vision pipelines and handling noisy, imbalanced data.

---

## Teaching Experience

**Support Teaching Assistant (STA)**  
AI VIETNAM (AIVN) — AIO2024–2025 Programme  
*2024 – Present*  

- Assisted in lesson preparation, technical documentation, and demonstration code development.
- Contributed to instructional materials for foundational and advanced machine learning topics, including linear regression, decision trees, gradient boosting, LightGBM, variational autoencoders, and diffusion models.
- Collaborated closely with instructors to improve clarity and structure of teaching materials.

---

## Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---

## Talks and Presentations

<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

---

## Teaching Materials

<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

---

## Skills

- **Machine Learning & Deep Learning:** Vision–Language Models, CNNs, Transformers, Diffusion Models
- **Computer Vision:** Face recognition, document understanding, text-rich image analysis
- **Programming:** Python, PyTorch, basic JAX
- **Research Skills:** Experimental design, ablation studies, paper writing, reproducibility

---

## Service and Academic Activities

- Research member at AI VIETNAM (AIVN)
- Contributor to open-source research codebases associated with published work
