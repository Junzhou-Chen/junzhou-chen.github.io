---
title: "A Purified Stacking Ensemble Framework for Cytology Classification"
collection: publications
permalink: /publication/A_Purified_Stacking_Ensemble_Framework_for_Cytology_Classification
excerpt: 'Linyi Qian, Qian Huang, Yulin Chen, and **Junzhou Chen**'
date: 2024-5-01
venue: '30th International Conference on Multimedia Modeling'
image: /images/Snipaste_2024-01-15.png
paperurl: '/files/A_Purified_Stacking_Ensemble_Framework_for_Cytology_Classification.pdf'

---

Linyi Qian, Qian Huang, Yulin Chen, and **Junzhou Chen**

## Abstract

Cancer is one of the fatal threats to human beings. However, early detection and diagnosis can significantly reduce death risk, in which cytology classification is indispensable. Researchers have proposed many deep learning-based methods for automated cancer diagnosis. Nevertheless, due to the similarity of pathological features in cytology images and the scarcity of high-quality datasets, neither the limited accuracy of single networks nor the complex architectures of ensemble methods can meet practical application needs. To address the issue, we propose a purified Stacking ensemble framework, which employs three homogeneous convolutional neural networks (CNNs) as base learners and integrates their outputs to generate a new dataset by a k-fold split and concatenation strategy. Then a distance weighted voting technique is applied to purify the dataset, on which a multinomial logistic regression model with a designed loss function is trained as the meta-learner and performs the final predictions. The method is evaluated on the FNAC, Ascites, and SIPaKMeD datasets, achieving accuracies of 99.85%, 99.24%, and 99.75%, respectively. The experimental results outperform the current state-of-the-art (SOTA) methods, demonstrating its potential for reducing screening workload and helping pathologists detect cancer.

<!-- ![fig3](/images/Snipaste_2024-01-15.png)
<center> The overall workflow of the purified Stacking ensemble, where KFSC represents k-fold split and concatenation, DW-Voting represents distance weighted voting and MLR with AW-Softmax represents multinomial logistic regression model with adaptive weighted softmax loss function.</center> -->
<div style="border: 1px solid #ccc; padding: 8px; margin-bottom: 20px;">
  <img src="../images/Snipaste_2024-01-15.png" alt="">
  <br>
  <p style="margin-top: 10px;margin-bottom: 5px;"> 
  <strong>Framework of the purified Stacking ensemble </strong> <br style="margin-bottom: 10px;"> The overall workflow of the purified Stacking ensemble, where KFSC represents k-fold split and concatenation, DW-Voting represents distance weighted voting and MLR with AW-Softmax represents multinomial logistic regression model with adaptive weighted softmax loss function.</p>
</div>

<par>
<par>


<div style="border: 1px solid #ccc; padding: 8px; margin-bottom: 20px;">
  <img src="../images/Result_qian1.png" alt="">
  <br>
  <p style="margin-top: 10px;margin-bottom: 5px;"> 
  <strong>Comparison with other methods. </strong> <br style="margin-bottom: 10px;"> Comparison with other methods, where P represents the number of parameters, S represents inference speed, Acc represents accuracy, Pre represents precision and Rec represents recall.</p>
</div>

[Paper download here](/files/A_Purified_Stacking_Ensemble_Framework_for_Cytology_Classification.pdf)

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->