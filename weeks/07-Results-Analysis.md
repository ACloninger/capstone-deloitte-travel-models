---
layout: week
title: Week 07
doodle: /doodle.png
---

# Benchmarking graph neural networks

## Topics

This week's assignments will guide you through the following topics:
* Evaluation of graph neural network models 
* Implementation of replication networks 

## Reading

### Benchmarks
Read the following two papers on benchmarking graph neural networks (you don’t need to understand every detail but rather get a high-level view of the challenges)

*  [Open Graph Benchmark: Datasets for Machine Learning on Graphs](https://arxiv.org/pdf/2005.00687.pdf)
*  [Benchmarking Graph Neural Networks](https://arxiv.org/pdf/2003.00982.pdf)

### Replication papers
Read section 4 (Experiments) of both replication papers (GCN-LPA and GraphSage).


## Tasks
Complete the following tasks: 
### GCN-LPA
•	Using the components you implemented last week, put together the full GCN-LPA network 
•	Run the network on Cora / Citeseer  using the hyper-parameters defined in Appendix F. 

### GraphSage
Two options (choose to perform either 1 or 2)

(1)	Finish implementing the GraphSage framework using the components you implemented in weeks 4 and 5.

Or 

(2)	The following [repository](https://github.com/williamleif/graphsage-simple) has a basic pytorch implementation of GraphSage with a supervised loss and mean aggregator. 
*	Based on the mean aggregator code, implement your own version of a pooling aggregator.
*	Based on the random walk code you implemented last week, implement the unsupervised loss in equation 1. 

## Weekly Questions

Answer the following questions
1.	Based on the reading describe a challenge with benchmarking (evaluating and comparing) graph neural networks.
2.	Go to the Open Graph Benchmark [website](https://ogb.stanford.edu/), choose a dataset you would like to evaluate your model on and provide the details of this dataset (so we can add it to the Datahub cluster).
3.	Report your accuracy on evaluating GCN-LPA on Cora or Citeseer. How does it compare to the paper?   



