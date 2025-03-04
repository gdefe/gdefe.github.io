---
title: "On the Regularization of Learnable Embeddings for Time Series Processing"
authors:
    - Luca Butera
    - Giovanni De Felice
    - Andrea Cini
    - Cesare Alippi
abstract: "In forecasting multiple time series, accounting for the individual features of each sequence can be challenging. To address this, modern deep learning methods for time series analysis combine a shared (global) model with local layers, specific to each time series, often implemented as learnable embeddings. Ideally, these local embeddings should encode meaningful representations of the unique dynamics of each sequence. However, when these are learned end-to-end as parameters of a forecasting model, they may end up acting as mere sequence identifiers. Shared processing blocks may then become reliant on such identifiers, limiting their transferability to new contexts. In this paper, we address this issue by investigating methods to regularize the learning of local learnable embeddings for time series processing. Specifically, we perform the first extensive empirical study on the subject and show how such regularizations consistently improve performance in widely adopted architectures. Furthermore, we show that methods attempting to prevent the co-adaptation of local and global parameters by means of embeddings perturbation are particularly effective in this context. In this regard, we include in the comparison several perturbation-based regularization methods, going as far as periodically resetting the embeddings during training. The obtained results provide an important contribution to understanding the interplay between learnable local parameters and shared processing layers: a key challenge in modern time series processing models and a step toward developing effective foundation models for time series." 
categories:
    - time-series 
    - spatio-temporal
link: https://openreview.net/pdf?id=F5ALCh3GWG
code: 
venue: TMLR
thumbnail: curves.png
layout: abstract
order: 8
---
