---
header:
  teaser: "mvaug-teaser.png"
title: "Two-level Data Augmentation for Calibrated Multi-view Detection"
collection: publications
permalink: /publications/mvaug
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-01-03
venue: 'WACV'
paperurl: '/files/papers/Engilberge et al. - 2023 - Two-level Data Augmentation for Calibrated Multiview Detection.pdf'
codeurl: 'https://github.com/cvlab-epfl/MVAug'
# posterurl: '/files/posters/bean-poster.pdf'
# talkurl: '/files/talks/bean-slides.pdf'
authors: 'M. Engilberge, H. Shi, Z. Wang, P. Fua'
---
## Abstract

Data augmentation has proven its usefulness to improve model generalization and performance. While it is commonly applied in computer vision application when it comes to multi-view systems, it is rarely used. Indeed geometric data augmentation can break the alignment among views. This is problematic since multi-view data tend to be scarce and it is expensive to annotate.
In this work we propose to solve this issue by introducing a new multi-view data augmentation pipeline that preserves alignment among views. Additionally to traditional augmentation of the input image we also propose a second level of augmentation applied directly at the scene level. When combined with our simple multi-view detection model, our two-level augmentation pipeline outperforms all existing baselines by a significant margin on the two main multi-view multi-person detection datasets WILDTRACK and MultiviewX.

## Links

{% if page.paperurl %} [Paper]({{ base_path }}{{ page.paperurl }}){: .btn .btn--info} {% endif %} {% if page.codeurl %} [Code]({{ page.codeurl }}){: .btn .btn--info} {% endif %} {% if page.dataurl %} [Data]({{ base_path }}{{ page.dataurl }}){: .btn .btn--info} {% endif %} {% if page.posterurl %} [Poster]({{ base_path }}{{ page.posterurl }}){: .btn .btn--info} {% endif %} {% if page.talkurl %} [Slides]({{ base_path }}{{ page.talkurl }}){: .btn .btn--info} {% endif %}

## Citation

If you found this work useful, please cite the associated paper:

<div class="notice--info">
M. Engilberge, H. Shi, Z. Wang, and P. Fua, “Two-level Data Augmentation for Calibrated Multi-view Detection” in Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision, Jan. 2023
</div>

<div class="notice--info" markdown="1">
**BibTex:**
~~~~~~~~
@inproceedings{engilber2023two,
	  title={Two-level Data Augmentation for Calibrated Multi-view Detection},
	  author={Engilberge, Martin and Shi, Haixin and Wang, Zhiye and Fua, Pascal},
	  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
	  year={2023}
}
~~~~~~~~
</div>
