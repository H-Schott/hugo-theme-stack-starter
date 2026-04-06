---
title: "Sphere Carving: Bounding Volumes for Signed Distance Fields"
description: Hugo Schott, Théo Thonat, Thibaud Lambert, Eric Guérin, Eric Galin, Axel Paris
slug: spherecarving
date: 2025-07-01 00:00:00+0000
journal: ACM Trans. Graph., presented at Siggraph 2025
image: spherecarving_mini.png
categories:
    - Signed Distance Field
tags:
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

<p class="publi_abstract">
    We introduce Sphere Carving, a novel method for automatically computing bounding volumes that closely bound a procedurally defined implicit surface. Starting from an initial bounding volume located far from the object, we iteratively approach the surface by leveraging the signed distance function information. Field function queries define a set of empty spheres, from which we extract intersection points that are used to compute a bounding volume. Our method is agnostic of the function representation and only requires a conservative signed distance field as input. This encompasses a large set of procedurally defined implicit surface models such as exact or Lipschitz functions, BlobTrees, or even neural representations. Sphere Carving is conceptually simple, independent of the function representation, requires a small number of function queries to create bounding volumes, and accelerates queries in Sphere Tracing and polygonization.
</p>

<iframe 
  width="100%" 
  style="aspect-ratio: 16/9;" 
  src="https://www.youtube.com/embed/feknkiREYZs" 
  frameborder="0" 
  allowfullscreen>
</iframe>

<div class="publi_bibtex">
    @article{schott2025,<br>
	&emsp; &emsp; &emsp; title = {Sphere Carving: Bounding Volumes For Signed Distance Fields},<br>
	&emsp; &emsp; &emsp; author = {Schott, Hugo and Thonat, Theo and Lambert, Thibaud and Guérin, Eric and Galin, Eric and Paris, Axel},<br>
	&emsp; &emsp; &emsp; journal = {ACM Transaction on Graphics (SIGGRAPH '25 Conference Proceedings)},<br>
	&emsp; &emsp; &emsp; publisher = {ACM},<br>
	&emsp; &emsp; &emsp; year = {2025},<br>
	&emsp; &emsp; &emsp; number = {4},<br>
	&emsp; &emsp; &emsp; volume = {44}<br>
}
</div>
<div class="publi_bottom_page"></div>

> [PDF HAL](https://hal.science/hal-05162169/file/paper.pdf)\
> [ACM TOG](https://dl.acm.org/doi/10.1145/3730845)\
> [Video](https://www.youtube.com/watch?v=feknkiREYZs)\
> [Source code](https://github.com/H-Schott/SphereCarvingRelease/)