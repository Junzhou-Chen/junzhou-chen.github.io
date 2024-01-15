---
title: "Enhancing Nucleus Segmentation with Haru-Net: A Hybrid Attention Based Residual U-Blocks Network"
collection: publications
permalink: /publication/Enhancing_Nucleus_Segmentation_with_Haru_Net__A_Hybrid_Attention_Based_Residual_U_Blocks_Network
excerpt: '**Junzhou Chen**, Qian Huang, Yulin Chen, Linyi Qian, Chengyuan Yu'
date: 2023-8-01
venue: 'Under review'
paperurl: 'https://arxiv.org/pdf/2308.03382.pdf'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

**Junzhou Chen**, Qian Huang, Yulin Chen, Linyi Qian, Chengyuan Yu


## Abstract
 Nucleus image segmentation is a crucial step in the analysis, pathological diagnosis, and classification, which heavily relies on the quality of nucleus segmentation. However, the complexity of issues such as variations in nucleus size, blurred nucleus contours, uneven staining, cell clustering, and overlapping cells poses significant challenges. Current methods for nucleus segmentation primarily rely on nuclear morphology or contour-based approaches. Nuclear morphology-based methods exhibit limited generalization ability and struggle to effectively predict irregular-shaped nuclei, while contourbased extraction methods face challenges in accurately segmenting overlapping nuclei. To address the aforementioned issues, we propose a dual-branch network using hybrid attention based residual U-blocks for nucleus instance segmentation. The network simultaneously predicts target information and target contours. Additionally, we introduce a post-processing method that combines the target information and target contours to distinguish overlapping nuclei and generate an instance segmentation image. Within the network, we propose a context fusion block (CF-block) that effectively extracts and merges contextual information from the network. Extensive quantitative evaluations are conducted to assess the performance of our method. Experimental results demonstrate the superior performance of the proposed method compared to state-of-the-art approaches on the BNS, MoNuSeg, CoNSeg, and CPM-17 datasets.

 <div style="border: 1px solid #ccc; padding: 8px; margin-bottom: 20px;">
  <img src="../images/NetWork.svg" alt="">
  <br>
  <p style="margin-top: 10px;margin-bottom: 5px;"> 
  <strong>Framework of HARU-Net </strong> <br style="margin-bottom: 10px;">  Overall architecture of the network demonstrates the precise placement of modules within the network. The channel attention mechanism is applied at the deepest layer, while the remaining layers utilize a hybrid attention mechanism.</p>
</div>


 [Download paper here](https://arxiv.org/pdf/2308.03382.pdf)
```bibtex
@article{chen2023enhancing,
  title={Enhancing Nucleus Segmentation with HARU-Net: A Hybrid Attention Based Residual U-Blocks Network},
  author={Chen, Junzhou and Huang, Qian and Chen, Yulin and Qian, Linyi and Yu, Chengyuan},
  journal={arXiv preprint arXiv:2308.03382},
  year={2023}
}
```

<!-- Recommended citation: Your Name, You. (2015). "Paper Title Number 3." <i>Journal 1</i>. 1(3). -->