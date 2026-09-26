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

I am currently a fourth-year undergraduate student at [Shanghai Jiao Tong University](https://www.sjtu.edu.cn/) (SJTU), majoring in Computer Science and Technology at the [School of Computer Science, SJTU](https://www.cs.sjtu.edu.cn/). I am advised by Prof. [Yulun Zhang](https://yulunzhang.com/).

My research focuses on efficient large language model (LLM) deployment, with particular emphasis on model compression and long-context inference. I am especially interested in post-training quantization (PTQ), low-bit quantization (e.g., binarization and ternarization), and KV cache compression, aiming to build accurate yet resource-efficient LLM systems that are practical for real-world deployment.

I am always open to collaborations and academic discussions. Feel free to reach out via email at yanxianglong@sjtu.edu.cn, or connect with me on WeChat (ID: yxlsds).


# 🔥 News
- *2026.09*: &nbsp;🎉🎉 Our paper [D²Quant](https://arxiv.org/abs/2602.02546) has been accepted to NeurIPS 2026!
- *2026.09*: &nbsp;🎉🎉 I was awarded the SenseTime Scholarship (30 recipients nationwide each year)!
- *2026.03*: &nbsp;🎉🎉 We released [Awesome Visual Autoregressive Modeling](https://github.com/XIANGLONGYAN/Awesome-Visual-Autoregressive-Modeling), a curated list of 60+ papers on the VAR paradigm!
- *2026.01*: &nbsp;🎉🎉 Our papers PT²-LLM and Quant-dLLM have been accepted to ICLR 2026!
- *2025.11*: &nbsp;🎉🎉 Our team was awarded the Grand Prize at the National “Challenge Cup” Competition (挑战杯全国特等奖)!
- *2025.01*: &nbsp;🎉🎉 Our paper ARB-LLM has been accepted to ICLR 2025!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026</div><img src='images/d2quant.png' alt="D²Quant framework" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[D²Quant: Accurate Low-bit Post-Training Weight Quantization for LLMs](https://arxiv.org/abs/2602.02546)

**<u>Xianglong Yan</u>**, Chengzhu Bao, Zhiteng Li, Tianao Zhang, Shaoqiu Zhang, Ruobing Xie, Xingwu Sun, Yulun Zhang

[**Code**](https://github.com/XIANGLONGYAN/D2Quant)

- **TL;DR**: Dual-scale quantization and deviation-aware correction improve sub-4-bit weight-only post-training quantization for LLMs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/pt2-llm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PT²-LLM: Post-Training Ternarization for Large Language Models](https://arxiv.org/abs/2510.03267)

**<u>Xianglong Yan</u>**<sup>†</sup>, Chengzhu Bao<sup>†</sup>, Zhiteng Li, Tianao Zhang, Kaicheng Yang, Haotong Qin, Ruobing Xie, Xingwu Sun, Yulun Zhang<sup>*</sup>  

[**Code**](https://github.com/XIANGLONGYAN/PT2-LLM)

- **TL;DR**: An efficient post-training ternarization framework for LLMs, incorporating an asymmetric ternary quantizer and column rearrangement strategy.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/arb-llm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ARB-LLM: Alternating Refined Binarizations for Large Language Models](https://arxiv.org/abs/2410.03129)

Zhiteng Li<sup>†</sup>, **<u>Xianglong Yan</u>**<sup>†</sup>, Tianao Zhang, Haotong Qin, Dong Xie, Jiang Tian, Zhongchao Shi, Linghe Kong<sup>*</sup>, Yulun Zhang<sup>*</sup>, Xiaokang Yang

[**Code**](https://github.com/ZHITENGLI/ARB-LLM)

- **TL;DR**: Proposes alternating refined binarization for LLMs, surpassing FP16 models on the Pareto curve.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/quant-dllm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Quant-dLLM: Post-Training Extreme Low-Bit Quantization for Diffusion Large Language Models](https://arxiv.org/abs/2510.03274)

Tianao Zhang<sup>†</sup>, Zhiteng Li<sup>†</sup>, **<u>Xianglong Yan</u>**, Haotong Qin, Yong Guo, Yulun Zhang<sup>*</sup>

[**Code**](https://github.com/ZTA2785/Quant-dLLM)

- **TL;DR**: The first work to explore low-bit quantization for diffusion LLMs, achieving SOTA performance at 2-bit.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/robuq.png' alt="RobuQ framework" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RobuQ: Pushing DiTs to W1.58A2 via Robust Activation Quantization](https://arxiv.org/abs/2509.23582)

Kaicheng Yang, Xun Zhang, Haotong Qin, Yucheng Lin, Kaisen Yang, **<u>Xianglong Yan</u>**, Yulun Zhang

[**Code**](https://github.com/racoonykc/RobuQ)

- **TL;DR**: Robust activation quantization and mixed precision enable diffusion transformers with ternary weights and near 2-bit activations.
</div>
</div>

# 🎖 Honors and Awards
- *2024.10*: National Scholarship, China (Top 0.2%)
- *2026.09*: SenseTime Scholarship (30 recipients nationwide each year)
- *2025.09*: NSFC Undergraduate Young Scientist Research Grant
- *2025.11*: National Grand Prize, “Challenge Cup” Competition (Team Leader)
- *2025.12*: SJTU Model Student (Top 10 university-wide, 2025)


# 💼 Internships
- *2026.03 - 2026.09*, Intern, Model Acceleration Group, Hunyuan.

# 📖 Educations
- *2023.09 - now*, B.Eng. in Computer Science and Technology, [Shanghai Jiao Tong University (SJTU)](https://www.sjtu.edu.cn/), Shanghai, China.
- *2020.09 - 2023.06*, High School, [The Experimental High School Attached to Beijing Normal University](https://www.sdsz.com.cn/), Beijing, China.

# 🤝 Academic Service
- Reviewer, ICLR 2026
- Reviewer, NeurIPS 2026
- Reviewer, ICLR 2027
