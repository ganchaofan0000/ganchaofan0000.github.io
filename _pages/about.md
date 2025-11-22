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

I am currently a joint Ph.D. candidate of **[Shanghai Jiao Tong University](https://www.sjtu.edu.cn)** and **[Monash University](https://www.monash.edu)** from [SEIEE](https://www.seiee.sjtu.edu.cn) since 2022, 
working with [Prof. Weiyao Lin](https://weiyaolin.github.io) and [Prof. Mehrtash Harandi](https://sites.google.com/site/mehrtashharandi/).
Before that, I spent 4 wonderful years studying at **[Huazhong University of Science and Technology](https://www.hust.edu.cn/)** as an undergraduate student since 2018 (top 5%).
My research interests lie in visual generation, visual understanding, and noise learning, with a particular focus on Diffusion Transformer (DiT). Currently, my work centers on **Unified Visual Generation and Understanding with DiT**, aiming to overcome the long-standing disconnect between these two tasks and enable them to mutually enhance each other.

If you are interested in my work, please contact me via *<ganchaofan@sjtu.edu.cn>*.


# 🎯 Research Interests
- **Diffusion Transformers**: Visual Generation and Representation Learning with DiTs, _et al._ 
- **Image/Video Understanding**: Multimodal Large Models, _et al._ 
- **Noise Learning**: Self-supervised Semantics Discovery, _et al._ 


# 🔥 News
- *2025.9*:  &nbsp;🎉🎉 1 first-author NeurIPS is accepted! 
- *2024.10*: &nbsp;✈️✈️ I will attend ACMMM conference in Melbourne in Oct. Looking forward to seeing old/new friends! 
- *2024.9*:  &nbsp;🎉🎉 1 NeurIPS(Spotlight) is accepted! 
- *2024.7*:  &nbsp;🎉🎉 1 first-author ACMMM is accepted! 


# 📝 Selected Projects

## 📦 Diffusion Transformers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ARXIV 2025, preprint</div><img src='images/paper_DG.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

<font size="3.5"><b>Massive Activations are the Key to Local Detail Synthesis in Diffusion Transformers</b></font>

<p style="margin: -1px 0;"><span style="font-weight: bold;"><u>Chaofan Gan</u></span>,<a>Zicheng Zhao</a>, <a href="https://yuanpengtu.github.io/" target="_blank">Yuanpeng Tu</a>, <a href="https://xavierchen34.github.io" target="_blank">Xi Chen</a>, <a href="https://scholar.google.com/citations?user=LdXFZScAAAAJ&hl=zh-CN&oi=ao" target="_blank">Ziran Qin</a>, <a href="https://scholar.google.com/citations?user=86n-wXsAAAAJ&hl=zh-CN" target="_blank">Tieyuan Chen</a>, <a href="https://scholar.google.com/citations?user=-24oYQoAAAAJ&hl=zh-CN&oi=ao" target="_blank">Yuxi Li</a>, <a href="https://sites.google.com/site/mehrtashharandi/" target="_blank">Mehrtash Harandi</a>, <a href="https://weiyaolin.github.io" target="_blank">Weiyao Lin</a></p>

<em>ARXIV 2025, preprint</em>

[**Arxiv**](http://arxiv.org/abs/2510.11538)|[**Project**](https://ganchaofan0000.github.io/project_dg/)|[**Github**](https://github.com/ganchaofan0000/DG)
- **Massive Activations Drive Fine-Grained Local Detail Synthesis in DiTs.** 
- **Detail Guidance: Superior Local Detail Fidelity Compared to CFG.** 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/paper_DiTF.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

<font size="3.5"><b>Unleashing Diffusion Transformers for Visual Correspondence by Modulating Massive Activations</b></font>

<p style="margin: -1px 0;"><span style="font-weight: bold;"><u>Chaofan Gan</u></span>, <a href="https://yuanpengtu.github.io/" target="_blank">Yuanpeng Tu</a>, <a href="https://xavierchen34.github.io" target="_blank">Xi Chen</a>, <a href="https://scholar.google.com/citations?user=86n-wXsAAAAJ&hl=zh-CN" target="_blank">Tieyuan Chen</a>, <a href="https://scholar.google.com/citations?user=-24oYQoAAAAJ&hl=zh-CN&oi=ao" target="_blank">Yuxi Li</a>, <a href="https://sites.google.com/site/mehrtashharandi/" target="_blank">Mehrtash Harandi</a>, <a href="https://weiyaolin.github.io" target="_blank">Weiyao Lin</a></p>

<em>Neural Information Processing Systems (<b>NeurIPS</b>), 2025</em>

[**Paper**](https://arxiv.org/pdf/2505.18584)| [**Github**](https://github.com/ganchaofan0000/DiTF)
- **Employ Diffusion Transformers as a feature extrator for visual correspondence!** 
</div>
</div>

## 🥑 Noise Learning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2025</div><img src='images/paper_dac.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

<font size="3.5"><b>DAC: 2D-3D Retrieval with Noisy Labels via Divide-and-Conquer Alignment and Correction</b></font>

<p style="margin: -1px 0;"><span style="font-weight: bold;"><u>Chaofan Gan</u></span>, <a href="https://yuanpengtu.github.io/" target="_blank">Yuanpeng Tu</a>, <a href="https://scholar.google.com/citations?user=-24oYQoAAAAJ&hl=zh-CN&oi=ao" target="_blank">Yuxi Li</a>, <a href="https://weiyaolin.github.io" target="_blank">Weiyao Lin</a></p>

<em>ACM International Conference on Multimedia (<b>ACMMM</b>), 2024</em>

[**Paper**](https://dl.acm.org/doi/abs/10.1145/3664647.3680859) |[**Arxiv**](https://arxiv.org/pdf/2407.17779) | [**Github**](https://github.com/ganchaofan0000/DAC)
- **Divide-and-Conquer stategy for 2D-3D multimodal noise learning!**
</div>
</div>


## 📺 Video Understanding

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024, Spotlight</div><img src='images/paper_mecd_teaser.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

<font size="3.5"><b>MECD: Unlocking Multi-Event Causal Discovery in Video Reasoning</b></font>

<p style="margin: -1px 0;"><a href="https://tychen-sjtu.github.io//" target="_blank">Tieyuan Chen*</a>, <a href="https://r00kie-liu.github.io" target="_blank">Huabin Liu*</a>, <a href="https://scholar.google.com/citations?hl=zh-CN&user=TTw8ZGcAAAAJ" target="_blank">Tianyao He</a>, <a href="https://yihangchen-ee.github.io/" target="_blank">Yihang Chen</a>, <span style="font-weight: bold;"><u>Chaofan Gan</u></span>, et. al</p>

<em>Neural Information Processing Systems (<b>NeurIPS</b>), <b><span style="color:#e74c3c">Spotlight</span></b>, 2024</em>

[**Arxiv**](https://arxiv.org/pdf/2409.17647) | [**Github**](https://github.com/tychen-SJTU/MECD-Benchmark)
</div>
</div>


# 🎓 Educations
- *2022.09 - present*, PhD Candidate (Joint), Information and Communication Engineering. Shanghai Jiao Tong University. 
- *2022.09 - present*, PhD Candidate (Joint), Electrical and Computer Systems Engineering. Monash University. 
- *2018.09 - 2022.06*, Undergraduate, Software Engineering. Huazhong University of Science and Technology.


# 📖 Publications
- <small>**<u>C. Gan</u>**, Y. Tu, X. Chen, T. Chen, Y. Li, M. Harandi, W. Lin, "Unleashing Diffusion Transformers for Visual Correspondence by Modulating Massive Activations", NeurIPS 2025.</small>
- <small>T. Chen, H. Liu, Y. Wang, Y. Chen, T. He, **<u>C. Gan</u>**, et al, "MECD+: Unlocking Event-Level Causal Graph Discovery for Video Reasoning", ARXIV 2025.</small>
- <small>G. Zou, **<u>C. Gan</u>**, CH. Lim, S. Aramvith, W. Lin, "MCA: 2D-3D Retrieval with Noisy Labels Via Multi-Level Adaptive Correction and Alignment", ICMEW 2025.</small>
- <small>T. Chen, H. Liu, T. He, Y. Chen, **<u>C. Gan</u>**, et al, "MECD: Unlocking Multi-Event Causal Discovery in Video Reasoning", NIPS 2024, Spotlight.</small>
- <small>**<u>C. Gan</u>**, Y. Tu, Y. Li, W. Lin, "DAC: 2D-3D Retrieval with Noisy Labels via Divide-and-Conquer Alignment and Correction", ACMMM 2024.</small>
