---
title: "Approximation of splines in Wasserstein spaces"
collection: publications
category: manuscripts
permalink: /publication/wasserstein_splines
excerpt: 'Justiniano, Jorge, Marko Rajković, and Martin Rumpf. "Consistent approximation of interpolating splines in image metamorphosis." Journal of Mathematical Imaging and Vision 65.1 (2023): 29-52.'
paperurl: 'https://arxiv.org/pdf/2302.10682'
doi: 'https://doi.org/10.1051/cocv/2024008'
bibtexurl: '/files/wasserstein_citation.bib'
---


This paper investigates a time discrete variational model for splines in Wasserstein spaces to interpolate probability measures. Cubic splines in Euclidean space are known to minimize the integrated squared acceleration subject to a set of interpolation constraints. As generalization on the space of probability measures the integral of the squared acceleration is considered as a spline energy and regularized by addition of the usual action functional. Both energies are then discretized in time using local Wasserstein-2 distances and the generalized Wasserstein barycenter. The existence of time discrete regularized splines for given interpolation conditions is established. On the subspace of Gaussian distributions, the spline interpolation problem is solved explicitly and consistency in the discrete to continuous limit is shown. The computation of time discrete splines is implemented numerically, based on entropy regularization and the Sinkhorn algorithm. A variant of Nesterov’s accelerated gradient descent algorithm is applied for the minimization of the fully discrete functional. A variety of numerical examples demonstrate the robustness of the approach and show striking characteristics of the method. As a particular application the spline interpolation for synthesized textures is presented.
