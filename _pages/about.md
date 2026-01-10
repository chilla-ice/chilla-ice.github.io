---
layout: single
title: "Hello!"
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I’m a second-year PhD student in Electrical & Computer Engineering at Duke, supervised by Prof. Tania Roy. My research explores emerging semiconductor device design and reliability physics. Beyond the lab, I read and travel to feel the world. 

## Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
