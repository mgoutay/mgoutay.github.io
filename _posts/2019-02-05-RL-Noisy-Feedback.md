---
layout: post
title:  "Deep Reinforcement Learning Autoencoder with Noisy Feedback."
subtitle: "Mathieu Goutay, Fayçal Ait Aoudia, Jakob Hoydis - Submitted at the Workshop on Machine Learning for Communications WMLC 2019, WiOpt 2019, Avignon, France"
date:   2019-02-05
description : "Mathieu Goutay, Fayçal Ait Aoudia, Jakob Hoydis - Submitted at the Workshop on Machine Learning for Communications WMLC 2019, WiOpt 2019, Avignon, France"
categories: [rl, autoencoder]
---

End-to-end learning of communication systems enables joint optimization of transmitter and receiver, implemented as deep neural network-based autoencoders, over any type of channel and for an arbitrary performance metric. Recently, an alternating training procedure was proposed which eliminates the need for an explicit channel model. However, this approach requires feedback of real-valued losses from the receiver to the transmitter during training. In this paper, we first show that alternating training works even with a noisy feedback channel. Then, we design a system that learns to transmit real numbers over an unknown channel without a preexisting feedback link. Once trained, this feedback system can be used to communicate losses during alternating training of autoencoders. Evaluations over additive white Gaussian noise and Rayleigh block-fading channels show that end-to-end communication systems trained using the proposed feedback system achieve the same performance as when trained with a perfect feedback link.

You can have a look at the article [here](https://arxiv.org/abs/1810.05419)
