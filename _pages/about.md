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

I am Chentao Cao, a second-year Ph.D. student at [TMLR group](https://bhanml.github.io/group.html) of Hong Kong Baptist University, advised by [Prof. Bo Han](https://bhanml.github.io/) and working with [Prof. Zhun Zhong](https://zhunzhong.site/). My research focuses on **trustworthy machine reasoning with foundation models**. I hope my research can help machines collaborate with humans for the common good.

My recent work includes:
- Agentic Systems for complex reasoning: [[AlphaApollo]](https://arxiv.org/pdf/2510.06261)
- Trustworthy Foundation Models: [[ReSA]](https://arxiv.org/pdf/2509.11629), [[NoisyTTA]](https://arxiv.org/pdf/2502.14604), [[EOE]](https://arxiv.org/pdf/2406.00806)


# Education
- *2024.09 - present*, Ph.D. Student, TMLR Group, Hong Kong Baptist University, advised by [Prof. Bo Han](https://bhanml.github.io/), worked closely with [Prof. Zhun Zhong](https://zhunzhong.site/).
- *2020.09 - 2023.06*, M.E. in Computer Technology, University of Chinese Academy of Sciences, advised by [Prof. Yanjie Zhu](https://scholar.google.com/citations?user=X2mIoQ4AAAAJ&hl=en) and [Prof. Dong Liang](https://scholar.google.com/citations?user=3cAJWoIAAAAJ&hl=en), worked closely with [Prof. Zhuo-Xu Cui](https://zhuoxucui.github.io/).
- *2016.09 – 2020.06*, B.E. in Communication Engineering, Harbin Institute of Technology.


# Selected Publications
\* Co-first author, † Corresponding author.

## Selected Preprint

- AlphaApollo: Orchestrating Foundation Models and Professional Tools into a Self-Evolving System for Deep Agentic Reasoning<br>
Zhanke Zhou, **Chentao Cao**, Xiao Feng, Xuan Li, Zongze Li, Xiangyu Lu, Jiangchao Yao, Weikai Huang, Linrui Xu, Tian Cheng, Guanyu Jiang, Yiming Zheng, Brando Miranda, Tongliang Liu, Sanmi Koyejo, Masashi Sugiyama, Bo Han<br>
[[Paper]](https://arxiv.org/pdf/2510.06261) [[Code]](https://github.com/tmlr-group/AlphaApollo)

## Selected Conference

- Reasoned Safety Alignment: Ensuring Jailbreak Defense via Answer-Then-Check<br>
**Chentao Cao**, Xiaojun Xu, Bo Han†, Hang Li.<br>
ICLR 2026. [[Paper]](https://arxiv.org/pdf/2509.11629) [[Website]](https://resa-bytedance.github.io/) [[Dataset]](https://huggingface.co/datasets/ByteDance-Seed/ReSA)

- DualCnst: Enhancing Zero-Shot Out-of-Distribution Detection via Text-Image Consistency in Vision-Language Models<br>
Fayi Le, Wenwu He†, **Chentao Cao**, Dong Liang†, Zhuo-Xu Cui†.<br>
NeurIPS 2025. [[Paper]](https://openreview.net/pdf?id=6uwV6ytamU) [[Code]](https://github.com/TMLSIAT/DualCnst)

- From Debate to Equilibrium: Belief-Driven Multi-Agent LLM Reasoning via Bayesian Nash Equilibrium<br>
Yi Xie, Zhanke Zhou, **Chentao Cao**, Qiyu Niu, Tongliang Liu, Bo Han†.<br>
ICML 2025. [[Paper]](https://arxiv.org/pdf/2506.08292) [[Code]](https://github.com/tmlr-group/ECON)

- Noisy Test-Time Adaptation in Vision-Language Models<br>
**Chentao Cao**, Zhun Zhong†, Zhanke Zhou, Tongliang Liu, Yang Liu, Kun Zhang, Bo Han†.<br>
ICLR 2025. [[Paper]](https://arxiv.org/pdf/2502.14604) [[Code]](https://github.com/tmlr-group/ZS-NTTA)

- Envisioning Outlier Exposure by Large Language Models for Out-of-Distribution Detection<br>
**Chentao Cao**, Zhun Zhong†, Zhanke Zhou, Yang Liu, Tongliang Liu, Bo Han†.<br>
ICML 2024. [[Paper]](https://arxiv.org/pdf/2406.00806) [[Code]](https://github.com/tmlr-group/EOE)

## Selected Journal

- SPIRiT-Diffusion: Self-Consistency Driven Diffusion Model for Accelerated MRI<br>
Zhuo-Xu Cui\*, **Chentao Cao**\*, Yue Wang\*, Sen Jia, Jing Cheng, Xin Liu, Hairong Zheng, Dong Liang†, Yanjie Zhu†<br>
IEEE Transactions on Medical Imaging, 2024. [[Paper]](https://arxiv.org/pdf/2304.05060) [[Code]](https://github.com/zhyjSIAT/SPIRiT-Diffusion)

- High-Frequency Space Diffusion Model for Accelerated MRI<br>
**Chentao Cao**\*, Zhuo-Xu Cui\*, Yue Wang\*, Shaonan Liu, Taijin Chen, Hairong Zheng, Dong Liang, Yanjie Zhu†<br>
IEEE Transactions on Medical Imaging, 2024. [[Paper]](https://arxiv.org/pdf/2208.05481) [[Code]](https://github.com/Aboriginer/HFS-SDE)

# Awards
- *2024.06*, ICML Travel Award.


# Talks
- *2025.03*, Noisy Test-Time Adaptation in Vision-Language Models @AI Time, Online.
- *2024.06*, Envisioning Outlier Exposure by Large Language Models for Out-of-Distribution Detection @AI Time, Online.


# Tutorials Organizer
- AAAI 2026 Tutorial on Trustworthy Machine Reasoning with Foundation Models.
[[Website]](https://trustworthy-machine-reasoning.github.io/) [[Slides]](https://trustworthy-machine-reasoning.github.io/AAAI2026Tutorial-TH10-slides-20250120-v6.pdf)

# Program Committee/Reviewer
- Program Committee/Reviewer: NeurIPS, ICML, ICLR.
- Journal Reviewer: TPAMI, IJCV, JAIR, NEUNET.


# Teaching
- Teaching Assistant for COMP3065 (UG) Artificial Intelligence Application Development, Sem. 2, 2025.
- Teaching Assistant for COMP7025 (G) Artificial Intelligence for Digital Transformation, Sem. 1, 2025.
- Teaching Assistant for COMP7025 (G) Artificial Intelligence for Digital Transformation, Sem. 2, 2024.

<br>
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=xAu4Mkp0NArssBb6bfFjG1yx7QWKZyxizECvptuGDO0&cl=ffffff&w=a"></script>
