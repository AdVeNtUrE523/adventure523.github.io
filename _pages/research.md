---
layout: archive
title: "Working Paper"
permalink: /research/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">
    You can also find my articles on 
    <a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.
  </div>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html post=post %}
{% endfor %}

## Frictionless Inflation 
with [*Miguel Bandeira*](https://sites.google.com/view/miguelbandeira/home) and [*Laura-Castillo Martinez*](https://www.lcastillo-martinez.com)

