---
layout: week
title: Week 04
doodle: /doodle.png
---

# Label Propogation

## Topics

This week’s assignments will guide you through the following topics:
*   Label Propagation
*    Start implementing GraphSage network


## Reading

### Replication task.
This week we will begin reading our second replication paper.
1. Our second paper unifies GCN with Label propagation (LPA). Read the following [tutorial](https://towardsdatascience.com/label-propagation-demystified-cd5390f27472) and [slideshow](http://www.leonidzhukov.net/hse/2015/networks/lectures/lecture17.pdf)
2. For the replication paper: [Unifying Graph Convolutional Neural Networks and Label Propagation](https://arxiv.org/pdf/2002.06755), complete the following reading tasks. As you read through the paper, keep a list of phrases and terms you are unfamiliar with.
* Quick read of Abstract, Conclusion, Introduction (section 1). 
* Careful read of the abstract, making sure you really understand it. You may need to look up terms.
* Carefully read sections 1 and 3.
* Optional: for those of you who want a few more details on Weisfeiler-Lehman Isomorphism test and its relation to GraphSage read this [post](https://towardsdatascience.com/expressive-power-of-graph-neural-networks-and-the-weisefeiler-lehman-test-b883db3c7c49)


## Tasks

Complete the following tasks

### Deep learning networks
* Implement an FCN with 2 hidden layers and a GCN with 2 hidden layers. Train these networks on a classification task for the Cora dataset. Do they perform better than the single-layer variant? Does increasing the number of layers to 3 improve results?
* Optional: Implement the GCN using the adjacency matrix normalization used in [Semi-supervised classification with graph convolutional networks](https://arxiv.org/pdf/1609.02907.pdf) (eq 2). Note: we read Kipf's blog post on this network last week.

### Replication task
This week we will start coding the replication task, breaking it up into parts.
1. Implement the unsupervised loss in equation (1), section 3.2. This is loss we will be training the network with.
2. Implement the mean aggregator and pooling aggregator in section 3.3 as a neural network layer. This class should have an initialization and a forward pass method.
*  For initialization the layer should receive as input arguments the layer input dimension, layer output dimensions, input dimension of the neighbors, nonlinear activation function.
*  For the forward pass, the input arguments are the embeddings of the node and the embedding of its neighbors.
*  There may be additional input arguments you need to add, based on your implementation



## Weekly Questions

1. What are the similarities and differences between the two replication papers
* In terms of the structure of the paper
* In terms of the problems it is trying to solve and the method
2. Report your results for the deep learning classification task (# of epochs trained, final traning and test loss, final training and test accuracy).

