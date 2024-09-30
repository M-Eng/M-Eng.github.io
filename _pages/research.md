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

My primary research interests lie in the fields of Machine Learning, Computer Vision, and Natural Language Processing.

Since 2020, I have been working on diverse topics in machine learning and computer vision. My research encompasses object detection and tracking, domain adaptation/generalization, 3D geometry, and scene understanding.

From 2017 to 2020, I completed my PhD thesis, which focused on joint visual and textual learning, with a specific emphasis on Visual-Semantic Embeddings (VSE). During this period, I was fortunate to be advised by [Matthieu Cord](http://webia.lip6.fr/~cord/), [Patrick Pérez](https://ptrckprz.github.io/), and Louis Chevallier.

My doctoral research centered on multimodal representation learning, applying it to various tasks including cross-modal retrieval, phrase grounding, ranking optimization, known instance search, and iterative search.

Looking ahead, I am enthusiastic about tackling emerging research challenges. I have a particular interest in embodied AI, multimodal interaction, and 3D scene understanding, areas that I believe will play crucial roles in shaping the future of artificial intelligence and computer vision.

# Projects

{% include publi_grid_wrapper.html %}

# Talks

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}