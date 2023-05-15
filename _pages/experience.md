---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
redirect_from:
  - /experience
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.experience reversed %}
  {% include archive-single.html %}
{% endfor %}
