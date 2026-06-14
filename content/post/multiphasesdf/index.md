---
title: "The PhaseTree: Multiphase Signed Distance Fields."
description: Eric Galin, Pierre Hubert-Brierre, Hugo Schott, Marie-Paule Cani, Adrien Peytavie, Eric Guérin
slug: multiphasesdf
date: 2026-06-01 00:00:00+0000
journal: ACM Trans. Graph., presented at Siggraph 2026
image: teaser_multiphasesdf.jpg
categories:
    - Signed Distance Field
tags:
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

<p class="publi_abstract">
    We introduce the PhaseTree, a novel hierarchical construction-tree representation for compactly modeling volumetric objects composed of multiple phases or materials across scales. An object is defined as a single construction tree that combines phase-aware primitives through composition and warping operators, yielding a unified multiphase signed distance representation that naturally supports complex topologies and interfaces between phases. The PhaseTree is compatible with standard signed distance field workflows: single-phase algorithms can be directly promoted to a PhaseTree, and conversely reduced without loss of information. As a result, our model integrates seamlessly with existing algorithms and rendering pipelines. We extend classical Sphere Tracing to robustly handle multiphase configurations and show that, despite the additional expressiveness, our implementation preserves the compactness and resolution independence of signed distance fields and incurs less than a 25% runtime overhead compared to single-phase Sphere Tracing.
</p>

<div class="publi_bibtex">
    @article{galin2026,<br>
	&emsp; &emsp; &emsp; title = {The PhaseTree: Multiphase Signed Distance Fields},<br>
	&emsp; &emsp; &emsp; author = {Galin, Eric and Hubert-Brierre, Pierre and Schott, Hugo and Cani, Marie-Paule and Peytavie, Adrien and Guérin, Eric},<br>
	&emsp; &emsp; &emsp; journal = {ACM Transaction on Graphics (SIGGRAPH '26 Conference Proceedings)},<br>
	&emsp; &emsp; &emsp; publisher = {ACM},<br>
	&emsp; &emsp; &emsp; year = {2026},<br>
}
</div>
<div class="publi_bottom_page"></div>

> [PDF](https://perso.liris.cnrs.fr/eric.galin/Articles/2026-phasetree.pdf)