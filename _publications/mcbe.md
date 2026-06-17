---
title: "Mixture of Concept Bottleneck Experts"
authors:
    - Francesco De Santis
    - Gabriele Ciravegna
    - Giovanni De Felice
    - Arianna Casanova
    - Francesco Giannini
    - Michelangelo Diligenti
    - Johannes Schneider
    - Danilo Giordano
    - Mateo Espinosa Zarlenga
    - Pietro Barbiero
abstract: "Concept Bottleneck Models (CBMs) promote interpretability by grounding predictions in human-understandable concepts. However, existing CBMs typically constrain their task predictor to a single expression whose functional form is set a priori, limiting both predictive accuracy and adaptability to diverse user needs. We propose Mixture of Concept Bottleneck Experts (M-CBE), a framework that generalizes existing CBMs along two dimensions: the number of expressions, referred to as experts, employed by the task predictor to map concepts to the task, and the functional form each expression takes, thus exposing an underexplored region of this design space. We investigate this region by instantiating two novel models: Linear M-CBE, which learns a finite set of linear expressions, and Symbolic M-CBE, which leverages symbolic regression to discover expert functions from data subject to user-specified operator vocabularies. Empirical evaluation demonstrates that varying the number of expressions and their functional form provides a robust framework for navigating the accuracy-interpretability trade-off."
categories:
    - interpretability
link: https://arxiv.org/abs/2602.02886
code: 
venue: ICML 2026 (spotlight)
thumbnail: moe.png
fit: contain
layout: abstract
order: 11
---
