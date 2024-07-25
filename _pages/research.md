---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{https://scholar.google.com/citations?user=xFVVMNoAAAAJ&hl=en&oi=ao}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

