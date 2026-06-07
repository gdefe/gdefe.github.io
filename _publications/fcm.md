---
title: "Federated Concept-Based Models: Interpretable models with distributed supervision"
authors:
    - Dario Fenoglio
    - Arianna Casanova
    - Francesco De Santis
    - Gabriele Dominici
    - Johannes Schneider
    - Pietro Barbiero
    - Giovanni De Felice
    - Marc Langheinrich
    - Martin Gjoreski
abstract: "Concept-based Models (CMs) enhance interpretability in deep learning by grounding predictions in human-understandable concepts. However, concept annotations are costly and rarely available at scale within a single data source. Federated Learning (FL) could alleviate this limitation by enabling cross-institutional training over concept annotations distributed across multiple data owners. Yet, FL lacks interpretable modeling paradigms. Integrating CMs with FL is non-trivial: although FL supports heterogeneous and non-stationary client participation, it typically assumes a fixed shared architecture, whereas CMs may require architectural adaptation as the available concept set evolves. We propose Federated Concept-based Models (F-CMs), a new methodology for deploying CMs in evolving FL settings. F-CMs aggregate concept-level information across institutions and efficiently adapt the model architecture to changes in concept supervision while preserving privacy. Empirically, F-CMs maintain accuracy and intervention effectiveness comparable to training settings with full concept supervision, while outperforming on average non-adaptive federated baselines. Notably, F-CMs enable interpretable inference on concepts unavailable to a given institution, a key novelty over existing approaches."
categories:
    - interpretability
link: https://arxiv.org/abs/2602.04093
code: 
venue: arXiv 2026
thumbnail: federated.png
fit: contain
layout: abstract
order: 10
---
