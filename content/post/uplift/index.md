---
title: Large-scale terrain authoring through interactive erosion simulation
description: Hugo Schott, Axel Paris, Lucie Fournier, Eric Guérin, Eric Galin
slug: uplift
date: 2023-10-01 00:00:00+0000
journal: ACM Trans. Graph., presented at Siggraph 2023
image: alps_uplift.png
categories:
    - Virtual Terrain
tags:
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---
<p class="publi_abstract">
    Large-scale terrains are essential in the definition of virtual worlds. Given the diversity of landforms and the geomorphological complexity, there is a need for authoring techniques offering hydrological consistency without sacrificing user control. In this paper, we bridge the gap between large-scale erosion simulation and authoring into an efficient framework. We set aside modelling in the elevation domain in favour of the uplift domain, and compute emerging reliefs by simulating the stream power erosion. Our simulation relies on a fast yet accurate approximation of drainage area and flow routing to compute the erosion interactively, which allows for incremental authoring. Our model provides landscape artists with tools for shaping mountain ranges and valleys, such as copy-and-paste operations; warping for imitating folds and faults; point and curve elevation constraints to precisely sculpt ridges or carve river networks. It also lends itself to inverse procedural modelling by reconstructing the uplift from an input digital elevation model and allows hydrologically consistent blending between terrain patches.
</p>

<iframe 
  width="100%" 
  style="aspect-ratio: 16/9;" 
  src="https://www.youtube.com/embed/gCP7jzcPLyQ" 
  frameborder="0" 
  allowfullscreen>
</iframe>

<div class="publi_bibtex">
    @article{10.1145/3592787,<br>
    &emsp; &emsp; &emsp; author = {Schott, Hugo and Paris, Axel and Fournier, Lucie and Gu\'{e}rin, Eric and Galin,
    Eric},<br>
    &emsp; &emsp; &emsp; title = {Large-Scale Terrain Authoring through Interactive Erosion Simulation},<br>
    &emsp; &emsp; &emsp; year = {2023},<br>
    &emsp; &emsp; &emsp; issue_date = {October 2023},<br>
    &emsp; &emsp; &emsp; publisher = {Association for Computing Machinery},<br>
    &emsp; &emsp; &emsp; address = {New York, NY, USA},<br>
    &emsp; &emsp; &emsp; volume = {42},<br>
    &emsp; &emsp; &emsp; number = {5},<br>
    &emsp; &emsp; &emsp; issn = {0730-0301},<br>
    &emsp; &emsp; &emsp; url = {https://doi.org/10.1145/3592787},<br>
    &emsp; &emsp; &emsp; doi = {10.1145/3592787},<br>
    &emsp; &emsp; &emsp; journal = {ACM Trans. Graph.},<br>
    &emsp; &emsp; &emsp; month = {jul},<br>
    &emsp; &emsp; &emsp; articleno = {162},<br>
    &emsp; &emsp; &emsp; numpages = {15},<br>
    &emsp; &emsp; &emsp; keywords = {landscapes, Erosion simulation}<br>
    }
</div>
<div class="publi_bottom_page"></div>

> [PDF HAL](https://hal.science/hal-04049125/document)\
> [ACM TOG](https://dl.acm.org/doi/10.1145/3592787)\
> [Video](https://www.youtube.com/watch?v=gCP7jzcPLyQ)\
> [Source code](https://github.com/H-Schott/StreamPowerErosion)