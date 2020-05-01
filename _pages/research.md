---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
entries_layout: "grid"
# toc: true
# toc_label: "My Table of Contents"
# toc_icon: "cog"
---

{% comment %}
<!-- {% include toc %} -->
{% endcomment %}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% include publi_grid_wrapper.html %}

{% comment %}
<!-- {% for post in site.publications reversed %}
  {% include archive-single-publi.html type="grid" %}
{% endfor %} -->
{% endcomment %}