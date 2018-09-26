---
title: "Cluster Toolkit"
collection: code
permalink: /code/cluster_toolkit
excerpt: "A library for the calculation of theoretical quantities related to galaxy clusters."
date: 2018-05-24
repo: "https://github.com/tmcclintock/cluster_toolkit"
---
## Summary
This package calculates numerous quantities related to galaxy clusters, including those that are essential for modeling weak lensing profiles. This includes 3D and 2D projected density profiles, 1 and 2-halo terms, correlation functions, halo bias, mass--concentration relationships, and the halo mass function. All implementations are extremely optimized and are suitable for use in an MCMC analysis.

The toolkit was used in the DES Year 1 weak lensing analysis of redMaPPer clusters, as well as the creation of emulators for the Aemulus Project, as detailed in the Publications section. An attractive feature of the toolkit is that while the back-end is entirely in C, the front-end is a Python module. This makes it simple to install on any machine that uses Python 2.7.