---
layout: archive
title: "Research"
permalink: /research
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">For additional information, see <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

## Published Research
**[Racial differences in parent response to COVID schooling policies](https://micah-baum.github.io/files/baum-jacob-pnas-2024.pdf)**
with Brian A. Jacob. _Proceedings of the National Academy of Sciences_, 2024. 


{% for post in site.research-published reversed %}
  {% include archive-single.html %}
{% endfor %}

## Work in Progress
{% for post in site.research-in-progress reversed %}
  {% include archive-single.html %}
{% endfor %}

