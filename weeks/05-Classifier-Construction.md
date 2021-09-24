---
layout: week
title: Week 05
doodle: /doodle.png
---

# Baseline Model

## Topics

This week's assignments will guide you through the following topics:
* GCN-LPA framework
* continue implementing GraphSage

## Reading
### Optimization
* Read about different gradient descent optimizers [here](https://towardsdatascience.com/optimizers-for-training-neural-network-59450d71caf6).

### Replication task.
This week we will continue reading our second replication paper.
1.  For the replication paper: [Unifying Graph Convolutional Neural Networks and Label Propagation](https://arxiv.org/pdf/2002.06755), carefully read section 2 and keep a list of phrases and terms you are unfamiliar with.
2. For the GraphSage paper, read Appendix A and C of the GraphSage paper (note: we will be learning about DeepWalk later in the quarter).

## Tasks

This week we will continue coding the replication task.
1. GraphSage: Using the aggregator layers you built last week, implement Algorithm 1 for forward propagation through the network with K=2 (use the full graph, do not implement the sampling scheme).
2. GCN-LPA:
* Implement the LPA loss in equation (15).
* Implement a pre-processing step for the weighted adjacency matrix A, such that based on user input, it will be either unnormalized, normalized as in [Kipf-Welling,2017] or as in equation (3).

## Weekly Questions

Answer the following questions
1.    For the multi-layer networks you implemented last week, what were the hyper-parameters you used to train your networks (# of hidden units in each layer/dimension of hidden layer, # training epochs, learning rate, optimizer, regularization)? Try changing some of the parameters of the 2-layer networks you trained (dimension of the hidden layers and learning rate) and compare the performance. When you report performance, note both the training and test accuracy.
2.    Describe one thing that you found difficult to understand in Section 2 of the Label Propagation paper. Try to be specific about what you don’t think you understand.
3.    Explain how GCN-LPA and GraphSage are each different from the baseline GCN model. What is each paper trying to learn to improve on a regular GCN network? What is the similarity between the two approaches? (be specific, “they improve on a GCN model” is not an answer)

