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

1. [**Know-evolve: Deep temporal reasoning for dynamic knowledge graphs.**](https://arxiv.org/pdf/1705.05742.pdf) \
*Rakshit Trivedi, Hanjun Dai, Yichen Wang, Le Song.* \
**ICML 2017**

1. [**Dyngem: Deep embedding method for dynamic graphs.**](https://arxiv.org/pdf/1805.11273.pdf) \
*Palash Goyal, Nitin Kamra, Xinran He, Yan Liu.*
**ICLR 2017 Workshop**

1. [**Attributed network embedding for learning in a dynamic environment.**](https://arxiv.org/pdf/1706.01860.pdf) \
*Jundong Li, Harsh Dani, Xia Hu, Jiliang Tang, Yi Chang, Huan Liu.*
**CIKM 2017**

1. [**Dynamic Network Embedding by Modeling Triadic Closure Process.**](http://yangy.org/works/dynamictriad/dynamic_triad.pdf) \
*Lekui Zhou, Yang Yang, Xiang Ren, Fei Wu, Yueting Zhuang.*
**AAAI 2018**

1. [**DepthLGP: Learning Embeddings of Out-of-Sample Nodes in Dynamic Networks.**](https://pdfs.semanticscholar.org/9499/b38866b1eb87ae43fa5be02f9d08cd3c20a8.pdf?_ga=2.6780794.935636364.1561139530-1831876308.1523264869) \
*Jianxin Ma, Peng Cui, Wenwu Zhu.*
**AAAI 2018**

1. [**TIMERS: Error-Bounded SVD Restart on Dynamic Networks.**](https://arxiv.org/pdf/1711.09541.pdf) \
*Ziwei Zhang, Peng Cui, Jian Pei, Xiao Wang, Wenwu Zhu.*
**AAAI 2018**

1. [**Dynamic Embeddings for User Profiling in Twitter.**](https://dl.acm.org/citation.cfm?id=3219819.3220043) \
*Shangsong Liang, Xiangliang Zhang, Zhaochun Ren, Evangelos Kanoulas.*
**KDD 2018**

1. [**Dynamic Network Embedding : An Extended Approach for Skip-gram based Network Embedding.**](https://www.ijcai.org/proceedings/2018/0288.pdf) \
*Lun Du, Yun Wang, Guojie Song, Zhicong Lu, Junshan Wang.*
**IJCAI 2018**

1. [**DyRep: Learning Representations over Dynamic Graphs.**](https://openreview.net/pdf?id=HyePrhR5KX)
*Rakshit Trivedi, Mehrdad Farajtabar, Prasenjeet Biswal, Hongyuan Zha.*
**ICLR 2019**


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

1. [**Encoding Sentences with Graph Convolutional Networks for Semantic Role Labeling.**](https://www.aclweb.org/anthology/D17-1159) \
*Diego Marcheggiani, Ivan Titov.* \
**EMNLP 2017**

1. [**Graph Convolutional Encoders for Syntax-aware Neural Machine Translation.**](https://www.aclweb.org/anthology/D17-1209) \
*Joost Bastings, Ivan Titov, Wilker Aziz, Diego Marcheggiani, Khalil Sima’an.* \
**EMNLP 2017**

1. [**Graph-based Neural Multi-Document Summarization.**](https://www.aclweb.org/anthology/K17-1045) \
*Michihiro Yasunaga, Rui Zhang, Kshitijh Meelu, Ayush Pareek, Krishnan Srinivasan, Dragomir Radev.* \
**CoNLL 2017**

1. [**QANet: Combining Local Convolution with Global Self-Attention for Reading Comprehension.**](https://arxiv.org/pdf/1804.09541.pdf) \
*Adams Wei Yu, David Dohan, Minh-Thang Luong, Rui Zhao, Kai Chen, Mohammad Norouzi, Quoc V. Le.*
**ICLR 2018**

1. [**A Structured Self-attentive Sentence Embedding.**](https://arxiv.org/pdf/1703.03130.pdf) \
*Zhouhan Lin, Minwei Feng, Cicero Nogueira dos Santos, Mo Yu, Bing Xiang, Bowen Zhou, Yoshua Bengio.*
**ICLR 2018**

1. [**Modeling Semantics with Gated Graph Neural Networks for Knowledge Base Question Answering.**](https://aclweb.org/anthology/C18-1280) \
*Daniil Sorokin, Iryna Gurevych.*
**COLING 2018**

1. [**Exploiting Semantics in Neural Machine Translation with Graph Convolutional Networks.**](https://www.aclweb.org/anthology/N18-2078) \
*Diego Marcheggiani, Joost Bastings, Ivan Titov.*
**NAACL 2018**

1. [**Linguistically-Informed Self-Attention for Semantic Role Labeling.**](https://www.aclweb.org/anthology/D18-1548) \
*Emma Strubell, Patrick Verga, Daniel Andor, David Weiss, Andrew McCallum.*
**EMNLP 2018**


1. [**Graph Convolution over Pruned Dependency Trees Improves Relation Extraction.**](https://aclweb.org/anthology/D18-1244) \
*Yuhao Zhang, Peng Qi, Christopher D. Manning.*
**EMNLP 2018**

1. [**A Graph-to-Sequence Model for AMR-to-Text Generation.**](https://www.aclweb.org/anthology/P18-1150) \
*Linfeng Song, Yue Zhang, Zhiguo Wang, Daniel Gildea.*
**ACL 2018**

1. [**Graph-to-Sequence Learning using Gated Graph Neural Networks.**](https://www.aclweb.org/anthology/P18-1026) \
*Daniel Beck, Gholamreza Haffari, Trevor Cohn.*
**ACL 2018**

1. [**Graph Convolutional Networks for Text Classification.**](https://arxiv.org/pdf/1809.05679.pdf) \
*Liang Yao, Chengsheng Mao, Yuan Luo*
**AAAI 2019**

1. [**Differentiable Perturb-and-Parse: Semi-Supervised Parsing with a Structured Variational Autoencoder.**](https://openreview.net/pdf?id=BJlgNh0qKQ) \
*Caio Corro, Ivan Titov.*
**ICLR 2019.**

1. [**Structured Neural Summarization.**](https://arxiv.org/pdf/1811.01824.pdf) \
*Patrick Fernandes, Miltiadis Allamanis, Marc Brockschmid*
**ICLR 2019**

1. [**Multi-task Learning over Graph Structures.**](https://arxiv.org/pdf/1811.10211.pdf)
*Pengfei Liu, Jie Fu, Yue Dong, Xipeng Qiu, Jackie Chi Kit Cheung.*
**AAAI 2019**

1. [**Imposing Label-Relational Inductive Bias for Extremely Fine-Grained Entity Typing.**](https://arxiv.org/pdf/1903.02591.pdf) \
*Wenhan Xiong, Jiawei Wu, Deren Lei, Mo Yu, Shiyu Chang, Xiaoxiao Guo, William Yang Wang.*
**NAACL 2019**

1. [**Single Document Summarization as Tree Induction.**](https://www.aclweb.org/anthology/N19-1173) \
*Yang Liu, Ivan Titov, Mirella Lapata.*
**NAACL 2019**

1. [**Long-tail Relation Extraction via Knowledge Graph Embeddings and Graph Convolution Networks.**](https://arxiv.org/pdf/1903.01306.pdf) \
*Ningyu Zhang, Shumin Deng, Zhanlin Sun, Guanying Wang, Xi Chen, Wei Zhang, Huajun Chen.*
**NAACL 2019**

1. [**Graph Neural Networks with Generated Parameters for Relation Extraction.**](https://arxiv.org/pdf/1902.00756.pdf) \
*Hao Zhu, Yankai Lin, Zhiyuan Liu, Jie Fu, Tat-seng Chua, Maosong Sun.*
**ACL 2019**

1. [**Dynamically Fused Graph Network for Multi-hop Reasoning.**](https://arxiv.org/pdf/1905.06933.pdf) \
*Yunxuan Xiao, Yanru Qu, Lin Qiu, Hao Zhou, Lei Li, Weinan Zhang, Yong Yu.*
**ACL 2019**

1. [**Encoding Social Information with Graph Convolutional Networks for Political Perspective Detection in News Media.**](https://www.cs.purdue.edu/homes/dgoldwas//downloads/papers/LiG_acl_2019.pdf) \
*Chang Li, Dan Goldwasser*
**ACL 2019**

1. [**Attention Guided Graph Convolutional Networks for Relation Extraction.**](https://arxiv.org/pdf/1906.07510.pdf) \
*Zhijiang Guo, Yan Zhang, Wei Lu.*
**ACL 2019**

1. [**Incorporating Syntactic and Semantic Information in Word Embeddings using Graph Convolutional Networks.**](https://arxiv.org/pdf/1809.04283.pdf) \
*Shikhar Vashishth, Manik Bhandari, Prateek Yadav, Piyush Rai, Chiranjib Bhattacharyya, Partha Talukdar.*
**ACL 2019**

1. [**GraphRel: Modeling Text as Relational Graphs for Joint Entity and Relation Extraction.**](https://tsujuifu.github.io/pubs/acl19_graph-rel.pdf) \
*Tsu-Jui Fu, Peng-Hsuan Li, Wei-Yun Ma.*
**ACL 2019**

1. [**Multi-hop Reading Comprehension across Multiple Documents by Reasoning over Heterogeneous Graphs.**](https://arxiv.org/pdf/1905.07374.pdf) \
*Ming Tu, Guangtao Wang, Jing Huang, Yun Tang, Xiaodong He, Bowen Zhou.*
**ACL 2019**

1. [**Cognitive Graph for Multi-Hop Reading Comprehension at Scale.**](https://arxiv.org/pdf/1905.05460.pdf) \
*Ming Ding, Chang Zhou, Qibin Chen, Hongxia Yang, Jie Tang.*
**ACL 2019**

1. [**Coherent Comment Generation for Chinese Articles with a Graph-to-Sequence Model.**](https://arxiv.org/pdf/1906.01231.pdf) \
*Wei Li, Jingjing Xu, Yancheng He, Shengli Yan, Yunfang Wu, Xu Sun.*
**ACL 2019**

1. [**Matching Article Pairs with Graphical Decomposition and Convolutions.**](https://arxiv.org/pdf/1802.07459.pdf) \
*Bang Liu, Di Niu, Haojie Wei, Jinghong Lin, Yancheng He, Kunfeng Lai, Yu Xu.*
**ACL 2019**

1. [**Embedding Imputation with Grounded Language Information.**](https://arxiv.org/pdf/1906.03753.pdf) \
*Ziyi Yang, Chenguang Zhu, Vin Sachidananda, Eric Darve.*
**ACL 2019**





<a name="gnn4cv" />

### Computer Vision

<a name="gnn4rs" />

### Recommender Systems
1. [**Graph Convolutional Neural Networks for Web-Scale Recommender Systems.**](https://arxiv.org/pdf/1806.01973.pdf)\
*Rex Ying, Ruining He, Kaifeng Chen, Pong Eksombatchai, William L. Hamilton, Jure Leskovec.* \
**KDD 2018**
*PinSage*

1. [**SocialGCN: An Efficient Graph Convolutional Network based Model for Social Recommendation.**](https://arxiv.org/pdf/1811.02815.pdf) \
*Le Wu, Peijie Sun, Richang Hong, Yanjie Fu, Xiting Wang, Meng Wang.*
**AAAI 2018** \
**GCN, Social recommendation**

1. [**Session-based Social Recommendation via Dynamic Graph Attention Networks.**](https://arxiv.org/pdf/1902.09362.pdf) \
*Weiping Song, Zhiping Xiao, Yifan Wang, Laurent Charlin, Ming Zhang, Jian Tang.*
**WSDM 2019**
**Social recommendation, session-based, GAT**

1. [**Dual Graph Attention Networks for Deep Latent Representation of Multifaceted Social Effects in Recommender Systems.**](https://arxiv.org/pdf/1903.10433.pdf) \
*Qitian Wu, Hengrui Zhang, Xiaofeng Gao, Peng He, Paul Weng, Han Gao, Guihai Chen.*
**WWW 2019**
**Social recommendation, GAT**

1. [**Graph Neural Networks for Social Recommendation.**](https://arxiv.org/pdf/1902.07243.pdf) \
*Wenqi Fan, Yao Ma, Qing Li, Yuan He, Eric Zhao, Jiliang Tang, Dawei Yin.*
**WWW 2019**
**Social recommendation, GNN**

1. [**Session-based Recommendation with Graph Neural Networks.**](https://arxiv.org/pdf/1811.00855.pdf) \
*Shu Wu, Yuyuan Tang, Yanqiao Zhu, Liang Wang, Xing Xie, Tieniu Tan.*
**AAAI 2019**
**Session-based recommendation, GNN**

1. [**A Neural Influence Diffusion Model for Social Recommendation.**](https://arxiv.org/pdf/1904.10322.pdf) \
*Le Wu, Peijie Sun, Yanjie Fu, Richang Hong, Xiting Wang, Meng Wang.*
**SIGIR 2019**
**Social Recommendation, diffusion**

1. [**Neural Graph Collaborative Filtering.**](https://arxiv.org/pdf/1905.08108.pdf) \
*Xiang Wang, Xiangnan He, Meng Wang, Fuli Feng, Tat-Seng Chua.*
**SIGIR 2019**
**Collaborative Filtering, GNN**

1. [**Binarized Collaborative Filtering with Distilling Graph Convolutional Networks.**](https://arxiv.org/pdf/1906.01829.pdf) \
*Haoyu Wang, Defu Lian, Yong Ge.*
**IJCAI 2019**


<a name="gnn4lp" />

### Link Prediction

1. [**Link Prediction Based on Graph Neural Networks.**](https://papers.nips.cc/paper/7763-link-prediction-based-on-graph-neural-networks.pdf) \
*Muhan Zhang, Yixin Chen.*
**NeurIPS 2018**

1. [**Link Prediction via Subgraph Embedding-Based Convex Matrix Completion.**](http://iiis.tsinghua.edu.cn/~weblt/papers/link-prediction-subgraphembeddings.pdf) \
*Zhu Cao, Linlin Wang, Gerard de Melo.*
**AAAI 2018** 

1. [**Graph Convolutional Matrix Completion.**](https://www.kdd.org/kdd2018/files/deep-learning-day/DLDay18_paper_32.pdf) \
*Rianne van den Berg, Thomas N. Kipf, Max Welling.*
**KDD 2018 Workshop**


<a name="gnn4ip" />

### Influence Prediction

1. [**DeepInf: Social Influence Prediction with Deep Learning.**](https://arxiv.org/pdf/1807.05560.pdf) \
*Jiezhong Qiu, Jian Tang, Hao Ma, Yuxiao Dong, Kuansan Wang, Jie Tang.*
**KDD 2018**

1. [**Estimating Node Importance in Knowledge Graphs Using Graph Neural Networks.**](https://arxiv.org/pdf/1905.08865.pdf) \
*Namyong Park, Andrey Kan, Xin Luna Dong, Tong Zhao, Christos Faloutsos.*
**KDD 2019**

<a name="gnn4nas" />

### Neural Architecture Search

1. [**Graph HyperNetworks for Neural Architecture Search.**](https://openreview.net/pdf?id=rkgW0oA9FX) \
*Chris Zhang, Mengye Ren, Raquel Urtasun.*
**ICLR 2019**

<a name="gnn4rl" />

### Reinforcement Learning

1. [**Action Schema Networks: Generalised Policies with Deep Learning.**](https://arxiv.org/pdf/1709.04271.pdf) \
*Sam Toyer, Felipe Trevizan, Sylvie Thiebaux, Lexing Xie.*
**AAAI 2018**

1. [**NerveNet: Learning Structured Policy with Graph Neural Networks.**](https://openreview.net/pdf?id=S1sqHMZCb) \
*Tingwu Wang, Renjie Liao, Jimmy Ba, Sanja Fidler.*
**ICLR 2018**

1. [**Graph Networks as Learnable Physics Engines for Inference and Control.**](https://arxiv.org/pdf/1806.01242.pdf) \
*Alvaro Sanchez-Gonzalez, Nicolas Heess, Jost Tobias Springenberg, Josh Merel, Martin Riedmiller.*
**ICML 2018**

1. [**Learning Policy Representations in Multiagent Systems.**](https://arxiv.org/pdf/1806.06464.pdf) \
*Aditya Grover, Maruan Al-Shedivat, Jayesh K. Gupta, Yura Burda, Harrison Edwards.*
**ICML 2018**

1. [**Relational recurrent neural networks.**](https://papers.nips.cc/paper/7960-relational-recurrent-neural-networks.pdf) \
*Adam Santoro,  Ryan Faulkner, David Raposo, Jack Rae, Mike Chrzanowski,Théophane Weber, Daan Wierstra, Oriol Vinyals, Razvan Pascanu, Timothy Lillicrap.*
**NeurIPS 2018**

1. [**Transfer of Deep Reactive Policies for MDP Planning.**](http://www.cse.iitd.ac.in/~mausam/papers/nips18.pdf) \
*Aniket Bajpai, Sankalp Garg, Mausam.*
**NeurIPS 2018**

1. [**Neural Graph Evolution: Towards Efficient Automatic Robot Design.**](https://openreview.net/pdf?id=BkgWHnR5tm) \
*Tingwu Wang, Yuhao Zhou, Sanja Fidler, Jimmy Ba.*
**ICLR 2019**

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




