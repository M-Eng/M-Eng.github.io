---
header:
  teaser: "videomem-teaser.png"
title: "VideoMem: Constructing, Analyzing, Predicting Short-Term and Long-Term Video Memorability"
collection: publications
permalink: /publications/videomem
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2019-10-27
venue: 'ICCV'
paperurl: 'http://m-eng.github.io/files/papers/Cohendet et al. - 2019 - VideoMem Constructing, Analyzing, Predicting Shor.pdf'
dataurl: 'https://www.interdigital.com/data_sets/video-memorability-dataset'
authors: 'R. Cohendet, C. Demarty, N. Duong, M. Engilberge'
---

## Abstract

Humans share a strong tendency to memorize/forget
some of the visual information they encounter. This paper focuses on understanding the intrinsic memorability of
visual content. To address this challenge, we introduce a
large scale dataset (VideoMem) composed of 10,000 videos
with memorability scores. In contrast to previous work on
image memorability – where memorability was measured a
few minutes after memorization – memory performance is
measured twice: a few minutes and again 24-72 hours after
memorization. Hence, the dataset comes with short-term
and long-term memorability annotations. After an in-depth
analysis of the dataset, we investigate various deep neural network-based models for the prediction of video memorability. Our best model using a ranking loss achieves a
Spearman’s rank correlation of 0.494 (respectively 0.256)
for short-term (resp. long-term) memorability prediction,
while our model with attention mechanism provides insights
of what makes a content memorable. The VideoMem dataset
with pre-extracted features is publicly available.

## Links

{% if page.paperurl %} [Paper]({{ page.paperurl }}){: .btn .btn--info} {% endif %} {% if page.codeurl %} [Code]({{ page.codeurl }}){: .btn .btn--info} {% endif %} {% if page.dataurl %} [Data]({{ page.dataurl }}){: .btn .btn--info} {% endif %} {% if page.posterurl %} [Poster]({{ page.posterurl }}){: .btn .btn--info} {% endif %} {% if page.talkurl %} [Slides]({{ page.talkurl }}){: .btn .btn--info} {% endif %}

## Citation

If you found this work useful, please cite the associated paper:

<div class="notice--info">
R. Cohendet, C.-H. Demarty, N. Q. K. Duong, and M. Engilberge, “VideoMem: Constructing, Analyzing, Predicting Short-Term and Long-Term Video Memorability,” in Proceedings of the IEEE International Conference on Computer Vision, 2019, pp. 2531–25
</div>

<div class="notice--info" markdown="1">
**BibTex:**
~~~~~~~~
@inproceedings{engilbergeFinding2018,
  title = {VideoMem: Constructing, Analyzing, Predicting Short-Term and Long-Term Video Memorability},
  booktitle = {Proceedings of the IEEE International Conference on Computer Vision},
  author = {Cohendet, Romain and Demarty, Claire-Helene and Duong, Ngoc Q. K. and Engilberge, Martin},
  year = {2019},
  pages = {2531--2540}
}
~~~~~~~~
</div>
