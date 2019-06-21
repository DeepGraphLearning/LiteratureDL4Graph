# Literature of Deep Learning for Graphs
This is a paper list about deep learning for graphs.

## Contents
- [Node Representation Learning](#node)
   - [Unsupervised Node Representation Learning](#unrl)
   - [Node Representation Learning in Heterogeneous Graphs](#hin)
   - [Node Representation Learning in Dynamic Graphs](#dynamic)
- [Knowledge Graph Embedding](#kge)
- [Graph Neural Networks](#gnn)
- [Applications of Graph Neural Networks](#gnnapp)
   - [Natural Language Processing](#gnn4nlp)
   - [Computer Vision](#gnn4cv)
   - [Recommender Systems](#gnn4rs)
   - [Link Prediction](#gnn4lp)
   - [Influence Prediction](#gnn4ip)
   - [Neural Architecture Search](#gnn4nas)
   - [Reinforcement Learning](#gnn4rl)
   - [Combinatorial Optimization](#gnn4co)
   - [Adversarial Attack](#gnn4aa)
   - [Meta Learning](#gnn4ml)
   - [Structure Learning](#gnn4sl)
   - [Bioinformatics](#gnn4bio)
   - [Theorem Proving](#gnn4tp)
- [Graph Generation](#gen)
- [Graph Layout and High-dimensional Data Visualization](#vis)
- [Graph Representation Learning Systems](#sys)
- [Datasets](#dat)

<a name="node" />

## Node Representation Learning

<a name="unrl" />

### Unsupervised Node Representation Learning
1. [**DeepWalk: Online Learning of Social Representations.**](https://arxiv.org/pdf/1403.6652.pdf) \
*Bryan Perozzi, Rami Al-Rfou, Steven Skiena.* \
**KDD 2014** \
*Node Classification, Random Walk, Skip-gram.*

1. [**LINE: Large-scale Information Network Embedding.**](https://arxiv.org/pdf/1503.03578.pdf) \
*Jian Tang, Meng Qu, Mingzhe Wang, Ming Zhang, Jun Yan, Qiaozhu Mei.* \
**WWW 2015** \
*First-order, Second-order, Node Classification.*

1. [**GraRep: Learning Graph Representations with Global Structural Information.**](https://dl.acm.org/citation.cfm?id=2806512) \
*Shaosheng Cao, Wei Lu, Qiongkai Xu.* \
**CIKM 2015** \
*High-order, SVD.*

1. [**node2vec: Scalable Feature Learning for Networks.**](https://arxiv.org/pdf/1607.00653.pdf) \
*Aditya Grover, Jure Leskovec.* \
**KDD 2016** \
*Breadth-first Search, Depth-first Search, Node Classification, Link Prediction.*

1. [**Scalable Graph Embedding for Asymmetric Proximity.**](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14696) \
*Chang Zhou, Yuqiong Liu, Xiaofei Liu, Zhongyi Liu, Jun Gao.* \
**AAAI 2017**

1. [**Fast Network Embedding Enhancement via High Order Proximity Approximation.**](https://www.ijcai.org/proceedings/2017/544) \
*Cheng Yang, Maosong Sun, Zhiyuan Liu, Cunchao Tu.* \
**IJCAI 2017**

1. [**struc2vec: Learning Node Representations from Structural Identity.**](https://arxiv.org/pdf/1704.03165.pdf) \
*Leonardo F. R. Ribeiro, Pedro H. P. Savarese, Daniel R. Figueiredo.* \
**KDD 2017** \
*Structural Identity.*

1. [**Poincaré Embeddings for Learning Hierarchical Representations.**](https://arxiv.org/pdf/1705.08039.pdf) \
*Maximilian Nickel, Douwe Kiela.* \
**NeurIPS 2017**

1. [**VERSE: Versatile Graph Embeddings from Similarity Measures.**](https://arxiv.org/pdf/1803.04742.pdf) \
*Anton Tsitsulin, Davide Mottin, Panagiotis Karras, Emmanuel Müller.* \
**WWW 2018**

1. [**Network Embedding as Matrix Factorization: Unifying DeepWalk, LINE, PTE, and node2vec.**](https://arxiv.org/pdf/1710.02971.pdf) \
*Jiezhong Qiu, Yuxiao Dong, Hao Ma, Jian Li, Kuansan Wang, Jie Tang.* \
**WSDM 2018**

1. [**Learning Structural Node Embeddings via Diffusion Wavelets.**](https://arxiv.org/pdf/1710.10321.pdf) \
*Claire Donnat, Marinka Zitnik, David Hallac, Jure Leskovec.* \
**KDD 2018**

1. [**Adversarial Network Embedding.**](https://arxiv.org/pdf/1711.07838.pdf) \
*Quanyu Dai, Qiang Li, Jian Tang, Dan Wang.* \
**AAAI 2018**

1. [**GraphGAN: Graph Representation Learning with Generative Adversarial Nets.**](https://arxiv.org/pdf/1711.08267.pdf) \
*Hongwei Wang, Jia Wang, Jialin Wang, Miao Zhao, Weinan Zhang, Fuzheng Zhang, Xing Xie, Minyi Guo.* \
**AAAI 2018**

1. [**A General View for Network Embedding as Matrix Factorization.**](https://dl.acm.org/citation.cfm?id=3291029) \
*Xin Liu, Tsuyoshi Murata, Kyoung-Sook Kim, Chatchawan Kotarasu, Chenyi Zhuang.* \
**WSDM 2019**

1. [**NetSMF: Large-Scale Network Embedding as Sparse Matrix Factorization.**](https://www.microsoft.com/en-us/research/uploads/prod/2019/03/www19netsmf.pdf) \
*Jiezhong Qiu, Yuxiao Dong, Hao Ma, Jian Li, Chi Wang, Kuansan Wang, Jie Tang.* \
**WWW 2019**

1. [**Adversarial Training Methods for Network Embedding.**](https://dl.acm.org/citation.cfm?id=3313445) \
*Quanyu Dai, Xiao Shen, Liang Zhang, Qiang Li, Dan Wang.* \
**WWW 2019**

<a name="hin" />

### Node Representation Learning in Heterogeneous Graphs

1. [**Learning Latent Representations of Nodes for Classifying in Heterogeneous Social Networks.**](https://dl.acm.org/citation.cfm?id=2556225) \
*Yann Jacob, Ludovic Denoyer, Patrick Gallinari.* \
**WSDM 2014**

1. [**PTE: Predictive Text Embedding through Large-scale Heterogeneous Text Networks.**](https://arxiv.org/pdf/1508.00200.pdf) \
*Jian Tang, Meng Qu, Qiaozhu Mei.* \
**KDD 2015** \
*Text Embedding, Heterogeneous Text Graphs.*

1. [**Heterogeneous Network Embedding via Deep Architectures.**](https://dl.acm.org/citation.cfm?id=2783296) \
*Shiyu Chang, Wei Han, Jiliang Tang, Guo-Jun Qi, Charu C. Aggarwal, Thomas S. Huang.* \
**KDD 2015**

1. [**Network Representation Learning with Rich Text Information.**](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI15/paper/view/11098) \
*Cheng Yang, Zhiyuan Liu, Deli Zhao, Maosong Sun, Edward Chang.* \
**AAAI 2015**

1. [**Max-Margin DeepWalk: Discriminative Learning of Network Representation.**](https://www.ijcai.org/Proceedings/16/Papers/547.pdf) \
*Cunchao Tu, Weicheng Zhang, Zhiyuan Liu, Maosong Sun.* \
**IJCAI 2016**

1. [**metapath2vec: Scalable Representation Learning for Heterogeneous Networks.**](https://dl.acm.org/citation.cfm?id=3098036) \
*Yuxiao Dong, Nitesh V. Chawla, Ananthram Swami.* \
**KDD 2017**

1. [**Meta-Path Guided Embedding for Similarity Search in Large-Scale Heterogeneous Information Networks.**](https://arxiv.org/pdf/1610.09769.pdf) \
*Jingbo Shang, Meng Qu, Jialu Liu, Lance M. Kaplan, Jiawei Han, Jian Peng.* \
**arXiv 2016**

1. [**HIN2Vec: Explore Meta-paths in Heterogeneous Information Networks for Representation Learning.**](https://dl.acm.org/citation.cfm?id=3132953) \
*Tao-yang Fu, Wang-Chien Lee, Zhen Lei.* \
**CIKM 2017**

1. [**An Attention-based Collaboration Framework for Multi-View Network Representation Learning.**](https://arxiv.org/pdf/1709.06636.pdf) \
*Meng Qu, Jian Tang, Jingbo Shang, Xiang Ren, Ming Zhang, Jiawei Han.* \
**CIKM 2017**

1. [**Multi-view Clustering with Graph Embedding for Connectome Analysis.**](https://dl.acm.org/citation.cfm?id=3132909) \
*Guixiang Ma, Lifang He, Chun-Ta Lu, Weixiang Shao, Philip S. Yu, Alex D. Leow, Ann B. Ragin.* \
**CIKM 2017**

1. [**Attributed Signed Network Embedding.**](https://dl.acm.org/citation.cfm?id=3132847.3132905) \
*Suhang Wang, Charu Aggarwal, Jiliang Tang, Huan Liu.* \
**CIKM 2017**

1. [**CANE: Context-Aware Network Embedding for Relation Modeling.**](https://aclweb.org/anthology/papers/P/P17/P17-1158/) \
*Cunchao Tu, Han Liu, Zhiyuan Liu, Maosong Sun.* \
**ACL 2017**

1. [**PME: Projected Metric Embedding on Heterogeneous Networks for Link Prediction.**](https://dl.acm.org/citation.cfm?id=3219986) \
*Hongxu Chen, Hongzhi Yin, Weiqing Wang, Hao Wang, Quoc Viet Hung Nguyen, Xue Li.* \
**KDD 2018**

1. [**BiNE: Bipartite Network Embedding.**](https://dl.acm.org/citation.cfm?id=3209978.3209987) \
*Ming Gao, Leihui Chen, Xiangnan He, Aoying Zhou.* \
**SIGIR 2018**

1. [**StarSpace: Embed All The Things!**](https://arxiv.org/abs/1709.03856) \
*Ledell Wu, Adam Fisch, Sumit Chopra, Keith Adams, Antoine Bordes, Jason Weston.* \
**AAAI 2018**

1. [**Exploring Expert Cognition for Attributed Network Embedding.**](https://dl.acm.org/citation.cfm?id=3159655) \
*Xiao Huang, Qingquan Song, Jundong Li, Xia Hu.* \
**WSDM 2018**

1. [**SHINE: Signed Heterogeneous Information Network Embedding for Sentiment Link Prediction.**](https://arxiv.org/abs/1712.00732) \
*Hongwei Wang, Fuzheng Zhang, Min Hou, Xing Xie, Minyi Guo, Qi Liu.* \
**WSDM 2018**

1. [**Multidimensional Network Embedding with Hierarchical Structures.**](https://dl.acm.org/citation.cfm?id=3159680) \
*Yao Ma, Zhaochun Ren, Ziheng Jiang, Jiliang Tang, Dawei Yin.* \
**WSDM 2018**

1. [**Curriculum Learning for Heterogeneous Star Network Embedding via Deep Reinforcement Learning.**](https://dl.acm.org/citation.cfm?id=3159711) \
*Meng Qu, Jian Tang, Jiawei Han.* \
**WSDM 2018**

1. [**Generative Adversarial Network based Heterogeneous Bibliographic Network Representation for Personalized Citation Recommendation.**](https://www.semanticscholar.org/paper/Generative-Adversarial-Network-Based-Heterogeneous-Cai-Han/1596d6487012696ba400fb69904a2c372a08a2be) \
*Xiaoyan Cai, Junwei Han, Libin Yang.* \
**AAAI 2018**

1. [**ANRL: Attributed Network Representation Learning via Deep Neural Networks.**](https://www.ijcai.org/proceedings/2018/438) \
*Zhen Zhang, Hongxia Yang, Jiajun Bu, Sheng Zhou, Pinggang Yu, Jianwei Zhang, Martin Ester, Can Wang.* \
**AAAI 2018**

1. [**Efficient Attributed Network Embedding via Recursive Randomized Hashing.**](https://www.ijcai.org/proceedings/2018/397) \
*Wei Wu, Bin Li, Ling Chen, Chengqi Zhang.* \
**IJCAI 2018**

1. [**Deep Attributed Network Embedding.**](https://www.ijcai.org/proceedings/2018/467) \
*Hongchang Gao, Heng Huang.* \
**IJCAI 2018**

1. [**Co-Regularized Deep Multi-Network Embedding.**](https://dl.acm.org/citation.cfm?id=3186113) \
*Jingchao Ni, Shiyu Chang, Xiao Liu, Wei Cheng, Haifeng Chen, Dongkuan Xu, Xiang Zhang.* \
**WWW 2018**

1. [**Easing Embedding Learning by Comprehensive Transcription of Heterogeneous Information Networks.**](https://arxiv.org/abs/1807.03490) \
*Yu Shi, Qi Zhu, Fang Guo, Chao Zhang, Jiawei Han.* \
**KDD 2018**

1. [**Meta-Graph Based HIN Spectral Embedding: Methods, Analyses, and Insights.**](https://www.semanticscholar.org/paper/Meta-Graph-Based-HIN-Spectral-Embedding%3A-Methods%2C-Yang-Feng/4d5f4d6785d550383e3f3afb04c3015bf0d28405) \
*Carl Yang, Yichen Feng, Pan Li, Yu Shi, Jiawei Han.* \
**ICDM 2018**

1. [**SIDE: Representation Learning in Signed Directed Networks.**](https://dl.acm.org/citation.cfm?id=3186117) \
*Junghwan Kim, Haekyu Park, Ji-Eun Lee, U Kang.* \
**WWW 2018**

1. [**Deep Graph Infomax.**](https://arxiv.org/abs/1809.10341) \
*Petar Veličković, William Fedus, William L. Hamilton, Pietro Liò, Yoshua Bengio, R Devon Hjelm.* \
**ICLR 2019**

<a name="dynamic" />

### Node Representation Learning in Dynamic Graphs

<a name="kge" />

## Knowledge Graph Embedding


<a name="gnn" />

## Graph Neural Networks

1. [**Revisiting Semi-supervised Learning with Graph Embeddings.**](https://arxiv.org/abs/1603.08861) \
*Zhilin Yang, William W. Cohen, Ruslan Salakhutdinov.* \
**ICML 2016**

1. [**Semi-Supervised Classification with Graph Convolutional Networks.**](https://arxiv.org/abs/1609.02907) \
*Thomas N. Kipf, Max Welling.* \
**ICLR 2017**

1. [**Neural Message Passing for Quantum Chemistry.**](https://arxiv.org/abs/1704.01212) \
*Justin Gilmer, Samuel S. Schoenholz, Patrick F. Riley, Oriol Vinyals, George E. Dahl.* \
**ICML 2017**

1. [**Motif-Aware Graph Embeddings.**](http://gearons.org/assets/docs/motif-aware-graph-final.pdf) \
*Hoang Nguyen, Tsuyoshi Murata.* \
**IJCAI 2017**

1. [**Learning Graph Representations with Embedding Propagation.**](https://arxiv.org/abs/1710.03059) \
*Alberto Garcia-Duran, Mathias Niepert.* \
**NeurIPS 2017**

1. [**Inductive Representation Learning on Large Graphs.**](https://arxiv.org/abs/1706.02216) \
*William L. Hamilton, Rex Ying, Jure Leskovec.* \
**NeurIPS 2017**

1. [**Graph Attention Networks.**](https://arxiv.org/abs/1710.10903) \
*Petar Veličković, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Liò, Yoshua Bengio.* \
**ICLR 2018**

1. [**FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling.**](https://arxiv.org/abs/1801.10247) \
*Jie Chen, Tengfei Ma, Cao Xiao.* \
**ICLR 2018**

1. [**Representation Learning on Graphs with Jumping Knowledge Networks.**](https://arxiv.org/abs/1806.03536) \
*Keyulu Xu, Chengtao Li, Yonglong Tian, Tomohiro Sonobe, Ken-ichi Kawarabayashi, Stefanie Jegelka.* \
**ICML 2018**

1. [**Stochastic Training of Graph Convolutional Networks with Variance Reduction.**](https://arxiv.org/abs/1710.10568) \
*Jianfei Chen, Jun Zhu, Le Song.* \
**ICML 2018**

1. [**Large-Scale Learnable Graph Convolutional Networks.**]() \
*XXX* \
**KDD 2018**

1. [**Adaptive Sampling Towards Fast Graph Representation Learning.**]() \
*XXX* \
**NeurIPS 2018**

1. [**Hierarchical Graph Representation Learning with Differentiable Pooling.**]() \
*XXX* \
**NeurIPS 2018**

1. [**Bayesian Semi-supervised Learning with Graph Gaussian Processes.**]() \
*XXX* \
**NeurIPS 2018**

1. [**Pitfalls of Graph Neural Network Evaluation.**]() \
*XXX* \
**arXiv 1811**

1. [**Heterogeneous Graph Attention Network.**]() \
*XXX* \
**WWW 2019**

1. [**How Powerful are Graph Neural Networks?**]() \
*XXX* \
**ICLR 2019**

1. [**LanczosNet: Multi-Scale Deep Graph Convolutional Networks.**]() \
*XXX* \
**ICLR 2019**

1. [**Graph Wavelet Neural Network.**]() \
*XXX* \
**ICLR 2019**

1. [**Supervised Community Detection with Line Graph Neural Networks.**]() \
*XXX* \
**ICLR 2019**

1. [**Predict then Propagate: Graph Neural Networks meet Personalized PageRank.**]() \
*XXX* \
**ICLR 2019**

1. [**Invariant and Equivariant Graph Networks.**]() \
*XXX* \
**ICLR 2019**

1. [**Capsule Graph Neural Network.**]() \
*XXX* \
**ICLR 2019**

1. [**MixHop: Higher-Order Graph Convolutional Architectures via Sparsified Neighborhood Mixing.**]() \
*XXX* \
**ICML 2019**

1. [**Graph U-Nets.**]() \
*XXX* \
**ICML 2019**

1. [**Disentangled Graph Convolutional Networks.**]() \
*XXX* \
**ICML 2019**

1. [**GMNN: Graph Markov Neural Networks.**]() \
*XXX* \
**ICML 2019**

1. [**Simplifying Graph Convolutional Networks.**]() \
*XXX* \
**ICML 2019**

1. [**Position-aware Graph Neural Networks.**]() \
*XXX* \
**ICML 2019**

1. [**Self-Attention Graph Pooling.**]() \
*XXX* \
**ICML 2019**


<a name="gnnapp" />

## Applications of Graph Neural Networks

<a name="gnn4nlp" />

### Natural Language Processing


<a name="gnn4cv" />

### Computer Vision

<a name="gnn4rs" />

### Recommender Systems
1. [**Graph Convolutional Neural Networks for Web-Scale Recommender Systems.**](https://arxiv.org/pdf/1806.01973.pdf)\
*Rex Ying, Ruining He, Kaifeng Chen, Pong Eksombatchai, William L. Hamilton, Jure Leskovec.* \
**KDD 2018**
*PinSage*


<a name="gnn4lp" />

### Link Prediction

<a name="gnn4ip" />

### Influence Prediction

<a name="gnn4nas" />

### Neural Architecture Search

<a name="gnn4rl" />

### Reinforcement Learning

<a name="gnn4co" />

### Combinatorial Optimization


<a name="gnn4aa" />

### Adversarial Attack


<a name="gnn4ml" />

### Meta Learning

<a name="gnn4sl" />

### Structure Learning

<a name="gnn4bio" />

### Bioinformatics

<a name="gnn4tp" />

### Theorem Proving

<a name="gen" />

## Graph Generation

<a name="vis" />

## Graph Layout and High-dimensional Data Visualization

<a name="sys" />

## Graph Representation Learning Systems


<a name="dat" />

## Datasets




