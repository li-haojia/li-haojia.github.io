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
# 🙋‍♂️ About Me

<big>
I'm ***Haojia Li (李昊佳)***, a Ph.D. candidate in the [Aerial Robotics Group](https://uav.hkust.edu.hk) at [The Hong Kong University of Science and Technology](https://hkust.edu.hk), supervised by Prof. [Shaojie Shen (沈劭劼)](https://uav.hkust.edu.hk/group) since 2021. I obtained my bachelor's degree from [Northeastern University](https://english.neu.edu.cn) in 2021, majoring in [Robotics Engineering](http://www.rse.neu.edu.cn/rseenglish). Previously, I joined the [ZJU Fast Lab](http://zju-fast.com/) as an research assistant, supervised by Prof. [Fei GAO (高飞)](https://person.zju.edu.cn/fgaoaa). </big>


<big>
My primary research interests include robot planning and control.</big>
  
<!--  
 I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user={{ site.author.google_scholar_id }}'>google scholar citations <strong><span id='total_cit'>{{ site.author.google_scholar_citations }}</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user={{ site.author.google_scholar_id }}'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<!-- TRO Impact -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-RO</div><img src='images/papers/TRO2024_Impact.webp' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Impact-Aware Planning and Control for Aerial Robots with Suspended Payloads](https://ieeexplore.ieee.org/document/10478625)

Haokun Wang\*, **Haojia Li**\*, Boyu Zhou, Fei Gao, Shaojie Shen.(\*equal contrib.)

*IEEE Transactions on Robotics (**T-RO**), 2024*.

In this paper, we propose a novel impact-aware planning and control framework that resolves potential impacts caused by motion mode switching.

[Project Page](https://sites.google.com/view/suspended-payload/) | 
<a href="https://github.com/HKUST-Aerial-Robotics/IMPACTOR"><img alt="Code" src="https://img.shields.io/github/stars/HKUST-Aerial-Robotics/IMPACTOR"/></a>
<a href="https://www.youtube.com/watch?v=k_XGQyrNh9I"> <img alt="Youtube" src="https://img.shields.io/badge/Video-YouTube-red"></a>
<a href="https://www.bilibili.com/video/BV1zg4y1L7dC"> <img alt="Bilibili" src="https://img.shields.io/badge/Video-Bilibili-FF3676"></a>

</div>
</div>

<!-- RAL-Autotrans -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RA-L</div><img src='images/papers/RAL2023-Autotrans.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AutoTrans: A Complete Planning and Control Framework for Autonomous UAV Paylaod Transportation](https://doi.org/10.1109/LRA.2023.3313010)

**Haojia Li**, Haokun Wang, Chen Feng, Fei Gao, Boyu Zhou, Shaojie Shen

*IEEE Robotics and Automation Letters (**RA-L**), 2023*

- A real-time planning method to generate smooth trajectories.
- An adaptive NMPC with a hierarchical disturbance compensation strategy to overcome unknown external perturbations. 

<a href="https://github.com/HKUST-Aerial-Robotics/AutoTrans"><img alt="Code" src="https://img.shields.io/github/stars/HKUST-Aerial-Robotics/AutoTrans"/></a>
<a href="https://www.youtube.com/watch?v=X9g-ivBqy5g"> <img alt="Youtube" src="https://img.shields.io/badge/Video-YouTube-red"></a>
<a href="https://www.bilibili.com/video/BV1aM4y1a7c9"> <img alt="Bilibili" src="https://img.shields.io/badge/Video-Bilibili-FF3676"></a>
<a href="https://arxiv.org/abs/2310.15050"> <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2310.15050-b31b1b"></a>
</div>
</div>

<!-- IROS 2021 -FAST_DV -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2021</div><img src='images/papers/IROS2021-FAST_DV.webp' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FAST-Dynamic-Vision: Detection and Tracking Dynamic Objects with Event and Depth Sensing](https://doi.org/10.1109/IROS51168.2021.9636448)

Botao He\*, **Haojia Li**\*, Siyuan Wu, Dong Wang, Zhiwei Zhang, Qianli Dong, Chao Xu, Fei Gao (\*equal contrib.)

*IEEE/RSJ International Conference on Intelligent Robots and Systems  (**IROS**), 2021*

 Event camera based low-latency fast-moving dynamic object detection, and object trajectory prediction. 

<a href="https://github.com/ZJU-FAST-Lab/FAST-Dynamic-Vision"><img alt="Code" src="https://img.shields.io/github/stars/ZJU-FAST-Lab/FAST-Dynamic-Vision"/></a>
<a href="https://www.youtube.com/watch?v=QPpwppeE_x0"> <img alt="Youtube" src="https://img.shields.io/badge/Video-YouTube-red"></a>
<a href="https://www.bilibili.com/video/BV11U4y1p7EF"> <img alt="Bilibili" src="https://img.shields.io/badge/Video-Bilibili-FF3676"></a>
<a href="https://arxiv.org/abs/2103.05903"> <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2103.05903-b31b1b"></a>
</div>
</div>

<!-- ICRA 2024 FC_planner-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2024</div><img src='images/papers/ICRA2024-FC_planner.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FC-Planner: A Skeleton-guided Planning Framework for Fast Aerial Coverage of Complex 3D Scenes](https://ieeexplore.ieee.org/document/10610621)

Chen Feng, **Haojia Li**, Mingjie Zhang, Xinyi Chen, Boyu Zhou, Shaojie Shen

*IEEE International Conference on Robotics and Automation (**ICRA**), 2024*

**Best UAV Paper Award Finalist**

A skeleton-guided planning framework tailored for fast coverage of large and complex 3D scenes, which results in the generation of high-quality coverage paths and high computational efficiency.

[Project Page](https://hkust-aerial-robotics.github.io/FC-Planner/) | 
<a href="https://github.com/HKUST-Aerial-Robotics/FC-Planner"><img alt="Code" src="https://img.shields.io/github/stars/HKUST-Aerial-Robotics/FC-Planner"/></a>
<a href="https://www.youtube.com/watch?v=U-X4OddXI88"> <img alt="Youtube" src="https://img.shields.io/badge/Video-YouTube-red"></a>
<a href="https://arxiv.org/abs/2309.13882"> <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2309.13882-b31b1b"></a>
</div>
</div>

<!-- ICRA 2023 PredRecon-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2023</div><img src='images/papers/ICRA2023-predrecon.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PredRecon: A Prediction-boosted Planning Framework for Fast and High-quality Autonomous Aerial Reconstruction](https://ieeexplore.ieee.org/document/10160933)

Chen Feng, **Haojia Li**, Fei Gao, Boyu Zhou, Shaojie Shen.

*IEEE International Conference on Robotics and Automation (**ICRA**), 2023*

A prediction-boosted planning framework that can efficiently reconstruct high-quality 3D models for the target areas in unknown environments with a single flight.

<a href="https://github.com/HKUST-Aerial-Robotics/PredRecon"><img alt="Code" src="https://img.shields.io/github/stars/HKUST-Aerial-Robotics/PredRecon"/></a>
<a href="https://www.youtube.com/watch?v=ek7yY_FZYAc"> <img alt="Youtube" src="https://img.shields.io/badge/Video-YouTube-red"></a>
<a href="https://arxiv.org/abs/2302.04488"> <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2302.04488-b31b1b"></a>
</div>
</div>


<!-- Science Robotics 2024 - Event camera -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Science: Robotics</div><img src='images/papers/SR2024-eventcam.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Microsaccade-inspired event camera for robotics](https://www.science.org/doi/10.1126/scirobotics.adj8124)

Botao He, Ze Wang, Yuan Zhou, Jingxi Chen, Chahat Deep Singh, **Haojia Li**, Yuman Gao, Shaojie Shen, Kaiwei Wang, Yanjun Cao, Chao Xu, Yiannis Aloimonos, Fei Gao, Cornelia Fermüller

***Science Robotics**, 2024*

[Project Page](https://bottle101.github.io/AMI-EV/) | 
<a href="https://www.youtube.com/channel/UC-ppUIm_Ia2HqQkno5A0jog"> <img alt="Youtube" src="https://img.shields.io/badge/Video-YouTube-red"></a>
<a href="https://www.bilibili.com/video/BV1qU411d7p2"> <img alt="Bilibili" src="https://img.shields.io/badge/Video-Bilibili-FF3676"></a>
<a href="https://arxiv.org/abs/2405.17769"> <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2405.17769-b31b1b"></a>
</div>
</div>


<!-- Science Robotics 2022 - Swarm -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Science: Robotics</div><img src='images/papers/SR2022-Swarm.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Swarm of micro flying robots in the wild](https://www.science.org/doi/abs/10.1126/scirobotics.abm5954)

Xin Zhou, Xiangyong Wen, Zhepei Wang, Yuman Gao, **Haojia Li**, Qianhao Wang, Tiankai Yang, Haojian Lu, Yanjun Cao, Chao Xu, Fei Gao

***Science Robotics**, 2022*

<a href="https://github.com/ZJU-FAST-Lab/EGO-Planner-v2"><img alt="Code" src="https://img.shields.io/github/stars/ZJU-FAST-Lab/EGO-Planner-v2"/></a>
<a href="https://www.youtube.com/watch?v=L0fJ0EHHfOA&list=PLa8ny3vRw76nN8ZoaNABTGtB67PXRbBTQ"> <img alt="Youtube" src="https://img.shields.io/badge/Video-YouTube-red"></a>
<a href="https://www.bilibili.com/video/BV1pv4y1K7zS/"> <img alt="Bilibili" src="https://img.shields.io/badge/Video-Bilibili-FF3676"></a>
</div>
</div>


<!-- TIM 2022 - Event-VPR -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIM</div><img src='images/papers/TIM2022-EventVPR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Event-VPR: End-to-End Weakly Supervised Deep Network Architecture for Visual Place Recognition Using Event-Based Vision Sensor](https://www.science.org/doi/abs/10.1126/scirobotics.abm5954)

Delei Kong, Zheng Fang, Kuanxu Hou, **Haojia Li**, Junjie Jiang, Sonya Coleman, Dermot Kerr

*IEEE Transactions on Instrumentation and Measurement (**TIM**), 2022*

<a href="https://www.youtube.com/watch?v=pcu1l8Wdc7g"> <img alt="Youtube" src="https://img.shields.io/badge/Video-YouTube-red"></a>
</div>
</div>

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards

- 2021 Outstanding Graduate in Liaoning Province (**Top 3%**) 
- 2021 Best Thesis, Northeastern University (**Top 3%**)
- 2020 National Scholarship, China
- 2020 President Medal, Northeastern University (Only 10 Persons)
- 2019 **National 1st Prize** in the National Undergraduate Electronic Design Contest, China
- 2019 **National 1st Prize** in the National Undergraduate Smart Car Contest, China
- 2019 National 2nd Prize in the China Robot Competition, China

# 📖 Educations
- *2021.09 - Present*, **Ph.D. Candidate**, Electronic and Computer Engineering (ECE), The Hong Kong University of Science and technology (**HKUST**),  Supervisor: Prof. Shaojie Shen
- *2017.09 - 2021.06*, **B.Eng**, Robot Engineering, Northeastern University (**NEU**), Supervisor: Prof. Shiguang Wen

<!-- # 💬 Invited Talks -->

# 💻 Internships
- *2023.5 - 2024.9*, Algorithm Engineer (Vehicle Mounted Drones), DJI Automotive, China