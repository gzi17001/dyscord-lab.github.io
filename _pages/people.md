---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---

{% include base_path %}

You can find out more about our lab members by clicking the links below their
names, including their
personal websites <nobr>(<i class="fa fa-link" aria-hidden="true"></i>)</nobr>,
GitHub profiles <nobr>(<i class="fab fa fa-github" aria-hidden="true"></i>)</nobr>,
and OSF profiles <nobr>(<i class="ai ai-fw ai-osf"></i>)</nobr>.

## Current lab members

{% for post in site.people_current %}
  {% include archive-people.html %}
{% endfor %}

## Past lab members

{% for post in site.people_past %}
  {% include archive-people.html %}
{% endfor %}
