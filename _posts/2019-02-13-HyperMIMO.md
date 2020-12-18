---
layout: post
title:  "Deep HyperNetwork-Based MIMO Detection"
subtitle: "Mathieu Goutay, Fayçal Ait Aoudia, and Jakob Hoydis"
date:   2020-02-12
description : "Mathieu Goutay, Fayçal Ait Aoudia, and Jakob Hoydis"
categories: [ml, mimo]
---

 Optimal symbol detection for multiple-input multiple-output (MIMO) systems is known to be an NP-hard problem. Conventional heuristic algorithms are either too complex to be practical or suffer from poor performance. Recently, several approaches tried to address those challenges by implementing the detector as a deep neural network. However, they either still achieve unsatisfying performance on practical spatially correlated channels, or are computationally demanding since they require retraining for each channel realization. In this work, we address both issues by training an additional neural network (NN), referred to as the hypernetwork, which takes as input the channel matrix and generates the weights of the neural NN-based detector. Results show that the proposed approach achieves near state-of-the-art performance without the need for re-training. 

You can have a look at the article [here]( https://arxiv.org/abs/2002.02750 )
