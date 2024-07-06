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

Hi! I'm Kangrui Du, a first-year M.S. in Computational Science and Engineering at College of Computing, [Georgia Institute of Technology](https://www.gatech.edu/). Before that, I received my Bachelor's degree in Computer Science and Technology at [University of Electronic Science and Technology of China (UESTC)](https://en.uestc.edu.cn/), where I was a member of [Brain and Intelligence Lab](https://guslab.org/) at [(UESTC)](https://en.uestc.edu.cn/) supervised by [Prof. Shi Gu](https://guslab.org/). I was a research intern at [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/en/) where I'm fortunate to work with [Prof. Shujun Wang](https://emma-sjwang.github.io/).
<!-- My research interests lie in building, analyzing and applying efficient and low energy intelligent systems, including spiking neural networks, efficient AI, and medical image analysis.  -->
My current research interests mainly lie in building systems for fast and efficient machine learning. I'm also interested in programing contests and traditional algorithms, and was a member of UESTC ACM-ICPC team.
<!-- construction, analysis, and practical implementation of efficient intelligent systems, including spiking neural networks, efficient AI, and medical image analysis. -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">In Submission to NeurIPS2024</div><img src='images/tiny_fig1.svg' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

Temporal Flexibility in Spiking Neural Networks: Towards Generalization Across Time Steps and Deployment Friendliness

**Kangrui Du**, Yuhang Wu, Shikuang Deng, Shi Gu

[*Old version*](https://openreview.net/forum?id=RmQAKu1wCe) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Existing direct training methods are confined to a fixed timestep, which hinders on-chip dynamic energy-performance balancing and renders the models incompatible with fully event-driven chips.
- Design *Mixed Timestep Training* to train *Temporal Flexible SNNs* compatible with varied temporal structures.
- TFSNN exhibits near-SOTA performance, generalization across varied timesteps, and event-driven friendliness.
- Our work is the **first to report large model results** (VGGSNN, cifar10-dvs) on fully event-driven platforms.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/tiny_fig1.svg' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

CMViM: Contrastive Masked Vim Autoencoder for 3D Multi-modal Representation Learning for AD classification

Guangqian Yang, **Kangrui Du**, Zhihan Yang, Ye Du, Yongping Zheng, Shujun Wang 

[**Paper**](https://arxiv.org/abs/2403.16520) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- While many efforts were made on multimodal representation learning for medical datasets, few discussions are made to 3D medical images.
- Introduced *Mamba SSM* and *contrastive learning* in multimodal masked pre-training for 3D ViT. Our method surpassed current SOTA methods in multimodal diagnosis of Alzheimer's Disease.

</div>
</div>

# 🎖 Honors and Awards
- *2023.10* **2022-2023 China National Scholarship** (top **0.1%**)
- *2022.10* **2021-2022 China National Scholarship** (top **0.1%**)
- *2022.10* **4th Place Winner** in [IEEEXtreme 16.0](https://ieeextreme.org/ieeextreme-16-0-ranking/)
- *2021.10* **2020-2021 China National Scholarship** (top **0.1%**)
- *2021.04* **Gold Medal** in [2020 ICPC Asia Kunming Regional Contest](https://icpc.global/)
- *2021.04* **Silver Medal** in [2020 ICPC Asia Asia-East Continent Final Contest (EC-Final)](https://icpc.global/)
- *2020.12* **Silver Medal** in [2020 ICPC Asia Shanghai Regional Contest](https://icpc.global/)

# 📖 Educations
- *2020.09 - 2024.06 (expected)*, **B. Eng. Degree in Computer Science**, University of Electronic Science and Technology of China ([UESTC](https://en.uestc.edu.cn/)). 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2021.10 - Present*, Research Intern, [Brain and Intelligence Lab](https://guslab.org/) at [UESTC](https://en.uestc.edu.cn/), working on spiking neural networks, supervised by [Prof. Shi Gu](https://guslab.org/).

- *2023.07 - Present*, Research Intern, [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/en/), working on multimodal prognosis for Alzheimer's Disease(AD), supervised by [Prof. Shujun Wang](https://emma-sjwang.github.io/).