---
layout: post
title:  "Tutorial: The Physical Layer as an Autoencoder"
subtitle: "Can we both learn a transmitter and a receiver over any kind of channel?"
date:   2019-11-18
description : "Can we both learn a transmitter and receiver over any kind of channel?"
categories: [tutorials]
---

The idea of representing the physical layer as an autoencoder has come a long way since the [first article]( https://arxiv.org/abs/1702.00832 ) written by  T. O’Shea and J. Hoydis in 2017.

In this post I present a basic notebook where a transmitter and a receiver, represented as the encoder and decoder parts of an autoencoder, jointly learn the best modulation for an AWGN channel.

You can play with the code on [Google Collab]( https://colab.research.google.com/github/mgoutay/autoencodeur/blob/master/Autoencoder.ipynb) and download the notebook on [my Github]( https://github.com/mgoutay/autoencodeur ).  

The two approaches of sending symbols or bits are discussed along with their corresponding loss function.

Small bibliography to come.





