---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---

{% include base_path %}

## Current lab members

{% for post in site.people_current %}
  {% include archive-people.html %}
{% endfor %}

## Past lab members

{% for post in site.people_past %}
  {% include archive-people.html %}
{% endfor %}
