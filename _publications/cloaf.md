---
header:
  teaser: "cloaf-teaser.pdf"
title: "CLOAF: CoLlisiOn-Aware Human Flow"
collection: publications
permalink: /publications/cloaf
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-06-20
venue: 'CVPR'
paperurl: '/files/papers/Davydov Andrey et al. - 2024 - CLOAF - CoLlisiOn-Aware Human Flow.pdf'
suppurl: '/files/supplementaries/Davydov Andrey et al. - 2024 - Supplementary CLOAF - CoLlisiOn-Aware Human Flow.pdf'
# codeurl: 'https://github.com/cvlab-epfl/CLOAF'
posterurl: '/files/posters/cloaf-poster.pdf'
# talkurl: '/files/talks/bean-slides.pdf'
# videourl: 'https://www.youtube.com/watch?v=WDUu3gar4hY&ab_channel=Vidits'
authors: 'D. Andrey, M. Engilberge, M. Salzmann, and P. Fua.'


---
## Abstract

Even the best current algorithms for estimating body 3D shape and pose yield results that include body self-intersections. In this paper, we present CLOAF, which exploits the diffeomorphic nature of Ordinary Differential Equations to eliminate such self-intersections while still imposing body shape constraints. We show that, unlike earlier approaches to addressing this issue, ours completely eliminates the self-intersections without compromising the accuracy of the reconstructions. 
Being differentiable, CLOAF can be used to fine-tune pose and shape estimation baselines to improve their overall performance and eliminate self-intersections in their predictions. Furthermore, we demonstrate how our CLOAF strategy can be applied to practically any motion field induced by the user.
CLOAF also makes it possible to edit motion to interact with the environment without worrying about potential collision or loss of body-shape prior.

## Links

{% if page.paperurl %} [Paper]({{ base_path }}{{ page.paperurl }}){: .btn .btn--info} {% endif %} {% if page.suppurl %} [Suppl.]({{ base_path }}{{ page.suppurl }}){: .btn .btn--info} {% endif %} {% if page.codeurl %} [Code]({{ page.codeurl }}){: .btn .btn--info} {% endif %} {% if page.dataurl %} [Data]({{ base_path }}{{ page.dataurl }}){: .btn .btn--info} {% endif %} {% if page.posterurl %} [Poster]({{ base_path }}{{ page.posterurl }}){: .btn .btn--info} {% endif %} {% if page.videourl %} [Video]({{ page.videourl }}){: .btn .btn--info} {% endif %} {% if page.talkurl %} [Talk]({{ page.talkurl }}){: .btn .btn--info} {% endif %}

## Citation

If you found this work useful, please cite the associated paper:

<div class="notice--info">
Davydov, Andrey, Martin Engilberge, Mathieu Salzmann, and Pascal Fua, “CLOAF: CoLlisiOn-Aware Human Flow” in Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2024.
</div>

<div class="notice--info" markdown="1">
**BibTex:**
~~~~~~~~
@inproceedings{davydov2024cloaf,
  title={CLOAF: CoLlisiOn-Aware Human Flow.},
  author={Davydov, Andrey, Martin Engilberge, Mathieu Salzmann, and Pascal Fua},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2024}
}
~~~~~~~~
</div>
