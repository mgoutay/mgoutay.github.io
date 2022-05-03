---
layout: post
title:  "[Article] End-to-End Learning of OFDM Waveforms with PAPR and ACLR Constraints"
subtitle: "Mathieu Goutay, Fayçal Ait Aoudia, Jakob Hoydis, and Jean-Marie Gorce <p>
           Submitted to 2021 IEEE Global Communications Conference (GLOBECOM), Madrid, Spain "
date:   2021-06-19
description : "Mathieu Goutay, Fayçal Ait Aoudia, Jakob Hoydis, and Jean-Marie Gorce"
categories: [ml, autoencoder]
---

Orthogonal frequency-division multiplexing (OFDM) is widely used in modern wireless networks thanks to its efficient handling of multipath environment. However, it suffers from a poor peak-to-average power ratio (PAPR) which requires a large power backoff, degrading the power amplifier (PA) efficiency. In this work, we propose to use a neural network (NN) at the transmitter to learn a high-dimensional modulation scheme allowing to control the PAPR and adjacent channel leakage ratio (ACLR). On the receiver side, a NN-based receiver is implemented to carry out demapping of the transmitted bits. The two NNs operate on top of OFDM, and are jointly optimized in and end-to-end manner using a training algorithm that enforces constraints on the PAPR and ACLR. Simulation results show that the learned waveforms enable higher information rates than a tone reservation baseline, while satisfying predefined PAPR and ACLR targets.

You can have a look at the article [here]( https://arxiv.org/abs/2106.16039)





