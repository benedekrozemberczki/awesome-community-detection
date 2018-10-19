# Awecome Community Detection
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A collection of community detection papers with implementations.

<p align="center">
  <img width="460" src="coms.png">
</p>

##### Table of Contents  

1. [Factorization](#factorization)  
2. [Deep Learning](#deep-learning) 
3. [Percolation](#percolation) 
4. [Label Propagation and Random Walks](#label-propagation-and-random-walks) 
5. [Tensor Decomposition](#tensor-decomposition)
6. [Spectral Methods](#spectral-methods) 
7. [Dynamic Networks](#dynamic-networks) 
8. [Others](#others) 
  
## Factorization
- **Graph Embedding with Self-Clustering (Arxiv 2018)**
  - Benedek Rozemberczki, Ryan Davies, Rik Sarkar and Charles Sutton
  - [[paper]](https://arxiv.org/abs/1802.03997)
  - [[Python Reference]](https://github.com/benedekrozemberczki/GEMSEC)
  
- **A Unified Framework for Community Detection and Network Representation Learning (TKDE 2018)**
  - Cunchao Tu, Xiangkai Zeng, Hao Wang, Zhengyan Zhang, Zhiyuan Liu, Maosong Sun, Bo Zhang and Leyu Lin
  - [[paper]](https://arxiv.org/pdf/1611.06645.pdf)
  - [[Java Reference]](http://nlp.csai.tsinghua.edu.cn//~tcc/datasets/simplified_CNRL.zip)
  
- **Community Preserving Network Embedding (AAAI 17)**
  -  Xiao Wang, Peng Cui, Jing Wang, Jain Pei, WenWu Zhu, Shiqiang Yang
  - [[paper]](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14589/13763)
  - [[Python Reference]](https://github.com/benedekrozemberczki/M-NMF)
  
- **Learning Community Embedding with Community Detection and Node Embedding on Graph (CIKM 2017)**
  - Sandro Cavallari, Vincent W. Zheng, Hongyun Cai, Kevin Chen-Chuan Chang, and Erik Cambria
  - [[paper]](http://sentic.net/community-embedding.pdf)
  - [[Python Reference]](https://github.com/andompesta/ComE)
  
- **A Uniﬁed Semi-Supervised Community Detection Framework Using Latent Space Graph Regularization (IEEE TOC 2015)**
  - Liang Yang, Xiaochun Cao, Di Jin, Xiao Wang and Dan Meng
  - [[paper]](http://yangliang.github.io/pdf/06985550.pdf)
  - [[Matlab reference]](http://yangliang.github.io/code/LSGR.rar)
  
- **Overlapping Community Detection Using Bayesian Non-negative Matrix Factorization (Physical Review E 2011)**
  - Ionnis Psorakis, Stephen Roberts, Mark Ebden, and Ben Sheldon
  - [[paper]](http://www.orchid.ac.uk/eprints/38/1/PRE_NMF.pdf)
  - [[Matlab reference]](https://github.com/ipsorakis/commDetNMF)
  
## Deep Learning
- **Improving the Efficiency and Effectiveness of Community Detection via Prior-Induced Equivalent Super-Network (Scientific Reports 2017)**
  - Liang Yang, Di Jin, Dongxiao He, Huazhu Fu, Xiaochun Cao and Francoise Fogelman-Soulie
  - [[paper]](http://yangliang.github.io/pdf/sr17.pdf)
  - [[Python Reference]](http://yangliang.github.io/code/SUPER.zip)
  
- **Community Detection with Graph Neural Networks (ArXiv 2017)**
  - Zhengdao Chen, Xiang Li, Joan Bruna
  - [[paper]](https://arxiv.org/abs/1705.08415)
  - [[LUA Reference]](https://github.com/joanbruna/GNN_community)
  
- **Modularity based Community Detection with Deep Learning (IJCAI 2016)**
  - Liang Yang, Xiaochun Cao, Dongxiao He, Chuan Wang, Xiao Wang and Weixiong Zhan
  - [[paper]](http://yangliang.github.io/pdf/ijcai16.pdf)
  - [[Python Reference]](http://yangliang.github.io/code/DC.zip)
  
## Percolation

## Label Propagation and Random Walks

- **Community Detection Based on Structure and Content: A Content Propagation Perspective (ICDM 2015)**
  -  Liyuan Liu, Linli Xu, Zhen Wangy, and Enhong Chen 
  - [[paper]](http://home.ustc.edu.cn/~llychina/papers/CommunityICDM15.pdf)
  - [[Matlab reference]](https://github.com/LiyuanLucasLiu/Content-Propagation)
  
- **SLPA: Uncovering Overlapping Communities in Social Networks via A Speaker-listener Interaction Dynamic Process (ICDMW 2011)**
  - Jierui Xie and Boleslaw K Szymanski and Xiaoming Liu
  - [[paper]](https://arxiv.org/pdf/1109.5720.pdf)
  - [[Java]](https://github.com/sebastianliu/SLPA-community-detection)
  - [[Python]](https://github.com/kbalasu/SLPA)
  - [[C++]](https://github.com/arminbalalaie/graphlab-slpa)
  
## Tensor Decomposition
- **Community detection, link prediction, and layer interdependence in multilayer networks (Physical Review E 2017)**
  - Caterina De Bacco, Eleanor A. Power, Daniel B. Larremore and Cristopher Moore
  - [[paper]](https://arxiv.org/abs/1701.01369)
  - [[Python Reference]](https://github.com/cdebacco/MultiTensor)
  
- **Fast Detection of Overlapping Communities via Online Tensor Methods on GPUs (ArXiV 2013)**
  - Furong Huang and Niranjan, UN and Hakeem, M and Anandkumar, Animashree
  - [[paper]](https://www.semanticscholar.org/paper/Fast-Detection-of-Overlapping-Communities-via-on-Huang-Niranjan/356e6c7eacca6caa94a5a96f41a9c785064f5693)
  - [[C++](https://github.com/mapleyustat/Fast-Detection-of-Overlapping-Communities-via-Online-Tensor-Methods)

## Spectral Methods

- **Uncovering the Small Community Structure in Large Networks: a Local Spectral Approach (WWW 2015)**
  - Li Yixuan and He Kun and David Bindel and John Hopcroft
  - [[paper]](https://arxiv.org/abs/1509.07715)
  - [[Python Reference]](https://github.com/YixuanLi/LEMON)
  
## Dynamic Networks

- **Sequential Detection of Temporal Communities by Estrangement Confinement (Scientific Reports 2012)**
  - Vikas Kawadia and Sameet Sreenivasan
  - [[paper]](https://www.nature.com/articles/srep00794)
  - [[Python Reference]](https://github.com/kawadia/estrangement)
  
## Others

- **An Overlapping Community Detection Algorithm Based on Density Peaks (NeuroComputing 2017)**
  - Xueying Bai, Peilin Yang and Xiaohu Shi
  - [[paper]](https://www.sciencedirect.com/science/article/pii/S092523121631400X)
  - [[Matlab Reference]](https://github.com/XueyingBai/An-overlapping-community-detection-algorithm-based-on-density-peaks)
  
- **Real-Time Community Detection in Large Social Networks on a Laptop (ArXiv 2017)**
  - Benjamin Paul Chamberlain, Josh Levy-Kramer, Clive Humby, and Marc Peter Deisenroth
  - [[paper]](https://arxiv.org/pdf/1601.03958.pdf)
  - [[Python Reference]](https://github.com/melifluos/LSH-community-detection)
  
- **Discovering Fuzzy Structural Patterns for Graph Analytics (IEEE TFS 2018)**
  - Tiantian He  and Keith C. C. Chan 
  - [[paper]](https://ieeexplore.ieee.org/document/8253904)
  - [[Reference]](https://github.com/he-tiantian/FSPGA)
