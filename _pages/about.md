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

I am currently pursuing a Bacholer's degree in Computer Science at [ShanghaiTech University](https://www.shanghaitech.edu.cn), with a minor in Mathematics and Applied Mathematics. Since the fall of 2024, I have also been a concurrent international student at [UC Berkeley](https://www.berkeley.edu/), which has offered me a broader academic perspective and numerous opportunities for cross-disciplinary collaboration.  

I joined the Mobile Perception Lab at ShanghaiTech University since the spring of 2023, where I work under the guidance of Ph.D. student Hang Su and Prof. Laurent Kneip. My previous projects primarily focused on event-camera-based SLAM for real-time 3D environment understanding and robust motion tracking in dynamic scenarios.

My research interests span computer vision, SLAM (Simultaneous Localization and Mapping), machine learning and deep learning. 


<div style="border: 2px solid #ff6347; padding: 12px; margin-top: 20px; background-color: #fff5f5;">
  <strong style="color: #c00;">⚠️ I am currently looking for Summer Research Internship opportunities in 2025 and Master's/Ph.D. positions for Fall 2026.</strong><br>
  If you have or know of any suitable and well-matched projects, please feel free to reach out to me via email!
</div>


# 🔥 News
- *2025.03*: &nbsp;🎉🎉 Our team won the first place at the Bay Area Data Science Summit 2025 with a Multi-Layer Perceptron and greedy strategy for equity derivative hedging, achieving strong performance in cost reduction and risk control.


# 📖 Educations
- *Aug 2024 - Jun 2025*, [University of California, Berkeley](https://www.berkeley.edu/)  
  Concurrent International in GLOBE Program, Major: Computer Science (GPA:3.957/4.0).

- *Sep 2022 - Present*, [ShanghaiTech University](https://www.shanghaitech.edu.cn)  
  B.Eng. in Computer Science, Minor in Mathematics & Applied Math(GPA:3.79/4.0)



# 🔍 Projects


<!-- Project -->

<!-- ## Multi-Layer Perceptron for Optimal Equity Derivative Hedging -->
<h2 style="display: flex; align-items: center; justify-content: space-between;">
  <span>Multi-Layer Perceptron for Optimal Equity Derivative Hedging</span>
  <span style="font-size: 0.8em;">
    <a href="https://jiangpf2022.github.io/files/badss_ppt.pdf" target="_blank" style="margin-left: 10px;">[PPT]</a>
    <a href="https://jiangpf2022.github.io/files/badss_report.pdf" target="_blank" style="margin-left: 10px;">[Paper]</a>
    <a href="https://github.com/jiangpf2022/MLP-for-Optimal-Equity-Derivative-Hedging/tree/main" target="_blank" style="margin-left: 10px;">[Code]</a>
  </span>
</h2>

<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">Feb 2025 - Mar 2025</div>
<img src='images/projects/badss.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

Traditional hedging strategies often fall short in equity derivatives markets due to their high-dimensional dynamics and stochastic volatility. To address this, we propose a data-driven framework for option hedging that integrates temporal market modeling with nonlinear predictive architectures. Our system comprises: (1) a robust preprocessing module that aligns time series, imputes data under causality constraints, and computes PnL and exposure trajectories; (2) a principled labeling mechanism that transforms exposure-adjusted returns into smooth, rank-preserving targets; and (3) a multi-layer perceptron trained via stratified cross-validation to learn risk-sensitive decision policies. Built atop this foundation is a modular trading engine that dynamically rebalances the portfolio through label-prioritized selection and adaptive sell-order management, effectively aligning exposure with market opportunities in real time.

</div><div markdown="1">

**Finished Works**:  
1.Engineered a fault-tolerant data pipeline for financial time series, incorporating custom temporal imputation and non-trading day exclusion logic, ensuring robust option lifecycle reconstruction.

2.Proposed and implemented a theoretically grounded labeling function that maps PnL-exposure ratios into continuous preference scores, preserving directional semantics under both positive and negative regimes.

3.Trained a deep MLP architecture with hyperparameter tuning and 5-fold cross-validation, achieving stable generalization across diverse market conditions and minimizing out-of-sample prediction error.

4.Developed a two-stage decision-making algorithm that orchestrates exposure tracking through priority-based liquidation and reallocation, enabling adaptive trade execution under soft budget constraints.

5.Integrated the full pipeline into a real-time simulation framework, supporting continuous decision rollouts, exposure drift correction, and trade performance monitoring at daily resolution.

</div>
</div>


<h2 style="display: flex; align-items: center; justify-content: space-between;">
  <span>Hybrid ML for Quality Prediction: Huber Loss Optimization and PCA-Driven Insights</span>
  <span style="font-size: 0.8em;">
    <a href="https://jiangpf2022.github.io/files/cs182_ppt.pdf" target="_blank" style="margin-left: 10px;">[PPT]</a>
    <a href="https://jiangpf2022.github.io/files/cs182_report.pdf" target="_blank" style="margin-left: 10px;">[Paper]</a>
    <a href="https://github.com/jiangpf2022/CS182-Project" target="_blank" style="margin-left: 10px;">[Code]</a>
  </span>
</h2>
<p style="color: #f57c00; font-weight: bold; margin-top: -10px;">
  This work won the 1st place certificate in Bay Area Data Science Summit 2025 (BADSS2025)
</p>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badge">Feb 2024 – Jun 2024</div>
    <img src='images/projects/cs182.png' alt="wine" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">

Wine quality prediction involves complex dependencies among physicochemical features, many of which are collinear or noisy. In this context, PCA proves especially powerful—not as a generic dimensionality reduction tool, but as a targeted method for denoising redundant feature spaces and isolating signal-bearing subspaces that align with latent quality drivers. Simultaneously, the use of Huber Loss addresses a critical modeling challenge: the presence of label noise and heavy-tailed residuals, which can severely distort optimization under standard squared error. By smoothly interpolating between L2 sensitivity and L1 robustness, Huber Loss enables stable convergence and improved generalization, particularly in small-to-medium data regimes where overfitting to outliers is a major risk. Together, these two components—eigenstructure-guided feature compression and statistically grounded robustification—form a principled foundation for our hybrid pipeline, allowing classical models like logistic regression and ensemble methods like XGBoost to operate closer to their theoretical optimal regimes.

</div><div markdown="1">

**Finished Works**:  
1. Conducted a thorough benchmarking of multiple models (Logistic Regression, Random Forest, XGBoost) for quality prediction on a real-world dataset from the wine industry.  
2. Employed Principal Component Analysis (PCA) to reduce feature dimensionality, improve interpretability, and eliminate noisy correlations.  
3. Incorporated Huber Loss into neural network and XGBoost models, significantly mitigating the influence of outliers and enhancing generalization on test data.  
4. Designed a comprehensive ablation study evaluating the impact of model choice, loss function, and feature preprocessing, identifying optimal configurations for predictive performance.  
5. Visualized and analyzed model behavior and prediction error metrics using MSE and Kaggle submissions, confirming improved robustness and lower error rates through hybrid techniques.

</div>
</div>

# 📝 Publications 

## 📃 Papers

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
<code class="language-plaintext highlighter-rouge">ICCV</code> Hang Su, Yunlong Feng, Daniel Gehrig, **Panfeng Jiang**, Ling Gao, Xavier Lagorce, Laurent Kneip . "[**An Efficient Asynchronous Point-based Solver for Camera Egomotion Recovery**](#)." *Submitted to the IEEE/CVF International Conference on Computer Vision (ICCV)*, 2025.

<!-- - <code class="language-plaintext highlighter-rouge">IJAMT</code> **Haofei Ma**, Gongcheng Wang, Hua Bai, Zhiyu Xia, Weidong Wang, and Zhijiang Du. "[**Robotic Grasping Method with 6D Pose Estimation and Point Cloud Fusion**](https://doi.org/10.1007/s00170-024-14372-3)." *The International Journal of Advanced Manufacturing Technology* (2024): 1-11. doi: [10.1007/s00170-024-14372-3](https://doi.org/10.1007/s00170-024-14372-3) -->

<!-- - <code class="language-plaintext highlighter-rouge">RAS</code> Gongcheng Wang, **Haofei Ma**, Han Wang, Pengchao Ding, Hua Bai, Wenda Xu, Weidong Wang, and Zhijiang Du. "[**Reactive mobile manipulation based on dynamic dual-trajectory tracking**](https://doi.org/10.1016/j.robot.2023.104589)." *Robotics and Autonomous Systems* 172 (2024): 104589. doi: [10.1016/j.robot.2023.104589](https://doi.org/10.1016/j.robot.2023.104589).

- <code class="language-plaintext highlighter-rouge">IEEE Sensors Journal</code> Zhiyu Xia, Han Wang, Yulong Men, **Haofei Ma**, Zexin Cao, Weidong Wang, Zhijiang Du. "[**Kalman Filter-based EM-optical Sensor Fusion for Bone Needle Position Tracking**](https://doi.org/10.1109/JSEN.2024.3364701)." *IEEE Sensors Journal* (2024). doi: [10.1109/JSEN.2024.3364701](https://doi.org/10.1109/JSEN.2024.3364701)

- <code class="language-plaintext highlighter-rouge">RAS</code> Hua Bai, Wenrui Gao, **Haofei Ma**, Pengchao Ding, Gongcheng Wang, Wenda Xu, Weidong Wang, Zhijiang Du. "[**A study of robotic search strategy for multi-radiation sources in unknown environments**](https://doi.org/10.1109/JSEN.2024.3364701)." *Robotics and Autonomous Systems* 169 (2023): 104529. doi: [10.1109/JSEN.2024.3364701](https://doi.org/10.1109/JSEN.2024.3364701). -->


<!-- ## 📚 Patents

- <code class="language-plaintext highlighter-rouge">Invention Patent</code> [**A Rock Core Box Handling Robot**](https://cprs.patentstar.com.cn/Search/Detail?ANE=9DIE1BAA2AAA8CDA8EDA9CIB9BIF9GBC9BED6BDA9HBH9IBE), Weidong Wang, Hengbin Liang, **Haofei Ma**, Gongcheng Wang (CN202310547284.5, Pending)

- <code class="language-plaintext highlighter-rouge">Utility Model Patent</code> [**A Spherical Metamorphic Robot and An Environmental Information Monitoring System**](https://cprs.patentstar.com.cn/Search/Detail?ANE=AHIA8FDA8AGA9GGE9HAA6GAA9HDD9CIC9FCA9HDC9GDF9ICF), Yuhan Rao, Manhong Li, *Haofei Ma*, Yuchong Gao, Nuo Zhang, Xinyu Liu (CN202120212154.2)

- <code class="language-plaintext highlighter-rouge">Utility Model Patent</code> [**A Rope Driven Cleaning Robot**](https://cprs.patentstar.com.cn/Search/Detail?ANE=AIHA6AGA7BEA9DID9BIC9ICBBFIA8BDA9IBF9ICG8EEA9FDG), Bao Li, Manhong Li, Shuofan Li, **Haofei Ma**, Jidong Guo, Yuchong Gao, Yingxin Dong (CN202120545507.0)

- <code class="language-plaintext highlighter-rouge">Utility Model Patent</code> [**Small Ocean Vehicles Using Wave Energy to Generate Electricity**](https://cprs.patentstar.com.cn/Search/Detail?ANE=9EEB9HFD3ABA3CBA9AIB9GIF8IAA9FADBCIA9BEA9ECDAGGA), Yihan Gao, **Haofei Ma**, Shaoan Chen, Haoran Sun, Chenxi Song (CN202020078465.X)

- <code class="language-plaintext highlighter-rouge">Software Copyright</code> [**Identity Recognition and Infrared Temperature Measurement Control System**](https://register.ccopyright.com.cn/publicInquiry.html?type=softList&registerNumber=2021SR1391064&keyWord=%E9%A9%AC%E6%B5%A9%E9%A3%9E&publicityType=ALL&registerDateType=ALL), **Haofei Ma** (2021SR1391064) -->

# 🏆 Honors and Awards

## 🏅 Honors
- *Dec 2023*, Department Prize for Outstanding Student Performance, 2023

## 🎏 Competitions
- *Mar 2025*, Bay Area Data Science Summit, First Place.
- *Sep 2024*, China Undergraduate Mathematical Contest in Modeling (CUMCM), Provincial Third Prize.

# 💼 Societies

- *Jul 2023 - Aug 2023*, Teaching Assistant in New Oriental Education & Technology Group Inc.
- *Jul 2023 - Mar 2025*, Staff & Referee in Rubik’s Cube competitions, including Bay Area Speedcubin’65 - Berkeley 2024, Berkeley Fall 2024, Berkeley October Weekday Tricubealon 2024, Cool Down Berkeley 2024, and
Changsha Rubik’s Cube Open 2023..
- *Aug 2023 - Aug 2024*, served as a volunteer in ShanghaiTech summer camp, Shanghai Planetarium,Shanghai Library as well as Shanghai Marathon 2023.

<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

<!-- 
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->