---
title: "Terrain synthesis and authoring based on iso-contours"
description: Benoît Huftier, Hugo Schott, Eric Galin, Oscar Argudo, Adrien Peytavie, Eric Guérin
slug: isos
date: 2026-04-01 00:00:00+0000
journal: Computer Graphics Forum, Eurographics 2026
image: teaser_isos.png
categories:
    - Virtual Terrain
tags:
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

<p class="publi_abstract">
    Digital terrains are central to realistic landscape depiction, yet authoring tools must balance perceptual realism with intuitive artistic control. We propose a compact vector-based representation that models terrain as nested iso-contours, inspired by geomorphology and cartography. Our method departs from traditional grid-based elevation models by generating contours through an inward Open Eden Growth simulation, followed by marching-triangles reconstruction into a Triangulated Irregular Network. This contour framework supports direct editing such as warping, slope modulation, and smoothing, while allowing reconstruction of a standard elevation map for downstream processing, including erosion and amplification. The approach enables the creation of diverse, realistic terrains from minimal user input and offers simple yet powerful control for designers.
</p>