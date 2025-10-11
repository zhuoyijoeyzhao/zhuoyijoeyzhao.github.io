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
<div style="border:1px solid #ddd; border-radius:10px; padding:20px; margin-bottom:25px; box-shadow:0 1px 3px rgba(0,0,0,0.1); background-color:white;">

<h3 style="margin-top:0;">
<a href="https://arxiv.org/pdf/2501.06688" target="_blank" style="color:#007ACC; text-decoration:none;">
Optimizing Age of Information without Knowing the Age of Information
</a>
</h3>

<p>
<b>📅 Published:</b> <i>IEEE INFOCOM</i>, May 2025
</p>

<div style="display:flex; align-items:flex-start; gap:20px;">
  <div style="flex:2;">
    <p>
    We consider a network where a wireless base station (BS) connects multiple source-destination pairs. Packets from each source are generated according to a general renewal process and are enqueued in a single packet queue that stores only the latest generated packet. The BS decides, at each time slot $t$, which sources to schedule. Selected sources transmit their packet to the BS via unreliable links. Successfully received packets are forwarded to their corresponding destinations. The connection between the BS and the destinations is assumed unreliable and delayed. Information freshness at the destination is captured by the Age of Information (AoI) metric. The objective of the scheduling decisions is to leverage the imperfect (i.e., delayed and unreliable) knowledge of the AoI to keep the information at the destinations as fresh as possible.
    In this work, we derive a lower bound on the achievable AoI by any transmission scheduling policy. Then, we develop an optimal randomized policy for any packet generation processes. Next, we develop minimum mean square error estimators of the AoI and system times, and develop a Max-Weight policy that leverages these estimators. We evaluate the AoI of the optimal randomized policy and of the Max-Weight policy both analytically and through simulations. The numerical results suggest that the Max-Weight policy with estimation outperforms the optimal randomized policy even when the BS has no knowledge of the AoI at the destination.
    </p>
  </div>

  <div style="flex:1; text-align:center;">
    <img src="images/INFOCOM_2025.pdf" alt="Figure_INFOCOM 2025" style="max-width:100%; border-radius:8px;"/>
  </div>
</div>
</div>

<!-- ===== Publication 2 ===== -->
