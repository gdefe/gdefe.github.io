---
title: "On the Regularization of Learnable Embeddings for Time Series Processing"
authors:
    - Luca Butera
    - Giovanni De Felice
    - Andrea Cini
    - Cesare Alippi
abstract: "In processing multiple time series, accounting for the individual features of each sequence can be challenging. To address this, modern deep learning methods for time series analysis combine a shared (global) model with local layers, specific to each time series, often implemented as learnable embeddings. Ideally, these local embeddings should encode meaningful representations of the unique dynamics of each sequence. However, when these are learned end-to-end as parameters of a forecasting model, they may end up acting as mere sequence identifiers. Shared processing blocks may then become reliant on such identifiers, limiting their transferability to new contexts. In this paper, we address this issue by investigating methods to regularize the learning of local learnable embeddings for time series processing. Specifically, we perform the first extensive empirical study on the subject and show how such regularizations consistently improve performance in widely adopted architectures. Furthermore, we show that methods preventing the co-adaptation of local and global parameters are particularly effective in this context. This hypothesis is validated by comparing several methods preventing the downstream models from relying on sequence identifiers, going as far as completely resetting the embeddings during training. The obtained results provide an important contribution to understanding the interplay between learnable local parameters and shared processing layers: a key challenge in modern time series processing models and a step toward developing effective foundation models for time series." 
categories:
    - time-series
    - spatio-temporal
link: https://arxiv.org/abs/2410.14630
code: 
venue: arXiv
thumbnail: curves.png
layout: abstract
order: 8
---
