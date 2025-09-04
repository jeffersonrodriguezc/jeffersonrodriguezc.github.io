---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<div class="about-content">
  <p>
    Below you’ll find my publications organized by year. Each entry keeps quick-access icons for
    the paper, code, dataset, and citation when available.
  </p>
</div>

{% assign pubs_sorted = site.publications | sort: "date" | reverse %}
{% assign pubs_by_year = pubs_sorted | group_by_exp: "post", "post.date | date: '%Y'" %}

{% for year_group in pubs_by_year %}
  <h2 class="archive__subtitle">{{ year_group.name }}</h2>

  {% for post in year_group.items %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}

<sup>*</sup> Equal authorship statement

