---
permalink: /open-positions
title: "Open Positions"
excerpt:
author_profile: true
redirect_from: 
  - /open-positions/
  - /open-positions.html
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
