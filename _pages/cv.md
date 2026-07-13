---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="academic-actions">
  <a class="btn btn--primary" href="/files/CV-Liu-Jie.pdf">Download CV as PDF</a>
</div>

## Academic appointments

- **Postdoctoral Fellow**, Department of Industrial Engineering and Decision Analytics, HKUST, July 2025–present<br>
  Supervisor: Prof. Jiheng Zhang
- **Research Assistant**, Department of Industrial Engineering and Decision Analytics, HKUST, July 2022–January 2023

## Education

- **Ph.D. in Data Science**, School of Data Science, CUHK(SZ), 2021–2025<br>
  Presidential Fellowship<br>
  Dissertation: *Online Decision Making in Revenue Management: Theory and Applications*<br>
  Supervisors: Prof. Zizhuo Wang and Prof. Hailun Zhang
- **B.S. in Mathematics and Applied Mathematics**, School of Science and Engineering, CUHK(SZ), 2017–2021<br>
  First Class Degree; First Class Academic Scholarship (top 1%)

## Research interests

- Game theory
- Pricing and revenue management
- Stochastic models
- Data-driven decision-making

## Publications and preprints

<ul class="cv-list">
{% assign ordered_publications = site.publications | sort: "order" %}
{% for post in ordered_publications %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Research project

**Impact of information transparency on airline revenue management**, with China Southern Airlines, 2023–2024

- Served as a core member studying the impact of information transparency through theoretical modeling and numerical simulation.
- Co-authored three industry reports and presented findings to stakeholders, supporting project approval and closure.

## Industry experience

**Operations Research Algorithm Intern**, Cardinal Operations, May 2024–February 2025

- One of three core algorithm developers for Huanghua Port's Intelligent Integrated Scheduling Platform.
- Developed algorithms for unified production scheduling, equipment optimization, and intelligent decision-making.

**Machine Learning Algorithm Research Assistant**, Shenzhen Research Institute of Big Data, June 2020–May 2021

- Developed an NLP model using feature engineering and convolutional neural networks to extract summaries and argumentation information from judicial judgment texts.

## Teaching experience

<ul class="cv-list">
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Award

- **Champion**, Smart City Datathon 2018, Asian Institute of Supply Chains & Logistics, CUHK
