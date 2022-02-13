---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

**Safe Learning On Maximizing the Region of Attraction of Partially Unknown Systems**{: style="color: RoyalBlue;"}
--------------------------
<img src="/images/research_topic_11.png" alt="IEEE" style="width:845px;height:309px;">
Recent advances in learning techniques have enabled the modelling of unknown dynamical systems directly from data. However, in many contexts, these learning-based methods are short of safety guarantee and strict stability verification. To address this issue, this work first approximates the partially unknown nonlinear systems by using a learned state space with Gaussian Processes and Chebyshev interpolants. A Sum-of-Squares Programming based approach is then proposed to synthesize a controller by searching an optimal control Lyapunov Barrier function. In this way, we maximize the estimated region of attraction of partially unknown nonlinear systems, while guaranteeing both safety and stability. It is shown that the proposed method improves the extrapolation performance, and at the same time, generates a significantly larger estimated region of attraction.

**Multi-vehicle Autonomous Driving via Multi-agent Reinforcement Learning**{: style="color: RoyalBlue;" }
----------------------
<img src="/images/research_topic_22.png" alt="IEEE" style="width:864px;height:303px;">
Controlling multiple autonomous vehicles is quite challenging in a mixed traffic where it coexists with human-driven vehicles. In this work, we
formulate the multiple autonomous vehicle driving problem as a multi-agent reinforcement learning problem, where the autonomous vehicles collaboratively learn a policy to adapt to human-driven vehicles, under interactions with other autonomous vehicles. A scalable learning algorithm is provided for time-varying interaction and communication. Parameter sharing and local rewards are exploited to foster inter-agent cooperation while achieving a desirable scalability. An action masking scheme is used to elevate learning efficiency by filtering out unsafe actions at each step. In addition, a novel priority-based safety supervisor is proposed to prevent collision and dramatically expedite the training process. In this way, a gym-like simulation environment is built with three different levels of traffic densities. We exploit curriculum learning to efficiently learn harder tasks from trained models under simpler settings. Comprehensive experimental results show the proposed framework consistently outperforms several state-of-theart benchmarks.


**Transient stability of Smart Grids with Renewable Energy Resources**{: style="color: RoyalBlue;" }
-----------------
<img src="/images/research_topic_33.jpg" alt="IEEE" style="width:728px;height:360px;">
This work is expected to use of an intelligent multi-agent system approach to investigate the effect of a sudden change in generator load and the impact of integrating renewable energy sources on the enhancement of the transient stability of smart power grids. In this proposed approach, an algorithm is developed through which intelligent agents properly coordinate a system's protective relays using the critical clearing time information to avoid loss of synchronism. Several benchmark cases are studied to dynamically evaluate the on-line performance and effectiveness of the proposed approach. The simulation results show that the individual agents provide a powerful framework to successfully enhance the transient stability of the system for different fault locations under various generator load conditions and increasing penetration of wind power.
