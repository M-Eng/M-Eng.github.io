---
header:
  teaser: "sodeep-teaser.png"
title: "SoDeep: A Sorting Deep Net to Learn Ranking Loss Surrogates"
collection: publications
permalink: /publications/sodeep
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2019-06-15
venue: 'CVPR'
paperurl: 'http://m-eng.github.io/files/papers/Engilberge et al. - 2019 - SoDeep A Sorting Deep Net to Learn Ranking Loss S.pdf'
codeurl: 'https://github.com/M-Eng/sodeep'
posterurl: 'http://m-eng.github.io/files/posters/sodeep_poster.pdf'
talkurl: 'http://m-eng.github.io/files/talks/sodeep-slides.pdf'
authors: 'M. Engilberge, L. Chevallier, P. Pérez, M. Cord'
---
## Abstract

Several tasks in machine learning are evaluated using non-differentiable metrics such as mean average precision or Spearman correlation. However, their nondifferentiability prevents from using them as objective functions in a learning framework. Surrogate and relaxation
methods exist but tend to be specific to a given metric.

In the present work, we introduce a new method to learn
approximations of such non-differentiable objective functions. Our approach is based on a deep architecture that
approximates the sorting of arbitrary sets of scores. It is
trained virtually for free using synthetic data. This sorting
deep (SoDeep) net can then be combined in a plug-and-play
manner with existing deep architectures. We demonstrate
the interest of our approach in three different tasks that
require ranking: Cross-modal text-image retrieval, multilabel image classification and visual memorability ranking.
Our approach yields very competitive results on these three
tasks, which validates the merit and the flexibility of SoDeep
as a proxy for sorting operation in ranking-based losses.

## Links

{% if page.paperurl %} [Paper]({{ page.paperurl }}){: .btn .btn--info} {% endif %} {% if page.codeurl %} [Code]({{ page.codeurl }}){: .btn .btn--info} {% endif %} {% if page.dataurl %} [Data]({{ page.dataurl }}){: .btn .btn--info} {% endif %} {% if page.posterurl %} [Poster]({{ page.posterurl }}){: .btn .btn--info} {% endif %} {% if page.talkurl %} [Talk]({{ page.talkurl }}){: .btn .btn--info} {% endif %}

## Citation

If you found this work useful, please cite the associated paper:

<div class="notice--info">
M. Engilberge, L. Chevallier, P. Perez, and M. Cord, “SoDeep: A Sorting Deep Net to Learn Ranking Loss Surrogates,” in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 2019, pp. 10792–10801
</div>

<div class="notice--info" markdown="1">
**BibTex:**
~~~~~~~~
@inproceedings{engilbergeSoDeep2019,
  title = {SoDeep: A Sorting Deep Net to Learn Ranking Loss Surrogates},
  booktitle = {Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  author = {Engilberge, Martin and Chevallier, Louis and Pérez, Patrick and Cord, Matthieu},
  year = {2019},
  pages = {10792--10801}
}
~~~~~~~~
</div>