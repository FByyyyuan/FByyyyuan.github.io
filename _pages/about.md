---
permalink: /
title: "About Me"
author_profile: true
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
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<div id="visitor-map" style="height: 400px; width: 100%;"></div>
fetch('https://ipinfo.io/json?token=YOUR_API_TOKEN')  // 替换为你的 ipinfo.io API Token
  .then(response => response.json())
  .then(data => {
    const loc = data.loc.split(','); // 获取经纬度，格式为 'latitude,longitude'
    const latitude = loc[0];
    const longitude = loc[1];
    const map = L.map('visitor-map').setView([latitude, longitude], 2);
    L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png').addTo(map);
    L.marker([latitude, longitude]).addTo(map)
      .bindPopup('Visitor Location: ' + data.city + ', ' + data.country)
      .openPopup();
  })
  .catch(err => console.log('Error getting geolocation: ', err));
