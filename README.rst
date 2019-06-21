Literature of Deep Learning for Graphs
**************************************
This is a paper list about deep learning for graphs.

.. contents::
    :local:
    :depth: 2

.. sectnum::
    :depth: 2

.. role:: author(emphasis)

.. role:: venue(strong)

.. role:: keyword(emphasis)

Node Representation Learning
============================

Unsupervised Node Representation Learning
-----------------------------------------

`DeepWalk: Online Learning of Social Representations
<https://arxiv.org/pdf/1403.6652>`_
    | :author:`Bryan Perozzi, Rami Al-Rfou, Steven Skiena`
    | :venue:`KDD 2014`
    | :keyword:`Node classification, Random walk, Skip-gram`

`LINE: Large-scale Information Network Embedding
<https://arxiv.org/pdf/1503.03578>`_
    | :author:`Jian Tang, Meng Qu, Mingzhe Wang, Ming Zhang, Jun Yan, Qiaozhu Mei`
    | :venue:`WWW 2015`
    | :keyword:`First-order, Second-order, Node classification`

`GraRep: Learning Graph Representations with Global Structural Information
<https://dl.acm.org/citation.cfm?id=2806512>`_
    | :author:`Shaosheng Cao, Wei Lu, Qiongkai Xu`
    | :venue:`CIKM 2015`
    | :keyword:`High-order, SVD`

`node2vec: Scalable Feature Learning for Networks
<https://arxiv.org/pdf/1607.00653>`_
    | :author:`Aditya Grover, Jure Leskovec`
    | :venue:`KDD 2016`
    | :keyword:`Breadth-first Search, Depth-first Search, Node Classification, Link Prediction`

`Scalable Graph Embedding for Asymmetric Proximity
<https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14696>`_
    | :author:`Chang Zhou, Yuqiong Liu, Xiaofei Liu, Zhongyi Liu, Jun Gao`
    | :venue:`AAAI 2017`

`Fast Network Embedding Enhancement via High Order Proximity Approximation
<https://www.ijcai.org/proceedings/2017/544>`_
    | :author:`Cheng Yang, Maosong Sun, Zhiyuan Liu, Cunchao Tu`
    | :venue:`IJCAI 2017`

`struc2vec: Learning Node Representations from Structural Identity
<https://arxiv.org/pdf/1704.03165>`_
    | :author:`Leonardo F. R. Ribeiro, Pedro H. P. Savarese, Daniel R. Figueiredo`
    | :venue:`KDD 2017`
    | :keyword:`Structural Identity`

`Poincaré Embeddings for Learning Hierarchical Representations
<https://arxiv.org/pdf/1705.08039>`_
    | :author:`Maximilian Nickel, Douwe Kiela`
    | :venue:`NIPS 2017`

`VERSE: Versatile Graph Embeddings from Similarity Measures
<https://arxiv.org/pdf/1803.04742>`_
    | :author:`Anton Tsitsulin, Davide Mottin, Panagiotis Karras, Emmanuel Müller`
    | :venue:`WWW 2018`

`Network Embedding as Matrix Factorization: Unifying DeepWalk, LINE, PTE, and node2vec
<https://arxiv.org/pdf/1710.02971>`_
    | :author:`Jiezhong Qiu, Yuxiao Dong, Hao Ma, Jian Li, Kuansan Wang, Jie Tang`
    | :venue:`WSDM 2018`

`Learning Structural Node Embeddings via Diffusion Wavelets
<https://arxiv.org/pdf/1710.10321>`_
    | :author:`Claire Donnat, Marinka Zitnik, David Hallac, Jure Leskovec`
    | :venue:`KDD 2018`

`Adversarial Network Embedding
<https://arxiv.org/pdf/1711.07838>`_
    | :author:`Quanyu Dai, Qiang Li, Jian Tang, Dan Wang`
    | :venue:`AAAI 2018`

`GraphGAN: Graph Representation Learning with Generative Adversarial Nets
<https://arxiv.org/pdf/1711.08267>`_
    | :author:`Hongwei Wang, Jia Wang, Jialin Wang, Miao Zhao, Weinan Zhang, Fuzheng Zhang, Xing Xie, Minyi Guo`
    | :venue:`AAAI 2018`

`A General View for Network Embedding as Matrix Factorization
<https://dl.acm.org/citation.cfm?id=3291029>`_
    | :author:`Xin Liu, Tsuyoshi Murata, Kyoung-Sook Kim, Chatchawan Kotarasu, Chenyi Zhuang`
    | :venue:`WSDM 2019`

`Deep Graph Infomax
<https://arxiv.org/pdf/1809.10341>`_
    | :author:`Petar Veličković, William Fedus, William L. Hamilton, Pietro Liò, Yoshua Bengio, R Devon Hjelm`
    | :venue:`ICLR 2019`

`NetSMF: Large-Scale Network Embedding as Sparse Matrix Factorization
<http://keg.cs.tsinghua.edu.cn/jietang/publications/www19-Qiu-et-al-NetSMF-Large-Scale-Network-Embedding.pdf>`_
    | :author:`Jiezhong Qiu, Yuxiao Dong, Hao Ma, Jian Li, Chi Wang, Kuansan Wang, Jie Tang`
    | :venue:`WWW 2019`

`Adversarial Training Methods for Network Embedding
<https://dl.acm.org/citation.cfm?id=3313445>`_
    | :author:`Quanyu Dai, Xiao Shen, Liang Zhang, Qiang Li, Dan Wang`
    | :venue:`WWW 2019`

Node Representation Learning in Heterogeneous Graphs
----------------------------------------------------

`Learning Latent Representations of Nodes for Classifying in Heterogeneous Social Networks
<https://dl.acm.org/citation.cfm?id=2556225>`_
    | :author:`Yann Jacob, Ludovic Denoyer, Patrick Gallinari`
    | :venue:`WSDM 2014`

`PTE: Predictive Text Embedding through Large-scale Heterogeneous Text Networks
<https://arxiv.org/pdf/1508.00200>`_
    | :author:`Jian Tang, Meng Qu, Qiaozhu Mei`
    | :venue:`KDD 2015`
    | :keyword:`Text Embedding, Heterogeneous Text Graphs`

`Heterogeneous Network Embedding via Deep Architectures
<https://dl.acm.org/citation.cfm?id=2783296>`_
    | :author:`Shiyu Chang, Wei Han, Jiliang Tang, Guo-Jun Qi, Charu C. Aggarwal, Thomas S. Huang`
    | :venue:`KDD 2015`

`Network Representation Learning with Rich Text Information
<https://www.aaai.org/ocs/index.php/IJCAI/IJCAI15/paper/view/11098>`_
    | :author:`Cheng Yang, Zhiyuan Liu, Deli Zhao, Maosong Sun, Edward Chang`
    | :venue:`AAAI 2015`

`Max-Margin DeepWalk: Discriminative Learning of Network Representation
<https://www.ijcai.org/Proceedings/16/Papers/547.pdf>`_
    | :author:`Cunchao Tu, Weicheng Zhang, Zhiyuan Liu, Maosong Sun`
    | :venue:`IJCAI 2016`

`metapath2vec: Scalable Representation Learning for Heterogeneous Networks
<https://dl.acm.org/citation.cfm?id=3098036>`_
    | :author:`Yuxiao Dong, Nitesh V. Chawla, Ananthram Swami`
    | :venue:`KDD 2017`

`Meta-Path Guided Embedding for Similarity Search in Large-Scale Heterogeneous Information Networks
<https://arxiv.org/pdf/1610.09769>`_
    | :author:`Jingbo Shang, Meng Qu, Jialu Liu, Lance M. Kaplan, Jiawei Han, Jian Peng`
    | :venue:`arXiv 2016`

`HIN2Vec: Explore Meta-paths in Heterogeneous Information Networks for Representation Learning
<https://dl.acm.org/citation.cfm?id=3132953>`_
    | :author:`Tao-yang Fu, Wang-Chien Lee, Zhen Lei`
    | :venue:`CIKM 2017`

`An Attention-based Collaboration Framework for Multi-View Network Representation Learning
<https://arxiv.org/pdf/1709.06636>`_
    | :author:`Meng Qu, Jian Tang, Jingbo Shang, Xiang Ren, Ming Zhang, Jiawei Han`
    | :venue:`CIKM 2017`

`Multi-view Clustering with Graph Embedding for Connectome Analysis
<https://dl.acm.org/citation.cfm?id=3132909>`_
    | :author:`Guixiang Ma, Lifang He, Chun-Ta Lu, Weixiang Shao, Philip S. Yu, Alex D. Leow, Ann B. Ragin`
    | :venue:`CIKM 2017`

`Attributed Signed Network Embedding
<https://dl.acm.org/citation.cfm?id=3132847.3132905>`_
    | :author:`Suhang Wang, Charu Aggarwal, Jiliang Tang, Huan Liu`
    | :venue:`CIKM 2017`

`CANE: Context-Aware Network Embedding for Relation Modeling
<https://aclweb.org/anthology/papers/P/P17/P17-1158/>`_
    | :author:`Cunchao Tu, Han Liu, Zhiyuan Liu, Maosong Sun`
    | :venue:`ACL 2017`

`PME: Projected Metric Embedding on Heterogeneous Networks for Link Prediction
<https://dl.acm.org/citation.cfm?id=3219986>`_
    | :author:`Hongxu Chen, Hongzhi Yin, Weiqing Wang, Hao Wang, Quoc Viet Hung Nguyen, Xue Li`
    | :venue:`KDD 2018`

`BiNE: Bipartite Network Embedding
<https://dl.acm.org/citation.cfm?id=3209978.3209987>`_
    | :author:`Ming Gao, Leihui Chen, Xiangnan He, Aoying Zhou`
    | :venue:`SIGIR 2018`

`StarSpace: Embed All The Things
<https://arxiv.org/pdf/1709.03856>`_
    | :author:`Ledell Wu, Adam Fisch, Sumit Chopra, Keith Adams, Antoine Bordes, Jason Weston`
    | :venue:`AAAI 2018`

`Exploring Expert Cognition for Attributed Network Embedding
<https://dl.acm.org/citation.cfm?id=3159655>`_
    | :author:`Xiao Huang, Qingquan Song, Jundong Li, Xia Hu`
    | :venue:`WSDM 2018`

`SHINE: Signed Heterogeneous Information Network Embedding for Sentiment Link Prediction
<https://arxiv.org/pdf/1712.00732>`_
    | :author:`Hongwei Wang, Fuzheng Zhang, Min Hou, Xing Xie, Minyi Guo, Qi Liu`
    | :venue:`WSDM 2018`

`Multidimensional Network Embedding with Hierarchical Structures
<https://dl.acm.org/citation.cfm?id=3159680>`_
    | :author:`Yao Ma, Zhaochun Ren, Ziheng Jiang, Jiliang Tang, Dawei Yin`
    | :venue:`WSDM 2018`

`Curriculum Learning for Heterogeneous Star Network Embedding via Deep Reinforcement Learning
<https://dl.acm.org/citation.cfm?id=3159711>`_
    | :author:`Meng Qu, Jian Tang, Jiawei Han`
    | :venue:`WSDM 2018`

`Generative Adversarial Network based Heterogeneous Bibliographic Network Representation for Personalized Citation Recommendation
<https://www.semanticscholar.org/paper/Generative-Adversarial-Network-Based-Heterogeneous-Cai-Han/1596d6487012696ba400fb69904a2c372a08a2be>`_
    | :author:`Xiaoyan Cai, Junwei Han, Libin Yang`
    | :venue:`AAAI 2018`

`ANRL: Attributed Network Representation Learning via Deep Neural Networks
<https://www.ijcai.org/proceedings/2018/438>`_
    | :author:`Zhen Zhang, Hongxia Yang, Jiajun Bu, Sheng Zhou, Pinggang Yu, Jianwei Zhang, Martin Ester, Can Wang`
    | :venue:`AAAI 2018`

`Efficient Attributed Network Embedding via Recursive Randomized Hashing
<https://www.ijcai.org/proceedings/2018/397>`_
    | :author:`Wei Wu, Bin Li, Ling Chen, Chengqi Zhang`
    | :venue:`IJCAI 2018`

`Deep Attributed Network Embedding
<https://www.ijcai.org/proceedings/2018/467>`_
    | :author:`Hongchang Gao, Heng Huang`
    | :venue:`IJCAI 2018`

`Co-Regularized Deep Multi-Network Embedding
<https://dl.acm.org/citation.cfm?id=3186113>`_
    | :author:`Jingchao Ni, Shiyu Chang, Xiao Liu, Wei Cheng, Haifeng Chen, Dongkuan Xu, Xiang Zhang`
    | :venue:`WWW 2018`

`Easing Embedding Learning by Comprehensive Transcription of Heterogeneous Information Networks
<https://arxiv.org/pdf/1807.03490>`_
    | :author:`Yu Shi, Qi Zhu, Fang Guo, Chao Zhang, Jiawei Han`
    | :venue:`KDD 2018`

`Meta-Graph Based HIN Spectral Embedding: Methods, Analyses, and Insights
<https://www.semanticscholar.org/paper/Meta-Graph-Based-HIN-Spectral-Embedding%3A-Methods%2C-Yang-Feng/4d5f4d6785d550383e3f3afb04c3015bf0d28405>`_
    | :author:`Carl Yang, Yichen Feng, Pan Li, Yu Shi, Jiawei Han`
    | :venue:`ICDM 2018`

`SIDE: Representation Learning in Signed Directed Networks
<https://dl.acm.org/citation.cfm?id=3186117>`_
    | :author:`Junghwan Kim, Haekyu Park, Ji-Eun Lee, U Kang`
    | :venue:`WWW 2018`

Node Representation Learning in Dynamic Graphs
----------------------------------------------

Knowledge Graph Embedding
=========================

Graph Neural Networks
=====================

`Revisiting Semi-supervised Learning with Graph Embeddings
<https://arxiv.org/pdf/1603.08861>`_
    | :author:`Zhilin Yang, William W. Cohen, Ruslan Salakhutdinov`
    | :venue:`ICML 2016`

`Semi-Supervised Classification with Graph Convolutional Networks
<https://arxiv.org/pdf/1609.02907>`_
    | :author:`Thomas N. Kipf, Max Welling`
    | :venue:`ICLR 2017`

`Neural Message Passing for Quantum Chemistry
<https://arxiv.org/pdf/1704.01212>`_
    | :author:`Justin Gilmer, Samuel S. Schoenholz, Patrick F. Riley, Oriol Vinyals, George E. Dahl`
    | :venue:`ICML 2017`

`Motif-Aware Graph Embeddings
<http://gearons.org/assets/docs/motif-aware-graph-final.pdf>`_
    | :author:`Hoang Nguyen, Tsuyoshi Murata`
    | :venue:`IJCAI 2017`

`Learning Graph Representations with Embedding Propagation
<https://arxiv.org/pdf/1710.03059>`_
    | :author:`Alberto Garcia-Duran, Mathias Niepert`
    | :venue:`NIPS 2017`

`Inductive Representation Learning on Large Graphs
<https://arxiv.org/pdf/1706.02216>`_
    | :author:`William L. Hamilton, Rex Ying, Jure Leskovec`
    | :venue:`NIPS 2017`

`Graph Attention Networks
<https://arxiv.org/pdf/1710.10903>`_
    | :author:`Petar Veličković, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Liò, Yoshua Bengio`
    | :venue:`ICLR 2018`

`FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling
<https://arxiv.org/pdf/1801.10247>`_
    | :author:`Jie Chen, Tengfei Ma, Cao Xiao`
    | :venue:`ICLR 2018`

`Representation Learning on Graphs with Jumping Knowledge Networks
<https://arxiv.org/pdf/1806.03536>`_
    | :author:`Keyulu Xu, Chengtao Li, Yonglong Tian, Tomohiro Sonobe, Ken-ichi Kawarabayashi, Stefanie Jegelka`
    | :venue:`ICML 2018`

`Stochastic Training of Graph Convolutional Networks with Variance Reduction
<https://arxiv.org/pdf/1710.10568>`_
    | :author:`Jianfei Chen, Jun Zhu, Le Song`
    | :venue:`ICML 2018`

`Large-Scale Learnable Graph Convolutional Networks
<https://arxiv.org/pdf/1808.03965>`_
    | :author:`Hongyang Gao, Zhengyang Wang, Shuiwang Ji`
    | :venue:`KDD 2018`

`Adaptive Sampling Towards Fast Graph Representation Learning
<https://papers.nips.cc/paper/7707-adaptive-sampling-towards-fast-graph-representation-learning.pdf>`_
    | :author:`Wenbing Huang, Tong Zhang, Yu Rong, Junzhou Huang`
    | :venue:`NeurIPS 2018`

`Hierarchical Graph Representation Learning with Differentiable Pooling
<https://arxiv.org/pdf/1806.08804>`_
    | :author:`Rex Ying, Jiaxuan You, Christopher Morris, Xiang Ren, William L. Hamilton, Jure Leskovec`
    | :venue:`NeurIPS 2018`

`Bayesian Semi-supervised Learning with Graph Gaussian Processes
<https://papers.nips.cc/paper/7440-bayesian-semi-supervised-learning-with-graph-gaussian-processes.pdf>`_
    | :author:`Yin Cheng Ng, Nicolò Colombo, Ricardo Silva`
    | :venue:`NeurIPS 2018`

`Pitfalls of Graph Neural Network Evaluation
<https://arxiv.org/pdf/1811.05868>`_
    | :author:`Oleksandr Shchur, Maximilian Mumme, Aleksandar Bojchevski, Stephan Günnemann`
    | :venue:`arXiv 2018.11`

`Heterogeneous Graph Attention Network
<https://arxiv.org/pdf/1903.07293>`_
    | :author:`Xiao Wang, Houye Ji, Chuan Shi, Bai Wang, Peng Cui, P. Yu, Yanfang Ye`
    | :venue:`WWW 2019`

`How Powerful are Graph Neural Networks?
<https://arxiv.org/pdf/1810.00826>`_
    | :author:`Keyulu Xu, Weihua Hu, Jure Leskovec, Stefanie Jegelka`
    | :venue:`ICLR 2019`

`LanczosNet: Multi-Scale Deep Graph Convolutional Networks
<https://arxiv.org/pdf/1901.01484>`_
    | :author:`Renjie Liao, Zhizhen Zhao, Raquel Urtasun, Richard S. Zemel`
    | :venue:`ICLR 2019`

`Graph Wavelet Neural Network
<https://arxiv.org/pdf/1904.07785>`_
    | :author:`Bingbing Xu, Huawei Shen, Qi Cao, Yunqi Qiu, Xueqi Cheng`
    | :venue:`ICLR 2019`

`Supervised Community Detection with Line Graph Neural Networks
<https://openreview.net/pdf?id=H1g0Z3A9Fm>`_
    | :author:`Zhengdao Chen, Xiang Li, Joan Bruna`
    | :venue:`ICLR 2019`

`Predict then Propagate: Graph Neural Networks meet Personalized PageRank
<https://arxiv.org/pdf/1810.05997>`_
    | :author:`Johannes Klicpera, Aleksandar Bojchevski, Stephan Günnemann`
    | :venue:`ICLR 2019`

`Invariant and Equivariant Graph Networks
<https://arxiv.org/pdf/1812.09902>`_
    | :author:`Haggai Maron, Heli Ben-Hamu, Nadav Shamir, Yaron Lipman`
    | :venue:`ICLR 2019`

`Capsule Graph Neural Network
<https://openreview.net/pdf?id=Byl8BnRcYm>`_
    | :author:`Zhang Xinyi, Lihui Chen`
    | :venue:`ICLR 2019`

`MixHop: Higher-Order Graph Convolutional Architectures via Sparsified Neighborhood Mixing
<https://arxiv.org/pdf/1905.00067>`_
    | :author:`Sami Abu-El-Haija, Bryan Perozzi, Amol Kapoor, Nazanin Alipourfard, Kristina Lerman,
        Hrayr Harutyunyan, Greg Ver Steeg, Aram Galstyan`
    | :venue:`ICML 2019`

`Graph U-Nets
<https://arxiv.org/pdf/1905.05178>`_
    | :author:`Hongyang Gao, Shuiwang Ji`
    | :venue:`ICML 2019`

`Disentangled Graph Convolutional Networks
<http://proceedings.mlr.press/v97/ma19a/ma19a.pdf>`_
    | :author:`Jianxin Ma, Peng Cui, Kun Kuang, Xin Wang, Wenwu Zhu`
    | :venue:`ICML 2019`

`GMNN: Graph Markov Neural Networks
<https://arxiv.org/pdf/1905.06214>`_
    | :author:`Meng Qu, Yoshua Bengio, Jian Tang`
    | :venue:`ICML 2019`

`Simplifying Graph Convolutional Networks
<https://arxiv.org/pdf/1902.07153>`_
    | :author:`Felix Wu, Tianyi Zhang, Amauri Holanda de Souza Jr., Christopher Fifty, Tao Yu, Kilian Q. Weinberger`
    | :venue:`ICML 2019`

`Position-aware Graph Neural Networks
<https://arxiv.org/pdf/1906.04817>`_
    | :author:`Jiaxuan You, Rex Ying, Jure Leskovec`
    | :venue:`ICML 2019`

`Self-Attention Graph Pooling
<https://arxiv.org/pdf/1904.08082>`_
    | :author:`Junhyun Lee, Inyeop Lee, Jaewoo Kang`
    | :venue:`ICML 2019`

Applications of Graph Neural Networks
=====================================

Natural Language Processing
---------------------------

Computer Vision
---------------

Recommender Systems
-------------------

Link Prediction
---------------

Influence Prediction
--------------------

Neural Architecture Search
--------------------------

Reinforcement Learning
----------------------

Combinatorial Optimization
--------------------------

Adversarial Attack
------------------

Meta Learning
-------------

Structure Learning
------------------

Bioinformatics
--------------

Theorem Proving
---------------

Graph Generation
================

Graph Layout and High-dimensional Data Visualization
====================================================

`Visualizing Data using t-SNE
<http://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf>`_
    | :author:`Laurens van der Maaten, Geoffrey Hinton`
    | :venue:`JMLR 2008`

`Visualizing non-metric similarities in multiple maps
<https://link.springer.com/content/pdf/10.1007/s10994-011-5273-4.pdf>`_
    | :author:`Laurens van der Maaten, Geoffrey Hinton`
    | :venue:`ML 2012`

`Visualizing Large-scale and High-dimensional Data
<https://arxiv.org/pdf/1602.00370>`_
    | :author:`Jian Tang, Jingzhou Liu, Ming Zhang, Qiaozhu Mei`
    | :venue:`WWW 2016`

Graph Representation Learning Systems
=====================================

`PyTorch-BigGraph: A Large-scale Graph Embedding System
<https://arxiv.org/pdf/1903.12287>`_
    | :author:`Adam Lerer, Ledell Wu, Jiajun Shen, Timothee Lacroix, Luca Wehrstedt,
        Abhijit Bose, Alex Peysakhovich`
    | :venue:`SysML 2019`

`GraphVite: A High-Performance CPU-GPU Hybrid System for Node Embedding
<https://arxiv.org/pdf/1903.00757>`_
    | :author:`Zhaocheng Zhu, Shizhen Xu, Meng Qu, Jian Tang`
    | :venue:`WWW 2019`

`AliGraph: A Comprehensive Graph Neural Network Platform
<https://arxiv.org/pdf/1902.08730>`_
    | :author:`Rong Zhu, Kun Zhao, Hongxia Yang, Wei Lin, Chang Zhou, Baole Ai,
        Yong Li, Jingren Zhou`
    | :venue:`VLDB 2019`

`Deep Graph Library
<https://www.dgl.ai>`_
    | :author:`DGL Team`

`Euler
<https://github.com/alibaba/euler>`_
    | :author:`Alimama Engineering Platform Team, Alimama Search Advertising Algorithm Team`

Datasets
========
