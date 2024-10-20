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

I am currently a joint Ph.D. candidate of **[Shanghai Jiao Tong University](https://www.sjtu.edu.cn)** and **[Monash University](https://www.monash.edu)** from [SEIEE](https://www.seiee.sjtu.edu.cn) since 2021, 
working with [Prof. Weiyao Lin](https://weiyaolin.github.io), [Prof. Jianfei Cai](https://jianfei-cai.github.io) and [Prof. Mehrtash Harandi](https://sites.google.com/site/mehrtashharandi/).
Before that, I spent 4 wonderful years studying at **[Dalian University of Technology](https://www.dlut.edu.cn)** as an undergraduate student since 2017 (top 5%).
My research interests include NeRF/3DGS compression, image/video compression and computer vision. Here is my [CV/Resume](https://yihangchen-ee.github.io/CV_Yihang_Chen.pdf).
I am also happy to share my good friend Qianyi Wu's fantastic works [here](https://qianyiwu.github.io).

If you are interested in my work, please contact me via *<yhchen.ee@sjtu.edu.cn>*.

# 🔥 News
- *2024*: &nbsp;🎉🎉 I will attend CVPR conference in Seattle in June. Looking forward to seeing old/new friends! 
- *2024*: &nbsp;🎉🎉 1 CVPR, 1 ACM TOMM, 1 ECCV, 1 NIPS are accepted! 

# 📝 Selected Projects

## 📦 Compression

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ARXIV 2024, preprint</div><img src='images/paper_fcgs_teaser.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

<font size="3.5"><b>Fast Feedforward 3D Gaussian Splatting Compression</b></font>

<p style="margin: -1px 0;"><span style="font-weight: bold;"><u>Yihang Chen</u></span>, <a href="https://qianyiwu.github.io" target="_blank">Qianyi Wu</a>, <a href="https://scholar.google.com/citations?user=fAIEYrEAAAAJ&hl=zh-CN&oi=ao" target="_blank">Mengyao Li</a>, <a href="https://weiyaolin.github.io" target="_blank">Weiyao Lin</a>, <a href="https://sites.google.com/site/mehrtashharandi/" target="_blank">Mehrtash Harandi</a>, <a href="http://jianfei-cai.github.io" target="_blank">Jianfei Cai</a></p>

[**Arxiv**](https://arxiv.org/pdf/2410.08017) | [**Project**](https://yihangchen-ee.github.io/project_fcgs/) | [**Github**](https://github.com/YihangChen-ee/FCGS)
- **Compress existing 3DGS rapidly in seconds without optimization!** 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/paper_hac_teaser.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

<font size="3.5"><b>HAC: Hash-grid Assisted Context for 3D Gaussian Splatting Compression</b></font>

<p style="margin: -1px 0;"><span style="font-weight: bold;"><u>Yihang Chen</u></span>, <a href="https://qianyiwu.github.io" target="_blank">Qianyi Wu</a>, <a href="https://weiyaolin.github.io" target="_blank">Weiyao Lin</a>, <a href="https://sites.google.com/site/mehrtashharandi/" target="_blank">Mehrtash Harandi</a>, <a href="http://jianfei-cai.github.io" target="_blank">Jianfei Cai</a></p>

[**Paper**](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01178.pdf) | [**Arxiv**](https://arxiv.org/pdf/2403.145301) | [**Project**](https://yihangchen-ee.github.io/project_hac/) | [**Github**](https://github.com/YihangChen-ee/HAC)
- **Compress 3D Gaussian Splatting for 75X without fidelity drop!** 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/paper_cnc_teaser.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

<font size="3.5"><b>How Far Can We Compress Instant-NGP-Based NeRF?</b></font>

<p style="margin: -1px 0;"><span style="font-weight: bold;"><u>Yihang Chen</u></span>, <a href="https://qianyiwu.github.io" target="_blank">Qianyi Wu</a>, <a href="https://sites.google.com/site/mehrtashharandi/" target="_blank">Mehrtash Harandi</a>, <a href="http://jianfei-cai.github.io" target="_blank">Jianfei Cai</a></p>

[**Paper**](https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_How_Far_Can_We_Compress_Instant-NGP-Based_NeRF_CVPR_2024_paper.pdf) | [**Arxiv**](https://arxiv.org/pdf/2406.04101) | [**Project**](https://yihangchen-ee.github.io/project_cnc/) | [**Github**](https://github.com/YihangChen-ee/CNC)
- **Significant compression ratio of 100X based on Instant-NGP!** 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM TOMM 2024</div><img src='images/paper_shizhan_teaser.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

<font size="3.5"><b>A Unified Framework for Jointly Compressing Visual and Semantic Data</b></font>

<p style="margin: -1px 0;"><a href="https://scholar.google.com/citations?user=LtTzNK4AAAAJ&hl=zh-CN&oi=ao" target="_blank">Shizhan Liu</a>, <a href="https://weiyaolin.github.io" target="_blank">Weiyao Lin</a>, <span style="font-weight: bold;"><u>Yihang Chen</u></span>, Yufeng Zhang, <a href="https://scholar.google.com/citations?user=Xg8MhyAAAAAJ&hl=zh-CN&oi=ao" target="_blank">Wenrui Dai</a>, <a href="https://johnsee.net" target="_blank">John See</a>, <a href="https://scholar.google.com/citations?user=bB16iN4AAAAJ&hl=zh-CN&oi=ao" target="_blank">Hongkai Xiong</a></p>

[**Paper**](https://dl.acm.org/doi/full/10.1145/3654800)
</div>
</div>

## 🧭 Other Fields

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NIPS 2024, Spotlight</div><img src='images/paper_mecd_teaser.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

<font size="3.5"><b>MECD: Unlocking Multi-Event Causal Discovery in Video Reasoning</b></font>

<p style="margin: -1px 0;"><a href="https://tychen-sjtu.github.io//" target="_blank">Tieyuan Chen*</a>, <a href="https://r00kie-liu.github.io" target="_blank">Huabin Liu*</a>, <a href="https://scholar.google.com/citations?hl=zh-CN&user=TTw8ZGcAAAAJ" target="_blank">Tianyao He</a>, <span style="font-weight: bold;"><u>Yihang Chen</u></span>, <a href="https://scholar.google.com/citations?hl=zh-CN&user=oOskImcAAAAJ" target="_blank">Chaofan Gan</a>, et. al</p>

[**Arxiv**](https://arxiv.org/pdf/2409.17647) | [**Github**](https://github.com/tychen-SJTU/MECD-Benchmark)
</div>
</div>


# 📖 Educations
- *2021.09 - present*, PhD Candidate (Joint), Information and Communication Engineering. Shanghai Jiao Tong University. 
- *2021.09 - present*, PhD Candidate (Joint), Electrical and Computer Systems Engineering. Monash University. 
- *2017.09 - 2021.06*, Undergraduate, Electronic Information Engineering (English Intensive). Dalian University of Technology.

# ✏️ Publications
 - <small>**<u>Y. Chen</u>**, Q. Wu, M. Li, W. Lin, M. Harandi, J. Cai, "Fast Feedforward 3D Gaussian Splatting Compression", ARXIV 2024, preprint.</small>
 - <small>T. Chen, H. Liu, T. He, **<u>Y. Chen</u>**, C. Gan, et al, "MECD: Unlocking Multi-Event Causal Discovery in Video Reasoning", NIPS 2024, Spotlight.</small>
 - <small>**<u>Y. Chen</u>**, Q. Wu, W. Lin, M. Harandi, J. Cai, "HAC: Hash-grid Assisted Context for 3D Gaussian Splatting Compression", ECCV 2024.</small>
 - <small>**<u>Y. Chen</u>**, Q. Wu, M. Harandi, J. Cai, "How Far Can We Compress Instant-NGP-Based NeRF?", CVPR 2024.</small>
 - <small>Z. Xie, Z. Ni, W. Yang, Yuang Zhang, **<u>Y. Chen</u>**, Yang Zhang, X. Ma, "A Robust Online Multi-Camera People Tracking System With Geometric Consistency and State-aware Re-ID Correction", CVPR workshop 2024.</small>
 - <small>S. Liu, W. Lin, **<u>Y. Chen</u>**, Y. Zhang, W. Dai, J. See, H. Xiong, "A Unified Framework for Jointly Compressing Visual and Semantic Data", ACM Trans. Multimedia Computing, Communications, and Applications, 2024.</small>
 - <small>**<u>Y. Chen</u>**, W. Dong, Y. Xie, "A dual realization of Chua’s chaotic oscillator using a current-controlled nonlinear resistor." 2021 IEEE 3rd International Conference on Circuits and Systems (ICCS). IEEE, 2021. [[Paper](https://ieeexplore.ieee.org/abstract/document/9697183)] (*This is my very first published paper. Most sincere appreciations to [Prof. Weijie Dong](http://faculty.dlut.edu.cn/0912345/zh_CN/index.htm)*'s guidance to this paper.)</small>
