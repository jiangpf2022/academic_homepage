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
<!-- <h2 style="color:red"> NOTE: THE WEBSITE IS UNDER CONSTRUCTION, ALL OF THE INFORMATIONS HERE MAY NOT BE TOTALLY CORRECT RIGHT NOW.</h2> -->
<!-- I am currently pursuing a Bacholer's degree in Computer Science at [ShanghaiTech University](https://www.shanghaitech.edu.cn), with a minor in Mathematics and Applied Mathematics. Since the fall of 2024, I have also been a concurrent international student at [UC Berkeley](https://www.berkeley.edu/), which has offered me a broader academic perspective and numerous opportunities for cross-disciplinary collaboration.   -->

<!-- I joined the Mobile Perception Lab at ShanghaiTech University since the spring of 2023, where I work under the guidance of Ph.D. student Hang Su and Prof. Laurent Kneip. My previous projects primarily focused on event-camera-based SLAM for real-time 3D environment understanding and robust motion tracking in dynamic scenarios. -->

<!-- My research interests span computer vision, SLAM (Simultaneous Localization and Mapping), machine learning and deep learning.  -->
Hi! I'm Panfeng Jiang.

<div style="border: 2px solid #ff6347; padding: 12px; margin-top: 20px; background-color: #fff5f5;">
  <strong style="color: #c00;">⚠️ I am currently looking for Master's/Ph.D. positions for Fall 2026.</strong><br>
  If you have or know of any suitable and well-matched projects, please feel free to reach out to me via email!
</div>


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 Our paper “[**A Linear N-Point Solver for Structure and Motion from Asynchronous Tracks**](https://arxiv.org/pdf/2507.22733)” was accepted as a **Highlight Paper** at ICCV 2025.
- *2025.05*: &nbsp;🎉🎉 Our team won the **Outstanding Winner Award and AMS Award** at the Mathematical Contest In Modeling 2025.
- *2025.03*: &nbsp;🎉🎉 Our team won **the first place** at the Bay Area Data Science Summit 2025 with a Multi-Layer Perceptron and greedy strategy for equity derivative hedging, achieving strong performance in cost reduction and risk control.


# 📖 Educations

- *Aug 2024 – Jun 2025*, [University of California, Berkeley](https://www.berkeley.edu/)  
<img
  src="images/projects/ucberkeley.png"
  alt="UC Berkeley Logo"
  style="float: right;
          height: 12em;
          margin-left: 1em;
          margin-bottom: 1em;"
/><br><br>

  Undergraduate Exchange Program in Computer Science (GPA: 3.81/4.0),  
  **2025 ShanghaiTech International Exchange Program Scholarship（～$14000）**  
  <div style="clear: both;"></div>

- *Sep 2022 – Present*, [ShanghaiTech University](https://www.shanghaitech.edu.cn)  
<img
  src="images/projects/shanghaitech.png"
  alt="ShanghaiTech Logo"
  style="float: right;
          height: 12em;
          margin-left: 1em;
          margin-bottom: 1em;"
/><br><br>

  Bachelor of Engineering in Computer Science,  
  Minor in Mathematics & Applied Mathematics  (GPA: 3.81/4.0),   
  **2023 ShanghaiTech Merit Student Award (Top 10%)**. 
  <div style="clear: both;"></div>

# 📝 Publications 
 <code class="language-plaintext highlighter-rouge">Under Review</code> **Panfeng  Jiang**, Max Van Fleet, Weitong Zhang, “**Improved Analysis For Variance-Aware Langevin Monte Carlo Thompson Sampling,**” September 2025, **Submitted**

  <code class="language-plaintext highlighter-rouge">Under Review</code> **Panfeng Jiang** <sup>1</sup>,**Yunchuan Li** <sup>1</sup> , Junting Chen, Jiacheng Du, Zixuan Chen, Chenrui Tie, Jiajun Deng, Lin Shao,“**LISN: Language-Instructed Social Navigation with VLM-based Controller Modulating,**” September 2025, **Under Review**

<code class="language-plaintext highlighter-rouge">ICCV 2025</code> Hang Su, Yunlong Feng, Daniel Gehrig, **Panfeng Jiang**, Ling Gao, Xavier Lagorce, Laurent Kneip . "[**A Linear N-Point Solver for Structure and Motion from Asynchronous Tracks**](https://arxiv.org/pdf/2507.22733)."   May 2025, **Accepted (Highlight Paper)**, the IEEE/CVF
International Conference on Computer Vision (ICCV)

# 🏅Awards
- *Jun 2025*, **Outstanding Winner Award (Top 0.1%)**, Mathematical Contest in Modeling 2025 (MCM) 
- *Jun 2025*, **American Mathematical Society Award**, Mathematical Contest in Modeling 2025 (Top 3 / 21,054)
- *Mar 2025*, **First Place Winner**, Bay Area Data Science Summit 2025 @ UC Berkeley endorsed by Wells Fargo .
- *Sep 2024*, **Provincial Third Prize**, China Undergraduate Mathematical Contest in Modeling (CUMCM).
# 💻 Research Experience

#### *Jun 2025 – Sep 2025*, **RoboScience Co., Ltd. & Lin Shao's Lab, National University of Singapore**
*Advisor: Dr. Lin Shao*
<img
  src="images/logos/roboscience.jpg"
  alt="Roboscience Logo"
  style="float: right;
         height: 13em;
         margin-left: 1em;
         margin-bottom: 1em;"
/>
<img
  src="images/logos/nus.jpeg"
  alt="NUS Logo"
  style="float: right;
         height: 11em;
         margin-left: 1em;
         margin-bottom: 1em;"
/><br><br>

- Deployed and integrated the RoboPoint vision–language model into a ROS-based navigation framework, enabling robots to interpret social cues and language instructions in real time.
- Extended the Social Force Model (SFM) with dynamic, VLM-conditioned parameters and costmaps, improving socially compliant behaviors such as yielding, following, and keeping context-aware distances.
- Built and validated a VLM-driven social navigation pipeline in ROSNav-Arena 2.0, combining fast-slow control architecture with DWA/TEB planners to achieve real-time, collision-free navigation in complex human–robot interaction scenarios.
  <div style="clear: both;"></div>

#### *Apr 2025 – Present*, **Weitong Zhang's Lab, University of North Carolina at Chapel Hill**  
*Advisor: Dr.Weitong Zhang*
<img
  src="images/logos/unc.png"
  alt="UNC Logo"
  style="float: right;
          height: 12em;
          margin-left: 1em;
          margin-bottom: 1em;"
/><br><br>

 - Integrated the latest proof framework for linear bandits into the Langevin Monte Carlo Thompson Sampling (LMC-TS) environment; formalized the convergence behavior of LMC toward a Gaussian distribution under infinite steps and aligned it with cutting-edge regret analysis for linear bandits, resulting in a refined and improved upper bound on regret.  
  - Introduced a variance-aware mechanism to the framework by incorporating heteroscedasticity across actions moving beyond standard homoscedastic assumptions to derive a more nuanced and practical regret bound that adapts to varying noise levels.  
  - sAddressed the finite-step LMC setting where sampling is approximately Gaussian by deriving a regret bound explicitly dependent on the number of exploration steps Kt. This bridges asymptotic theory with practical application, demonstrating convergence to the classical linear bandit bound as $K_t \rightarrow \infty$ , while maintaining computational efficiency for finite $K_t$.
  <div style="clear: both;"></div>

#### *Apr 2023 – Mar 2025*, [**Mobile Perception Lab, ShanghaiTech University**](https://mpl.sist.shanghaitech.edu.cn/MPL@shanghaitech.html) 
*Advisor: Prof. Laurent Kneip* 
<img
  src="images/logos/mpl.jpeg"
  alt="MPL Logo"
  style="float: right;
          height: 8em;
          margin-left: 1em;
          margin-bottom: 1em;"
/><br><br>

- Developed the core real-time detection module for identifying LED matrices, and contributed to the LED encoding and tracking modules ensuring high-precision localization and stable data transmission.
- Integrated feature trackers including ArcStar and RATE for the second publication, enabling capture of temporally varying key points. This enhanced the extraction of event-based feature locations, supplying the solver with more accurate and richer tracking data for improved ego motion estimation.
  <div style="clear: both;"></div>
# 💼 Activities

- *Aug 2025 – Present*, **Teaching Assistant, CS101A Data Structure (ShanghaiTech Honor Class)**
  - Assisted in designing and launching the university’s first honors-level data structure course.
  - Developed syllabus, programming assignments, and advanced instructional materials tailored for high-achieving students.

- *Jul 2025*, **Designer, “1001 Inventions” Curation – Humanities Institute of ShanghaiTech**
  - Designed a geometric pattern for a specialized Rubik’s Cube, selected for the Institute’s “1001 Inventions” exhibition.
  - Inspired by historical motifs; tessellation integrates mathematical precision with aesthetic innovation, recognized for conceptual depth and distinctive visual appeal.

- *Jul 2023 – Mar 2025*, **Staff & Referee, Official Rubik’s Cube Competitions**
  - Officiated events including Bay Area Speedcubin’ 65 (Berkeley 2024), Berkeley Fall 2024, Berkeley October Weekday Tricubealon 2024, Cool Down Berkeley 2024, and Changsha Rubik’s Cube Open 2023.
  - Enforced competition regulations to ensure fair play; coordinated competitor flow and managed stations to keep events on pace; supported logistics including setup, registration, and awards.




# 🔍 Projects

<!-- Project -->
<h2 id="(Under Review)" style="display: flex; align-items: center; justify-content: space-between;">
  <span>LISN: Language-Instructed Social Navigation with VLM-based Controller Modulating </span>
  <span style="font-size: 0.8em;">
    <!-- <a href="https://arxiv.org/pdf/2507.22733" target="_blank" style="margin-left: 10px;">[Paper]</a> -->
    <a href="images/projects/ICRA2026.mp4" target="_blank" style="margin-left: 10px;">[Video]</a>
  </span>
</h2>
<p style="color: #f57c00; font-weight: bold; margin-top: -10px;">
  This work has been submitted to a conference and is currently under review.
</p>
<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">May 2025 - Oct 2025</div>
<img src='images/projects/ICRA2026.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

Towards human-robot coexistence, socially aware navigation is significant for mobile robots. Yet existing studies on this area focus mainly on path efficiency and pedestrian collision avoidance, which are essential but represent only a fraction of social navigation. Beyond these basics, robots must also comply with user instructions, aligning their actions to task goals and social norms expressed by humans. In this work, we present LISN-Bench, the first simulation-based benchmark for language-instructed social navigation. Built on Rosnav-Arena 3.0, it is the first standardized social navigation benchmark to incorporate instruction following and scene understanding across diverse contexts. To address this task, we further propose Social-Nav-Modulator, a fast–slow hierarchical system where a VLM agent modulates costmaps and controller parameters. Decoupling low-level action generation from the slower VLM loop reduces reliance on high-frequency VLM inference while improving dynamic avoidance and perception adaptability. Our method achieves an average success rate of 91.3%, which is greater than 63% than the most competitive baseline, with most of the improvements observed in challenging tasks such as following a person in a crowd and navigating while strictly avoiding instruction-forbidden regions.


</div>
<!-- Project -->
<h2 id="ICCV 2025" style="display: flex; align-items: center; justify-content: space-between;">
  <span>A Linear N-Point Solver for Structure and Motion from Asynchronous Tracks </span>
  <span style="font-size: 0.8em;">
    <a href="https://arxiv.org/pdf/2507.22733" target="_blank" style="margin-left: 10px;">[Paper]</a>
    <a href="https://github.com/suhang99/AsyncTrack-Motion-Solver" target="_blank" style="margin-left: 10px;">[Code]</a>
  </span>
</h2>
<p style="color: #f57c00; font-weight: bold; margin-top: -10px;">
  This work has been accepted as highlight paper at 
  <a href="https://iccv.thecvf.com/" target="_blank" style="color: #f57c00; text-decoration: underline; font-weight: bold;">ICCV 2025</a>.
</p>
<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">Nov 2024 - Mar 2025</div>
<img src='images/projects/ICCV2025.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

Structure and continuous motion estimation from point correspondences is a fundamental problem in computer vision that has been powered by well-known algorithms such as the familiar 5-point or 8-point algorithm. However, despite their acclaim, these algorithms are limited to processing point correspondences originating from a pair of views each one representing an instantaneous capture of the scene. Yet, in the case of rolling shutter cameras, or more recently, event cameras, this synchronization breaks down. In this work, we present a unified approach for structure and linear motion estimation from 2D point correspondences with arbitrary timestamps, from an arbitrary set of views. By formulating the problem in terms of first-order dynamics and leveraging a constant velocity motion model, we derive a novel, linear point incidence relation allowing for the efficient recovery of both linear velocity and 3D points with predictable degeneracies and solution multiplicities. Owing to its general formulation, it can handle correspondences from a wide range of sensing modalities such as global shutter, rolling shutter, and event cameras, and can even combine correspondences from different collocated sensors. We validate the effectiveness of our solver on both simulated and real-world data, where we show consistent improvement across all modalities when compared to recent approaches. We believe our work opens the door to efficient structure and motion estimation from asynchronous data.


</div>




<h2 id="MCM2025" style="display: flex; align-items: center; justify-content: space-between;">
  <span>Rebalancing Nature’s Scale: A Model to Tame Overtourism</span>
  <!-- <span style="font-size: 0.8em;">
    <a href="https://jiangpf2022.github.io/files/badss_report.pdf" target="_blank" style="margin-left: 10px;">[Paper]</a>
    <a href="https://github.com/jiangpf2022/MLP-for-Optimal-Equity-Derivative-Hedging/tree/main" target="_blank" style="margin-left: 10px;">[Code]</a>
  </span> -->
</h2>
<p style="color: #f57c00; font-weight: bold; margin-top: -10px;">
  This work won the Outstanding Winner Award and AMS Award in Mathematical Contest in Modeling 2025(MCM). 
  (<a href="https://www.comap.com/contests/mcm-icm" target="_blank" style="color: #f57c00; text-decoration: underline; font-weight: bold;">MCM2025</a>)
</p>
<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">Feb 2025 - Mar 2025</div>
<img src='images/projects/mcm_overtourism.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

Overtourism has become a global challenge, disrupting economic growth, environmental protection, and residents’ quality of life. Rising tourist numbers have caused environmental damage, strained infrastructure, and social tensions. Meanwhile, strict tourism limits can reduce local income and well-being. This dual challenge highlights the need for sustainable tourism strategies and data-driven models to optimize resources and maximize overall benefits. We developed the Sustainable Tourism Dynamics Model (STDM) using differential equations to simulate interactions among tourism-driven population growth (tourist numbers), environmental pressure (glacier equilibrium line altitude), and economic factors (hotel tax revenue), with government interventions (tax policies) as controllable inputs, then employed AHP to evaluate sustainability across social, environmental, and economic dimensions, dynamically optimizing strategies through sensitivity-validated feedback (identifying key parameters like tourist growth rate r₁), and successfully demonstrated model adaptability in Big Sur by improving sustainability scores from 0.33 to 0.74 through targeted infrastructure and visitor management policies, ultimately generating actionable recommendations for Juneau's tourism governance.


</div>

<h2 id="BADSS2025" style="display: flex; align-items: center; justify-content: space-between;">
  <span>Multi-Layer Perceptron for Optimal Equity Derivative Hedging</span>
  <span style="font-size: 0.8em;">
    <a href="https://jiangpf2022.github.io/files/badss_ppt.pdf" target="_blank" style="margin-left: 10px;">[Slides]</a>
    <a href="https://jiangpf2022.github.io/files/badss_report.pdf" target="_blank" style="margin-left: 10px;">[Paper]</a>
    <a href="https://github.com/jiangpf2022/MLP-for-Optimal-Equity-Derivative-Hedging/tree/main" target="_blank" style="margin-left: 10px;">[Code]</a>
  </span>
</h2>
<p style="color: #f57c00; font-weight: bold; margin-top: -10px;">
  This work won the 1st place certificate in Bay Area Data Science Summit 2025 
  (<a href="https://badss.berkeley.edu/" target="_blank" style="color: #f57c00; text-decoration: underline; font-weight: bold;">BADSS2025</a>)
</p>
<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">Feb 2025 - Mar 2025</div>
<img src='images/projects/badss.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

Traditional hedging strategies often fall short in equity derivatives markets due to their high-dimensional dynamics and stochastic volatility. To address this, we propose a data-driven framework for option hedging that integrates temporal market modeling with nonlinear predictive architectures. Our system comprises: (1) a robust preprocessing module that aligns time series, imputes data under causality constraints, and computes PnL and exposure trajectories; (2) a principled labeling mechanism that transforms exposure-adjusted returns into smooth, rank-preserving targets; and (3) a multi-layer perceptron trained via stratified cross-validation to learn risk-sensitive decision policies. Built atop this foundation is a modular trading engine that dynamically rebalances the portfolio through label-prioritized selection and adaptive sell-order management, effectively aligning exposure with market opportunities in real time.

</div>


<h2 style="display: flex; align-items: center; justify-content: space-between;">
  <span>Hybrid ML for Quality Prediction: Huber Loss Optimization and PCA-Driven Insights</span>
  <span style="font-size: 0.8em;">
    <a href="https://jiangpf2022.github.io/files/cs182_ppt.pdf" target="_blank" style="margin-left: 10px;">[Slides]</a>
    <a href="https://jiangpf2022.github.io/files/cs182_report.pdf" target="_blank" style="margin-left: 10px;">[Paper]</a>
    <a href="https://github.com/jiangpf2022/CS182-Project" target="_blank" style="margin-left: 10px;">[Code]</a>
  </span>
</h2>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge">Feb 2024 – Jun 2024</div>
    <img src='images/projects/cs182.png' alt="wine" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">

Wine quality prediction involves complex dependencies among physicochemical features, many of which are collinear or noisy. In this context, PCA proves especially powerful—not as a generic dimensionality reduction tool, but as a targeted method for denoising redundant feature spaces and isolating signal-bearing subspaces that align with latent quality drivers. Simultaneously, the use of Huber Loss addresses a critical modeling challenge: the presence of label noise and heavy-tailed residuals, which can severely distort optimization under standard squared error. By smoothly interpolating between L2 sensitivity and L1 robustness, Huber Loss enables stable convergence and improved generalization, particularly in small-to-medium data regimes where overfitting to outliers is a major risk. Together, these two components—eigenstructure-guided feature compression and statistically grounded robustification—form a principled foundation for our hybrid pipeline, allowing classical models like logistic regression and ensemble methods like XGBoost to operate closer to their theoretical optimal regimes.
</div>



<!-- ## 📃 Papers -->

<!-- Paper 2023.12 -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">International Journal of Advanced Manufacturing Technology</div><img src='images/publications/202409_Robotic_Grasping_Method_with_6D_Pose_Estimation_and_Point_Cloud_Fusion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Robotic Grasping Method with 6D Pose Estimation and Point Cloud Fusion**](https://doi.org/10.1007/s00170-024-14372-3)

**Haofei Ma**, Gongcheng Wang, Hua Bai, Zhiyu Xia, Weidong Wang, Zhijiang Du

[**Paper**](https://doi.org/10.1007/s00170-024-14372-3)
- A grasping pose estimation framework based on point cloud fusion and filtering is proposed, which solves the problem of sparse point clouds at object edges and facilitates more robust grasping.
- A novel pose estimation method based on viewpoint selection is introduced, which first uses an RGBD cam
era to reconstruct the point cloud model of the object, and then applies the principle of viewpoint selection to 
obtain the 6D pose of the object.
- We demonstrate that through pose estimation and point cloud fusion, this grasping framework can accurately grasp object from a single-view RGBD image, maintaining a high success rate even in cluttered scenes.

</div>
</div> -->

<!--
[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->






<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

<!-- 
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->