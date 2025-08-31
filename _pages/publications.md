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
{% if post.abstract %}
<p style="font-size: 0.9em; margin-top: 5px;">{{ post.abstract }}</p>
{% endif %}
<p style="font-size: 0.9em;">
{% if post.link %}<a href="{{ post.link }}">Paper</a> | {% endif %}
{% if post.quote %}<a href="{{ post.quote }}">Citation</a> | {% endif %}
{% if post.code %} <a href="{{ post.code }}">Code</a> | {% endif %}
</p>
</li>
{% endfor %}

</ul>
</details>

<br>
<small><sup>*</sup> Equal authorship statement</small>
