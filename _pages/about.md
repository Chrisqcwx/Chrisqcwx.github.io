---
permalink: /
title: 
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


Hongyao Yu is a Master student in Computer Science at [Tsinghua University](https://www.tsinghua.edu.cn/), under the mentorship of Prof. [Shu-Tao Xia](https://www.sigs.tsinghua.edu.cn/xst/main.htm). He works closely with Prof. [Bin Chen](https://faculty.hitsz.edu.cn/BinChen). Before that, He completed undergraduate studies in Computer Science and Technology at [Harbin Institute of Technology, Shenzhen](https://www.hitsz.edu.cn/). He has published articles on training data detection and trustworthy AI. His research interests generally include trustworthy AI, machine learning and data privacy. He has also served as a reviewer for top-tier conferences, such as ICLR and ACM CSUR.

My research interests focus on:

- Diffusion Large Language Models
- Multimodal Large Language Models
- Training Data Detection
- Trustworthy AI


## 📧 Concat

email: chrisqcwx@gmail.com

<!-- ## 🔥 News
- *2025.05*: &nbsp;🎉🎉 Two papers are accepted by ICML 2025!
- *2024.12*: &nbsp;🎉🎉 One paper is accepted by AAAI 2025! -->

## 📝 Publications

Notes:（*）indicates the equal contributions.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGKDD, 2026</div><img src='images/loft.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Rank Matters: Understanding and Defending Model Inversion
Attacks via Low-Rank Feature Filtering

**Hongyao Yu**, Yixiang Qiu, Hao Fang, Tianqu Zhuang, Bin Chen, Sijin Yu, Bin Wang, Shu-Tao Xia and Ke Xu

[ **Paper**](https://dl.acm.org/doi/pdf/10.1145/3770854.3780328)   [**Code**](https://github.com/Chrisqcwx/LoFt)  

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGKDD, 2026</div><img src='images/3dgs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

GaussTrap: Stealthy Poisoning Attacks on 3D Gaussian Splatting
for Targeted Scene Confusion

Jiaxin Hong\*, Sixu Chen\*, Shuoyang Sun\*, **Hongyao Yu**\*, Hao Fang, Yuqi Tan, Bin Chen, Shuhan Qi and Shu-Tao Xia

[ **Paper**](https://arxiv.org/pdf/2504.20829)   

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL, 2026</div><img src='images/badrdm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Retrievals Can Be Detrimental: Unveiling the Backdoor Vulnerability of
Retrieval-Augmented Diffusion Models

Hao Fang\*, Xiaohang Sui\*, **Hongyao Yu**\*, Kuofeng Gao, Jiawei Kong, Sijin Yu, Bin Chen and Shu-Tao Xia

[ **Paper**](https://arxiv.org/pdf/2501.13340)   [**Code**](https://github.com/ffhibnese/BadRDM_Backdoor_RAG_diffusion_models)  

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL, 2026</div><img src='images/cred.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">



Chenxi Qing, Jinxi Wu, Zheng Liu, Yixiang Qiu, **Hongyao Yu**, Bin Chen, Hao Wu and Shu-Tao Xia

[ **Paper**](https://arxiv.org/pdf/2604.11796)   

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM, 2025</div><img src='images/ICAS.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

ICAS: Detecting Training Data from Autoregressive Image Generative Models

**Hongyao Yu**, Yixiang Qiu, Yiheng Yang, Hao Fang, Tianqu Zhuang, Jiaxin Hong, Bin Chen, Hao Wu, and Shu-Tao Xia

[ **Paper**](https://arxiv.org/abs/2507.05068)   [**Code**](https://github.com/Chrisqcwx/ImageAR-MIA)  ![Stars](https://img.shields.io/github/stars/Chrisqcwx/ImageAR-MIA)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR, 2025</div>
<img src='images/ssd.png' alt="sym" width="100%">
</div></div>
<div class='paper-box-text' markdown="1">

Stealthy Shield Defense: A Conditional Mutual Information-Based Approach against Black-Box Model Inversion Attacks

Tianqu Zhuang\*, **Hongyao Yu**\*, Yixiang Qiu\*, Hao Fang\*, Bin Chen, Shu-Tao Xia

[ **Paper**](https://openreview.net/pdf?id=p0DjhjPXl3)   [**Code**](https://github.com/ZhuangQu/Stealthy-Shield-Defense)  ![Stars](https://img.shields.io/github/stars/ZhuangQu/Stealthy-Shield-Defense)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV, 2024 (oral)</div><img src='images/ifgmi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

A Closer Look at GAN Priors: Exploiting Intermediate Features for Enhanced Model Inversion Attacks

Yixiang Qiu\*, Hao Fang\*, **Hongyao Yu**\*, Bin Chen, MeiKang Qiu, Shu-Tao Xia

[ **Paper**](https://arxiv.org/pdf/2407.13863)   [**Code**](https://github.com/final-solution/IF-GMI)  ![Stars](https://img.shields.io/github/stars/final-solution/IF-GMI)

</div>
</div>

<!-- ## 🖨️ PrePrint -->



## 📖 Educations

- *2025.09 - 2028.07 (expected)*, MSc in Computer Science, ![](images/tsinghua.png) **Tsinghua University**
- *2021.09 - 2025.06*, Bachelor in Computer Science and Technology, **Harbin Institute of Technology, Shenzhen**




## 🏆 Awards

+ Chinese National Scholarship for Undergraduate Students × 2 (2022, 2024)
+ Top Ten Academic Excellence Stars of Harbin Institute of Technology (2024)
+ First class scholarship × 3 (2022, 2023, 2024)
+ National Second Prize in the China Undergraduate Mathematical Contest in Modeling (2023)
+ National Third Prize in the National Student Computer System Capability Challenge (NSCSCC) (2023)
+ Provincial First Prize in the China Undergraduate Mathematical Contest in Modeling (2022)

# 📝 Services

+ Reviewer for ICLR 2025, 2026 and ACM CSUR.