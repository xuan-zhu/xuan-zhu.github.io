---
layout: archive
title: "Work in Progress"
permalink: /projects/
author_profile: true
---

I figured it out

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
