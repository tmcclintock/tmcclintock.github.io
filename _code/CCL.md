---
title: "Core Cosmology Library"
collection: code
permalink: /code/CCL
excerpt: "The Core Cosmology Library for the Dark Energy Science Collaboration."
date: 2018-05-24
repo: "https://github.com/LSSTDESC/CCL"
---
## Summary
This library is the primary tool for theoretical calculations to be used by the Dark Energy Science Collaboration as part of LSST. The library computes distances, correlation functions, and halo properties, while allowing for seemless integration with different routines for calculating the matter power spectrum including CLASS, BBKS, the CosmicEmu, and analytic expressions. As a main contributor, I helped develop much of the Python front-end as well as most of the documentation.

An attractive feature of CCL is that it supports both Python and C/C++. The back-end is entirely in C, meaning it is well optimized, and the Python front-end is pip installable. This library is a must for any graduate student just getting started with research, as it will significantly cut the time to develop your own theoretical routines.