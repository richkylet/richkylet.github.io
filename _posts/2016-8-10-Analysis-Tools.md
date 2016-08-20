---
layout: single
title: Analysis Tools
permalink: null
published: true
---

## Signal Processing example scripts

**Basic descritpion:** simple script for calculating the power spectral density (PSD) of a signal (see: `PSDestimation.py`). 

** Information:**
The power Spectral Density (PSD) of a time-domain signal represents the signal power in the frequency domain.  
That is, the PSD shows which frequency content within a signal are strong relative to other frequency content. 
Generally, the PSD is computed using the Fast Fourier Transform (FFT), an algorithm for comuputing the Discrete Fourier transform (DFT) of a sequence or signal.   

Here is a basic [python script](https://github.com/richkylet/analysis-tools/blob/gh-pages/PSDestimation.py) for calculating the FTT and PSD of a time-domain signal. 
I figured these would serve as nice examples for people looking for code with example problems that are easily modified to fit other applications. 

If we first consider some time-domain signal (subplot titled 'Time-domain signal'), with (red) and without (blue) zero-sum noise, qualitatively we notice the signal 'looks' like it is composed of two sinusoids. We can first check if this is true by taking the FFT of the signal. That is, we can convert the signal to the frequency domain using a FFT. The normalized frequency spectrum is shown in the subplot titled 'Frequency Spectrum'. Indeed, the signal is composed of two 

![]({{site.baseurl}}https://github.com/richkylet/analysis-tools/blob/gh-pages/images/PSD.jpeg?raw=true)



### Basic signal processing (DFT using FFT in python): `signalProcessingExamples.py`

Here, I'm simply demonstrating how to take a 1D FFT with proper normalization of a time-domain signal. Also shown are examples for calculating the power spectral density (PSD) using the method of periodogram and Welch's method. Results are shown for a clean, original sinusoidal signal (blue) and the orginal signal with zero-sum, random noise added to it (red). 

![]({{site.baseurl}}https://github.com/richkylet/analysis-tools/blob/gh-pages/images/PSD.jpeg?raw=true)


### Basic image processing (image filtering for various effects): `imageProcessingExamples.py`

Here are a few basic examples of image processing with  spline, convolved, and guassian type filters for edge, shift, and blurred effects/processing. 

![]({{site.baseurl}}https://github.com/richkylet/analysis-tools/blob/gh-pages/images/imageProcessPic.jpeg?raw=true)








