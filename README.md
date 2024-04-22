# Project Descriptions

## Topic: Uncertainty-aware Deep Learning

This project explores the concept of uncertainty-aware deep learning, focusing on the paper "Simple and Principled Uncertainty Estimation with Deterministic Deep Learning via Distance Awareness" by authors (insert author names) published in (insert publication details).

- Paper: [Simple and Principled Uncertainty Estimation with Deterministic Deep Learning via Distance Awareness](https://papers.nips.cc/paper/2020/file/543e83748234f7cbab21aa0ade66565f-Paper.pdf)

- Reference code: [TensorFlow Tutorial on SNGP](https://www.tensorflow.org/tutorials/understanding/sngp)

### Problem 1
**Problem Statement:** What is the problem that the paper aims to solve, and why is this problem important or interesting?

The paper addresses the challenge of uncertainty estimation in deep learning models and its importance lies in enabling AI systems to quantify their confidence in predictions, crucial for applications in safety-critical domains such as healthcare and autonomous driving.

### Problem 2
**Problem Statement:** What is the meaning of "distance awareness"? How do the authors achieve "distance awareness"?

"Distance awareness" refers to the capability of the model to understand the relative distances between data points in the input space. The authors achieve this by incorporating spectral normalization, which constrains the Lipschitz constant of the neural network.

### Problem 3
**Problem Statement:** Design and implement a toy experiment to showcase the effect of "spectral normalization".

To showcase the effect of spectral normalization, we design a simple toy experiment using synthetic data where we compare the performance of a neural network trained with and without spectral normalization in terms of convergence behavior and generalization.

### Problem 4
**Problem Statement:** Reproduce the toy experiment (Figure 1 (f),(i),(j)) in the paper. You need to output the three figures.

We will reproduce the toy experiment as described in Figure 1 (f), (i), and (j) of the paper using the provided reference code and dataset. The output will consist of the three figures demonstrating the experimental results.

### Problem 5
**Problem Statement:** Conduct the same sets of experiments as Problem 4 on the mixture of 8 Gaussians and 25 Gaussians respectively. These Gaussians can be either identical or with different parameters at your choice. You need to output six pictures.

We will extend the experimentation to a more complex scenario by conducting experiments on mixtures of 8 and 25 Gaussians. The experiments will involve training neural networks with and without spectral normalization and analyzing their performance. The output will include six pictures showcasing the results.

