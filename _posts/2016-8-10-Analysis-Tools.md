---
layout: splash
title: Analysis Tools
permalink: null
published: true
---

## Signal & Image Processing example scripts

I finally generated some _very_ basic signal (see: `signalProcessingExamples.py`) and image (see: `imageProcessingExamples.py`) processing python scripts. 
I figured these would serve as nice examples for people looking for code with example problems that are easily modified to fit other applications.  

All code has been generalized from its original use to serve as a starter for anyone new to signal & image processing in python.  

Scripts are here: [analysis-tools](https://github.com/richkylet/analysis-tools)

### Basic signal processing
Here, I'm simply demonstrating how to take a time-domain signal, take a 1D FFT with proper normalization. Also shown are examples determining the power desnity spectrum using the method of periodogram and Welch's method. Results are shown for a clean, original sinusoidal signal and one with zero-sum noise added to it. 

![]({{site.baseurl}}https://github.com/richkylet/analysis-tools/blob/gh-pages/images/signalProcessPic.jpeg?raw=true)


### Basic image processing
Here are a few very basic introductions to filter an image with a spline, convolved, guassian type filters for edge, shift, or blurred filtering effects/processing. 

![]({{site.baseurl}}https://github.com/richkylet/analysis-tools/blob/gh-pages/images/imageProcessPic.jpeg?raw=true)








