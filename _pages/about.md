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

<!--
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

Hi! I'm Tianfu LI (李天夫), currently pursuing a M.Phil. degree in ROBOTICS & AUTONOMOUS SYSTEMS at Hong Kong University of Science and Technology (Guangzhou), supervised by [Prof. Haoang LI (李昊昂)](https://sites.google.com/view/haoangli/homepage). My research sits in the broad field of Embodied AI and Robotics, with a particular focus on Vision-and-Language Navigation (VLN) and Robotic Manipulation - building intelligent systems that can perceive, reason, and act in complex real-world environments.

Beyond my academic research, I am an algorithm engineer intern at Knowin AI, where I work on developing advanced robotic manipulation algorithms, bridging the gap between high-level task understanding and low-level motor control. I am passionate about creating embodied agents that can seamlessly interact with humans and their surroundings through natural language instructions and visual perception.

<!--
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Vision-and-Language Navigation](https://tli794.github.io/homepage/)

**Preprint**

**Tianfu Li<sup>\*</sup>**, Wenbo Chen<sup>\*</sup>, Haoxuan Xu<sup>\*</sup>, et al.

<!--[**Project**](https://tli794.github.io/homepage/)--> <!--<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>-->
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

<!--
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->

# 🔭 Projects 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Group Project</div><img src='images/servicerobot2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Embodied AI-based Multi-terrain Service Robots with Dynamic SLAM and VLN](https://hkustgz-my.sharepoint.com/:v:/g/personal/tli794_connect_hkust-gz_edu_cn/IQDgJwFjAooCSo7sP3nDN0oJAW-Q2tHK82hu6SsTg-3mu2o?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=VJfYsC)

**Red Brid M.Phil. (RBM) Group Project**

- Proposed an embodied AI-based robotic system for autonomous daily service in dynamic indoor environments;
- Integrated semantic sence graphs with geometric maps;
- Devised object-oriented/language-guided navigation functions;
- Deployed this system on a real-world wheeled robot.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Group Project</div><img src='images/coastalrobot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Coastal Hydrological Monitoring Unmanned System](https://mp.weixin.qq.com/s/ZgVO-W9tWL1KAQG7vN-JXg)

**Red Brid Project**

- Participated in the development of the advanced “sea-land-air” collaborative unmanned monitoring system;
- Contributed to the VLN module for unmanned ground vehicles (UGV) serving as drone-delivery rovers.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Individual Project</div><img src='images/gesturerobot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Gesture Recognition for Robot Control under Optical Camera Communication Interference]()

**Bachelor’s Dissertation**

- Designed a style-transfer-based denoising pipeline using CycleGAN to isolate gesture data from noisy image matrices;
- Integrated Swin-Transformer to enhance spatial feature extraction and signal disentanglement;
- Deployed the model on ROS, with Qt-based visualization interface.
</div>
</div>

# 🎖 Honors and Awards
- Postgraduate Studentship (PGS) Award from Hong Kong University of Science and Technology (Guangzhou)
- Outstanding Bachelor’s Dissertation (Second Prize) of Sichuan University 
- Outstanding Graduate of Sichuan University
- Outstanding Undergraduate of Sichuan University
- Comprehensive Scholarship (Third Prize) from Sichuan University
- Individual Scholarship (First Prize) from Sichuan University
- Meritorious Winner in Mathematical Contest in Modeling by COMAP 

# 📖 Educations
- M.Phil. in Robotics and Automation Systems, **[Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/)**, China, *2024 - Present*
- B.Eng. in Computer Science and Technology, **[Sichuan University](https://en.scu.edu.cn/)**, China, *2020 - 2024* 

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

# 💻 Internships
- Algorithm Engineer for Robot Manipulation, **[Knowin AI](https://mp.weixin.qq.com/s/HTQM37HK87JvG75Ga801EA)**, Shenzhen, China, *Jan. 2026 - Present*
