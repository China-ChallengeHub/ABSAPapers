# ABSAPapers
Must-read papers and related awesome resources on aspect-based sentiment analysis (ABSA). This repository mainly focused on aspect-term sentiment classification (ATSC). ABSA task contains five fine-grained subtasks:
- Aspect Term Sentiment Classification (ATSC)
- Aspect Term Extraction (ATE)
- Aspect Category Sentiment Classification (ACSC)
- Aspect Category Detection (ACD)
- Opniton Term Extraction (OTE)

Suggestions about adding papers, repositories and other resource are welcomed!

值得一读的方面级情感分析论文与相关资源集合。这里主要关注方面词（aspect-term）的情感分类。具体来说，方面级情感分析包括方面词情感分类、方面词抽取、方面类目情感分类、方面类目抽取、观点词抽取五个子任务。

欢迎新增论文、代码仓库与其他资源等建议！

## Paper
- Effective LSTMs for Target-Dependent Sentiment Classification (COLING 2016) [[paper]](https://www.aclweb.org/anthology/C16-1311)[[code]](https://drive.google.com/drive/folders/17RF8MZs456ov9MDiUYZp0SCGL6LvBQl6) - ***TD-LSTM TC-LSTM***
- Attention-based LSTM for Aspect-level Sentiment Classification (EMNLP 2016) [[paper]](https://aclweb.org/anthology/D16-1058) - ***ATAE-LSTM***
- A Hierarchical Model of Reviews for Aspect-based Sentiment Analysis (EMNLP 2016) [[paper]](https://arxiv.org/pdf/1609.02745.pdf) - ***H-LSTM***
- Aspect Level Sentiment Classification with Deep Memory Network (EMNLP 2016) [[paper]](https://www.aclweb.org/anthology/D16-1021)[[code]](https://drive.google.com/drive/folders/1Hc886aivHmIzwlawapzbpRdTfPoTyi1U) - ***MemNet***
- Interactive Attention Networks for Aspect-Level Sentiment Classification (IJCAI 2017) [[paper]](https://www.ijcai.org/proceedings/2017/0568.pdf) - ***IAN***
- Recurrent Attention Network on Memory for Aspect Sentiment Analysis (EMNLP 2017) [[paper]](https://www.aclweb.org/anthology/D17-1047)[[unofficial code]](https://github.com/lpq29743/RAM) - ***RAM***
- Attention Modeling for Targeted Sentimen (EACL 2017) [[paper]](https://www.aclweb.org/anthology/E17-2091/) - ***BiLSTM-ATT-G***
- Aspect-level Sentiment Classification with HEAT (HiErarchical ATtention) Network (CIKM 2017) [[paper]](https://dl.acm.org/citation.cfm?doid=3132847.3133037) - ***HEAT***
- Aspect Based Sentiment Analysis with Gated Convolutional Networks (ACL 2018) [[paper]](https://www.aclweb.org/anthology/P18-1234)[[code]](https://github.com/wxue004cs/GCAE) - ***GCAE***
- Target-Sensitive Memory Networks for Aspect Sentiment Classification (ACL 2018) [[paper]](https://www.aclweb.org/anthology/P18-1088/) - ***TMN***
- Transformation Networks for Target-Oriented Sentiment Classification (ACL 2018) [[paper]](https://aclweb.org/anthology/P18-1087)[[code]](https://github.com/lixin4ever/TNet) - ***TNet***
- Learning to Attend via Word-Aspect Associative Fusion for Aspect-Based Sentiment Analysis (AAAI 2018) [[paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16570/16162) - ***AF-LSTM***
- Targeted Aspect-Based Sentiment Analysis via Embedding Commonsense Knowledge into an Attentive LSTM (AAAI 2018) [[paper]](https://sentic.net/sentic-lstm.pdf)[[code]](https://github.com/SenticNet/sentic-lstm) - ***Sentic LSTM***
- A Position-aware Bidirectional Attention Network for Aspect-level Sentiment Analysis (COLING 2018) [[paper]](https://aclweb.org/anthology/C18-1066/)[[code]](https://github.com/hiyouga/PBAN-PyTorch) - ***PBAN***
- Enhanced Aspect Level Sentiment Classification with Auxiliary Memory (COLING 2018) [[paper]](https://www.aclweb.org/anthology/C18-1092/) - ***DAuM***
- Effective Attention Modeling for Aspect-Level Sentiment Classification (COLING 2018) [[paper]](https://www.aclweb.org/anthology/C18-1096/)
- Modeling Inter-Aspect Dependencies for Aspect-Based Sentiment Analysis (NAACL 2018) [[paper]](https://www.aclweb.org/anthology/N18-2043/)[[unofficial code]](https://github.com/xgy221/lstm-inter-aspect)
- Recurrent Entity Networks with Delayed Memory Update for Targeted Aspect-Based Sentiment Analysis (NAACL 2018) [[paper]](https://www.aclweb.org/anthology/N18-2045/) [[code]](https://github.com/liufly/delayed-memory-update-entnet)
- Content Attention Model for Aspect Based Sentiment Analysis (WWW 2018) [[paper]](https://dl.acm.org/citation.cfm?doid=3178876.3186001)[[code]](https://github.com/uestcnlp/Cabasc) - ***Cabasc***
- Aspect Level Sentiment Classification with Attention-over-Attention Neural Networks (SBP-BRiMS 2018) [[paper]](https://arxiv.org/pdf/1804.06536.pdf) - ***AOA***
- Aspect Sentiment Classification with both Word-level and Clause-level Attention Networks (IJCAI 2018) [[paper]](https://www.ijcai.org/proceedings/2018/0617)
- IARM: Inter-Aspect Relation Modeling with Memory Networks in Aspect-Based Sentiment Analysis (EMNLP 2018) [[paper]](https://aclweb.org/anthology/D18-1377/)[[code]](https://github.com/SenticNet/IARM) - ***IARM***
- Multi-grained Attention Network for Aspect-Level Sentiment Classification (EMNLP 2018) [[paper]](https://aclweb.org/anthology/D18-1380) - ***MGAN***
- Parameterized Convolutional Neural Networks for Aspect Level Sentiment Classification (EMNLP 2018) [[paper]](https://aclweb.org/anthology/D18-1136/) - ***PCNN***
- Left-Center-Right Separated Neural Network for Aspect-based Sentiment Analysis with Rotatory Attention [[paper]](https://arxiv.org/abs/1802.00892) - ***LCR-Rot***
- BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (NAACL 2019) [[paper]](https://www.aclweb.org/anthology/N19-1423/) - ***BERT-SPC***
- BERT Post-Training for Review Reading Comprehension and Aspect-based Sentiment Analysis  (NAACL 2019) [[paper]](https://www.aclweb.org/anthology/N19-1242)[[code]](https://github.com/howardhsu/BERT-for-RRC-ABSA) - ***BERT-PT***
- Utilizing BERT for Aspect-Based Sentiment Analysis via Constructing Auxiliary Sentence (NAACL 2019) [[paper]](https://www.aclweb.org/anthology/N19-1035/)[[code]](https://github.com/HSLCY/ABSA-BERT-pair)
- Attentional Encoder Network for Targeted Sentiment Classification (CoRR 2019) [[paper]](https://arxiv.org/pdf/1902.09314.pdf)[[code]](https://github.com/songyouwei/ABSA-PyTorch/blob/master/models/aen.py) - ***AEN-BERT***
- LCF: A Local Context Focus Mechanism for Aspect-Based Sentiment Classification (Applied Sciences 2019) [[paper]](https://www.mdpi.com/2076-3417/9/16/3389/pdf)[[code]](https://github.com/yangheng95/LCF-ABSA) - ***LCF-BERT***
- A Multi-task Learning Model for Chinese-oriented Aspect Polarity Classification and Aspect Term Extraction (CoRR 2019) [[paper]](https://arxiv.org/abs/1912.07976)[[code]](https://github.com/yangheng95/LCF-ATEPC) - ***LCF-ATEPC***
- A Novel Aspect-Guided Deep Transition Model for Aspect Based Sentiment Analysis (EMNLP 2019) [[paper]](https://arxiv.org/pdf/1909.00324.pdf)[[code]](https://github.com/XL2248/AGDT) - ***AGDT***
- Aspect-based Sentiment Classification with Aspect-specific Graph Convolutional Networks (ASGCN) [[paper]](https://arxiv.org/abs/1909.03477)[[code]](https://github.com/GeneZC/ASGCN) - ***ASGCN***
- CAN: Constrained Attention Networks for Multi-Aspect Sentiment (EMNLP 2019) [[paper]](https://arxiv.org/pdf/1812.10735.pdf) - ***CAN***
- Syntax-Aware Aspect-Level Sentiment Classification with Proximity-Weighted Convolution Network (SIGIR 2019) [[paper]](https://arxiv.org/abs/1909.10171)[[code]](https://github.com/GeneZC/PWCN) - ***PWCN***
- Adapt or Get Left Behind: Domain Adaptation through BERT Language Model Finetuning for Aspect-Target Sentiment Classification (CoRR 2019) [[paper]](https://arxiv.org/abs/1908.11860)[[code]](https://github.com/deepopinion/domain-adapted-atsc) - ***BERT-ADA***

### Multi-task Learning
Combining two or more ABSA's subtasks in one framework to produce results is an intutively effective way for industrial application. There are two patterns of multi-task learning: pipeline and joint model. For pipeline pattern, the framework complete subtasks in more than one step, using the result of last step to guide the next step's output, which might lead to error propogation problem. Joint model processes the data with shared layers to extract universal semantic features for all subtasks. Then model outputs results of different tasks through task-specific layers.

- MTNA: A Neural Multi-task Model for Aspect Category Classification and Aspect Term Extraction On Restaurant Reviews (IJCNLP 2017) [[paper]](https://www.aclweb.org/anthology/I17-2026/) - ***MTNA***
- Exploiting Coarse-to-Fine Task Transfer for Aspect-Level Sentiment Classification (AAAI 2019) [[paper]](https://www.aaai.org/ojs/index.php/AAAI/article/view/4332) - ***MGAN***
- A Unified Model for Opinion Target Extraction and Target Sentiment Prediction (AAAI 2019) [[paper]](https://aaai.org/ojs/index.php/AAAI/article/view/4643)[[code]](https://github.com/lixin4ever/E2E-TBSA) - ***E2E-TBSA***
- An Interactive Multi-Task Learning Network for End-to-End Aspect-Based Sentiment Analysis (ACL 2019) [[paper]](https://arxiv.org/abs/1906.06906)[[code]](https://github.com/ruidan/IMN-E2E-ABSA) - ***IMN-E2E-ABSA***
- DOER: Dual Cross-Shared RNN for Aspect Term-Polarity Co-Extraction (ACL 2019) [[paper]](https://www.aclweb.org/anthology/P19-1056/)[[code]](https://github.com/ArrowLuo/DOER) - ***DOER***
- Learning Explicit and Implicit Structures for Targeted Sentiment Analysis (EMNLP 2019) [[paper]](https://www.aclweb.org/anthology/D19-1550/)[[code]](https://github.com/leodotnet/ei) - ***EI***
- Exploiting BERT for End-to-End Aspect-based Sentiment Analysis (EMNLP 2019) [[paper]](https://www.aclweb.org/anthology/D19-5505/)[[code]](https://github.com/lixin4ever/BERT-E2E-ABSA) - ***BERT-E2E-ABSA***
- Transferable End-to-End Aspect-based Sentiment Analysis with Selective Adversarial Learning (EMNLP 2019) [[paper]](https://www.aclweb.org/anthology/D19-1466/)[[code]](https://github.com/hsqmlzno1/Transferable-E2E-ABSA) - ***Transferable-E2E-ABSA***
- Knowing What, How and Why: A Near Complete Solution for Aspect-based Sentiment Analysis (AAAI 2020) [[paper]](https://arxiv.org/abs/1911.01616)[[data]](https://github.com/xuuuluuu/SemEval-Triplet-data) - ***ASTE***
- Open-Domain Targeted Sentiment Analysis via Span-Based Extraction and Classification (ACL 2019) [[paper]](https://arxiv.org/abs/1906.03820)[[code]](https://github.com/huminghao16/SpanABSA) - ***SpanABSA***

### Document Level
- Document-Level Multi-Aspect Sentiment Classification as Machine Comprehension (EMNLP 2017) [[paper]](http://www.cse.ust.hk/~yqsong/papers/2017-EMNLP-AspectClassification.pdf)
- Document-level Multi-aspect Sentiment Classification by Jointly Modeling Users, Aspects, and Overall Ratings (COLING 2018) [[paper]](https://www.aclweb.org/anthology/C18-1079/) - ***HUARN***

## Dataset
- SemEval-2014 Task 4: Aspect Based Sentiment Analysis [[paper]](https://www.aclweb.org/anthology/S14-2004/)[[preprocessed data 1]](https://github.com/songyouwei/ABSAPyTorch/tree/master/datasets/semeval14)[[preprocessed data 2]](https://github.com/howardhsu/BERT-for-RRC-ABSA) - ***Restaurants14 & Laptop14***
- Adaptive Recursive Neural Network for Target-dependent Twitter Sentiment Classification (ACL 2014) [[paper]](https://www.aclweb.org/anthology/P14-2009)[[preprocessed data]](https://github.com/songyouwei/ABSA-PyTorch/tree/master/datasets/acl-14-short-data) - ***Twitter***
- SemEval-2015 Task 12: Aspect Based Sentiment Analysis [[paper]](https://www.aclweb.org/anthology/S15-2082/)[[data]](http://alt.qcri.org/semeval2015/task12/)
- SemEval-2016 Task 5: Aspect Based Sentiment Analysis [[paper]](https://www.aclweb.org/anthology/S16-1002/)[[data]](http://alt.qcri.org/semeval2016/task5/)
- SentiHood: Targeted Aspect Based Sentiment Analysis Dataset for Urban Neighbourhoods (COLING 2016) [[paper]](https://www.aclweb.org/anthology/C16-1146)[[data]](https://github.com/uclmr/jack/tree/master/data/sentihood) -  ***LSTM-LOC***
- Target-oriented Opinion Words Extraction with Target-fused Neural Sequence Labeling (NAACL 2019) [[paper]](https://www.aclweb.org/anthology/N19-1259/)[[data]](https://github.com/NJUNLP/TOWE) - ***TOWE***
- A Challenge Dataset and Effective Models for Aspect-Based Sentiment Analysis (EMNLP 2019) [[paper]](https://www.aclweb.org/anthology/D19-1654/)[[data]](https://github.com/siat-nlp/MAMS-for-ABSA) - ***MAMS***
### Normal Sentiment Analysis Dataset (More Coarse-grained)
- CLUEbenchmark/CLUEmotionAnalysis2020 [[data]](https://github.com/CLUEbenchmark/CLUEmotionAnalysis2020)

## Survey & Review & Tutorial
- Sentiment Analysis and Opinion Mining (AAAI 2011 Tutorial) [[slide]](https://www.seas.upenn.edu/~cis630/Sentiment-Analysis-tutorial-AAAI-2011.pdf)
- Deep Learning for Aspect-Based Sentiment Analysis: A Comparative Review (ESWA 2019) [[paper]](https://doi.org/10.1016/j.eswa.2018.10.003)
- Deep Learning for Aspect-Level Sentiment Classification: Survey, Vision, and Challenges (IEEE Access 2019) [[paper]](https://ieeexplore.ieee.org/document/8726353)

## Repositories/Resources
- [songyouwei/ABSA-PyTorch](https://github.com/songyouwei/ABSA-PyTorch)
- [AlexYangLi/ABSA_Keras](https://github.com/AlexYangLi/ABSA_Keras)
- [NUSTM/ABSC](https://github.com/NUSTM/ABSC)
- [jiangqn/Aspect-Based-Sentiment-Analysis](https://github.com/jiangqn/Aspect-Based-Sentiment-Analysis)
- [haiker2011/awesome-nlp-sentiment-analysis](https://github.com/haiker2011/awesome-nlp-sentiment-analysis)

## Blog
- [Kaiyuan Gao/基于特定实体的文本情感分类总结 [PART I]](https://blog.csdn.net/Kaiyuan_sjtu/article/details/89788314)[[PART II]](https://blog.csdn.net/Kaiyuan_sjtu/article/details/89811824)[[PART III]](https://blog.csdn.net/Kaiyuan_sjtu/article/details/89850685)
- [细粒度情感分析任务（ABSA）的最新进展](https://mp.weixin.qq.com/s/Jzra95XfjNtDDTNDMD8Lkw)
