---
header:
  teaser: "geoshift-teaser.png"
title: "Learning Transformations To Reduce the Geometric Shift in Object Detection"
collection: publications
permalink: /publications/geo-shift
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-06-19
venue: 'CVPR'
paperurl: '/files/papers/Vidit et al. - 2023 - Learning Transformations To Reduce the Geometric Shift in Object Detection.pdf'
suppurl: '/files/supplementaries/Vidit et al. - 2023 - Supplementary Learning Transformations To Reduce the Geometric Shift in Object Detection.pdf'
codeurl: 'https://github.com/vidit09/geoshift'
posterurl: '/files/posters/geoshift-poster.pdf'
talkurl: 'https://www.youtube.com/watch?v=B7L8YVvNPnw&ab_channel=Vidits'
authors: 'Vidit, M. Engilberge, M. Salzmann'


---
## Abstract

The performance of modern object detectors drops when the test distribution differs from the training one. Most of the methods that address this focus on object appearance changes caused by, e.g., different illumination conditions, or gaps between synthetic and real images. Here, by contrast, we tackle geometric shifts emerging from variations in the image capture process, or due to the constraints of the environment causing differences in the apparent geometry of the content itself. We introduce a self-training approach that learns a set of geometric transformations to minimize these shifts without leveraging any labeled data in the new domain, nor any information about the cameras. We evaluate our method on two different shifts, i.e., a camera's field of view (FoV) change and a viewpoint change. Our results evidence that learning geometric transformations helps detectors to perform better in the target domains.  

## Links

{% if page.paperurl %} [Paper]({{ base_path }}{{ page.paperurl }}){: .btn .btn--info} {% endif %} {% if page.suppurl %} [Suppl.]({{ base_path }}{{ page.suppurl }}){: .btn .btn--info} {% endif %} {% if page.codeurl %} [Code]({{ page.codeurl }}){: .btn .btn--info} {% endif %} {% if page.dataurl %} [Data]({{ base_path }}{{ page.dataurl }}){: .btn .btn--info} {% endif %} {% if page.posterurl %} [Poster]({{ base_path }}{{ page.posterurl }}){: .btn .btn--info} {% endif %} {% if page.talkurl %} [Talk]({{ page.talkurl }}){: .btn .btn--info} {% endif %}

## Citation

If you found this work useful, please cite the associated paper:

<div class="notice--info">
Vidit, M. Engilberge, and M. Salzmann, “Learning Transformations To Reduce the Geometric Shift in Object Detection” in Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023.
</div>

<div class="notice--info" markdown="1">
**BibTex:**
~~~~~~~~
@inproceedings{vidit2023learning,
  title={Learning Transformations To Reduce the Geometric Shift in Object Detection},
  author={Vidit, Vidit and Engilberge, Martin and Salzmann, Mathieu},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2023}
}
~~~~~~~~
</div>
