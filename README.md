# KAIST WINTER2022 INTERNSHIP(DSAIL)
    Recommeder System and Graph Neural Network paper review & code implementation practice
## Data Science and Artificial Intelligence Laboratory (DSAIL)
- [Official Laboratory Homepage (Website)](http://dsail.kaist.ac.kr/)
- [Introduction to the laboratory (YouTube)](https://www.youtube.com/watch?v=3Nz19Kln-yE)
- [What we are interested in (Research PDF)](https://dsail.kaist.ac.kr/files/research.pdf)

### REVIEW SCHEDULE 
| Date | Year | Paper | Code |
| :---: | --- | --- | --- |
| 1/3 | 2016 | [Semi-Supervised Classification with Graph Convolutional Networks](https://arxiv.org/abs/1609.02907)| GCN |
|     | 2014 | [DeepWalk: Online Learning of Social Representations](https://arxiv.org/abs/1403.6652)| Deepwalk |
|     | 2008 | [Probabilistic Matrix Factorization](https://papers.nips.cc/paper/2007/file/d7322ed717dedf1eb4e6e52a37ea7bcd-Paper.pdf)| PMF |
| 1/10| 2009 | [Matrix Factorization Techniques for Recommender Systems](https://datajobs.com/data-science-repo/Recommender-Systems-[Netflix].pdf)| Netflix |
|     | 2008 | [Factorization Meets the Neighborhood: a Multifaceted Collaborative Filtering Model](https://dl.acm.org/doi/pdf/10.1145/1401890.1401944)| Netflix |
|     | 2008 | [Collaborative Filtering for Implicit Feedback Datasets](http://yifanhu.net/PUB/cf.pdf)| OCCF |
|     | 2012 | [BPR: Bayesian Personalized Ranking from Implicit Feedback](https://arxiv.org/ftp/arxiv/papers/1205/1205.2618.pdf)| BPR |
| 1/17| 2013 | [Translating Embeddings for Modeling Multi-relational Data](https://papers.nips.cc/paper/2013/hash/1cecc7a77928ca8133fa24680a88d2f9-Abstract.html)| TransE |
|     | 2017 | [Collaborative Metric Learning](https://www.cs.cornell.edu/~ylongqi/paper/HsiehYCLBE17.pdf)| CML |
|     | 2010 | [Factorization Machines](https://www.csie.ntu.edu.tw/~b97053/paper/Rendle2010FM.pdf)| FM |
| 1/24| |Holiday|| 
| 1/31| 2016 | [Wide & Deep Learning for Recommender Systems](https://arxiv.org/abs/1606.07792) | wide&deep|
|     | 2008 | [SoRec: Social Recommendation Using Probabilistic Matrix Factorization](https://dl.acm.org/doi/10.1145/1458082.1458205)| SoRec |
|     | 2011 | [Recommender Systems with Social Regularization](https://dennyzhou.github.io/papers/RSR.pdf)| SoReg |
|     | 2017 | [metapath2vec : Scalable Representation Learning for Heterogeneous Networks](https://dl.acm.org/doi/10.1145/3097983.3098036)| Metapath2Vec 
| 2/7 | 2018 | [Deep Graph Infomax](https://arxiv.org/abs/1809.10341)| DGI |
|     | 2017 | [Inductive Representation Learning on Large Graphs](https://papers.nips.cc/paper/2017/file/5dd9db5e033da9c6fb5ba83c7a7ebea9-Paper.pdf)| GraphSAGE |
|     | 2016 | [Variational Graph Auto-Encoders](https://arxiv.org/abs/1611.07308)| VGAE |
|     | 2013 | [Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114)| VAE |
| 2/14| 2016 | [Deep Neural Networks for YouTube Recommendations](https://static.googleusercontent.com/media/research.google.com/ko//pubs/archive/45530.pdf)| Youtube |
|     | 2015 | [AutoRec: Autoencoders Meet Collaborative Filtering](https://users.cecs.anu.edu.au/~akmenon/papers/autorec/autorec-paper.pdf)| Autorec |
|     | 2016 | [ConvMF: Convolutional Matrix Factorization for Document Context-Aware Recommendation](https://dsail.kaist.ac.kr/files/RecSys16_slide.pdf) | ConvMF | 
|     | 2022 | [AFGRL : Augmentation-Free Self-Supervised Learning on Graphs](https://arxiv.org/abs/2112.02472) | AFGRL | 
| 2/17|      | 개별연구 아이디어 발표 | |


<!--
### 참고 
|Random Walk 기반 방법 | 
| :--- |
| https://arxiv.org/pdf/1403.6652.pdf (Deepwalk) |
| https://arxiv.org/pdf/1607.00653.pdf (Node2vec) |
| https://arxiv.org/pdf/1503.03578.pdf (LINE) |
| https://ericdongyx.github.io/papers/KDD17-dong-chawla-swami-metapath2vec.pdf (metapath2vec) |

|Graph Neural Network 기반 방법|
|:---|
|Supervised|
|https://openreview.net/pdf?id=SJU4ayYgl (GCN)|
|https://arxiv.org/pdf/1710.10903.pdf (GAT)|
|Unsupervised|
|https://arxiv.org/abs/1809.10341 (DGI)|
|https://arxiv.org/abs/1611.07308 (GVAE)|
|https://arxiv.org/abs/1312.6114 (VAE)|
|Scalability 고려 : https://arxiv.org/pdf/1706.02216.pdf (GraphSAGE)|
|https://arxiv.org/abs/2112.02472 (AFGRL)|
|Knowledge graph embedding 방법|
|https://papers.nips.cc/paper/2013/file/1cecc7a77928ca8133fa24680a88d2f9-Paper.pdf (TransE)|

|Recommender System Paper | 
|:---|
|Explicit feedback|
|Matrix factorization 기반|
|https://dl.acm.org/doi/pdf/10.1145/1401890.1401944 (Netflix)|
|https://datajobs.com/data-science-repo/Recommender-Systems-[Netflix].pdf|
|https://papers.nips.cc/paper/2007/file/d7322ed717dedf1eb4e6e52a37ea7bcd-Paper.pdf (PMF)|
|Implicit feedback|
|Matrix factorization 기반|
|Point-wise method: http://yifanhu.net/PUB/cf.pdf (OCCF)|
|Pair-wise method: https://arxiv.org/pdf/1205.2618.pdf (BPR)|
|Metric learning 기반|
|http://www.cs.cornell.edu/~ylongqi/paper/HsiehYCLBE17.pdf (CML)|
|Neural network 기반|
|https://arxiv.org/pdf/1708.05031.pdf (NCF)|
|Side information (Social network)|
|http://web.cs.ucla.edu/~yzsun/classes/2014Spring_CS7280/Papers/Recommendation/paper_cikm08_sorec_hao.pdf (SoRec)|
|https://dennyzhou.github.io/papers/RSR.pdf (SoReg)|

|Deep learning based recommender system |
| :---|
|http://www.wanghao.in/paper/KDD15_CDL.pdf (CDL)|
|http://uclab.khu.ac.kr/resources/publication/C_351.pdf (ConvMF)|
|http://users.cecs.anu.edu.au/~u5098633/papers/www15.pdf (Autorec)|
|https://static.googleusercontent.com/media/research.google.com/ko//pubs/archive/45530.pdf (YouTube)|
|https://arxiv.org/abs/1606.07792 (wide&deep)|
|https://ieeexplore.ieee.org/document/5694074 (FM)|

|과거 랩인턴 archive|
|:---|
|https://github.com/DSAILatKAIST|
|Graph|
|https://github.com/thunlp/GNNPapers|
|https://github.com/thunlp/NRLPapers|
|Library (code)|
|https://pytorch-geometric.readthedocs.io/en/latest/|
|Many others… (Authors’ code, etc)|
|Recommender system|
|https://github.com/jihoo-kim/awesome-RecSys||
|Library (code)|
|https://github.com/NicolasHug/Surprise|
|Many others… (Authors’ code, etc)|

-->
