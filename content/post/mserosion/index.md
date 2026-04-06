---
title: Terrain Amplification using Multi-Scale Erosion
description: Hugo Schott, Eric Galin, Eric Guérin, Adrien Peytavie, Axel Paris
slug: mserosion
date: 2024-07-01 00:00:00+0000
journal: ACM Trans. Graph., presented at Siggraph 2024
image: teaser_mserosion.png
categories:
    - Virtual Terrain
tags:
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

<p class="publi_abstract">
    Modeling high-resolution terrains is a perennial challenge in the creation of virtual worlds. In this paper, we focus on the amplification of a low- resolution input terrain into a high-resolution, hydrologically consistent terrain featuring complex patterns by a multi-scale approach. Our framework combines the best of both worlds, relying on physics-inspired erosion models producing consistent erosion landmarks and introducing control at different scales, thus bridging the gap between physics-based erosion simulations and multi-scale procedural modeling. The method uses a fast and accurate approximation of different simulations, including thermal, stream power erosion and deposition performed at different scales to obtain a range of effects. Our approach provides landscape designers with tools for amplifying mountain ranges and valleys with consistent details.
</p>

<iframe 
  width="100%" 
  style="aspect-ratio: 16/9;" 
  src="https://www.youtube.com/embed/mUBsPjwp8TM" 
  frameborder="0" 
  allowfullscreen>
</iframe>

<div class="publi_bibtex">
    @article{schott2024,<br>
    &emsp; &emsp; &emsp; author = {Schott, Hugo and Galin, Eric and Gu\'{e}rin, Eric and Peytavie, Adrien and Paris, Axel},<br>
    &emsp; &emsp; &emsp; title = {Terrain Amplification using Multi-Scale Erosion},<br>
    &emsp; &emsp; &emsp; year = {2024},<br>
    &emsp; &emsp; &emsp; issue_date = {July 2024},<br>
    &emsp; &emsp; &emsp; publisher = {Association for Computing Machinery},<br>
    &emsp; &emsp; &emsp; address = {New York, NY, USA},<br>
    &emsp; &emsp; &emsp; volume = {43},<br>
    &emsp; &emsp; &emsp; number = {4},<br>
    &emsp; &emsp; &emsp; issn = {0730-0301},<br>
    &emsp; &emsp; &emsp; url = {https://doi.org/10.1145/3658200},<br>
    &emsp; &emsp; &emsp; doi = {10.1145/3658200},<br>
    &emsp; &emsp; &emsp; journal = {ACM Trans. Graph.},<br>
    &emsp; &emsp; &emsp; month = jul,<br>
    &emsp; &emsp; &emsp; articleno = {145},<br>
    &emsp; &emsp; &emsp; numpages = {12},<br>
    &emsp; &emsp; &emsp; keywords = {landscapes, erosion simulation}<br>
    }
</div>
<div class="publi_bottom_page"></div>

> [PDF HAL](https://hal.science/hal-04565030v1/document)\
> [ACM TOG](https://dl.acm.org/doi/10.1145/3658200)\
> [Video](https://www.youtube.com/watch?v=mUBsPjwp8TM)\
> [Source code](https://github.com/H-Schott/MultiScaleErosion)