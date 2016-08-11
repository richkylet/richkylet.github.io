---
layout: single
title: Analysis Tools
permalink: null
published: true
---

## Signal & Image Processing example scripts

I generated some _very_ basic signal (see: `signalProcessingExamples.py`) and image (see: `imageProcessingExamples.py`) processing python scripts. 
I figured these would serve as nice examples for people looking for code with example problems that are easily modified to fit other applications.  

All code has been generalized from its original use to serve as a starter for anyone new to signal & image processing in python.  

Scripts are here: [analysis-tools](https://github.com/richkylet/analysis-tools)

### Basic signal processing (DFT using FFT in python): `signalProcessingExamples.py`

Here, I'm simply demonstrating how to take a 1D FFT with proper normalization of a time-domain signal. Also shown are examples for calculating the power density spectrum using the method of periodogram and Welch's method. Results are shown for a clean, original sinusoidal signal (blue) and the orginal signal with zero-sum, random noise added to it (red). 

![]({{site.baseurl}}https://github.com/richkylet/analysis-tools/blob/gh-pages/images/signalProcessPic.jpeg?raw=true)


### Basic image processing (image filtering for various effects): `imageProcessingExamples.py`

Here are a few basic examples of image processing with  spline, convolved, and guassian type filters for edge, shift, and blurred effects/processing. 

![]({{site.baseurl}}https://github.com/richkylet/analysis-tools/blob/gh-pages/images/imageProcessPic.jpeg?raw=true)








