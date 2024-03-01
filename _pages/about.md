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

I'm Yangxintong Lyu, a last-year Ph.D. student in Vrije Universiteit Brussel supervised by [Prof. Adrian Munteanu](https://www.etrovub.be/people/member/about-bio/acmuntea/). I also work closely with [Ir. Remco Royen](https://remcoroyen.github.io/) and [Dr. Ionut Schiopu](https://www.linkedin.com/in/ionutschiopu/?originalSubdomain=fi).

My research interests include but not limited to deep learning, object pose estimation, image semantic segmentation, 2D/3D vision, and domain adaptation. During my Ph.D., my research mainly focus on deep learning based multi-modal scene understanding for traffic camera. 

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<span class='anchor' id='educations'></span>
# 📖 Educations
- *2019.07 - 2024.09 (expected)*, Vrije Universiteit Brussel, Ph.D..
- *2016.09 - 2018.06*, Vrije Universiteit Brussel, Master. 
- *2013.08 - 2017.06*, Xidian University, Bachelor.

<span class='anchor' id='experience'></span>
# 🧗🏻‍♀️ Experience
- *2018.08 - 2019.05*, R&D Engineer, FABU Technology Co. Ltd.. 
- *2017.06 - 2018.06*, Student research assistant, Vrije Universiteit Brussel.

<span class='anchor' id='publications'></span>
# 📝 Publications 

<!-- W6DNet -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIM 2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box'><div class='paper-box-image'><div style="height: 300px; width: 500px;"><div class="badge">TIM 2024</div><img src='images/pubs/w6dnet/pipeline.png' onmouseout="this.src='images/pubs/w6dnet/pipeline.png';" onmouseover="this.src='images/pubs/w6dnet/dataset.png';" alt="sym" style="height: auto; width: 100%;" object-fit="contain"></div></div>
<div class='paper-box-text' markdown="1">

**W6DNet: Weakly-supervised Domain Adaptation for Monocular Vehicle 6D Pose Estimation with 3D Priors and Synthetic Data**

**Yangxintong Lyu**, Remco Royen, Adrian Munteanu

*IEEE Transactions on Instrumentation and Measurement*

[**Code**]()|[**Paper**](https://ieeexplore.ieee.org/abstract/document/10443331)
</div>
</div>

<!-- Mono6D -->
<div class='paper-box'><div class='paper-box-image'><div style="height: 300px; width: 500px;"><div class="badge">ICIP 2022</div><img src='images/pubs/mono6d/pipeline.png' onmouseout="this.src='images/pubs/mono6d/pipeline.png';" onmouseover="this.src='images/pubs/mono6d/vis_results.png';" alt="sym" style="height: 100%; width: auto;" object-fit="contain"></div></div>
<div class='paper-box-text' markdown="1">

**Mono6D: Monocular vehicle 6D pose estimation with 3D priors**

**Yangxintong Lyu**, Remco Royen, Adrian Munteanu

*IEEE International Conference on Image Processing (ICIP)*

[**Paper**](https://ieeexplore.ieee.org/abstract/document/9897311/)
</div>
</div>

<!-- RGBT -->
<div class='paper-box'><div class='paper-box-image'><div style="height: 300px; width: 500px;"><div class="badge">IET Letters</div><img src='images/pubs/rgbt/pipeline.png' onmouseout="this.src='images/pubs/rgbt/pipeline.png';" onmouseover="this.src='images/pubs/rgbt/vis_result.png';" alt="sym" style="height: 100%; width: auto;" object-fit="contain"></div></div>
<div class='paper-box-text' markdown="1">

**Multi-modal neural networks with multi-scale RGB-T fusion for semantic segmentation**

**Yangxintong Lyu**, Ionut Schiopu, Adrian Munteanu

*IET Electronics Letters*

[**Paper**](https://ietresearch.onlinelibrary.wiley.com/doi/abs/10.1049/el.2020.1635)
</div>
</div>

<!-- Curved -->
<div class='paper-box'><div class='paper-box-image'><div style="height: 300px; width: 500px;"><div class="badge">SPIC 2019</div><img src='images/pubs/curved/vr_setting.jpg' onmouseout="this.src='images/pubs/curved/vr_setting.jpg';" onmouseover="this.src='images/pubs/curved/curved_surface.png';" alt="sym" style="height: 100%; width: auto;" object-fit="contain"></div></div>
<div class='paper-box-text' markdown="1">

**Consistent video projection on curved displays**

**Yangxintong Lyu**, Shao-Ping Lu, Quentin Bolsee, Adrian Munteanu

*Elsvier Signal Processing: Image Communication*

[**Paper**](https://www.sciencedirect.com/science/article/pii/S0923596518309457)
</div>
</div>

<!-- VMMR -->
<div class='paper-box'><div class='paper-box-image'><div style="height: 300px; width: 500px;"><div class="badge">Sensors 2022</div><img src='images/pubs/vmmr/pipeline.png' onmouseout="this.src='images/pubs/vmmr/pipeline.png';" onmouseover="this.src='images/pubs/vmmr/vis_result.png';" alt="sym" style="height: auto; width: 100%;" object-fit="contain"></div></div>
<div class='paper-box-text' markdown="1">

**Framework for Vehicle Make and Model Recognition—A New Large-Scale Dataset and an Efficient Two-Branch–Two-Stage Deep Learning Architecture**

**Yangxintong Lyu**, Ionut Schiopu, Bruno Cornelis, Adrian Munteanu

*MDPI Sensors*

[**Paper**](https://www.mdpi.com/1424-8220/22/21/8439)
</div>
</div>
<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**  -->

- [Mono6D++: Learning Point Cloud Visibility for 3D Prior-based Vehicle 6D Pose Estimation](https://ieeexplore.ieee.org/abstract/document/10323075/), **Yangxintong Lyu**, Olivier Ducastel, Remco Royen, Adrian Munteanu, *11th European Workshop on Visual Information Processing (EUVIP) 2023*

- [Occlusion-Aware 3D Priors for Deep Learning-Based Applications](https://ieeexplore.ieee.org/abstract/document/10337644/), Olivier Ducastel, **Yangxintong Lyu**, Leon Denis, Adrian Munteanu, *IEEE International Workshop on Multimedia Signal Processing (MMSP) 2023*

<span class='anchor' id='hornors-and-awards'></span>
# 🎖 Honors and Awards
- *National Scholarship*, awarded by the Chinese Ministry of Education (*top 1%*). 
- The 3rd prize in Shaanxi province, ACM/ICPC. 
- The 2nd prize in Shaanxi province, Contemporary Undergraduate Mathematical Contest in Modeling.

<span class='anchor' id='services'></span>
# 🌟 Services
- *Reviewer*: IEEE TIP (IF: 10.8), EAAI (IF: 8.0), CVPR and ICIP.
- *Teaching assistant (2020 - now)*: Image Processing.
- *Co-supervisor*: 4 master theses.

<div align="right">Thanks for the template from <a href="https://github.com/RayeRen/acad-homepage.github.io">Yi Ren</a>.</div>


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->