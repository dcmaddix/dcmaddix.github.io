---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

For a complete list of my publications please see: [my Google Scholar profile](https://scholar.google.com/citations?user=IPDByA8AAAAJ&hl=en).

## Selected Publications

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
