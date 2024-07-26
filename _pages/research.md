---
layout: archive
title: "Research"
permalink: /research
author_profile: true
---

## Published Research
{% include base_path %}

{% for post in site.research-published reversed %}
  {% include archive-single.html %}
{% endfor %}

## Work in Progress
{% include base_path %}

{% for post in site.research-in-progress reversed %}
  {% include archive-single.html %}
{% endfor %}

