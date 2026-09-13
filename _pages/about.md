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

<style>
/* Homepage-only typography with restrained Northwestern Purple accents. */
.page__content {
  --home-ink: #303138;
  --home-accent: #4E2A84;
  --home-muted: #60616b;
  --home-rule: #E4E0EE;
  color: var(--home-ink);
  font-size: 17px;
  line-height: 1.68;
  overflow-wrap: break-word;
}

.page__content p {
  margin: 0 0 1em;
}

.page__content p + p {
  margin-top: 0;
  text-indent: 0;
}

.page__content a {
  color: var(--home-accent);
  text-decoration-thickness: 1px;
  text-underline-offset: 0.16em;
}

.page__content a:hover {
  color: #401F68;
}

.page__content a:focus-visible {
  outline: 2px solid var(--home-accent);
  outline-offset: 3px;
}

.page__content h2 {
  margin: 2em 0 0.8em;
  padding-bottom: 0.35em;
  border-bottom: 1px solid var(--home-rule);
  color: var(--home-accent);
  font-size: 1.35em;
  font-weight: 700;
  line-height: 1.35;
  scroll-margin-top: 5rem;
}

.page__content h3 {
  margin: 1.4em 0 0.85em;
  color: var(--home-accent);
  font-size: 1.06em;
  font-weight: 700;
  line-height: 1.4;
  scroll-margin-top: 5rem;
}

.page__content ul {
  margin-bottom: 1em;
}

.page__content li {
  margin-bottom: 0.55em;
}

.page__content li > p {
  margin-bottom: 0.55em;
}

.page__content li > ul {
  margin-top: 0.3em;
  margin-bottom: 0.65em;
}

/* Replace the theme's old negative-margin About anchor. */
.page__content #about-me {
  display: block;
  height: 0;
  margin: 0;
  padding: 0;
  scroll-margin-top: 5rem;
}

.page__content #about-me::before {
  display: none;
  content: none;
}

.page__content .publication-list {
  margin: 0 0 1.4em;
  padding: 0;
  list-style: none;
}

.page__content .publication-list > li {
  margin: 0 0 1.35em;
  padding: 0;
}

.page__content .publication-title {
  margin: 0 0 0.2em;
  font-size: 1em;
  font-weight: 700;
  line-height: 1.5;
}

.page__content .publication-title a {
  color: var(--home-ink);
  text-decoration: none;
}

.page__content .publication-title a:hover,
.page__content .publication-title a:focus-visible {
  color: var(--home-accent);
  text-decoration: underline;
}

.page__content .publication-id {
  margin-right: 0.25em;
  color: var(--home-muted);
  font-size: 0.86em;
  font-weight: 400;
  white-space: nowrap;
}

.page__content .publication-authors {
  margin: 0 0 0.12em;
  font-size: 0.94em;
  line-height: 1.55;
}

.page__content .publication-meta {
  color: var(--home-muted);
  font-size: 0.9em;
  line-height: 1.55;
}

.page__content .publication-venue {
  color: var(--home-ink);
  font-weight: 600;
}

.page__content .publication-status {
  color: var(--home-accent);
}

@media (max-width: 600px) {
  .page__content {
    font-size: 16px;
  }

  .page__content h2 {
    margin-top: 1.7em;
  }

  .page__content .publication-list > li {
    margin-bottom: 1.5em;
  }
}
</style>

<div id="about-me" aria-hidden="true"></div>

My name is Zhuoyi Zhao, and I am currently a first-year Ph.D. student at The University of Hong Kong, supervised by [Prof. Xianhao Chen](https://xianhaochen.net/).

Previously, I was a Graduate Research Assistant at the University of Toronto, supervised by [Prof. Ben Liang](http://www.comm.utoronto.ca/~liang). I received the M.S. degree in Electrical Engineering from Northwestern University, Evanston, USA, in 2025, where I was supervised by [Prof. Igor Kadota](https://sites.northwestern.edu/networkx/), and the B.E. degree in Information Engineering from Beijing Jiaotong University, Beijing, China, in 2023, under the supervision of [Prof. Jiayi Zhang](https://sites.google.com/site/jiayizhang8650/).

My current research interests focus on developing theories and models that capture the fundamental limits and trade-offs in communication networks, federated learning, and multi-agent systems.

I am (always) actively seeking collaboration opportunities. If you are interested in my research, please feel free to reach out via email at zhuoyijoeyzhao@gmail.com or WeChat: joeyzzhao.

## Education

- *2026 - present*, University of Hong Kong, Ph.D in Electrical and Computer Engineering.

- *2023 - 2025*, Northwestern University, Master of Science in Electrical Engineering (Thesis-track). *Thesis:* *Optimizing Age-of-Information in Real-World Networks*.

- *2019 - 2023*, Beijing Jiaotong University, Bachelor of Engineering in Information Engineering.

## Experience

- Aug. 2025 – May. 2026, Graduate Research Assistant, University of Toronto, Focus on Online Optimization & Communication-Efficient Federated Learning.

## Publications

### Manuscripts Under Review

<ul class="publication-list">
  <li>
    <div class="publication-title"><span class="publication-id">[M6]</span> Analysis and Optimization of Age of Infomation in Large Scale Random Access Networks</div>
    <div class="publication-authors">Y. Chen, S. Fan, <strong>Z. Zhao</strong>, I. Hou, I. Kadota</div>
    <div class="publication-meta">IEEE conferences &middot; <span class="publication-status">Under review</span></div>
  </li>
  <li>
    <div class="publication-title"><span class="publication-id">[M5]</span> <a href="https://arxiv.org/pdf/2607.20967">Update the Unseen Only: Minimizing AoI for Collaborative Perception through Online Learning</a></div>
    <div class="publication-authors">Y. Ma, <strong>Z. Zhao</strong>, Z. Fang, H. An, X. Chen, Y. Fang</div>
    <div class="publication-meta">IEEE journals &middot; <span class="publication-status">Under review</span> &middot; <a href="https://arxiv.org/pdf/2607.20967">Paper</a></div>
  </li>
  <li>
    <div class="publication-title"><span class="publication-id">[M4]</span> <a href="https://arxiv.org/pdf/2607.23987">Adaptive Data Admission and Retention for Streaming Federated Learning</a></div>
    <div class="publication-authors"><strong>Z. Zhao</strong>, B. Liang</div>
    <div class="publication-meta">ACM conferences &middot; <span class="publication-status">Under review</span> &middot; <a href="https://arxiv.org/pdf/2607.23987">Paper</a></div>
  </li>
  <li>
    <div class="publication-title"><span class="publication-id">[M3]</span> <a href="https://arxiv.org/pdf/2605.13012">Toward Practical Age-of-Information Scheduling in 5G Cellular</a></div>
    <div class="publication-authors"><strong>Z. Zhao</strong>, I. Kadota</div>
    <div class="publication-meta">IEEE conferences &middot; <span class="publication-status">Under review</span> &middot; <a href="https://arxiv.org/pdf/2605.13012">Paper</a></div>
  </li>
  <li>
    <div class="publication-title"><span class="publication-id">[M2]</span> Scheduling Policies for Age Minimization in Wireless Networks with Mixed Update Sizes</div>
    <div class="publication-authors"><strong>Z. Zhao</strong>, V. Tripathi, I. Kadota</div>
    <div class="publication-meta"><span class="publication-venue">IEEE/ACM Transactions on Networking</span> &middot; <span class="publication-status">Major revision</span></div>
  </li>
  <li>
    <div class="publication-title"><span class="publication-id">[M1]</span> Minimizing Age of Information Without Knowing the Age of Information</div>
    <div class="publication-authors"><strong>Z. Zhao</strong>, I. Kadota</div>
    <div class="publication-meta">IEEE journals &middot; <span class="publication-status">Under review</span></div>
  </li>
</ul>

### Conference Papers

<ul class="publication-list">
  <li>
    <div class="publication-title"><span class="publication-id">[C3]</span> <a href="https://arxiv.org/pdf/2503.23658">Optimizing Age of Information in Networks with Large and Small Updates</a></div>
    <div class="publication-authors"><strong>Z. Zhao</strong>, V. Tripathi, I. Kadota</div>
    <div class="publication-meta"><span class="publication-venue">WiOpt 2025</span> &middot; Invited paper &middot; <a href="https://arxiv.org/pdf/2503.23658">Paper</a></div>
  </li>
  <li>
    <div class="publication-title"><span class="publication-id">[C2]</span> <a href="https://arxiv.org/pdf/2501.06688">Optimizing Age of Information Without Knowing the Age of Information</a></div>
    <div class="publication-authors"><strong>Z. Zhao</strong>, I. Kadota</div>
    <div class="publication-meta"><span class="publication-venue">IEEE INFOCOM 2025</span> &middot; Acceptance rate: 18.7% &middot; <a href="https://arxiv.org/pdf/2501.06688">Paper</a> &middot; <a href="https://github.com/Net-X-Research-Group/AoI_Estimator/tree/main">Code</a></div>
  </li>
  <li>
    <div class="publication-title"><span class="publication-id">[C1]</span> <a href="https://arxiv.org/pdf/2210.08869">Performance Analysis of Cell-Free Massive MIMO Systems with Asynchronous Reception</a></div>
    <div class="publication-authors">J. Zheng, <strong>Z. Zhao</strong>, J. Zhang, J. Cheng, V. Leung</div>
    <div class="publication-meta"><span class="publication-venue">IEEE GlobeCom Workshops, 2023</span> &middot; <a href="https://arxiv.org/pdf/2210.08869">Paper</a></div>
  </li>
</ul>

## News

- *May. 2026*: After more than a year of waiting for my visa, I decided to join The University of Hong Kong to pursue my Ph.D. Despite the difficult circumstances, I truly enjoyed my research experience this year. Many thanks to my advisor, **[Prof. Ben Liang](http://www.comm.utoronto.ca/~liang)**, for his support throughout this journey; it has been a great honor to work with him.
- *Aug. 2025*: Admitted to the Ph.D. program at the University of Toronto with the Edward S. Rogers Sr. Graduate Scholarship, but was unable to enroll due to visa delays. :(

<img src="/images/withIgor_May2025.jpg"
      alt="With Prof. Igor Kadota"
      style="float: right; width: 250px; height: auto; margin: 0 0 12px 24px; border-radius: 8px;">
- *May. 2025*: Awarded the **Best Electrical Engineering MS Thesis Award** for my Thesis entitled “Optimizing Age of Information in Real-World Network”. Sincere gratitude to my advisor, **[Prof. Igor Kadota](https://sites.northwestern.edu/kadota/)**.
- *May. 2025*: Just presented the paper entitled “Optimizing Age of Information without Knowing the Age of Information” in **IEEE INFOCOM 2025** and enjoyed a wonderful trip. The [Open Source Code](https://github.com/Net-X-Research-Group/AoI_Estimator/tree/main) for this work could be found here.
<div style="clear: both;"></div>
- *Mar. 2025*: Our paper entitled “Optimizing Age of Information in Networks with Large and Small Updates” has been accepted by **WiOPT 2025**. See you in Linköping!
- *Dec. 2024*: Our paper entitled “Optimizing Age of Information without Knowing the Age of Information” has been accepted by **IEEE INFOCOM 2025**. See you in London!

## Services

- **Journal reviewer**
  - *IEEE/ACM Transactions on Networking*
  - *IEEE Transactions on Mobile Computing*
  - *IEEE Wireless Communication Letters*
- **Conference reviewer**
  - *IEEE INFOCOM 2027*
  - *IEEE GLOBECOM 2026*
- **Teaching Assistant**: *EE 307: Communication Systems*, Northwestern University, Fall 2024

## Honors and Awards

- *Postgraduate Scholarship*, University of Hong Kong, 2026-2030
- *Best Electrical Engineering MS Thesis Award*, Northwestern University, 2025

## Contact

- Email: **zhuoyijoeyzhao@connect.hku.hk, zhuoyijoeyzhao@gmail.com**
