---
title: "Channel Estimation for Pinching-Antenna Systems (PASS)"
collection: publications
category: manuscripts
permalink: /publication/CE_PASS
date: 30 May 2025
excerpt: 'This letter is the first to explore channel estimation for Pinching-Antenna SyStems (PASS), addressing their uniquely ill-conditioned and underdetermined channel characteristics. In particular, two efficient deep learning-based channel estimators are proposed. 1) PAMoE: This estimator incorporates dynamic padding, feature embedding, fusion, and mixture of experts (MoE) modules, which effectively leverage the positional information of PAs and exploit expert diversity. 2) PAformer: This Transformer-style estimator employs the self-attention mechanism to predict channel coefficients in a per-antenna manner, which offers more flexibility to adaptively deal with dynamic numbers of PAs in practical deployment. The code is available at [PASS](https://github.com/WiCi-Lab/Channel-Estimation-for-Pinching-Antenna-Systems)'
venue: ' IEEE Communications Letters '
paperurl: 'https://ieeexplore.ieee.org/document/11018390'
citation: 'J. Xiao, J. Wang, and Y. Liu, "Channel Estimation for Pinching-Antenna Systems (PASS)," in IEEE Communications Letters. 2025.'
---

Pinching antennas (PAs) represent a revolutionary flexible antenna technology that leverages dielectric waveguides and electromagnetic coupling to mitigate large-scale path
loss. This letter is the first to explore channel estimation for Pinching-Antenna SyStems (PASS), addressing their uniquely ill-conditioned and underdetermined channel characteristics. In
particular, two efficient deep learning-based channel estimators are proposed. 1) PAMoE: This estimator incorporates dynamic padding, feature embedding, fusion, and mixture of experts
(MoE) modules, which effectively leverage the positional information of PAs and exploit expert diversity. 2) PAformer: This Transformer-style estimator employs the self-attention mechanism to predict channel coefficients in a per-antenna manner,
which offers more flexibility to adaptively deal with dynamic numbers of PAs in practical deployment. Numerical results demonstrate that 1) the proposed deep learning-based channel
estimators outperform conventional methods and exhibit excellent zero-shot learning capabilities, and 2) PAMoE delivers higher channel estimation accuracy via MoE specialization, while
PAformer natively handles an arbitrary number of PAs, trading self-attention complexity for superior scalability.
