
<h1 align="center"> 
  Awesome Multi-Agent Reinforcement Learning (MARL) 
  <br>on Graphs 
 </h1>

<p align="center">
  <img src="https://awesome.re/badge.svg">
  <a href="https://github.com/clandolt/awesome-marl-on-graphs">
    <img src="https://img.shields.io/badge/Awesome-AwesomeMARLonGraphs-orange">
  </a>
  <a href="https://github.com/clandolt/awesome-marl-on-graphs/stargazers">
    <img src="https://img.shields.io/github/stars/clandolt/awesome-marl-on-graphs">
  </a>
  <a href="https://github.com/clandolt/awesome-marl-on-graphs/network/members">
    <img src="https://img.shields.io/github/forks/clandolt/awesome-marl-on-graphs">
  </a>
  <a href="https://github.com/clandolt/awesome-marl-on-graphs">
    <img src="https://img.shields.io/github/issues/clandolt/awesome-marl-on-graphs">
  </a>
</p>


A curated collection of resources, implementations, research papers, and tools focused on **Multi-Agent Reinforcement Learning (MARL)** in the context of **Graph-based** environments. This repository aims to provide a comprehensive overview of the intersection between MARL and graph theory, enabling researchers and developers to explore, understand, and build on the emerging applications of multi-agent systems in graph-structured domains.

<p align="center">
<img src="img/marl_on_graphs.webp" width="30%", height="30%">
</p>

## What is MARL on Graphs?

Multi-Agent Reinforcement Learning (MARL) involves multiple agents interacting within an environment, with the goal of learning optimal policies through trial and error. In graph-based environments, these agents are typically represented as nodes in a graph, with edges defining relationships or interactions between agents. This setup allows for a diverse range of applications, from social network analysis to decentralized decision-making in robotics and smart grids.

## Who is this for?

- Researchers and practitioners interested in **multi-agent systems** and **reinforcement learning**.
- Developers looking for resources to **implement MARL algorithms** in graph-based environments.
- Students seeking a comprehensive introduction to the **intersection of MARL and graph theory**.

## Table of Contents

- [Graph-Based Machine Learning](#-graph-based-machine-learning)
  - [Papers](#papers)
  - [Books](#books)
  - [Talks](#talks)
- [Game Theory for Machine Learning](#game-theory-for-machine-learning)
  - [GANs](#gans)
  - [Other Resources](#other-resources)
- [Multi-Agent Reinforcement Learning](#multi-agent-reinforcement-learning)
  - [Papers](#papers)
  - [Talks](#talks)
  - [Books](#books)
  - [Blogs](#blogs)
  - [Miscellaneous](#miscellaneous)

---

## Graph-Based Machine Learning

Graph-based machine learning focuses on applying machine learning techniques to graph-structured data.

### Papers
- [(2024) Graph Transformers: A Survey, Ahsan Shehzad et al.](https://arxiv.org/abs/2407.09777)
- [(2024) Explaining the Explainers in Graph Neural Networks: a Comparative Study, Antonio Longa et al.](https://dl.acm.org/doi/abs/10.1145/3696444)
- [(2024) Graph Mamba: Towards Learning on Graphs with State Space Models, Ali Behrouz  et al.](https://dl.acm.org/doi/abs/10.1145/3637528.3672044?casa_token=xiBPTGSwMcwAAAAA:GVyBPDQx8K66mGf-aP52A41N7WkMj5C5n85B71TQ2VJJJrhngLJlpitKT7ihtqQ6NJ5kUgTb2BBEYQ)
- [(2023) On the Connection Between MPNN and Graph Transformer, Chen Cai et al.](https://proceedings.mlr.press/v202/cai23b/cai23b.pdf)
- [(2023) Attending to Graph Transformers, Luis Müller et al.](https://arxiv.org/abs/2302.04181)
- [(2023) A Network Science perspective of Graph Convolutional Networks: A survey, Mingshan Jia et al.](https://arxiv.org/pdf/2301.04824)
- [(2023) Co-embedding of edges and nodes with deep graph convolutional neural networks, Yuchen Zhou et al.](https://www.nature.com/articles/s41598-023-44224-1)
- [(2023) A Generalization of ViT/MLP-Mixer to Graphs, Xiaoxin He et al.](https://proceedings.mlr.press/v202/he23a.html)
- [(2023) Neural Graphical Models, Shrivastava  et al.](https://www.microsoft.com/en-us/research/publication/neural-graphical-models/)
- [(2022) GraphGPS: General Powerful Scalable Graph Transformers, Rampasek et al.](https://github.com/rampasek/GraphGPS)
- [(2021) Knowledge Embedding Based Graph Convolutional Network, Donghan Yu et al.](https://github.com/PlusRoss/KE-GCN)
- [(2020) Machine Learning on Graphs: A Model and Comprehensive Taxonomy, Ines Chami et al.](https://arxiv.org/abs/2005.03675)
- [(2020) Graph Representation Learning via Graphical Mutual Information Maximization, Zhen Peng et al.](https://arxiv.org/abs/2002.01169)
- [(2019) How powerful are graph neural networks?, Keyulu Xu et al.](https://arxiv.org/abs/1810.00826)
- [(2019) Hyperbolic Graph Convolutional Neural Networks, Ines Chami et al.](https://arxiv.org/abs/1910.12933)
- [(2019) Hyperbolic Graph Neural Networks, Qi Liu et al.](https://arxiv.org/abs/1910.12892)
- [(2019) Graphite: Iterative Generative Modeling of Graphs, Aditya Grover et al.](https://arxiv.org/pdf/1803.10459)
- [(2019) Fast Graph Representation Learning with PyTorch Geometric, Matthias Fey et al.](https://arxiv.org/abs/1903.02428)
- [(2018) Relational inductive biases, deep learning, and graph networks, Peter W. Battaglia et al.](https://arxiv.org/abs/1806.01261)
- [(2018) Deep Graph Infomax, Petar Veličković et al.](https://arxiv.org/abs/1809.10341)
- [(2017) Neural Message Passing for Quantum Chemistry, Justin Gilmer et al.](https://arxiv.org/abs/1704.01212)
- [(2017) Learning Edge Representations via Low-Rank Asymmetric Projections, Sami Abu-El-Haija et al.](https://arxiv.org/abs/1705.05615)
- [(2017) Watch Your Step: Learning Node Embeddings via Graph Attention, Sami Abu-El-Haija et al.](https://arxiv.org/abs/1710.09599)
- [(2017) Inductive Representation Learning on Large Graphs, William L. Hamilton et al.](https://arxiv.org/abs/1706.02216)
- [(2017) Graph Attention Networks, Petar Veličković et al.](https://arxiv.org/abs/1710.10903)
- [(2017) Poincaré Embeddings for Learning Hierarchical Representations, Maximilian Nickel et al.](https://arxiv.org/abs/1705.08039)
- [(2016) Geometric deep learning: going beyond Euclidean data, Michael M. Bronstein et al.](https://arxiv.org/abs/1611.08097)
- [(2016) Semi-Supervised Classification with Graph Convolutional Networks, Thomas N. Kipf et al.](https://arxiv.org/abs/1609.02907)
- [(2016) node2vec: Scalable Feature Learning for Networks, Aditya Grover et al.](https://arxiv.org/abs/1607.00653)
- [(2016) Geometric deep learning on graphs and manifolds using mixture model CNNs, Federico Monti et al.](https://arxiv.org/abs/1611.08402)
- [(2016) Structural Deep Network Embedding, Daixin Wang et al.](https://www.kdd.org/kdd2016/papers/files/rfp0191-wangAemb.pdf)
- [(2016) Revisiting Semi-Supervised Learning with Graph Embeddings,  Zhilin Yang et al.](https://arxiv.org/pdf/1603.08861)
- [(2015) Gated Graph Sequence Neural Networks, Yujia Li et al.](https://arxiv.org/abs/1511.05493)
- [(2015) Geodesic convolutional neural networks on Riemannian manifolds, Jonathan Masci et al.](https://arxiv.org/abs/1501.06297)
- [(2014) DeepWalk: Online Learning of Social Representations, Bryan Perozzi et al.](https://arxiv.org/abs/1403.6652)
- [(2013) Spectral Networks and Locally Connected Networks on Graphs, Joan Bruna et al.](https://arxiv.org/abs/1312.6203)
- [(2011) Low Distortion Delaunay Embedding of Trees in Hyperbolic Plane](https://link.springer.com/chapter/10.1007/978-3-642-25878-7_34)
- [(2009) The Graph Neural Network Model, Franco Scarselli et al.](https://ieeexplore.ieee.org/document/4700287)
- [(2005) A new model for learning in graph domains, M. Gori et al.](https://ieeexplore.ieee.org/document/1555942)

### Papers Graph Based Reinforcement Learning
- [(2022) Reinforcement learning on graphs: A survey, Mingshuo Nie et al.](https://arxiv.org/abs/2204.06127)
- [(2020) Graph Convolutional Reinforcement Learning, Jiechuan et al.](https://openreview.net/pdf?id=HkxdQkSYDB)
- [(2018) Reinforcement Learning Combinatorial Optimization Algorithms over Graphs, Elias B. Khalil](https://arxiv.org/abs/1704.01665) [Video:](https://www.youtube.com/watch?v=z5vSUl0XcNo)


### Books
- [*Probabilistic Machine Learning: An Introduction* by Kevin Patrick Murphy (MIT Press, March 2022.)](https://probml.github.io/pml-book/book1.html)
- [(2025) Graph Representation Learning Book, William L. Hamilton et al.](https://www.cs.mcgill.ca/~wlh/grl_book/)

### Talks and Videos
- [Understanding Graph Neural Networks | Part 1/3 - Introduction](https://www.youtube.com/watch?v=fOctJB4kVlM&list=PLV8yxwGOxvvoNkzPfCx2i8an--Tkt7O8Z)
- [Understanding Graph Neural Networks | Part 2/3 - GNNs and it's Variants](https://www.youtube.com/watch?v=ABCGCf8cJOE&list=PLV8yxwGOxvvoNkzPfCx2i8an--Tkt7O8Z&index=3)
- [How to use edge features in Graph Neural Networks (and PyTorch Geometric)](https://www.youtube.com/watch?v=mdWQYYapvR8)
- [Data handling in PyTorch Geometric (Part 1)](https://www.youtube.com/watch?v=Vz5bT8Xw6Dc)
- [Pytorch Geometric tutorial: Edge analysis](https://www.youtube.com/watch?v=m1G7oS9hmwE)
- [Advanced PyTorch Geometric Tutorial 4](https://www.youtube.com/watch?v=qL09oshDKww)
- [Fast Graph Representation Learning with PyTorch Geometric (PyG), Matthias Fey et al.](https://rusty1s.github.io/pyg_slides.pdf)
- [Stanford CS224W: Machine Learning with Graphs | 2021 | Lecture 1.1 - Why Graphs](https://www.youtube.com/watch?v=JAB_plj2rbA)
- [(2023) Overview of Graph Representation Learning (Slides),  Jure Leskovec](https://snap.stanford.edu/graphlearning-workshop/slides/stanford_graph_learning_Overview.pdf)
- [(2023) PyG 2.0 Advanced Representation Learning on Graphs (Slides), Talk by Matthias Fey](https://snap.stanford.edu/graphlearning-workshop/slides/stanford_graph_learning_PyG_2_0.pdf)
- [(2023) GraphGym: Easy-to-use API for Graph Learning (Slides), Talk by Jiaxuan You](https://snap.stanford.edu/graphlearning-workshop/slides/stanford_graph_learning_GraphGym.pdf)

### Learning Ressources
- [Stanford CS224W Graph ML Projects](https://medium.com/stanford-cs224w)
- [Stanford CS224W: Machine Learning with Graphs (Playlist)](https://www.youtube.com/playlist?list=PLoROMvodv4rOP-ImU-O1rYRg2RFxomvFp)


### Blog Posts
- [(2024) Graph Neural Networks Part 2. Graph Attention Networks vs. GCNs (medium.com article), Hennie de Harder](https://towardsdatascience.com/graph-neural-networks-part-2-graph-attention-networks-vs-gcns-029efd7a1d92)
- [(2024) Graph Neural Networks Part 1. Graph Convolutional Networks Explained (medium.com article), Hennie de Harder](https://towardsdatascience.com/graph-neural-networks-part-1-graph-convolutional-networks-explained-9c6aaa8a406e)

### GNN software library
- The software library available for graph neural network development: [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/)
- Easy-to-use API for Graph Learning: [GraphGym](https://snap.stanford.edu/graphlearning-workshop/slides/stanford_graph_learning_GraphGym.pdf)
- Library to process spatio-temporal signals: [PyTorch Geometric Temporal](https://pytorch-geometric-temporal.readthedocs.io/en/latest/index.html)
- A space representing graph information as a series of nodes connected with edges: [Gymnasium Spaces Graph](https://gymnasium.farama.org/api/spaces/composite/#gymnasium.spaces.Graph)

### Graph database

Graph databases are database management systems that store information as logical nodes and edges, representing information as a connected graph rather than tables and columns. Graph lends itself well to the complex data and datasets enterprises seek to connect and understand. Graph is used for everything from fraud detection to recommendation engines. Neo4j is the world’s leading provider of scalable graph technology, enabling connected data applications for more than 75% of the Fortune 100 companies. See: [Neo4j - Quick Guide](tutorialspoint.com)

---

## Game Theory for Machine Learning

Game theory plays a significant role in understanding competitive and cooperative behaviors in multi-agent systems, including GANs.

### GANs
- [(2021) Game of GANs: Game-Theoretical Models for Generative Adversarial Networks, Monireh Mohebbi Moghadam et al.](https://arxiv.org/abs/2106.06976)

### Other Resources
- [tbd](#)

---

## Multi-Agent Reinforcement Learning

Multi-Agent Reinforcement Learning (MARL) involves multiple agents interacting in an environment, learning to maximize their respective rewards through coordinated actions.

### Papers
- [tbd](#)

### Talks
- [tbd](#)

### Books
- [(2024) *Multi-Agent Reinforcement Learning: Foundations and Modern Approaches*, Stefano V. Albrecht et al.](https://www.marl-book.com/)

### Blogs
- [tbd](#)


## Contribute

Contributions are very welcome. Please use Github issues and pull requests.

### List of Contributors

Thanks for all your contributions and keeping this project up-to-date.

<a href="https://github.com/clandolt/awesome-marl-on-graphs/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=clandolt/awesome-marl-on-graphs" />
</a>

## License

[LICENSE](LICENSE)

Creative Commons

(C) 2021-2024
