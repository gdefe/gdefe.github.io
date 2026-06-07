---
title: "Why Do Time Series Models Need Long Context Windows?"
authors:
    - Luca Butera
    - Giovanni De Felice
    - Andrea Cini
    - Cesare Alippi
abstract: "Modern deep learning models for forecasting groups of time series rely on increasingly longer observation windows. However, the benefit of increasing the window size is often simply attributed to capturing long-range dependencies, and broader discussion on how global forecasting models leverage input observations has been limited. In this paper, we show that forecasting groups of time series involves two objectives: (i) generative process identification (GPI), i.e., inferring the specific process generating the input sequence, and (ii) conditional forecasting (CF), i.e., predicting future values given input observations. From this perspective, optimal predictions can be interpreted as an average over plausible data-generating processes, weighted by their likelihood given the input window. This suggests another explanation for the benefits of long context windows: they reduce the uncertainty about which specific process is generating the input time series during operation. We prove that even for processes with memory length P, an input window size strictly larger than P is necessary to achieve the minimum attainable error. Finally, we show how decoupling GPI and CF can improve computational scalability without compromising accuracy. Experiments on synthetic and real-world data validate our insights and their relevance for designing forecasting architectures."
categories:
    - time-series
link: https://arxiv.org/abs/2606.01999
code: 
venue: arXiv 2026
thumbnail: windows.png
layout: abstract
order: 14
---
