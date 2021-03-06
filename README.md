# Awesome Graph & SSL-based Recommendation

 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![GitHub stars](https://img.shields.io/github/stars/juyongjiang/awesome-graph-self-supervised-learning-based-recommendation?color=yellow)  ![GitHub forks](https://img.shields.io/github/forks/juyongjiang/awesome-graph-self-supervised-learning-based-recommendation?color=green&label=Fork)  ![visitors](https://visitor-badge.glitch.me/badge?page_id=juyongjiang.awesome-graph-self-supervised-learning-based-recommendation)

A curated list of awesome Graph & Self-Supervised-Learning-based Recommendation resources. Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search), [awesome-self-supervised-learning](https://github.com/jason718/awesome-self-supervised-learning), [awesome-self-supervised-learning-for-graphs](https://github.com/SXKDZ/awesome-self-supervised-learning-for-graphs), and [GNNPapers](https://github.com/juyongjiang/GNNPapers).

## Introduction
With the explosive growth of the amount of information on the Internet, recommender systems play a crucial role to alleviate the problem of information overload. **The graph-based recommendation is a promising method to capture users' dynamic preferences and complex transitions of items in realistic scenarios**. Besides, to eliminate the problem of label scarcity, self-supervised learning (SSL) has been attracted a lot of research attention and achieved remarkable successes in various fields, e.g. visual, natural language processing, and robotics. However, the development of SSL in the recommendation domain is still at a nascent stage. Moreover, due to the complexity of users' dynamic interest patterns and item's various attributes, constructing applicative self-supervision signals can extract more meaningful user behavior patterns and further encode the user and item representations effectively. This vibrant research direction is termed self-supervised learning-based recommendation. This repository provides you with a curated list of awesome Graph & Self-Supervised-Learning-based Recommendation resources. 

## Contributing

Please, feel free to send [pull requests](https://github.com/juyongjiang/awesome-graph-based-recommendation/pulls) to add more resources!

Markdown Format:

```markdown
- Paper Name. [[PDF]](link) [[Code]](link)
  Author 1, Author 2, and Author 3. 
  *Conference Year*
```

## Table of Contents

* [Graph-based Recommendation](#papers)
  * [Surveys](#surveys) | [2021](#2021) | [2020](#2020) | [2019](#2019) | [2018-](#2018)
* [SSL-based Recommendation](#SSL-based-Recommendation)
  * [2021](#2021) | [2020](#2020)

## Graph-based Recommendation

### Surveys
* Graph Neural Networks for Recommender Systems: Challenges, Methods, and Directions [[PDF]](https://arxiv.org/abs/2109.12843)
  
  Chen Gao, Yu Zheng, Nian Li, Yinfeng Li, Yingrong Qin, Jinghua Piao, Yuhan Quan, Jianxin Chang, Depeng Jin, Xiangnan He, Yong Li

  *TOIS 2021*

* Graph Learning based Recommender Systems: A Review [[PDF]](https://arxiv.org/abs/2105.06339)

  Shoujin Wang, Liang Hu, Yan Wang, Xiangnan He, Quan Z. Sheng, Mehmet A. Orgun, Longbing Cao, Francesco Ricci, Philip S. Yu

  *IJCAI 2021*

* Graph Neural Networks in Recommender Systems: A Survey [[PDF]](https://arxiv.org/abs/2011.02260)

  Shiwen Wu, Fei Sun, Wentao Zhang, Bin Cui

  *arXiv 2020*  

* A Survey on Knowledge Graph-Based Recommender Systems [[PDF]](https://arxiv.org/abs/2003.00911)

  Qingyu Guo, Fuzhen Zhuang, Chuan Qin, Hengshu Zhu, Xing Xie, Hui Xiong, Qing He

  *arXiv 2020*

* A Comprehensive Survey on Graph Neural Networks [[PDF]](https://ieeexplore.ieee.org/abstract/document/9046288)

  Wu, Zonghan, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, and S. Yu Philip
  
  *IEEE Transactions on Neural Networks and Learning Systems 2020*

### 2021
* HCGR: Hyperbolic Contrastive Graph Representation Learning for Session-based Recommendation [[PDF]](https://arxiv.org/abs/2107.05366)

  Naicheng Guo, Xiaolei Liu, Shaoshuai Li, Qiongxu Ma, Yunan Zhao, Bing Han, Lin Zheng, Kaixin Gao, Xiaobo Guo

  *arXiv 2021*

* Self-Supervised Graph Co-Training for Session-based Recommendation [[PDF]](https://arxiv.org/abs/2108.10560)

  Xin Xia, Hongzhi Yin, Junliang Yu, Yingxia Shao, Lizhen Cui

  *CIKM 2021*

* Self-supervised Graph Learning for Recommendation [[PDF]](https://dl.acm.org/doi/abs/10.1145/3404835.3462862?casa_token=FRle0kG9Q1oAAAAA:MnrL-4zDJHIXlPxilVgSZ8d24i1t7SaEOIeSMvPa0q5Z3RavCzitttSBNgqj6CTwiizd5bN3EHsbqQ)

  Wu, Jiancan, Xiang Wang, Fuli Feng, Xiangnan He, Liang Chen, Jianxun Lian, and Xing Xie.

  *SIGIR 2021* 

* Sequential Recommendation with Graph Neural Networks [[PDF]](https://dl.acm.org/doi/abs/10.1145/3404835.3462968?casa_token=oEK41kDW83MAAAAA:dimSPuv3CybEDXEDOVICgK-NSG1YHBjHKlEGTnjdOS-NyxcEYWtcziBJx8XO1hpYLvezmT_Uj42NLg)

  Chang, Jianxin, Chen Gao, Yu Zheng, Yiqun Hui, Yanan Niu, Yang Song, Depeng Jin, and Yong Li.

  *SIGIR 2021* 

* Self-Supervised Hypergraph Convolutional Networks for Session-based Recommendation [[PDF]](https://www.aaai.org/AAAI21Papers/AAAI-1889.XiaX.pdf)
  
  Xia, Xin, Hongzhi Yin, Junliang Yu, Qinyong Wang, Lizhen Cui, and Xiangliang Zhang

  *AAAI 2021*

* Self-Supervised Multi-Channel Hypergraph Convolutional Network for Social Recommendation [[PDF]](https://arxiv.org/abs/2101.06448)
  
  Yu, Junliang, Hongzhi Yin, Jundong Li, Qinyong Wang, Nguyen Quoc Viet Hung, and Xiangliang Zhang
  
  *WWW 2021*

### 2020
* Handling Information Loss of Graph Neural Networks for Session-based Recommendation [[PDF]](https://dl.acm.org/doi/abs/10.1145/3394486.3403170)
  
  Chen, Tianwen, and Raymond Chi-Wing Wong

  *KDD 2020*

* Global context enhanced graph neural networks for session-based recommendation [[PDF]](https://dl.acm.org/doi/abs/10.1145/3397271.3401142)

  Wang, Ziyang, Wei Wei, Gao Cong, Xiao-Li Li, Xian-Ling Mao, and Minghui Qiu

  *SIGIR 2020*

* Target Attentive Graph Neural Networks for Session-based Recommendation [[PDF]](https://dl.acm.org/doi/abs/10.1145/3397271.3401319?casa_token=kEkjeK1SBdoAAAAA:CQKK0j96jDleXCgo7CEkTFMwbDk0llKbxvFtsyCDAbFdcQavKTuoMCfXOv2ds6ntePz9h4nUcUMyfA)

  Yu, Feng, Yanqiao Zhu, Qiang Liu, Shu Wu, Liang Wang, and Tieniu Tan

  *SIGIR 2020* 

* Beyond Clicks: Modeling Multi-Relational Item Graph for Session-Based Target Behavior Prediction [[PDF]](https://dl.acm.org/doi/abs/10.1145/3366423.3380077)
  
  Wang, Wen, Wei Zhang, Shukai Liu, Qi Liu, Bo Zhang, Leyu Lin, and Hongyuan Zha

  *WWW 2020*

* Global Context Enhanced Graph Neural Networks for Session-based Recommendation [[PDF]](https://dl.acm.org/doi/abs/10.1145/3397271.3401142)
  
  Wang, Ziyang, Wei Wei, Gao Cong, Xiao-Li Li, Xian-Ling Mao, and Minghui Qiu
  
  *SIGIR 2020*

* Handling Information Loss of Graph Neural Networks for Session-based Recommendation [[PDF]](https://dl.acm.org/doi/abs/10.1145/3394486.3403170)
  
  Chen, Tianwen, and Raymond Chi-Wing Wong

  *KDD 2020*

* Learning Graph-Based Geographical Latent Representation for Point-of-Interest Recommendation [[PDF]](https://dl.acm.org/doi/abs/10.1145/3340531.3411905?casa_token=9nEwYQRns64AAAAA:Sc45Ih6SmlLLR5FybQnaoWEhUWbX2amHjycLd9v0-9PC6dpP10sRfHMWDstwiCgVbSykesptA6Sa9Q)
  
  Chang, Buru, Gwanghoon Jang, Seoyoon Kim, and Jaewoo Kang
  
  *CIKM 2020*

* GAME: Learning Graphical and Attentive Multi-View Embeddings for Occasional Group Recommendation [[PDF]](https://dl.acm.org/doi/abs/10.1145/3397271.3401064?casa_token=SGXsdJPPgLcAAAAA:ZlbfcT5rgFXTG5TD9f996nWiJzqx1dhU9e98dfcxt2wnbYYUTd5w-2XMkskfA_Hapc1QvwkvSSGFpw)
  
  He, Zhixiang, Chi-Yin Chow, and Jia-Dong Zhang
  
  *SIGIR 2020*

* Bundle Recommendation with Graph Convolutional Networks [[PDF]](https://dl.acm.org/doi/abs/10.1145/3397271.3401198?casa_token=4f-c4LLYz-UAAAAA:zHgLI761osy0hBzhTZTntH7VTWG-YJVdsuo9XDo9X-WXKqvXyJt2qHTMt3D8FTUxscg4Jwm9qf5S4A)
  
  Chang, Jianxin, Chen Gao, Xiangnan He, Depeng Jin, and Yong Li
  
  *SIGIR 2020*

* LightGCN: Simplifying and Powering Graph Convolution Network for Recommendation [[PDF]](https://dl.acm.org/doi/abs/10.1145/3397271.3401063?casa_token=DjPwZ2sW-zoAAAAA:3mYmUvAJcXlcctAA36I5or7zSgkrn7gfZbnSe7Pw0Wl-aiBR6AaF4ydxvPByqVq4Sbnzef9xalBs-Q)

  He, Xiangnan, Kuan Deng, Xiang Wang, Yan Li, Yongdong Zhang, and Meng Wang

  *SIGIR 2020*  

* Memory Augmented Graph Neural Networks for Sequential Recommendation [[PDF]](https://arxiv.org/abs/1912.11730)

  Chen Ma, Liheng Ma, Yingxue Zhang, Jianing Sun, Xue Liu, Mark Coates
    
  *AAAI 2020*

* Revisiting Graph based Collaborative Filtering: A Linear Residual Graph Convolutional Network Approach [[PDF]](https://arxiv.org/abs/2001.10167)

  Lei Chen, Le Wu, Richang Hong, Kun Zhang, Meng Wang

  *AAAI 2020*

* Inductive Matrix Completion Based on Graph Neural Networks [[PDF]](https://openreview.net/pdf?id=ByxxgCEYDS)

  Muhan Zhang, Yixin Chen

  *ICLR 2020*

### 2019
* Rethinking the Item Order in Session-based Recommendation with Graph Neural Networks [[PDF]](https://dl.acm.org/doi/abs/10.1145/3357384.3358010)

  Qiu, Ruihong, Jingjing Li, Zi Huang, and Hongzhi Yin
  
  *CIKM 2019*

* Graph Contextualized Self-Attention Network for Session-based Recommendation [[PDF]](https://www.ijcai.org/proceedings/2019/0547.pdf)

  Xu, Chengfeng, Pengpeng Zhao, Yanchi Liu, Victor S. Sheng, Jiajie Xu, Fuzhen Zhuang, Junhua Fang, and Xiaofang Zhou

  *IJCAI 2019*

* Rethinking the Item Order in Session-based Recommendation with Graph Neural Networks [[PDF]](https://dl.acm.org/doi/abs/10.1145/3357384.3358010)
  
  Qiu, Ruihong, Jingjing Li, Zi Huang, and Hongzhi Yin

  *CIKM 2019*

* A Neural Influence Diffusion Model for Social Recommendation [[PDF]](https://dl.acm.org/doi/abs/10.1145/3331184.3331214?casa_token=rXDSv_bfKHsAAAAA:w9OmqhkuU57AmU8oJBpp1mdN3rIvqkj-XAJUIWIvr5jkhzTBED3klzjIFIyGnXTkaOeIB_TL1wGQug)
  
  Wu, Le, Peijie Sun, Yanjie Fu, Richang Hong, Xiting Wang, and Meng Wang
  
  *SIGIR 2019*

* Graph Neural Networks for Social Recommendation [[PDF]](https://dl.acm.org/doi/abs/10.1145/3308558.3313488?casa_token=Oqb0f6E-yGQAAAAA:mhyP-YkXKLmawvlG2UitqRJZJKNEGc-GzgEdQdz9ziXs-q-XOX46MerL-S3oU1X5H5Njr_1lyw5E9w) 
  
  Fan, Wenqi, Yao Ma, Qing Li, Yuan He, Eric Zhao, Jiliang Tang, and Dawei Yin.
  
  *WWW 2019*

* Knowledge Graph Convolutional Networks for Recommender Systems [[PDF]](https://arxiv.org/pdf/1904.12575.pdf)
  
  Wang, Hongwei, Miao Zhao, Xing Xie, Wenjie Li, and Minyi Guo.
  
  *WWW 2019*

* KGAT: Knowledge Graph Attention Network for Recommendation [[PDF]](https://dl.acm.org/doi/abs/10.1145/3292500.3330989?casa_token=X6F5RJQDWIwAAAAA:d8PwY9yDUZkdl1u4gNARWqDKPtogisYcJpPPe7LdFqcO9ohUplOVZQO-p6WEORu-QTnkSq6LWH6Nog)
  
  Wang, Xiang, Xiangnan He, Yixin Cao, Meng Liu, and Tat-Seng Chua
  
  *KDD 2019*

* Graph contextualized self-attention network for session-based recommendation [[PDF]](https://www.ijcai.org/proceedings/2019/0547.pdf)
  
  Xu, Chengfeng, Pengpeng Zhao, Yanchi Liu, Victor S. Sheng, Jiajie Xu, Fuzhen Zhuang, Junhua Fang, and Xiaofang Zhou
  
  *IJCAI 2019*

* Session-based social recommendation via dynamic graph attention networks [[PDF]](https://dl.acm.org/doi/abs/10.1145/3289600.3290989?casa_token=N0cXXM9E4xAAAAAA:DGJ3rk-3beY9y4rQR3G24spfu1-yjw2uebCSmQ9zReKwQeNVG2P7HA3E0PPZrFOAW8qzlcHnM08Z-g)
  
  Song, Weiping, Zhiping Xiao, Yifan Wang, Laurent Charlin, Ming Zhang, and Jian Tang
  
  *WSDM 2019*

* Fi-GNN: Modeling Feature Interactions via Graph Neural Networks for CTR Prediction [[PDF]](https://dl.acm.org/doi/abs/10.1145/3357384.3357951?casa_token=05Y0DQkIHiUAAAAA:TpejXzub-RaxAh_mMMH_cK0q5TbVRaSZa4HGg8BHMEmotDNeQZkOnZqq_wzruwKyNh4_1dWvXGRIkQ) 
  
  Li, Zekun, Zeyu Cui, Shu Wu, Xiaoyu Zhang, and Liang Wang

  *WWW 2019*

*  Neural Graph Collaborative Filtering [[PDF]](https://dl.acm.org/doi/abs/10.1145/3331184.3331267?casa_token=AWNqcjAeFo0AAAAA:YUgQdSPWZOGycyT3Qh7T7GWr7NPR9-nY7G-0efjP9Tg6tAxCsw_m-PFqeSFhd44PZ9JGTwekxlPYig)
   
   Wang, Xiang, Xiangnan He, Meng Wang, Fuli Feng, and Tat-Seng Chua
   
   *SIGIR 2019*  

* STAR-GCN: Stacked and Reconstructed Graph Convolutional Networks for Recommender Systems [[PDF]](https://arxiv.org/pdf/1905.13129.pdf)
  
  Jiani Zhang, Xingjian Shi, Shenglin Zhao, Irwin King
  
  *IJCAI 2019*

* Binarized Collaborative Filtering with Distilling Graph Convolutional Networks [[PDF]](https://arxiv.org/pdf/1906.01829.pdf)
  
  Haoyu Wang, Defu Lian, Yong Ge
  
  *IJCAI 2019*

* Graph Contextualized Self-Attention Network for Session-based Recommendation [[PDF]](https://www.ijcai.org/proceedings/2019/0547.pdf)
  
  Chengfeng Xu, Pengpeng Zhao, Yanchi Liu, Victor S. Sheng, Jiajie Xu, Fuzhen Zhuang, Junhua Fang, Xiaofang Zhou

  *IJCAI 2019*

* Session-based Recommendation with Graph Neural Networks. [[PDF]](https://arxiv.org/pdf/1811.00855.pdf)

  Shu Wu, Yuyuan Tang, Yanqiao Zhu, Liang Wang, Xing Xie, Tieniu Tan
  
  *AAAI 2019* 

* Geometric Hawkes Processes with Graph Convolutional Recurrent Neural Networks. [[PDF]](https://jshang2.github.io/pubs/geo.pdf)

  Jin Shang, Mingxuan Sun

  *AAAI 2019*

* Knowledge-aware Graph Neural Networks with Label Smoothness Regularization for Recommender Systems [[PDF]](https://arxiv.org/pdf/1905.04413)

  Hongwei Wang, Fuzheng Zhang, Mengdi Zhang, Jure Leskovec, Miao Zhao, Wenjie Li, Zhongyuan Wang
  
  *KDD 2019*

* Exact-K Recommendation via Maximal Clique Optimization [[PDF]](https://arxiv.org/pdf/1905.07089)

  Yu Gong, Yu Zhu, Lu Duan, Qingwen Liu, Ziyu Guan, Fei Sun, Wenwu Ou, Kenny Q. Zhu
  
  *KDD 2019*

* KGAT: Knowledge Graph Attention Network for Recommendation [[PDF]](https://arxiv.org/pdf/1905.07854)

  Xiang Wang, Xiangnan He, Yixin Cao, Meng Liu, Tat-Seng Chua

  *KDD 2019*
    
* Knowledge Graph Convolutional Networks for Recommender Systems [[PDF]](https://arxiv.org/pdf/1904.12575.pdf)

  Hongwei Wang, Miao Zhao, Xing Xie, Wenjie Li, Minyi Guo
  
  *WWW 2019* 
    
* Dual Graph Attention Networks for Deep Latent Representation of Multifaceted Social Effects in Recommender Systems [[PDF]](https://arxiv.org/pdf/1903.10433.pdf)

  Qitian Wu, Hengrui Zhang, Xiaofeng Gao, Peng He, Paul Weng, Han Gao, Guihai Chen

  *WWW 2019* 
    
* Graph Neural Networks for Social Recommendation [[PDF]](https://arxiv.org/pdf/1902.07243.pdf)

  Wenqi Fan, Yao Ma, Qing Li, Yuan He, Eric Zhao, Jiliang Tang, Dawei Yin
  
  *WWW 2019* 

### 2018-
* Graph Convolutional Neural Networks for Web-Scale Recommender Systems [[PDF]](https://arxiv.org/abs/1806.01973)

  Rex Ying, Ruining He, Kaifeng Chen, Pong Eksombatchai, William L. Hamilton, Jure Leskovec

  *KDD 2018* 

* Geometric Matrix Completion with Recurrent Multi-Graph Neural Networks [[PDF]](https://arxiv.org/abs/1704.06803)

  Federico Monti, Michael M. Bronstein, Xavier Bresson

  *NIPS 2017*

* Graph Convolutional Matrix Completion [[PDF]](https://arxiv.org/abs/1706.02263)

  Rianne van den Berg, Thomas N. Kipf, Max Welling

  *arXiv 2017*

## SSL-based-Recommendation
### 2021
* Self-supervised on Graphs: Contrastive, Generative, or Predictive. [[PDF]](https://arxiv.org/abs/2105.07342)
  
  Lirong Wu, Haitao Lin, Zhangyang Gao, Cheng Tan, Stan.Z.Li

  *arXiv 2021*

* Contrastive Learning for Recommender System [[PDF]](https://arxiv.org/abs/2101.01317)
  
  Zhuang Liu, Yunpu Ma, Yuanxin Ouyang, Zhang Xiong
  
  *arXiv 2021*

* Contrastive Learning for Sequential Recommendation [[PDF]](https://arxiv.org/abs/2010.14395)
  
  Xu Xie, Fei Sun, Zhaoyang Liu, Shiwen Wu, Jinyang Gao, Bolin Ding, Bin Cui
  
  *arXiv 2021*

* Contrastive Self-supervised Sequential Recommendation with Robust Augmentation [[PDF]](https://arxiv.org/abs/2108.06479)
  
  Zhiwei Liu, Yongjun Chen, Jia Li, Philip S. Yu, Julian McAuley, Caiming Xiong
  
  *arXiv 2021*

* Pattern-enhanced Contrastive Policy Learning Network for Sequential Recommendation [[PDF]](https://www.ijcai.org/proceedings/2021/0220.pdf)
  
  Tong, Xiaohai, Pengfei Wang, Chenliang Li, Long Xia, and Shaozhang Niu
  
  *IJCAT 2021*

### 2020
* Self-supervised learning on graphs: Deep insights and new direction [[PDF]](https://arxiv.org/abs/2006.10141)
  
  Wei Jin, Tyler Derr, Haochen Liu, Yiqi Wang, Suhang Wang, Zitao Liu, Jiliang Tang

  *arXiv 2020*

* S3-Rec: Self-Supervised Learning for Sequential Recommendation with Mutual Information Maximization [[PDF]](https://dl.acm.org/doi/abs/10.1145/3340531.3411954?casa_token=q2q66TG21UoAAAAA:coz8SYHu25USUEnSYYMfOosX_dUemCqTOIGdVnuJ_9at5cA5NImR5ofLEpdzgE_g6Wii1SZl6diFFg)
  
  Zhou, Kun, Hui Wang, Wayne Xin Zhao, Yutao Zhu, Sirui Wang, Fuzheng Zhang, Zhongyuan Wang, and Ji-Rong Wen.
  
  *CIKM 2020*

* Self-supervised Learning for Large-scale Item Recommendations [[PDF]](https://arxiv.org/pdf/2007.12865.pdf)
  
  Yao, Tiansheng, et al. 
  
  *arXiv 2020*