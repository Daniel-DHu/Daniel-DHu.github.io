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

I am currently a PhD student, candidate in the Department of Industrial and Systems Engineering (ISE) at The Hong Kong Polytechnic University (PolyU), studenting in the [Human-Oriented Intelligent Systems Lab (HOIS)](https://www.chaohuang.net/), and my supervisor is Dr. Chao Huang. 

In my research, I focus on the intersection between reinforcement learning (RL) and autonomous vehicles (AVs), with the aim of developing algorithms that can endow agent safer, more efficient and economical. In particular, my research interests include reinforcement learning algorithm, behavioral decision-making/planning of AVs, and data-driven energy management of electrified vehicles. 


# 💬 News
- *2025.05*: &nbsp;🎉🎉 Our paper on “Feariosity”-guided reinforcement learning has been accepted by IEEE RA-L!
- *2025.04*: &nbsp;🎉🎉 Congratulations on completing my PhD confirmation, and becoming a PhD candidate!
- *2024.11*: &nbsp;🎉🎉 Our paper on expert-guided EMS for electrified vehicles has been accepted by Applied Energy (APEN)!
- *2023.12*: &nbsp;🎉🎉 Our paper on Transfer-based reinforcement learning for energy management has been accepted by Energy!
- *2023.11*: &nbsp;🎉🎉 I have honored with the Best Student Paper Award at the conference [CEVVE](https://www.cevve.org/) held in Shenzhen, China. 
- *2023.09*: &nbsp;🎉🎉 I have joined PolyU and am about to embark on my PhD career. Wishing me a bright future!
- *2023.04*: &nbsp;🎉🎉 Our paper on apprenticeship-reinforcement learning for energy management has been accepted by Applied Energy (APEN)!
- *2021.10*: &nbsp;🎉🎉 We won the Silver Medal of 2021 China (Shenyang) intelligent connected automobile prospective application competition!
- *2021.06*: &nbsp;🎉🎉 We won the Gold Medal of 2021 World Intelligent Driving "HUAWEI MDC Cup" extreme challenge competition!

# 🔥 Highlights 

<div class='paper-box'><div class='paper-box-image'><img src='images/frame_FogRL.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">
[“Feariosity”-Guided Reinforcement Learning for Safe and Efficient Autonomous End-to-end Navigation](https://ieeexplore.ieee.org/abstract/document/11027413), **Dong Hu**, Longfei Mo, Jingda Wu, Chao Huang.
**IEEE Robotics and Automation Letters (RA-L), 2025**
-  Inspired by this scientific insight, we propose the “Feariosity” model, which integrates fear and curiosity model to simulate the complex psychological dynamics organisms experience during exploration. Based on this model, we also developed an innovative policy constraint and a new experience replay mechanism.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/EGRL.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">
[Enhancing data-driven energy management strategy via digital expert guidance for electrified vehicles](https://www.sciencedirect.com/science/article/pii/S0306261924025224), **Dong Hu**, Chao Huang, Jingda Wu etc.
**Applied Energy, 2025**
-  This study proposes a new energy management strategy framework that combines digital expert guidance.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/PTRL.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">
[Pre-trained Transformer-Enabled Strategies with Human-Guided Fine-Tuning for End-to-end Navigation of Autonomous Vehicles](https://arxiv.org/abs/2402.12666), **Dong Hu**, Chao Huang, Jingda Wu etc.
**Preprint, 2024**
-  This study proposes a new autonomous vehicle end-to-end training framework that combines pre-trained Transformers with human guided reinforcement learning fine-tuning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/TRL.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">
[A transfer-based reinforcement learning collaborative energy management strategy for extended-range electric buses with cabin temperature comfort consideration](https://www.sciencedirect.com/science/article/pii/S0360544223034916), **Dong Hu**, Chao Huang, etc.

**Energy, 2023**
-  We propose a collaborative energy management strategy for air conditioning and power systems based on transfer-based reinforcement learning framework.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/ARL.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[An apprenticeship and reinforcement learning scheme based on expert demonstrations for energy management strategy of hybrid electric vehicle](https://www.sciencedirect.com/science/article/pii/S0306261923005913), **Dong Hu**, Hui Xie, etc.

**Applied Energy, 2023**
-  We propose an apprenticeship-reinforcement learning (A-RL) framework based on expert demonstration model learned by domain adaptive meta-learning (DAML).
</div>
</div>




# 📝 Publications 
## Journal
- [“Feariosity”-Guided Reinforcement Learning for Safe and Efficient Autonomous End-to-end Navigation](https://ieeexplore.ieee.org/abstract/document/11027413), **Dong Hu**, Longfei Mo, Jingda Wu, Chao Huang. **IEEE Robotics and Automation Letters (RA-L), 2025**
  
- [Enhancing data-driven energy management strategy via digital expert guidance for electrified vehicles](https://www.sciencedirect.com/science/article/pii/S0306261924025224), **Dong Hu**, Chao Huang, Jingda Wu, Henglai Wei, Dawei Pi **Applied Energy, 2025**

- [A transfer-based reinforcement learning collaborative energy management strategy for extended-range electric buses with cabin temperature comfort consideration](https://www.sciencedirect.com/science/article/pii/S0360544223034916), **Dong Hu**, Chao Huang, Guodong Yin, Yangmin Li, Yue Huang, Hailong Huang, Jingda Wu, Wenfei Li, Hui Xie **Energy, 2023**

- [An apprenticeship and reinforcement learning scheme based on expert demonstrations for energy management strategy of hybrid electric vehicle](https://www.sciencedirect.com/science/article/pii/S0306261923005913), **Dong Hu**, Hui Xie, Kang Song, Yuanyuan Zhang, Long Yan, **Applied Energy, 2023**

- [Deep reinforcement learning based on driver experience embedding for energy management strategies in hybrid electric vehicles](https://onlinelibrary.wiley.com/doi/epdf/10.1002/ente.202200123), **Dong Hu**, Yuanyuan Zhang, **Energy Technology, 2022**

- [Effect of spherical-convex surface texture on tribological performance of water-lubricated bearing](https://www.sciencedirect.com/science/article/abs/pii/S0301679X19300751), **Dong Hu**, Zhiwei Guo, Xin Xie, Chengqing Yuan, **Tribology International, 2019**

- [A Novel Hydrophilic PVA Fiber Reinforced Thermoplastic Polyurethane Materials for Water-lubricated Stern Bearing](https://link.springer.com/article/10.1007/s12221-021-0013-2), **Dong Hu**, Zhiwei Guo, Tian Jun, Chengqing Yuan, **Fibers and Polymers, 2021**

## Conference
- Enhancing autonomous driving following motion decision-making through model-based policy optimization, **Dong Hu**, Zhipeng Shen, Chao Huang, Hailong Huang, **International Conference on Electric Vehicle and Vehicle Engineering (CEVVE 2023), 2023**

- An Iterative Optimization Algorithm for Vehicle Speed Prediction Considering Driving Style and Historical Data Effects, Hui Xie, **Dong Hu**, Kang Song, **40th Chinese Control Conference (CCC), 2021**

# 🎖 Honors and Awards
- 2021.10 China (Shenyang) Intelligent Connected Automobile Prospective Application competition, Silver Medal
- 2021.06 World Intelligent Driving "HUAWEI MDC Cup" Extreme Challenge competition, Gold Medal
- 2020.06 World Intelligent Driving Challenge competition, Excellence Award

# 📖 Educations
- *2023.09 - Today*, PhD, The Hong Kong Polytechnic University, Hong Kong, China
- *2020.09 - 2023.03*, Master of Engineering, Power mechanical engineering , Tianjin University, Tianjin, China
- *2016.09 - 2020.06*, Bachelor of Engineering, Marine Engineering, Wuhan University of technology, Wuhan, China

# 📚 Academic Services
*Journal Reviewer*
- IEEE Transactions on Intelligent Vehicles (T-IV)
- IEEE Transactions on Mobile Computing (T-MC)
- IEEE Transactions on Vehicular Technology (T-VT)
- IEEE Transactions on Automation Science and Engineering (T-ASE)
- Energy

*Conference Reviewer*
- IEEE Intelligent Transportation Systems Conference (ITSC) 2024 – 2025

