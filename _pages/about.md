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

I am currently a master, candidate in the school of mechanical engineering at Tianjin University. I am working in the Intelligent Vehicle Research Center.

In my research, I focus on the intersection between autonomous driving / traffic flow and machine learning, with the aim of developing algorithms and techniques that can endow the interaction between traffic vehicles safer, more efficient and economical. In particular, my research interests include deep learning, reinforcement learning and game theory with the application to autonomous driving / traffic flow decision-making, prediction, planning, and energy efficiency optimization. 

**Skills:** Python (Sk-learn, Pytorch, Tensorflow), Matlab/Simulink, C/C++, Linux/ROS, IPG-CarMaker, SUMO

# 🔥 News
- *2022.04*: &nbsp;🎉🎉 Our paper on driving experience is embedded in reinforcement learning has been accepted by Energy Technology!
- *2021.10*: &nbsp;🎉🎉 We won the Silver Medal of 2021 China (Shenyang) intelligent connected automobile prospective application competition!
- *2021.06*: &nbsp;🎉🎉 We won the Gold Medal of 2021 World Intelligent Driving "HUAWEI MDC Cup" extreme challenge competition!
- *2021.06*: &nbsp;🎉🎉 Our paper on multi-scale fusion speed prediction accepted by 40th Chinese Control Conference (CCC)!

# 📝 Highlights 

<div class='paper-box'><div class='paper-box-image'><img src='images/ARL.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

An apprenticeship and reinforcement learning scheme based on expert demonstrations for energy management strategy of hybrid electric vehicle, **Dong Hu**, Hui Xie, etc.

**Applied Energy, submitted**
-  We propose an apprenticeship-reinforcement learning (A-RL) framework based on expert demonstration model learned by domain adaptive meta-learning (DAML).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/DE_RL.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

Deep reinforcement learning based on driver experience embedding for energy management strategies in hybrid electric vehicles, **Dong Hu**, Yuanyuan Zhang

**Energy Technology, 2022**
-  We propose an advanced driver experience (DE) model of traffic congestion level and power matching constructed based on fuzzy clustering, then embed it into DRL.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><img src='images/HJY_V2X.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

Vehicle-road-edge-cloud collaboration system in Tianjin Haihe Education Park

**Project:** Smart road and automatic driving
-  Edge computing, big data
-  Scene algorithm of vehicle road collaborative function
-  Federated learning, reinforcement learning, automl and privacy computing
-  Compression and optimization of deep learning model
</div>
</div>

# 📝 Publications 
## Journal
- [Deep reinforcement learning based on driver experience embedding for energy management strategies in hybrid electric vehicles](https://onlinelibrary.wiley.com/doi/epdf/10.1002/ente.202200123), **Dong Hu**, Yuanyuan Zhang, **Energy Technology, 2022**

- An apprenticeship and reinforcement learning scheme based on expert demonstrations for energy management strategy of hybrid electric vehicle, **Dong Hu**, Hui Xie, Kang Song, Yuanyuan Zhang, Long Yan, **Applied Energy, Submitted**

- [Effect of spherical-convex surface texture on tribological performance of water-lubricated bearing](https://www.sciencedirect.com/science/article/abs/pii/S0301679X19300751), **Dong Hu**, Zhiwei Guo, Xin Xie, Chengqing Yuan, **Tribology International, 2019**

- [A Novel Hydrophilic PVA Fiber Reinforced Thermoplastic Polyurethane Materials for Water-lubricated Stern Bearing](https://link.springer.com/article/10.1007/s12221-021-0013-2), **Dong Hu**, Zhiwei Guo, Tian Jun, Chengqing Yuan, **Fibers and Polymers, 2021**

## Conference
- An Iterative Optimization Algorithm for Vehicle Speed Prediction Considering Driving Style and Historical Data Effects, Hui Xie, **Dong Hu**, Kang Song, **40th Chinese Control Conference (CCC), 2021**

# 🎖 Honors and Awards
- 2021.10 China (Shenyang) Intelligent Connected Automobile Prospective Application competition, Silver Medal
- 2021.06 World Intelligent Driving "HUAWEI MDC Cup" Extreme Challenge competition, Gold Medal
- 2020.06 World Intelligent Driving Challenge competition, Excellence Award

# 📖 Educations
- *2020.09 - 2023.03*, Master of Engineering, Power mechanical engineering , Tianjin University, Tianjin, China
- *2016.09 - 2020.06*, Bachelor of Engineering, Marine Engineering, Wuhan University of technology, Wuhan, China

# 📚 Research Topics
- Driver modeling based on domain adaptive meta learning (DAML);
- HEV energy management based on deep reinforcement learning (DRL) and apprenticeship learning (AL);
- Torque distribution of four-driven EV based on DDPG;
- Speed planning of connected vehicles based on DDPG and PPO;
- Traffic signal planning based on DQN;
- Intersection speed planning based on MPC;
- Driving style recognition based on convolution recurrent network (CRNN); 
- Global speed prediction based on Gaussian process regression (GPR); 
- Instantaneous speed prediction based on long-term and short-term memory (LSTM) network; 
- Iterative fusion algorithm based on Markov chain.
