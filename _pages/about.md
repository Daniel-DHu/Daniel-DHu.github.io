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

I’m currently a PhD candidate in the Department of Industrial and Systems Engineering (ISE) at The Hong Kong Polytechnic University (PolyU), where I hang out in the [Human-Oriented Intelligent Systems Lab (HOIS)](https://www.chaohuang.net/) under the wise (and patient) guidance of Dr. Chao Huang. 

My research lives at the crossroads of reinforcement learning (RL) and autonomous vehicles (AVs)—think of it as teaching cars to be smarter, safer, and thriftier, all without needing coffee breaks. Specifically, I’m diving into RL, motion planning for AVs (because nobody likes a car that hesitates at intersections), and energy management for electrified vehicles (saving watts like a pro).


# 💬 News
- *2025.09*: &nbsp;🎉🎉 Our paper on Uncertainty-driven active RL for EMS has been accepted by IEEE T-TE!
- *2025.07*: &nbsp;🎉🎉 Our paper on Human-in-the-loop adversarial RL with diffusion policy has been accepted by IEEE T-ITS!
- *2025.07*: &nbsp;🎉🎉 Our paper on Adaptative rollout model-based policy optimization has been accepted by IEEE T-TE!
- *2025.07*: &nbsp;🎉🎉 Our paper on Trust-calibrated human-in-the-loop reinforcement learning has been accepted by IEEE IOT-J!
- *2025.07*: &nbsp;🎉🎉 Our paper about Generalizing navigation has been accepted by ITSC 2025, See you on the Gold Coast!
- *2025.05*: &nbsp;🎉🎉 Our paper on “Feariosity”-guided reinforcement learning has been accepted by IEEE RA-L!
- *2025.04*: &nbsp;🎉🎉 Congratulations on completing my PhD confirmation, and becoming a PhD candidate!
- *2024.11*: &nbsp;🎉🎉 Our paper on expert-guided EMS for electrified vehicles has been accepted by Applied Energy (APEN)!
- *2023.12*: &nbsp;🎉🎉 Our paper on Transfer-based reinforcement learning for energy management has been accepted by Energy!
- *2023.11*: &nbsp;🎉🎉 I have honored with the Best Student Paper Award at the conference [CEVVE](https://www.cevve.org/) held in Shenzhen, China. 
- *2023.09*: &nbsp;🎉🎉 I have joined PolyU and am about to embark on my PhD career. Wishing me a bright future!
- *2023.04*: &nbsp;🎉🎉 Our paper on Apprenticeship-reinforcement learning for EMS has been accepted by Applied Energy (APEN)!


# 🔥 Highlights 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-ITS'25</div><img src='images/frame_HardP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Towards Multi-Task Generalization in Autonomous Navigation: a Human-in-the-Loop Adversarial Reinforcement Learning with Diffusion Policy](https://ieeexplore.ieee.org/document/11106367), **Dong Hu**, Chao Huang, Jingda Wu and Xin Yuan.
**IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2025**
-  A novel human-in-the-loop adversarial RL with diffusion policy (Hard-P) is proposed. Training Diffusion models in online RL can be unstable and sample-inefficient. To address this, human guidance is incorporated into the learning process, effectively stabilizing policy updates and accelerating convergence. In addition, adversarial training is introduced to enhance robustness and adaptability across dynamic, multi-task environments.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-TE'25</div><img src='images/frame_MBPO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Autonomous Driving Economic Car-following Motion Strategy based on Adaptive Rollout Model-based Policy Optimization](https://ieeexplore.ieee.org/document/11083629), **Dong Hu**, Chao Huang, Jing Zhao, Yifan Zhao and Jingda Wu.
**IEEE Transactions on Transportation Electrification (T-TE), 2025**
-  We propose an adaptive rollout model-based policy optimization (AR-MBPO) algorithm tailored for car-following motion planning in autonomous electric vehicles. The algorithm improves overall performance by incorporating a error-aware ensemble environment model and leveraging branched rollouts for efficient sample collection and policy optimization.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IOTJ'25</div><img src='images/frame_TCHIL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Trust-Calibrated Human-in-the-Loop Reinforcement Learning for Safe and Efficient Autonomous Navigation](https://ieeexplore.ieee.org/document/11079651), **Dong Hu**, Guanzhong Zhou, Jingda Wu, Chao Huang.
**IEEE Internet of Things Journal (IOT-J), 2025**
-  Human-in-the-loop (HIL) guidance has been shown to be effective in improving the performance of RL algorithms. Existing methods in this field often assume that human guidance is always beneficial. However, incorrect guidance can cause oscillations or even divergences in training. We propose an innovative trust-calibrated HIL-RL approach to address these gaps. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L'25</div><img src='images/frame_FogRL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[“Feariosity”-Guided Reinforcement Learning for Safe and Efficient Autonomous End-to-end Navigation](https://ieeexplore.ieee.org/abstract/document/11027413), **Dong Hu**, Longfei Mo, Jingda Wu, Chao Huang.
**IEEE Robotics and Automation Letters (RA-L), 2025**
-  Inspired by this scientific insight, we propose the “Feariosity” model, which integrates fear and curiosity model to simulate the complex psychological dynamics organisms experience during exploration. Based on this model, we also developed an innovative policy constraint and a new experience replay mechanism.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">APEN'25</div><img src='images/EGRL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Enhancing data-driven energy management strategy via digital expert guidance for electrified vehicles](https://www.sciencedirect.com/science/article/pii/S0306261924025224), **Dong Hu**, Chao Huang, Jingda Wu etc.
**Applied Energy, 2025**
-  This study proposes a new energy management strategy framework that combines digital expert guidance.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EGY'24</div><img src='images/TRL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[A transfer-based reinforcement learning collaborative energy management strategy for extended-range electric buses with cabin temperature comfort consideration](https://www.sciencedirect.com/science/article/pii/S0360544223034916), **Dong Hu**, Chao Huang, etc.

**Energy, 2023**
-  We propose a collaborative energy management strategy for air conditioning and power systems based on transfer-based reinforcement learning framework.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">APEN'23</div><img src='images/ARL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An apprenticeship and reinforcement learning scheme based on expert demonstrations for energy management strategy of hybrid electric vehicle](https://www.sciencedirect.com/science/article/pii/S0306261923005913), **Dong Hu**, Hui Xie, etc.

**Applied Energy, 2023**
-  We propose an apprenticeship-reinforcement learning (A-RL) framework based on expert demonstration model learned by domain adaptive meta-learning (DAML).
</div>
</div>




# 📝 Publications 
## Journal

- [Towards Multi-Task Generalization in Autonomous Navigation: a Human-in-the-Loop Adversarial Reinforcement Learning with Diffusion Policy](https://ieeexplore.ieee.org/document/11106367), **Dong Hu**, Chao Huang, Jingda Wu and Xin Yuan. **IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2025**
-  [Autonomous Driving Economic Car-following Motion Strategy based on Adaptive Rollout Model-based Policy Optimization](https://ieeexplore.ieee.org/document/11083629), **Dong Hu**, Chao Huang, Jing Zhao, Yifan Zhao and Jingda Wu. **IEEE Transactions on Transportation Electrification (T-TE), 2025**
- [Trust-Calibrated Human-in-the-Loop Reinforcement Learning for Safe and Efficient Autonomous Navigation](https://ieeexplore.ieee.org/document/11079651), **Dong Hu**, Guanzhong Zhou, Jingda Wu, Chao Huang. **IEEE Internet of Things Journal (IOT-J), 2025**
- [“Feariosity”-Guided Reinforcement Learning for Safe and Efficient Autonomous End-to-end Navigation](https://ieeexplore.ieee.org/abstract/document/11027413), **Dong Hu**, Longfei Mo, Jingda Wu, Chao Huang. **IEEE Robotics and Automation Letters (RA-L), 2025**
- [Uncertainty-driven Active Reinforcement Learning for Energy Management Strategy in Electrified Vehicles](https://ieeexplore.ieee.org/abstract/document/11180060), **Dong Hu**, Cheng Tian, Anh-Tu Nguyen, Chao Huang **IEEE Transactions on Transportation Electrification (T-TE), 2025**
- [Enhancing Data-driven Energy Management Strategy via Digital Expert Guidance for Electrified Vehicles](https://www.sciencedirect.com/science/article/pii/S0306261924025224), **Dong Hu**, Chao Huang, Jingda Wu, Henglai Wei, Dawei Pi **Applied Energy, 2025**
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
- Applied Energy
- Energy

*Conference Reviewer*
- IEEE Intelligent Transportation Systems Conference (ITSC) 2024 – 2025

