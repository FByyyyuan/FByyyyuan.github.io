---
title: "Letting Go of Self-Domain Awareness: Multi-Source Domain-Adversarial Generalization via Dynamic Domain-Weighted Contrastive Transfer Learning"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'Domain generalization (DG) aims to train models that generalize to unseen target domains, often by learning domain-invariant representations. However, overly compressed representations can confuse classes within the same domain. To address this, we propose MsCtrl, a framework incorporating dynamic domain-weighted contrastive loss to enhance class separation within domains while aligning source and target subdomains adversarially. Experiments show that MsCtrl outperforms state-of-the-art methods on real-world datasets.'
date: 2023-10-01
venue: 'ECAI'
paperurl: 'http://academicpages.github.io/files/Yuan Ma-ECAI2023MsCtrl.pdf'
citation: 'Y. Ma et al., " Letting Go of Self-Domain Awareness: Multi-Source Domain-Adversarial Generalization via Dynamic Domain-Weighted Contrastive Transfer Learning," in ECAI 2023. IOS Press, 2023: 1664-1671.'
---

Domain generalization (DG), which aims to learn a model that can generalize to an unseen target domain, has recently attracted increasing research interest. A major approach is to learn domain invariant representations to avoid greedily capturing all the correlations found in source domains caused by empirical risk minimization. Nevertheless, overly emphasizing learning of domain invariant representations might lead to learning overly-compressed domain invariant representations, causing confusion of different classes in a same domain. 

To address this limitation, we introduce a novel dynamic domain-weighted contrastive loss, which maximizes the subdomain differences between different classes (especially those belonging to the same domain), while minimizing the diameter of the convex hull of the source domains. We propose Multi-source domain-adversarial generalization via Contrastive transfer learning (MsCtrl), a novel domain-adversarial generalization framework, which optimizes the distribution alignment of source and potential target subdomains in an adversarial manner under the "control" of the aforementioned contrastive loss. Extensive experiments based on real-world datasets demonstrate significant advantages of MsCtrl over existing state-of-the-art methods.

![image](https://raw.githubusercontent.com/FByyyyuan/FByyyyuan.github.io/master/files/FB001.png)
