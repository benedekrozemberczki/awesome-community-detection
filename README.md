# Awesome Community Detection Research Papers
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
 ![GitHub stars](https://img.shields.io/github/stars/benedekrozemberczki/awesome-community-detection.svg?style=plastic) ![GitHub forks](https://img.shields.io/github/forks/benedekrozemberczki/awesome-community-detection.svg?color=blue&style=plastic) ![License](https://img.shields.io/github/license/benedekrozemberczki/awesome-community-detection.svg?color=blue&style=plastic)


A collection of community detection papers with implementations.

Similar collections about [graph classification](https://github.com/benedekrozemberczki/awesome-graph-classification), [classification/regression tree](https://github.com/benedekrozemberczki/awesome-decision-tree-papers), [fraud detection](https://github.com/benedekrozemberczki/awesome-fraud-detection-papers), and [gradient boosting](https://github.com/benedekrozemberczki/awesome-gradient-boosting-papers) papers with implementations.

<p align="center">
  <img width="460" src="coms.png">
</p>

##### Table of Contents  

1. [Matrix Factorization](https://github.com/benedekrozemberczki/awesome-community-detection/blob/master/factorization.md)  
2. [Deep Learning](https://github.com/benedekrozemberczki/awesome-community-detection/blob/master/deep_learning.md) 
3. [Label Propagation, Percolation and Random Walks](https://github.com/benedekrozemberczki/awesome-community-detection/blob/master/label_propagation.md) 
4. [Tensor Decomposition](https://github.com/benedekrozemberczki/awesome-community-detection/blob/master/tensor_decomposition.md)
5. [Spectral Methods](https://github.com/benedekrozemberczki/awesome-community-detection/blob/master/spectral.md) 
6. [Temporal Methods](https://github.com/benedekrozemberczki/awesome-community-detection/blob/master/temporal.md) 
7. [Cyclic Patterns](https://github.com/benedekrozemberczki/awesome-community-detection/blob/master/cyclic.md)
8. [Centrality and Cuts](https://github.com/benedekrozemberczki/awesome-community-detection/blob/master/centrality.md) 
9. [Physics Inspired](https://github.com/benedekrozemberczki/awesome-community-detection/blob/master/physics.md) 
10. [Others](https://github.com/benedekrozemberczki/awesome-community-detection/blob/master/others.md) 
11. [Libraries](https://github.com/benedekrozemberczki/awesome-community-detection/blob/master/libraries.md)

## Centrality and Cuts

- **A Novel Graph-based Clustering Method Using Noise Cutting (Information Systems 2020)**
  - Lin-Tao Li, Zhong-Yang Xiong, Qi-Zhu Dai, Yong-Fang Zha. Yu-Fang Zhang, Jing-Pei Dan
  - [[Paper]](https://www.sciencedirect.com/science/article/pii/S0306437920300156)
  - [[Matlab Reference]](https://github.com/lintao6/CutPC)

- **Hypergraph Clustering with Categorical Edge Labels (Arxiv 2019)**
  - Ilya Amburg, Nate Veldt, Austin R. Benson
  - [[Paper]](https://arxiv.org/pdf/1910.09943.pdf)
  - [[Julia Reference]](https://github.com/nveldt/CategoricalEdgeClustering)

- **Learning Resolution Parameters for Graph Clustering (WWW 2019)**
  - Nate Veldt, David F. Gleich, Anthony Wirth
  - [[Paper]](https://arxiv.org/abs/1903.05246)
  - [[Julia Reference]](https://github.com/nveldt/LearnResParams)

- **Parallelizing Pruning-based Graph Structural Clustering (ICPP 2018)**
  - Yulin Che, Shixuan Sun, and Qiong Luo
  - [[Paper]](https://dl.acm.org/citation.cfm?doid=3225058.3225063)
  - [[C++ Reference]](https://github.com/GraphProcessor/ppSCAN)
  
- **Real-Time Community Detection in Large Social Networks on a Laptop (PLOS 2018)**
  - Benjamin Paul Chamberlain, Josh Levy-Kramer, Clive Humby, and Marc Peter Deisenroth
  - [[Paper]](https://arxiv.org/pdf/1601.03958.pdf)
  - [[Python Reference]](https://github.com/melifluos/LSH-community-detection)
  
- **A Polynomial Algorithm for Balanced Clustering via Graph Partitioning (EJOR 2018)**
  - Luis-Evaristo Caraballo, José-Miguel Díaz-Báñez, Nadine Kroher
  - [[Paper]](https://arxiv.org/abs/1801.03347)
  - [[Python Reference]](https://github.com/varocaraballo/graph_partition_clustering)
  
- **A Community Detection Algorithm Using Network Topologies and Rule-based Hierarchical Arc-merging Strategies (PLOS 2018)**
  - Yu-Hsiang Fu, Chung-Yuan Huang, and Chuen-Tsai Sun
  - [[Paper]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0187603)
  - [[Python Reference]](https://github.com/yuhsiangfu/Hierarchical-Arc-Merging)
  
- **Hidden Community Detection in Social Networks (Information Sciences 2018)**
  - Kun He, Yingru Li, Sucheta Soundarajan, John E. Hopcroft
  - [[Paper]](https://arxiv.org/pdf/1702.07462v1.pdf)
  - [[Python Reference]](https://github.com/JHL-HUST/HiCode)
  
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
  
- **General Optimization Technique for High-quality Community Detection in Complex Networks (Physical Review E 2014)**
  - Stanislav Sobolevsky, Riccardo Campari, Alexander Belyi, and Carlo Ratti
  - [[Paper]](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.90.012811)
  - [[Python Reference]](https://github.com/Casyfill/pyCombo)
  
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

- **Fluid Communities: A Community Detection Algorithm (CompleNet 2017)**
  - Ferran Parés, Dario Garcia-Gasulla, Armand Vilalta, Jonatan Moreno, Eduard Ayguadé, Jesús Labarta, Ulises Cortés and Toyotaro Suzumura
  - [[Paper]](https://arxiv.org/abs/1703.09307)
  - [[Python Reference]](https://github.com/HPAI-BSC/Fluid-Communities)
  
- **A Local Perspective on Community Structure in Multilayer Networks (Network Science 2017)**
  - Lucas GS Jeub, Michael Mahoney, Peter J Mucha and Mason A Porter
  - [[Paper]](https://arxiv.org/pdf/1510.05185.pdf)
  - [[Python Reference]](https://github.com/LJeub/LocalCommunities)
  
- **BlackHole: Robust Community Detection Inspired by Graph Drawing (ICDE 2016)**
  -  Sungsu Lim, Junghoon Kim, and Jae-Gil Lee 
  - [[Paper]](https://ieeexplore.ieee.org/document/7498226)
  - [[C++ Reference]](https://github.com/thousfeet/Blackhole-Community-detection)
  
- **Defining Least Community as a Homogeneous Group in Complex Networks (Physica A 2015)**
  - Renaud Lambiotte, J-C Delvenne, and Mauricio Barahona
  - [[Paper]](https://arxiv.org/pdf/1502.00284.pdf)
  - [[Python Reference]](https://github.com/dingmartin/HeadTailCommunityDetection)
  
- **Community Detection Based on Distance Dynamics (KDD 2015)**
  - Shao Junming, Han Zhichao, Yang Qinli, and Zhou Tao
  - [[Paper]](https://dl.acm.org/citation.cfm?id=2783301)
  - [[Python Reference]](https://github.com/chocolates/Community-detection-based-on-distance-dynamics)
  
- **Think Locally, Act Locally: Detection of Small, Medium-Sized, and Large Communities in Large Networks (Physica Review E 2015)**
  - Lucas G. S. Jeub, Prakash Balachandran, Mason A. Porter, Peter J. Mucha, and Michael W. Mahoney
  - [[Paper]](https://arxiv.org/abs/1403.3795v1)
  - [[Python Reference]](https://github.com/LJeub/LocalCommunities)
  
- **Detecting Community Structure Using Label Propagation with Weighted Coherent Neighborhood Propinquity (Physica A 2013)**
  - Hao Lou, Shenghong Li, and Yuxin Zhao
  - [[Paper]](https://www.sciencedirect.com/science/article/pii/S0378437113002173)
  - [[Java Reference]](https://github.com/mahdiabdollahpour/Detecting-Community-Structure/tree/master/src)
  
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

- **A Novel Density-based Clustering Algorithm Using Nearest Neighbor Graph (Pattern Recognition 2020)**
  - Hao Li, Xiaojie Liu, Tao Li, and Rundong Gan
  - [[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S0031320320300121?via%3Dihub)
  - [[Python Reference]](https://github.com/tommylee3003/SDBSCAN)
  
- **Ensemble Clustering for Graphs: Comparisons and Applications (Applied Network Science 2019)**
  - Valérie Poulin and François Théberge
  - [[Paper]](https://arxiv.org/abs/1809.05578)
  - [[Python Reference]](https://github.com/ftheberge/Ensemble-Clustering-for-Graphs)

- **CutESC: Cutting Edge Spatial Clustering Technique based on Proximity Graphs (Knowledge-Based Systems 2019)**
  - Alper Aksac, Tansel Özyer, Reda Alhajja
  - [[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320319302468)
  - [[Python Reference]](https://github.com/alperaksac/cutESC)

- **A Study of Graph-based System for Multi-view Clustering (Knowledge-Based Systems 2019)**
  - Hao Wang, Yan Yang, BingLiu, Hamido Fujita
  - [[Paper]](https://www.sciencedirect.com/science/article/pii/S0950705118305082)
  - [[Python Reference]](https://github.com/cswanghao/gbs)

- **Learning Resolution Parameters for Graph Clustering (WWW 2019)**
  - Nate Veldt, David Gleich, Anthony Wirth
  - [[Paper]](https://arxiv.org/abs/1903.05246)
  - [[Julia Reference]](https://github.com/nveldt/LearnResParams)

- **Multiview Consensus Graph Clustering (IEEE TIP 2019)**
  - Kun Zhan and Feiping Nie and Jing Wang and Yi Yang
  - [[Paper]](https://www.ncbi.nlm.nih.gov/pubmed/30346283)
  - [[Matlab Reference]](https://github.com/kunzhan/MCGC)
  
- **CutESC: Cutting Edge Spatial Clustering Technique based on Proximity Graphs (Knowledge-Based Systems 2019)**
  - Alper Aksac, Tansel Özyer, Reda Alhajja
  - [[Paper]](https://www.sciencedirect.com/science/article/pii/S0031320319302468)
  - [[Python Reference]](https://github.com/alperaksac/cutESC)
  
- **Clubmark - Bench bencmarking Framework for the Clustering Algorithms Evaluation (ICDM 2018)**
  - Artem Lutov, Mourad Khayati, Philippe Cudre-Mauroux
  - [[Paper]](https://github.com/eXascaleInfolab/clubmark/blob/master/docs/clubmark.pdf)
  - [[Python Reference]](https://github.com/eXascaleInfolab/clubmark/tree/master/algorithms)
  
- **The Difference Between Optimal and Germane Communities (Social Network Analysis and Mining 2018)**
  - Jerry Scripps, Christian TrefftzZachary Kurmas
  - [[Paper]](https://link.springer.com/article/10.1007/s13278-018-0522-1)
  - [[Java Reference]](https://cis.gvsu.edu/~scrippsj/pubs/software.htm)

- **Discovering Fuzzy Structural Patterns for Graph Analytics (IEEE TFS 2018)**
  - Tiantian He  and Keith C. C. Chan 
  - [[Paper]](https://ieeexplore.ieee.org/document/8253904)
  - [[Executable Reference]](https://github.com/he-tiantian/FSPGA)
  
- **Wiring Together Large Single-Cell RNA-Seq Sample Collections (biorxiv 2018)**
  - Nikolas Barkas, Viktor Petukhov, Daria Nikolaeva, Yaroslav Lozinsky, Samuel Demharter, Konstantin Khodosevich, Peter V. Kharchenko
  - [[Paper]](https://www.biorxiv.org/content/10.1101/460246v1)
  - [[C++]](https://github.com/hms-dbmi/conos)
  
- **Community Detection and Stochastic Block Models: Recent Developments (JMLR 2017)**
  - Emmanuel Abbe
  - [[Paper]](https://arxiv.org/pdf/1703.10146v1.pdf)
  
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

- **Community Detection in Multi-Partite Multi-Relational Networks Based on Information Compression (New Generation Computing 2016)**
  - Xin Liu, Weichu Liu, Tsuyoshi Murata, and Ken Wakita
  - [[Paper]](https://link.springer.com/article/10.1007/s00354-016-0206-1)
  - [[Scala Reference]](https://github.com/weichuliu/hetero_scala)
  
- **Integration of Graph Clustering with Ant Colony Optimization for Feature Selection (Knowledge-Based Systems 2015)**
  - Parham Moradi, Mehrdad Rostami
  - [[Paper]](http://www.sciencedirect.com/science/article/pii/S0950705115001458)
  - [[Matlab Reference]](https://github.com/XuesenYang/Graph-clustering-with-ant-colony-optimization-for-feature-selection)  

- **Greedy Discrete Particle Swarm Optimization for Large-Scale Social Network Clustering (Information Sciences 2015)**
  - Qing Cai, Maoguo Gong, Lijia Ma, Shasha Ruan, Fuyan Yuan, Licheng Jiao
  - [[Paper]](https://www.sciencedirect.com/science/article/pii/S0020025514009530)
  - [[C++ Reference]](https://github.com/doctor-cai/GDPSO)

- **Community Detection via Maximization of Modularity and Its Variants (IEEE TCSS 2014)**
  - Mingming Chen, Konstantin Kuzmin, and Boleslaw K. Szymanski 
  - [[Paper]](https://www.cs.rpi.edu/~szymansk/papers/TCSS-14.pdf)
  - [[Python Reference]](https://github.com/itaneja2/community-detection)

- **A Smart Local Moving Algorithm for Large-Scale Modularity-Based Community Detection (The European Physical Journal B 2013)**
  - Ludo Waltman and Nees Jan Van Eck
  - [[Paper]](https://link.springer.com/content/pdf/10.1140/epjb/e2013-40829-0.pdf)
  - [[R Reference]](https://github.com/chen198328/slm)
  - [[Python Reference]](https://github.com/iosonofabio/slmpy)
  
- **Bayesian Hierarchical Community Discovery (NIPS 2013)**
  - Charles Blundell and Yee Whye Teh
  - [[Paper]](http://papers.nips.cc/paper/5048-bayesian-hierarchical-community-discovery.pdf)
  - [[Python Reference]](https://github.com/krzychu/bhcd/)
  - [[C++ Reference]](https://github.com/blundellc/bhcd/)
  
- **Efficient Discovery of Overlapping Communities in Massive Networks (PNAS 2013)**
  - Prem K. Gopalan and David M. Blei
  - [[Paper]](https://www.pnas.org/content/110/36/14534)
  - [[C++ Reference]](https://github.com/premgopalan/svinet)
  
- **Complex Network Clustering by Multiobjective Discrete Particle Swarm Optimization Based on Decomposition (IEEE Trans. Evolutionary Computation 2013)**
  - Maoguo Gong, Qing Cai, Xiaowei Chen, and Lijia Ma
  - [[Paper]](https://ieeexplore.ieee.org/document/6510542?reason=concurrency)
  - [[C++ Reference]](https://github.com/doctor-cai/MODPSO)
  
- **An Efficient and Principled Method for Detecting Communities in Networks (Physical Review E 2011)**
  - Brian Ball, Brian Karrer, M. E. J. Newman
  - [[Paper]](https://arxiv.org/pdf/1104.3590.pdf)
  - [[C++ Reference]](http://www.personal.umich.edu/~mejn/OverlappingLinkCommunities.zip)
  - [[Python Reference]](https://github.com/Zabot/principled_clustering)
  
- **A Game-Theoretic Approach to Hypergraph Clustering (NIPS 2009)**
  - Samuel R. Bulò and Marcello Pelillo
  - [[Paper]](https://papers.nips.cc/paper/3714-a-game-theoretic-approach-to-hypergraph-clustering)
  - [[Matlab Reference]](https://github.com/Schofield-Mao/Gametheory-Clustring)
  
## Libraries

- **DynComm R Package - Dynamic Community Detection for Evolving Networks (Arxiv 2019)**
  - Rui Portocarrero Sarmento, Luís Lemos, Mário Cordeiro, Giulio Rossetti, and Douglas Cardoso
  - [[Paper]](https://arxiv.org/abs/1905.01498)
  - [[R Reference]](https://github.com/softskillsgroup/DynComm-R-package)
  
- **CDLIB: a python library to extract, compare and evaluate communities from complex networks (Applied Network Science, 2019)**
  - Giulio Rossetti, Letizia Milli and Rémy Cazabet 
  - [[Paper]](https://link.springer.com/article/10.1007/s41109-019-0165-9)
  - [[Python Reference]](https://github.com/GiulioRossetti/cdlib/tree/master/cdlib)
