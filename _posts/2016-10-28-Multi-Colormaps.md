---
layout: single
title: Plotting overlapping colormaps
permalink: null
published: true
---



### Example plotting overlapping colormaps: `MWE_overlayColormap.m`


**Basic descritpion:** simple script for plotting overlapping colormaps in MATLAB. (see: [`MWE_overlayColormap.m`](https://github.com/richkylet/analysis-tools/blob/gh-pages/MWE_overlayColormap.m)).
This is part of a [collection of basic scripts](https://github.com/richkylet/analysis-tools) used for analysis during my PhD. 


Information: One challenge that often arises with plotting image data in MATLAB is the need to use multiple, overlapping colormaps. 
This isn't always a straightforward problem to solve, so I've generated a simple MWE. 
This example is easy to follow: two axes are defined and plotted, the axes linked, colormaps assigned, and second (or third and fourth and...) axes turned off:


![]({{site.baseurl}}https://github.com/richkylet/analysis-tools/blob/gh-pages/images/twoColormaps.jpg?raw=true)
