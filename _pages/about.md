---
layout: archive
permalink: /
title: "Academic profile"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! I am a Master student in the [Biomedical imaging, vision and learning laboratory](http://www.bivl2ab.uis.edu.co/) 
from the [Escuela de Ingeniería de Sistemas e Informática](http://cormoran.uis.edu.co/eisi/) at
[Universidad Industrial de Santander](https://www.uis.edu.co/webUIS/es/index.jsp). 

My research focuses on computer vision topics applied to different applications using machine learning and deep learning models. However, I have worked in areas outside of computer vision by analyzing other types of information. In summary, the applications where I have a lot of experience are the following:

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
