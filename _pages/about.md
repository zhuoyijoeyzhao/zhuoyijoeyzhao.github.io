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

My name is Zhuoyi Zhao, and I am currently a Graduate Research Assistant at the University of Toronto, supervised by Prof. Ben Liang.  
Prior to this, I received the M.S. in Electrical and Engineering from Northwestern University, Evanston, USA, in 2025, where I was supervised by [Prof. Igor Kadota](https://sites.northwestern.edu/kadota/), and the B.E. in Information Engineering from Beijing Jiaotong University, Beijing, China, in 2023, under the supervision of [Prof. Jiayi Zhang](https://sites.google.com/site/jiayizhang8650/).
My current research interests lie in My current research interest is to develop theories and models that capture the fundamental limits and trade-offs of next-generation communication networks and multi-agent systems.



---

## Education

- *2023.09 - 2025.06*, Northwestern University, Master of Science in Electrical Engineering (Thesis-track). *Thesis:* *Optimizing Age-of-Information in Real-World Networks*.
  
- *2019.09 - 2023.06*, Beijing Jiaotong University, Bachelor of Engineering in Information Engineering. 

---

## Experience
- Aug. 2025 – present, Graduate Research Assistant, University of Toronto, Focus on Online Optimization & Communication-Efficient Fedarated Learning.
  
- Fall 2024, Grader, EE 307 Communication Systems, Northwestern University.

---

## Publications

**Conference Paper**  

- **Z. Zhao**, V. Tripathi, I. Kadota. *Optimizing Age of Information in Networks with Large and Small Updates.* To appear in **WiOpt 2025**. (Invited paper)  

- **Z. Zhao**, I. Kadota. *Optimizing Age of Information Without Knowing the Age of Information.* To appear in **IEEE INFOCOM 2025**. (Acceptance rate: 18.7%)  

- J. Zheng, **Z. Zhao**, J. Zhang, J. Cheng, V. Leung. *Performance Analysis of Cell-Free Massive MIMO Systems with Asynchronous Reception.* **IEEE Globecom Workshops**, 2023.  

**Journal manuscripts**  
- **Z. Zhao**, V. Tripathi, I. Kadota. *Minimizing Age of Information in Networks with Heterogeneous Updates.* (submitted), **IEEE/ACM Transactions on Networking**.
  
- **Z. Zhao**, I. Kadota. *Minimizing Age of Information Without Knowing the Age of Information.* (in preparation), **IEEE/ACM Transactions on Networking**.
  
- Y. Chen, **Z. Zhao**, I. Kadota, I. Hou. *Minimizing Age of Information in Random Access Networks with Age Threshold.* (in preparation), **IEEE/ACM Transactions on Networking**.


---
## Research

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
    We consider a network where a wireless base station (BS) connects multiple source-destination pairs. Packets from each source are generated according to a general renewal process and are enqueued in a single packet queue that stores only the latest generated packet. The BS decides, at each time slot $t$, which sources to schedule. Selected sources transmit their packet to the BS via unreliable links. Successfully received packets are forwarded to their corresponding destinations. The connection between the BS and the destinations is assumed unreliable and delayed. Each served packet will be delivered to the corresponding destination after two transmissions: a wireless uplink transmission and a multi-hop heterogeneous transmission with a two-way delay. The BS decides, at each time slot, which sources to serve to the corresponding destinations. Information freshness at the destination is captured by the Age of Information (AoI) metric. The objective of the scheduling decisions is to leverage the imperfect (i.e., delayed and unreliable) knowledge of the AoI to keep the information at the destinations as fresh as possible. 
    In this work, we derive a lower bound on the achievable AoI by any transmission scheduling policy. Then, we develop an optimal randomized policy for any packet generation processes. Next, we develop minimum mean square error estimators of the AoI and system times, and develop a Max-Weight policy that leverages these estimators. We evaluate the AoI of the optimal randomized policy and of the Max-Weight policy both analytically and through simulations. The numerical results suggest that the Max-Weight policy with estimation outperforms the optimal randomized policy even when the BS has no knowledge of the AoI at the destination.
    </p>
  </div>

  <div style="flex:1; text-align:center;">
    <img src="images/INFOCOM_2025.pdf" alt="Figure_INFOCOM 2025" style="max-width:100%; border-radius:8px;"/>
  </div>
</div>
</div>


---

## News
- *May. 2025*: Awarded the **Best Electrical Engineering MS Thesis Award** for my Thesis entitled “Optimizing Age of Information in Real-World Network”. Sincere gratitude to my advisor, [Igor Kadota](https://sites.northwestern.edu/kadota/).
- *May. 2025*: Just presented the paper entitled “Optimizing Age of Information without Knowing the Age of Information” in **IEEE INFOCOM 2025** and enjoyed a wonderful trip. The [Open Source Code](https://github.com/Net-X-Research-Group/AoI_Estimator/tree/main) for this work could be found here. 
- *Mar. 2025*: Our paper entitled “Optimizing Age of Information in Networks with Large and Small Updates” has been accepted by **WiOPT 2025**. See you in Linköping!
- *Dec. 2024*: Our paper entitled “Optimizing Age of Information without Knowing the Age of Information” has been accepted by **IEEE INFOCOM 2025**. See you in London!

---

# Honor and award
*Edward S. Rogers Sr. Graduate Scholarship*, University of Toronto, 2025-2029

*Best Electrical Engineering MS Thesis Award*, Northwestern University, 2025

---

## Skills
- Programming: **C, MATLAB, Python, LabVIEW, NetSim**.  
- Languages: **TOEFL 109**.

---

## Contact
- Email: **zhuoyijoeyzhao@gmail.com, ZhuoyiZhao@u.northwestern.edu**  
