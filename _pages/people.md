---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---

{% include base_path %}

You can find out more about our lab members by clicking the links below their
names, including their
personal websites (<i class="fa fa-link" aria-hidden="true"></i>),
GitHub profiles (<i class="fa fa-github" aria-hidden="true"></i>), and
OSF profiles (<i class="ai ai-fw ai-osf"></i>).

## Current lab members

{% for post in site.people_current %}
  {% include archive-people.html %}
{% endfor %}

## Past lab members

{% for post in site.people_past %}
  {% include archive-people.html %}
{% endfor %}
