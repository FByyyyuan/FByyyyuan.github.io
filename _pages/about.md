---
permalink: /
title: "About Me"
author_profile: true
layout: archive
redirect_from: 
  - /about/
  - /about.html
---

I am Yuan Ma from Beijing, China. I am a Ph.D. student at Institute Of Computing Technology advised by Prof. Yiqiang Chen, and I work primarily in the intersection of transfer learning algorithms and applications in ubiquitous computing.

### Research Interests:
- **Transfer Learning： Domain Adaptation and Generalization**  
- **AI for Healthcare**

### Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-photo.html %}
  {% endfor %}</ul>

<p>This map is generated from a Jupyter Notebook file in <a href="https://github.com/academicpages/academicpages.github.io/blob/master/_talks/talkmap.ipynb">/_talks/talkmap.ipynb</a>, which mines the location fields in the .md files in _talks/.</p>
<iframe src="/talkmap/map.html" height="700" width="850" style="border:none;"></iframe>
