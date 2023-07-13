---
header:
  teaser: "clip-the-gap-teaser.png"
title: "CLIP the Gap: A Single Domain Generalization Approach for Object Detection"
collection: publications
permalink: /publications/clip-the-gap
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-06-20
venue: 'CVPR'
paperurl: '/files/papers/Vidit et al. - 2023 - CLIP the Gap  A Single Domain Generalization Approach for Object Detection.pdf'
suppurl: '/files/supplementaries/Vidit et al. - 2023 - Supplementary CLIP the Gap  A Single Domain Generalization Approach for Object Detection.pdf'
codeurl: 'https://github.com/vidit09/domaingen'
posterurl: '/files/posters/clipthegap-poster.pdf'
talkurl: 'https://www.youtube.com/watch?v=WDUu3gar4hY&ab_channel=Vidits'
authors: 'Vidit, M. Engilberge, M. Salzmann'


---
## Abstract

Single Domain Generalization (SDG) tackles the problem of training a model on a single source domain so that it generalizes to any unseen target domain. While this has been well studied for image classification, the literature on SDG object detection remains almost non-existent. To address the challenges of simultaneously learning robust object localization and representation, we propose to leverage a pre-trained vision-language model to introduce semantic domain concepts via textual prompts. We achieve this via a semantic augmentation strategy acting on the features extracted by the detector backbone, as well as a text-based classification loss. 
    Our experiments evidence the benefits of our approach, outperforming  by 10\% the only existing SDG object detection method, Single-DGOD, on their own diverse weather-driving benchmark.

## Links

{% if page.paperurl %} [Paper]({{ base_path }}{{ page.paperurl }}){: .btn .btn--info} {% endif %} {% if page.suppurl %} [Suppl.]({{ base_path }}{{ page.suppurl }}){: .btn .btn--info} {% endif %} {% if page.codeurl %} [Code]({{ page.codeurl }}){: .btn .btn--info} {% endif %} {% if page.dataurl %} [Data]({{ base_path }}{{ page.dataurl }}){: .btn .btn--info} {% endif %} {% if page.posterurl %} [Poster]({{ base_path }}{{ page.posterurl }}){: .btn .btn--info} {% endif %} {% if page.talkurl %} [Talk]({{ page.talkurl }}){: .btn .btn--info} {% endif %}

## Citation

If you found this work useful, please cite the associated paper:

<div class="notice--info">
Vidit, M. Engilberge, and M. Salzmann, “CLIP the Gap: A Single Domain Generalization Approach for Object Detection” in Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023.
</div>

<div class="notice--info" markdown="1">
**BibTex:**
~~~~~~~~
@inproceedings{vidit2023clip,
  title={CLIP the Gap: A Single Domain Generalization Approach for Object Detection},
  author={Vidit, Vidit and Engilberge, Martin and Salzmann, Mathieu},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2023}
}
~~~~~~~~
</div>
