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

I am currently an undergraduate student in computer science at the [University of Minnesota Twin Cities](https://twin-cities.umn.edu/). I transferred from the [Beijing University of Chemical Technology](https://www.buct.edu.cn/main.html), where I studied computer science for one years. I am also a visiting student at the [HCP Laboratory of Sun Yat-sen University](https://www.sysu-hcp.net/).

Previously, my research interests were in learning with noisy labels, semi-supervised learning, and test-time adaptation. My current research interests include multimodal large models, reinforcement learning in Embodied Instruction Following and prompt learning.

# 💻 Experience 
- *2024.12 - present*, Sun Yat-sen University, HCP Lab, Visiting Student.  
  <!-- - Supervised by [Ruirui Li](https://en-cist.buct.edu.cn/2024/1226/c13314a202781/pagem.htm) -->
  - Research Focus: Multimodal Large Models, Reinforcement Learning, Embodied Instruction Following

- *2024.01 - 2025.03*, Beijing University of Chemical Technology, Vision Lab.  
  <!-- - Supervised by [Ruirui Li](https://en-cist.buct.edu.cn/2024/1226/c13314a202781/pagem.htm) -->
  - Research Focus: Label-Noise Learning, Semi-Supervised Learning, Test-Time Adaptation.

- *2023.09 - 2023.12*, Beijing University of Chemical Technology, ACM Laboratory.  
  <!-- - Supervised by [Yong Liu](https://liuyong0076.github.io/) -->
  - Research Focus: Competitive programming training, with an emphasis on data structures, dynamic programming, and graph theory.

# 🔥 News
<!-- - *2023.10*: &nbsp; 🎉🎉🎉 Achieved a silver (🥈) and a bronze (🥉) medal at the ICPC Asia Regional Contest.
- *2024.01*: &nbsp; 🎉 Joined BUCT Vision Lab, marking a new chapter in my research journey.
- *2024.11*: &nbsp; 🎉 Began my role as a Visiting Student at HCP, expanding my academic horizons.
- *2025.01*: &nbsp; 🎉 Started my undergraduate studies at the University of Minnesota Twin Cities. -->
- *2025.03*: &nbsp; 🎉🎉🎉One paper accepted at ICME 2025 on test-time adaptation.
- *2025.03*: &nbsp; 🎉🎉🎉One paper accepted at ICLR 2025 FM-Wild Workshop on test-time adaptation.

# 📝 Publications (* Equal Contribution)

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review</div>
      <img src='images/MCP.png' alt="Paper Thumbnail" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Multi-Cache enhanced Prototype Learning for Test-Time Generalization of Vision-Language Models]()

<!-- <span style="color:green">Also accepted at ICLR 2025 FM-Wild Workshop</span> -->

*We observed that cache-based test-time adaptation performance is positively correlated with intra-class compactness. To address the unreliability of low-entropy samples under distribution shifts, we propose MCP, which uses an entropy cache for prototype initialization, an align cache to fuse visual and textual information and tighten intra-class distributions, and a negative cache to calibrate high-entropy predictions. We further extend this into the MCP++ framework by introducing cross-modal prototype alignment and residual learning, achieving state-of-the-art generalization on 15 downstream tasks.*

**Xinyu Chen<sup>*</sup>, Haotian Zhai<sup>*</sup>, Can Zhang<sup>*</sup>, Xiupeng Shi<sup>†</sup>, Ruirui Li<sup>†</sup>**

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICME 2025 (CCF-B)</div>
      <img src='images/mitigating-cache-noise.png' alt="Paper Thumbnail" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[Mitigating Cache Noise in Test-Time Adaptation for Large Vision-Language Models](https://arxiv.org/abs/2503.18334)

<span style="color:green">Also accepted at ICLR 2025 FM-Wild Workshop</span>

*We analyzed the root causes of the performance gap between zero-shot and few-shot TTA, identifying noisy cache labels as a critical bottleneck. We then propose the CRG framework, which maintains positive and negative visual prototypes alongside text prototypes, employs learnable residuals to align modalities, and leverages Gaussian Discriminant Analysis to dynamically model class distributions and suppress noisy samples. Finally, by jointly minimizing prediction entropy and maximizing inter-prototype distances, CRG achieves superior robustness and generalization across 13 benchmarks..*

**Haotian Zhai<sup>*</sup>, Xinyu Chen<sup>*</sup>, Can Zhang<sup>*</sup>, Tianming Sha, Ruirui Li<sup>†</sup>**


</div>
</div>

# 🎖 Honors and Awards
- *2023.10*: &nbsp; 🎉🎉🎉 Achieved a silver (🥈) and a bronze (🥉) medal at the ICPC Asia Regional Contest.

# 📖 Educations
- *2025.01 - 2027.6 (expected)*, Bachelor of Arts in Computer Science, University of Minnesota Twin Cities

- *2023.09 - 2024.10*, Bachelor of Engineering in Computer Science, Beijing University of Chemical Technology

