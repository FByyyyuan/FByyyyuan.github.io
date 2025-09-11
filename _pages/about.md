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
        A domain decoupling invariant representation learning method is proposed, which effectively separates DOI and domain-invariant features to achieve accurate predictions in cross-domain scenarios.
      </div>
    </div>
    <div class="publication-visual">
      <img src="/files/FB004.jpg" alt="DDIR Method" class="diagram-img">
      <div class="diagram-caption">DDIR method</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-text">
      <div class="pub-title">
        Grade-Skewed Domain Adaptation via Asymmetric Bi-Classifier Discrepancy Minimization for Diabetic Retinopathy Grading
      </div>
      <div class="pub-venue">IEEE Transactions on Medical Imaging 2024</div>
      <div class="pub-description">
        To address the issue of grade skew in medical image analysis, an asymmetric dual classifier method was developed, which significantly improved the diagnostic accuracy.
      </div>
    </div>
    <div class="publication-visual">
      <img src="/files/FB003-2.png" alt="Retinopathy System" class="diagram-img">
      <div class="diagram-caption">ABiD grading system</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-text">
      <div class="pub-title">
        Class-imbalanced time series domain adaptation via multi-expert consistency entropy minimization
      </div>
      <div class="pub-venue">IEEE International Conference on Bioinformatics and Biomedicine 2024</div>
      <div class="pub-description">
        By adopting the multi-expert consistency entropy minimization strategy, we effectively address the dual challenges of the reliability of the enhancement method and the domain adaptation for the imbalance of categories in time series data.
      </div>
    </div>
    <div class="publication-visual">
      <img src="/files/FB002-2.jpg" alt="Time Series Experts" class="diagram-img">
      <div class="diagram-caption">MECEM framework</div>
    </div>
  </div>

  <div class="publication-card">
    <div class="publication-text">
      <div class="pub-title">
        Letting Go of Self-Domain Awareness: Multi-Source Domain-Adversarial Generalization via Dynamic Domain-Weighted Contrastive Transfer Learning
      </div>
      <div class="pub-venue">European Conference on Artificial Intelligence 2023 </div>
      <div class="pub-description">
        By breaking away from the limitations of traditional self-domain perception, stronger multi-source domain generalization capabilities are achieved through dynamic domain-weighted contrastive learning.
      </div>
    </div>
    <div class="publication-visual">
      <img src="/files/FB001.png" alt="Multi-source Framework" class="diagram-img">
      <div class="diagram-caption">MsCtrl framework</div>
    </div>
  </div>
</div>


### Footprint

<iframe src="/talkmap/map.html" height="700" width="850" style="border:none;"></iframe>
