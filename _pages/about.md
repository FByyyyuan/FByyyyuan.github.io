---
permalink: /
title: "About Me"
author_profile: true
layout: archive
redirect_from: 
  - /about/
  - /about.html
---

I am Yuan Ma from Beijing, China. I am a Ph.D. student at [Institute Of Computing Technology, Chinese Academy of Sciences](http://english.ict.cas.cn/), advised by [Prof. Yiqiang Chen](https://scholar.google.com/citations?user=LC3SwhEAAAAJ&hl=en), and I work primarily in the intersection of transfer learning algorithms and applications in ubiquitous computing.

### Research Interests:
- **Transfer Learning： Domain Adaptation (DA) and Generalization (DG)**
- **Retrieval-Augmented Generation (RAG)**  
- **AI for Healthcare**

### Publications
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
<style>
.publications-grid {
  display: grid;
  gap: 25px;
  margin: 20px 0;
}

.publication-card {
  display: grid;
  grid-template-columns: 1fr 300px;
  gap: 20px;
  padding: 20px;
  border: 1px solid #e0e0e0;
  border-radius: 12px;
  background: white;
  box-shadow: 0 3px 15px rgba(0,0,0,0.08);
  transition: all 0.3s ease;
}

.publication-card:hover {
  box-shadow: 0 8px 25px rgba(0,0,0,0.15);
  transform: translateY(-2px);
}

.publication-text {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.pub-title {
  font-size: 16px;
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 8px;
  line-height: 1.4;
}

.pub-venue {
  font-size: 14px;
  color: #7f8c8d;
  font-style: italic;
  margin-bottom: 10px;
}

.pub-description {
  font-size: 13px;
  color: #555;
  line-height: 1.5;
}

.publication-visual {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.diagram-img {
  width: 100%;
  aspect-ratio: 16/9;
  object-fit: cover;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.diagram-caption {
  font-size: 11px;
  color: #666;
  text-align: center;
  margin-top: 6px;
  font-style: italic;
}

/* 响应式设计 */
@media (max-width: 900px) {
  .publication-card {
    grid-template-columns: 1fr;
    gap: 15px;
  }
  
  .publication-visual {
    order: -1;
  }
}
</style>

<h2>Publications</h2>

<div class="publications-grid">
  
  <div class="publication-card">
    <div class="publication-text">
      <div class="pub-title">
        DDIR: Domain-Disentangled Invariant Representation Learning for Tailored Predictions
      </div>
      <div class="pub-venue">Knowledge-Based Systems 2025</div>
      <div class="pub-description">
        提出了域解耦不变表示学习方法，通过有效分离域特定和域不变特征，实现跨域场景下的精准预测。
      </div>
    </div>
    <div class="publication-visual">
      <img src="/images/ddir-method.jpg" alt="DDIR Method" class="diagram-img">
      <div class="diagram-caption">DDIR方法示意图</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-text">
      <div class="pub-title">
        Grade-Skewed Domain Adaptation for Diabetic Retinopathy Grading
      </div>
      <div class="pub-venue">IEEE Trans. Medical Imaging 2024</div>
      <div class="pub-description">
        针对医学图像分析中的等级偏斜问题，开发了非对称双分类器方法，显著提升糖尿病视网膜病变诊断准确率。
      </div>
    </div>
    <div class="publication-visual">
      <img src="/images/retinopathy-system.jpg" alt="Retinopathy System" class="diagram-img">
      <div class="diagram-caption">视网膜病变分级系统</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-text">
      <div class="pub-title">
        Class-imbalanced Time Series Adaptation via Multi-Expert Consistency
      </div>
      <div class="pub-venue">IEEE BIBM 2024</div>
      <div class="pub-description">
        通过多专家一致性熵最小化策略，有效解决时间序列数据中的类别不平衡和域适应双重挑战。
      </div>
    </div>
    <div class="publication-visual">
      <img src="/images/timeseries-experts.jpg" alt="Time Series Experts" class="diagram-img">
      <div class="diagram-caption">多专家时间序列模型</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-text">
      <div class="pub-title">
        Multi-Source Domain-Adversarial Generalization via Dynamic Domain-Weighted Contrastive Learning
      </div>
      <div class="pub-venue">ECAI 2023</div>
      <div class="pub-description">
        摆脱传统自域感知限制，通过动态域加权对比学习实现更强的多源域泛化能力。
      </div>
    </div>
    <div class="publication-visual">
      <img src="/images/multisource-framework.jpg" alt="Multi-source Framework" class="diagram-img">
      <div class="diagram-caption">多源域泛化框架</div>
    </div>
  </div>
</div>


### Footprint

<iframe src="/talkmap/map.html" height="700" width="850" style="border:none;"></iframe>
