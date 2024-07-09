---
layout: archive
title: ""
# permalink: /about/
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
  # - /
---






I am a third-year Ph.D. candidate in School of Geodesy and Geomatics at <strong>[Wuhan University](https://www.whu.edu.cn/)</strong>. I am very lucky to be supervised by [Prof. Jiancheng Li](https://hrold.whu.edu.cn/EN/Professors.htm) at Wuhan University. My research interests lie in 3D computer vision, Simultaneous Localization and Mapping (SLAM), Global Navigation Satellite System (GNSS) localization. I was a research intern at JingDong (JD.com, Inc). I got my Bechelor's Degree from [China University of Geosciences Beijing](https://www.cugb.edu.cn/) in 2018, and Master's Degree from [Wuhan University](https://www.whu.edu.cn/) supervised by [Prof. Jiancheng Li](https://hrold.whu.edu.cn/EN/Professors.htm) in 2021. 



News
======
<style>
  .news-container p {
    margin: 5px 0; /* 调整段落间距 */
    line-height: 1.2; /* 调整行高 */
  }

  .show-more-link {
    text-align: center;
    display: block;
    margin-top: 10px;
  }
</style>

<div class="news-container">
  <p>🚀 <span style="color: red;">[07.2024] One paper <a href="">URS-NeRF</a> is accepted at ECCV 2024!!</span></p>
  <p>😎 <span style="color: red;">[10.2023] Joined <a href="https://www.comp.nus.edu.sg/~leegh/">CVRP Lab</a> of NUS as a visiting student supervised by Gim Hee Lee!</span></p>
  <!-- <p>🚀 [08.2023] One paper <a href="https://ieeexplore.ieee.org/document/10154545">PVI-DSO</a> is accepted at IEEE Sensors Journal!</p> -->
  <p>🚀 [06.2023] One paper <a href="https://openaccess.thecvf.com/content/CVPR2023/papers/He_A_Rotation-Translation-Decoupled_Solution_for_Robust_and_Efficient_Visual-Inertial_Initialization_CVPR_2023_paper.pdf">DRT-VIO</a> is CVPR 2023!</p>
  <p>🚀 [06.2022] One paper <a href="https://link.springer.com/article/10.1007/s10291-023-01396-7">EDM Method</a> is accepted at GPS Solutions!</p>
  <p>🚀 [01.2022] One paper <a href="https://arxiv.org/pdf/2105.04064">PLS-VIO</a> is accepted at ICRA 2022 & RAL!</p>
  <div id="hidden-news" style="display: none;">
  <p>👨‍🎓 [07.2021] Awarded Outstanding Graduate in <a href="https://www.whu.edu.cn/">Wuhan University</a>!</p>
  <!-- <p>🚀 [09.2020] One paper <a href="https://www.mdpi.com/2072-4292/12/18/2901">IPL-VIO</a> is accepted at Remote Sensing!</p> -->
  <p>🙇 [09.2020] Joined <a href="https://corporate.jd.com/">JingDong</a> as a research intern!</p>
  <p>👨‍🎓 [07.2018] Awarded Outstanding Graduate in <a href="https://www.cugb.edu.cn/">China University of Geosciences Beijing</a>!</p>
  
  
  <!-- <p>🙇 [10.2019] Joined <a href="https://en.megvii.com/megvii_research">MEGVII Research</a> as a 3D vision research intern!</p> -->
  <!-- <p>🙇 [06.2019] Joined <a href="http://www.vie.group/team">VIE Lab</a> at PKU as a research intern!</p> -->
  <!-- <p>😎 [09.2017] Joined <a href="https://hc.buaa.edu.cn/">ShenYuan Honors College</a> at Beihang University as an undergraduate!</p> -->
  <!-- <p>👨‍🎓 [07.2017] Awarded Outstanding Graduate in <a href="http://www.szsy.cn/">SZSY High School</a>!</p> -->
    <!-- <p>🏆 [15.03.2024] Received the .</p> -->
    <!-- 你可以在这里添加更多隐藏的新闻项 -->
  </div>
</div>

<a href="#" class="show-more-link" id="show-more-link">⬇ SHOW MORE ⬇</a>

<script>
  document.getElementById('show-more-link').addEventListener('click', function(event) {
    event.preventDefault();
    var hiddenNews = document.getElementById('hidden-news');
    if (hiddenNews.style.display === 'none') {
      hiddenNews.style.display = 'block';
      this.textContent = '⬆ SHOW LESS ⬆';
    } else {
      hiddenNews.style.display = 'none';
      this.textContent = '⬇ SHOW MORE ⬇';
    }
  });
</script>



Featured Works
======


<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/TreeSBA.gif" alt="URS-NeRF: Unordered Rolling Shutter Bundle Adjustment for Neural Radiance Fields" style="width: 350px; height: auto; margin-right: 20px;">

  <div>
    <h3 style="margin: 0;"><a href="projects/URS-NeRF/" style="text-decoration: none;">URS-NeRF: Unordered Rolling Shutter Bundle Adjustment for Neural Radiance Fields</a></h3>
    <p style="margin: 5px 0;">
      <a href="https://boxuLibrary.github.io/"><strong>Bo Xu</strong></a>,,
      Ziao Liu,
      <a href="">Mengqi Guo</a>,
      Jiancheng Li,
      <a href="https://www.comp.nus.edu.sg/~leegh/">Gim Hee Lee</a>
      <br>
      ECCV, 2024<br>
      <a href="projects/URS-NeRF/" style="text-decoration: none;">[Project Page]</a>
      <!-- <a href="" style="text-decoration: none;">[PDF]</a>
      <a href="" style="text-decoration: none;">[Code]</a> -->
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/UNIKD.gif" alt="A Rotation-Translation-Decoupled Solution for Robust and Efficient
Visual-Inertial Initialization" style="width: 350px; height: auto; margin-right: 20px;">

  <div>
    <h3 style="margin: 0;"><a href="projects/DRTVIO/" style="text-decoration: none;">A Rotation-Translation-Decoupled Solution for Robust and Efficient
Visual-Inertial Initialization</a></h3>
    <p style="margin: 5px 0;">
      <a href="https://chaneyddtt.github.io/">Yijia He*</a>,
      <a href="https://boxuLibrary.github.io/"><strong>Bo Xu</strong>*</a>,
      <a href="https://hlinchen.github.io/">Zhanpeng Ouyang</a>,
      <a href="https://scholar.google.com.sg/citations?hl=zh-CN&user=Mq89JAcAAAAJ">Hongdong Li</a>
      <br>
      CVPR, 2023<br>
      <a href="projects/DRTVIO/" style="text-decoration: none;">[Project Page]</a>
      <!-- <a href="" style="text-decoration: none;">[PDF]</a>
      <a href="" style="text-decoration: none;">[Code]</a> -->
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/GNeSF.jpg" alt="A unified cycle-slip, multipath estimation, detection and mitigation method for VIO-aided PPP in urban environments" style="width: 350px; height: auto; margin-right: 20px;">

  <div>
    <h3 style="margin: 0;"><a href="https://link.springer.com/article/10.1007/s10291-023-01396-7" style="text-decoration: none;">A unified cycle-slip, multipath estimation, detection and mitigation method for VIO-aided PPP in urban environments</a></h3>
    <p style="margin: 5px 0;">
      <a href="https://boxuLibrary.github.io/"><strong>Bo Xu</strong></a>,
      Shoujian Zhang,
      Kaifa Kuang,
      Xingxing Li,
      <br>
      GPS Solutions<br>
      <!-- <a href="https://hlinchen.github.io/projects/VCR-GauS/" style="text-decoration: none;">[Project Page]</a> -->
      <a href="https://link.springer.com/article/10.1007/s10291-023-01396-7" style="text-decoration: none;">[PDF]</a>
      <!-- <a href="https://github.com/HLinChen/GNeSF" style="text-decoration: none;">[Code]</a> -->
    </p>
  </div>
</div>


<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/cgpart.jpg" alt="PVI-DSO: Leveraging Planar Regularities for Direct Sparse Visual-Inertial Odometry" style="width: 350px; height: auto; margin-right: 20px;">

  <div>
    <h3 style="margin: 0;"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Learning_Part_Segmentation_Through_Unsupervised_Domain_Adaptation_From_Synthetic_Vehicles_CVPR_2022_paper.pdf" style="text-decoration: none;">PVI-DSO: Leveraging Planar Regularities for Direct Sparse Visual-Inertial Odometry</a></h3>
    <p style="margin: 5px 0;">
      <a href="https://boxuLibrary.github.io/"><strong>Bo Xu</strong></a>,
      <a href="">Xin Li</a>,
      <a href="">Jingrong Wang</a>,
      <a href="">Chau Yue</a>,
      <a href="">Jiancheng Li</a>,
      <br>
      IEEE Sensors Journal<br>
       <a href="https://github.com/boxuLibrary/PVI-DSO-SIM" style="text-decoration: none;">[Code]</a>
      <!-- <a href="https://qliu24.github.io/udapart/" style="text-decoration: none;">[Project Page]</a> -->
      <a href="https://arxiv.org/abs/2204.02635" style="text-decoration: none;">[PDF]</a>
    </p>
  </div>
</div>



<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/cgpart.jpg" alt="Leveraging Structural Information to Improve Point Line Visual-Inertial Odometry" style="width: 350px; height: auto; margin-right: 20px;">

  <div>
    <h3 style="margin: 0;"><a href="https://arxiv.org/abs/2105.04064" style="text-decoration: none;">Leveraging Structural Information to Improve Point Line Visual-Inertial Odometry</a></h3>
    <p style="margin: 5px 0;">
      <a href="https://boxuLibrary.github.io/"><strong>Bo Xu</strong></a>,
      Peng Wang,
      Yijia He,
      Yu Chen,
      Yongnan Chen,
      Ming Zhou,
      <br>
      ICRA 2022 & RAL<br>
       <a href="https://github.com/boxuLibrary/Structural-and-Non-structural-line" style="text-decoration: none;">[Code]</a>
      <!-- <a href="https://qliu24.github.io/udapart/" style="text-decoration: none;">[Project Page]</a> -->
      <a href="https://arxiv.org/abs/2105.04064" style="text-decoration: none;">[PDF]</a>
    </p>
  </div>
</div>




Other Publications / Preprints
------

- Yu Chen, **Bo Xu**, Bin Wang, Jiaming Na, Pei Yang [GNSS Reconstrainted Visual–Inertial Odometry System Using Factor Graphs](https://ieeexplore.ieee.org/document/10016469). IEEE Geoscience and Remote Sensing Letters.

- Jingrong Wang, Jingnan Liu, Shoujian Zhang, **Bo Xu**, Yarong Luo and Ronghe Jin [Sky-view images aided NLOS detection and suppression for tightly coupled GNSS/INS system in urban canyon areas](). Measurement Science and Technology.

- **Bo Xu**, Shoujian Zhang, Jingrong Wang, Jiancheng Li [An innovation-based cycle-slip, multipath
estimation, detection and mitigation method for
tightly coupled GNSS/INS/Vision navigation in
urban areas](). ArXiv.


- Jingrong Wang, **Bo Xu**, Ronghe Jin, Shoujian Zhang, Kefu Gao, Jingnan Liu [Sky-GVIO: an enhanced GNSS/INS/Vision navigation with FCN-based sky-segmentation in urban canyon](https://arxiv.org/abs/2404.11070). ArXiv.

- Zewen Xu, Yijia He, Hao Wei, **Bo Xu**, BinJian Xie, Yihong Wu [An Accurate and Real-time Relative Pose Estimation from Triple Point-line Images by Decoupling Rotation and Translation](https://arxiv.org/abs/2403.11639). ArXiv.

<div style="width: 100px; height: 100px; display: block; align-items: center; margin-top: 40px; margin-bottom: 40px;">
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=lftFrm-MMWTRUWnwlg-Gxcpkjk-LZP23KerLj0iEi6g"></script>
</div>
