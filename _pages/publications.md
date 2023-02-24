---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

For a complete list of my publications please see: <u><a href="{{https://scholar.google.com/citations?user=IPDByA8AAAAJ&hl=en}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
