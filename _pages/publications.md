---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
See full publications in my [google scholar](https://scholar.google.com/citations?user=BWfPrE4AAAAJ)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
