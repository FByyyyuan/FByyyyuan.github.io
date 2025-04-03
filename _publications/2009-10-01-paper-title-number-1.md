---
title: "Grade-Skewed Domain Adaptation via Asymmetric Bi-Classifier Discrepancy Minimization for Diabetic Retinopathy Grading"
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Diabetic retinopathy (DR) is a leading cause of preventable blindness, with deep learning showing promise in its grading. However, domain shifts, small lesions, and imbalanced grade distributions complicate generalization and adaptation, often leading to biased predictions. To address this, we propose Asymmetric Bi-Classifier Discrepancy Minimization (ABiD), which leverages classifier discrepancy and distribution compensation to enhance feature extraction and reduce bias, achieving state-of-the-art performance on multiple DR datasets.'
date: 2024-10-16
venue: 'IEEE TMI'
paperurl: 'https://ieeexplore.ieee.org/document/10731841'
citation: 'Y. Ma et al., "Grade-Skewed Domain Adaptation via Asymmetric Bi-Classifier Discrepancy Minimization for Diabetic Retinopathy Grading," in IEEE Transactions on Medical Imaging, doi: 10.1109/TMI.2024.3485064.'
---

Results on toy dataset:

Visualizations of comparisons of decision boundaries on balanced and imbalanced inter-twining moons datasets.

For the balanced dataset, in both the source and target domains, each class has 100 instances. For the imbalanced dataset, we designed the dataset based on the specific characteristics of GSDA: the source domain consists of two classes with sample sizes of 300 and 30, while the target domain comprises two classes with sample sizes of 100 and 50, respectively. The balanced and imbalanced datasets used the same model configuration.

The purple dots represent the target domain data, and the red and blue dots represent the source data points belonging to classes 1 and 2, respectively.
![图片描述](https://github.com/FByyyyuan/FByyyyuan.github.io/blob/master/files/FB003.png)

## Resources  
🔗 [GitHub Repository](https://github.com/FByyyyuan/ABiD)  
📄 [Paper Link](https://ieeexplore.ieee.org/document/10731841)  
