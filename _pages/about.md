---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About Me

I am **Qihao Xu**, currently affiliated with **Harbin Institute of Technology (Shenzhen)**. My research interests mainly include **computer vision**, **medical image analysis**, **interpretable artificial intelligence**, and **trustworthy machine learning**.

My recent research focuses on developing explainable and reliable AI systems for medical image diagnosis. In particular, I am interested in **concept bottleneck models**, **multi-view medical image understanding**, **vision-language-guided reasoning**, **uncertainty-aware diagnosis**, and **hyperbolic representation learning**. The goal of my research is to build AI models that are not only accurate but also transparent, clinically meaningful, and easy for human experts to verify and intervene.

I am especially interested in interpretable diagnosis for ophthalmic and dermatological images, including diabetic retinopathy grading, lesion-concept prediction, and concept-based medical decision-making.

Google Scholar: 
<a href='https://scholar.google.com/citations?user=y4MVyeEAAAAJ&hl=zh-CN'>Google Scholar Profile</a>
<a href='https://scholar.google.com/citations?user=y4MVyeEAAAAJ&hl=zh-CN'>
<img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">
</a>


# 🔥 News

- *2026.05*: &nbsp;🎉 Our work on interpretable multi-view diabetic retinopathy diagnosis is under active development.
- *2026.05*: &nbsp;🎉 I am maintaining this personal homepage to share my research, publications, and academic activities.
- *2026.04*: &nbsp;🎉 Our recent research focuses on concept-based reasoning, uncertainty-aware fusion, and trustworthy medical AI.


# 📝 Publications 

## Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Medical AI</div><img src='images/500x300.png' alt="ProConMV" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ProConMV: Provenance-Enabled Conceptual Framework for Interpretable Multi-View Diabetic Retinopathy Diagnosis](#)

**Qihao Xu**, et al.

[**Paper**](#) | [**Code**](#) | [**Project**](#)

- We propose an interpretable multi-view diabetic retinopathy diagnosis framework that integrates multi-view fundus images, lesion masks, clinical text priors, concept-based reasoning, physician intervention, and dual-uncertainty fusion.
- The model aims to provide a transparent diagnostic chain from medical images to lesion concepts and final disease grading.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Explainable AI</div><img src='images/500x300.png' alt="HCEM" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hyperbolic Concept Embedding Model for Interpretable Medical Image Diagnosis](#)

**Qihao Xu**, et al.

[**Paper**](#) | [**Code**](#) | [**Project**](#)

- We explore hyperbolic representation learning for concept-based medical image diagnosis.
- The model embeds medical concepts and diseases into hyperbolic space to better capture hierarchical and semantic relationships among clinical concepts.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Vision-Language Reasoning</div><img src='images/500x300.png' alt="VLM-GCR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Vision-Language-Guided Graph Conceptual Reasoning for Medical Image Diagnosis](#)

**Qihao Xu**, et al.

[**Paper**](#) | [**Code**](#) | [**Project**](#)

- We investigate vision-language-guided concept graph reasoning for medical image diagnosis.
- The method aims to combine visual evidence, clinical concepts, and graph-structured medical knowledge for more interpretable predictions.

</div>
</div>


## Other Publications

- [Title of Your Paper](#), **Qihao Xu**, Author B, Author C, *Conference/Journal*, Year.
- [Title of Your Paper](#), Author A, **Qihao Xu**, Author C, *Conference/Journal*, Year.
- [Title of Your Paper](#), Author A, Author B, **Qihao Xu**, *Conference/Journal*, Year.


# 🎖 Honors and Awards

- *2026*: To be updated.
- *2025*: To be updated.
- *2024*: To be updated.


# 📖 Education

- *Present*, Harbin Institute of Technology (Shenzhen), Shenzhen, China.
- Research area: Computer Vision, Medical Image Analysis, and Interpretable Artificial Intelligence.


# 💬 Academic Services

- Reviewer for conferences and journals in computer vision, medical image analysis, and artificial intelligence.
- Research topics include interpretable medical AI, concept-based learning, multi-view diagnosis, uncertainty estimation, and trustworthy machine learning.


# 💻 Research Interests

- Interpretable Artificial Intelligence
- Medical Image Analysis
- Concept Bottleneck Models
- Multi-view Medical Diagnosis
- Vision-Language Medical Reasoning
- Hyperbolic Representation Learning
- Uncertainty-Aware Deep Learning
- Trustworthy Machine Learning
