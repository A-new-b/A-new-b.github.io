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

Hi👋，I am Jue Wang, an MS student at [Southern University of Science and Technology](https://www.sustech.edu.cn/)<img src='images/sustech.png' style='width: 1.1em;'> and [Shenzhen Institute of Advanced Technology (SIAT), CAS](https://english.siat.ac.cn/) <img src='images/favicon-32x32.png' style='width: 1.1em;'>. 

You can find me at [jue.wang.info@gmail.com](jue.wang.info@gmail.com).

My research interest mainly includes:
  + **Multi-modal LLM**: LLM Reasoning, LLM Application.
  + **Diffusion model**: High Quality and Stable Image Generation.
  + **Nerf/3D GS**: 3D Scene Reconstruction.


# 📖 Educations
- *2022.08 - now*, Southern University of Science and Technology, Master in Electronic and Information Engineering.
- *2018.08 - 2022.06*, Northeastern University, Bachelor in Information and Computing Science.

# 🔥 News
- *2024.06*: We propose a new task and benchmark about understanding emotional triggers. Checkout the [EmCoBench](https://github.com/Lum1104/EmCoBench/tree/main).
- *2024.03*: We published a paper about RGB-T gas detection. Checkout the [Invisable Gas Detection](https://arxiv.org/abs/2403.17712).

# 📝 Publications 
Working in Progress: CVIU (1: Under Review); NeurIPS (2: Under Review);

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ArXiv Preprint</div>
        <img src='resources/emco/emcobench.png' alt="emco" width="100%">
      </div>
    </div>
  <div class='paper-box-text' markdown="1">

  [EmCoBench: An Extensive Benchmark for General Emotion Comprehension](../resources/emco/emcobench_paper.pdf)

  Yuxiang Lin, **Jue Wang**, Haomin Liang, Zebang Cheng, Jun-Yan He, Zhi-Qi Cheng, Xiaojiang Peng, Alexander G. Hauptmann

  **<font color=red>ArXiv</font>** \| [[Paper]](../resources/emco/emcobench_paper.pdf) [[Code]](https://github.com/Lum1104/EmCoBench)
  - We proposing the Emotion Comprehension task, which focuses on identifying emotional triggers rather than merely classifying emotions, crucial for building more empathetic systems;
  - We introducing the Coarse-to-Fine Self-Ask (CFSA) method, a novel VLLM-assisted data annotation technique;
  - We developing the EmCoBench dataset, which includes 78 fine-grained emotions and 1,655 emotion comprehension samples, with 50 multifacets complex samples;

  </div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ArXiv Preprint</div>
        <img src='resources/RT_CAN/gas.png' alt="gas" width="100%">
      </div>
    </div>
  <div class='paper-box-text' markdown="1">

  [Invisible Gas Detection: An RGB-Thermal Cross Attention Network and A New Benchmark](https://arxiv.org/pdf/2403.17712)

  **Jue Wang\***, Yuxiang Lin\*, Qi Zhao, Dong Luo, Shuaibao Chen, Wei Chen, Xiaojiang Peng (\* denotes equal contribution)

  **<font color=red>ArXiv</font>** \| [[Paper]](https://arxiv.org/pdf/2403.17712)
  - We design the RGB-Thermal Cross Attention Network for invisible gas detection, by effectively integrating texture information from RGB images and gas information from thermal images.
  - We propose the RGB-assisted Cross Attention Module and the Global Textual Attention Module for cross modality feature fusion and diverse contextual information extraction.
  - We introduce Gas-DB, the first comprehensive open-source gas detection database, including approximately 1.3K well-annotated RGB-thermal images for gas detection algorithms.

  </div>
</div>


# 💻 Experience
- *2023.12 - now*, Research Intern, [MIPS-Lab](https://scholar.google.com/citations?user=7oRD67kAAAAJ).
- *2023.06 - 2023.07*, Teaching Assistant, [OpenMMLab](https://github.com/open-mmlab/OpenMMLabCourse)


# 🎖 Honors and Awards
- *2024.01* Outstanding Graduate Student of Southern University of Science and Technology for the Academic Year 2022-2023.
- *2023.03* Winner Award in the 18th "Challenge Cup" SUSTech Inramural Competition. 