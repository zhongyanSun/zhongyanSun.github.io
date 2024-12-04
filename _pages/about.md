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

# 💬 About Me
- 本人本科毕业于南开大学人工智能学院自动化专业，大四保研进入南开大学机器人智能感知与协同控制实验室后开始进行机器人SLAM方向的学习与研究。本人掌握 C++、Python 等编程语言，熟悉Linux系统，具有ROS框架开发经验；具有IMU、激光雷达、热成像与可见光相机等传感器调试、标定以及多传感器融合SLAM算法开发经验；熟悉四足机器人、移动机器人、无人机等机器人平台；参与过多项国家级项目以及横向项目，积累了机器人平台部署以及算法设计的经验。
- 本人的学习主要围绕热成像与可见光跨光谱视觉多传感器融合的主题展开，开展了如**传感器标定、跨光谱图像配准、跨光谱多传感器融合里程计**等工作。整体的研究如下图所示：
<img src='images/关键技术体系.png' alt="sym" style="max-width: 100%; height: auto;">


<span class='anchor' id='-projects'></span>

# 🔥 Projects
- *2022.09至今*: **国家自然科学基金区域创新发展联合基金重点项目**:可视度受限环境下跨光谱多传感信息融合的机器人语义感知与交互协作. 负责**可视度受限环境下的跨光谱视觉-惯导-激光雷达传感器融合的机器人SLAM**工作
- 跨光谱视觉-惯导-激光雷达传感器融合SLAM框架：
<img src='images/VTIO流程图.png' alt="sym" style="max-width: 100%; height: auto;">
- 在天津市陈塘热电厂利用四足机器人(unitree A1)和移动机器人(husky)平台采集数据测试效果如下：
<div style="display: flex;">
    <img src='images/狗室外 00_00_00-00_00_42.gif' alt="sym" style="max-width: 50%; height: auto;">
    <img src='images/husky-indoor1 00_00_00-00_00_40.gif' alt="sym" style="max-width: 50%; height: auto;">
</div>
<img src='images/dog-indoor-LVTI.gif' alt="sym" style="max-width: 100%; height: auto;">

- 四足机器人平台的搭建与传感器标定（独立完成）
  <img src='images/四足平台.png' alt="sym" style="max-width: 50%; height: auto;">


<span class='anchor' id='-publications'></span>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCC 2023</div><img src='images/陪准.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RGB-T Cross-Modal Image Registration Fusing Global Structure and Local Mutual Information](https://ieeexplore.ieee.org/document/10241056)

**Zhongyan Sun**, Jing Yuan

[**Project**](https://scholar.google.com.hk/citations?view_op=view_citation&hl=zh-CN&user=YtIR4HoAAAAJ&citation_for_view=YtIR4HoAAAAJ:u-x6o8ySG0sC)
- This paper proposes an RGB and thermal (RGB-T) image registration method that combines global structure with local mutual information, called GSLMI 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RICAI 2023</div><img src='images/TIO流程图.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Thermal image based direct method visual-inertial odometry for robot navigation](https://ieeexplore.ieee.org/document/10488925)

**Zhongyan Sun**, Jing Yuan, Yang Wang, Guanming Qu, Hongzhi Yu

[**Project**](https://scholar.google.com.hk/citations?view_op=view_citation&hl=zh-CN&user=YtIR4HoAAAAJ&citation_for_view=YtIR4HoAAAAJ:d1gkVwhDpl0C)
- This paper proposes a thermal visual and IMU sensors tightly-coupled visualinertial odometry based on a direct method optimization framework, which is immune to illumination conditions and visual occlusions.
</div>
</div>

- [A 3 RGB-D SLAM: Active RGB-D SLAM with Active Exploration, Adaptive TEB and Active Loop Closure](https://ieeexplore.ieee.org/abstract/document/10240308), Shuhao Zhu, Xingyu Sun, **Zhongyan Sun**, **CCC 2023**
  
- 一篇IEEE Trans论文在撰写

<span class='anchor' id='-honors-and-awards'></span>
# 🎖 Honors and Awards
- *2017.09* 全国中学生物理竞赛三等奖.
- *2020.10* 南开大学国家励志奖学金. 
- *2021.09* 天津津航技术物理研究所暑期实训项目优秀实训证书.
- *2022.09* 南开大学研究生推免生奖学金.
- *2023.10* 南开大学公能奖学金.
- *2023.12* 第五届机器人、智能控制与人工智能国际学术会议海报证书.
- *2024.07* 招商银行天津分行金融科技训练营认证证书.
- *2024.09* 中国移动杭州研发中心优秀实习证书.
- 大学英语四/六级证书（CET-4/6）.
- 国家普通话一级乙等证书.

<span class='anchor' id='-educations'></span>
# 📖 Educations
- *2022.09 - 2025.07*, 南开大学人工智能学院 控制工程 **(研究生)** 排名top10%  可信行为智能算法与系统教育部工程研究中心. 
- *2018.08 - 2022.07*, 南开大学人工智能学院 自动化 **(本科)**  排名top10%    南开大学机器人智能感知与协同控制实验室. 


<span class='anchor' id='-internships'></span>
# 💻 Internships
- *2021.07 - 2021.09*, [天津津航技术物理研究所暑期实习](https://ai.nankai.edu.cn/info/1018/4339.htm)**(央企)**.
参与‘多源信息融合目标识别’科研课题，完成文献调研、代码实现与部署、算法改进等工作；实习评定为优秀.
- *2024.06 - 2024.07*, 招商银行天津分行信息技术部 **(国企)** -金融科技实习生. 参与招商银行天津分行金融科技项目，协助开发人员进行代码开发、测试优化、运行维护等金融科技业务.
- *2024.07 - 2024.09*, 中国移动杭州研发中心 **(央企)** -机器人研发实习生，参与‘基于ROS的移动机器人VSLAM的研究与实现’课题，对机器人的定位、具身智能算法进行前沿性探索.
