---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
You can also find my articles on <a href="{{author.googlescholar}}">my Google Scholar profile</a>.
{% endif %}

{% assign pubs = site.publications | sort: "date" | reverse %}
{% assign current_year = "0" %}

{% for post in pubs %}
{% assign post_year = post.date | date: "%Y" %}
{% if post_year != current_year %}
{% unless forloop.first %}
</ul>
</details>
{% endunless %}
<details open>
<summary><strong>{{ post_year }}</strong></summary>
<ul>
{% assign current_year = post_year %}
{% endif %}
<li>
<a href="{{ post.link | default: post.url }}">{{ post.title }}</a>, {{ post.venue | default: "Preprint" }}.
</li>
{% endfor %}

</ul>
</details>

<br>
<small><sup>*</sup> Equal authorship statement</small>
