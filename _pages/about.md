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

My current research interests mainly lie in building systems for fast and efficient machine learning, focusing on Spiking Neural Networks and Large Language Model acceleration. I'm also interested in programing contests and traditional algorithms, and was a member of UESTC ACM-ICPC team.


# 🔥 News
- *2024.8*: I became a master's student at **Georgia Institute of Technology**.
- *2024.6*: I graduated from **UESTC**.
- *2024.4*: I joined [**ByteDance**](https://www.bytedance.com/) as an intern, developing cloud computing systems for Douyin (TikTok China) video search.
- *2023.12*: After a heated competition with the best students from various schools across the university, I'm awarded **The Most Outstanding Students Award of UESTC (2023)**. [Related link](https://mp.weixin.qq.com/s?__biz=MjM5NTQ4Mzc5Nw==&mid=2651596067&idx=1&sn=82204903a3fb3e452386725e72f441cd&chksm=bd0f5cd98a78d5cfa7aecca6983ead6d587fc59b3e5e89c83b9b07acbe548f7ad5dd01e8976d&scene=27)

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS2024 Poster</div><img src='images/STMixer.pdf' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

Spiking Token Mixer: An Event-Driven Friendly Former Structure for Spiking Neural Networks

\*Shikuang Deng, \*Yuhang Wu, **Kangrui Du**, Shi Gu

[*link*]([https://openreview.net/forum?id=RmQAKu1wCe](https://nips.cc/virtual/2024/poster/93999)) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- To harness the energy efficiency of Spiking Neural Networks (SNNs), deploying them on neuromorphic chips is essential.
- While recent advancements have significantly boosted SNN performance, many designs remain incompatible with asynchronous, event-driven chips, limiting their integration and energy-saving potential.
- We proposed a novel state-of-the-art spike-based transformer, STMixer, to address these limitations by relying solely on operations supported by asynchronous hardware.
- Our experiments validate STMixer's outstanding performance in both event-driven and clock-driven scenarios.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">In Submission to ICLR2025</div><img src='images/Fig1_neurips2024.png' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

Temporal Flexibility in Spiking Neural Networks: Towards Generalization Across Time Steps and Deployment Friendliness

**\*Kangrui Du**, \*Yuhang Wu, Shikuang Deng, Shi Gu

[*Old version*](https://openreview.net/forum?id=RmQAKu1wCe) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Existing direct training methods are confined to a fixed timestep, which hinders on-chip dynamic energy-performance balancing and renders the models incompatible with fully event-driven chips.
- Design *Mixed Timestep Training* to train *Temporal Flexible SNNs* compatible with varied temporal structures.
- TFSNN exhibits near-SOTA performance, generalization across varied timesteps, and event-driven friendliness.
- Our work is the **first to report large model results** (VGGSNN, cifar10-dvs) on fully event-driven platforms.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/cmvim.jpg' alt="sym" width="100%"></div></div>

<div class='paper-box-text' markdown="1">

CMViM: Contrastive Masked Vim Autoencoder for 3D Multi-modal Representation Learning for AD classification

Guangqian Yang, **Kangrui Du**, Zhihan Yang, Ye Du, Yongping Zheng, Shujun Wang 

[**Paper**](https://arxiv.org/abs/2403.16520) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- While many efforts were made on multimodal representation learning for medical datasets, few discussions are made to 3D medical images.
- Introduced *Mamba SSM* and *contrastive learning* in multimodal masked pre-training for 3D ViT. Our method surpassed current SOTA methods in multimodal diagnosis of Alzheimer's Disease.

</div>
</div>

# 🎖 Honors and Awards
- *2023.12* **The Most Outstanding Students Award of UESTC (2023)** (Top 10 undergraduates in UESTC)
- *2023.10* **2022-2023 China National Scholarship** (top **1%**)
- *2023.10* **9th Place Winner** in [IEEEXtreme 17.0](https://ieeextreme.org/ieeextreme-17-0-ranking/)
- *2022.10* **2021-2022 China National Scholarship** (top **1%**)
- *2022.10* **4th Place Winner** in [IEEEXtreme 16.0](https://ieeextreme.org/ieeextreme-16-0-ranking/)
- *2021.10* **2020-2021 China National Scholarship** (top **1%**)
- *2021.04* **Gold Medal** in [2020 ICPC Asia Kunming Regional Contest](https://icpc.global/)
- *2021.04* **Silver Medal** in [2020 ICPC Asia Asia-East Continent Final Contest (EC-Final)](https://icpc.global/)
- *2020.12* **Silver Medal** in [2020 ICPC Asia Shanghai Regional Contest](https://icpc.global/)

# 📖 Educations
- *2024.08 - Present*, **M.S. in Computational Science and Engineering**, Georgia Institute of Technology ([Gatech](https://www.gatech.edu/)). 
- *2020.09 - 2024.06*, **B.Eng. in Computer Science and Technology**, University of Electronic Science and Technology of China ([UESTC](https://en.uestc.edu.cn/)). 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.04 - Present*, Software Engineering Intern, search architecture group at [Bytedance](https://www.bytedance.com/), working on cloud computing systems for Douyin video search.

- *2021.10 - 2024.06*, Research Assistant, [Brain and Intelligence Lab](https://guslab.org/) at [UESTC](https://en.uestc.edu.cn/), working on spiking neural networks, supervised by [Prof. Shi Gu](https://guslab.org/).

- *2023.07 - 2024.03*, Research Intern, [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/en/), working on multimodal prognosis for Alzheimer's Disease(AD), supervised by [Prof. Shujun Wang](https://emma-sjwang.github.io/).
