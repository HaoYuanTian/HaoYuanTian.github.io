---
# 页面路径设置
permalink: /
# 页面标题（若为空，页面不显示标题）
title: ""
# 页面摘要（用于 SEO/摘要）
excerpt: ""
# 是否显示侧栏作者卡片
author_profile: true
# 旧链接重定向
redirect_from: 
  - /about/
  - /about.html
---

<!-- 下面这段用于生成 Google Scholar 引用统计的徽章数据地址 -->
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<!-- 锚点：用于顶部导航跳转到首页内容 -->
<span class='anchor' id='about-me'></span>

<!-- 个人简介正文（可替换为你的介绍） -->
I am a Professor with the School of Information and Intelligent Science, Donghua University, China. I received the B.Eng. degree in 2000 and the Ph.D. degree in 2005 from Northeastern University (China). I was a Visiting Scholar at the Cymer Center for Control Systems and Dynamics, University of California, San Diego, from March 2013 to February 2014 and from June to September 2015; a Visiting Scholar with the Department of Chemical and Materials Engineering, University of Alberta, from January 2019 to January 2020; and an Academic Visitor at the Mathematical Institute, University of Oxford, from September 2023 to September 2024. I currently serve as an Associate Editor for Systems & Control Letters. I am also a member of the Teaching Committee of the Chinese Association of Automation, an Executive Council Member of the Shanghai Association of Automation, and a Council Member of the Shanghai Association of Systems Simulation. I have received the Baosteel Excellent Teacher Award and the Shanghai Young Talents Award.

<!-- 研究兴趣与引用统计展示 -->
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->
My research interests include control and estimation of partial differential equations, control of time-delay systems, learning-based control for PDE systems, and their applications in multi-agent systems and industrial production processes.


<!-- 动态/新闻
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- 论文列表 -->
# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<!-- 简要论文条目 -->
<!-- 格式说明：[论文标题](链接), 作者, 期刊/会议, 年份, 状态/卷期, DOI -->
- [Neural operator feedback for a first-order PIDE with spatially-varying state delay](LINK_HERE), Jie Qi\*, Jiaqi Hu, Jing Zhang, Miroslav Krstic. **IEEE Transactions on Automatic Control**, 2025, online, DOI: 10.1109/TAC.2025.3614407
- [Optimal experimental design for parameter estimation in the presence of observation noise](LINK_HERE), Jie Qi\*, Ruth E. Baker. **Mathematical Biosciences**, 2026, 392: 109571.
- [Observer-based adaptive tracking control for unmanned surface vehicles under actuator saturation in high sea states](LINK_HERE), Hang Zou, Jie Qi\*, Nailong Wu. **Ocean Engineering**, 2025, 340: 122352.
- [Delay-adaptive Compensation for 3-D Formation Control of Leader-Actuated Multi-agent Systems](LINK_HERE), Shanshan Wang, Mamadou Diagne, and Jie Qi\*. **Automatica**, 2024, 164: 111645.
- [Robustness of Reaction-Diffusion PDEs Predictor-Feedback to Stochastic Delay Perturbations](LINK_HERE), Dandan Guan, Jie Qi, Mamadou Diagne\*. **Automatica**, 2024, 167: 111784, regular paper.
- [Multi-agent Deployment in 3-D via Reaction-Diffusion System with Radially-varying Reaction](LINK_HERE), Jing Zhang, Rafeal Vazquez\*, Jie Qi, Miroslav Krstic. **Automatica**, 2024, 161: 111491, regular paper.
- [Neural Operators for PDE Backstepping Control of First-Order Hyperbolic PIDE with Recycle and Delay](LINK_HERE), Jie Qi\*, Jing Zhang, Miroslav Krstic. **Systems & Control Letters**, 2024, 185: 105714.
- [Delay-adaptive Control of First-order Hyperbolic Partial Integro-differential Equations](LINK_HERE), Shanshan Wang, Jie Qi\*, Miroslav Krstic. **International Journal of Robust and Nonlinear Control**, 2024, 34(10): 6784-6803.
- [Proximal Policy Optimization Learning Based Control of Congested Freeway Traffic](LINK_HERE), Shurong Mo, Nailong Wu\*, Jie Qi, et al. **Optimal Control Applications and Methods**, 2024, 45(2): 719-736.
- [Delay-Compensated Distributed PDE Control of Traffic with Connected/Automated Vehicles](LINK_HERE), Jie Qi\*, Shurong Mo, Miroslav Krstic. **IEEE Transaction on Automatic Control**, 2023, 68(4): 2229-2244, full paper.
- [Robust Stabilization of 2x2 First-order Hyperbolic PDEs with Uncertain Input Delay](LINK_HERE), Jing Zhang, Jie Qi\*. **Automatica**, 2023, 157: 111235.
- [Bilateral Boundary Control of an Input Delayed 2-D Reaction-Diffusion Equation](LINK_HERE), Dandan Guan, Yanmei Chen, Jie Qi\*, Linglong Du. **Automatica**, 2023, 157: 111242.
- [Kernel Well-posedness and Computation by Power Series in Backstepping Output Feedback for Radially-dependent Reaction-Diffusion PDEs on Multidimensional Balls](LINK_HERE), Vazquez, Rafael\*, Jing Zhang, Jie Qi, Miroslav Krstic. **Systems & Control Letters**, 2023, 177: 105538.
- [Delay-Adaptive Predictor Feedback Control of Reaction-Advection-Diffusion PDEs with a Delayed Distributed Input](LINK_HERE), Shanshan Wang, Mamadou Diagne, Jie Qi\*. **IEEE Transactions on Automatic Control**, 2022, 67(7): 3762-3769.
- [Radially Varying Delay-compensated Distributed Control of Reaction-Diffusion PDEs on n-ball under Revolution Symmetry Conditions](LINK_HERE), Dandan Guan, Jie Qi\*. **International Journal of Robust and Nonlinear Control**, 2022, 32(15): 8421-8450.
- [Output Regulation for a First-Order Hyperbolic PIDE with State and Sensor delays](LINK_HERE), Jing Zhang, Jie Qi\*, Stevan Dubljevic, Bo Shen. **European Journal of Control**, 2022, 65: 100643.
- [Stubborn State Estimation for Nonlinear Distributed Parameter Systems Subject to Measurement Outliers](LINK_HERE), Jie Sun, Bo Shen\*, Jie Qi, Yufei Liu. **International Journal of Robust and Nonlinear Control**, 2022, 32(1): 13-28.
- [Compensation of Spatially-Varying Input Delay in Distributed Control of Reaction-Diffusion PDEs](LINK_HERE), Jie Qi\*, Miroslav Krstic. **IEEE Transaction on Automatic Control**, 2021, 66(9): 4069-4083, full paper.
- [Output Feedback Compensation to State and Measurement Delays for a First-order Hyperbolic PIDE with Recycle](LINK_HERE), Jie Qi, Stevan Dubljevic\*, Weijian Kong. **Automatica**, 2021, 128(6): 109565.
- [Adaptive Boundary Control of Reaction-Diffusion PDEs with Unknown Input Delay](LINK_HERE), Shanshan Wang, Jie Qi, Mamadou Diagne\*. **Automatica**, 2021, 134: 109909, regular paper.
- [Compensation of Spatially-Varying State Delay for a First-Order Hyperbolic PIDE using Boundary Control](LINK_HERE), Jing Zhang, Jie Qi\*. **Systems & Control Letters**, 2021, 157(11): 105050.
- [Control of Multi-Agent Systems with Input Delay via PDE-based Method](LINK_HERE), Jie Qi, Shanshan Wang, Jianan Fang, Mamadou Diagne\*. **Automatica**, 2019, 161(3): 91-100.
- [Stabilization of Reaction-Diffusions PDE with Delayed Distributed Actuation](LINK_HERE), Jie Qi\*, Miroslav Krstic, Shanshan Wang. **Systems & Control Letters**, 2019, 133: 104558.
- [Parabolic PDE-based Multi-Agent Formation Control on a Cylindrical Surface](LINK_HERE), Jie Qi, Shuxia Tang\* and Chuan Wang. **International Journal of Control**, 2019, 92(1): 77-99.
- [Wave Equation-based Time-varying Formation Control of Multiagent Systems](LINK_HERE), Jie Qi\*, Jing Zhang, Yongsheng Ding. **IEEE Transactions on Control Systems Technology**, 2018, 26(5): 1578-1591.
- [Multi-agent Deployment in 3-D via PDE Control](LINK_HERE), Jie Qi\*, Rafael Vazquez, Miroslav Krstic. **IEEE Transaction on Automatic Control**, 2015, 60(4): 891-906, full paper.

* Corresponding author

<!-- 荣誉与奖项 -->
# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

<!-- 教育经历 -->
# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

<!-- 邀请报告 -->
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

<!-- 实习经历 -->
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.