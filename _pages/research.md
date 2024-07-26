---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Published Research
{% include base_path %}

{% for post in site.research-published reversed %}
  {% include archive-single.html %}
{% endfor %}

Work in Progress
{% include base_path %}

{% for post in site.research-in-progress reversed %}
  {% include archive-single.html %}
{% endfor %}

<div class="wordwrap">You can also find my articles on <a href="{{https://scholar.google.com/citations?user=xFVVMNoAAAAJ&hl=en&oi=ao}}">my Google Scholar profile</a>.</div>


