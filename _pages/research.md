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

My primary research interests are in the fields of Machine Learning, Computer Vision and Natural Language Processing.  

From 2017 to 2020, I did a PhD thesis focused on joint visual and textual learning, specifically on Visual-Semantic Embeddings (VSE).  
I was advised by [Matthieu Cord](http://webia.lip6.fr/~cord/), [Patrick Pérez](https://ptrckprz.github.io/) and Louis Chevallier.  
During this time I worked on multimodal representation learning applied to multiple tasks: cross-modal retrieval, phrase grounding, ranking optimization, known instance search and iterative search.  

I am excited about the upcoming research challenges, with a keen interest in exploring self-supervised and reasoning methods to bring multimodal interaction to the next level.

# Projects

{% include publi_grid_wrapper.html %}

# Talks

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}