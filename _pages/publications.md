---
permalink: /publications/
title: "Research"
excerpt: ""
author_profile: true
redirect_from: 
  - /publications
  - /publications.html
---
<!-- ===== Publication 1 ===== -->
<div style="border:1px solid #ddd; border-radius:10px; padding:20px; margin-bottom:25px; box-shadow:0 1px 3px rgba(0,0,0,0.1); background-color:white; text-align:justify;">

<h3 style="margin-top:0; text-align:left;">
<a href="https://arxiv.org/pdf/2501.06688" target="_blank" style="color:#007ACC; text-decoration:none;">
Achieving Age of Information-Aware Scheduling in Real-World System
</a>
</h3>


<div style="text-align:center; margin-bottom:15px;">
  <img src="/images/INFOCOM_2025.png" alt="Figure_INFOCOM 2025" style="max-width:60%; border-radius:10px; box-shadow:0 2px 6px rgba(0,0,0,0.15);"/>
</div>

<div>
  <p>
  We consider a network where a wireless base station (BS) connects multiple source–destination pairs. Packets from each source are generated according to a general renewal process and are stored in a single-packet queue that always keeps the latest generated packet. At each time slot $t$, the BS decides which sources to schedule for transmission. The selected sources send their packets to the BS through unreliable uplink channels. Successfully received packets are then forwarded to their corresponding destinations through unreliable and delayed downlink connections. Each delivered packet thus undergoes two transmission stages: a wireless uplink transmission and a multi-hop heterogeneous transmission with a two-way delay. The freshness of information at the destination is measured by the Age of Information (AoI) metric. The objective of the scheduling policy is to leverage imperfect (i.e., delayed and unreliable) feedback of the AoI to keep the destination information as fresh as possible.
  </p>

  <p>
  In [C2], we derive a lower bound on the achievable AoI under any transmission scheduling policy. Then, we design an optimal randomized policy applicable to general packet generation processes. Next, we develop minimum mean square error estimators of the AoI and system times, based on which we propose a Max-Weight scheduling policy that exploits these estimators. We evaluate the AoI performance of both the optimal randomized and Max-Weight policies analytically and through simulations. The numerical results show that the Max-Weight policy with estimation achieves lower AoI than the optimal randomized policy, even when the BS has no direct knowledge of the destination AoI.
  </p>

  <p>
  In [J2], we further develop a Low-Complexity Estimator based on a Bernoulli Approximation, which achieves near-optimal performance and maintains provable performance guarantees while significantly reducing computational cost. We implement the proposed estimator in NetSim, a system-level 5G network simulator, to further demonstrate its performance and generalization capability in realistic wireless network scenarios.
  </p>
</div>
</div>


<!-- ===== Publication 2 ===== -->
<div style="border:1px solid #ddd; border-radius:10px; padding:20px; margin-bottom:25px; box-shadow:0 1px 3px rgba(0,0,0,0.1); background-color:white; text-align:justify;">

<h3 style="margin-top:0; text-align:left;">
<a href="https://arxiv.org/pdf/2503.23658" target="_blank" style="color:#007ACC; text-decoration:none;">
Minimizing Age of Information in Networks with Heterogeneous Updates
</a>
</h3>

<div style="display:flex; flex-wrap:wrap; align-items:flex-start; gap:25px;">

  <!-- 左侧文字 -->
  <div style="flex:1.8; min-width:270px;">
    <p>
    Modern sensing and monitoring systems often involve sources generating updates of heterogeneous sizes, ranging from small telemetry data such as position and temperature measurements to large-scale data such as images, video frames, and LiDAR point clouds. Existing wireless scheduling approaches for information freshness often neglect this heterogeneity, resulting in suboptimal performance. In this paper, we study a single-hop wireless broadcast network in which multiple sources transmit updates of different sizes to a base station over unreliable links. Some sources generate large updates that span multiple time slots, while others generate small updates occupying only a few slots. Because only one source can transmit to the base station in each time slot, it is necessary to design scheduling policies that account for the update size diversity. 
    </p>
    <p>
    In [C3], we first derive a lower bound on the achievable Age of Information (AoI) under any transmission scheduling policy. Then, we propose optimal randomized policies that consider both switching and non-switching behaviors during large update transmissions. We introduce a Lyapunov-based analytical framework to design an AoI-aware Max-Weight policy with a provable constant-factor optimality guarantee. Finally, we evaluate the proposed policies through extensive simulations, showing that the Max-Weight policy achieves near-optimal AoI performance across a variety of network conditions. 
    </p>
    <p>
    In [J3], motivated by transmission scheduling frameworks for minimizing AoI in multihop wireless networks, we further develop an Age Debt policy based on a Lyapunov formulation that incorporates virtual age-debt queues. This approach enables one-slot Lyapunov drift analysis for networks with heterogeneous update lengths ($L_i > 1$), where the objective is to minimize the cumulative age debt across multiple virtual queues. The key insight is that scheduling large updates with $L_i > 1$ is structurally similar to scheduling transmissions in multihop networks, since in both cases multiple transmissions are required before an AoI reduction occurs. Building on this analogy, we adapt the multihop solution framework proposed in previous work (Tripathi et al., 2021) to our heterogeneous update setting. Simulation results show that the Age Debt policy can outperform the Max-Weight policy under certain network configurations.
    </p>
  </div>

  <!-- 右侧两张堆叠的图片（加大宽度） -->
  <div style="flex:1.2; min-width:230px; display:flex; flex-direction:column; align-items:center; gap:20px;">
    <img src="/images/WiOPT_2025_1.png" alt="WiOPT Figure 1" style="max-width:120%; border-radius:10px; box-shadow:0 2px 6px rgba(0,0,0,0.15);"/>
    <img src="/images/WiOPT_2025_2.png" alt="WiOPT Figure 2" style="max-width:120%; border-radius:10px; box-shadow:0 2px 6px rgba(0,0,0,0.15);"/>
  </div>

</div>
</div>
