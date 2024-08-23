---
layout: archive
title: "Workshops"
permalink: /workshops/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.category == 'workshops' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
