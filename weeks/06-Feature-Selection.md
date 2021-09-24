---
layout: week
title: Week 06
doodle: /doodle.png
---

# Random walks on graphs

## Topics

This week's assignments will guide you through the following topics:
* Random walks on graphs
* Implementation of GCN-LPA

## Reading

A random walk is a very important concept in graph theory. In our capstone it plays a role in implementation of the unsupervised loss of GraphSage and in week 8 when we leanr about node2vec and deepwalk.
Read:
* Random walks on graphs: read first 4 pages of Dan Spielma's [notes](http://cs.yale.edu/homes/spielman/561/lect10-18.pdf)
* [Slides](https://www.ic.unicamp.br/~wainer/cursos/1s2014/2007-10-01.sarkar.pdf) on random walks and their connection to PageRank
* [Random walks and applications of random walks](https://www.cs.rpi.edu/~slotag/classes/FA16/slides/lec20-sample2.pdf) (clustering and classificaiton)

## Tasks

Complete the following tasks:

### Random walk
Implement a random walk of length *k* on a graph given the graph and an initial node as inputs.

### GCN-LPA
The loss function of the [GCN-LPA model](https://arxiv.org/pdf/2002.06755) consists of two terms: <img src="https://render.githubusercontent.com/render/math?math=L_{gcn}"> which is the softmax loss applied to the output features of the GCN and <img src="https://render.githubusercontent.com/render/math?math=L_{lpa}"> which is the loss you implemented last week. This is a softmax loss applied to the predicted labels obtained by *k* iterations of LPA.
* Implement the full GCN-LPA loss.
* Implement a layer that performs Label Propagation: it applies label propagation (equations 1-2) for *k* iterations to an input of initial labels (<img src="https://render.githubusercontent.com/render/math?math=Y^{(0)}">), and its variables are the graph weighted adjacency matrix ***A***.
* Implement the GCN layer in equation 16 using the random walk normalization <img src="https://render.githubusercontent.com/render/math?math=D^{-1}A"> you implemented last week. Its variables are both the trainable weight matrix ***W*** and the weighted adjacency matrix ***A***.
* Next week we will put together the full model and train and evaluate a GCN-LPA. This end-to-end model will learn both ***A*** and ***W***. Note that in this framework the edges themselves are fixed (we are not adding or removing edges) and we are only learning the weights of existing edges.
Note there is a confusing double use of the terms “weights”, once in ***W*** to represent the weights of the neural network and once in ***A*** to represent the edge weights of the graph.


## Weekly Questions

Answer the following questions
1.    How is Label Propagation related to a random walk?
2.    How can random walks be used to cluster data?
3. Plot 10 steps pf a random walk on the [Zachary Karate club graph](https://networkx.org/documentation/stable/reference/generated/networkx.generators.social.karate_club_graph.html?highlight=karate) starting from a random node. More details on this dataset [here](http://networkdata.ics.uci.edu/netdata/html/zacharyKarate.html).

