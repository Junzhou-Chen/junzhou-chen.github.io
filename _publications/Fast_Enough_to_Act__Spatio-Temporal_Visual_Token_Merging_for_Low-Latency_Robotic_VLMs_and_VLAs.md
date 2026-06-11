---
title: "Fast Enough to Act Spatio-Temporal Visual Token Merging for Low-Latency Robotic VLMs and VLAs"
collection: publications
permalink: /publication/Fast_Enough_to_Act__Spatio-Temporal_Visual_Token_Merging_for_Low-Latency_Robotic_VLMs_and_VLAs
excerpt: '**Junzhou Chen**, Jindong Wang, Zhou Gang'
date: 2026-6-16
venue: 'The IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2026'
image: /images/pipline_fast_VLA.svg
paperurl: '/files/Fast_Enough_to_Act__Spatio-Temporal_Visual_Token_Merging_for_Low-Latency_Robotic_VLMs_and_VLAs.pdf'

---

**Junzhou Chen**, Jindong Wang, Zhou Gang

## Abstract

Vision Language Model and Vision Language Action Model endowed the robot with unprecedented capabilities.
However, the input of video and high-resolution images yields a massive number of visual tokens, leading to extremely high inference latency and severely hindering the robot's real-time control.
To break through this computational bottleneck, we propose ST-Merge, a plug-and-play, training-free framework that efficiently fuses redundant tokens directly during the visual encoding phase.
By explicitly constructing 3D spatiotemporal coordinates, it employs a multi-queue parallel matching and weighted aggregation mechanism to achieve efficient and geometrically consistent fusion of redundant tokens across frames.
In addition, we introduced a post-merge positional correction mechanism that effectively eliminated spatial deviation caused by merging by dynamically re-evaluating the rotational position code of the weighted centroid of the vision token, thereby ensuring the high-precision spatial awareness required for dexterous operation.
In the Video Question Answering task on the mainstream VLM, Qwen2.5-VL, ST-Merge achieves a 2$\times$ inference speedup with only a tiny 1\% loss in precision.
When deployed on the VLA strategy of $\pi_{0.5}$, this method achieves an extreme speedup of 8.3$\times$ at a resolution of $1024\times1024$, and maintains zero performance degradation in both LIBERO and real-world robot experiments, truly empowering high-fidelity, real-time embodied intelligence systems.



<div style="border: 1px solid #ccc; padding: 8px; margin-bottom: 20px;">
  <img src="../images/pipline_fast_VLA.svg" alt="">
  <br>
  <p style="margin-top: 10px;margin-bottom: 5px;"> 
  <strong>Pipeline of ST-Merge, which can be seamlessly deployed within existing LVLMs. Inserted into shallow layer of the vision encoder, ST-Merge (1) partitions tokens into an anchor queue and multiple candidate queues for parallel matching, (2) computes spatio-temporal neighborhood weights via Gaussian kernels, (3) performs weighted matching combining similarity and neighborhood priors, (4) merges tokens by confidence-guided, size-weighted averaging, and (5) applies RoPE-aware positional correction before feeding tokens to the language decoder.</p>
</div>


[Paper download here](https://junzhou-chen.github.io//files/Fast_Enough_to_Act__Spatio-Temporal_Visual_Token_Merging_for_Low-Latency_Robotic_VLMs_and_VLAs.pdf)

