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


Here is an applied example: we have some region of interest within the field of an ultrasound transducer. The configuration is shown in (a), a cylinderical tube with an unfocused and focused transducer each aligned orthogonally with it. 
The ultrasound field within the cylindrical tube for the (b) focused and (c) unfocused transducers are highlighted in a 'hot' colormap with the background field mapped in grayscale. 

![]({{site.baseurl}}https://github.com/richkylet/analysis-tools/blob/gh-pages/images/twoColormapsExample.jpg?raw=true)

Ultrasound fields in these figures were simulated using an exact series expansion method in MATLAB following [1].




[1] Mast, T. D. and Yu, F. (2005). Simplified expansions for radiation from a baffled circular piston. J. Acoust. Soc. Am., 118(6):3457–3464.
