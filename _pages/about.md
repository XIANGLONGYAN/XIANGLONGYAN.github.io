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

Welcome to Xianglong Yan’s (闫相龙) personal website!

I am currently a third-year undergraduate student at [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/) (SJTU), majoring in Computer Science and Technology in the School of Computer Science at [Shanghai Jiao Tong University School of Computer Science](https://www.cs.sjtu.edu.cn/). I am advised by Prof. [Yulun Zhang](https://yulunzhang.com/).

My research focuses on efficient large language model (LLM) deployment, with particular emphasis on model compression and long-context inference. I am especially interested in post-training quantization (PTQ), low-bit quantization (e.g., binarization and ternarization), and KV cache compression, aiming to build accurate yet resource-efficient LLM systems that are practical for real-world deployment.

I am always open to collaborations and academic discussions. Feel free to reach out via email at yanxianglong@sjtu.edu.cn, or connect with me on WeChat (ID: yxlsds).


# 🔥 News
- *2026.01*: &nbsp;🎉🎉 Our paper PT²-LLM has been accepted to ICLR 2026!
- *2026.01*: &nbsp;🎉🎉 Our paper Quant-dLLM has been accepted to ICLR 2026!
- *2025.11*: &nbsp;🎉🎉 Our team was awarded the Grand Prize at the National “Challenge Cup” Competition (挑战杯全国特等奖)!
- *2025.01*: &nbsp;🎉🎉 Our paper ARB-LLM has been accepted to ICLR 2025!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/pt2-llm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PT²-LLM: Alternating Refined Binarizations for Large Language Models](https://arxiv.org/abs/2510.03267)

**<u>Xianglong Yan</u>**<sup>†</sup>, Chengzhu Bao<sup>†</sup>, Zhiteng Li, Tianao Zhang, Kaicheng Yang, Haotong Qin, Ruobing Xie, Xingwu Sun, Yulun Zhang<sup>*</sup>  

[**Code**](https://github.com/XIANGLONGYAN/PT2-LLM) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/arb-llm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ARB-LLM: Alternating Refined Binarizations for Large Language Models](https://arxiv.org/abs/2410.03129)

Zhiteng Li<sup>†</sup>, **<u>Xianglong Yan</u>**<sup>†</sup>, Tianao Zhang, Haotong Qin, Dong Xie, Jiang Tian, Zhongchao Shi, Linghe Kong<sup>*</sup>, Yulun Zhang<sup>*</sup>, Xiaokang Yang  

[**Code**](https://github.com/ZHITENGLI/ARB-LLM) 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/quant-dllm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Quant-dLLM: Post-Training Extreme Low-Bit Quantization for Diffusion Large Language Models](https://arxiv.org/abs/2510.03274)

Tianao Zhang<sup>†</sup>, Zhiteng Li<sup>†</sup>, **<u>Xianglong Yan</u>**, Haotong Qin, Yong Guo, Yulun Zhang<sup>*</sup>

[**Code**](https://github.com/ZTA2785/Quant-dLLM) 
</div>
</div>

# 🎖 Honors and Awards
- *2024.10*: National Scholarship (China; top national-level scholarship for undergraduate students)
- *2025.09*: National Natural Science Foundation of China (NSFC) Undergraduate Young Scientist Research Grant (RMB 100,000)
- *2025.11*: China International College Students’ Innovation Competition (“Challenge Cup”) — National Grand Prize (Team Leader)
- *2025.12*: SJTU Model Student (Outstanding Student Award; awarded annually to 10 students across the entire university)


# 📖 Education
- *2023.09 - now*, B.Eng. in Computer Science and Technology, [Shanghai Jiao Tong University (SJTU)](https://www.sjtu.edu.cn/), Shanghai, China.
- *2020.09 - 2023.06*, High School, [The Experimental High School Attached to Beijing Normal University](https://www.sdsz.com.cn/), Beijing, China.

# 🤝 Academic Service
- Reviewer, ECCV 2026
- Reviewer, ICML 2026
- Reviewer, ICLR 2026
- Reviewer, CVPR 2026
  
<!--
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
