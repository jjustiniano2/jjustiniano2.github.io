---
title: "Consistent approximation of interpolating splines in image metamorphosis"
collection: publications
category: manuscripts
permalink: /publication/wasserstein_splines
excerpt: 'Justiniano, Jorge, Marko Rajković, and Martin Rumpf. "Consistent approximation of interpolating splines in image metamorphosis." Journal of Mathematical Imaging and Vision 65.1 (2023): 29-52.'
paperurl: 'https://arxiv.org/pdf/2108.00731'
doi: 'https://doi.org/10.1007/s10851-022-01128-5'
bibtexurl: '/files/justiniano2023consistent.bib'
---


This paper investigates a variational model for splines in the image metamorphosis model for the smooth interpolation of key frames in the space of images. The Riemannian manifold of images based on the metamorphosis model defines shortest geodesic paths interpolating two images as minimizers of the path energy which measures the viscous dissipation caused by the motion field and dissipation caused by the material derivative of the image intensity along motion paths. In this paper, we aim at smooth interpolation of multiple key frame images picking up the general observation of cubic splines in Euclidean space which minimize the squared acceleration along the interpolation path. To this end, we propose the spline functional which combines quadratic functionals of the Eulerian motion acceleration and of the second material derivative of the image intensity as the proper notion of image intensity acceleration. We propose a variational time discretization of this model and study the convergence to a suitably relaxed time continuous model via 
$$\Gamma$$-convergence methodology. As a byproduct, this also allows to establish the existence of metamorphosis splines for given key frame images as minimizers of the time continuous spline functional. The time discretization is complemented by effective spatial discretization based on finite differences and a stable B-spline interpolation of deformed quantities. A variety of numerical examples demonstrates the robustness and versatility of the proposed method in applications. For the minimization of the fully discrete energy functional, a variant of the iPALM algorithm is used.
