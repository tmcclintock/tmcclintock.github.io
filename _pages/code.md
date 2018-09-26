---
layout: archive
title: "Code"
permalink: /code/
author_profile: true
classes: thin
---

The computational problems I am focus on include parameter inference from models of physical data, Gaussian process regression, and applying high performance computing techniques to optimize problems.

You can find almost all the code I have written on my [GitHub page](https://github.com/tmcclintock). My most useful contributions are found here.

{% for post in site.code reversed %}
  {% include archive-single.html %}
{% endfor %}
