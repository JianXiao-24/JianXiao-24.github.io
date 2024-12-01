---
title: "Hybrid Near/Far-Field Channel Prediction for RIS-Aided LEO Satellite Networks"
collection: publications
category: manuscripts
permalink: /publication/CP4RIS_LEO
date: 01 November 2024
excerpt: 'A hybrid near- and far- field cascaded channel prediction scheme is proposed for reconfigurable intelligent surface (RIS) assisted low earth orbit (LEO) satellite networks. The code is available at [SIN](https://github.com/WiCi-Lab/SIN)'
venue: ' IEEE Communications Letters  '
paperurl: 'https://ieeexplore.ieee.org/document/10741249'
citation: 'J. Xiao, J. Wang, X. Li, W. Xie, N. C. Luong and A. Nallanathan, "Hybrid Near/Far-Field Channel Prediction for RIS-Aided LEO Satellite Networks," in IEEE Communications Letters, doi: 10.1109/LCOMM.2024.3489579, 2024.'
---

A joint cascaded channel estimation scheme is proposed for simultaneously transmitting and reflecting reconfigurable intelligent surface (STAR-RIS) systems with hardware imperfections. In particular, the practical hybrid near- and far-field electromagnetic radiation with spatial non-stationarity is investigated. By exploiting the cascaded channel correlations between different users and between different STAR-RIS elements, a multi-task learning (MTL)-based channel estimation framework is proposed. This framework is capable of estimating the cascaded channels for transmission and reflection simultaneously based on noisy observations of the mixture channel. Following the design guideline of the proposed MTL framework, an efficient multi-task network (MTN) is developed to reconstruct the high-dimensional channels with limited pilot overhead. In the proposed MTN architecture, a mixed convolution and multilayer perception module is exploited to capture the effective hybrid-field channel features. This module integrates the locality bias modeling of the channel-wise convolution and the long-range dependency modeling of multilayer perception, which finely learns both local spatial correlations and specific spatial non-stationarity of the hybrid-field cascaded channels. Numerical results show that the proposed MTN achieves superior channel estimation accuracy with less training overhead compared with the existing state-of-the-art benchmarks, in terms of required pilots, computations, and network parameters.

