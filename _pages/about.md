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
[1] [Neural operator feedback for a first-order PIDE with spatially-varying state delay](https://ieeexplore.ieee.org/document/11180047), Jie Qi\*, Jiaqi Hu, Jing Zhang, Miroslav Krstic. **IEEE Transactions on Automatic Control**, 2025, online, DOI: 10.1109/TAC.2025.3614407

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