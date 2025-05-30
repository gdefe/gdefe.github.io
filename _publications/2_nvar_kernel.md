---
title: "Time Series Kernels based on Nonlinear Vector AutoRegressive Delay Embeddings"
authors:
    - Giovanni De Felice
    - John Goulermas
    - Vladimir Gusev
abstract: "Kernel design is a pivotal but challenging aspect of time series analysis, especially in the context of small datasets. In recent years, Reservoir Computing (RC) has emerged as a powerful tool to compare time series based on the underlying dynamics of the generating process rather than the observed data. However, the performance of RC highly depends on the hyperparameter setting, which is hard to interpret and costly to optimize because of the recurrent nature of RC. Here, we present a new kernel based on the recently established equivalence between reservoir dynamics and Nonlinear Vector AutoRegressive (NVAR) processes. The kernel is non-recurrent and depends on a small set of meaningful hyperparameters, for which we suggest an effective heuristic. We demonstrate excellent performance on a wide range of real-world classification tasks, both in terms of accuracy and speed. This further advances the understanding of RC representation learning models and extends the typical use of the NVAR framework beyond forecasting."
categories:
    - time-series
link: https://openreview.net/forum?id=UBUWFEwn7p
code: https://github.com/gdefe/nvark-kernel
venue: NeurIPS 2023
thumbnail: nvark.png
layout: abstract
order: 6
---
