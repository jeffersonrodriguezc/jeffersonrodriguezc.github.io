---
permalink: /
title: "Academic profile"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Welcome! I am a Postdoctoral Research Fellow in the
[Weidenbaum Center on the Economy, Government, and Public Policy](https://wc.wustl.edu/) 
and [Department of Political Science](https://polisci.wustl.edu/) at
[Washington University in St. Louis](https://wustl.edu/). I am also an
affiliated researcher with the [Data-driven Analysis of Peacekeeping Project](https://dapp-lab.org)
lab. I specialize in International Relations and Political Methodology. I earned
my Ph.D in Political Science from the
[University *of* North Carolina *at* Chapel Hill](https://www.unc.edu/) and my
B.A. in Political Science from [Haverford College](https://www.haverford.edu/).

My research falls into two main areas: understanding patterns of rebel behavior before, during, and after civil conflict, and developing new tools to improve the study of peace and conflict. One strand of research explores how the territories that ethnic groups inhabit shape rebel group formation and condition their relationship with the state. This interest in rebel behavior also informs projects on the evolution of government repression and rebel killings of civilians over the course of a conflict.

My other main research agenda uses advanced methods to allow us to ask new questions in the study of peace and conflict. One project uses Bayesian item response theory to measure the strength of peace agreements as a latent variable and free researchers from post-treatment bias caused by using the duration of agreements as a proxy for their strength. In another project, I use visual imagery contained in Salafi jihadist propaganda videos to detect similiarties in videos produced by different groups, allowing researchers to estimate collaboration networks within a broader clandestine movement. Other work uses over two billion observations of international trade data to develop new measures of economic interdependence and methods to detect disruptions of regular economic exchange between states.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
