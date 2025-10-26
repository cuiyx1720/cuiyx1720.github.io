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

👋 I am a PhD student at Tongji University, affiliated with the Institute of Intelligent Vehicles (TJU-IIV). Previously completed my bachelor's degree at Jilin University, graduating as an Outstanding Graduate (Top 1%). I am currently under the supervision of [Prof. Yanjun Huang](https://scholar.google.com/citations?user=r_XUM78AAAAJ), who is National High-level Talent in China.

🚘 My research centers on the continual closed-loop evolution of autonomous systems. I focus on enabling self-evolving, adaptive, and trustworthy autonomous systems through Reinforcement learning, Continual learning, and LLM reasoning.


# 🔥 News
- *2025.10*: &nbsp;🌟 Selected as a Pioneer Scholar in the SAE Doctoral Talent Program.
- *2025.07*: &nbsp;👏 Our paper [GEMINUS](https://arxiv.org/abs/2507.14456) on the Mixture-of-Experts framework for end-to-end autonomous driving has been released.
- *2025.05*: &nbsp;👏 Our survey [CoT4AD](https://arxiv.org/abs/2505.20223) on Chain-of-Thought for autonomous driving has been released.
- *2025.02*: &nbsp;👏 Our paper [MoPE](https://arxiv.org/abs/2502.05943) on continual adaptation of learning-based autonomous driving has been released.
- *2024.09*: &nbsp;🎓 Started my Ph.D. studies at Tongji University.
- *2024.06*: &nbsp;🎉 Graduated from Jilin University with the honor of **Outstanding Bachelor Graduate**!
- *2022.11*: &nbsp;📑 My first [invention patent](https://kns.cnki.net/kcms2/article/abstract?v=FqAfUZ3F7baPG1Bx9_olX9DYGWZbjmkgIzugBV-T4XtdedrwgyWYuPofTEdMbS_UWxc_XwqsSjGKK07MiCnkOOMpCZFEHSelFx4bNU8T9WdNIRSWo9r9dI_sxF-gCjD98_U9zdULTlN2KmJ1-8c8kGm1Qh4cKb4WrGKtl4Dh9ExWn5-_qEQrqQ==&uniplatform=NZKPT&language=CHS) ZL114655114A has been officially granted.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><img src='images/GEMINUS.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**GEMINUS: Dual-aware Global and Scene-Adaptive Mixture-of-Experts for End-to-End Autonomous Driving**

Chi Wan, **Yixin Cui**<span style="color:#7a8288;">, Jiatong Du, Shuo Yang, Yulong Bai, Yanjun Huang*

GEMINUS, a Mixture-of-Experts framework for end-to-end autonomous driving with a dual-aware router, achieves state-of-the-art performance and robust adaptability across diverse traffic scenarios.

<span style="color:#2c4a88;">arXiv, 2025</span> \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://arxiv.org/abs/2507.14456) \| [![](https://img.shields.io/github/stars/newbrains1/GEMINUS?style=social&label=Code%20Stars&logoColor=2c4a88)](https://github.com/newbrains1/GEMINUS)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/CoT4AD.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Chain-of-Thought for Autonomous Driving: A Comprehensive Survey and Future Prospects**

**Yixin Cui**<span style="color:#7a8288;">, Haotian Lin, Shuo Yang, Yixiao Wang, Yanjun Huang*, Hong Chen</span>

We explore how Chain-of-Thought reasoning enhances autonomous driving systems and propose its integration with self-learning for continual model evolution.

<span style="color:#2c4a88;">arXiv, 2025</span> \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://arxiv.org/abs/2505.20223) \| [![](https://img.shields.io/github/stars/cuiyx1720/Awesome-CoT4AD?style=social&label=Code%20Stars&logoColor=2c4a88)](https://github.com/cuiyx1720/Awesome-CoT4AD)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/MoPE.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**Continual Adaptation for Autonomous Driving with the Mixture of Progressive Experts Network**

**Yixin Cui** <span style="color:#7a8288;">, Shuo Yang, Chi Wan, Xincheng Li, Jiaming Xing, Yuanjian Zhang, Yanjun Huang*, Hong Chen

MoPE enables continual adaptation in autonomous driving via progressive expert activation, achieving strong performance in complex driving scenarios.

<span style="color:#2c4a88;">arXiv, 2025</span> \| [<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://arxiv.org/abs/2502.05943)

</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🔬 Project

<div class='paper-box'><div class='paper-box-image'><img src='images/HEAD.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**<img src='images/head_logo.jpg' style='width: 30px; height: auto; vertical-align: middle; margin-right:3px;'> HEAD: Holistic Evolutionary Autonomous Driving**

<span style="color:#7a8288;"> Institute of Intelligent Vehicles, Tongji University, *2024.10 - now*</span>

**Student Leader**

HEAD is a holistic suite of evolutionary autonomous driving software, based on the MetaDrive simulation platform, that seamlessly imports driving scenarios, uploads training models, and efficiently performs continuous training designed to significantly improve the performance of arbitrary models.
It was also showcased at the National Industrial Software Conference, where it received high praise from experts.

[<img src='images/paper.png' style='width: auto; height: 21px; vertical-align:-30%; margin-right:0px;'>](https://ieeexplore.ieee.org/abstract/document/10384641) \| [![](https://img.shields.io/github/stars/XingZuoMuYe/HEAD?style=social&label=Code%20Stars&logoColor=2c4a88)](https://github.com/XingZuoMuYe/HEAD)

</div>
</div>

# 🏆 Awards
- *2024.11* &nbsp; **National First Prize**, 2024 China Intelligent Vehicle Future Challenge – Complex Traffic Environment Algorithm Track (NSFC)
- *2024.11* &nbsp; **Province Second Prize**, 2024 China–Shandong Innovation and Entrepreneurship Competition for PhD and Postdoctoral Talents
- *2022.11* &nbsp; **National First Prize**, 2022 GAC Honda Automobile Road Safety Innovation Competition
- *2021.08* &nbsp; **National Second Prize**, 2021 National College Student Energy Conservation and Emission Reduction Competition

# 🏅 Honors
- *2025.10* &nbsp; **Pioneer Scholar**, SAE Doctoral Talent Program 🏅 (**One of 10 nationwide**)
- *2024.06* &nbsp; **Outstanding Graduate** of Jilin University (**Top 1%**)
- *2023.09* &nbsp; **MAXUS Automative Scholarship**, awarded by SAIC MAXUS Automotive Co., Ltd. (**Top 2%**)
- *2022.09* &nbsp; **Suzhou Industrial Zone Scholarship**, funded by the Suzhou Government of Jiangsu Province (**Top 1%**)
- *2020-2024* &nbsp; **First-class Scholarship** of Jilin University (Four times, **Top 2%**)
- *2020-2024* &nbsp; **Academic and Scientific Scholarship** of Jilin University (Four times, **Top 5%**)

# 📖 Educations
- *2024.09 - Now*, Ph.D., Automotive Engineering, <img src='images/Tongji_logo.png' style='width: 25px; height: auto; vertical-align:-33%; margin-right:0px;'> Tongji University (TJU), Shanghai, China **(Test Waiver Admission)**
- *2020.09 - 2024.06*, B.Eng., Automotive Operation Engineering, <img src='images/JLU_logo.png' style='width: 25px; height: auto; vertical-align:-35%; margin-right:0px;'> Jilin University (JLU), Changchun, China **(Outstanding Graduate,Top 1%)**
- *2017.09 - 2020.07*, High School Diploma, <img src='images/haian.jpg' style='width: 23px; height: auto; vertical-align:-35%; margin-right:0px;'> Haian Senior School of Jiangsu Province, Nantong, China

# 📚 Academic Services
**Journal Reviewer**:
- IEEE Transactions on Intelligent Transportation Systems \| [T-ITS](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6979)
- Proceedings of the Institution of Mechanical Engineers, Part D: Journal of Automobile Engineering \| [Part D](https://journals.sagepub.com/home/pid)
**Conference Reviewer**: 
- IEEE International Conference on Robotics and Automation \| [ICRA 2025](https://2025.ieee-icra.org/)

[//]: # (**Conference Reviewer**:  )

[//]: # (- IEEE Intelligent Transportation Systems Conference \| [ITSC]&#40;https://ieee-itsc.org/2024/&#41;)

# 🗣️ Talks
- *2025.05*, Three-Minute Thesis (3MT) Academic Talk at Tongji University, on the topic of *Continual Self-Evolution in Closed-Loop Autonomous Driving Systems*
- *2023.10*, Presentation of National Excellent Bachelor Project, Innovation and Entrepreneurship Program: *Design of an Automatic Rear-End Collision Warning System for Vehicles* (Project Leader)
- *2021.10*, Presentation of National Excellent Bachelor Project, Innovation and Entrepreneurship Program: *Visual Filter Based on Self-Driven Film Materials* (Project Participant)

# 📌 Hobbies
- 🏓 I enjoy playing **table tennis** and am currently a member of the Tongji University Team. During my undergraduate studies, I served as the Vice President of the Jilin University Table Tennis Association.
- ♟️ I have a strong interest in strategic board games and play **Go** at an amateur 2-dan level.
- 🎸 I enjoy playing acoustic **guitar** (Level 8). My favorite guitarist is Masaaki Kishibe, whose music greatly inspires my playing.
- ⚽️ I am a loyal supporter of [Arsenal Football Club](https://www.arsenal.com/), with the former coach [Arsène Wenger](https://en.wikipedia.org/wiki/Ars%C3%A8ne_Wenger) being a major source of inspiration — COYG!
- 🎮 I enjoy **Nintendo** games, particularly Super Mario Maker 2 for its creativity and fun.
- 📸 Recently, I’ve also been exploring **baseball**, **fitness** and **photography** to enrich my daily life.