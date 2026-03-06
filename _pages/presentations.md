---
layout: archive
title: "Presentations"
permalink: /presentations/
author_profile: true
---

## Talks
{% include base_path %}
{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}

## Posters
{% for post in site.posters reversed %}
  {% include archive-single.html %}
{% endfor %}