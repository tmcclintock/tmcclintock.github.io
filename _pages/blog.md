---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
classes: thin
---

In addition to the blog posts that appear here, I have written for a few other site. Here are the links:

1. DArchive: Finding the edges of massive galaxy clusters (2018, soon). This article summarizes the work of [Chang et al.](https://arxiv.org/abs/1710.06808) (2018) where the authors detected the splashback radius in DES galaxy clusters. The splashback radius is nice physical boundary used to defined dark matter halos, and has people excited about the future of connecting cluster cosmology with cluster astrophysics.

2. Ultiworld: [Simulated usage rats in mixed ultimate: Investigating an observed gender throwing bias](https://ultiworld.com/2018/07/24/simulating-usage-rates-mixed-ultimate-investigating-observed-gender-throwing-bias/) (2018). This article summarizes my project where I simulated usage rates on mixed gender ultimate teams. The results showed that there is a "throwing gender bias" in the mixed division, meaning that female players are not thrown to as often as their male counterparts.

3. Astrobites: [Shifting the Pillars - Constraining Lithium Production in Big Bang Nucleosynthesis](https://astrobites.org/2015/07/27/shifting-the-pillars-constraining-lithium-production-in-big-bang-nucleosynthesis/) (2015). This is a summary of an arXiv paper where the authors used solar data to constrain a critical reaction cross section in BBN.

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}