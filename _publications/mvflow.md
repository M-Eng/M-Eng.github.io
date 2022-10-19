---
header:
  teaser: "mvflow-teaser.png"
title: "Multi-view Tracking Using Weakly Supervised Human Motion Prediction"
collection: publications
permalink: /publications/mvflow
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-01-03
venue: 'WACV'
paperurl: '/files/papers/Engilberge et al. - 2023 - Multi-view Tracking Using Weakly Supervised Human Motion Prediction.pdf'
suppurl: '/files/supplementaries/Engilberge et al. - 2023 - Supplementary Multi-view Tracking Using Weakly Supervised Human Motion Prediction.pdf'
codeurl: 'https://github.com/cvlab-epfl/MVFlow'
# posterurl: '/files/posters/bean-poster.pdf'
# talkurl: '/files/talks/bean-slides.pdf'
authors: 'M. Engilberge, W. Liu, P. Fua '
---
## Abstract

Multi-view approaches to people-tracking have the potential to better handle occlusions than single-view ones in crowded scenes. They often rely on the tracking-by-detection paradigm, which involves detecting people first and then connecting the detections. In this paper, we argue that an even more effective approach is to predict people motion over time and infer people’s presence in individual frames from these. This enables to enforce consistency both over time and across views of a single temporal frame. We validate our approach on the PETS2009 and WILDTRACK datasets and demonstrate that it outperforms state-of-the-art methods.

## Links

{% if page.paperurl %} [Paper]({{ base_path }}{{ page.paperurl }}){: .btn .btn--info} {% endif %} {% if page.suppurl %} [Suppl.]({{ base_path }}{{ page.suppurl }}){: .btn .btn--info} {% endif %} {% if page.codeurl %} [Code]({{ page.codeurl }}){: .btn .btn--info} {% endif %} {% if page.dataurl %} [Data]({{ base_path }}{{ page.dataurl }}){: .btn .btn--info} {% endif %} {% if page.posterurl %} [Poster]({{ base_path }}{{ page.posterurl }}){: .btn .btn--info} {% endif %} {% if page.talkurl %} [Slides]({{ base_path }}{{ page.talkurl }}){: .btn .btn--info} {% endif %}

## Citation

If you found this work useful, please cite the associated paper:

<div class="notice--info">
M. Engilberge, W. Liu, and P. Fua, “Multi-view Tracking Using Weakly Supervised Human Motion Prediction” in Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision, Jan. 2023
</div>

<div class="notice--info" markdown="1">
**BibTex:**
~~~~~~~~
@inproceedings{engilber2023multi,
  title={Multi-view Tracking Using Weakly Supervised Human Motion Prediction},
  author={Engilberge, Martin and Liu, Weizhe and Fua, Pascal},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  year={2023}
}
~~~~~~~~
</div>
