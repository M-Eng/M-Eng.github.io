---
header:
  teaser: "elephant-in-the-room-teaser.png"
title: "Addressing the Elephant in the Room: Robust Animal Re-Identification with Unsupervised Part-Based Feature Alignment"
collection: publications
permalink: /publications/elephant-in-the-room
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-06-17
venue: 'CVPRW'
paperurl: '/files/papers/Yu et al. - 2024 - Addressing the Elephant in the Room - Robust Animal Re-Identification with Unsupervised Part-Based Feature Alignment.pdf'
# suppurl: '/files/supplementaries/Vidit et al. - 2023 - Supplementary CLIP the Gap A Single Domain Generalization Approach for Object Detection.pdf'
codeurl: 'https://github.com/Chloe-Yu/Animal-Re-ID'
posterurl: '/files/posters/elephant-in-the-room.pdf'
# talkurl: '/files/talks/bean-slides.pdf'
# videourl: 'https://www.youtube.com/watch?v=WDUu3gar4hY&ab_channel=Vidits'
authors: 'Y. Yu, Vidit, A. Davydov, M. Engilberge, P. Fua'


---
## Abstract

Animal Re-ID is crucial for wildlife conservation, yet it faces unique challenges compared to person Re-ID. First, the scarcity and lack of diversity in datasets lead to background-biased models. Second, animal Re-ID depends on subtle, species-specific cues, further complicated by variations in pose, background, and lighting. This study addresses background biases by proposing a method to systematically remove backgrounds in both training and evaluation phases. And unlike prior works that depend on pose annotations, our approach utilizes an unsupervised technique for feature alignment across body parts and pose variations, enhancing practicality. Our method achieves superior results on three key animal Re-ID datasets: ATRW, YakReID-103, and ELPephants.

## Links

{% if page.paperurl %} [Paper]({{ base_path }}{{ page.paperurl }}){: .btn .btn--info} {% endif %} {% if page.suppurl %} [Suppl.]({{ base_path }}{{ page.suppurl }}){: .btn .btn--info} {% endif %} {% if page.codeurl %} [Code]({{ page.codeurl }}){: .btn .btn--info} {% endif %} {% if page.dataurl %} [Data]({{ base_path }}{{ page.dataurl }}){: .btn .btn--info} {% endif %} {% if page.posterurl %} [Poster]({{ base_path }}{{ page.posterurl }}){: .btn .btn--info} {% endif %} {% if page.videourl %} [Video]({{ page.videourl }}){: .btn .btn--info} {% endif %} {% if page.talkurl %} [Talk]({{ page.talkurl }}){: .btn .btn--info} {% endif %}

## Citation

If you found this work useful, please cite the associated paper:

<div class="notice--info">
Yu, Y., Vidit, V., Davydov, A., Engilberge, M., & Fua, P."Addressing the Elephant in the Room: Robust Animal Re-Identification with Unsupervised Part-Based Feature Alignment" in Proceedings of CV4Animals CVPRW. 2024.
</div>

<div class="notice--info" markdown="1">
**BibTex:**
~~~~~~~~
@inproceedings{yu2024elephant,
  title={Addressing the Elephant in the Room: Robust Animal Re-Identification with Unsupervised Part-Based Feature Alignment},
  author={Yu, Yingxue, Vidit Vidit, Andrey Davydov, Martin Engilberge, and Pascal Fua.},
  booktitle={Proceedings of CV4Animals CVPR Workshop.},
  year={2024}
}
~~~~~~~~
</div>
