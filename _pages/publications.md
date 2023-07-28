---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <a href="https://scholar.google.com/citations?user=c71tf4oAAAAJ&hl=en">my Google Scholar profile</a>.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
