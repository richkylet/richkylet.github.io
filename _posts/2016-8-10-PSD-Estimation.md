---
layout: single
title: PSD Estimation
permalink: null
published: true
---

## Signal Processing example scripts: PSD estimation


**Basic descritpion:** simple script for calculating the power spectral density (PSD) of a signal (see: [`PSDestimation.py`](https://github.com/richkylet/analysis-tools/blob/gh-pages/PSDestimation.py)). 

Information: The power Spectral Density (PSD) of a time-domain signal represents the signal power in the frequency domain.  
That is, the PSD shows which frequency content within a signal are strong relative to other frequency content. 
Generally, the PSD is computed using the Fast Fourier Transform (FFT), an algorithm for comuputing the Discrete Fourier transform (DFT) of a sequence or signal.   

Here is a basic [python script](https://github.com/richkylet/analysis-tools/blob/gh-pages/PSDestimation.py) for calculating the FTT and PSD of a time-domain signal. 
I figured these would serve as nice examples for people looking for code with example problems that are easily modified to fit other applications. 

If we first consider some time-domain signal (subplot titled 'Time-domain signal'), with (red) and without (blue) zero-sum noise, qualitatively we notice the signal 'looks' like it is composed of two sinusoids. We can first check if this is true by taking the FFT of the signal. That is, we can convert the signal to the frequency domain using a FFT. The normalized frequency spectrum is shown in the subplot titled 'Frequency Spectrum'. Indeed, the signal is composed of two principle frequency components. 

![]({{site.baseurl}}https://github.com/richkylet/analysis-tools/blob/gh-pages/images/PSD.jpeg?raw=true)

Now, potentially we want to calculate the PSD of the signal to estimate the power per frequncy bin. 
The `scipy` package offers various methods for calculating the PSD. 
The periodogram method is a basic method (shown in subplot titled 'Method of periodograms').
Welch's method improves upon the periodogram method by reducing noise in 
exchange for reducing the frequency resolution (shown in subplot titled 'Welchs method').










