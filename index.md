---
title: Home
category: home
layout: default
---

{% capture index %}{% include_relative content/website_data/index.md %}{% endcapture %}
{{ index | markdownify }}

### Module Handbook

A pdf copy of the module handbook can be downloaded [here](content/handbook/handbook.pdf).

### Citation

This course is the basis for a publication on the [Journal of Open Source
Education](https://jose.theoj.org/). If you use material from this course, I would appreciate if you used the following citation:

[![DOI](http://jose.theoj.org/papers/10.21105/jose.00042/status.svg)](https://doi.org/10.21105/jose.00042)
[![DOI](https://zenodo.org/badge/145456898.svg)](https://zenodo.org/badge/latestdoi/145456898)

```
@article{darribas_gds18,
  author = {Dani Arribas-Bel},
  title = {A course on Geographic Data Science},
  year = 2019,
  journal = {The Journal of Open Source Education},
  volume = 2,
  number = 14,
  doi = {https://doi.org/10.21105/jose.00042}
}
```


### Code repository

<a rel="repo" href="https://github.com/darribas/gds18"><img alt="@darribas/gds18" style="border-width:0" src="GitHub-Mark.png" /></a>

This website, as well as the entire set of materials, code, and data included
in this course are available as an open Github repository available at:


> [https://github.com/darribas/gds18](https://github.com/darribas/gds18)

### License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Geographic Data Science'18</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://darribas.org" property="cc:attributionName" rel="cc:attributionURL">Dani Arribas-Bel</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
