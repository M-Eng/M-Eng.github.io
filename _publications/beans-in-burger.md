---
header:
  teaser: "beans-in-burger-teaser.png"
title: "Finding Beans in Burgers: Deep Semantic-Visual Embedding with Localization"
collection: publications
permalink: /publications/beans-in-burger
excerpt: ''
date: 2018-06-18
venue: 'CVPR'
paperurl: 'http://m-eng.github.io/files/papers/Engilberge et al. - 2018 - Finding Beans in Burgers Deep Semantic-Visual Emb.pdf'
codeurl: 'https://github.com/M-Eng/dsve-loc'
posterurl: 'http://m-eng.github.io/files/posters/bean-poster.pdf'
talkurl: 'http://m-eng.github.io/files/talks/bean-slides.pdf'
author: 'Engilberge, Martin and Chevallier, Louis and Pérez, Patrick and Cord, Matthieu'
---

## Abstract

Several works have proposed to learn a two-path neural
network that maps images and texts, respectively, to a same
shared Euclidean space where geometry captures useful semantic relationships. Such a multi-modal embedding can be
trained and used for various tasks, notably image captioning. In the present work, we introduce a new architecture
of this type, with a visual path that leverages recent spaceaware pooling mechanisms. Combined with a textual path
which is jointly trained from scratch, our semantic-visual
embedding offers a versatile model. Once trained under the
supervision of captioned images, it yields new state-of-theart performance on cross-modal retrieval. It also allows the
localization of new concepts from the embedding space into
any input image, delivering state-of-the-art result on the visual grounding of phrases.

## Links

{% if paperurl %}
    <a href=" {{ paperurl }} " class="btn btn--info">Paper</a>
{% endif %}
{% if codeurl %}
    <a href=" {{ codeurl }} " class="btn btn--info">Code</a>
{% endif %}
{% if dataurl %}
    <a href=" {{ dataurl }} " class="btn btn--info">Data</a>
{% endif %}
{% if posterurl %}
    <a href=" {{ posterurl }} " class="btn btn--info">Poster</a>
{% endif %}
{% if talkurl %}
    <a href=" {{ talkurl }} " class="btn btn--info">Talk</a>
{% endif %}

## Citation
<pre>
@inproceedings{engilbergeFinding2018,
  title = {Finding Beans in Burgers: Deep Semantic-Visual Embedding with Localization},
  booktitle = {Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  author = {Engilberge, Martin and Chevallier, Louis and Pérez, Patrick and Cord, Matthieu},
  year = {2018},
  pages = {3984--3993}
}
</pre>

<div class="notice--info">
>@inproceedings{engilbergeFinding2018,
>  title = {Finding Beans in Burgers: Deep Semantic-Visual Embedding with Localization},
>  booktitle = {Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
>  author = {Engilberge, Martin and Chevallier, Louis and Pérez, Patrick and Cord, Matthieu},
>  year = {2018},
>  pages = {3984--3993}
>}
</div>