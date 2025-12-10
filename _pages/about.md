---
permalink: /
title: "Mission and Vision"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* ===== 全局样式 ===== */
:root {
  --primary-color: #2c3e50;
  --secondary-color: #3498db;
  --accent-color: #e74c3c;
  --light-gray: #f8f9fa;
  --medium-gray: #95a5a6;
  --dark-gray: #34495e;
}

/* ===== 时间线项目布局 ===== */
.timeline-item {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 1.2rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid #eee;
  position: relative;
}

.timeline-left {
  flex: 1;
  padding-right: 20px;
}

.timeline-right {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  min-width: 220px;
  text-align: right;
}

.timeline-date {
  font-style: italic;
  color: #7f8c8d;
  margin-bottom: 8px;
  font-size: 0.9rem;
}

.timeline-logo {
  width: 80px;
  height: 80px;
  display: flex;
  align-items: center;
  justify-content: center;
  border: 1px solid #eee;
  border-radius: 4px;
  padding: 5px;
  background: white;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

.timeline-logo img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}

/* ===== 职位样式 ===== */
.position-org {
  font-weight: 600;
  color: var(--primary-color);
  font-size: 1.1rem;
}

.position-title {
  color: var(--dark-gray);
  font-weight: 500;
  margin: 0.3rem 0;
}

.position-details {
  color: var(--medium-gray);
  font-size: 0.9rem;
  margin-top: 0.2rem;
}

/* ===== 教育背景样式 ===== */
.education-degree {
  font-weight: 600;
  color: var(--primary-color);
  font-size: 1rem;
}

.education-school {
  color: var(--dark-gray);
  font-weight: 500;
  margin-top: 0.2rem;
}

.education-details {
  color: var(--medium-gray);
  font-size: 0.9rem;
  margin-top: 0.2rem;
}

/* ===== 奖项样式 ===== */
.award-item {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 1rem;
  padding-bottom: 0.8rem;
  border-bottom: 1px dashed #eee;
}

.award-left {
  flex: 1;
  padding-right: 20px;
}

.award-right {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  min-width: 220px;
}

.award-year {
  color: var(--medium-gray);
  font-style: italic;
  margin-bottom: 8px;
}

.award-logo {
  width: 70px;
  height: 70px;
  display: flex;
  align-items: center;
  justify-content: center;
  border: 1px solid #eee;
  border-radius: 4px;
  padding: 5px;
  background: white;
}

.award-logo img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}

/* ===== 出版物样式 ===== */
.pub-container {
  counter-reset: pub-counter;
}

.pub-item {
  display: flex;
  justify-content: space-between;
  margin-bottom: 1.2rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid #eee;
}

.pub-left {
  flex: 1;
  padding-right: 20px;
}

.pub-number {
  font-weight: bold;
  color: var(--secondary-color);
  min-width: 30px;
}

.pub-content {
  flex: 1;
}

.pub-authors {
  font-weight: 500;
  color: var(--primary-color);
}

.pub-title {
  font-weight: 600;
  color: var(--dark-gray);
  margin: 0.3rem 0;
}

.pub-venue {
  font-style: italic;
  color: var(--medium-gray);
}

.pub-year {
  font-weight: bold;
  color: var(--secondary-color);
}

.pub-right {
  min-width: 150px;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}

.journal-logo {
  width: 60px;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 0.5rem;
  border: 1px solid #eee;
  border-radius: 4px;
  padding: 3px;
  background: white;
}

.journal-logo img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}

/* ===== 专业服务样式 ===== */
.service-item {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 1rem;
  padding-bottom: 0.8rem;
  border-bottom: 1px solid #f0f0f0;
}

.service-left {
  flex: 1;
  padding-right: 20px;
}

.service-right {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  min-width: 220px;
}

.service-role {
  font-weight: 600;
  color: var(--primary-color);
}

.service-org {
  color: var(--dark-gray);
  margin: 0.2rem 0;
}

.service-period {
  color: var(--medium-gray);
  font-style: italic;
  margin-bottom: 8px;
  font-size: 0.9rem;
}

.service-logo {
  width: 70px;
  height: 70px;
  display: flex;
  align-items: center;
  justify-content: center;
  border: 1px solid #eee;
  border-radius: 4px;
  padding: 5px;
  background: white;
}

.service-logo img {
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}

/* ===== 研究兴趣样式 ===== */
.research-category {
  margin-bottom: 1.5rem;
  padding: 1rem;
  background: var(--light-gray);
  border-radius: 8px;
  border-left: 4px solid var(--secondary-color);
}

.research-title {
  font-weight: 600;
  color: var(--primary-color);
  margin-bottom: 0.5rem;
  font-size: 1.1rem;
}

.research-tools {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-top: 0.5rem;
}

.tool-tag {
  background: #e3f2fd;
  padding: 0.3rem 0.8rem;
  border-radius: 15px;
  font-size: 0.85rem;
  color: #1565c0;
  border: 1px solid #bbdefb;
}

/* ===== 章节标题样式 ===== */
.section-title {
  border-bottom: 2px solid var(--primary-color);
  padding-bottom: 0.5rem;
  margin: 2.5rem 0 1.5rem 0;
  color: var(--primary-color);
  font-weight: 600;
  font-size: 1.4rem;
}

.section-subtitle {
  color: var(--dark-gray);
  margin: 1.5rem 0 1rem 0;
  font-weight: 500;
  font-size: 1.1rem;
}

/* ===== 响应式设计 ===== */
@media (max-width: 768px) {
  .timeline-item, .award-item, .pub-item, .service-item {
    flex-direction: column;
  }
  
  .timeline-right, .award-right, .pub-right, .service-right {
    align-items: flex-start;
    text-align: left;
    margin-top: 1rem;
    min-width: auto;
  }
  
  .timeline-logo, .award-logo, .journal-logo, .service-logo {
    margin-top: 0.5rem;
  }
}
</style>

## About Me

The **Intelligent Communication Lab** is dedicated to pushing the frontiers of research and innovation in wireless communications, networking, and machine learning. We have a dual research focus: one dedicated to uncovering fundamental insights, and the other focused on crafting practical solutions with real-world impact. To achieve these goals, we employ a blend of traditional techniques like signal processing and interdisciplinary methods like data science.

---

<div class="section-title">Academic Positions</div>

### Current Positions

<div class="timeline-item">
  <div class="timeline-left">
    <div class="position-org">The University of Hong Kong</div>
    <div class="position-title">Assistant Professor</div>
    <div class="position-details">Department of Electrical and Electronic Engineering</div>
  </div>
  <div class="timeline-right">
    <div class="timeline-date">15/08/2025 – Present</div>
    <div class="timeline-logo">
      <img src="/images/Enhao.jpg" alt="HKU Logo">
    </div>
  </div>
</div>

The Intelligent Communication Lab is dedicated to pushing the frontiers of research and innovation in wireless communications, networking, and machine learning. We have a dual research focus:  one dedicated to uncovering fundamental insights, and the other focused on crafting practical solutions with real-world impact. To achieve these goals, we employ a blend of traditional techniques like signal processing and interdisciplinary methods like data science.

About the Supervisor
======



I am an Assistant Professor at the Department of Electrical and Electronic Engineering ([EEE](https://www.eee.hku.hk/)), The University of Hong Kong. I am also a Visiting Researcher at the Department of Electrical and Electronic Engineering ([EEE](https://www.imperial.ac.uk/electrical-engineering/)), Imperial College London.

Please contact me by:

> University of Hong Kong: ylshao@hku.hk

> Imperial College London: y.shao@imperial.ac.uk


I am an Editor of IEEE Communication Magazine ([ComMag](https://www.comsoc.org/publications/magazines/ieee-communications-magazine/editorial-board)), IEEE Transactions on Wireless Communications ([TWC](https://www.comsoc.org/publications/journals/ieee-twc/editorial-board)), IEEE Transactions on Communications ([TCOM](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=26)), and IEEE Communications Letters ([ComLett](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=4234)).

Please contact me by:

> IEEE:  ylshao@ieee.org

Education
------
* Ph.D. in Information Engineering, Chinese University of Hong Kong, Aug. 2016 – Dec. 2020.
* B.E. and M.E. in Communication Engineering, Xidian University, Sept. 2009 – Jan. 2016.

Work experience
------
* Imperial College London
  * Visiting Researcher, Department of EEE
    
* University of Macau
  * Assistant Professor, IOTSC State key Lab
    
* University of Exeter
  * Lecturer (AP) in Information Processing, Department of Engineering

* Imperial College London
  * Research Associate, Department of Electrical and Electronic Engineering
  
* Massachusetts Institute of Technology
  * Visiting Scholar, Claude E. Shannon Communication and Network Group
  
* Institute of Network Coding
  * Research Assistant
 
  
Research Interests
------
* Fundamentals of wireless communications
  * Tools: signal processing, matrix theory, real analysis, information theory.
* Data science and machine learning
  * Tools: deep learning, variational Bayesian methods, statistical inference.
* Networking and stochastic control
  * Tools: Markov decision process theory, reinforcement learning, optimization.

I am particularly drawn to two types of problems: 1) problems that yield fundamental insights; 2) problems that are grounded in practical applications or have practical value.

My recent research endeavors focus on: 1) exploring deep learning techniques to achieve new breakthroughs in wireless communications, networking, and control; 2) developing new designs for wireless links and networks to enhance support for machine learning applications.

Awards
------
* Best Paper Award, IEEE Wireless Communications and Networking Conference (WCNC) 2024, Dubai, United Arab Emirates.
* Best Paper Award, IEEE International Conference on Communications (ICC) 2023, Rome, Italy.
* International Telecommunication Union (ITU) AI/ML in 5G Challenge 2021, ranked third in problem “Federated learning for spatial reuse” and nominated as a finalist in the Grand Challenge Finale.
* Global scholarship programme for research excellence, 2019.
* Overseas research attachment programme, 2018.
 

Professional Services
------
* IEEE Communications Magazine, Editor.
* IEEE Transactions on Wireless Communications, Editor.
* IEEE Transactions on Communications, Editor.
* IEEE Communications Letters, Editor.
* IEEE Communication Society flagship conferences, Session chair and TPC member.
* 5G Academy Italy 2022, Guest Lecturer.
* IEEE Information Theory Society Bangalore Chapter, Invited Speaker.


Selected Journal Publications
------

* Y. Shao. DEEP-IoT: Downlink-Enhanced Efficient-Power Internet of Things, IEEE Transactions on Wireless Communications, 2024.
  
* Y. Shao, Q. Cao, and D. Gunduz. A Theory of Semantic Communication, IEEE Transactions on Mobile Computing, 2024.
  
* Y. Shao, C. Bian, L. Yang, Q. Yang, Z. Zhang, D. Gunduz, Point Cloud in the Air, IEEE Communications Magazine, 2024.

* Y. Shao, S. Liew and D. Gunduz. Denoising noisy neural networks: A Bayesian approach with compensation, IEEE Transactions on Signal Processing, 2023.

* Y. Shao, Y. Cai, T. Wang, Z. Guo, P. Liu, J. Luo, D. Gunduz. Learning-based autonomous channel access in the presence of hidden terminals, IEEE Transactions on Mobile Computing, 2023.

* Y. Shao, D. Gunduz and S. Liew. Bayesian over-the-air computation, IEEE Journal on Selected Areas in Communications, vol. 41, no. 3, pp. 589-606, 2023.

* Y. Shao, D. Gunduz and S. Liew. Federated edge learning with misaligned over-the-air computation,” IEEE Transactions on Wireless Communications, vol. 21, no. 6, pp. 3951-3964, 2022.

* Y. Shao, D. Gunduz. Semantic communications with discrete-time analog transmission: a PAPR perspective,” IEEE Wireless Communication Letter, 2022.

* Y. Shao. Goal-oriented communication system redesign for wireless collaborative intelligence, IEEE Multimedia Communication Technical Committee – Frontiers, 2022.

* Y. Shao, Q, Cao, S. Liew, and H. Chen. Partially observable minimum-age scheduling: the greedy policy, IEEE Transactions on Communications, vol. 70, no. 1, pp. 404-418, 2021.

* Y. Shao, S. Liew, H. Chen, Y. Du. Flow sampling: network monitoring in large-scale software-defined IoT networks, IEEE Transactions on Communications, vol. 69, no. 9, pp. 6120-6133, 2021.

* Y. Shao and S. Liew. Flexible subcarrier allocation for interleaved frequency division multiple access, IEEE Transactions on Wireless Communications, vol. 19, no. 11, pp. 7139-7152, 2020.

* Y. Shao, A. Rezaee, S. Liew, and V. Chan. Significant sampling for shortest path routing: a deep reinforcement learning solution, IEEE Journal on Selected Areas in Communications, vol. 38, no. 10, pp. 2234–2248, 2020.

* Y. Shao, S. Liew, and J. Liang. Sporadic ultra-time-critical crowd messaging in V2X, IEEE Transactions on Communications, vol. 69, no. 2, pp. 817-830, 2020.

* Y. Shao, S. Liew, and T. Wang. AlphaSeq: sequence discovery with deep reinforcement learning, IEEE Transactions on Neural Networks and Learning Systems, vol. 31, no. 9, pp. 3319–3333, 2019.

* Y. Shao, S. Liew, and L. Lu. Asynchronous physical-layer network coding: symbol misalignment estimation and its effect on decoding, IEEE Transactions on Wireless Communications, vol. 16, no. 10, pp. 6881–6894, 2017.
