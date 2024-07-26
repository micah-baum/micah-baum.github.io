---
layout: archive
title: "Research"
permalink: /research
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">For a full list of publications, see <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

## Published Research
{% for post in site.research-published reversed %}
  {% include archive-single.html %}
{% endfor %}

## Work in Progress
{% for post in site.research-in-progress reversed %}
  {% include archive-single.html %}
{% endfor %}

