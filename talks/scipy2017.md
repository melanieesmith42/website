---
title: Bringing the Generic Mapping Tools to Python
author: uieda, pwessel
date: 2017-07-13
repository: GenericMappingTools/scipy2017
slides: <a href="https://github.com/GenericMappingTools/scipy2017/raw/master/slides.pdf">PDF slides</a>
event: Python in Science Conference
thumbnail: scipy2017.png
license: CC-BY
layout: publication
---

# Slides

<div class="embed-responsive embed-responsive-4by3">
<iframe
src="https://docs.google.com/presentation/d/15he1klG9gCvBgGr3jGeQhTbcY5xShKv54l4BVnIxYBg/embed?start=false&loop=false&delayms=3000"
frameborder="0" width="960" height="749" allowfullscreen="true"
mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>
\[[view in Google Drive](https://docs.google.com/presentation/d/15he1klG9gCvBgGr3jGeQhTbcY5xShKv54l4BVnIxYBg/pub?start=false&loop=false&delayms=3000)\]


# About

This was the first talk I gave about [GMT/Python][/software/gmt-python].
I didn't have that much implemented yet but was able to give a quick demo (see
notebook link below).

* See my blog post with the initial [talk
  proposal][/blog/scipy2017-proposal-gmt].
* Read the [reviews we got and our replies][/blog/scipy2017-reviews].
* There is a [Jupyter notebook with the live
  demo](http://nbviewer.jupyter.org/github/GenericMappingTools/scipy2017/blob/master/demo.ipynb).
  It only works on Linux for now, sorry.

# Abstract

The Generic Mapping Tools (GMT) is an open-source software package widely used
in the geosciences to process and visualize time series and gridded data.
Maps generated by GMT are ubiquitous in scientific publications in areas such
as seismology and oceanography.
We present a new GMT Python wrapper library built by the GMT team.
We will show the design plans, internal implementations, and demonstrate an
initial prototype of the library.
Our wrapper connects to the GMT C API using ctypes and allows input and
output using data from numpy ndarrays and xarray Datasets.
The library is still in early stages of design and implementation and
we are eager for contributions and feedback from the Scipy community.