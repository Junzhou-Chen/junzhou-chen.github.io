---
title: "Mitigating In-Transit Vision Noise for Enhanced Vehicle Safety"
collection: publications
permalink: /publication/Mitigating_In-Transit_Vision_Noise_for_Enhanced_Vehicle_Safety
excerpt: 'Yichen Luo, **Junzhou Chen**, Xinyu Chen, Sidi Lu'
date: 2025-2-25
venue: 'ACM Conference on Embedded Networked Sensor Systems'
image: /images/Snipaste_2024-01-15.png
paperurl: '/files/Mitigating_In-Transit_Vision_Noise_for_Enhanced_Vehicle_Safety.pdf'

---

Yichen Luo, **Junzhou Chen**, Xinyu Chen, Sidi Lu

## Abstract

Software-defined vehicles (SDVs) are sensor-enabled systems, with cameras playing a crucial role in intelligent and safety-critical applications. However, they face significant challenges from environmental noise, such as inclement weather and unexpected occlusions. Unlike static sensors, SDV cameras experience dynamically changing noise patterns influenced by driving speed — an aspect often overlooked in previous research on camera-based vision tasks. To address this gap, we conduct a quantitative analysis of the in-transit noise impact using data from public datasets, the CARLA simulator, a robotic vehicle, and a real vehicle. Our findings suggest that maintaining a speed below 40km/h may serve as a threshold for ensuringreliable camera-based applications under noisy urban conditions. In addition, we propose TransitNet, a novel model designed to mitigate in-transit camera noise and enhance driving safety, particularly at higher speeds. Compared to multiple baselines, experimental results show that TransitNet improves the F-measure by 5.1%, mAP@50 by 3.6%, and increases FPS by 56.7% across all datasets. We also provide detailed observations and insights from extensive testing.

<!-- ![fig3](/images/Snipaste_2024-01-15.png)
<center> The overall workflow of the purified Stacking ensemble, where KFSC represents k-fold split and concatenation, DW-Voting represents distance weighted voting and MLR with AW-Softmax represents multinomial logistic regression model with adaptive weighted softmax loss function.</center> -->

[Paper download here](https://junzhou-chen.github.io//files/Mitigating_In-Transit_Vision_Noise_for_Enhanced_Vehicle_Safety.pdf)

