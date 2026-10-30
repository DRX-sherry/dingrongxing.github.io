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

I am currently a Ph.D. student at the School of Computer Science and Engineering, Nanjing University of Science and Technology, under the supervision of Prof. Xinguang Xiang and Prof. Xiangbo Shu. I am affiliated with the <a href="https://shuxb104.github.io/team/">Visual Intelligence and Multimedia (VIM)</a> and <a href="https://imag-njust.net/">Intelligent Media Analysis Group (IMAG)</a>.

My research interests primarily focus on **Computer Vision** and **Embodied AI**.

<!-- I am currently a Research Fellow at <a href='https://www.asintelligence.xyz/'>The Artificial Scientific Intelligence Lab (ASI Lab)</a> at the National University of Singapore, under the supervision of <a href='https://scholar.google.com/citations?user=kGSzBpMAAAAJ&hl=en'>Prof. Leo Dianbo Liu</a>. Before that, I received my Ph.D. from Nanjing University of Science and Technology, where I was affiliated with the <a href="https://shuxb104.github.io/team/">Visual Intelligence and Multimedia (VIM)</a> and <a href="https://imag-njust.net/">Intelligent Media Analysis Group (IMAG)</a> under the supervision of <a href='https://shuxb104.github.io/'>Prof. Xiangbo Shu</a>.

Previously, I was a visiting Ph.D. student at A*STAR and NUS for two years, working with <a href='https://cde.nus.edu.sg/ece/staff/shou-zheng-mike/'>Prof. Mike Z. Shou</a> and <a href='https://basurafernando.github.io/'>Dr. Basura</a>. -->
<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

📫 **Get in Touch / Collaborations**

I am open to exploring a wide range of topics with others. Please feel free to contact me via <a href="mailto:rxding4@gmail.com">Email</a>.

# 🔥 News

<!-- <div style="height: 250px; overflow-y: auto; border: 1px solid #eee; padding: 15px; border-radius: 8px; background-color: #f9f9f9; margin-bottom: 20px;">
  <ul style="list-style-type: none; margin-left: 0; line-height: 1.6;"> -->
  <div style="max-height: 120px; overflow-y: auto; padding: 10px;">
  <ul style="margin: 0; padding-left: 20px;">
    <li><b>2026-05-01</b>: 🎉🎉 GMPSSG is accepted by ICML 2026!</li>
    <li><b>2025-05-14</b>: 🎉🎉 One paper about Wireless Body Area Networks is accepted by IEEE TNSM!</li>
    <li><b>2024-07-22</b>: 🎉🎉 LSENet is accepted by IEEE GRSL!</li>
  </ul>
</div>

<!-- # 📝 Selected Publications (*co-first author) -->
<!-- <div id="selected-publications"></div>
# 📝 Selected Publications (*co-first author) -->
<span class='anchor' id='selected-publications'></span>
# 📝 Selected Publications (\* Equal Contribution, ✉ Corresponding Author)

## Spatial Intelligence

<div class='paper-box'>
  <div class='paper-box-image' style="flex: 0.3; min-width: 200px;">
    <div>
      <div class="badge">ICML 2026</div>
      <img src="{{ '/images/GMPSSG.png' | relative_url }}" alt="GMPSSG" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1" style="flex: 0.7; padding-left: 20px;">

[Learning Gaussian Mixture-distributed Prototypes for 3D Scene Graph Generation from RGB-D Sequences](https://openreview.net/pdf?id=PgcMxkhzoG)

Rongxing Ding\*, Hongyu Qu\*, Xinguang Xiang✉, Pengpeng Li and Xiangbo Shu✉

*Forty-third International Conference on Machine Learning* (**ICML**), 2026

<div>
<a href="https://openreview.net/pdf?id=PgcMxkhzoG"><strong>[pdf]</strong></a>
</div>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image' style="flex: 0.3; min-width: 200px;">
    <div>
      <div class="badge">Under Review</div>
      <img src="{{ '/images/HPSSG.png' | relative_url }}" alt="HPSSG" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1" style="flex: 0.7; padding-left: 20px;">

Hierarchical Prototype Learning for 3D Scene Graph Generation from RGB-D Sequences

Rongxing Ding

*Manuscript under review*, 2026

  </div>
</div>

## Embodied AI

<div class='paper-box'>
  <div class='paper-box-image' style="flex: 0.3; min-width: 200px;">
    <div>
      <div class="badge">arXiv 2026</div>
      <img src="{{ '/images/arxiv.png' | relative_url }}" alt="HiFOR" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1" style="flex: 0.7; padding-left: 20px;">

[HiFOR: Hierarchical Foresight with Action-Guided World Grounding for Vision-Language-Action Model](https://arxiv.org/pdf/2610.40373)

Rongxing Ding, Hongyu Qu, Kehong Wu, Xudong Wang, Fan Zhang, Xinguang Xiang and Xiangbo Shu

*arXiv preprint arXiv:2610.40373*, 2026

<div>
<a href="https://arxiv.org/pdf/2610.40373"><strong>[pdf]</strong></a>
</div>

  </div>
</div>

## Remote Sensing

<div class='paper-box'>
  <div class='paper-box-image' style="flex: 0.3; min-width: 200px;">
    <div>
      <div class="badge">IEEE GRSL 2024</div>
      <img src="{{ '/images/LSENet.png' | relative_url }}" alt="LSENet" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1" style="flex: 0.7; padding-left: 20px;">

[LSENet: Local and Spatial Enhancement to Improve the Semantic Segmentation of Remote Sensing Images](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10605831)

Rong-xing Ding, Yi-Han Xu✉, Jie Liu, Wen Zhou, and Chen Chen

*IEEE Geoscience and Remote Sensing Letters* (**IEEE GRSL**), 2024

<div>
<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10605831"><strong>[pdf]</strong></a>
</div>

  </div>
</div>


# 🎖 Honors and Awards

- **Second Prize**, 19th Graduate Mathematical Modeling Competition
- **First-Class Doctoral Scholarship**, 2026

# 🛎 Academic Service

**Journal Reviewer:**

- IEEE Geoscience and Remote Sensing Letters (GRSL)
- IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)

**Conference Reviewer:**

- International Conference on Machine Learning (ICML 2026)
