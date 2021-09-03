---
layout: week
title: Week 02
doodle: /doodle.png
---

# Graph-based Data

This week's assignments will guide you through the following topics:
* Graph properties and measures
* Graph construction 

## Reading

Please read the following:
* Read section 2.2-2.6, 2.8-2.10 of [Network Science by Barabási](http://networksciencebook.com/chapter/2#networks-graphs) - (this is mostly a review of material learned in DSC40B)
* [Graph theory centrality measures](https://towardsdatascience.com/notes-on-graph-theory-centrality-measurements-e37d2e49550a) - graph centrality memeasures identify vertices that are importnat within a graph or network.


### Replication task
This week we will begin reading the [GraphSage](https://www-cs.stanford.edu/~jure/pubs/graphsage-nips17.pdf) paper. As you read through the paper, keep a list of phrases and terms you are unfamiliar  with.
* Read the abstract and the conclusions.
* Read Sections 1-2. Note 2-3 references that sound interesting to you.

## Tasks

Complete the following tasks:
1. SNAP
* Explore the the [SNAP dataset collection](http://snap.stanford.edu/data/index.html) and download two datasets of different types.
* Using [network](https://networkx.github.io/) and/or [snap.py](http://snap.stanford.edu/snappy/index.html) explore, compare the properties and visualize the two graphs, based on the reading material. You may find these tutorials [1](https://networkx.github.io/documentation/stable/tutorial.html), [2](http://snap.stanford.edu/proj/snap-www/SNAP-WWW15-part3.pdf) helpful.

2. Cora - 
The Cora dataset consists of 2708 scientific publications classified into one of seven classes. The citation network consists of 5429 links. Each publication in the dataset is described by a 0/1-valued word vector indicating the absence/presence of the corresponding word from the dictionary. The dictionary consists of 1433 unique words. The README file in the dataset provides more details.
[Download Link](https://linqs-data.soe.ucsc.edu/public/lbc/cora.tgz).
* Download the Cora dataset. Read the readme file. 
* Construct a graph from the features (word_attributes within cora.content) using one of the methods you learned about in section 2.2 of the von Luxburg tutorial in week 1.
* Construct an adjacency matrix from the citation information given in cora.cites. Compare the graph properties of the constructed graph to the given citation graph. Are the graphs similar?

## Weekly Questions
Answer the folowing questions on Canvas:
* Submit the visualization of the two graphs you chose from the SNAP dataset. Calculate one of the centrality measures you learned about and color the nodes in the graph by their centrality.
* Compare the two SNAP graphs and report their average degree, network diameter, average path length, average clustering coefficient and plot their degree distribution.
* For Cora, visualize the constructed graph and the given citation graph. Overlay the node labels (paper classes) on the graphs. Which does a better job of separating the papers according to the label?
