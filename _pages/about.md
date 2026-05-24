---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student in the Department of Data Science at LKC Medical School, [Nanyang Technological University](https://www.ntu.edu.sg/), under the supervision of [Prof. Si Yong Yeo](https://medvisailab.github.io/), [Prof. Yu Baosheng](https://scholar.google.com/citations?user=fjzIdMQAAAAJ&hl=en), and [Prof. Li Ming](https://ming1993li.github.io/).

I completed my master’s degree at the [Department of Computer Engineering](https://cde.nus.edu.sg/ece/), [Show Lab @ National University of Singapore](https://sites.google.com/view/showlab), where I was supervised by [Prof. Mike Zheng Shou](https://cde.nus.edu.sg/ece/staff/shou-zheng-mike/).

You can find my CV here: [Yufei Shi's Curriculum Vitae](../assets/CV-Shi_Yufei.pdf) and [Chinese CV](../assets/申请简历_师羽飞.pdf).

[Email](mailto:yufei005@e.ntu.edu.sg) / [Github](https://github.com/Yufei2000) 

## Recent News

- [May. 2026] One Sentence, One Drama: Personalized Short-Form Drama Generation via Multi-Agent Systems is available on ***arXiv***.
- [May. 2026] 4DPC^2hat: Towards Dynamic Point Cloud Understanding with Failure-Aware Bootstrapping is accepted by ***ICML 2026***!
- [Mar. 2026] RIHA: Report-Image Hierarchical Alignment for Radiology Report Generation is published online in ***IEEE JBHI***!
- [Feb. 2026] SciEducator: Scientific Video Understanding and Educating via Deming-Cycle Multi-Agent System is accepted by ***CVPR 2026***!
- [Sep. 2025] ColonNeRF: Hierarchical Neural Radiance Fields for High-Fidelity Long-Sequence Colon Reconstruction is accepted by ***Neurocomputing 2025***.
- [Jun. 2025] PVChat: Personalized Video Chat with One-Shot Learning is accepted by ***ICCV 2025***!

## Publications

<div class="home-publications">
{% assign pubs = site.publications | sort: "date" | reverse %}
{% for post in pubs %}
  {% include archive-single.html %}
{% endfor %}
</div>
