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
She is a professor at Donghua University and a Ph.D. supervisor. She is a member of the Faculty Working Committee of the Chinese Association of Automation, an Executive Council Member of the Shanghai Association of Automation, and a Council Member of the Shanghai Society for System Simulation. She serves as an Editorial Board Member of international journals including Systems & Control Letters.

Her research interests include control and estimation of partial differential equations, control of time-delay systems, control of time-delay systems, learning-based control for PDE systems, and their applications in multi-agent systems and industrial production processes.


<!-- 锚点：用于顶部导航跳转到首页内容 -->
<span class='anchor' id='educations'></span>

<!-- 教育经历 -->
# 📖 Educations
- **PhD. of Engineering**, March 2005<br>
  Systems Engineering, Institute of Systems Engineering, Northeastern University, China<br>
  Thesis: "The dynamics analysis and optimization of a class of advertisement models and its applications"<br>
  Advisor: Prof. Wang, Dingwei
- **Bachelor of Engineering**, Automation, July 2000<br>
  Dept. of Automation, Northeastern University, China


<span class='anchor' id='professional-experiences'></span>

<!-- 职业经历 -->
# 💼 Professional Experiences
- **Sep. 2016 to present**, Professor<br>
  Department of Automation, School of Information and Intelligent Science, Donghua University, Shanghai, China
- **September 2023 to September 2024**, Academic Visitor<br>
  Mathematical Institute, University of Oxford, UK, with Prof. Ruth Baker
- **January 2019 to January 2020**, Visiting Scholar<br>
  Chemical & Materials Engineering Department, Donadeo Innovation Center for Engineering, University of Alberta, Canada, with Prof. Stevan Dubljevic
- **June 2015 to September 2015**, Visiting Scholar<br>
  Department of Mechanical and Aerospace Engineering, University of California, San Diego, USA, with Prof. Miroslav Krstic
- **March 2013 to February 2014**, Visiting Scholar<br>
  Department of Mechanical and Aerospace Engineering, University of California, San Diego, USA, with Prof. Miroslav Krstic
- **September 2008 to August 2016**, Associate Professor<br>
  Department of Automation, College of Information Science and Technology, Donghua University, Shanghai, China
- **March 2007 to March 2008**, Research Assistant<br>
  Institute of Textiles & Clothing, The Hong Kong Polytechnic University, Hong Kong, with Prof. Wai-Keung Wong
- **July 2005 to August 2008**, Lecture<br>
  Department of Automation, College of Information Science and Technology, Donghua University, Shanghai, China


<span class='anchor' id='publications'></span>

<!-- 论文列表 -->
# 📝 Selected publications

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
- Jie Qi\*, Jiaqi Hu, Jing Zhang, Miroslav Krstic. [Neural operator feedback for a first-order PIDE with spatially-varying state delay](https://ieeexplore.ieee.org/document/11180047). **IEEE Transactions on Automatic Control**, 2025, online, DOI: 10.1109/TAC.2025.3614407
- Jie Qi\*, Ruth E. Baker. [Optimal experimental design for parameter estimation in the presence of observation noise](https://www.sciencedirect.com/science/article/abs/pii/S002555642500197X). **Mathematical Biosciences**, 2026, 392: 109571.
- Hang Zou, Jie Qi\*, Nailong Wu. [Observer-based adaptive tracking control for unmanned surface vehicles under actuator saturation in high sea states](https://www.sciencedirect.com/science/article/abs/pii/S0029801825020360). **Ocean Engineering**, 2025, 340: 122352.
- Shanshan Wang, Mamadou Diagne, and Jie Qi\*. [Delay-adaptive Compensation for 3-D Formation Control of Leader-Actuated Multi-agent Systems](https://www.sciencedirect.com/science/article/abs/pii/S0005109824001389). **Automatica**, 2024, 164: 111645.
- Dandan Guan, Jie Qi, Mamadou Diagne\*. [Robustness of Reaction-Diffusion PDEs Predictor-Feedback to Stochastic Delay Perturbations](https://www.sciencedirect.com/science/article/abs/pii/S0005109824002784). **Automatica**, 2024, 167: 111784, regular paper.
- Jing Zhang, Rafeal Vazquez\*, Jie Qi, Miroslav Krstic. [Multi-agent Deployment in 3-D via Reaction-Diffusion System with Radially-varying Reaction](https://www.sciencedirect.com/science/article/pii/S000510982300660X). **Automatica**, 2024, 161: 111491, regular paper.
- Jie Qi\*, Jing Zhang, Miroslav Krstic. [Neural Operators for PDE Backstepping Control of First-Order Hyperbolic PIDE with Recycle and Delay](https://www.sciencedirect.com/science/article/abs/pii/S0167691124000021). **Systems & Control Letters**, 2024, 185: 105714.
- Shanshan Wang, Jie Qi\*, Miroslav Krstic. [Delay-adaptive Control of First-order Hyperbolic Partial Integro-differential Equations](https://onlinelibrary.wiley.com/doi/abs/10.1002/rnc.7257). **International Journal of Robust and Nonlinear Control**, 2024, 34(10): 6784-6803.
- Shurong Mo, Nailong Wu\*, Jie Qi, et al. [Proximal Policy Optimization Learning Based Control of Congested Freeway Traffic](https://onlinelibrary.wiley.com/doi/abs/10.1002/oca.3068). **Optimal Control Applications and Methods**, 2024, 45(2): 719-736.
- Jie Qi\*, Shurong Mo, Miroslav Krstic. [Delay-Compensated Distributed PDE Control of Traffic with Connected/Automated Vehicles](https://ieeexplore.ieee.org/document/9772310). **IEEE Transaction on Automatic Control**, 2023, 68(4): 2229-2244, full paper.
- Jing Zhang, Jie Qi\*. [Robust Stabilization of 2x2 First-order Hyperbolic PDEs with Uncertain Input Delay](https://www.sciencedirect.com/science/article/abs/pii/S0005109823003965). **Automatica**, 2023, 157: 111235.
- Dandan Guan, Yanmei Chen, Jie Qi\*, Linglong Du. [Bilateral Boundary Control of an Input Delayed 2-D Reaction-Diffusion Equation](https://www.sciencedirect.com/science/article/abs/pii/S000510982300403X). **Automatica**, 2023, 157: 111242.
- Vazquez, Rafael\*, Jing Zhang, Jie Qi, Miroslav Krstic. [Kernel Well-posedness and Computation by Power Series in Backstepping Output Feedback for Radially-dependent Reaction-Diffusion PDEs on Multidimensional Balls](https://www.sciencedirect.com/science/article/pii/S0167691123000853). **Systems & Control Letters**, 2023, 177: 105538.
- Shanshan Wang, Mamadou Diagne, Jie Qi\*. [Delay-Adaptive Predictor Feedback Control of Reaction-Advection-Diffusion PDEs with a Delayed Distributed Input](https://ieeexplore.ieee.org/document/9528941). **IEEE Transactions on Automatic Control**, 2022, 67(7): 3762-3769.
- Dandan Guan, Jie Qi\*. [Radially Varying Delay-compensated Distributed Control of Reaction-Diffusion PDEs on n-ball under Revolution Symmetry Conditions](https://onlinelibrary.wiley.com/doi/abs/10.1002/rnc.6293). **International Journal of Robust and Nonlinear Control**, 2022, 32(15): 8421-8450.
- Jing Zhang, Jie Qi\*, Stevan Dubljevic, Bo Shen. [Output Regulation for a First-Order Hyperbolic PIDE with State and Sensor delays](https://www.sciencedirect.com/science/article/abs/pii/S094735802200036X). **European Journal of Control**, 2022, 65: 100643.
- Jie Sun, Bo Shen\*, Jie Qi, Yufei Liu. [Stubborn State Estimation for Nonlinear Distributed Parameter Systems Subject to Measurement Outliers](https://onlinelibrary.wiley.com/doi/abs/10.1002/rnc.5801). **International Journal of Robust and Nonlinear Control**, 2022, 32(1): 13-28.
- Jie Qi\*, Miroslav Krstic. [Compensation of Spatially-Varying Input Delay in Distributed Control of Reaction-Diffusion PDEs](https://ieeexplore.ieee.org/document/9209093). **IEEE Transaction on Automatic Control**, 2021, 66(9): 4069-4083, full paper.
- Jie Qi, Stevan Dubljevic\*, Weijian Kong. [Output Feedback Compensation to State and Measurement Delays for a First-order Hyperbolic PIDE with Recycle](https://www.sciencedirect.com/science/article/abs/pii/S0005109821000856). **Automatica**, 2021, 128(6): 109565.
- Shanshan Wang, Jie Qi, Mamadou Diagne\*. [Adaptive Boundary Control of Reaction-Diffusion PDEs with Unknown Input Delay](https://academic.oup.com/imamci/article-abstract/42/4/dnaf034/8303977?redirectedFrom=fulltext). **Automatica**, 2021, 134: 109909, regular paper.
- Jing Zhang, Jie Qi\*. [Compensation of Spatially-Varying State Delay for a First-Order Hyperbolic PIDE using Boundary Control](https://www.sciencedirect.com/science/article/abs/pii/S0167691121001808). **Systems & Control Letters**, 2021, 157(11): 105050.
- Jie Qi, Shanshan Wang, Jianan Fang, Mamadou Diagne\*. [Control of Multi-Agent Systems with Input Delay via PDE-based Method](https://www.sciencedirect.com/science/article/abs/pii/S000510981930192X). **Automatica**, 2019, 161(3): 91-100.
- Jie Qi\*, Miroslav Krstic, Shanshan Wang. [Stabilization of Reaction-Diffusions PDE with Delayed Distributed Actuation](https://www.sciencedirect.com/science/article/abs/pii/S0167691119301689). **Systems & Control Letters**, 2019, 133: 104558.
- Jie Qi, Shuxia Tang\* and Chuan Wang. [Parabolic PDE-based Multi-Agent Formation Control on a Cylindrical Surface](https://www.tandfonline.com/doi/full/10.1080/00207179.2017.1308556). **International Journal of Control**, 2019, 92(1): 77-99.
- Jie Qi\*, Jing Zhang, Yongsheng Ding. [Wave Equation-based Time-varying Formation Control of Multiagent Systems](https://ieeexplore.ieee.org/document/8125141). **IEEE Transactions on Control Systems Technology**, 2018, 26(5): 1578-1591.
- Jie Qi\*, Rafael Vazquez, Miroslav Krstic. [Multi-agent Deployment in 3-D via PDE Control](https://ieeexplore.ieee.org/document/6914569). **IEEE Transaction on Automatic Control**, 2015, 60(4): 891-906, full paper.

\* Corresponding author


<span class='anchor' id='invited-talks'></span>

<!-- 邀请报告 -->
# 💬 Invited Talks
- *2025.06*, Keynote talk at the 5th IFAC Workshop on Control of Systems Governed by Partial Differential Equations: "Backstepping Control Design for PDE Systems with Different Delay Forms".
- *2024.11*, Keynote talk at the 3rd International Symposium on Computing and Artificial Intelligence: "Large-Scale Multi-Agent Control via a PDE-Based Approach".


<span class='anchor' id='honors-and-awards'></span>

<!-- 荣誉与奖项 -->
# 🎖 Honors and Awards
<!-- - *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- *2025* Songjiang District High-Level Talent Program (Shanghai)
- *2017* Baosteel Excellent Teacher Award
- *2013* Twelfth Shanghai Outstanding Youth Post Expert.
- *2010* Donghua University the First Prize in the Lectures Contest.
- *2009* Shanghai Excellent Instructor of the Mathematical Contest in Modeling.
- *2008* Dawn of the Shanghai Scholar. 


<span class='anchor' id='research-works'></span>

<!-- 科研项目 -->
# 🔬 Research Works
**Main Projects:**
- Project 1: Control of Several Classes of Distributed Parameter Systems with Spatially-Varying Delays. National Natural Science Foundation of China (NSFC), 62173084, 2022.1-2025.12, Principal Investigator.
- Project 2: Reinforcement Learning based Control of the Melt Spinning Forming Process for Polyamide Fiber. Shanghai Natural Science Foundation, 23ZR1401800, 2023.4-2026.3, Principal Investigator.
- Project 3: PDE-Based Modeling and Formation Control for Large Scale Collective Systems with Time-Delay and Time-Varying. National Natural Science Foundation of China (NSFC), 61773112, 2018.1-2021.12, Principal Investigator.


<span class='anchor' id='teaching'></span>

<!-- 教学 -->
# 📚 Teaching
- Automation Control Theory, Undergraduate, Spring 05, 06, 08-11, 12-18, 20-23, 25-
- Mathematical modeling and Mathematical experiments, Undergraduate, Fall 05, 06, 08-18, 20
- Modern Control Theory, Graduated, Spring 09, 11, 12, 15, 25
- Special topics in theory and technology of complex system modeling, Graduated, Fall 15-18, 20-23, 25-


<!-- 办公地址（备注） -->
### Office Address
<i class="fas fa-map-marker-alt"></i> Building 2, Room 2221, No 2999 North Renmin Road, Songjiang, Shanghai, China