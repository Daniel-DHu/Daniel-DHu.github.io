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

🎓 I received my Ph.D. from the Department of Industrial and Systems Engineering at The Hong Kong Polytechnic University, under the supervision of Dr. [Chao Huang](https://www.chaohuang.net/). I also visited the Robot Perception and Learning Lab at University College London, where I worked with Prof. [Dimitrios Kanoulas](https://dkanou.github.io/).

🤖 My research lies at the intersection of robotics, physical AI, and autonomous systems. I aim to build embodied agents that can perceive, reason, learn, and act efficiently in complex physical environments.

🧠 I am particularly interested in enabling autonomous agents to develop self-awareness, self-reflection, deliberative reasoning, active learning, and continual improvement capabilities, so that they can better understand their own capabilities and limitations.

🌍 I also study efficient long-horizon world models that allow agents to simulate future scenarios, reason over extended time horizons, and anticipate potential risks beyond their immediate sensing range.

📚 More broadly, I investigate efficient and adaptive learning methods that enable robots to rapidly adapt with limited supervision, learn from human feedback and demonstrations, and improve through real-world interaction.

🚗 My research covers **mobile robots**, **autonomous driving**, and **low-altitude aerial vehicles**, with a focus on robot navigation, efficient decision-making, and motion planning in complex, dynamic, and safety-critical environments.


# 💬 News
- *2026.10*: &nbsp;🎉🎉 Our paper on Game-Theoretic Risk-Shaped RL has been accepted by IEEE T-NNLS!
- *2026.09*: &nbsp;🎓🎓 I have completed my PhD oral defense. Wishing me a bright future!
- *2025.09*: &nbsp;🎉🎉 Our paper on Uncertainty-driven active RL for EMS has been accepted by IEEE T-TE!
- *2025.07*: &nbsp;🎉🎉 Our paper on Human-in-the-loop adversarial RL with diffusion policy has been accepted by IEEE T-ITS!
- *2025.07*: &nbsp;🎉🎉 Our paper on Adaptive rollout model-based policy optimization has been accepted by IEEE T-TE!
- *2025.07*: &nbsp;🎉🎉 Our paper on Trust-calibrated human-in-the-loop RL has been accepted by IEEE IOT-J!
- *2025.07*: &nbsp;🎉🎉 Our paper about Generalizing navigation has been accepted by ITSC 2025, See you on the Gold Coast!
- *2025.05*: &nbsp;🎉🎉 Our paper on “Feariosity”-guided reinforcement learning has been accepted by IEEE RA-L!
- *2025.04*: &nbsp;🎓🎓 Congratulations on completing my PhD confirmation, and becoming a PhD candidate!



# 🔥 Highlights 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv'26</div><img src='images/SAGE.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Self-Aware Active Learning Enables Continual Improvement in Autonomous Driving](https://arxiv.org/abs/2608.29772), **Dong Hu**, Chao Huang, Carman K.M. Lee and Dimitrios Kanoulas.
**Preprint**
- We present a self-aware guided exploration (SAGE) active learning framework for post-training adaptation of autonomous driving systems. SAGE learns a predictive world model to produce two intrinsic signals: fear for short-horizon risk and uncertainty, and curiosity for novelty. Curiosity adaptively calibrates the fear threshold to trigger expert takeover, and high-value takeover trajectories are reused for targeted imitation learning, mitigating long-tail failures and enabling closed-loop continual improvement.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TNNLS'26</div><img src='images/GTR2L.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Game-Theoretic Risk-Shaped Reinforcement Learning for Safe Autonomous Driving](https://arxiv.org/abs/2510.10960), **Dong Hu**, Fenqing Hu, Lidong Yang and Chao Huang.
**IEEE Transactions on Neural Networks and Learning Systems (T-NNLS), 2026 (Accepted)**
<a href="https://github.com/Daniel-DHu/GTR2L" target="_blank" class="btn paper-btn">
  <i class="fab fa-github"></i> Code
</a>
- A game-theoretic risk-shaped RL (GTRL2) framework is proposed for safe autonomous driving. It builds a multi-level game-theoretic world model to predict interactive vehicle behaviors and associated risks, with an adaptive rollout horizon adjusted by prediction uncertainty. An uncertainty-aware barrier mechanism flexibly regulates safety boundaries, explicitly modeling both epistemic and aleatory uncertainty for constrained policy optimization. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-ITS'25</div><img src='images/frame_HardP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Towards Multi-Task Generalization in Autonomous Navigation: a Human-in-the-Loop Adversarial Reinforcement Learning with Diffusion Policy](https://ieeexplore.ieee.org/document/11106367), **Dong Hu**, Chao Huang, Jingda Wu and Xin Yuan.
**IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2025**
-  A novel human-in-the-loop adversarial RL with diffusion policy (Hard-P) is proposed. Training Diffusion models in online RL can be unstable and sample-inefficient. To address this, human guidance is incorporated into the learning process, effectively stabilizing policy updates and accelerating convergence. In addition, adversarial training is introduced to enhance robustness and adaptability across dynamic, multi-task environments.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L'25</div><img src='images/FogRL.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[“Feariosity”-Guided Reinforcement Learning for Safe and Efficient Autonomous End-to-end Navigation](https://ieeexplore.ieee.org/abstract/document/11027413), **Dong Hu**, Longfei Mo, Jingda Wu, Chao Huang.
**IEEE Robotics and Automation Letters (RA-L), 2025**
-  Inspired by this scientific insight, we propose the “Feariosity” model, which integrates fear and curiosity model to simulate the complex psychological dynamics organisms experience during exploration. Based on this model, we also developed an innovative policy constraint and a new experience replay mechanism.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IOTJ'25</div><img src='images/frame_TCHIL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Trust-Calibrated Human-in-the-Loop Reinforcement Learning for Safe and Efficient Autonomous Navigation](https://ieeexplore.ieee.org/document/11079651), **Dong Hu**, Guanzhong Zhou, Jingda Wu, Chao Huang.
**IEEE Internet of Things Journal (IOT-J), 2025**
-  Human-in-the-loop (HIL) guidance has been shown to be effective in improving the performance of RL algorithms. Existing methods in this field often assume that human guidance is always beneficial. However, incorrect guidance can cause oscillations or even divergences in training. We propose an innovative trust-calibrated HIL-RL approach to address these gaps. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-TE'25</div><img src='images/frame_MBPO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Autonomous Driving Economic Car-following Motion Strategy based on Adaptive Rollout Model-based Policy Optimization](https://ieeexplore.ieee.org/document/11083629), **Dong Hu**, Chao Huang, Jing Zhao, Yifan Zhao and Jingda Wu.
**IEEE Transactions on Transportation Electrification (T-TE), 2025**
<a href="https://github.com/Daniel-DHu/RL-Eco-follower" target="_blank" class="btn paper-btn">
  <i class="fab fa-github"></i> Code
</a>
-  We propose an adaptive rollout model-based policy optimization (AR-MBPO) algorithm tailored for car-following motion planning in autonomous electric vehicles. The algorithm improves overall performance by incorporating ans error-aware ensemble environment model and leveraging branched rollouts for efficient sample collection and policy optimization.
</div>
</div>


# 📝 Publications 
## Journal

- [Game-Theoretic Risk-Shaped Reinforcement Learning for Safe Autonomous Driving](https://arxiv.org/abs/2510.10960), **Dong Hu**, Fenqing Hu, Lidong Yang and Chao Huang.
**IEEE Transactions on Neural Networks and Learning Systems (T-NNLS), 2026**
- [Towards Multi-Task Generalization in Autonomous Navigation: a Human-in-the-Loop Adversarial Reinforcement Learning with Diffusion Policy](https://ieeexplore.ieee.org/document/11106367), **Dong Hu**, Chao Huang, Jingda Wu and Xin Yuan. **IEEE Transactions on Intelligent Transportation Systems (T-ITS), 2025**
-  [Autonomous Driving Economic Car-following Motion Strategy based on Adaptive Rollout Model-based Policy Optimization](https://ieeexplore.ieee.org/document/11083629), **Dong Hu**, Chao Huang, Jing Zhao, Yifan Zhao and Jingda Wu. **IEEE Transactions on Transportation Electrification (T-TE), 2025**
- [Trust-Calibrated Human-in-the-Loop Reinforcement Learning for Safe and Efficient Autonomous Navigation](https://ieeexplore.ieee.org/document/11079651), **Dong Hu**, Guanzhong Zhou, Jingda Wu, Chao Huang. **IEEE Internet of Things Journal (IOT-J), 2025**
- [“Feariosity”-Guided Reinforcement Learning for Safe and Efficient Autonomous End-to-end Navigation](https://ieeexplore.ieee.org/abstract/document/11027413), **Dong Hu**, Longfei Mo, Jingda Wu, Chao Huang. **IEEE Robotics and Automation Letters (RA-L), 2025**
- [Uncertainty-driven Active Reinforcement Learning for Energy Management Strategy in Electrified Vehicles](https://ieeexplore.ieee.org/abstract/document/11180060), **Dong Hu**, Cheng Tian, Anh-Tu Nguyen, Chao Huang. **IEEE Transactions on Transportation Electrification (T-TE), 2025**
- [Enhancing Data-driven Energy Management Strategy via Digital Expert Guidance for Electrified Vehicles](https://www.sciencedirect.com/science/article/pii/S0306261924025224), **Dong Hu**, Chao Huang, Jingda Wu, Henglai Wei, Dawei Pi. **Applied Energy, 2025**
- [A transfer-based reinforcement learning collaborative energy management strategy for extended-range electric buses with cabin temperature comfort consideration](https://www.sciencedirect.com/science/article/pii/S0360544223034916), **Dong Hu**, Chao Huang, Guodong Yin, Yangmin Li, Yue Huang, Hailong Huang, Jingda Wu, Wenfei Li, Hui Xie. **Energy, 2023**
- [An apprenticeship and reinforcement learning scheme based on expert demonstrations for energy management strategy of hybrid electric vehicle](https://www.sciencedirect.com/science/article/pii/S0306261923005913), **Dong Hu**, Hui Xie, Kang Song, Yuanyuan Zhang, Long Yan. **Applied Energy, 2023**
- [Deep reinforcement learning based on driver experience embedding for energy management strategies in hybrid electric vehicles](https://onlinelibrary.wiley.com/doi/epdf/10.1002/ente.202200123), **Dong Hu**, Yuanyuan Zhang. **Energy Technology, 2022**
- [Effect of spherical-convex surface texture on tribological performance of water-lubricated bearing](https://www.sciencedirect.com/science/article/abs/pii/S0301679X19300751), **Dong Hu**, Zhiwei Guo, Xin Xie, Chengqing Yuan. **Tribology International, 2019**
- [A Novel Hydrophilic PVA Fiber Reinforced Thermoplastic Polyurethane Materials for Water-lubricated Stern Bearing](https://link.springer.com/article/10.1007/s12221-021-0013-2), **Dong Hu**, Zhiwei Guo, Tian Jun, Chengqing Yuan. **Fibers and Polymers, 2021**
  

## Conference
- [Generalizing Autonomous Navigation via Human-Guided Diffusion Policies with Adversarial Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/11423599/), **Dong Hu**, Yangyang Zhou, Fengqing Hu, Chao Huang, Jingda Wu, Andrey V Savkin, **2025 IEEE 28th International Conference on Intelligent Transportation Systems (ITSC), 2025**
- [Enhancing autonomous driving following motion decision-making through model-based policy optimization](https://digital-library.theiet.org/doi/abs/10.1049/icp.2023.3356), **Dong Hu**, Zhipeng Shen, Chao Huang, Hailong Huang, **International Conference on Electric Vehicle and Vehicle Engineering (CEVVE 2023), 2023**
- An Iterative Optimization Algorithm for Vehicle Speed Prediction Considering Driving Style and Historical Data Effects, Hui Xie, **Dong Hu**, Kang Song, **40th Chinese Control Conference (CCC), 2021**

# 🎖 Honors and Awards
- 2021.10 China (Shenyang) Intelligent Connected Automobile Prospective Application competition, Silver Medal
- 2021.06 World Intelligent Driving "HUAWEI MDC Cup" Extreme Challenge competition, Gold Medal
- 2020.06 World Intelligent Driving Challenge competition, Excellence Award

# 📖 Education
- *2023.09 - 2026.09*, PhD, The Hong Kong Polytechnic University, Hong Kong, China
- *2020.09 - 2023.03*, Master of Engineering, Power mechanical engineering , Tianjin University, Tianjin, China
- *2016.09 - 2020.06*, Bachelor of Engineering, Marine Engineering, Wuhan University of technology, Wuhan, China

# 📚 Academic Services
*Journal Reviewer*
- IEEE Transactions on Mobile Computing (T-MC), IEEE Transactions on Automation Science and Engineering (T-ASE), IEEE Robotics and Automation Letters (RA-L)
- IEEE Transactions on Intelligent Transportation Systems (T-ITS), IEEE Transactions on Vehicular Technology (T-VT), IEEE Transactions on Intelligent Vehicles (T-IV)
- Scientific Reports, Applied Energy, Energy, EAAI

*Conference Reviewer*
- IEEE Intelligent Transportation Systems Conference (ITSC) 2024 – 2025

