---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
# toc: true
# toc_label: "My Table of Contents"
# toc_icon: "cog"
---

{% comment %}
<!-- {% include toc %} -->
{% endcomment %}

{% include base_path %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Projects

{% include publi_grid_wrapper.html %}

# Talks

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}