---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm currently a **final-year PhD. Candidate** from Hong Kong PolyU (AAE) and will be graduated within 2026. My PhD. Thesis is **Promoting Underwater Visual Intelligence: From 2D to 3D Applications**. I am supervised by [Prof. Chih-yung Wen](https://www.polyu.edu.hk/aae/people/academic-staff/ir-prof-wen-chih-yung/) and co-supervised by [Prof. Bing Wang](https://bingcs.github.io/). Before I pursuit my doctoral degree, I received a master degree with **distinction** also from PolyU supervised by [Prof. Boyang Li](https://boyangli.com/team/) in 2023, and a bachelor degree from Nanjing University of Aeronautics and Astronautics (NUAA) supervised by [Prof. Meng Yu](https://scholar.google.com/citations?user=nGZhpS4AAAAJ&hl=zh-CN) in 2019.  

Research Focus
======

My PhD. reserach **consistently locates in** how to improve the **underwater images degraded by water medium** (including color-bias, low-contrast, and blur effects that weaken the vision-based tasks) to support both 2D visual evaluation and downstream 3D reconstruction. Specifically, I've spent much effort to solve the issues of **label noise** and **multi-view inconsistency** that impair the model performance by physics-informed and learning-based strategies.

2D Evaluation-oriented Enhancement
------
- **Underwater sequential images enhancement via diffusion and physics priors fusion**

  This work focuses on:
  1. leveraging diffusion prior to achieve SOTA performance from only synthetic data;
  2. full physics-based synthesis for improving visual clarity. 

<p align="center">
  <img src="/images/PFUISE-Framework.png" alt="Framework of PF-UISE" width="60%">
</p>

<p align="center">
  <img src="/images/time_consistency.jpg" alt="Visual Results" width="60%">
</p>

- **Fusing Transferred Priors and Physics-based Decomposition for Underwater Image Enhancement**

  This work focuses on:
  1. transfer-learning from multiple data/model priors to avoid noisy label issue;
  2. Physics-based task decomposition to provide theoretical soundness.
   
<p align="center">
  <img src="/images/P2UIE-Framework.png" alt="Framework of P2-UIE" width="60%">
</p>

<p align="center">
  <img src="/images/LabelBiasComp.png" alt="Visual Results" width="60%">
</p>


3D Reconstruction-oriented Enhancement
------

- **NVS-UIE: Diffusion UIE towards Novel View Synthesis via Physics-Aligned Frequency Fusion**

  This work focuses on:
  1. frequency-fusion strategy to preserve the texture details;
  2. physics-controlled sequential image synthesis to improve the multi-view consistency.
   
<p align="center">
  <img src="/images/NVSUIE-Framework.png" alt="Framework of NVS-UIE" width="60%">
</p>

<p align="center">
  <img src="/images/Final_Visualization.png" alt="Visual Results" width="60%">
</p>

- **RQUL-UIE: Revitalizing Quality-Unstable Labels for Underwater Image Enhancement via In-Dataset Self-Supervision**

  This work focuses on:
  1. label quality quantization to fully utilize the quality-unstable labels;
  2. a fourier-based texture refinement to for multi-view consistent texture preservation. 
  
<p align="center">
  <img src="/images/RQUL-Framework.png" alt="Framework of RQUL-UIE" width="60%">
</p>

<p align="center">
  <img src="/images/vis_comp_exp.png" alt="Visual Results" width="60%">
</p>

<p align="center">
  <video src="/images/output.mp4" controls autoplay muted loop playsinline width="80%">
    您的浏览器不支持播放该视频。
  </video>
</p>

Selected Publications
=====

- **Underwater sequential images enhancement via diffusion and physics priors fusion**<br> **Haochen Hu**, Yanrui Bin, Chih-yung Wen, Bing Wang  
  *Information Fusion **IF:15.5***.  
  [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S1566253525004385)

- **Fusing Transferred Priors and Physics-based Decomposition for Underwater Image Enhancement**<br> **Haochen Hu**, Yanrui Bin, Zhengyan Zhang, Minchen Wei, Chih-yung Wen, Bing Wang  
  *Information Fusion **IF:15.5** (major review)*.  
  [[Paper]](https://arxiv.org/abs/xxxx.xxxxx)

- **NVS-UIE: Diffusion UIE towards Novel View Synthesis via Physics-Aligned Frequency Fusion**<br> **Haochen Hu**, Yanze Lu, Yuanbo Xue, Zhengyan Zhang, Shu Yang, Chih-yung Wen, Bing Wang  
  *Visual Intelligence (minor review)*.  
  [[Paper]](https://arxiv.org/abs/xxxx.xxxxx)

- **RQUL-UIE: Revitalizing Quality-Unstable Labels for Underwater Image Enhancement via In-Dataset Self-Supervision**<br> **Haochen Hu**, Yanrui Bin, Chih-yung Wen, Bing Wang  
  *Prepared to submitted tot CVPR 2027*.  
  [[Paper]](https://arxiv.org/abs/2606.06176)



