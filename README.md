# ad-reading

computational advertising reading list (计算广告阅读）

## 目录

#### Basics (计算广告基础）
- [斯坦福计算广告公开课](http://web.stanford.edu/class/msande239/)：由计算广告之父，Yahoo广告首席科学家[Andrei Broder](https://en.wikipedia.org/wiki/Andrei_Broder)开设。
- [《计算广告》](https://book.douban.com/subject/26596778/)：360高级总监刘鹏著，通俗易懂，计算广告入门推荐。*2015*

#### Architect (计算广告架构)
- [美团机器学习@吃喝玩乐中的算法问题](./architect/美团机器学习_吃喝玩乐中的算法问题.pdf)：美团王栋博士的一篇关于美团机器学习相关问题的介绍，介绍的比较全但比较粗浅，可以借此了解美团的一些机器学习问题。*2016-11*

#### CTR Prediction (点击率预估)
- [Image Matters: Visually modeling user behaviors using Advanced Model Server](./ctr/DeepImageCTR.pdf):使用推荐商品图片和历史商品图片学习embedding作为特征进行推荐。 *2018-09*
- [Deep Interest Network for Click-Through Rate Prediction](./ctr/DIN.pdf):候选商品与历史商品做注意力模型。 *2018-09*
- [xDeepFM: Combining Explicit and Implicit Feature Interactions for Recommender Systems](./ctr/xDeepFM.pdf):同DeepFM，本文中使用向量外积，采用卷积。 *2018-05*
- [Deep & Cross Network for Ad Click Predictions](./ctr/DCN.pdf):谷歌实习生搞的隐层与输入层做交叉。 *2017-08*
- [DeepFM: A Factorization-Machine based Neural Network for CTR Prediction](./ctr/DeepFM.pdf):输入层考虑二阶特征交叉。 *2017-03*
- [Learning Tree-based Deep Model for Recommender Systems](./ctr/treeDNN.pdf): 阿里盖坤团队的深层树结构检索模型。*2018-01*
- [Deep Neural Networks for YouTube Recommendations](./ctr/Deep%20Neural%20Networks%20for%20YouTube%20Recommendations.pdf)：Youtube推荐模型，京东也使用这一套DNN的模型。*2016-09*
- [Wide & Deep Learning for Recommender Systems](./ctr/WideDeep.pdf):考虑特征记忆与泛化性能。 *2016-06*
- [Practical Lessons from Predicting Clicks on Ads at Facebook](./ctr/Practical%20Lessons%20from%20Predicting%20Clicks%20on%20Ads%20at%20Facebook.pdf)：Facebook的一篇非常出名的文章，GBDT＋LR/FM解决CTR预估问题，工程性很强，海量离散特征+简单线性模型 对抗 少量连续特征+复杂深度模型。*2014-08*
- [Ad Click Prediction: a View from the Trenches](./ctr/41159.pdf): 应用性很强的一篇来自于Google Search Ads的文章，对于稀疏特征，内存，特征可视化，Calibration等都有介绍。*2013-08*

#### CVR Prediction (转化率预估)
- [Entire Space Multi-Task Model: An Effective Approach for Estimating Post-Click Conversion Rate](./cvr/ali_cvr.pdf):ctr模型和cvr模型做multi-task learning，共享底部全联接层。 *2018-04*
- [Modeling Delayed Feedback in Display Advertising](./cvr/delayedConv.pdf): 前雅虎现Google的广告大牛Olivier的一篇关于转化率预估的文章，转化率预估分为点击率预估和转化时间预估两个模型，其中用survival analysis来刻画转化时间。通俗易懂。*2014-08*

#### Feature Engineering (特征工程)
- [特征哈希](./ctr/shi09a.pdf)：将原始特征哈希到定长的hash list，这样特征的维度就固定了。*2009*

#### NLP (NLP在广告中的应用)
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](./nlp/bert.pdf):谷歌的划时代的NLP模型。 *2018-10*
- [Real-time Personalization using Embeddings for Search Ranking at Airbnb](./nlp/airbnb_emb.pdf):2018 kdd best paper，同时考虑点击和转化，embedding的系统评估。 *2018-08*
- [Billion-scale Commodity Embedding for E-commerce Recommendation in Alibaba](./nlp/ali_emb.pdf):同为2018 kdd上的文章，介绍了基于graph学习embedding，使用特征解决冷启动问题。 *2018-08*
- [Enriching Word Vectors with Subword Information](./nlp/fasttext.pdf):基于word2vec，考虑了词缀的因素。 *2017-06*
- [Distributed Representations of Words and Phrases and their Compositionality](./nlp/word2vec.pdf):划时代的NLP模型。 *2013-10*

#### Offline Evaluation (离线评估)
- [AUC的介绍和计算](./offline_eval/auc.pdf):AUC的介绍和计算。
- [推荐系统评价指标综述](./offline_eval/metrics.pdf)：推荐系统常用的衡量指标，包括逆序比，NDCG，新颖性等相似概念。*2012*

#### Allocation (分流)
- [Ad Serving Using a Compact Allocation Plan](Ad%20Serving%20Using%20a%20Compact%20Allocation%20Plan.pdf)：雅虎的一篇比较经典的流量分配的文章，文中的HWM和DUAL算法都比较实用。*2012-03*

#### Bidding Strategy（广告定价）
- [Optimized Cost per Click in Taobao Display Advertising](./bidding/ocpc.pdf):从最优化广告主ROI出发，计算bidding的上下界。 *2017-08*
- [Research Frontier of Real-Time Bidding based Display Advertising](./bidding/Research%20Frontier%20of%20Real-Time%20Bidding%20based%20Display%20Advertising.pdf)：张伟楠博士的一篇介绍竞价算法的ppt，可以非常清晰的了解该问题的主要方法。*2015*

#### Reinforce Learning (强化学习的应用)
- [Learning To Teach](./rl/l2t.pdf)：微软亚研院在ICLR上关于teacher student网络，用teacher为student网络提供数据，loss，函数形式的指导的方法。*2018*

## 参考资料
- [王喆的github列表](https://github.com/wzhe06/Ad-papers)
