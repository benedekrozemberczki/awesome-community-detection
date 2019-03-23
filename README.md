# Awesome Community Detection
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A collection of community detection papers with implementations.

A similar collection on [[graph embedding]](https://github.com/benedekrozemberczki/awesome-graph-embedding) papers with implementations.

<p align="center">
  <img width="460" src="coms.png">
</p>

##### Table of Contents  

1. [Factorization](#factorization)  
2. [Deep Learning](#deep-learning) 
3. [Label Propagation, Percolation and Random Walks](#label-propagation-percolation-and-random-walks) 
4. [Tensor Decomposition](#tensor-decomposition)
5. [Spectral Methods](#spectral-methods) 
6. [Temporal Methods](#temporal-methods) 
7. [Cyclic Patterns](#cyclic-patterns)
8. [Centrality and Cuts](#centrality-and-cuts) 
9. [Physics Inspired](#physics-inspired) 
10. [Others](#others) 

## Factorization

- **Graph Embedding with Self-Clustering (Arxiv 2018)**
  - Benedek Rozemberczki, Ryan Davies, Rik Sarkar, and Charles Sutton
  - [[Paper]](https://arxiv.org/abs/1802.03997)
  - [[Python Reference]](https://github.com/benedekrozemberczki/GEMSEC)
  
- **Non-Linear Attributed Graph Clustering by Symmetric NMF with PU Learning (Arxiv 2018)**
  - Seiji Maekawa, Koh Takeuch, Makoto Onizuka
  - [[Paper]](https://arxiv.org/abs/1810.00946)
  - [[Python Reference]](https://github.com/seijimaekawa/NAGC)
  
- **Deep Autoencoder-like Nonnegative Matrix Factorization for Community Detection (CIKM 2018)**
  - Fanghua Ye, Chuan Chen, and Zibin Zheng
  - [[Paper]](https://smartyfh.com/Documents/18DANMF.pdf)
  - [[Python Reference]](https://github.com/benedekrozemberczki/DANMF)
  - [[Matlab Reference]](https://github.com/smartyfh/DANMF)

- **Adaptive Community Detection Incorporating Topology and Content in Social Networks (Knowledge-Based Systems 2018)**
  - Qin Meng, Jin Di, Lei Kai, Bogdan Gabrys, Katarzyna, Musial-Gabrys
  - [[Paper]](https://www.sciencedirect.com/science/article/pii/S0950705118303885?dgcid=coauthor)
  - [[Matlab Reference]](https://github.com/KuroginQin/ASCD)

- **Learning Latent Factors for Community Identification and Summarization (IEEE Access 2018)**
  - Tiantian He, Lun Hu, Keith C. C. Chan, and Pengwei Hu 
  - [[Paper]](https://ieeexplore.ieee.org/document/8374421)
  - [[Executable Reference]](https://github.com/he-tiantian/LFCIS)
  
- **Bayesian Robust Attributed Graph Clustering: Joint Learning of Partial Anomalies and Group Structure (AAAI 2018)**
  - Aleksandar Bojchevski and Stephan Günnemann
  - [[Paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16363/16542)
  - [[Python Reference]](https://github.com/abojchevski/paican)
  
- **Sentiment-driven Community Profiling and Detection on Social Media (ACM HSM 2018)**
  - Amin Salehi, Mert Ozer, and Hasan Davulcu
  - [[Paper]](https://arxiv.org/pdf/1810.06917v1.pdf)
  - [[Matlab Reference]](https://github.com/amin-salehi/GSNMF)
  
- **TNE: A Latent Model for Representation Learning on Networks (Arxiv 2018)**
  - Abdulkadir Çelikkanat and Fragkiskos D. Malliaros 
  - [[Paper]](https://arxiv.org/pdf/1611.06645.pdf)
  - [[Python Reference]](https://github.com/abdcelikkanat/TNE)
  
- **Non-Linear Attributed Graph Clustering by Symmetric NMF with PU Learning (Arxiv 2018)**
  - Seiji Maekawa, Koh Takeuch, Makoto Onizuka
  - [[Paper]](https://arxiv.org/abs/1810.00946)
  - [[Python Reference]](https://github.com/seijimaekawa/NAGC)
  
- **Community Preserving Network Embedding (AAAI 17)**
  - Xiao Wang, Peng Cui, Jing Wang, Jain Pei, WenWu Zhu, Shiqiang Yang
  - [[Paper]](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14589/13763)
  - [[Python Reference]](https://github.com/benedekrozemberczki/M-NMF)
  - [[Matlab Reference]](https://github.com/AnryYang/M-NMF)
  
- **Self-weighted Multiview Clustering with Multiple Graphs (IJCAI 17)**
  - Feiping Nie, Jing Li, and Xuelong Li
  - [[Paper]](https://www.ijcai.org/proceedings/2017/0357.pdf)
  - [[Matlab Reference]](https://github.com/kylejingli/SwMC-IJCAI17)
  
- **Semi-supervised Clustering in Attributed Heterogeneous Information Networks (WWW 17)**
  - Xiang Li, Yao Wu, Martin Ester, Ben Kao, Xin Wang, and Yudian Zheng
  - [[Paper]](https://dl.acm.org/citation.cfm?id=3052576)
  - [[Python Reference]](https://github.com/wedoso/SCHAIN-NL)
  
- **Learning Community Embedding with Community Detection and Node Embedding on Graph (CIKM 2017)**
  - Sandro Cavallari, Vincent W. Zheng, Hongyun Cai, Kevin Chen-Chuan Chang, and Erik Cambria
  - [[Paper]](http://sentic.net/community-embedding.pdf)
  - [[Python Reference]](https://github.com/andompesta/ComE)
  
- **Cross-Validation Estimate of the Number of Clusters in a Network (Scientific Report 2017)**
  - Matsuro Kawamoto and Yoshiyuki Kabashima
  - [[Paper]](https://arxiv.org/abs/1605.07915)
  - [[Julia Reference]](https://github.com/tatsuro-kawamoto/graphBIX)
  
- **Comparative Analysis on the Selection of Number of Clusters in Community Detection (ArXiv 2017)**
  - Matsuro Kawamoto and Yoshiyuki Kabashima
  - [[Paper]](https://arxiv.org/abs/1606.07668)
  - [[Julia Reference]](https://github.com/tatsuro-kawamoto/graphBIX)
  
- **Joint Community and Structural Hole Spanner Detection via Harmonic Modularity (KDD 2016)**
  - Lifang He, Chun-Ta Lu, Jiaqi Mu, Jianping Cao, Linlin Shen, and Philip S Yu
  - [[Paper]](https://www.kdd.org/kdd2016/papers/files/rfp1184-heA.pdf)
  - [[Python Reference]](https://github.com/LifangHe/KDD16_HAM)
  
- **Community Detection via Fused Loadings Principal Component Analysis (2016)**
  - Richard Samworth, Yang Feng, and Yi Yu
  - [[R Reference]](https://github.com/cran/FusedPCA)

- **Feature Extraction via Multi-view Non-negative Matrix Factorization with Local Graph Regularization (IEEE ICIP 2015)**
  - Zhenfan Wang, Xiangwei Kong, Hiayan Fu, Ming Li, and Yujia Zhang
  - [[Paper]](https://ieeexplore.ieee.org/document/7351455)
  - [[Matlab Reference]](https://github.com/DUT-DIPLab/Graph-Multi-NMF-Feature-Clustering)
  
- **A Uniﬁed Semi-Supervised Community Detection Framework Using Latent Space Graph Regularization (IEEE TOC 2015)**
  - Liang Yang, Xiaochun Cao, Di Jin, Xiao Wang, and Dan Meng
  - [[Paper]](http://yangliang.github.io/pdf/06985550.pdf)
  - [[Matlab Reference]](http://yangliang.github.io/code/LSGR.rar)
  
- **Community Detection via Measure Space Embedding (NIPS 2015)**
  - Mark Kozdoba and Shie Mannor
  - [[Paper]](https://papers.nips.cc/paper/5808-community-detection-via-measure-space-embedding.pdf)
  - [[Python Reference]](https://github.com/komarkdev/der_graph_clustering)
  
- **Community Detection for Clustered Attributed Graphs via a Variational EM Algorithm (Big Data 2014)**
  - Xiangyong Cao, Xiangyu Chang, and Zongben Xu
  - [[Paper]](https://dl.acm.org/citation.cfm?id=2644179)
  - [[Matlab Reference]](https://github.com/xiangyongcao/Variational-EM-for-Community-Detection)
  
- **Improved Graph Clustering (Transactions on Information Network Theory 2014)**
  - Yudong Chen, Sujay Sanghavi, Huan Xu 
  - [[Paper]](https://ieeexplore.ieee.org/document/6873307)
  - [[Matlab Reference]](https://github.com/sara-karami/improved_graph_clustering)
  
- **Overlapping Community Detection at Scale: a Nonnegative Matrix Factorization Approach (WSDM 2013)**
  - Jaewon Yang and Jure Leskovec
  - [[Paper]](http://i.stanford.edu/~crucis/pubs/paper-nmfagm.pdf)
  - [[C++ Reference]](https://github.com/snap-stanford/snap/tree/master/examples/bigclam)
  - [[Java Spark Reference]](https://github.com/thangdnsf/BigCLAM-ApacheSpark)
  - [[Python Reference]](https://github.com/RobRomijnders/bigclam)
  
- **Symmetric Nonnegative Matrix Factorization for Graph Clustering (SDM 2012)**
  - Da Kuang, Chris Ding, and Haesun Park
  - [[Paper]](https://www.cc.gatech.edu/~hpark/papers/DaDingParkSDM12.pdf)
  - [[Matlab Reference]](https://github.com/dakuang/symnmf)
  
- **A Model-based Approach to Attributed Graph Clustering (SIGMOID 2012)**
  - Zhiqiang Xu, Yiping Ke, Yi Wang, Hong Cheng, and James Cheng
  - [[Paper]](http://www-std1.se.cuhk.edu.hk/~hcheng/paper/BAGC_sigmod12.pdf)
  - [[Matlab Reference]](https://github.com/zhiqiangxu2001/BAGC)
  
- **Overlapping Community Detection Using Bayesian Non-negative Matrix Factorization (Physical Review E 2011)**
  - Ionnis Psorakis, Stephen Roberts, Mark Ebden, and Ben Sheldon
  - [[Paper]](http://www.orchid.ac.uk/eprints/38/1/PRE_NMF.pdf)
  - [[Matlab Reference]](https://github.com/ipsorakis/commDetNMF)
  
## Deep Learning

- **Supervised Community Detection with Line Graph Neural Networks (ICLR 2019)**
  - Zhengdao Chen, Xiang Li, and Joan Bruna
  - [[Paper]](https://arxiv.org/abs/1705.08415)
  - [[LUA Reference]](https://github.com/joanbruna/GNN_community)
  - [[Python Reference]](https://github.com/afansi/multiscalegnn)
  
- **CommunityGAN: Community Detection with Generative Adversarial Nets (ArXiv 2019)**
  - Yuting Jia, Qinqin Zhang, Weinan Zhang, Xinbing Wang
  - [[Paper]](https://arxiv.org/abs/1901.06631)
  - [[Python Reference]](https://github.com/SamJia/CommunityGAN)
  
- **An Adaptive Graph Learning Method Based on Dual Data Representations for Clustering (Pattern Recognition 2018)**
  - Tianchi Liu, Chamara Kasun, Liyanaarachchi Lekamalage Guang-Bin Huang, and Zhiping Lin
  - [[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320317304880)
  - [[Matlab Reference]](https://github.com/liut0012/ELM-CLR)

- **Improving the Efficiency and Effectiveness of Community Detection via Prior-Induced Equivalent Super-Network (Scientific Reports 2017)**
  - Liang Yang, Di Jin, Dongxiao He, Huazhu Fu, Xiaochun Cao, and Francoise Fogelman-Soulie
  - [[Paper]](http://yangliang.github.io/pdf/sr17.pdf)
  - [[Python Reference]](http://yangliang.github.io/code/SUPER.zip)
  
- **MGAE: Marginalized Graph Autoencoder for Graph Clustering (CIKM 2017)**
  - Chun Wang, Shirui Pan, Guodong Long, Xingquabn Zhu, and Jing Jiang
  - [[Paper]](https://dl.acm.org/citation.cfm?id=3132967)
  - [[Matlab Reference]](https://github.com/FakeTibbers/MGAE)
  
- **Graph Clustering with Dynamic Embedding (Arxiv 2017)**
  - Carl Yang, Mengxiong Liu, Zongyi Wang, Liyuan Liu, Jiawei Han
  - [[Paper]](https://arxiv.org/abs/1712.08249)
  - [[Python Reference]](https://github.com/yangji9181/GRACE)
  
- **Modularity based Community Detection with Deep Learning (IJCAI 2016)**
  - Liang Yang, Xiaochun Cao, Dongxiao He, Chuan Wang, Xiao Wang, and Weixiong Zhan
  - [[Paper]](http://yangliang.github.io/pdf/ijcai16.pdf)
  - [[Python Reference]](http://yangliang.github.io/code/DC.zip)
  
- **Learning Deep Representations for Graph Clustering (AAAI 2014)**
  - Fei Tian, Bin Gao, Qing Cui, Enhong Chen, and Tie-Yan Liu
  - [[Paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/view/8527)
  - [[Python Reference]](https://github.com/quinngroup/deep-representations-clustering)
  
## Label Propagation, Percolation and Random Walks

- **Dynamic Graph-Based Label Propagation for Density Peaks Clustering (Expert Systems 2019)**
  - Seyed Amjad Seyedi, Abdulrahman Lotfi, Parham Moradi and Nooruldeen Nasih Qader
  - [[Paper]](https://www.sciencedirect.com/science/article/pii/S0957417418304998?via%3Dihub)
  - [[Matlab Reference]](https://github.com/amjadseyedi/DPC-DLP)

- **Community Detection by Information Flow Simulation (ArXiv 2018)**
  - Rajagopal Venkatesaramani and Yevgeniy Vorobeychik 
  - [[Paper]](https://arxiv.org/abs/1805.04920)
  - [[Python Reference]](https://github.com/rajagopalvenkat/Community_Detection-Flow_Simulation)

- **Multiple Local Community Detection (ACM SIGMETRICS 2017)**
  - Alexandre Hollocou, Thomas Bonald, and Marc Lelarge
  - [[Paper]](https://hal.archives-ouvertes.fr/hal-01625444)
  - [[Python Reference]](https://github.com/ahollocou/multicom)
  
- **Krylov Subspace Approximation for Local Community Detection in Large Networks (ArXiv 2017)**
  - Kun He, Pan Shi, David Bindel, and John E. Hopcroft
  - [[Paper]](https://arxiv.org/pdf/1712.04823.pdf)
  - [[Matlab Reference]](https://github.com/PanShi2016/LOSP_Plus)
  
- **Many Heads are Better than One: Local Community Detection by the Multi-Walker Chain (ICDM 2017)**
  - Yuchen Bian, Jingchao Ni, Wei Cheng, and Zhang Xiang
  - [[Paper]](https://ieeexplore.ieee.org/document/8215474)
  - [[C++ Reference]](https://github.com/flyingdoog/MWC)

- **Improving PageRank for Local Community Detection (ArXiv 2016)**
  - Alexandre Hollocou, Thomas Bonald, and Marc Lelarge
  - [[Paper]](https://arxiv.org/abs/1610.08722)
  - [[C Reference]](https://github.com/ahollocou/walkscan)
  - [[Python Reference]](https://github.com/ahollocou/walkscan)
  
- **Limited Random Walk Algorithm for Big Graph Data Clustering (Journal of Big Data 2016)**
  - Honglei Zhang, Jenni Raitoharju, Serkan Kiranyaz, and Moncef Gabbouj
  - [[Paper]](https://arxiv.org/abs/1606.06450)
  - [[C++ Reference]](https://github.com/harleyzhang/LRW)
  
- **Community Detection Based on Structure and Content: A Content Propagation Perspective (ICDM 2015)**
  - Liyuan Liu, Linli Xu, Zhen Wang, and Enhong Chen 
  - [[Paper]](https://liyuanlucasliu.github.io/pdf/Liyuan-Liu-ICDM.pdf)
  - [[Matlab Reference]](https://github.com/LiyuanLucasLiu/Content-Propagation)
  
- **Modeling Community Detection Using Slow Mixing Random Walks (IEEE Big Data 2015)**
  - Ramezan Paravi, Torghabeh Narayana, and Prasad Santhanam
  - [[Paper]](https://ieeexplore.ieee.org/abstract/document/7364008)
  - [[Python Reference]](https://github.com/paravi/MarovCommunity)
  
- **GossipMap: A Distributed Community Detection Algorithm for Billion-Edge Directe Graphs (SC 2015)**
  - Seung-Hee Bae and Bill Howe
  - [[Paper]](https://dl.acm.org/citation.cfm?id=2807668)
  - [[C++ Reference]](https://github.com/uwescience/GossipMap)
  
- **Overlapping Community Detection Using Seed Set Expansion (CIKM 2013)**
  - Joyce Jiyoung Whang, David F. Gleich, and Inderjit S. Dhillon
  - [[Paper]](http://www.cs.utexas.edu/~inderjit/public_papers/overlapping_commumity_cikm13.pdf)
  - [[Python Reference]](https://github.com/pratham16/community-detection-by-seed-expansion)
  
- **Influence-Based Network-Oblivious Community Detection (ICDM 2013)**
  - Nicola Barbieri, Francesco Bonchi, and Giuseppe Manco 
  - [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6729581)
  - [[Java  Reference]](https://github.com/gmanco/cwn)
  
- **SLPA: Uncovering Overlapping Communities in Social Networks via A Speaker-listener Interaction Dynamic Process (ICDMW 2011)**
  - Jierui Xie, Boleslaw K Szymanski, and Xiaoming Liu
  - [[Paper]](https://arxiv.org/pdf/1109.5720.pdf)
  - [[Java Reference]](https://github.com/sebastianliu/SLPA-community-detection)
  - [[Python Reference]](https://github.com/kbalasu/SLPA)
  - [[C++ Reference]](https://github.com/arminbalalaie/graphlab-slpa)
  
- **On the Generation of Stable Communities of Users for Dynamic Mobile Ad Hoc Social Networks (IEEE ICOIN  2011)**
  - Guillaume-Jean Herbiet and Pascal Bouvry
  - [[Paper]](https://herbiet.gforge.uni.lu/research.html)
  - [[Java Reference]](https://github.com/gjherbiet/gs-sharc)
  
- **SHARC: Community-Based Partitioning for Mobile Ad Hoc Networks Using Neighborhood Similarity (IEEE WoWMoM 2010)**
  - Guillaume-Jean Herbiet and Pascal Bouvry
  - [[Paper]](https://herbiet.gforge.uni.lu/research.html)
  - [[Java Reference]](https://github.com/gjherbiet/gs-sharc)
  
- **Bridge Bounding: A Local Approach for Efficient Community Discovery in Complex Networks (ArXiv 2009)**
  - Symeon Papadopoulos, Andre Skusa, Athena Vakali, Yiannis Kompatsiaris, and Nadine Wagner
  - [[Paper]](https://arxiv.org/abs/0902.0871)
  - [[Java Reference]](https://github.com/kleinmind/bridge-bounding)
  
- **The Map Equation (The European Physical Journal Special Topics 2009)**
  - Martin Rossvall, Daniel Axelsson, and Carl T Bergstrom
  - [[Paper]](https://arxiv.org/abs/0906.1405)
  - [[R Reference]](igraph.org/r/doc/cluster_infomap.html)
  - [[C Reference]](http://igraph.org/c/)
  - [[Python Reference]](https://github.com/Tavpritesh/MapEquation)
  
- **Chinese Whispers: an Efficient Graph Clustering Algorithm and its Application to Natural Language Processing Problems (HLT NAACL 2006)**
  - Chris Biemann
  - [[Paper]](http://www.aclweb.org/anthology/W06-3812)
  - [[Python Reference]](https://github.com/sanmayaj/ChineseWhispers)
  
- **An Efficient Algorithm for Large-scale Detection of Protein Families (Nucleic Acids Research 2002)**
  - Anton Enright, Stijn Van Dongen, and Christos Ouzounis
  - [[Paper]](https://academic.oup.com/nar/article/30/7/1575/2376029)
  - [[Python Reference]](https://github.com/HarshHarwani/markov-clustering-for-graphs)
  - [[Python Reference]](https://github.com/lucagiovagnoli/Markov_clustering-Graph_API)
  
## Tensor Decomposition

- **Community Detection, Link Prediction, and Layer Interdependence in Multilayer Networks (Physical Review E 2017)**
  - Caterina De Bacco, Eleanor A. Power, Daniel B. Larremore, and Cristopher Moore
  - [[Paper]](https://arxiv.org/abs/1701.01369)
  - [[Python Reference]](https://github.com/cdebacco/MultiTensor)
  
- **Overlapping Community Detection via Constrained PARAFAC: A Divide and Conquer Approach (ICDM 2017)**
  - Fatemeh Sheikholeslami and Georgios B. Giannakis 
  - [[Paper]](https://ieeexplore.ieee.org/document/8215485)
  - [[Python Reference]](https://github.com/FatemehSheikholeslami/EgoTen)
  
- **Fast Detection of Overlapping Communities via Online Tensor Methods on GPUs (ArXiV 2013)**
  - Furong Huang and Animashree Anandkumar
  - [[Paper]](https://www.semanticscholar.org/paper/Fast-Detection-of-Overlapping-Communities-via-on-Huang-Niranjan/356e6c7eacca6caa94a5a96f41a9c785064f5693)
  - [[C++ Reference]](https://github.com/mapleyustat/Fast-Detection-of-Overlapping-Communities-via-Online-Tensor-Methods)

## Spectral Methods

- **Scalable Spectral Clustering Using Random Binning Features (KDD 2018)**
  - Lingfei Wu, Pin-Yu Chen, Ian En-Hsu Yen, Fangli Xu, Yinglong Xia, and Charu Aggarwal 
  - [[Paper]](https://arxiv.org/abs/1805.11048)
  - [[Matlab Reference]](https://github.com/IBM/SpectralClustering_RandomBinning)

- **Community Detection and Stochastic Block Models: Recent Developments (JMLR 2018)**
  - Emmanuel Abbe
  - [[Paper]](https://arxiv.org/pdf/1703.10146v1.pdf)
  - [[Python Reference]](https://github.com/yashpatel5400/anonychain)

- **Understanding Regularized Spectral Clustering via Graph Conductance (NIPS 2018)**
  - Yilin Zhang and Karl Rohe
  - [[Paper]](https://arxiv.org/abs/1806.01468)
  - [[Python Reference]](https://github.com/crisbodnar/regularised-spectral-clustering)

- **Locally-Biased Spectral Approximation for Community Detection (Knowledge-Based Systems 2018)**
  - Pan Shi, Kun He, David Bindel, and John Hopcroft
  - [[Paper]](https://pdfs.semanticscholar.org/d9e2/598b261a61c69d970e1c9eab7a50da4e458c.pdf)
  - [[Matlab Reference]](https://github.com/PanShi2016/LBSA)
  
- **Community Detection on Euclidean Random Graphs (Electronic Journal of Statistics 2018)**
  - Abishek Sankararaman and Francois Baccelli
  - [[Paper]](http://abishek90.github.io/CommDet.pdf)
  - [[Python Reference]](https://github.com/abishek90/Community-Detection-on-a-Spatial-Graph)

- **Community Detection by L0-Penalized Graph Laplacian (Electronic Journal of Statistics 2018)**
  - Chong Chen, Ruibin Xi, and Nan Lin
  - [[Paper]](https://projecteuclid.org/euclid.ejs/1528769122)
  - [[Matlab Reference]](https://github.com/ChongC1990/L0Lap)
  
- **Phase Transitions and a Model Order Selection Criterion for Spectral Graph Clustering (IEEE TSP 2018)**
  - Pin-Yu Chen and Alfred O. Hero
  - [[Paper]](https://arxiv.org/abs/1604.03159)
  - [[Python Reference]](https://github.com/tgensol/AMOS)
  
- **An Algorithm J-SC of Detecting Communities in Complex Networks (Physics Letters A 2017)**
  - Fang Hu, Mingzhu Wang, Yanran Wang, Zhehao Hong, and Yanhui Zhu
  - [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0375960117308678)
  - [[Matlab reference]](https://github.com/yanhueiju/community_detection_J-SC)

- **Local Lanczos Spectral Approximation for Community Detection (ECML PKDD 2017)**
  - Pan Shi, He Kun, David Bindel, and John Hopcroft
  - [[Paper]](http://ecmlpkdd2017.ijs.si/papers/paperID161.pdf)
  - [[Python Reference]](https://github.com/PanShi2016/LLSA)
  
- **AMOS: An Automated Model Order Selection Algorithm for Spectral Graph Clustering (ICASSP 2017)**
  - Pin-Yu Chen, Thibaut Gensollen, and Alfred O. Hero III 
  - [[Paper]](https://arxiv.org/abs/1609.06457)
  - [[Python Reference]](https://github.com/tgensol/AMOS)
  
- **Clustering Signed Networks with the Geometric Mean of Laplacians (NIPS 2016)**
  - Pedro Mercado, Francesco Tudisco, and Matthias Hein
  - [[Paper]](http://papers.nips.cc/paper/6164-clustering-signed-networks-with-the-geometric-mean-of-laplacians.pdf)
  - [[Matlab Reference]](https://github.com/melopeo/GM)

- **Spectral Clustering with Graph Filtering and Landmark Based Representation (ICASSP 2016)**
  - Nicolas Tremblay, Gilles Puy, Pierre Borgnat, Rémi Gribonval, and Pierre Vandergheynst
  - [[Paper]](https://arxiv.org/pdf/1509.08863.pdf)
  - [[Python Reference]](https://github.com/cylindricalcow/FastSpectralClustering)

- **Uncovering the Small Community Structure in Large Networks: a Local Spectral Approach (WWW 2015)**
  - Li Yixuan, He Kun, David Bindel, and John Hopcroft
  - [[Paper]](https://arxiv.org/abs/1509.07715)
  - [[Python Reference]](https://github.com/YixuanLi/LEMON)
  
- **Large-Scale Multi-View Spectral Clustering via Bipartite Graph (AAAI 2015)**
  - Yeqing Li, Feiping Nie, Heng Huang, and Junzhou Huang
  - [[Paper]](https://pdfs.semanticscholar.org/9383/f08c697b8aa43782e16c9a57e089911584d8.pdf)
  - [[Matlab Reference]](https://github.com/zzz123xyz/MVSC)
  
- **Self-Taught Spectral Clustering via Constraint Augmentation (SDM 2014)**
  - Xiang Wang, Jun Wang, Buyue Qian, Fei Wang and Ian Davidson
  - [[Paper]](https://epubs.siam.org/doi/pdf/10.1137/1.9781611973440.48)
  - [[Matlab Reference]](https://github.com/gnaixgnaw/CSP)
  
- **Multi-Objective Multi-View Spectral Clustering via Pareto Optimization (SDM 2013)**
  - Xiang Wang, Buyue Qian, Jieping Ye, and Ian Davidson
  - [[Paper]](http://www2.cs.uh.edu/~ceick/DM/P4_DM4.pdf)
  - [[Matlab Reference]](https://github.com/gnaixgnaw/CSP)
  
- **Co-Clustering for Directed Graphs: the Stochastic Co-Blockmodel and Spectral Algorithm Di-Sim (ArXiv 2012)**
  - Karl Rohe, Tai Qin, and Bin Yu
  - [[Paper]](https://arxiv.org/abs/1204.2296)
  - [[R Reference]](https://github.com/karlrohe/disim)
  
- **Asymptotic Analysis of the Stochastic Block Model for Modular Networks and its Algorithmic Applications (Physical Review 2011)**
  - Aurelien Decelle, Florent Krzakala, Cristopher Moore, and Lenka Zdeborova
  - [[Paper]](https://arxiv.org/abs/1109.3041)
  - [[C++ Reference]](https://github.com/junipertcy/sbm-bp)
  
- **Phase Transition in the Detection of Modules in Sparse Networks (Physical Review Letters 2011)**
  - Aurelien Decelle, Florent Krzakala, Cristopher Moore, and Lenka Zdeborova
  - [[Paper]](https://arxiv.org/abs/1102.1182)
  - [[C++ Reference]](https://github.com/junipertcy/sbm-bp)
  
- **Active Spectral Clustering (ICDM 2010)**
  - Xiang Wang and Ian Davidson
  - [[Paper]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.299.7661&rep=rep1&type=pdf)
  - [[Matlab Reference]](https://github.com/gnaixgnaw/CSP)

- **Flexible Constrained Spectral Clustering (KDD 2010)**
  - Xiang Wang and Ian Davidson
  - [[Paper]](http://web.cs.ucdavis.edu/~davidson/Publications/rp058d-wang.pdf)
  - [[Matlab Reference]](https://github.com/gnaixgnaw/CSP)
  
- **Spectral Clustering Based on the Graph p-Laplacian (ICML 2009)**
  - Thomas Buhler and  Matthias Hein 
  - [[Paper]](https://www.ml.uni-saarland.de/Publications/BueHei-pSpectralClustering2009.pdf)
  - [[Matlab Reference]](https://github.com/tbuehler/pSpectralClustering)
  
- **Community structure in directed networks (Physical Review Letters 2008)**
  - Elizabeth A. Leicht and Mark E. J. Newman 
  - [[Paper]](https://arxiv.org/abs/0709.4500v1)
  - [[Python Reference]](https://zhiyzuo.github.io/python-modularity-maximization/)

## Temporal Methods

- **Temporally Evolving Community Detection and Prediction in Content-Centric Networks (ECML 2018)**
  - Ana Paula Appel, Renato L. F. Cunha, Charu C. Aggarwal, and Marcela Megumi Terakado 
  - [[Paper]](https://arxiv.org/pdf/1807.06560v1.pdf)
  - [[Python Reference]](https://github.com/renatolfc/chimera-stf)

- **Model-Based Clustering of Time-Evolving Networks through Temporal Exponential-Family Random Graph Models (Arxiv 2017)**
  - Kevin H. Lee, Lingzhou Xue, and David R. Hunter
  - [[Paper]](https://arxiv.org/abs/1712.07325)
  - [[R Reference]](https://github.com/amalag-19/dynERGM_R)
  
- **A Streaming Algorithm for Graph Clustering (Arxiv 2017)**
  - Alexandre Hollocou, Julien Maudet, Thomas Bonald and Marc Lelarge
  - [[Paper]](https://arxiv.org/pdf/1712.04337v1.pdf)
  - [[C++ Reference]](https://github.com/ahollocou/graph-streaming)
  
- **Sequential Detection of Temporal Communities by Estrangement Confinement (Scientific Reports 2012)**
  - Vikas Kawadia and Sameet Sreenivasan
  - [[Paper]](https://www.nature.com/articles/srep00794)
  - [[Python Reference]](https://github.com/kawadia/estrangement)
  
- **GraphScope: Parameter-Free Mining of Large Time-Evolving Graphs (KDD 2007)**
  - Jimeng Sun, Christos Faloutsos, Spiros Papadimitriou, and Philip S. Yu
  - [[Paper]](https://dl.acm.org/citation.cfm?id=1281266)
  - [[Java Reference]](https://github.com/sarovios/social-graph-cluster)
  
## Cyclic Patterns

- **ComSim: A Bipartite Community Detection Algorithm Using Cycle and Node's Similarity (International Workshop on Complex Networks 2018)**
  - Tackx Raphaël, Fabien Tarissan, and Jean-Loup Guillaume
  - [[Paper]](https://www.researchgate.net/publication/321317139_ComSim_A_Bipartite_Community_Detection_Algorithm_Using_Cycle_and_Node%27s_Similarity)
  - [[Python Reference]](https://github.com/rtackx/ComSim)

- **Adaptive Modularity Maximization via Edge Weighting Scheme (Information Sciences 2018)**
  - Xiaoyan Lu, Konstantin Kuzmin, Mingming Chen, and Boleslaw K Szymanski
  - [[Paper]](https://link.springer.com/chapter/10.1007/978-3-319-72150-7_23)
  - [[Python Reference]](https://github.com/xil12008/adaptive_modularity)
  
- **Semi-Supervised Community Detection Using Structure and Size (ICDM 2018)**
  - Arjun Bakshi, Srinivasan Parthasarathy, and Kannan Srinivasan
  - [[Paper]](!!Missing!!)
  - [[Python Reference]](https://github.com/abaxi/bespoke-icdm18)
  
- **Graph sketching-based Space-efficient Data Clustering (SDM 2018)**
  - Anne Morvan, Krzysztof Choromanski, Cédric Gouy-Pailler, Jamal Atif
  - [[Paper]](https://epubs.siam.org/doi/pdf/10.1137/1.9781611975321.2)
  - [[Python Reference]](https://github.com/annemorvan/DBMSTClu)
  
- **Hierarchical Graph Clustering using Node Pair Sampling (Arxiv 2018)**
  - Thomas Bonald, Bertrand Charpentier, Alexis Galland and Alexandre Hollocou
  - [[Paper]](https://arxiv.org/pdf/1806.01664v2.pdf)
  - [[Python Reference]](https://github.com/tbonald/paris)
  
- **Priority Based Clustering in Weighted Graph Streams (JISE 2018)**
  - Mohsen Saadatpour, Sayyed Kamyar Izadi, Mohammad Nasirifar, and Hamed Kavoosi
  - [[Paper]](https://www.researchgate.net/publication/326622737_Priority-based_clustering_in_weighted_graph_streams)
  - [[Java Reference]](https://github.com/farnasirim/pri-bas-clu)
  
- **Graph Learning for Multiview Clustering (IEEE Transactions on Cybernetics 2017)**
  - Anne Morvan, Krzysztof Choromanski, Cédric Gouy-Pailler, and Jamal Atif
  - [[Paper]](https://link.springer.com/chapter/10.1007/978-3-319-72150-7_23)
  - [[Matlab Reference]](https://github.com/kunzhan/MVGL)
  
- **DCEIL: Distributed Community Detection with the CEIL Score (IEEE HPCC 2017)**
  - Akash Jain, Rupesh Nasre, Balaraman Ravindran 
  - [[Paper]](https://ieeexplore.ieee.org/document/8291922)
  - [[Java Reference]](https://github.com/RBC-DSAI-IITM/DCEIL)
  
- **A Community Detection Algorithm Using Network Topologies and Rule-Based Hierarchical Arc-Merging Strategies (PLOS One 2017)**
  - Yu-Hsiang Fu, Chung-Yuan Huang, and Chuen-Tsai Sun 
  - [[Paper]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0187603)
  - [[Python Reference]](https://github.com/yuhsiangfu/Hierarchical-Arc-Merging)
  
- **Local Higher-Order Graph Clustering (KDD 2017)**
  - Hao Yin, Austin Benson, Jure Leskovec, and David Gleich 
  - [[Paper]](https://cs.stanford.edu/~jure/pubs/mappr-kdd17.pdf)
  - [[Python Reference]](https://github.com/thecamelrider/MAPPR-Community-detection)
  - [[C++ SNAP Reference]](http://snap.stanford.edu/mappr/code.html)
  
- **ComSim: A Bipartite Community Detection Algorithm Using Cycle and Node’s Similarity (Complex Networks 2017)**
  - Raphael Tack, Fabien Tarissan, and Jean-Loup Guillaume
  - [[Paper]](https://arxiv.org/pdf/1705.04863.pdf)
  - [[C++ Reference]](https://github.com/rtackx/ComSim)
  
- **Evolutionary Graph Clustering for Protein Complex Identification (IEEE Transactions on Computational Biology and Bioinformatics  2016)**
  - Tiantian He and Keith C.C. Chan 
  - [[Paper]](https://ieeexplore.ieee.org/document/7792218)
  - [[Java Reference]](https://github.com/he-tiantian/EGCPI)
  
- **pSCAN: Fast and Exact Structural Graph Clustering (ICDE 2016)**
  - T Lijun Chang, Wei Li, Xuemin Lin, Lu Qin, and Wenjie Zhang 
  - [[Paper]](https://ieeexplore.ieee.org/document/7498245)
  - [[C++ Reference]](https://github.com/LijunChang/pSCAN)
  
- **Node-Centric Detection of OverlappingCommunities in Social Networks (IWSCN 2016)**
  - Yehonatan Cohen, Danny Hendler, Amir Rubin
  - [[Paper]](https://arxiv.org/pdf/1607.01683.pdf)
  - [[Java Reference]](https://github.com/amirubin87/NECTAR)
  
- **Intra-Graph Clustering Using Collaborative Similarity Measure (DPCD 2015)**
  - Waqas Nawaz, Kifayat-Ullah Khan, Young-Koo Lee, and Sungyoung Lee
  - [[Paper]](https://link.springer.com/article/10.1007/s10619-014-7170-x)
  - [[Java Reference]](https://github.com/WNawaz/CSM)
  
- **High Quality, Scalable and Parallel Community Detection for Large Real Graphs (WWW 2014)**
  - Arnau Prat-Perez David Dominguez-Sal and Josep-Lluis Larriba-Pey
  - [[Paper]](http://wwwconference.org/proceedings/www2014/proceedings/p225.pdf)
  - [[C++ Reference]](https://github.com/Het-SCD/Het-SCD)
  
- **GMAC: A Seed-Insensitive Approach to Local Community Detection (DaWak 2013)**
  - Lianhang Ma, Hao Huang, Qinming He, Kevin Chiew, Jianan Wu, and Yanzhe Che
  - [[Paper]](https://link.springer.com/chapter/10.1007/978-3-642-40131-2_26)
  - [[Python Reference]](https://github.com/SnehaManjunatha/Local-Community-Detection)
  
- **Community Detection in Networks with Node Attributes (ICDM 2013)**
  - Jaewon Yang, Julian McAuley, and Jure Leskovec
  - [[Paper]](https://www-cs.stanford.edu/~jure/pubs/cesna-icdm13.pdf)
  - [[C++ Reference]](https://github.com/snap-stanford/snap/tree/master/examples/cesna)
  
- **Detecting the Structure of Social Networks Using (α,β)-Communities (IWAMW 2011)**
  - Jing He, John Hopcroft, Liang Hongyu, Supasorn Suwajanakorn, and Liaoruo Wang
  - [[Paper]](https://ecommons.cornell.edu/bitstream/handle/1813/22415/WAW2011.pdf?sequence=2&isAllowed=y)
  - [[Python Reference]](https://github.com/handasontam/Alpha-Beta-Communities)
  
## Centrality and Cuts

- **Parallelizing Pruning-based Graph Structural Clustering (ICPP 2018)**
  - Yulin Che, Shixuan Sun, and Qiong Luo
  - [[Paper]](https://dl.acm.org/citation.cfm?doid=3225058.3225063)
  - [[C++ Reference]](https://github.com/GraphProcessor/ppSCAN)
  
- **Real-Time Community Detection in Large Social Networks on a Laptop (PLOS 2018)**
  - Benjamin Paul Chamberlain, Josh Levy-Kramer, Clive Humby, and Marc Peter Deisenroth
  - [[Paper]](https://arxiv.org/pdf/1601.03958.pdf)
  - [[Python Reference]](https://github.com/melifluos/LSH-community-detection)
  
- **A Community Detection Algorithm Using Network Topologies and Rule-based Hierarchical Arc-merging Strategies (PLOS 2018)**
  - Yu-Hsiang Fu, Chung-Yuan Huang, and Chuen-Tsai Sun
  - [[Paper]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0187603)
  - [[Python Reference]](https://github.com/yuhsiangfu/Hierarchical-Arc-Merging)
  
- **Ego-splitting Framework: from Non-Overlapping to Overlapping Clusters (KDD 2017)**
  -  Alessandro Epasto, Silvio Lattanzi, and Renato Paes Leme
  - [[Paper]](https://www.eecs.yorku.ca/course_archive/2017-18/F/6412/reading/kdd17p145.pdf)
  - [[Python Reference]](https://github.com/benedekrozemberczki/EgoSplitting)
  
- **Query-oriented Graph Clustering (PAKDD 2017)**
  -  Li-Yen Kuo, Chung-Kuang Chou, and Ming-Syan Chen
  - [[Paper]](https://link.springer.com/chapter/10.1007/978-3-319-57529-2_58)
  - [[Python Reference]](https://github.com/iankuoli/QGC)
  
- **Fast Heuristic Algorithm for Multi-scale Hierarchical Community Detection (ASONAM 2017)**
  - Eduar Castrillo, Elizabeth León, and Jonatan Gómez
  - [[Paper]](https://dl.acm.org/citation.cfm?doid=3110025.3110125)
  - [[C++ Reference]](https://github.com/eduarc/WMW)
  
- **Community Detection in Signed Networks: the Role of Negative Ties in Different Scales (Scientific Reports 2015)**
  - Pouya Esmailian and Mahdi Jalili
  - [[Paper]](https://www.nature.com/articles/srep14339)
  - [[Java Reference]](https://github.com/pouyaesm/signed-community-detection)  
  
- **Detecting Community Structures in Social Networks by Graph Sparsification (CODS 2016)**
  - Partha Basuchowdhuri, Satyaki Sikdar, Sonu Shreshtha, and Subhasis Majumder
  - [[Paper]](http://dl.acm.org/citation.cfm?id=2888479)
  - [[Python Reference]](https://github.com/satyakisikdar/spanner-comm-detection)
  
- **Community Detection in Complex Networks Using Density-Based Clustering Algorithm and Manifold Learning (Physica A 2016)**
  - Tao Youa, Hui-Min Chenga, Yi-Zi Ninga, Ben-Chang Shiab, and Zhong-Yuan Zhang
  - [[Paper]](https://www.sciencedirect.com/science/article/pii/S0378437116304563)
  - [[Matlab Reference]](https://github.com/isaac-you/IsoFpd)
  
- **Smart Partitioning of Geo-Distributed Resources to Improve Cloud Network Performance (CloudNet 2015)**
  - Hooman Peiro Sajjad, Fatemeh Rahimian, and Vladimir Vlassov 
  - [[Paper]](https://ieeexplore.ieee.org/document/7335292)
  - [[Java Reference]](https://github.com/shps/mdc-community-detection)
  
- **Generalized Modularity for Community Detection (ECML 2015)**
  - Mohadeseh Ganji, Abbas Seifi, Hosein Alizadeh, James Bailey, and Peter J. Stuckey
  - [[Paper]](https://people.eng.unimelb.edu.au/mganji/papers/ECML15.pdf)
  - [[Python Reference]](https://github.com/xiaoylu/ResolutionCommunityDetection)
  
- **Online Community Detection for Large Complex Networks (IJCAI 2013)**
  - Wangsheng Zhang, Gang Pan, Zhaohui Wu and Shijian Li
  - [[Paper]](https://www.ijcai.org/Proceedings/13/Papers/281.pdf)
  - [[C++ Reference]](https://github.com/isaac-you/IsoFpd)
  
- **Agglomerative Clustering via Maximum Incremental Path Integral (Pattern Recognition 2013)**
  - Wei Zhang, Deli Zhao, and Xiaogang Wang
  - [[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320313001830)
  - [[Matlab Reference]](https://github.com/waynezhanghk/gactoolbox)
  
- **Graph Degree Linkage: Agglomerative Clustering on a Directed Graph (ECCV 2012)**
  - Wei Zhang, Xiaogang Wang, Deli Zhao and Xiaoou Tang
  - [[Paper]](https://arxiv.org/abs/1208.5092)
  - [[Matlab Reference]](https://github.com/waynezhanghk/gactoolbox)
  - [[Python Reference]](https://github.com/myungjoon/GDL)
  
- **Weighted Graph Cuts without Eigenvectors a Multilevel Approach (IEEE TPAMI 2007)**
  - Inderjit S Dhillon, Brian Kulis, and Yuqiang Guan 
  - [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4302760)
  - [[C Reference]](https://github.com/iromu/Graclus)
  
## Physics Inspired

- **Community Detection Using Preference Networks (Physica A 2018)**
  - Mursel Tasgin and Halu Bingol
  - [[Paper]](https://arxiv.org/pdf/1708.08305.pdf)
  - [[Java Reference]](https://github.com/murselTasginBoun/CDPN)
  
- **Thermodynamics of the Minimum Description Length on Community Detection (ArXiv 2018)**
  - Juan Ignacio Perotti, Claudio Juan Tessone, Aaron Clauset and Guido Caldarelli
  - [[Paper]](https://arxiv.org/pdf/1806.07005.pdf)
  - [[Python Reference]](https://github.com/jipphysics/bmdl_edm)

- **Fluid Communities: A Community Detection Algorithm (Complenet 2017)**
  - Ferran Parés, Dario Garcia-Gasulla, Armand Vilalta, Jonatan Moreno, Eduard Ayguadé, Jesús Labarta, Ulises Cortés and Toyotaro Suzumura
  - [[Paper]](https://arxiv.org/abs/1703.09307)
  - [[Python Reference]](https://github.com/HPAI-BSC/Fluid-Communities)
  
- **A Local Perspective on Community Structure in Multilayer Networks (Network Science 2017)**
  - Lucas GS Jeub, Michael Mahoney, Peter J Mucha and Mason A Porter
  - [[Paper]](https://arxiv.org/pdf/1510.05185.pdf)
  - [[Python Reference]](https://github.com/LJeub/LocalCommunities)
  
- **Defining Least Community as a Homogeneous Group in Complex Networks (Physica A 2015)**
  - Renaud Lambiotte, J-C Delvenne, and Mauricio Barahona
  - [[Paper]](https://arxiv.org/pdf/1502.00284.pdf)
  - [[Python Reference]](https://github.com/dingmartin/HeadTailCommunityDetection)
  
- **Think Locally, Act Locally: Detection of Small, Medium-Sized, and Large Communities in Large Networks (Physica Review E 2015)**
  - Lucas G. S. Jeub, Prakash Balachandran, Mason A. Porter, Peter J. Mucha, and Michael W. Mahoney
  - [[Paper]](https://arxiv.org/abs/1403.3795v1)
  - [[Python Reference]](https://github.com/LJeub/LocalCommunities)
  
- **Parallel Community Detection on Large Networks with Propinquity Dynamics (KDD 2009)**
  - Yuzhou Zhang, Jianyong Wang, Yi Wang, and Lizhu Zhou 
  - [[Paper]](https://grid.cs.gsu.edu/~myan2/communitydetection/16.pdf)
  - [[Java Reference]](https://github.com/csdashes/GraphStreamCommunityDetection)
    
- **Laplacian Dynamics and Multiscale Modular Structure in Networks (IEEE TNSE 2008)**
  - Renaud Lambiotte, J-C Delvenne, and Mauricio Barahona
  - [[Paper]](https://arxiv.org/abs/0812.1770v3)
  - [[R Reference]](https://github.com/buzzlumberjack/Communities-Detection)
  
- **Statistical Mechanics of Community Detection (Phyics Review E 2006)**
  - Jorh Reichardt and Stefan Bornholdt
  - [[Paper]](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.74.016110)
  - [[Ruby Reference]](https://github.com/duett/community-detection)
  
## Others
  
- **Discovering Fuzzy Structural Patterns for Graph Analytics (IEEE TFS 2018)**
  - Tiantian He  and Keith C. C. Chan 
  - [[Paper]](https://ieeexplore.ieee.org/document/8253904)
  - [[Executable Reference]](https://github.com/he-tiantian/FSPGA)
  
- **Watset: Automatic Induction of Synsets for a Graph of Synonyms (ACL 2017)**
  - Dmitry Ustalov, Alexander Panchenko, and Chris Biemann
  - [[Paper]](https://doi.org/10.18653/v1/P17-1145)
  - [[Python Reference]](https://github.com/dustalov/watset)
  - [[Java Reference]](https://github.com/nlpub/watset-java)
  
- **An Overlapping Community Detection Algorithm Based on Density Peaks (NeuroComputing 2017)**
  - Xueying Bai, Peilin Yang, and Xiaohu Shi
  - [[Paper]](https://www.sciencedirect.com/science/article/pii/S092523121631400X)
  - [[Matlab Reference]](https://github.com/XueyingBai/An-overlapping-community-detection-algorithm-based-on-density-peaks)
  
- **Fast Heuristic Algorithm for Multi-scale Hierarchical Community Detection (ASONAM 2017)**
  - Eduar Castrillo, Elizabeth León, and Jonatan Gómez
  - [[Paper]](https://arxiv.org/abs/1707.02362)
  - [[C++ Reference]](https://github.com/eduarc/HAMUHI)
  
- **Time Series Clustering via Community Detection in Networks (Information Sciences 2016)**
  - Leonardo N. Ferreira and Liang Zhao
  - [[Paper]](https://www.sciencedirect.com/science/article/pii/S002002551500554X)
  - [[R Reference]](https://github.com/lnferreira/time_series_clustering_via_community_detection)

- **General Optimization Technique for High-quality Community Detection in Complex Networks (Physical Review E 2014)**
  - Stanislav Sobolevsky, Riccardo Campari, Alexander Belyi, and Carlo Ratti
  - [[Paper]](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.90.012811)
  - [[Python Reference]](https://github.com/Casyfill/pyCombo)
  
- **Community Detection in Multi-Partite Multi-Relational Networks Based on Information Compression (New Generation Computing 2016)**
  - Xin Liu, Weichu Liu, Tsuyoshi Murata, and Ken Wakita
  - [[Paper]](https://link.springer.com/article/10.1007/s00354-016-0206-1)
  - [[Scala Reference]](https://github.com/weichuliu/hetero_scala)
  
- **Integration of Graph Clustering with Ant Colony Optimization for Feature Selection (Knowledge-Based Systems 2015)**
  - Parham Moradi, Mehrdad Rostami
  - [[Paper]](http://www.sciencedirect.com/science/article/pii/S0950705115001458)
  - [[Matlab Reference]](https://github.com/XuesenYang/Graph-clustering-with-ant-colony-optimization-for-feature-selection)  
  
- **Community Detection via Maximization of Modularity and Its Variants (IEEE TCSS 2014)**
  - Mingming Chen, Konstantin Kuzmin, and Boleslaw K. Szymanski 
  - [[Paper]](https://www.cs.rpi.edu/~szymansk/papers/TCSS-14.pdf)
  - [[Python Reference]](https://github.com/itaneja2/community-detection)

- **A Smart Local Moving Algorithm for Large-Scale Modularity-Based Community Detection (The European Physical Journal B 2013)**
  - Ludo Waltman and Nees Jan Van Eck
  - [[Paper]](https://link.springer.com/content/pdf/10.1140/epjb/e2013-40829-0.pdf)
  - [[R Reference]](https://github.com/chen198328/slm)
  
- **Bayesian Hierarchical Community Discovery (NIPS 2013)**
  - Charles Blundell and Yee Whye Teh
  - [[Paper]](http://papers.nips.cc/paper/5048-bayesian-hierarchical-community-discovery.pdf)
  - [[Python Reference]](https://github.com/krzychu/bhcd/)
  - [[C++ Reference]](https://github.com/blundellc/bhcd/)
  
- **A Game-Theoretic Approach to Hypergraph Clustering (NIPS 2009)**
  - Samuel R. Bulò and Marcello Pelillo
  - [[Paper]](https://papers.nips.cc/paper/3714-a-game-theoretic-approach-to-hypergraph-clustering)
  - [[Matlab Reference]](https://github.com/Schofield-Mao/Gametheory-Clustring)
