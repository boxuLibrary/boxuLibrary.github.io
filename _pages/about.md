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






I am currently a postdoctoral researcher at the School of Geodesy and Geomatics, <strong>[Wuhan University](https://www.whu.edu.cn/)</strong>, working with Prof. Yibin Yao. My research interests include 3D computer vision, embodied intelligence, multi-sensor fusion, and Global Navigation Satellite System (GNSS) localization. I was also a research intern at JD.com, Inc. I received my Bachelor's degree from [China University of Geosciences (Beijing)](https://www.cugb.edu.cn/) in 2018, and my Master's and Ph.D. degrees from [Wuhan University](https://www.whu.edu.cn/) in 2021 and 2025, respectively, under the supervision of Prof. Jiancheng Li.




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
  <p>🚀 [09.2026] One paper is accepted by Satellite Navigation!</p>
  <p>🚀 [04.2026] One paper is accepted at ICLR 2026 as an Oral!</p>
  <p>🚀 [01.2026] One paper is accepted by IEEE Transactions on Robotics (T-RO)!</p>
  <p>🚀 [12.2024] Reached 100+ citations milestone on Google Scholar</p>
  <p>🚀 [07.2024] One paper <a href="">URS-NeRF</a> is accepted at ECCV 2024</p>
  <p>😎 [10.2023] Joined <a href="https://www.comp.nus.edu.sg/~leegh/">CVRP Lab</a> of NUS as a visiting student supervised by Gim Hee Lee!</p>
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
  <img src="images/cross_epoch_ambiguity_tracking.png" alt="A Cross-epoch Ambiguity Tracking Method for GNSS/INS/Vision Urban Navigation" style="width: 350px; height: auto; margin-right: 20px;">

  <div>
    <h3 style="margin: 0;">A Cross-epoch Ambiguity Tracking Method for GNSS/INS/Vision Urban Navigation</h3>
    <p style="margin: 10px 0;">
      <strong>Bo Xu</strong>,
      Shoujian Zhang,
      Yibin Yao,
      Xingxing Li,
      Jingrong Wang,
      Shengyu Li
      <br>
      Satellite Navigation, 2026 <strong>(Accepted)</strong>
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="https://chenhaijier.github.io/Vid-LLM/static/images/cover.png" alt="Vid-LLM: A Compact Video-based 3D Multimodal LLM with Reconstruction-Reasoning Synergy" style="width: 350px; height: auto; margin-right: 20px;">

  <div>
    <h3 style="margin: 0;"><a href="https://chenhaijier.github.io/Vid-LLM/" style="text-decoration: none;">Vid-LLM: A Compact Video-based 3D Multimodal LLM with Reconstruction-Reasoning Synergy</a></h3>
    <p style="margin: 10px 0;">
      Haijier Chen*,
      <strong>Bo Xu</strong>*,
      Shoujian Zhang,
      Haoze Liu,
      Jiaxuan Lin,
      Jingrong Wang
      <br>
      ICLR, 2026 <strong>(Oral)</strong><br>
      <a href="https://chenhaijier.github.io/Vid-LLM/" style="text-decoration: none;">[Project Page]</a>
      <a href="https://arxiv.org/pdf/2509.24385" style="text-decoration: none;">[PDF]</a>
      <a href="https://github.com/chenhaijier/Vid-LLM" style="text-decoration: none;">[Code]</a>
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/drt_vi_ostc_comparison.png" alt="A Rotation-Translation Decoupled Solution for Visual-Inertial Initialization and Online Spatial-Temporal Calibration" style="width: 350px; height: auto; margin-right: 20px;">

  <div>
    <h3 style="margin: 0;"><a href="https://ieeexplore.ieee.org/document/11353084" style="text-decoration: none;">A Rotation-Translation Decoupled Solution for Visual-Inertial Initialization and Online Spatial-Temporal Calibration</a></h3>
    <p style="margin: 10px 0;">
      <strong>Bo Xu</strong>*,
      Zewen Xu*,
      Yijia He,
      Zhanpeng Ouyang,
      Hao Wei,
      Yihong Wu,
      Jiancheng Li,
      Hongdong Li
      <br>
      IEEE Transactions on Robotics (T-RO), 2026<br>
      <a href="https://ieeexplore.ieee.org/document/11353084" style="text-decoration: none;">[Paper]</a>
      <a href="https://github.com/BITcats/DRT-VI-OSTC" style="text-decoration: none;">[Code]</a>
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/URS-NeRF2.gif" alt="URS-NeRF: Unordered Rolling Shutter Bundle Adjustment for Neural Radiance Fields" style="width: 350px; height: auto; margin-right: 20px;">

  <div>
    <h3 style="margin: 0;"><a href="projects/URS-NeRF/" style="text-decoration: none;">URS-NeRF: Unordered Rolling Shutter Bundle Adjustment for Neural Radiance Fields</a></h3>
    <p style="margin: 10px 0;">
     <strong>Bo Xu</strong>,
      <a href="">Ziao Liu</a>,
      <a href="https://dreamguo.github.io/">Mengqi Guo</a>,
      <a href="">Jiancheng Li</a>,
      <a href="https://www.comp.nus.edu.sg/~leegh/">Gim Hee Lee</a>
      <br>
      ECCV, 2024<br>
      <a href="projects/URS-NeRF/" style="text-decoration: none;">[Project Page]</a>
      <a href="https://arxiv.org/pdf/2403.10119" style="text-decoration: none;">[PDF]</a>
      <a href="https://github.com/ZiaoLiuS/URS-NERF" style="text-decoration: none;">[Code]</a>
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/DRT_VIO.png" alt="A Rotation-Translation-Decoupled Solution for Robust and Efficient
Visual-Inertial Initialization" style="width: 350px; height: auto; margin-right: 20px;">

  <div>
    <h3 style="margin: 0;"><a href="" style="text-decoration: none;">A Rotation-Translation-Decoupled Solution for Robust and Efficient
Visual-Inertial Initialization</a></h3>
    <p style="margin: 5px 0;">
      <a href="https://scholar.google.com/citations?user=_0lKGnkAAAAJ&hl=en">Yijia He*</a>,
      <strong>Bo Xu</strong>*,
      <a href="">Zhanpeng Ouyang</a>,
      <a href="https://scholar.google.com.sg/citations?hl=zh-CN&user=Mq89JAcAAAAJ">Hongdong Li</a>
      <br>
      CVPR, 2023<br>
      <!-- <a href="projects/DRTVIO/" style="text-decoration: none;">[Project Page]</a> -->
      <a href="https://openaccess.thecvf.com/content/CVPR2023/papers/He_A_Rotation-Translation-Decoupled_Solution_for_Robust_and_Efficient_Visual-Inertial_Initialization_CVPR_2023_paper.pdf" style="text-decoration: none;">[PDF]</a>
      <a href="https://github.com/boxuLibrary/drt-vio-init" style="text-decoration: none;">[Code]</a>
    </p>
  </div>
</div>

<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/EDM.png" alt="A unified cycle-slip, multipath estimation, detection and mitigation method for VIO-aided PPP in urban environments" style="width: 350px; height: auto; margin-right: 20px;">

  <div>
    <h3 style="margin: 0;"><a href="https://link.springer.com/article/10.1007/s10291-023-01396-7" style="text-decoration: none;">A unified cycle-slip, multipath estimation, detection and mitigation method for VIO-aided PPP in urban environments</a></h3>
    <p style="margin: 5px 0;">
      <strong>Bo Xu</strong>,
      <a href="">Shoujian Zhang</a>,
      <a href="">Kaifa Kuang</a>,
      <a href="">Xingxing Li</a>,
      <br>
      GPS Solutions<br>
      <!-- <a href="https://hlinchen.github.io/projects/VCR-GauS/" style="text-decoration: none;">[Project Page]</a> -->
      <a href="https://link.springer.com/article/10.1007/s10291-023-01396-7" style="text-decoration: none;">[PDF]</a>
      <!-- <a href="https://github.com/HLinChen/GNeSF" style="text-decoration: none;">[Code]</a> -->
    </p>
  </div>
</div>


<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/PVI-DSO.gif" alt="PVI-DSO: Leveraging Planar Regularities for Direct Sparse Visual-Inertial Odometry" style="width: 350px; height: auto; margin-right: 20px;">

  <div>
    <h3 style="margin: 0;"><a href="https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Learning_Part_Segmentation_Through_Unsupervised_Domain_Adaptation_From_Synthetic_Vehicles_CVPR_2022_paper.pdf" style="text-decoration: none;">PVI-DSO: Leveraging Planar Regularities for Direct Sparse Visual-Inertial Odometry</a></h3>
    <p style="margin: 5px 0;">
      <strong>Bo Xu</strong>,
      <a href="https://lixin97.github.io/">Xin Li</a>,    
      <a href=""> Jingrong Wang</a>,  
      <a href=""> Chau Yue</a>,  
      <a href=""> Jiancheng Li</a>,       
      <br>
      IEEE Sensors Journal<br>
       <a href="https://github.com/boxuLibrary/PVI-DSO-SIM" style="text-decoration: none;">[Code]</a>
      <!-- <a href="https://qliu24.github.io/udapart/" style="text-decoration: none;">[Project Page]</a> -->
      <a href="https://arxiv.org/abs/2204.02635" style="text-decoration: none;">[PDF]</a>
    </p>
  </div>
</div>



<div style="display: flex; align-items: center; margin-bottom: 40px;">
  <img src="images/PLS-VIO.png" alt="Leveraging Structural Information to Improve Point Line Visual-Inertial Odometry" style="width: 350px; height: auto; margin-right: 20px;">

  <div>
    <h3 style="margin: 0;"><a href="https://arxiv.org/abs/2105.04064" style="text-decoration: none;">Leveraging Structural Information to Improve Point Line Visual-Inertial Odometry</a></h3>
    <p style="margin: 5px 0;">
      <strong>Bo Xu</strong>,
      <a href="">Peng Wang</a>,
      <a href="https://scholar.google.com/citations?user=_0lKGnkAAAAJ&hl=en">Yijia He</a>,
      <a href="">Yu Chen</a>,
      <a href="">Yongnan Chen</a>,
      <a href="">Ming Zhou</a>,
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

- Mingyue Liu, Shoujian Zhang, **Bo Xu**, Jingrong Wang, Huizhong Zhu, Xinchao Xu [GNSS/Vision/INS tight integration navigation and positioning method based on feature enhancement in low-light environments](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=d6U3GwoAAAAJ&sortby=pubdate&citation_for_view=d6U3GwoAAAAJ:KlAtU1dfN6UC). Measurement Science and Technology, 2026.

- Li Yan, Yinghao Zhao, Jicheng Dai, **Bo Xu**, Hong Xie, Yuquan Zhou [Intelligent perception measurement technology of autonomous UAV for unknown environment ](http://xb.chinasmp.com/EN/abstract/abstract13309.shtml). Acta Geodaetica et Cartographica Sinica (测绘学报).


- Yu Chen, **Bo Xu**, Bin Wang, Jiaming Na, Pei Yang [GNSS Reconstrainted Visual–Inertial Odometry System Using Factor Graphs](https://ieeexplore.ieee.org/document/10016469). IEEE Geoscience and Remote Sensing Letters.

- Jingrong Wang, Jingnan Liu, Shoujian Zhang, **Bo Xu**, Yarong Luo and Ronghe Jin [Sky-view images aided NLOS detection and suppression for tightly coupled GNSS/INS system in urban canyon areas](https://iopscience.iop.org/article/10.1088/1361-6501/ad087f). Measurement Science and Technology.

- **Bo Xu**, Shoujian Zhang, Jingrong Wang, Jiancheng Li [An innovation-based cycle-slip, multipath
estimation, detection and mitigation method for
tightly coupled GNSS/INS/Vision navigation in
urban areas](). ArXiv.


- Jingrong Wang, **Bo Xu**, Ronghe Jin, Shoujian Zhang, Kefu Gao, Jingnan Liu [Sky-GVIO: an enhanced GNSS/INS/Vision navigation with FCN-based sky-segmentation in urban canyon](https://arxiv.org/abs/2404.11070). ArXiv.

- Zewen Xu, Yijia He, Hao Wei, **Bo Xu**, BinJian Xie, Yihong Wu [An Accurate and Real-time Relative Pose Estimation from Triple Point-line Images by Decoupling Rotation and Translation](https://arxiv.org/abs/2403.11639). ArXiv.

<div style="width: 100px; height: 100px; display: block; align-items: center; margin-top: 40px; margin-bottom: 40px;">
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=lftFrm-MMWTRUWnwlg-Gxcpkjk-LZP23KerLj0iEi6g"></script>
</div>
