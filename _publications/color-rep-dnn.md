---
header:
  teaser: "color-rep-dnn-teaser.png"
title: "Color Representation in Deep Neural Networks"
collection: publications
permalink: /publications/color-representation-dnn
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2017-09-17
venue: 'ICIP'
paperurl: '/files/papers/Engilberge et al. - 2017 - Color representation in deep neural networks.pdf'
posterurl: '/files/posters/color-rep-poster.pdf'
authors: 'M. Engilberge, E. Collins, S. Susstrunk'
---
## Abstract

Convolutional neural networks are top-performers on image
classification tasks. Understanding how they make use of
color information in images may be useful for various tasks.
In this paper we analyze the representation learned by a popular CNN to detect and characterize color-related features.
We confirm the existence of some object- and color-specific
units, as well as the effect of layer-depth on color-sensitivity
and class-invariance.

## Links

{% if page.paperurl %} [Paper]({{ base_path }}{{ page.paperurl }}){: .btn .btn--info} {% endif %} {% if page.codeurl %} [Code]({{ base_path }}{{ page.codeurl }}){: .btn .btn--info} {% endif %} {% if page.dataurl %} [Data]({{ base_path }}{{ page.dataurl }}){: .btn .btn--info} {% endif %} {% if page.posterurl %} [Poster]({{ base_path }}{{ page.posterurl }}){: .btn .btn--info} {% endif %} {% if page.talkurl %} [Slides]({{ base_path }}{{ page.talkurl }}){: .btn .btn--info} {% endif %}

## Citation

If you found this work useful, please cite the associated paper:

<div class="notice--info">
M. Engilberge, E. Collins, and S. Susstrunk, “Color representation in deep neural networks,” in Proceedings of the IEEE International Conference on Image Processing, Sep. 2017, pp. 2786–2790
</div>

<div class="notice--info" markdown="1">
**BibTex:**
~~~~~~~~
@inproceedings{engilbergeColor2017,
  title = {Color Representation in Deep Neural Networks},
  booktitle = {Proceedings of the IEEE International Conference on Image Processing}
  author = {Engilberge, Martin and Collins, Edo and Susstrunk, Sabine},
  year = {2017},
  pages = {2786--2790}
}
~~~~~~~~
</div>
