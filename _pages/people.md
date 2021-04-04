---
layout: archive
title: "People"
permalink: /people/
author_profile: true
redirect_from:
  - /members
---

{% include base_path %}

{% for post in site.people %}
  {% include archive-people.html %}
{% endfor %}
