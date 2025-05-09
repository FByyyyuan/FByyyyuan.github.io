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
- **Transfer Learning： Domain Adaptation and Generalization**  
- **AI for Healthcare**

### Publications
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>



### Footprint

<iframe src="/talkmap/map.html" height="700" width="850" style="border:none;"></iframe>
