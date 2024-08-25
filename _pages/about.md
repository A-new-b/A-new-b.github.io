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

🔥🔥🔥<font color=red>I am looking for a Ph.D. position.</font> If you would like to discuss potential opportunities or learn more about my qualifications, please feel free to contact me [jue.wang.info@gmail.com](jue.wang.info@gmail.com).

My research interest mainly includes:
  + **Multi-modal LLM**: LLM Reasoning, LLM Application.
  + **Diffusion model**: High Quality and Stable Image Generation.
  + **Nerf/3D GS**: 3D Scene Reconstruction.
  + **Multispectral Detection**: Multispectral/Hyperspectral Imaging and Detection.

# 📖 Educations
- *2022.08 - now*, Southern University of Science and Technology, Master in Electronic and Information Engineering.
- *2018.08 - 2022.06*, Northeastern University, Bachelor in Information and Computing Science.

# 🔥 News
- *2024.07*: Our paper about invisible gas detection is accepted by CVIU (JCR Q1, CCF rank B). 🎉.
- *2024.06*: We propose a new task and benchmark about understanding emotional triggers. Checkout the [EmCoBench](https://github.com/Lum1104/EmCoBench/tree/main).
- *2024.03*: We published a paper about RGB-T gas detection. Checkout the [Invisable Gas Detection](https://arxiv.org/abs/2403.17712).

# 📝 Publications 
Working in Progress: CVIU (1: Accepted); AAAI (2: Under Review);
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Arxiv</div>
        <img src='resources/FlexEdit/model.png' alt="flexedit" width="100%">
      </div>
    </div>
  <div class='paper-box-text' markdown="1">

  [FlexEdit: Marrying Free-Shape Masks to VLLM for Flexible Image Editing](https://arxiv.org/abs/2408.12429)

  **Jue Wang\***, Yuxiang Lin\*, Tianshuo Yuan, Zhi-Qi Cheng, Xiaolong Wang, Jiao GH, Wei Chen, Xiaojiang Peng (\* denotes equal contribution)

  **<font color=red>Arxiv</font>** \| [[Paper]](https://arxiv.org/abs/2408.12429)
  - We propose FlexEdit, an end-to-end image editing method that combines free-shape masks and language instructions, overcoming the limitations of traditional methods that require precise mask drawing.
  - We introduce the Mask Enhanced Adapter (MEA) structure that seamlessly enhance the mask embedding of the Vision Large Language Model (VLLM) with image data, enhancing the model’s ability to understand and execute complex editing tasks.
  - We create the Free Shape Mask Instruction Edit (FSIM-Edit) benchmark, which includes a comprehensive dataset with diverse scenarios and editing instructions, to rigorously evaluate the performance of image editing models under free-shape mask conditions.
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CVIU</div>
        <img src='resources/RT_CAN/gas.png' alt="gas" width="100%">
      </div>
    </div>
  <div class='paper-box-text' markdown="1">

  [Invisible Gas Detection: An RGB-Thermal Cross Attention Network and A New Benchmark](https://arxiv.org/pdf/2403.17712)

  **Jue Wang\***, Yuxiang Lin\*, Qi Zhao, Dong Luo, Shuaibao Chen, Wei Chen, Xiaojiang Peng (\* denotes equal contribution)

  **<font color=red>CVIU(JCR Q1, CCF-B)</font>** \| [[Paper]](https://arxiv.org/pdf/2403.17712)[[Code]](https://github.com/logic112358/RT-CAN)
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
