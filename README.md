# MT-paper-list-of-ACL
This is a reading list of papers related to machine translation in ACL from 2016 to 2021.

We made a classification about machine translation, and sorted the papers according to the classification. And we also collected the interpretations of papers published in WeChat official account, Zhihu, CSDN and bilibili, and put them in the list. Of course, our classification may not be accurate, and related conference papers are incomplete. We will continuously update and improve the list. Welcome to provide comments and suggestions!

**[List by Conference](#list-by-conference)**

  - [ACL](#ACL)

    - [2016](#2016)

    - [2017](#2017)

    - [2018](#2018)

    - [2019](#2019)

    - [2020](#2020)

    - [2021](#2021)

**[List by Area](#list-by-area)**

  - [Statistical Machine Translation](#StatisticalMachineTranslation)

    - [Word-based Models](#Word-basedModels)

    - [Distortion-based and Fertility-based models](#Distortion-basedandFertility-basedmodels)

    - [Phrase-based Models](#Phrase-basedModels)

    - [Syntax-based Models](#Syntax-basedModels)

  - [Evaluation](#Evaluation)

    - [Reference-based](#Reference-based)

    - [Reference-free](#Reference-free)

  - [Efficiency](#Efficiency)

    - [Model Compression](#ModelCompression)

      - [Pruning](#Pruning)

      - [Knowledge Distillation](#KnowledgeDistillation)

      - [Quantization](#Quantization)

      - [Low-rank Factorization](#Low-rankFactorization)

      - [Weight Sharing](#WeightSharing)

    - [Compution Optimization](#ComputionOptimization)

    - [Energy Cost](#EnergyCost)

    - [Conditional Computation](#ConditionalComputation)

  - [Open-source Systems and Datasets](#Open-sourceSystemsandDatasets)

  - [Training Strategy](#TrainingStrategy)

    - [Contrastive Learning](#ContrastiveLearning)

    - [Reinforcement Learning](#ReinforcementLearning)

    - [Meta Learning](#MetaLearning)

    - [Dual Learning](#DualLearning)

    - [Generative Adversarial Networks](#GenerativeAdversarialNetworks)

  - [Inference](#Inference)

    - [Non-autoregressive](#Non-autoregressive)

    - [Constrained Inference](#ConstrainedInference)

      - [Interactive NMT](#InteractiveNMT)

      - [Automatic Post-Editing](#AutomaticPost-Editing)

      - [Restricted NMT](#RestrictedNMT)

    - [Beam Search](#BeamSearch)

  - [Interpretability](#Interpretability)

  - [Ensemble](#Ensemble)

  - [Reranking](#Reranking)

  - [Model Architecture](#ModelArchitecture)

  - [Prior Knowledge](#PriorKnowledge)

  - [Attention Mechanism](#AttentionMechanism)

  - [Domain Adaptation](#DomainAdaptation)

  - [Transfer Learning](#TransferLearning)

  - [Pre-training](#Pre-training)

  - [Diversity and Fairness](#DiversityandFairness)

  - [Robustness](#Robustness)

  - [Data-based Methods](#Data-basedMethods)

    - [Word Segmentation](#WordSegmentation)

    - [Character-level NMT](#Character-levelNMT)

    - [Data Augmentation](#DataAugmentation)

    - [Schedule Strategy](#ScheduleStrategy)

      - [Data Selection](#DataSelection)

      - [Curriculum Learning](#CurriculumLearning)

  - [Low-resource NMT](#Low-resourceNMT)

    - [Unsupervised NMT](#UnsupervisedNMT)

    - [Semi-supervised NMT](#Semi-supervisedNMT)

    - [Endangered Language Study](#EndangeredLanguageStudy)

  - [Multilingual NMT](#MultilingualNMT)

  - [Document-level NMT](#Document-levelNMT)

  - [Real-time NMT](#Real-timeNMT)

  - [Multimodal NMT](#MultimodalNMT)

    - [Speech](#Speech)

      - [Cascaded Speech Translation](#CascadedSpeechTranslation)

      - [End-to-End Speech Translation](#End-to-EndSpeechTranslation)

    - [Image](#Image)

  - [WMT](#WMT)

    - [Efficiency](#Efficiency)

    - [Quality Estimation](#Quality Estimation)

    - [News Translation](#NewsTranslation)

  - [Survey](#Survey)

## List by Conference

### ACL

#### 2016

1. **Models and Inference for Prefix-Constrained Machine Translation.** [paper](https://aclanthology.org/P16-1007)

    *Joern Wuebker, Spence Green, John DeNero, Saša Hasan, Minh-Thang Luong*

    **Domain**: Inference → Constrained Inference → Interactive NMT

2. **Modeling Coverage for Neural Machine Translation.** [paper](https://aclanthology.org/P16-1008/)

    *Zhaopeng Tu, Zhengdong Lu, Yang Liu, Xiaohua Liu, Hang Li*

    **Domain**: Attention Mechanism

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/wnYGIbEuQ3QHQ8X5ElaVoA) ; [Paper Reading&Interpretation2](https://mp.weixin.qq.com/s/kmS8CewYOyEHD_MHolfihw) ; [Paper Reading&Interpretation3](https://blog.csdn.net/u011414416/article/details/51567254) ; [Paper Reading&Interpretation4](https://zhuanlan.zhihu.com/p/22993927)

3. **Improving Neural Machine Translation Models with Monolingual Data.** [paper](https://aclanthology.org/P16-1009/)

    *Rico Sennrich, Barry Haddow, Alexandra Birch*

    **Domain**: Data-based Methods → Data Augmentation

    [Paper Reading&Interpretation1](https://blog.csdn.net/feifei3211/article/details/103344445?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/330866548)

4. **Pointing the Unknown Words.** [paper](https://aclanthology.org/P16-1014/)

    *Caglar Gulcehre, Sungjin Ahn, Ramesh Nallapati, Bowen Zhou, Yoshua Bengio*

    **Domain**: Model Architecture

    [Paper Reading&Interpretation1](https://blog.csdn.net/sanra123/article/details/87917588?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/36368316) ; [Paper Reading&Interpretation3](https://zhuanlan.zhihu.com/p/73590690)

5. **Tree-to-Sequence Attentional Neural Machine Translation.** [paper](https://aclanthology.org/P16-1078/)

    *Akiko Eriguchi, Kazuma Hashimoto, Yoshimasa Tsuruoka*

    **Domain**: Model Architecture ; Prior Knowledge

6. **Achieving Open Vocabulary Neural Machine Translation with Hybrid Word-Character Models.** [paper](https://aclanthology.org/P16-1100/)

    *Minh-Thang Luong, Christopher D. Manning*

    **Domain**: Model Architecture

    [Paper Reading&Interpretation1](https://blog.csdn.net/u011414416/article/details/51108193)

7. **Synthesizing Compound Words for Machine Translation.** [paper](https://aclanthology.org/P16-1103/)

    *Austin Matthews, Eva Schlinger, Alon Lavie, Chris Dyer*

    **Domain**: Inference → Constrained Inference → Restricted NMT

8. **A Continuous Space Rule Selection Model for Syntax-based Statistical Machine Translation.** [paper](https://aclanthology.org/P16-1130)

    *Jingyi Zhang, Masao Utiyama, Eiichro Sumita, Graham Neubig, Satoshi Nakamura*

    **Domain**: Statistical Machine Translation → Syntax-based Models

9. **Learning Structured Predictors from Bandit Feedback for Interactive NLP.** [paper](https://aclanthology.org/P16-1152)

    *Artem Sokolov, Julia Kreutzer, Christopher Lo, Stefan Riezler*

    **Domain**: Training Strategy → Reinforcement Learning

10. **Minimum Risk Training for Neural Machine Translation.** [paper](https://aclanthology.org/P16-1159)

    *Shiqi Shen, Yong Cheng, Zhongjun He, Wei He, Hua Wu, Maosong Sun, Yang Liu*

    **Domain**: Training Strategy → Reinforcement Learning

11. **A Character-level Decoder without Explicit Segmentation for Neural Machine Translation.** [paper](https://aclanthology.org/P16-1160)

    *Junyoung Chung, Kyunghyun Cho, Yoshua Bengio*

    **Domain**: Model Architecture

12. **Target-Side Context for Discriminative Models in Statistical Machine Translation.** [paper](https://aclanthology.org/P16-1161)

    *Aleš Tamchyna, Alexander Fraser, Ondřej Bojar, Marcin Junczys-Dowmunt*

    **Domain**: Statistical Machine Translation → Phrase-based Models

13. **Neural Machine Translation of Rare Words with Subword Units.** [paper](https://aclanthology.org/P16-1162)

    *Rico Sennrich, Barry Haddow, Alexandra Birch*

    **Domain**: Data-based Methods → Word Segmentation

    [Paper Reading&Interpretation1](https://blog.csdn.net/zmx1996/article/details/83153311) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/38574684)

14. **MUTT: Metric Unit TesTing for Language Generation Tasks.** [paper](https://aclanthology.org/P16-1182)

    *William Boag, Renan Campos, Kate Saenko, Anna Rumshisky*

    **Domain**: Evaluation → Reference-free

15. **N-gram language models for massively parallel devices.** [paper](https://aclanthology.org/P16-1183)

    *Nikolay Bogoychev, Adam Lopez*

    **Domain**: Efficiency → Compution Optimization

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_34112900/article/details/86752409)

16. **Semi-Supervised Learning for Neural Machine Translation.** [paper](https://aclanthology.org/P16-1185)

    *Yong Cheng, Wei Xu, Zhongjun He, Wei He, Hua Wu, Maosong Sun, Yang Liu*

    **Domain**: Low-resource NMT → Semi-supervised NMT

17. **Strategies for Training Large Vocabulary Neural Language Models.** [paper](https://aclanthology.org/P16-1186)

    *Wenlin Chen, David Grangier, Michael Auli*

    **Domain**: Training Strategy ; Efficiency → Compution Optimization

18. **Set-Theoretic Alignment for Comparable Corpora.** [paper](https://aclanthology.org/P16-1189)

    *Thierry Etchegoyhen, Andoni Azpeitia*

    **Domain**: Data-based Methods → Data Augmentation

19. **Jointly Learning to Embed and Predict with Multiple Languages.** [paper](https://aclanthology.org/P16-1190)

    *Daniel C. Ferreira, André F. T. Martins, Mariana S. C. Almeida*

    **Domain**: Data-based Methods → Data Augmentation

20. **Supersense Embeddings: A Unified Model for Supersense Interpretation, Prediction, and Utilization.** [paper](https://aclanthology.org/P16-1191)

    *Lucie Flekova, Iryna Gurevych*

    **Domain**: Model Architecture

21. **A New Psychometric-inspired Evaluation Metric for Chinese Word Segmentation.** [paper](https://aclanthology.org/P16-1206)

    *Peng Qian, Xipeng Qiu, Xuanjing Huang*

    **Domain**: Evaluation → Reference-based

22. **Grammatical Error Correction: Machine Translation and Classifiers.** [paper](https://aclanthology.org/P16-1208)

    *Alla Rozovskaya, Dan Roth*

    **Domain**: Interpretability

23. **Knowledge-Based Semantic Embedding for Machine Translation.** [paper](https://aclanthology.org/P16-1212)

    *Chen Shi, Shujie Liu, Shuo Ren, Shi Feng, Mu Li, Ming Zhou, Xu Sun, Houfeng Wang*

    **Domain**: Model Architecture

24. **Graph-based Dependency Parsing with Bidirectional LSTM.** [paper](https://aclanthology.org/P16-1218)

    *Wenhui Wang, Baobao Chang*

    **Domain**: Model Architecture

25. **Improving Statistical Machine Translation Performance by Oracle-BLEU Model Re-estimation.** [paper](https://aclanthology.org/P16-2007/)

    *Praveen Dakwale, Christof Monz*

    **Domain**: Statistical Machine Translation → Phrase-based Models

26. **Reference Bias in Monolingual Machine Translation Evaluation.** [paper](https://aclanthology.org/P16-2013/)

    *Marina Fomicheva, Lucia Specia*

    **Domain**: Evaluation → Reference-based

27. **Vocabulary Manipulation for Neural Machine Translation.** [paper](https://aclanthology.org/P16-2021/)

    *Haitao Mi, Zhiguo Wang, Abe Ittycheriah*

    **Domain**: Efficiency → Compution Optimization

28. **An Open Web Platform for Rule-Based Speech-to-Sign Translation.** [paper](https://aclanthology.org/P16-2027)

    *Manny Rayner, Pierrette Bouillon, Sarah Ebling, Johanna Gerlach, Irene Strasly, Nikos Tsourakis*

    **Domain**: Open-source Systems and Datasets

29. **An Unsupervised Method for Automatic Translation Memory Cleaning.** [paper](https://aclanthology.org/P16-2047/)

    *Masoud Jalili Sabet, Matteo Negri, Marco Turchi, Eduard Barbu*

    **Domain**: Open-source Systems and Datasets

30. **Exponentially Decaying Bag-of-Words Input Features for Feed-Forward Neural Network in Statistical Machine Translation.** [paper](https://aclanthology.org/P16-2048/)

    *Jan-Thorsten Peter, Weiyue Wang, Hermann Ney*

    **Domain**: Statistical Machine Translation → Word-based Models

31. **Syntactically Guided Neural Machine Translation.** [paper](https://aclanthology.org/P16-2049/)

    *Felix Stahlberg, Eva Hasler, Aurelien Waite, Bill Byrne*

    **Domain**: Prior Knowledge

32. **Character-based Neural Machine Translation.** [paper](https://aclanthology.org/P16-2058/)

    *Marta R. Costa-jussà, José A. R. Fonollosa*

    **Domain**: Model Architecture

33. **Metrics for Evaluation of Word-level Machine Translation Quality Estimation.** [paper](https://aclanthology.org/P16-2095/)

    *Varvara Logacheva, Michal Lukasik, Lucia Specia*

    **Domain**: Evaluation → Reference-based

#### 2017

1. **A Convolutional Encoder Model for Neural Machine Translation.** [paper](https://aclanthology.org/P17-1012)

    *Jonas Gehring, Michael Auli, David Grangier, Yann Dauphin*

    **Domain**: Model Architecture

    [Paper Reading&Interpretation1](https://blog.csdn.net/Xiao_yanling/article/details/92064214) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/30515849)

2. **Deep Neural Machine Translation with Linear Associative Unit.** [paper](https://aclanthology.org/P17-1013)

    *Mingxuan Wang, Zhengdong Lu, Jie Zhou, Qun Liu*

    **Domain**: Model Architecture

3. **Creating Training Corpora for NLG Micro-Planners.** [paper](https://aclanthology.org/P17-1017)

    *Claire Gardent, Anastasia Shimorina, Shashi Narayan, Laura Perez-Beltrachini*

    **Domain**: Data-based Methods → Data Augmentation

4. **A** ***CCG Parsing with a Supertag and Dependency Factored Model.** [paper](https://aclanthology.org/P17-1026)

    *Masashi Yoshikawa, Hiroshi Noji, Yuji Matsumoto*

    **Domain**: Statistical Machine Translation → Syntax-based Models

5. **Multi-space Variational Encoder-Decoders for Semi-supervised Labeled Sequence Transduction.** [paper](https://aclanthology.org/P17-1029)

    *Chunting Zhou, Graham Neubig*

    **Domain**: Low-resource NMT → Semi-supervised NMT

6. **Joint CTC/attention decoding for end-to-end speech recognition.** [paper](https://aclanthology.org/P17-1048)

    *Takaaki Hori, Shinji Watanabe, John Hershey*

    **Domain**: Multimodal NMT → Speech → End-to-End Speech Translation

    [Paper Reading&Interpretation1](https://blog.csdn.net/pitaojun/article/details/111493883?spm=1001.2014.3001.5502)

7. **Modeling Source Syntax for Neural Machine Translation.** [paper](https://aclanthology.org/P17-1064)

    *Junhui Li, Deyi Xiong, Zhaopeng Tu, Muhua Zhu, Min Zhang, Guodong Zhou*

    **Domain**: Prior Knowledge

8. **Sequence-to-Dependency Neural Machine Translation.** [paper](https://aclanthology.org/P17-1065)

    *Shuangzhi Wu, Dongdong Zhang, Nan Yang, Mu Li, Ming Zhou*

    **Domain**: Prior Knowledge

    [Paper Reading&Interpretation1](https://blog.csdn.net/appleml/article/details/77835921)

9. **A Nested Attention Neural Hybrid Model for Grammatical Error Correction.** [paper](https://aclanthology.org/P17-1070)

    *Jianshu Ji, Qinlong Wang, Kristina Toutanova, Yongen Gong, Steven Truong, Jianfeng Gao*

    **Domain**: Ensemble

10. **Automatic Annotation and Evaluation of Error Types for Grammatical Error Correction.** [paper](https://aclanthology.org/P17-1074)

    *Christopher Bryant, Mariano Felice, Ted Briscoe*

    **Domain**: Prior Knowledge

11. **Neural Machine Translation via Binary Code Prediction.** [paper](https://aclanthology.org/P17-1079)

    *Yusuke Oda, Philip Arthur, Graham Neubig, Koichiro Yoshino, Satoshi Nakamura*

    **Domain**: Efficiency → Compution Optimization

12. **What do Neural Machine Translation Models Learn about Morphology?.** [paper](https://aclanthology.org/P17-1080)

    *Yonatan Belinkov, Nadir Durrani, Fahim Dalvi, Hassan Sajjad, James Glass*

    **Domain**: Interpretability

13. **Visualizing and Understanding Neural Machine Translation.** [paper](https://aclanthology.org/P17-1106)

    *Yanzhuo Ding, Yang Liu, Huanbo Luan, Maosong Sun*

    **Domain**: Interpretability

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/27349828)

14. **Adversarial Multi-Criteria Learning for Chinese Word Segmentation.** [paper](https://aclanthology.org/P17-1110)

    *Xinchi Chen, Zhan Shi, Xipeng Qiu, Xuanjing Huang*

    **Domain**: Data-based Methods → Word Segmentation

    [Paper Reading&Interpretation1](https://blog.csdn.net/appleml/article/details/78408207)

15. **Neural Joint Model for Transition-based Chinese Syntactic Analysis.** [paper](https://aclanthology.org/P17-1111)

    *Shuhei Kurita, Daisuke Kawahara, Sadao Kurohashi*

    **Domain**: Data-based Methods → Word Segmentation

16. **Robust Incremental Neural Semantic Graph Parsing.** [paper](https://aclanthology.org/P17-1112)

    *Jan Buys, Phil Blunsom*

    **Domain**: Prior Knowledge

17. **Adversarial Adaptation of Synthetic or Stale Data.** [paper](https://aclanthology.org/P17-1119)

    *Young-Bum Kim, Karl Stratos, Dongchan Kim*

    **Domain**: Training Strategy → Generative Adversarial Networks

18. **Can Syntax Help? Improving an LSTM-based Sentence Compression Model for New Domains.** [paper](https://aclanthology.org/P17-1127)

    *Liangguo Wang, Jing Jiang, Hai Leong Chieu, Chen Hui Ong, Dandan Song, Lejian Liao*

    **Domain**: Domain Adaptation

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_30219017/article/details/86839487)

19. **Bandit Structured Prediction for Neural Sequence-to-Sequence Learning.** [paper](https://aclanthology.org/P17-1138)

    *Julia Kreutzer, Artem Sokolov, Stefan Riezler*

    **Domain**: Domain Adaptation

20. **Prior Knowledge Integration for Neural Machine Translation using Posterior Regularization.** [paper](https://aclanthology.org/P17-1139)

    *Jiacheng Zhang, Yang Liu, Huanbo Luan, Jingfang Xu, Maosong Sun*

    **Domain**: Prior Knowledge

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_37625243/article/details/88374840) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/31659142)

21. **Incorporating Word Reordering Knowledge into Attention-based Neural Machine Translation.** [paper](https://aclanthology.org/P17-1140)

    *Jinchao Zhang, Mingxuan Wang, Qun Liu, Jie Zhou*

    **Domain**: Attention Mechanism

22. **Lexically Constrained Decoding for Sequence Generation Using Grid Beam Search.** [paper](https://aclanthology.org/P17-1141)

    *Chris Hokamp, Qun Liu*

    **Domain**: Inference → Constrained Inference → Interactive NMT

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/62523524) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/441751333)

23. **Enhanced LSTM for Natural Language Inference.** [paper](https://aclanthology.org/P17-1152)

    *Qian Chen, Xiaodan Zhu, Zhen-Hua Ling, Si Wei, Hui Jiang, Diana Inkpen*

    **Domain**: Inference

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38526306/article/details/88045134) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/141622985) ; [Paper Reading&Interpretation3](https://zhuanlan.zhihu.com/p/350933915) ; [Paper Reading&Interpretation4](https://zhuanlan.zhihu.com/p/366340728) ; [Paper Reading&Interpretation5](https://zhuanlan.zhihu.com/p/47580077)

24. **Universal Dependencies Parsing for Colloquial Singaporean English.** [paper](https://aclanthology.org/P17-1159)

    *Hongmin Wang, Yue Zhang, GuangYong Leonard Chan, Jie Yang, Hai Leong Chieu*

    **Domain**: Low-resource NMT → Endangered Language Study

25. **An Algebra for Feature Extraction.** [paper](https://aclanthology.org/P17-1173)

    *Vivek Srikumar*

    **Domain**: Efficiency → Compution Optimization

26. **Chunk-based Decoder for Neural Machine Translation.** [paper](https://aclanthology.org/P17-1174)

    *Shonosuke Ishiwatari, Jingtao Yao, Shujie Liu, Mu Li, Ming Zhou, Naoki Yoshinaga, Masaru Kitsuregawa, Weijia Jia*

    **Domain**: Inference

27. **Doubly-Attentive Decoder for Multi-modal Neural Machine Translation.** [paper](https://aclanthology.org/P17-1175)

    *Iacer Calixto, Qun Liu, Nick Campbell*

    **Domain**: Multimodal NMT → Image

28. **A Teacher-Student Framework for Zero-Resource Neural Machine Translation.** [paper](https://aclanthology.org/P17-1176)

    *Yun Chen, Yang Liu, Yong Cheng, Victor O.K. Li*

    **Domain**: Low-resource NMT → Endangered Language Study

29. **Improved Neural Machine Translation with a Syntax-Aware Encoder and Decoder.** [paper](https://aclanthology.org/P17-1177)

    *Huadong Chen, Shujian Huang, David Chiang, Jiajun Chen*

    **Domain**: Model Architecture

30. **One-Shot Neural Cross-Lingual Transfer for Paradigm Completion.** [paper](https://aclanthology.org/P17-1182)

    *Katharina Kann, Ryan Cotterell, Hinrich Schütze*

    **Domain**: Transfer Learning

31. **Revisiting Recurrent Networks for Paraphrastic Sentence Embeddings.** [paper](https://aclanthology.org/P17-1190)

    *John Wieting, Kevin Gimpel*

    **Domain**: Transfer Learning

32. **Neural Architectures for Multilingual Semantic Parsing.** [paper](https://aclanthology.org/P17-2007)

    *Raymond Hendy Susanto, Wei Lu*

    **Domain**: Multilingual NMT

33. **Incorporating Dialectal Variability for Socially Equitable Language Identification.** [paper](https://aclanthology.org/P17-2009)

    *David Jurgens, Yulia Tsvetkov, Dan Jurafsky*

    **Domain**: Multilingual NMT

34. **Learning to Parse and Translate Improves Neural Machine Translation.** [paper](https://aclanthology.org/P17-2012)

    *Akiko Eriguchi, Yoshimasa Tsuruoka, Kyunghyun Cho*

    **Domain**: Model Architecture

35. **Hybrid Neural Network Alignment and Lexicon Model in Direct HMM for Statistical Machine Translation.** [paper](https://aclanthology.org/P17-2020)

    *Weiyue Wang, Tamer Alkhouli, Derui Zhu, Hermann Ney*

    **Domain**: Model Architecture

36. **Towards String-To-Tree Neural Machine Translation.** [paper](https://aclanthology.org/P17-2021)

    *Roee Aharoni, Yoav Goldberg*

    **Domain**: Model Architecture

37. **The Role of Prosody and Speech Register in Word Segmentation: A Computational Modelling Perspective.** [paper](https://aclanthology.org/P17-2028)

    *Bogdan Ludusan, Reiko Mazuka, Mathieu Bernard, Alejandrina Cristia, Emmanuel Dupoux*

    **Domain**: Data-based Methods → Word Segmentation

38. **Attention Strategies for Multi-Source Sequence-to-Sequence Learning.** [paper](https://aclanthology.org/P17-2031/)

    *Jindřich Libovický, Jindřich Helcl*

    **Domain**: Attention Mechanism

39. **Neural System Combination for Machine Translation.** [paper](https://aclanthology.org/P17-2060/)

    *Long Zhou, Wenpeng Hu, Jiajun Zhang, Chengqing Zong*

    **Domain**: Ensemble

40. **An Empirical Comparison of Domain Adaptation Methods for Neural Machine Translation.** [paper](https://aclanthology.org/P17-2061/)

    *Chenhui Chu, Raj Dabre, Sadao Kurohashi*

    **Domain**: Domain Adaptation

41. **Efficient Extraction of Pseudo-Parallel Sentences from Raw Monolingual Data Using Word Embeddings.** [paper](https://aclanthology.org/P17-2062)

    *Benjamin Marie, Atsushi Fujita*

    **Domain**: Data-based Methods → Data Augmentation

42. **Sentence Embedding for Neural Machine Translation Domain Adaptation.** [paper](https://aclanthology.org/P17-2089)

    *Rui Wang, Andrew Finch, Masao Utiyama, Eiichiro Sumita*

    **Domain**: Domain Adaptation

43. **Data Augmentation for Low-Resource Neural Machine Translation.** [paper](https://aclanthology.org/P17-2090/)

    *Marzieh Fadaee, Arianna Bisazza, Christof Monz*

    **Domain**: Data-based Methods → Data Augmentation

44. **Speeding Up Neural Machine Translation Decoding by Shrinking Run-time Vocabulary.** [paper](https://aclanthology.org/P17-2091)

    *Xing Shi, Kevin Knight*

    **Domain**: Efficiency → Compution Optimization

45. **Chunk-Based Bi-Scale Decoder for Neural Machine Translation.** [paper](https://aclanthology.org/P17-2092/)

    *Hao Zhou, Zhaopeng Tu, Shujian Huang, Xiaohua Liu, Hang Li, Jiajun Chen*

    **Domain**: Model Architecture

46. **Challenging Language-Dependent Segmentation for Arabic: An Application to Machine Translation and Part-of-Speech Tagging.** [paper](https://aclanthology.org/P17-2095/)

    *Hassan Sajjad, Fahim Dalvi, Nadir Durrani, Ahmed Abdelali, Yonatan Belinkov, Stephan Vogel*

    **Domain**: Data-based Methods → Word Segmentation

#### 2018

1. **Unsupervised Neural Machine Translation with Weight Sharing.** [paper](https://aclanthology.org/P18-1005/)

    *Zhen Yang, Wei Chen, Feng Wang, Bo Xu*

    **Domain**: Low-resource NMT → Unsupervised NMT

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38937984/article/details/102159541?spm=1001.2014.3001.5502)

2. **Triangular Architecture for Rare Language Translation.** [paper](https://aclanthology.org/P18-1006/)

    *Shuo Ren, Wenhu Chen, Shujie Liu, Mu Li, Ming Zhou, Shuai Ma*

    **Domain**: Low-resource NMT → Endangered Language Study

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/_SfY-JZsUEKReSoI6qHg9w)

3. **On the Limitations of Unsupervised Bilingual Dictionary Induction.** [paper](https://aclanthology.org/P18-1072/)

    *Anders Søgaard, Sebastian Ruder, Ivan Vulić*

    **Domain**: Low-resource NMT → Unsupervised NMT

4. **The Best of Both Worlds: Combining Recent Advances in Neural Machine Translation.** [paper](https://aclanthology.org/P18-1008/)

    *Mia Xu Chen, Orhan Firat, Ankur Bapna, Melvin Johnson, Wolfgang Macherey, George Foster, Llion Jones, Mike Schuster, Noam Shazeer, Niki Parmar, Ashish Vaswani, Jakob Uszkoreit, Lukasz Kaiser, Zhifeng Chen, Yonghui Wu, Macduff Hughes*

    **Domain**: Model Architecture

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/415071203)

5. **Attention Focusing for Neural Machine Translation by Bridging Source and Target Embeddings.** [paper](https://aclanthology.org/P18-1164/)

    *Shaohui Kuang, Junhui Li, Antonio Branco, Weihua Luo, Deyi Xiong*

    **Domain**: Attention Mechanism

    [Paper Reading&Interpretation1](https://blog.csdn.net/Doron15/article/details/83033275?spm=1001.2014.3001.5502)

6. **Accelerating Neural Transformer via an Average Attention Network.** [paper](https://aclanthology.org/P18-1166/)

    *Biao Zhang, Deyi Xiong, Jinsong Su*

    **Domain**: Attention Mechanism ; Efficiency → Compution Optimization ; Robustness

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/75796168) ; [Paper Reading&Interpretation2](https://blog.csdn.net/wwx123521/article/details/83238989?spm=1001.2014.3001.5502)

7. **Neural Hidden Markov Model for Machine Translation.** [paper](https://aclanthology.org/P18-2060/)

    *Weiyue Wang, Derui Zhu, Tamer Alkhouli, Zixuan Gan, Hermann Ney*

    **Domain**: Model Architecture

8. **Subword Regularization: Improving Neural Network Translation Models with Multiple Subword Candidates.** [paper](https://aclanthology.org/P18-1007/)

    *Taku Kudo*

    **Domain**: Data-based Methods → Word Segmentation

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/38546218) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/333333666) ; [Paper Reading&Interpretation3](https://mp.weixin.qq.com/s/5z3CMmIR0U9-p2BwJnsYKg) ; [Paper Reading&Interpretation4](https://blog.csdn.net/u014248127/article/details/99998954?spm=1001.2014.3001.5502)

9. **A Stochastic Decoder for Neural Machine Translation.** [paper](https://aclanthology.org/P18-1115/)

    *Philip Schulz, Wilker Aziz, Trevor Cohn*

    **Domain**: Model Architecture

10. **Forest-Based Neural Machine Translation.** [paper](https://aclanthology.org/P18-1116/)

    *Chunpeng Ma, Akihiro Tamura, Masao Utiyama, Tiejun Zhao, Eiichiro Sumita*

    **Domain**: Model Architecture

    [Paper Reading&Interpretation1](https://blog.csdn.net/u014475479/article/details/81538819?spm=1001.2014.3001.5502)

11. **Towards Robust Neural Machine Translation.** [paper](https://aclanthology.org/P18-1163/)

    *Yong Cheng, Zhaopeng Tu, Fandong Meng, Junjie Zhai, Yang Liu*

    **Domain**: Robustness

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/417612841) ; [Paper Reading&Interpretation2](https://blog.csdn.net/void_p/article/details/90676771?spm=1001.2014.3001.5502)

#### 2019

1. **Latent Variable Model for Multi-modal Translation.** [paper](https://aclanthology.org/P19-1642/)

    *Iacer Calixto, Miguel Rios, Wilker Aziz*

    **Domain**: Multimodal NMT → Image

2. **Learning Deep Transformer Models for Machine Translation.** [paper](https://aclanthology.org/P19-1176/)

    *Qiang Wang, Bei Li, Tong Xiao, Jingbo Zhu, Changliang Li, Derek F. Wong, Lidia S. Chao*

    **Domain**: Model Architecture ; Robustness

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/NehJOAC0_nOPWES9KsoE4A)

3. **When a Good Translation is Wrong in Context: Context-Aware Machine Translation Improves on Deixis, Ellipsis, and Lexical Cohesion.** [paper](https://aclanthology.org/P19-1116/)

    *Elena Voita, Rico Sennrich, Ivan Titov*

    **Domain**: Data-based Methods → Data Augmentation

4. **A Compact and Language-Sensitive Multilingual Translation Method.** [paper](https://aclanthology.org/P19-1117/)

    *Yining Wang, Long Zhou, Jiajun Zhang, Feifei Zhai, Jingfang Xu, Chengqing Zong*

    **Domain**: Multilingual NMT

5. **Robust Neural Machine Translation with Doubly Adversarial Inputs.** [paper](https://aclanthology.org/P19-1425)

    *Yong Cheng, Lu Jiang, Wolfgang Macherey*

    **Domain**: Robustness

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/419459265) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/445671515) ; [Paper Reading&Interpretation3](https://blog.csdn.net/crystal_sugar/article/details/104836197?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation4](https://blog.csdn.net/weixin_43301333/article/details/106087909?spm=1001.2014.3001.5502)

6. **Shared-Private Bilingual Word Embeddings for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1352)

    *Xuebo Liu, Derek F. Wong, Yang Liu, Lidia S. Chao, Tong Xiao, Jingbo Zhu*

    **Domain**: Efficiency → Model Compression → Weight Sharing

7. **Unsupervised Parallel Sentence Extraction with Parallel Segment Detection Helps Machine Translation.** [paper](https://aclanthology.org/P19-1118)

    *Viktor Hangya, Alexander Fraser*

    **Domain**: Low-resource NMT → Unsupervised NMT

8. **Unsupervised Bilingual Word Embedding Agreement for Unsupervised Neural Machine Translation.** [paper](https://aclanthology.org/P19-1119/)

    *Haipeng Sun, Rui Wang, Kehai Chen, Masao Utiyama, Eiichiro Sumita, Tiejun Zhao*

    **Domain**: Low-resource NMT → Unsupervised NMT ; Pre-training

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38937984/article/details/102388490?spm=1001.2014.3001.5502)

9. **Neural Machine Translation with Reordering Embeddings.** [paper](https://aclanthology.org/P19-1174/)

    *Kehai Chen, Rui Wang, Masao Utiyama, Eiichiro Sumita*

    **Domain**: Prior Knowledge

10. **Neural Fuzzy Repair: Integrating Fuzzy Matches into Neural Machine Translation.** [paper](https://aclanthology.org/P19-1175/)

    *Bram Bulte, Arda Tezcan*

    **Domain**: Data-based Methods → Data Augmentation

11. **Effective Cross-lingual Transfer of Neural Machine Translation Models without Shared Vocabularies.** [paper](https://aclanthology.org/P19-1120/)

    *Yunsu Kim, Yingbo Gao, Hermann Ney*

    **Domain**: Transfer Learning

12. **Bridging the Gap between Training and Inference for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1426/)

    *Wen Zhang, Yang Feng, Fandong Meng, Di You, Qun Liu*

    **Domain**: Model Architecture

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/99738265) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/82548568) ; [Paper Reading&Interpretation3](https://zhuanlan.zhihu.com/p/82049108) ; [Paper Reading&Interpretation4](https://blog.csdn.net/Xiao_yanling/article/details/102620839?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation5](https://blog.csdn.net/iling5/article/details/101681405?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation6](https://blog.csdn.net/boywaiter/article/details/102908902?spm=1001.2014.3001.5502)

13. **Improved Zero-shot Neural Machine Translation via Ignoring Spurious Correlations.** [paper](https://aclanthology.org/P19-1121/)

    *Jiatao Gu, Yong Wang, Kyunghyun Cho, Victor O.K. Li*

    **Domain**: Low-resource NMT → Unsupervised NMT

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38937984/article/details/102406585?spm=1001.2014.3001.5502)

14. **Lattice Transformer for Speech Translation.** [paper](https://aclanthology.org/P19-1649/)

    *Pei Zhang, Niyu Ge, Boxing Chen, Kai Fan*

    **Domain**: Multimodal NMT → Speech → Cascaded Speech Translation

15. **Generalized Data Augmentation for Low-Resource Translation.** [paper](https://aclanthology.org/P19-1579/)

    *Mengzhou Xia, Xiang Kong, Antonios Anastasopoulos, Graham Neubig*

    **Domain**: Data-based Methods → Data Augmentation ; Low-resource NMT → Unsupervised NMT

16. **Syntactically Supervised Transformers for Faster Neural Machine Translation.** [paper](https://aclanthology.org/P19-1122/)

    *Nader Akoury, Kalpesh Krishna, Mohit Iyyer*

    **Domain**: Inference → Constrained Inference → Restricted NMT

17. **Unsupervised Pivot Translation for Distant Languages.** [paper](https://aclanthology.org/P19-1017/)

    *Yichong Leng, Xu Tan, Tao Qin, Xiang-Yang Li, Tie-Yan Liu*

    **Domain**: Low-resource NMT → Unsupervised NMT

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38937984/article/details/102316524?spm=1001.2014.3001.5502)

18. **Dynamically Composing Domain-Data Selection with Clean-Data Selection by "Co-Curricular Learning" for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1123/)

    *Wei Wang, Isaac Caswell, Ciprian Chelba*

    **Domain**: Transfer Learning

19. **On the Word Alignment from Neural Machine Translation.** [paper](https://aclanthology.org/P19-1124/)

    *Xintong Li, Guanlin Li, Lemao Liu, Max Meng, Shuming Shi*

    **Domain**: Prior Knowledge

20. **Imitation Learning for Non-Autoregressive Neural Machine Translation.** [paper](https://aclanthology.org/P19-1125/)

    *Bingzhen Wei, Mingxuan Wang, Hao Zhou, Junyang Lin, Xu Sun*

    **Domain**: Inference → Non-autoregressive

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/XVFp3l7iDJp-0_mJhSe17Q)

21. **Monotonic Infinite Lookback Attention for Simultaneous Machine Translation.** [paper](https://aclanthology.org/P19-1126)

    *Naveen Arivazhagan, Colin Cherry, Wolfgang Macherey, Chung-Cheng Chiu, Semih Yavuz, Ruoming Pang, Wei Li, Colin Raffel*

    **Domain**: Real-time NMT

22. **Domain Adaptation of Neural Machine Translation by Lexicon Induction.** [paper](https://aclanthology.org/P19-1286/)

    *Junjie Hu, Mengzhou Xia, Graham Neubig, Jaime Carbonell*

    **Domain**: Domain Adaptation

23. **Beyond BLEU:Training Neural Machine Translation with Semantic Similarity.** [paper](https://aclanthology.org/P19-1427/)

    *John Wieting, Taylor Berg-Kirkpatrick, Kevin Gimpel, Graham Neubig*

    **Domain**: Evaluation → Reference-based

24. **An Effective Approach to Unsupervised Machine Translation.** [paper](https://aclanthology.org/P19-1019/)

    *Mikel Artetxe, Gorka Labaka, Eneko Agirre*

    **Domain**: Low-resource NMT → Unsupervised NMT

    [Paper Reading&Interpretation1](https://blog.csdn.net/alzy133/article/details/105419257?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://blog.csdn.net/weixin_38937984/article/details/102297382?spm=1001.2014.3001.5502)

25. **Distilling Translations with Visual Awareness.** [paper](https://aclanthology.org/P19-1653/)

    *Julia Ive, Pranava Madhyastha, Lucia Specia*

    **Domain**: Multimodal NMT → Image

26. **Reference Network for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1287/)

    *Han Fu, Chenghao Liu, Jianling Sun*

    **Domain**: Prior Knowledge

27. **Retrieving Sequential Information for Non-Autoregressive Neural Machine Translation.** [paper](https://aclanthology.org/P19-1288/)

    *Chenze Shao, Yang Feng, Jinchao Zhang, Fandong Meng, Xilin Chen, Jie Zhou*

    **Domain**: Inference → Non-autoregressive

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/E6E6tc2uDJofuNDJArB5RQ)

28. **Sparse Sequence-to-Sequence Models.** [paper](https://aclanthology.org/P19-1146/)

    *Ben Peters, Vlad Niculae, André F. T. Martins*

    **Domain**: Efficiency → Compution Optimization

29. **Look Harder: A Neural Machine Translation Model with Hard Attention.** [paper](https://aclanthology.org/P19-1290/)

    *Sathish Reddy Indurthi, Insoo Chung, Sangha Kim*

    **Domain**: Attention Mechanism

30. **Robust Neural Machine Translation with Joint Textual and Phonetic Embedding.** [paper](https://aclanthology.org/P19-1291/)

    *Hairong Liu, Mingbo Ma, Liang Huang, Hao Xiong, Zhongjun He*

    **Domain**: Robustness

31. **Self-Supervised Neural Machine Translation.** [paper](https://aclanthology.org/P19-1178/)

    *Dana Ruiter, Cristina España-Bonet, Josef van Genabith*

    **Domain**: Low-resource NMT → Unsupervised NMT

32. **Soft Contextual Data Augmentation for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1555/)

    *Fei Gao, Jinhua Zhu, Lijun Wu, Yingce Xia, Tao Qin, Xueqi Cheng, Wengang Zhou, Tie-Yan Liu*

    **Domain**: Data-based Methods → Data Augmentation

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/70122299)

33. **Domain Adaptive Inference for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1022/)

    *Danielle Saunders, Felix Stahlberg, Adrià de Gispert, Bill Byrne*

    **Domain**: Domain Adaptation

34. **Revisiting Low-Resource Neural Machine Translation: A Case Study.** [paper](https://aclanthology.org/P19-1021/)

    *Rico Sennrich, Biao Zhang*

    **Domain**: Low-resource NMT

35. **Target Conditioned Sampling: Optimizing Data Selection for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/P19-1583/)

    *Xinyi Wang, Graham Neubig*

    **Domain**: Data-based Methods → Schedule Strategy → Data Selection ; Multilingual NMT

36. **Reducing Word Omission Errors in Neural Machine Translation: A Contrastive Learning Approach.** [paper](https://aclanthology.org/P19-1623)

    *Zonghan Yang, Yong Cheng, Yang Liu, Maosong Sun*

    **Domain**: Training Strategy → Contrastive Learning

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_40676758/article/details/114546304?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://blog.csdn.net/fengdu78/article/details/116725544?spm=1001.2014.3001.5502)

37. **Translating Translationese: A Two-Step Approach to Unsupervised Machine Translation.** [paper](https://aclanthology.org/P19-1293/)

    *Nima Pourdamghani, Nada Aldarrab, Marjan Ghazvininejad, Kevin Knight, Jonathan May*

    **Domain**: Low-resource NMT → Unsupervised NMT

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38937984/article/details/102060942?spm=1001.2014.3001.5502)

38. **Generating Diverse Translations with Sentence Codes.** [paper](https://aclanthology.org/P19-1177)

    *Raphael Shu, Hideki Nakayama, Kyunghyun Cho*

    **Domain**: Diversity and Fairness

39. **Exploring Phoneme-Level Speech Representations for End-to-End Speech Translation.** [paper](https://aclanthology.org/P19-1179/)

    *Elizabeth Salesky, Matthias Sperber, Alan W Black*

    **Domain**: Multimodal NMT → Speech → End-to-End Speech Translation

40. **Training Neural Machine Translation To Apply Terminology Constraints.** [paper](https://aclanthology.org/P19-1294/)

    *Georgiana Dinu, Prashant Mathur, Marcello Federico, Yaser Al-Onaizan*

    **Domain**: Prior Knowledge

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_24367797/article/details/108754346?spm=1001.2014.3001.5502)

41. **Exploiting Sentential Context for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1624/)

    *Xing Wang, Zhaopeng Tu, Longyue Wang, Shuming Shi*

    **Domain**: Model Architecture

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/q8Va0IJ3hkFQFDZo6pEZng)

42. **Depth Growing for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1558)

    *Lijun Wu, Yiren Wang, Yingce Xia, Fei Tian, Fei Gao, Tao Qin, Jianhuang Lai, Tie-Yan Liu*

    **Domain**: Model Architecture ; Training Strategy

43. **Effective Adversarial Regularization for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1020)

    *Motoki Sato, Jun Suzuki, Shun Kiyono*

    **Domain**: Training Strategy ; Robustness

    [Paper Reading&Interpretation1](https://blog.csdn.net/DragonBark/article/details/103150354?spm=1001.2014.3001.5502)

44. **Evaluating Gender Bias in Machine Translation.** [paper](https://aclanthology.org/P19-1164/)

    *Gabriel Stanovsky, Noah A. Smith, Luke Zettlemoyer*

    **Domain**: Evaluation → Reference-based

45. **Putting Evaluation in Context: Contextual Embeddings improve Machine Translation Evaluation.** [paper](https://aclanthology.org/P19-1269)

    *Nitika Mathur, Timothy Baldwin, Trevor Cohn*

    **Domain**: Evaluation → Reference-free

46. **Sentence-Level Agreement for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1296)

    *Mingming Yang, Rui Wang, Kehai Chen, Masao Utiyama, Eiichiro Sumita, Min Zhang, Tiejun Zhao*

    **Domain**: Model Architecture

47. **Bilingual Lexicon Induction through Unsupervised Machine Translation.** [paper](https://aclanthology.org/P19-1494)

    *Mikel Artetxe, Gorka Labaka, Eneko Agirre*

    **Domain**: Low-resource NMT → Unsupervised NMT

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38937984/article/details/102220543?spm=1001.2014.3001.5502)

48. **Better OOV Translation with Bilingual Terminology Mining.** [paper](https://aclanthology.org/P19-1581)

    *Matthias Huck, Viktor Hangya, Alexander Fraser*

    **Domain**: Prior Knowledge

49. **Lattice-Based Transformer Encoder for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1298/)

    *Fengshun Xiao, Jiangtong Li, Hai Zhao, Rui Wang, Kehai Chen*

    **Domain**: Prior Knowledge ; Attention Mechanism

50. **Simultaneous Translation with Flexible Policy via Restricted Imitation Learning.** [paper](https://aclanthology.org/P19-1582/)

    *Baigong Zheng, Renjie Zheng, Mingbo Ma, Liang Huang*

    **Domain**: Training Strategy → Contrastive Learning ; Real-time NMT

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/i70lV_-znoyDhEaU_3yBsw)

#### 2020

1. **Addressing Posterior Collapse with Mutual Information for Improved Variational Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.753/)

    *Arya D. McCarthy, Xian Li, Jiatao Gu, Ning Dong*

    **Domain**: Model Architecture

2. **Multiscale Collaborative Deep Models for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.40)

    *Xiangpeng Wei, Heng Yu, Yue Hu, Yue Zhang, Rongxiang Weng, Weihua Luo*

    **Domain**: Model Architecture

3. **Hard-Coded Gaussian Attention for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.687)

    *Weiqiu You, Simeng Sun, Mohit Iyyer*

    **Domain**: Attention Mechanism

4. **Improving Neural Machine Translation with Soft Template Prediction.** [paper](https://aclanthology.org/2020.acl-main.531/)

    *Jian Yang, Shuming Ma, Dongdong Zhang, Zhoujun Li, Ming Zhou*

    **Domain**: Model Architecture ; Prior Knowledge

5. **Learning Source Phrase Representations for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.37/)

    *Hongfei Xu, Josef van Genabith, Deyi Xiong, Qiuhui Liu, Jingyi Zhang*

    **Domain**: Model Architecture ; Attention Mechanism

6. **A Reinforced Generation of Adversarial Examples for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.319/)

    *Wei Zou, Shujian Huang, Jun Xie, Xinyu Dai, Jiajun Chen*

    **Domain**: Data-based Methods → Data Augmentation ; Robustness

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_42137700/article/details/107297116?spm=1001.2014.3001.5502)

7. **Boosting Neural Machine Translation with Similar Translations.** [paper](https://aclanthology.org/2020.acl-main.144/)

    *Jitao XU, Josep Crego, Jean Senellart*

    **Domain**: Data-based Methods → Data Augmentation

8. **Selecting Backtranslated Data from Multiple Sources for Improved Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.359)

    *Xabier Soto, Dimitar Shterionov, Alberto Poncelas, Andy Way*

    **Domain**: Data-based Methods → Schedule Strategy → Data Selection

9. **AdvAug: Robust Adversarial Augmentation for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.529/)

    *Yong Cheng, Lu Jiang, Wolfgang Macherey, Jacob Eisenstein*

    **Domain**: Data-based Methods → Data Augmentation

10. **Norm-Based Curriculum Learning for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.41/)

    *Xuebo Liu, Houtim Lai, Derek F. Wong, Lidia S. Chao*

    **Domain**: Data-based Methods → Schedule Strategy → Curriculum Learning

11. **Uncertainty-Aware Curriculum Learning for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.620/)

    *Yikai Zhou, Baosong Yang, Derek F. Wong, Yu Wan, Lidia S. Chao*

    **Domain**: Data-based Methods → Schedule Strategy → Curriculum Learning

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_41997479/article/details/118891253?spm=1001.2014.3001.5502)

12. **Balancing Training for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.754/)

    *Xinyi Wang, Yulia Tsvetkov, Graham Neubig*

    **Domain**: Data-based Methods → Schedule Strategy → Data Selection ; Multilingual NMT

13. **Improving Massively Multilingual Neural Machine Translation and Zero-Shot Translation.** [paper](https://aclanthology.org/2020.acl-main.148/)

    *Biao Zhang, Philip Williams, Ivan Titov, Rico Sennrich*

    **Domain**: Multilingual NMT

    [Paper Reading&Interpretation1](https://blog.csdn.net/jokerxsy/article/details/121392856?spm=1001.2014.3001.5502)

14. **Knowledge Distillation for Multilingual Unsupervised Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.324/)

    *Haipeng Sun, Rui Wang, Kehai Chen, Masao Utiyama, Eiichiro Sumita, Tiejun Zhao*

    **Domain**: Efficiency → Model Compression → Knowledge Distillation ; Low-resource NMT → Unsupervised NMT ; Multilingual NMT

15. **Translationese as a Language in “Multilingual” NMT.** [paper](https://aclanthology.org/2020.acl-main.691/)

    *Parker Riley, Isaac Caswell, Markus Freitag, David Grangier*

    **Domain**: Prior Knowledge

16. **A Novel Graph-based Multi-modal Fusion Encoder for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.273/)

    *Yongjing Yin, Fandong Meng, Jinsong Su, Chulun Zhou, Zhengyuan Yang, Jie Zhou, Jiebo Luo*

    **Domain**: Multimodal NMT → Image

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_40459958/article/details/120625411?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://blog.csdn.net/qq874455953/article/details/114949138?spm=1001.2014.3001.5502)

17. **Unsupervised Multimodal Neural Machine Translation with Pseudo Visual Pivoting.** [paper](https://aclanthology.org/2020.acl-main.731/)

    *Po-Yao Huang, Junjie Hu, Xiaojun Chang, Alexander Hauptmann*

    **Domain**: Multimodal NMT → Image

18. **Learning a Multi-Domain Curriculum for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.689/)

    *Wei Wang, Ye Tian, Jiquan Ngiam, Yinfei Yang, Isaac Caswell, Zarana Parekh*

    **Domain**: Data-based Methods → Schedule Strategy → Curriculum Learning ; Domain Adaptation

19. **Multi-Domain Neural Machine Translation with Word-Level Adaptive Layer-wise Domain Mixing.** [paper](https://aclanthology.org/2020.acl-main.165/)

    *Haoming Jiang, Chen Liang, Chong Wang, Tuo Zhao*

    **Domain**: Domain Adaptation

20. **Reducing Gender Bias in Neural Machine Translation as a Domain Adaptation Problem.** [paper](https://aclanthology.org/2020.acl-main.690/)

    *Danielle Saunders, Bill Byrne*

    **Domain**: Domain Adaptation

21. **BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension.** [paper](https://aclanthology.org/2020.acl-main.703/)

    *Mike Lewis, Yinhan Liu, Naman Goyal, Marjan Ghazvininejad, Abdelrahman Mohamed, Omer Levy, Veselin Stoyanov, Luke Zettlemoyer*

    **Domain**: Pre-training

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/121788986) ; [Paper Reading&Interpretation2](https://blog.csdn.net/chansonzhang/article/details/120474056?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation3](https://forlogen.blog.csdn.net/article/details/102866116?spm=1001.2014.3001.5502)

22. **Curriculum Pre-training for End-to-End Speech Translation.** [paper](https://aclanthology.org/2020.acl-main.344/)

    *Chengyi Wang, Yu Wu, Shujie Liu, Ming Zhou, Zhenglu Yang*

    **Domain**: Data-based Methods → Schedule Strategy → Curriculum Learning ; Multimodal NMT → Speech → End-to-End Speech Translation ; Pre-training

23. **Bilingual Dictionary Based Neural Machine Translation without Using Parallel Sentences.** [paper](https://aclanthology.org/2020.acl-main.143/)

    *Xiangyu Duan, Baijun Ji, Hao Jia, Min Tan, Min Zhang, Boxing Chen, Weihua Luo, Yue Zhang*

    **Domain**: Low-resource NMT → Unsupervised NMT

24. **A Retrieve-and-Rewrite Initialization Method for Unsupervised Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.320/)

    *Shuo Ren, Yu Wu, Shujie Liu, Ming Zhou, Shuai Ma*

    **Domain**: Low-resource NMT → Unsupervised NMT

25. **Document Translation vs. Query Translation for Cross-Lingual Information Retrieval in the Medical Domain.** [paper](https://aclanthology.org/2020.acl-main.613/)

    *Shadi Saleh, Pavel Pecina*

    **Domain**: Document-level NMT

26. **Dynamic Programming Encoding for Subword Segmentation in Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.275/)

    *Xuanli He, Gholamreza Haffari, Mohammad Norouzi*

    **Domain**: Data-based Methods → Word Segmentation

27. **In Neural Machine Translation, What Does Transfer Learning Transfer?.** [paper](https://aclanthology.org/2020.acl-main.688/)

    *Alham Fikri Aji, Nikolay Bogoychev, Kenneth Heafield, Rico Sennrich*

    **Domain**: Interpretability

28. **Jointly Masked Sequence-to-Sequence Model for Non-Autoregressive Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.36/)

    *Junliang Guo, Linli Xu, Enhong Chen*

    **Domain**: Inference → Non-autoregressive

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/uMz-cAyZfXqIH-le38luEw)

29. **Learning to Recover from Multi-Modality Errors for Non-Autoregressive Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.277/)

    *Qiu Ran, Yankai Lin, Peng Li, Jie Zhou*

    **Domain**: Inference → Non-autoregressive

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/HFqkigKldOHt1JS7rQCqpQ) ; [Paper Reading&Interpretation2](https://nopsled.blog.csdn.net/article/details/115004440?spm=1001.2014.3001.5502)

30. **Multi-Hypothesis Machine Translation Evaluation.** [paper](https://aclanthology.org/2020.acl-main.113/)

    *Marina Fomicheva, Lucia Specia, Francisco Guzmán*

    **Domain**: Evaluation → Reference-based

31. **On the Limitations of Cross-lingual Encoders as Exposed by Reference-Free Machine Translation Evaluation.** [paper](https://www.aclweb.org/anthology/2020.acl-main.151)

    *Wei Zhao, Goran Glavaš, Maxime Peyrard, Yang Gao, Robert West, Steffen Eger*

    **Domain**: Evaluation → Reference-free

32. **On The Evaluation of Machine Translation Systems Trained With Back-Translation.** [paper](https://www.aclweb.org/anthology/2020.acl-main.253)

    *Sergey Edunov, Myle Ott, Marc’Aurelio Ranzato, Michael Auli*

    **Domain**: Evaluation → Reference-based

33. **Tangled up in BLEU: Reevaluating the Evaluation of Automatic Machine Translation Evaluation Metrics.** [paper](https://www.aclweb.org/anthology/2020.acl-main.448)

    *Nitika Mathur, Timothy Baldwin, Trevor Cohn*

    **Domain**: Evaluation → Reference-based

34. **Evaluating Explanation Methods for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.35/)

    *Jierui Li, Lemao Liu, Huayang Li, Guanlin Li, Guoping Huang, Shuming Shi*

    **Domain**: Interpretability

35. **On the Inference Calibration of Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.278/)

    *Shuo Wang, Zhaopeng Tu, Shuming Shi, Yang Liu*

    **Domain**: Robustness

36. **Regularized Context Gates on Transformer for Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.757/)

    *Xintong Li, Lemao Liu, Rui Wang, Guoping Huang, Max Meng*

    **Domain**: Model Architecture

37. **Character-Level Translation with Self-attention.** [paper](https://aclanthology.org/2020.acl-main.145/)

    *Yingqiang Gao, Nikola I. Nikolov, Yuhuang Hu, Richard H.R. Hahnloser*

    **Domain**: Model Architecture

38. **Variational Neural Machine Translation with Normalizing Flows.** [paper](https://aclanthology.org/2020.acl-main.694/)

    *Hendra Setiawan, Matthias Sperber, Udhyakumar Nallasamy, Matthias Paulik*

    **Domain**: Model Architecture

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/294966561)

39. **Enhancing Machine Translation with Dependency-Aware Self-Attention.** [paper](https://aclanthology.org/2020.acl-main.147/)

    *Emanuele Bugliarello, Naoaki Okazaki*

    **Domain**: Prior Knowledge

40. **Content Word Aware Neural Machine Translation.** [paper](https://www.aclweb.org/anthology/2020.acl-main.34)

    *Kehai Chen, Rui Wang, Masao Utiyama, Eiichiro Sumita*

    **Domain**: Prior Knowledge

41. **Using Context in Neural Machine Translation Training Objectives.** [paper](https://aclanthology.org/2020.acl-main.693)

    *Danielle Saunders, Felix Stahlberg, Bill Byrne*

    **Domain**: Document-level NMT

42. **A Simple and Effective Unified Encoder for Document-Level Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.321/)

    *Shuming Ma, Dongdong Zhang, Ming Zhou*

    **Domain**: Document-level NMT ; Model Architecture

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/358639090)

43. **Contextual Neural Machine Translation Improves Translation of Cataphoric Pronouns.** [paper](https://aclanthology.org/2020.acl-main.530/)

    *KayYen Wong, Sameen Maruf, Gholamreza Haffari*

    **Domain**: Document-level NMT

44. **Does Multi-Encoder Help? A Case Study on Context-Aware Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.322)

    *Bei Li, Hui Liu, Ziyang Wang, Yufan Jiang, Tong Xiao, Jingbo Zhu, Tongran Liu, Changliang Li*

    **Domain**: Document-level NMT ; Interpretability

    [Paper Reading&Interpretation1](https://blog.csdn.net/xiao_xian_/article/details/108441933?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://blog.csdn.net/c9Yv2cf9I06K2A9E/article/details/106964479?spm=1001.2014.3001.5502)

45. **ENGINE: Energy-Based Inference Networks for Non-Autoregressive Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.251/)

    *Lifu Tu, Richard Yuanzhe Pang, Sam Wiseman, Kevin Gimpel*

    **Domain**: Inference → Non-autoregressive

46. **Lexically Constrained Neural Machine Translation with Levenshtein Transformer.** [paper](https://aclanthology.org/2020.acl-main.325/)

    *Raymond Hendy Susanto, Shamil Chollampatt, Liling Tan*

    **Domain**: Inference → Constrained Inference → Automatic Post-Editing ; Inference → Constrained Inference → Restricted NMT

47. **Improving Non-autoregressive Neural Machine Translation with Monolingual Data.** [paper](https://aclanthology.org/2020.acl-main.171/)

    *Jiawei Zhou, Phillip Keung*

    **Domain**: Data-based Methods → Data Augmentation

48. **Evaluating Robustness to Input Perturbations for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.755/)

    *Xing Niu, Prashant Mathur, Georgiana Dinu, Yaser Al-Onaizan*

    **Domain**: Evaluation → Reference-based

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/416885789) ; [Paper Reading&Interpretation2](https://blog.csdn.net/weixin_41696015/article/details/118468788?spm=1001.2014.3001.5502)

49. **It’s Easier to Translate out of English than into it: Measuring Neural Translation Difficulty by Cross-Mutual Information.** [paper](https://aclanthology.org/2020.acl-main.149/)

    *Emanuele Bugliarello, Sabrina J. Mielke, Antonios Anastasopoulos, Ryan Cotterell, Naoaki Okazaki*

    **Domain**: Evaluation → Reference-based

50. **Automatic Machine Translation Evaluation using Source Language Inputs and Cross-lingual Language Model.** [paper](https://aclanthology.org/2020.acl-main.327/)

    *Kosuke Takahashi, Katsuhito Sudoh, Satoshi Nakamura*

    **Domain**: Evaluation → Reference-based

51. **Language-aware Interlingua for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.150/)

    *Changfeng Zhu, Heng Yu, Shanbo Cheng, Weihua Luo*

    **Domain**: Multilingual NMT

52. **Leveraging Monolingual Data with Self-Supervision for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.252/)

    *Aditya Siddhant, Ankur Bapna, Yuan Cao, Orhan Firat, Mia Chen, Sneha Kudugunta, Naveen Arivazhagan, Yonghui Wu*

    **Domain**: Low-resource NMT → Unsupervised NMT ; Multilingual NMT

53. **Multimodal Transformer for Multimodal Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.400/)

    *Shaowei Yao, Xiaojun Wan*

    **Domain**: Multimodal NMT → Image

54. **Opportunistic Decoding with Timely Correction for Simultaneous Translation.** [paper](https://aclanthology.org/2020.acl-main.42/)

    *Renjie Zheng, Mingbo Ma, Baigong Zheng, Kaibo Liu, Liang Huang*

    **Domain**: Real-time NMT

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_47196664/article/details/106542477?spm=1001.2014.3001.5502)

55. **Simultaneous Translation Policies: From Fixed to Adaptive.** [paper](https://aclanthology.org/2020.acl-main.254/)

    *Baigong Zheng, Kaibo Liu, Renjie Zheng, Mingbo Ma, Hairong Liu, Liang Huang*

    **Domain**: Real-time NMT

56. **Tagged Back-translation Revisited: Why Does It Really Work?.** [paper](https://aclanthology.org/2020.acl-main.532/)

    *Benjamin Marie, Raphael Rubino, Atsushi Fujita*

    **Domain**: Data-based Methods → Data Augmentation

57. **Modeling Word Formation in English–German Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.389/)

    *Marion Weller-Di Marco, Alexander Fraser*

    **Domain**: Data-based Methods → Word Segmentation

58. **“You Sound Just Like Your Father” Commercial Machine Translation Systems Include Stylistic Biases.** [paper](https://aclanthology.org/2020.acl-main.154/)

    *Dirk Hovy, Federico Bianchi, Tommaso Fornaciari*

    **Domain**: Diversity and Fairness

59. **On Exposure Bias, Hallucination and Domain Shift in Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.326/)

    *Chaojun Wang, Rico Sennrich*

    **Domain**: Training Strategy

#### 2021

1. **Contrastive Learning for Many-to-many Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.21/)

    *Xiao Pan, Mingxuan Wang, Liwei Wu, Lei Li*

    **Domain**: Multilingual NMT ; Training Strategy → Contrastive Learning

    [Paper Reading&Interpretation1](https://bbs.gpushare.com/topic/761/%E6%9C%BA%E5%99%A8%E7%BF%BB%E8%AF%91-21-7-mrasp2?_=1640584574620)

2. **Understanding the Properties of Minimum Bayes Risk Decoding in Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.22/)

    *Mathias Müller, Rico Sennrich*

    **Domain**: Robustness ; Interpretability

3. **Multi-Head Highly Parallelized LSTM Decoder for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.23/)

    *Hongfei Xu, Qiuhui Liu, Josef van Genabith, Deyi Xiong, Meng Zhang*

    **Domain**: Efficiency → Compution Optimization

4. **Learning Language Specific Sub-network for Multilingual Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.25/)

    *Zehui Lin, Liwei Wu, Mingxuan Wang, Lei Li*

    **Domain**: Multilingual NMT

    [Paper Reading&Interpretation1](https://blog.csdn.net/jokerxsy/article/details/121279106)

5. **Cascaded Head-colliding Attention.** [paper](https://aclanthology.org/2021.acl-long.45/)

    *Lin Zheng, Zhiyong Wu, Lingpeng Kong*

    **Domain**: Attention Mechanism

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/jq_wA_nKKJNMffJU1LzUMA)

6. **Do Context-Aware Translation Models Pay the Right Attention?.** [paper](https://aclanthology.org/2021.acl-long.65/)

    *Kayo Yin, Patrick Fernandes, Danish Pruthi, Aditi Chaudhary, André F. T. Martins, Graham Neubig*

    **Domain**: Attention Mechanism ; Interpretability

7. **Adapting High-resource NMT Models to Translate Low-resource Related Languages without Parallel Data.** [paper](https://aclanthology.org/2021.acl-long.66/)

    *Wei-Jen Ko, Ahmed El-Kishky, Adithya Renduchintala, Vishrav Chaudhary, Naman Goyal, Francisco Guzmán, Pascale Fung, Philipp Koehn, Mona Diab*

    **Domain**: Low-resource NMT → Endangered Language Study

8. **Multilingual Speech Translation from Efficient Finetuning of Pretrained Models.** [paper](https://aclanthology.org/2021.acl-long.68/)

    *Xian Li, Changhan Wang, Yun Tang, Chau Tran, Yuqing Tang, Juan Pino, Alexei Baevski, Alexis Conneau, Michael Auli*

    **Domain**: Multimodal NMT → Speech → Cascaded Speech Translation ; Multilingual NMT ; Pre-training

9. **Improving Zero-Shot Translation by Disentangling Positional Information.** [paper](https://aclanthology.org/2021.acl-long.101/)

    *Danni Liu, Jan Niehues, James Cross, Francisco Guzmán, Xian Li*

    **Domain**: Multilingual NMT

10. **Exploiting Language Relatedness for Low Web-Resource Language Model Adaptation: An Indic Languages Study.** [paper](https://aclanthology.org/2021.acl-long.105/)

    *Yash Khemchandani, Sarvesh Mehtani, Vaidehi Patil, Abhijeet Awasthi, Partha Talukdar, Sunita Sarawagi*

    **Domain**: Pre-training

11. **Glancing Transformer for Non-Autoregressive Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.155/)

    *Lihua Qian, Hao Zhou, Yu Bao, Mingxuan Wang, Lin Qiu, Weinan Zhang, Yong Yu, Lei Li*

    **Domain**: Inference → Non-autoregressive

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/392167557) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/395824887)

12. **Weight Distillation: Transferring the Knowledge in Neural Network Parameters.** [paper](https://aclanthology.org/2021.acl-long.162/)

    *Ye Lin, Yanyang Li, Ziyang Wang, Bei Li, Quan Du, Tong Xiao, Jingbo Zhu*

    **Domain**: Efficiency → Model Compression → Knowledge Distillation

    [Paper Reading&Interpretation1](https://blog.csdn.net/gjh1716718326/article/details/119033923)

13. **Data Augmentation for Text Generation Without Any Augmented Data.** [paper](https://aclanthology.org/2021.acl-long.173/)

    *Wei Bi, Huayang Li, Jiacheng Huang*

    **Domain**: Data-based Methods → Data Augmentation

14. **Beyond Sentence-Level End-to-End Speech Translation: Context Helps.** [paper](https://aclanthology.org/2021.acl-long.200/)

    *Biao Zhang, Ivan Titov, Barry Haddow, Rico Sennrich*

    **Domain**: Multimodal NMT → Speech → End-to-End Speech Translation

15. **Self-Training Sampling with Monolingual Data Uncertainty for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.221/)

    *Wenxiang Jiao, Xing Wang, Zhaopeng Tu, Shuming Shi, Michael Lyu, Irwin King*

    **Domain**: Data-based Methods → Data Augmentation

16. **Breaking the Corpus Bottleneck for Context-Aware Neural Machine Translation with Cross-Task Pre-training.** [paper](https://aclanthology.org/2021.acl-long.222/)

    *Linqing Chen, Junhui Li, Zhengxian Gong, Boxing Chen, Weihua Luo, Min Zhang, Guodong Zhou*

    **Domain**: Pre-training

17. **Guiding Teacher Forcing with Seer Forcing for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.223/)

    *Yang Feng, Shuhao Gu, Dengji Guo, Zhengxin Yang, Chenze Shao*

    **Domain**: Efficiency → Model Compression → Knowledge Distillation ; Model Architecture

18. **Cascade versus Direct Speech Translation: Do the Differences Still Make a Difference?.** [paper](https://aclanthology.org/2021.acl-long.224/)

    *Luisa Bentivogli, Mauro Cettolo, Marco Gaido, Alina Karakanta, Alberto Martinelli, Matteo Negri, Marco Turchi*

    **Domain**: Multimodal NMT → Speech → Cascaded Speech Translation

19. **Unsupervised Neural Machine Translation for Low-Resource Domains via Meta-Learning.** [paper](https://aclanthology.org/2021.acl-long.225/)

    *Cheonbok Park, Yunwon Tae, TaeHee Kim, Soyoung Yang, Mohammad Azam Khan, Lucy Park, Jaegul Choo*

    **Domain**: Low-resource NMT → Unsupervised NMT ; Domain Adaptation

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_30232405/article/details/120903124)

20. **Marginal Utility Diminishes: Exploring the Minimum Knowledge for BERT Knowledge Distillation.** [paper](https://aclanthology.org/2021.acl-long.228/)

    *Yuanxin Liu, Fandong Meng, Zheng Lin, Weiping Wang, Jie Zhou*

    **Domain**: Efficiency → Model Compression → Knowledge Distillation ; Pre-training

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_41485273/article/details/117822718)

21. **LeeBERT: Learned Early Exit for BERT with cross-level optimization.** [paper](https://aclanthology.org/2021.acl-long.231/)

    *Wei Zhu*

    **Domain**: Pre-training

22. **Meta-KD: A Meta Knowledge Distillation Framework for Language Model Compression across Domains.** [paper](https://aclanthology.org/2021.acl-long.236/)

    *Haojie Pan, Chengyu Wang, Minghui Qiu, Yichang Zhang, Yaliang Li, Jun Huang*

    **Domain**: Efficiency → Model Compression → Knowledge Distillation ; Domain Adaptation

    [Paper Reading&Interpretation1](https://nopsled.blog.csdn.net/article/details/119754960?spm=1001.2014.3001.5502)

23. **Online Learning Meets Machine Translation Evaluation: Finding the Best Systems with the Least Human Effort.** [paper](https://aclanthology.org/2021.acl-long.242/)

    *Vânia Mendonça, Ricardo Rei, Luisa Coheur, Alberto Sardinha, Ana Lúcia Santos*

    **Domain**: Evaluation → Reference-based

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/380822788)

24. **How Good is Your Tokenizer? On the Monolingual Performance of Multilingual Language Models.** [paper](https://aclanthology.org/2021.acl-long.243/)

    *Phillip Rust, Jonas Pfeiffer, Ivan Vulić, Sebastian Ruder, Iryna Gurevych*

    **Domain**: Pre-training

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/403177621)

25. **From Machine Translation to Code-Switching: Generating High-Quality Code-Switched Text.** [paper](https://aclanthology.org/2021.acl-long.245/)

    *Ishan Tarunesh, Syamantak Kumar, Preethi Jyothi*

    **Domain**: Low-resource NMT → Endangered Language Study

26. **Fast and Accurate Neural Machine Translation with Translation Memory.** [paper](https://aclanthology.org/2021.acl-long.246/)

    *Qiuxiang He, Guoping Huang, Qu Cui, Li Li, Lemao Liu*

    **Domain**: Model Architecture

27. **Meta-Learning to Compositionally Generalize.** [paper](https://aclanthology.org/2021.acl-long.258/)

    *Henry Conklin, Bailin Wang, Kenny Smith, Ivan Titov*

    **Domain**: Training Strategy → Meta Learning

28. **Taming Pre-trained Language Models with N-gram Representations for Low-Resource Domain Adaptation.** [paper](https://aclanthology.org/2021.acl-long.259/)

    *Shizhe Diao, Ruijia Xu, Hongjin Su, Yilei Jiang, Yan Song, Tong Zhang*

    **Domain**: Domain Adaptation

29. **Consistency Regularization for Cross-Lingual Fine-Tuning.** [paper](https://aclanthology.org/2021.acl-long.264/)

    *Bo Zheng, Li Dong, Shaohan Huang, Wenhui Wang, Zewen Chi, Saksham Singhal, Wanxiang Che, Ting Liu, Xia Song, Furu Wei*

    **Domain**: Multilingual NMT

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/XAuPGfscU4szlX3Hb1sneA) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/384664475)

30. **Rejuvenating Low-Frequency Words: Making the Most of Parallel Data in Non-Autoregressive Translation.** [paper](https://aclanthology.org/2021.acl-long.266/)

    *Liang Ding, Longyue Wang, Xuebo Liu, Derek F. Wong, Dacheng Tao, Zhaopeng Tu*

    **Domain**: Pre-training ; Efficiency → Model Compression → Knowledge Distillation

31. **G-Transformer for Document-Level Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.267/)

    *Guangsheng Bao, Yue Zhang, Zhiyang Teng, Boxing Chen, Weihua Luo*

    **Domain**: Document-level NMT

    [Paper Reading&Interpretation1](https://nopsled.blog.csdn.net/article/details/121034422?spm=1001.2014.3001.5502)

32. **Prevent the Language Model from being Overconfident in Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.268/)

    *Mengqi Miao, Fandong Meng, Yijin Liu, Xiao-Hua Zhou, Jie Zhou*

    **Domain**: Inference → Constrained Inference → Restricted NMT

    [Paper Reading&Interpretation1](https://nopsled.blog.csdn.net/article/details/121746619?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/424116870)

33. **A Sweet Rabbit Hole by DARCY: Using Honeypots to Detect Universal Trigger’s Adversarial Attacks.** [paper](https://aclanthology.org/2021.acl-long.296/)

    *Thai Le, Noseong Park, Dongwon Lee*

    **Domain**: Training Strategy → Generative Adversarial Networks

34. **Cross-language Sentence Selection via Data Augmentation and Rationale Training.** [paper](https://aclanthology.org/2021.acl-long.300/)

    *Yanda Chen, Chris Kedzie, Suraj Nair, Petra Galuscakova, Rui Zhang, Douglas Oard, Kathleen McKeown*

    **Domain**: Data-based Methods → Data Augmentation

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_41485273/article/details/117711905)

35. **Point, Disambiguate and Copy: Incorporating Bilingual Dictionaries for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.307/)

    *Tong Zhang, Long Zhang, Wei Ye, Bo Li, Jinan Sun, Xiaoyu Zhu, Wen Zhao, Shikun Zhang*

    **Domain**: Model Architecture

36. **VECO: Variable and Flexible Cross-lingual Pre-training for Language Understanding and Generation.** [paper](https://aclanthology.org/2021.acl-long.308/)

    *Fuli Luo, Wei Wang, Jiahao Liu, Yijia Liu, Bin Bi, Songfang Huang, Fei Huang, Luo Si*

    **Domain**: Pre-training

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/401333337)

37. **A unified approach to sentence segmentation of punctuated text in many languages.** [paper](https://aclanthology.org/2021.acl-long.309/)

    *Rachel Wicks, Matt Post*

    **Domain**: Data-based Methods → Word Segmentation

38. **Towards User-Driven Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.310/)

    *Huan Lin, Liang Yao, Baosong Yang, Dayiheng Liu, Haibo Zhang, Weihua Luo, Degen Huang, Jinsong Su*

    **Domain**: Model Architecture

39. **End-to-End Lexically Constrained Machine Translation for Morphologically Rich Languages.** [paper](https://aclanthology.org/2021.acl-long.311/)

    *Josef Jon, João Paulo Aires, Dusan Varis, Ondřej Bojar*

    **Domain**: Inference → Constrained Inference → Restricted NMT

40. **Improving Speech Translation by Understanding and Learning from the Auxiliary Text Translation Task.** [paper](https://aclanthology.org/2021.acl-long.328)

    *Yun Tang, Juan Pino, Xian Li, Changhan Wang, Dmitriy Genzel*

    **Domain**: Multimodal NMT → Speech → Cascaded Speech Translation

41. **Reservoir Transformers.** [paper](https://aclanthology.org/2021.acl-long.331)

    *Sheng Shen, Alexei Baevski, Ari Morcos, Kurt Keutzer, Michael Auli, Douwe Kiela*

    **Domain**: Model Architecture

42. **SemFace: Pre-training Encoder and Decoder with a Semantic Interface for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.348)

    *Shuo Ren, Long Zhou, Shujie Liu, Furu Wei, Ming Zhou, Shuai Ma*

    **Domain**: Pre-training

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_30232405/article/details/120699960)

43. **Energy-Based Reranking: Improving Neural Machine Translation Using Energy-Based Models.** [paper](https://aclanthology.org/2021.acl-long.349)

    *Sumanta Bhattacharyya, Amirmohammad Rooshenas, Subhajit Naskar, Simeng Sun, Mohit Iyyer, Andrew McCallum*

    **Domain**: Reranking

44. **On Compositional Generalization of Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.368)

    *Yafu Li, Yongjing Yin, Yulong Chen, Yue Zhang*

    **Domain**: Robustness

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/421451635) ; [Paper Reading&Interpretation2](https://www.bilibili.com/video/BV16P4y1H7uK?from=search&seid=10274723515390347439&spm_id_from=333.337.0.0)

45. **GWLAN: General Word-Level AutocompletioN for Computer-Aided Translation.** [paper](https://aclanthology.org/2021.acl-long.370)

    *Huayang Li, Lemao Liu, Guoping Huang, Shuming Shi*

    **Domain**: Inference → Constrained Inference → Automatic Post-Editing

46. **Rewriter-Evaluator Architecture for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.443)

    *Yangming Li, Kaisheng Yao*

    **Domain**: Model Architecture

47. **Modeling Bilingual Conversational Characteristics for Neural Chat Translation.** [paper](https://aclanthology.org/2021.acl-long.444/)

    *Yunlong Liang, Fandong Meng, Yufeng Chen, Jinan Xu, Jie Zhou*

    **Domain**: Document-level NMT

48. **Importance-based Neuron Allocation for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.445/)

    *Wanying Xie, Yang Feng, Shuhao Gu, Dong Yu*

    **Domain**: Multilingual NMT

    [Paper Reading&Interpretation1](https://blog.csdn.net/jokerxsy/article/details/121816932)

49. **Transfer Learning for Sequence Generation: from Single-source to Multi-source.** [paper](https://aclanthology.org/2021.acl-long.446/)

    *Xuancheng Huang, Jingfang Xu, Maosong Sun, Yang Liu*

    **Domain**: Pre-training

50. **Good for Misconceived Reasons: An Empirical Revisiting on the Need for Visual Context in Multimodal Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.480/)

    *Zhiyong Wu, Lingpeng Kong, Wei Bi, Xiang Li, Ben Kao*

    **Domain**: Multimodal NMT → Image

51. **Selective Knowledge Distillation for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.504/)

    *Fusheng Wang, Jianhao Yan, Fandong Meng, Jie Zhou*

    **Domain**: Efficiency → Model Compression → Knowledge Distillation

    [Paper Reading&Interpretation1](https://nopsled.blog.csdn.net/article/details/121951287?spm=1001.2014.3001.5502)

52. **Measuring and Increasing Context Usage in Context-Aware Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.505/)

    *Patrick Fernandes, Kayo Yin, Graham Neubig, André F. T. Martins*

    **Domain**: Document-level NMT

53. **CCMatrix: Mining Billions of High-Quality Parallel Sentences on the Web.** [paper](https://aclanthology.org/2021.acl-long.507/)

    *Holger Schwenk, Guillaume Wenzek, Sergey Edunov, Edouard Grave, Armand Joulin, Angela Fan*

    **Domain**: Open-source Systems and Datasets

54. **Determinantal Beam Search.** [paper](https://aclanthology.org/2021.acl-long.512/)

    *Clara Meister, Martina Forster, Ryan Cotterell*

    **Domain**: Inference → Beam Search

55. **Mid-Air Hand Gestures for Post-Editing of Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.527)

    *Rashad Albo Jamara, Nico Herbig, Antonio Krüger, Josef van Genabith*

    **Domain**: Inference → Constrained Inference → Automatic Post-Editing

56. **The statistical advantage of automatic NLG metrics at the system level.** [paper](https://aclanthology.org/2021.acl-long.533)

    *Johnny Wei, Robin Jia*

    **Domain**: Interpretability

57. **Beyond Noise: Mitigating the Impact of Fine-grained Semantic Divergences on Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.562)

    *Eleftheria Briakou, Marine Carpuat*

    **Domain**: Robustness

58. **Discriminative Reranking for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.563)

    *Ann Lee, Michael Auli, Marc’Aurelio Ranzato*

    **Domain**: Reranking

59. **Scientific Credibility of Machine Translation Research: A Meta-Evaluation of 769 Papers.** [paper](https://aclanthology.org/2021.acl-long.566)

    *Benjamin Marie, Atsushi Fujita, Raphael Rubino*

    **Domain**: Survey

60. **Neural Machine Translation with Monolingual Translation Memory.** [paper](https://aclanthology.org/2021.acl-long.567)

    *Deng Cai, Yan Wang, Huayang Li, Wai Lam, Lemao Liu*

    **Domain**: Prior Knowledge

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/5HR04WW_EmoKy7414rzrZQ) ; [Paper Reading&Interpretation2](https://blog.csdn.net/qq_42341984/article/details/119535281) ; [Paper Reading&Interpretation3](https://zhuanlan.zhihu.com/p/397888408) ; [Paper Reading&Interpretation4](https://zhuanlan.zhihu.com/p/387147408)

61. **Vocabulary Learning via Optimal Transport for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.571)

    *Jingjing Xu, Hao Zhou, Chun Gan, Zaixiang Zheng, Lei Li*

    **Domain**: Data-based Methods → Word Segmentation

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_16949707/article/details/118694959) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/420759521) ; [Paper Reading&Interpretation3](https://zhuanlan.zhihu.com/p/390854862) ; [Paper Reading&Interpretation4](https://zhuanlan.zhihu.com/p/388813045)

62. **Difficulty-Aware Machine Translation Evaluation.** [paper](https://aclanthology.org/2021.acl-short.5)

    *Runzhe Zhan, Xuebo Liu, Derek F. Wong, Lidia S. Chao*

    **Domain**: Evaluation → Reference-based

63. **Gender bias amplification during Speed-Quality optimization in Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-short.15)

    *Adithya Renduchintala, Denise Diaz, Kenneth Heafield, Xian Li, Mona Diab*

    **Domain**: Diversity and Fairness

64. **Machine Translation into Low-resource Language Varieties.** [paper](https://aclanthology.org/2021.acl-short.16)

    *Sachin Kumar, Antonios Anastasopoulos, Shuly Wintner, Yulia Tsvetkov*

    **Domain**: Low-resource NMT → Endangered Language Study

65. **Continual Quality Estimation with Online Bayesian Meta-Learning.** [paper](https://aclanthology.org/2021.acl-short.25)

    *Abiola Obamuyide, Marina Fomicheva, Lucia Specia*

    **Domain**: Evaluation → Reference-free ; Training Strategy → Meta Learning

66. **Anchor-based Bilingual Word Embeddings for Low-Resource Languages.** [paper](https://aclanthology.org/2021.acl-short.30)

    *Tobias Eder, Viktor Hangya, Alexander Fraser*

    **Domain**: Low-resource NMT → Endangered Language Study

67. **Multilingual Agreement for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-short.31)

    *Jian Yang, Yuwei Yin, Shuming Ma, Haoyang Huang, Dongdong Zhang, Zhoujun Li, Furu Wei*

    **Domain**: Multilingual NMT

68. **Modeling Task-Aware MIMO Cardinality for Efficient Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-short.46)

    *Hongfei Xu, Qiuhui Liu, Josef van Genabith, Deyi Xiong*

    **Domain**: Multilingual NMT

69. **Adaptive Nearest Neighbor Machine Translation.** [paper](https://aclanthology.org/2021.acl-short.47)

    *Xin Zheng, Zhirui Zhang, Junliang Guo, Shujian Huang, Boxing Chen, Weihua Luo, Jiajun Chen*

    **Domain**: Inference → Constrained Inference → Restricted NMT

70. **On Orthogonality Constraints for Transformers.** [paper](https://aclanthology.org/2021.acl-short.48)

    *Aston Zhang, Alvin Chan, Yi Tay, Jie Fu, Shuohang Wang, Shuai Zhang, Huajie Shao, Shuochao Yao, Roy Ka-Wei Lee*

    **Domain**: Training Strategy

71. **An Exploratory Analysis of Multilingual Word-Level Quality Estimation with Cross-Lingual Transformers.** [paper](https://aclanthology.org/2021.acl-short.55)

    *Tharindu Ranasinghe, Constantin Orasan, Ruslan Mitkov*

    **Domain**: Pre-training ; WMT → Quality Estimation

72. **An Empirical Study on Adversarial Attack on NMT: Languages and Positions Matter.** [paper](https://aclanthology.org/2021.acl-short.58)

    *Zhiyuan Zeng, Deyi Xiong*

    **Domain**: Robustness

73. **Bilingual Mutual Information Based Adaptive Training for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-short.65)

    *Yangyifan Xu, Yijin Liu, Fandong Meng, Jiajun Zhang, Jinan Xu, Jie Zhou*

    **Domain**: Training Strategy

74. **When is Char Better Than Subword: A Systematic Study of Segmentation Algorithms for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-short.69)

    *Jiahuan Li, Yutong Shen, Shujian Huang, Xinyu Dai, Jiajun Chen*

    **Domain**: Data-based Methods → Word Segmentation

75. **nmT5 - Is parallel data still relevant for pre-training massively multilingual language models?.** [paper](https://aclanthology.org/2021.acl-short.87)

    *Mihir Kale, Aditya Siddhant, Rami Al-Rfou, Linting Xue, Noah Constant, Melvin Johnson*

    **Domain**: Pre-training ; Multilingual NMT

76. **Improving Lexically Constrained Neural Machine Translation with Source-Conditioned Masked Span Prediction.** [paper](https://aclanthology.org/2021.acl-short.94)

    *Gyubok Lee, Seongjun Yang, Edward Choi*

    **Domain**: Training Strategy

77. **Lightweight Adapter Tuning for Multilingual Speech Translation.** [paper](https://aclanthology.org/2021.acl-short.103)

    *Hang Le, Juan Pino, Changhan Wang, Jiatao Gu, Didier Schwab, Laurent Besacier*

    **Domain**: Multimodal NMT → Speech → End-to-End Speech Translation ; Multilingual NMT

78. **Don’t Rule Out Monolingual Speakers: A Method For Crowdsourcing Machine Translation Data.** [paper](https://aclanthology.org/2021.acl-short.139)

    *Rajat Bhatnagar, Ananya Ganesh, Katharina Kann*

    **Domain**: Data-based Methods

## List by Area

### <span id="StatisticalMachineTranslation">Statistical Machine Translation</span>

#### <span id="Word-basedModels">Word-based Models</span>

1. **Exponentially Decaying Bag-of-Words Input Features for Feed-Forward Neural Network in Statistical Machine Translation.** [paper](https://aclanthology.org/P16-2048/)

    *Jan-Thorsten Peter, Weiyue Wang, Hermann Ney*

    **Venue**: ACL-2016

#### <span id="Distortion-basedandFertility-basedmodels">Distortion-based and Fertility-based models</span>

#### <span id="Phrase-basedModels">Phrase-based Models</span>

1. **Target-Side Context for Discriminative Models in Statistical Machine Translation.** [paper](https://aclanthology.org/P16-1161)

    *Aleš Tamchyna, Alexander Fraser, Ondřej Bojar, Marcin Junczys-Dowmunt*

    **Venue**: ACL-2016

2. **Improving Statistical Machine Translation Performance by Oracle-BLEU Model Re-estimation.** [paper](https://aclanthology.org/P16-2007/)

    *Praveen Dakwale, Christof Monz*

    **Venue**: ACL-2016

#### <span id="Syntax-basedModels">Syntax-based Models</span>

1. **A Continuous Space Rule Selection Model for Syntax-based Statistical Machine Translation.** [paper](https://aclanthology.org/P16-1130)

    *Jingyi Zhang, Masao Utiyama, Eiichro Sumita, Graham Neubig, Satoshi Nakamura*

    **Venue**: ACL-2016

2. **A** ***CCG Parsing with a Supertag and Dependency Factored Model.** [paper](https://aclanthology.org/P17-1026)

    *Masashi Yoshikawa, Hiroshi Noji, Yuji Matsumoto*

    **Venue**: ACL-2017

### <span id="Evaluation">Evaluation</span>

#### <span id="Reference-based">Reference-based</span>

1. **A New Psychometric-inspired Evaluation Metric for Chinese Word Segmentation.** [paper](https://aclanthology.org/P16-1206)

    *Peng Qian, Xipeng Qiu, Xuanjing Huang*

    **Venue**: ACL-2016

2. **Reference Bias in Monolingual Machine Translation Evaluation.** [paper](https://aclanthology.org/P16-2013/)

    *Marina Fomicheva, Lucia Specia*

    **Venue**: ACL-2016

3. **Metrics for Evaluation of Word-level Machine Translation Quality Estimation.** [paper](https://aclanthology.org/P16-2095/)

    *Varvara Logacheva, Michal Lukasik, Lucia Specia*

    **Venue**: ACL-2016

4. **Beyond BLEU:Training Neural Machine Translation with Semantic Similarity.** [paper](https://aclanthology.org/P19-1427/)

    *John Wieting, Taylor Berg-Kirkpatrick, Kevin Gimpel, Graham Neubig*

    **Venue**: ACL-2019

5. **Evaluating Gender Bias in Machine Translation.** [paper](https://aclanthology.org/P19-1164/)

    *Gabriel Stanovsky, Noah A. Smith, Luke Zettlemoyer*

    **Venue**: ACL-2019

6. **Multi-Hypothesis Machine Translation Evaluation.** [paper](https://aclanthology.org/2020.acl-main.113/)

    *Marina Fomicheva, Lucia Specia, Francisco Guzmán*

    **Venue**: ACL-2020

7. **On The Evaluation of Machine Translation Systems Trained With Back-Translation.** [paper](https://www.aclweb.org/anthology/2020.acl-main.253)

    *Sergey Edunov, Myle Ott, Marc’Aurelio Ranzato, Michael Auli*

    **Venue**: ACL-2020

8. **Tangled up in BLEU: Reevaluating the Evaluation of Automatic Machine Translation Evaluation Metrics.** [paper](https://www.aclweb.org/anthology/2020.acl-main.448)

    *Nitika Mathur, Timothy Baldwin, Trevor Cohn*

    **Venue**: ACL-2020

9. **Evaluating Robustness to Input Perturbations for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.755/)

    *Xing Niu, Prashant Mathur, Georgiana Dinu, Yaser Al-Onaizan*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/416885789) ; [Paper Reading&Interpretation2](https://blog.csdn.net/weixin_41696015/article/details/118468788?spm=1001.2014.3001.5502)

10. **It’s Easier to Translate out of English than into it: Measuring Neural Translation Difficulty by Cross-Mutual Information.** [paper](https://aclanthology.org/2020.acl-main.149/)

    *Emanuele Bugliarello, Sabrina J. Mielke, Antonios Anastasopoulos, Ryan Cotterell, Naoaki Okazaki*

    **Venue**: ACL-2020

11. **Automatic Machine Translation Evaluation using Source Language Inputs and Cross-lingual Language Model.** [paper](https://aclanthology.org/2020.acl-main.327/)

    *Kosuke Takahashi, Katsuhito Sudoh, Satoshi Nakamura*

    **Venue**: ACL-2020

12. **Online Learning Meets Machine Translation Evaluation: Finding the Best Systems with the Least Human Effort.** [paper](https://aclanthology.org/2021.acl-long.242/)

    *Vânia Mendonça, Ricardo Rei, Luisa Coheur, Alberto Sardinha, Ana Lúcia Santos*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/380822788)；

13. **Difficulty-Aware Machine Translation Evaluation.** [paper](https://aclanthology.org/2021.acl-short.5)

    *Runzhe Zhan, Xuebo Liu, Derek F. Wong, Lidia S. Chao*

    **Venue**: ACL-2021

#### <span id="Reference-free">Reference-free</span>

1. **MUTT: Metric Unit TesTing for Language Generation Tasks.** [paper](https://aclanthology.org/P16-1182)

    *William Boag, Renan Campos, Kate Saenko, Anna Rumshisky*

    **Venue**: ACL-2016

2. **Putting Evaluation in Context: Contextual Embeddings improve Machine Translation Evaluation.** [paper](https://aclanthology.org/P19-1269)

    *Nitika Mathur, Timothy Baldwin, Trevor Cohn*

    **Venue**: ACL-2019

3. **On the Limitations of Cross-lingual Encoders as Exposed by Reference-Free Machine Translation Evaluation.** [paper](https://www.aclweb.org/anthology/2020.acl-main.151)

    *Wei Zhao, Goran Glavaš, Maxime Peyrard, Yang Gao, Robert West, Steffen Eger*

    **Venue**: ACL-2020

4. **Continual Quality Estimation with Online Bayesian Meta-Learning.** [paper](https://aclanthology.org/2021.acl-short.25)

    *Abiola Obamuyide, Marina Fomicheva, Lucia Specia*

    **Venue**: ACL-2021

### <span id="Efficiency">Efficiency</span>

#### <span id="ModelCompression">Model Compression</span>

##### <span id="Pruning">Pruning</span>

##### <span id="KnowledgeDistillation">Knowledge Distillation</span>

1. **Knowledge Distillation for Multilingual Unsupervised Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.324/)

    *Haipeng Sun, Rui Wang, Kehai Chen, Masao Utiyama, Eiichiro Sumita, Tiejun Zhao*

    **Venue**: ACL-2020

2. **Weight Distillation: Transferring the Knowledge in Neural Network Parameters.** [paper](https://aclanthology.org/2021.acl-long.162/)

    *Ye Lin, Yanyang Li, Ziyang Wang, Bei Li, Quan Du, Tong Xiao, Jingbo Zhu*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://blog.csdn.net/gjh1716718326/article/details/119033923)；

3. **Guiding Teacher Forcing with Seer Forcing for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.223/)

    *Yang Feng, Shuhao Gu, Dengji Guo, Zhengxin Yang, Chenze Shao*

    **Venue**: ACL-2021

4. **Marginal Utility Diminishes: Exploring the Minimum Knowledge for BERT Knowledge Distillation.** [paper](https://aclanthology.org/2021.acl-long.228/)

    *Yuanxin Liu, Fandong Meng, Zheng Lin, Weiping Wang, Jie Zhou*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_41485273/article/details/117822718)；

5. **Meta-KD: A Meta Knowledge Distillation Framework for Language Model Compression across Domains.** [paper](https://aclanthology.org/2021.acl-long.236/)

    *Haojie Pan, Chengyu Wang, Minghui Qiu, Yichang Zhang, Yaliang Li, Jun Huang*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://nopsled.blog.csdn.net/article/details/119754960?spm=1001.2014.3001.5502)；

6. **Rejuvenating Low-Frequency Words: Making the Most of Parallel Data in Non-Autoregressive Translation.** [paper](https://aclanthology.org/2021.acl-long.266/)

    *Liang Ding, Longyue Wang, Xuebo Liu, Derek F. Wong, Dacheng Tao, Zhaopeng Tu*

    **Venue**: ACL-2021

7. **Selective Knowledge Distillation for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.504/)

    *Fusheng Wang, Jianhao Yan, Fandong Meng, Jie Zhou*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://nopsled.blog.csdn.net/article/details/121951287?spm=1001.2014.3001.5502)；

##### <span id="Quantization">Quantization</span>

##### <span id="Low-rankFactorization">Low-rank Factorization</span>

##### <span id="WeightSharing">Weight Sharing</span>

1. **Shared-Private Bilingual Word Embeddings for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1352)

    *Xuebo Liu, Derek F. Wong, Yang Liu, Lidia S. Chao, Tong Xiao, Jingbo Zhu*

    **Venue**: ACL-2019

#### <span id="ComputionOptimization">Compution Optimization</span>

1. **N-gram language models for massively parallel devices.** [paper](https://aclanthology.org/P16-1183)

    *Nikolay Bogoychev, Adam Lopez*

    **Venue**: ACL-2016

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_34112900/article/details/86752409)；

2. **Strategies for Training Large Vocabulary Neural Language Models.** [paper](https://aclanthology.org/P16-1186)

    *Wenlin Chen, David Grangier, Michael Auli*

    **Venue**: ACL-2016

3. **Vocabulary Manipulation for Neural Machine Translation.** [paper](https://aclanthology.org/P16-2021/)

    *Haitao Mi, Zhiguo Wang, Abe Ittycheriah*

    **Venue**: ACL-2016

4. **Neural Machine Translation via Binary Code Prediction.** [paper](https://aclanthology.org/P17-1079)

    *Yusuke Oda, Philip Arthur, Graham Neubig, Koichiro Yoshino, Satoshi Nakamura*

    **Venue**: ACL-2017

5. **An Algebra for Feature Extraction.** [paper](https://aclanthology.org/P17-1173)

    *Vivek Srikumar*

    **Venue**: ACL-2017

6. **Speeding Up Neural Machine Translation Decoding by Shrinking Run-time Vocabulary.** [paper](https://aclanthology.org/P17-2091)

    *Xing Shi, Kevin Knight*

    **Venue**: ACL-2017

7. **Accelerating Neural Transformer via an Average Attention Network.** [paper](https://aclanthology.org/P18-1166/)

    *Biao Zhang, Deyi Xiong, Jinsong Su*

    **Venue**: ACL-2018

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/75796168) ; [Paper Reading&Interpretation2](https://blog.csdn.net/wwx123521/article/details/83238989?spm=1001.2014.3001.5502)

8. **Sparse Sequence-to-Sequence Models.** [paper](https://aclanthology.org/P19-1146/)

    *Ben Peters, Vlad Niculae, André F. T. Martins*

    **Venue**: ACL-2019

9. **Multi-Head Highly Parallelized LSTM Decoder for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.23/)

    *Hongfei Xu, Qiuhui Liu, Josef van Genabith, Deyi Xiong, Meng Zhang*

    **Venue**: ACL-2021

#### <span id="EnergyCost">Energy Cost</span>

#### <span id="ConditionalComputation">Conditional Computation</span>

### <span id="Open-sourceSystemsandDatasets">Open-source Systems and Datasets</span>

1. **An Open Web Platform for Rule-Based Speech-to-Sign Translation.** [paper](https://aclanthology.org/P16-2027)

    *Manny Rayner, Pierrette Bouillon, Sarah Ebling, Johanna Gerlach, Irene Strasly, Nikos Tsourakis*

    **Venue**: ACL-2016

2. **An Unsupervised Method for Automatic Translation Memory Cleaning.** [paper](https://aclanthology.org/P16-2047/)

    *Masoud Jalili Sabet, Matteo Negri, Marco Turchi, Eduard Barbu*

    **Venue**: ACL-2016

3. **CCMatrix: Mining Billions of High-Quality Parallel Sentences on the Web.** [paper](https://aclanthology.org/2021.acl-long.507/)

    *Holger Schwenk, Guillaume Wenzek, Sergey Edunov, Edouard Grave, Armand Joulin, Angela Fan*

    **Venue**: ACL-2021

### <span id="TrainingStrategy">Training Strategy</span>

1. **Strategies for Training Large Vocabulary Neural Language Models.** [paper](https://aclanthology.org/P16-1186)

    *Wenlin Chen, David Grangier, Michael Auli*

    **Venue**: ACL-2016

2. **Depth Growing for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1558)

    *Lijun Wu, Yiren Wang, Yingce Xia, Fei Tian, Fei Gao, Tao Qin, Jianhuang Lai, Tie-Yan Liu*

    **Venue**: ACL-2019

3. **Effective Adversarial Regularization for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1020)

    *Motoki Sato, Jun Suzuki, Shun Kiyono*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://blog.csdn.net/DragonBark/article/details/103150354?spm=1001.2014.3001.5502)；

4. **On Exposure Bias, Hallucination and Domain Shift in Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.326/)

    *Chaojun Wang, Rico Sennrich*

    **Venue**: ACL-2020

5. **On Orthogonality Constraints for Transformers.** [paper](https://aclanthology.org/2021.acl-short.48)

    *Aston Zhang, Alvin Chan, Yi Tay, Jie Fu, Shuohang Wang, Shuai Zhang, Huajie Shao, Shuochao Yao, Roy Ka-Wei Lee*

    **Venue**: ACL-2021

6. **Bilingual Mutual Information Based Adaptive Training for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-short.65)

    *Yangyifan Xu, Yijin Liu, Fandong Meng, Jiajun Zhang, Jinan Xu, Jie Zhou*

    **Venue**: ACL-2021

7. **Improving Lexically Constrained Neural Machine Translation with Source-Conditioned Masked Span Prediction.** [paper](https://aclanthology.org/2021.acl-short.94)

    *Gyubok Lee, Seongjun Yang, Edward Choi*

    **Venue**: ACL-2021

#### <span id="ContrastiveLearning">Contrastive Learning</span>

1. **Reducing Word Omission Errors in Neural Machine Translation: A Contrastive Learning Approach.** [paper](https://aclanthology.org/P19-1623)

    *Zonghan Yang, Yong Cheng, Yang Liu, Maosong Sun*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_40676758/article/details/114546304?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://blog.csdn.net/fengdu78/article/details/116725544?spm=1001.2014.3001.5502)

2. **Simultaneous Translation with Flexible Policy via Restricted Imitation Learning.** [paper](https://aclanthology.org/P19-1582/)

    *Baigong Zheng, Renjie Zheng, Mingbo Ma, Liang Huang*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/i70lV_-znoyDhEaU_3yBsw)；

3. **Contrastive Learning for Many-to-many Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.21/)

    *Xiao Pan, Mingxuan Wang, Liwei Wu, Lei Li*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://bbs.gpushare.com/topic/761/%E6%9C%BA%E5%99%A8%E7%BF%BB%E8%AF%91-21-7-mrasp2?_=1640584574620)；

#### <span id="ReinforcementLearning">Reinforcement Learning</span>

1. **Learning Structured Predictors from Bandit Feedback for Interactive NLP.** [paper](https://aclanthology.org/P16-1152)

    *Artem Sokolov, Julia Kreutzer, Christopher Lo, Stefan Riezler*

    **Venue**: ACL-2016

2. **Minimum Risk Training for Neural Machine Translation.** [paper](https://aclanthology.org/P16-1159)

    *Shiqi Shen, Yong Cheng, Zhongjun He, Wei He, Hua Wu, Maosong Sun, Yang Liu*

    **Venue**: ACL-2016

#### <span id="MetaLearning">Meta Learning</span>

1. **Meta-Learning to Compositionally Generalize.** [paper](https://aclanthology.org/2021.acl-long.258/)

    *Henry Conklin, Bailin Wang, Kenny Smith, Ivan Titov*

    **Venue**: ACL-2021

2. **Continual Quality Estimation with Online Bayesian Meta-Learning.** [paper](https://aclanthology.org/2021.acl-short.25)

    *Abiola Obamuyide, Marina Fomicheva, Lucia Specia*

    **Venue**: ACL-2021

#### <span id="DualLearning">Dual Learning</span>

#### <span id="GenerativeAdversarialNetworks">Generative Adversarial Networks</span>

1. **Adversarial Adaptation of Synthetic or Stale Data.** [paper](https://aclanthology.org/P17-1119)

    *Young-Bum Kim, Karl Stratos, Dongchan Kim*

    **Venue**: ACL-2017

2. **A Sweet Rabbit Hole by DARCY: Using Honeypots to Detect Universal Trigger’s Adversarial Attacks.** [paper](https://aclanthology.org/2021.acl-long.296/)

    *Thai Le, Noseong Park, Dongwon Lee*

    **Venue**: ACL-2021

### <span id="Inference">Inference</span>

1. **Enhanced LSTM for Natural Language Inference.** [paper](https://aclanthology.org/P17-1152)

    *Qian Chen, Xiaodan Zhu, Zhen-Hua Ling, Si Wei, Hui Jiang, Diana Inkpen*

    **Venue**: ACL-2017

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38526306/article/details/88045134) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/141622985) ; [Paper Reading&Interpretation3](https://zhuanlan.zhihu.com/p/350933915) ; [Paper Reading&Interpretation4](https://zhuanlan.zhihu.com/p/366340728) ; [Paper Reading&Interpretation5](https://zhuanlan.zhihu.com/p/47580077)

2. **Chunk-based Decoder for Neural Machine Translation.** [paper](https://aclanthology.org/P17-1174)

    *Shonosuke Ishiwatari, Jingtao Yao, Shujie Liu, Mu Li, Ming Zhou, Naoki Yoshinaga, Masaru Kitsuregawa, Weijia Jia*

    **Venue**: ACL-2017

#### <span id="Non-autoregressive">Non-autoregressive</span>

1. **Imitation Learning for Non-Autoregressive Neural Machine Translation.** [paper](https://aclanthology.org/P19-1125/)

    *Bingzhen Wei, Mingxuan Wang, Hao Zhou, Junyang Lin, Xu Sun*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/XVFp3l7iDJp-0_mJhSe17Q)；

2. **Retrieving Sequential Information for Non-Autoregressive Neural Machine Translation.** [paper](https://aclanthology.org/P19-1288/)

    *Chenze Shao, Yang Feng, Jinchao Zhang, Fandong Meng, Xilin Chen, Jie Zhou*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/E6E6tc2uDJofuNDJArB5RQ)；

3. **Jointly Masked Sequence-to-Sequence Model for Non-Autoregressive Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.36/)

    *Junliang Guo, Linli Xu, Enhong Chen*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/uMz-cAyZfXqIH-le38luEw)；

4. **Learning to Recover from Multi-Modality Errors for Non-Autoregressive Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.277/)

    *Qiu Ran, Yankai Lin, Peng Li, Jie Zhou*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/HFqkigKldOHt1JS7rQCqpQ) ; [Paper Reading&Interpretation2](https://nopsled.blog.csdn.net/article/details/115004440?spm=1001.2014.3001.5502)

5. **ENGINE: Energy-Based Inference Networks for Non-Autoregressive Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.251/)

    *Lifu Tu, Richard Yuanzhe Pang, Sam Wiseman, Kevin Gimpel*

    **Venue**: ACL-2020

6. **Glancing Transformer for Non-Autoregressive Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.155/)

    *Lihua Qian, Hao Zhou, Yu Bao, Mingxuan Wang, Lin Qiu, Weinan Zhang, Yong Yu, Lei Li*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/392167557) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/395824887)

#### <span id="ConstrainedInference">Constrained Inference</span>

##### <span id="InteractiveNMT">Interactive NMT</span>

1. **Models and Inference for Prefix-Constrained Machine Translation.** [paper](https://aclanthology.org/P16-1007)

    *Joern Wuebker, Spence Green, John DeNero, Saša Hasan, Minh-Thang Luong*

    **Venue**: ACL-2016

2. **Lexically Constrained Decoding for Sequence Generation Using Grid Beam Search.** [paper](https://aclanthology.org/P17-1141)

    *Chris Hokamp, Qun Liu*

    **Venue**: ACL-2017

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/62523524) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/441751333)

##### <span id="AutomaticPost-Editing">Automatic Post-Editing</span>

1. **Lexically Constrained Neural Machine Translation with Levenshtein Transformer.** [paper](https://aclanthology.org/2020.acl-main.325/)

    *Raymond Hendy Susanto, Shamil Chollampatt, Liling Tan*

    **Venue**: ACL-2020

2. **GWLAN: General Word-Level AutocompletioN for Computer-Aided Translation.** [paper](https://aclanthology.org/2021.acl-long.370)

    *Huayang Li, Lemao Liu, Guoping Huang, Shuming Shi*

    **Venue**: ACL-2021

3. **Mid-Air Hand Gestures for Post-Editing of Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.527)

    *Rashad Albo Jamara, Nico Herbig, Antonio Krüger, Josef van Genabith*

    **Venue**: ACL-2021

##### <span id="RestrictedNMT">Restricted NMT</span>

1. **Synthesizing Compound Words for Machine Translation.** [paper](https://aclanthology.org/P16-1103/)

    *Austin Matthews, Eva Schlinger, Alon Lavie, Chris Dyer*

    **Venue**: ACL-2016

2. **Syntactically Supervised Transformers for Faster Neural Machine Translation.** [paper](https://aclanthology.org/P19-1122/)

    *Nader Akoury, Kalpesh Krishna, Mohit Iyyer*

    **Venue**: ACL-2019

3. **Lexically Constrained Neural Machine Translation with Levenshtein Transformer.** [paper](https://aclanthology.org/2020.acl-main.325/)

    *Raymond Hendy Susanto, Shamil Chollampatt, Liling Tan*

    **Venue**: ACL-2020

4. **Prevent the Language Model from being Overconfident in Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.268/)

    *Mengqi Miao, Fandong Meng, Yijin Liu, Xiao-Hua Zhou, Jie Zhou*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://nopsled.blog.csdn.net/article/details/121746619?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/424116870)

5. **End-to-End Lexically Constrained Machine Translation for Morphologically Rich Languages.** [paper](https://aclanthology.org/2021.acl-long.311/)

    *Josef Jon, João Paulo Aires, Dusan Varis, Ondřej Bojar*

    **Venue**: ACL-2021

6. **Adaptive Nearest Neighbor Machine Translation.** [paper](https://aclanthology.org/2021.acl-short.47)

    *Xin Zheng, Zhirui Zhang, Junliang Guo, Shujian Huang, Boxing Chen, Weihua Luo, Jiajun Chen*

    **Venue**: ACL-2021

#### <span id="BeamSearch">Beam Search</span>

1. **Determinantal Beam Search.** [paper](https://aclanthology.org/2021.acl-long.512/)

    *Clara Meister, Martina Forster, Ryan Cotterell*

    **Venue**: ACL-2021

### <span id="Interpretability">Interpretability</span>

1. **Grammatical Error Correction: Machine Translation and Classifiers.** [paper](https://aclanthology.org/P16-1208)

    *Alla Rozovskaya, Dan Roth*

    **Venue**: ACL-2016

2. **What do Neural Machine Translation Models Learn about Morphology?.** [paper](https://aclanthology.org/P17-1080)

    *Yonatan Belinkov, Nadir Durrani, Fahim Dalvi, Hassan Sajjad, James Glass*

    **Venue**: ACL-2017

3. **Visualizing and Understanding Neural Machine Translation.** [paper](https://aclanthology.org/P17-1106)

    *Yanzhuo Ding, Yang Liu, Huanbo Luan, Maosong Sun*

    **Venue**: ACL-2017

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/27349828)；

4. **In Neural Machine Translation, What Does Transfer Learning Transfer?.** [paper](https://aclanthology.org/2020.acl-main.688/)

    *Alham Fikri Aji, Nikolay Bogoychev, Kenneth Heafield, Rico Sennrich*

    **Venue**: ACL-2020

5. **Evaluating Explanation Methods for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.35/)

    *Jierui Li, Lemao Liu, Huayang Li, Guanlin Li, Guoping Huang, Shuming Shi*

    **Venue**: ACL-2020

6. **Does Multi-Encoder Help? A Case Study on Context-Aware Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.322)

    *Bei Li, Hui Liu, Ziyang Wang, Yufan Jiang, Tong Xiao, Jingbo Zhu, Tongran Liu, Changliang Li*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://blog.csdn.net/xiao_xian_/article/details/108441933?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://blog.csdn.net/c9Yv2cf9I06K2A9E/article/details/106964479?spm=1001.2014.3001.5502)

7. **Understanding the Properties of Minimum Bayes Risk Decoding in Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.22/)

    *Mathias Müller, Rico Sennrich*

    **Venue**: ACL-2021

8. **Do Context-Aware Translation Models Pay the Right Attention?.** [paper](https://aclanthology.org/2021.acl-long.65/)

    *Kayo Yin, Patrick Fernandes, Danish Pruthi, Aditi Chaudhary, André F. T. Martins, Graham Neubig*

    **Venue**: ACL-2021

9. **The statistical advantage of automatic NLG metrics at the system level.** [paper](https://aclanthology.org/2021.acl-long.533)

    *Johnny Wei, Robin Jia*

    **Venue**: ACL-2021

### <span id="Ensemble">Ensemble</span>

1. **A Nested Attention Neural Hybrid Model for Grammatical Error Correction.** [paper](https://aclanthology.org/P17-1070)

    *Jianshu Ji, Qinlong Wang, Kristina Toutanova, Yongen Gong, Steven Truong, Jianfeng Gao*

    **Venue**: ACL-2017

2. **Neural System Combination for Machine Translation.** [paper](https://aclanthology.org/P17-2060/)

    *Long Zhou, Wenpeng Hu, Jiajun Zhang, Chengqing Zong*

    **Venue**: ACL-2017

### <span id="Reranking">Reranking</span>

1. **Energy-Based Reranking: Improving Neural Machine Translation Using Energy-Based Models.** [paper](https://aclanthology.org/2021.acl-long.349)

    *Sumanta Bhattacharyya, Amirmohammad Rooshenas, Subhajit Naskar, Simeng Sun, Mohit Iyyer, Andrew McCallum*

    **Venue**: ACL-2021

2. **Discriminative Reranking for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.563)

    *Ann Lee, Michael Auli, Marc’Aurelio Ranzato*

    **Venue**: ACL-2021

### <span id="ModelArchitecture">Model Architecture</span>

1. **Pointing the Unknown Words.** [paper](https://aclanthology.org/P16-1014/)

    *Caglar Gulcehre, Sungjin Ahn, Ramesh Nallapati, Bowen Zhou, Yoshua Bengio*

    **Venue**: ACL-2016

    [Paper Reading&Interpretation1](https://blog.csdn.net/sanra123/article/details/87917588?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/36368316) ; [Paper Reading&Interpretation3](https://zhuanlan.zhihu.com/p/73590690)

2. **Tree-to-Sequence Attentional Neural Machine Translation.** [paper](https://aclanthology.org/P16-1078/)

    *Akiko Eriguchi, Kazuma Hashimoto, Yoshimasa Tsuruoka*

    **Venue**: ACL-2016

3. **Achieving Open Vocabulary Neural Machine Translation with Hybrid Word-Character Models.** [paper](https://aclanthology.org/P16-1100/)

    *Minh-Thang Luong, Christopher D. Manning*

    **Venue**: ACL-2016

    [Paper Reading&Interpretation1](https://blog.csdn.net/u011414416/article/details/51108193)；

4. **A Character-level Decoder without Explicit Segmentation for Neural Machine Translation.** [paper](https://aclanthology.org/P16-1160)

    *Junyoung Chung, Kyunghyun Cho, Yoshua Bengio*

    **Venue**: ACL-2016

5. **Supersense Embeddings: A Unified Model for Supersense Interpretation, Prediction, and Utilization.** [paper](https://aclanthology.org/P16-1191)

    *Lucie Flekova, Iryna Gurevych*

    **Venue**: ACL-2016

6. **Knowledge-Based Semantic Embedding for Machine Translation.** [paper](https://aclanthology.org/P16-1212)

    *Chen Shi, Shujie Liu, Shuo Ren, Shi Feng, Mu Li, Ming Zhou, Xu Sun, Houfeng Wang*

    **Venue**: ACL-2016

7. **Graph-based Dependency Parsing with Bidirectional LSTM.** [paper](https://aclanthology.org/P16-1218)

    *Wenhui Wang, Baobao Chang*

    **Venue**: ACL-2016

8. **Character-based Neural Machine Translation.** [paper](https://aclanthology.org/P16-2058/)

    *Marta R. Costa-jussà, José A. R. Fonollosa*

    **Venue**: ACL-2016

9. **A Convolutional Encoder Model for Neural Machine Translation.** [paper](https://aclanthology.org/P17-1012)

    *Jonas Gehring, Michael Auli, David Grangier, Yann Dauphin*

    **Venue**: ACL-2017

    [Paper Reading&Interpretation1](https://blog.csdn.net/Xiao_yanling/article/details/92064214) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/30515849)

10. **Deep Neural Machine Translation with Linear Associative Unit.** [paper](https://aclanthology.org/P17-1013)

    *Mingxuan Wang, Zhengdong Lu, Jie Zhou, Qun Liu*

    **Venue**: ACL-2017

11. **Improved Neural Machine Translation with a Syntax-Aware Encoder and Decoder.** [paper](https://aclanthology.org/P17-1177)

    *Huadong Chen, Shujian Huang, David Chiang, Jiajun Chen*

    **Venue**: ACL-2017

12. **Learning to Parse and Translate Improves Neural Machine Translation.** [paper](https://aclanthology.org/P17-2012)

    *Akiko Eriguchi, Yoshimasa Tsuruoka, Kyunghyun Cho*

    **Venue**: ACL-2017

13. **Hybrid Neural Network Alignment and Lexicon Model in Direct HMM for Statistical Machine Translation.** [paper](https://aclanthology.org/P17-2020)

    *Weiyue Wang, Tamer Alkhouli, Derui Zhu, Hermann Ney*

    **Venue**: ACL-2017

14. **Towards String-To-Tree Neural Machine Translation.** [paper](https://aclanthology.org/P17-2021)

    *Roee Aharoni, Yoav Goldberg*

    **Venue**: ACL-2017

15. **Chunk-Based Bi-Scale Decoder for Neural Machine Translation.** [paper](https://aclanthology.org/P17-2092/)

    *Hao Zhou, Zhaopeng Tu, Shujian Huang, Xiaohua Liu, Hang Li, Jiajun Chen*

    **Venue**: ACL-2017

16. **The Best of Both Worlds: Combining Recent Advances in Neural Machine Translation.** [paper](https://aclanthology.org/P18-1008/)

    *Mia Xu Chen, Orhan Firat, Ankur Bapna, Melvin Johnson, Wolfgang Macherey, George Foster, Llion Jones, Mike Schuster, Noam Shazeer, Niki Parmar, Ashish Vaswani, Jakob Uszkoreit, Lukasz Kaiser, Zhifeng Chen, Yonghui Wu, Macduff Hughes*

    **Venue**: ACL-2018

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/415071203)；

17. **Neural Hidden Markov Model for Machine Translation.** [paper](https://aclanthology.org/P18-2060/)

    *Weiyue Wang, Derui Zhu, Tamer Alkhouli, Zixuan Gan, Hermann Ney*

    **Venue**: ACL-2018

18. **A Stochastic Decoder for Neural Machine Translation.** [paper](https://aclanthology.org/P18-1115/)

    *Philip Schulz, Wilker Aziz, Trevor Cohn*

    **Venue**: ACL-2018

19. **Forest-Based Neural Machine Translation.** [paper](https://aclanthology.org/P18-1116/)

    *Chunpeng Ma, Akihiro Tamura, Masao Utiyama, Tiejun Zhao, Eiichiro Sumita*

    **Venue**: ACL-2018

    [Paper Reading&Interpretation1](https://blog.csdn.net/u014475479/article/details/81538819?spm=1001.2014.3001.5502)；

20. **Learning Deep Transformer Models for Machine Translation.** [paper](https://aclanthology.org/P19-1176/)

    *Qiang Wang, Bei Li, Tong Xiao, Jingbo Zhu, Changliang Li, Derek F. Wong, Lidia S. Chao*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/NehJOAC0_nOPWES9KsoE4A)；

21. **Bridging the Gap between Training and Inference for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1426/)

    *Wen Zhang, Yang Feng, Fandong Meng, Di You, Qun Liu*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/99738265) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/82548568) ; [Paper Reading&Interpretation3](https://zhuanlan.zhihu.com/p/82049108) ; [Paper Reading&Interpretation4](https://blog.csdn.net/Xiao_yanling/article/details/102620839?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation5](https://blog.csdn.net/iling5/article/details/101681405?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation6](https://blog.csdn.net/boywaiter/article/details/102908902?spm=1001.2014.3001.5502)

22. **Exploiting Sentential Context for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1624/)

    *Xing Wang, Zhaopeng Tu, Longyue Wang, Shuming Shi*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/q8Va0IJ3hkFQFDZo6pEZng)；

23. **Depth Growing for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1558)

    *Lijun Wu, Yiren Wang, Yingce Xia, Fei Tian, Fei Gao, Tao Qin, Jianhuang Lai, Tie-Yan Liu*

    **Venue**: ACL-2019

24. **Sentence-Level Agreement for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1296)

    *Mingming Yang, Rui Wang, Kehai Chen, Masao Utiyama, Eiichiro Sumita, Min Zhang, Tiejun Zhao*

    **Venue**: ACL-2019

25. **Addressing Posterior Collapse with Mutual Information for Improved Variational Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.753/)

    *Arya D. McCarthy, Xian Li, Jiatao Gu, Ning Dong*

    **Venue**: ACL-2020

26. **Multiscale Collaborative Deep Models for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.40)

    *Xiangpeng Wei, Heng Yu, Yue Hu, Yue Zhang, Rongxiang Weng, Weihua Luo*

    **Venue**: ACL-2020

27. **Improving Neural Machine Translation with Soft Template Prediction.** [paper](https://aclanthology.org/2020.acl-main.531/)

    *Jian Yang, Shuming Ma, Dongdong Zhang, Zhoujun Li, Ming Zhou*

    **Venue**: ACL-2020

28. **Learning Source Phrase Representations for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.37/)

    *Hongfei Xu, Josef van Genabith, Deyi Xiong, Qiuhui Liu, Jingyi Zhang*

    **Venue**: ACL-2020

29. **Regularized Context Gates on Transformer for Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.757/)

    *Xintong Li, Lemao Liu, Rui Wang, Guoping Huang, Max Meng*

    **Venue**: ACL-2020

30. **Character-Level Translation with Self-attention.** [paper](https://aclanthology.org/2020.acl-main.145/)

    *Yingqiang Gao, Nikola I. Nikolov, Yuhuang Hu, Richard H.R. Hahnloser*

    **Venue**: ACL-2020

31. **Variational Neural Machine Translation with Normalizing Flows.** [paper](https://aclanthology.org/2020.acl-main.694/)

    *Hendra Setiawan, Matthias Sperber, Udhyakumar Nallasamy, Matthias Paulik*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/294966561)；

32. **A Simple and Effective Unified Encoder for Document-Level Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.321/)

    *Shuming Ma, Dongdong Zhang, Ming Zhou*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/358639090)；

33. **Guiding Teacher Forcing with Seer Forcing for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.223/)

    *Yang Feng, Shuhao Gu, Dengji Guo, Zhengxin Yang, Chenze Shao*

    **Venue**: ACL-2021

34. **Fast and Accurate Neural Machine Translation with Translation Memory.** [paper](https://aclanthology.org/2021.acl-long.246/)

    *Qiuxiang He, Guoping Huang, Qu Cui, Li Li, Lemao Liu*

    **Venue**: ACL-2021

35. **Point, Disambiguate and Copy: Incorporating Bilingual Dictionaries for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.307/)

    *Tong Zhang, Long Zhang, Wei Ye, Bo Li, Jinan Sun, Xiaoyu Zhu, Wen Zhao, Shikun Zhang*

    **Venue**: ACL-2021

36. **Towards User-Driven Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.310/)

    *Huan Lin, Liang Yao, Baosong Yang, Dayiheng Liu, Haibo Zhang, Weihua Luo, Degen Huang, Jinsong Su*

    **Venue**: ACL-2021

37. **Reservoir Transformers.** [paper](https://aclanthology.org/2021.acl-long.331)

    *Sheng Shen, Alexei Baevski, Ari Morcos, Kurt Keutzer, Michael Auli, Douwe Kiela*

    **Venue**: ACL-2021

38. **Rewriter-Evaluator Architecture for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.443)

    *Yangming Li, Kaisheng Yao*

    **Venue**: ACL-2021

### <span id="PriorKnowledge">Prior Knowledge</span>

1. **Tree-to-Sequence Attentional Neural Machine Translation.** [paper](https://aclanthology.org/P16-1078/)

    *Akiko Eriguchi, Kazuma Hashimoto, Yoshimasa Tsuruoka*

    **Venue**: ACL-2016

2. **Syntactically Guided Neural Machine Translation.** [paper](https://aclanthology.org/P16-2049/)

    *Felix Stahlberg, Eva Hasler, Aurelien Waite, Bill Byrne*

    **Venue**: ACL-2016

3. **Modeling Source Syntax for Neural Machine Translation.** [paper](https://aclanthology.org/P17-1064)

    *Junhui Li, Deyi Xiong, Zhaopeng Tu, Muhua Zhu, Min Zhang, Guodong Zhou*

    **Venue**: ACL-2017

4. **Sequence-to-Dependency Neural Machine Translation.** [paper](https://aclanthology.org/P17-1065)

    *Shuangzhi Wu, Dongdong Zhang, Nan Yang, Mu Li, Ming Zhou*

    **Venue**: ACL-2017

    [Paper Reading&Interpretation1](https://blog.csdn.net/appleml/article/details/77835921)；

5. **Automatic Annotation and Evaluation of Error Types for Grammatical Error Correction.** [paper](https://aclanthology.org/P17-1074)

    *Christopher Bryant, Mariano Felice, Ted Briscoe*

    **Venue**: ACL-2017

6. **Robust Incremental Neural Semantic Graph Parsing.** [paper](https://aclanthology.org/P17-1112)

    *Jan Buys, Phil Blunsom*

    **Venue**: ACL-2017

7. **Prior Knowledge Integration for Neural Machine Translation using Posterior Regularization.** [paper](https://aclanthology.org/P17-1139)

    *Jiacheng Zhang, Yang Liu, Huanbo Luan, Jingfang Xu, Maosong Sun*

    **Venue**: ACL-2017

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_37625243/article/details/88374840) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/31659142)

8. **Neural Machine Translation with Reordering Embeddings.** [paper](https://aclanthology.org/P19-1174/)

    *Kehai Chen, Rui Wang, Masao Utiyama, Eiichiro Sumita*

    **Venue**: ACL-2019

9. **On the Word Alignment from Neural Machine Translation.** [paper](https://aclanthology.org/P19-1124/)

    *Xintong Li, Guanlin Li, Lemao Liu, Max Meng, Shuming Shi*

    **Venue**: ACL-2019

10. **Reference Network for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1287/)

    *Han Fu, Chenghao Liu, Jianling Sun*

    **Venue**: ACL-2019

11. **Training Neural Machine Translation To Apply Terminology Constraints.** [paper](https://aclanthology.org/P19-1294/)

    *Georgiana Dinu, Prashant Mathur, Marcello Federico, Yaser Al-Onaizan*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_24367797/article/details/108754346?spm=1001.2014.3001.5502)；

12. **Better OOV Translation with Bilingual Terminology Mining.** [paper](https://aclanthology.org/P19-1581)

    *Matthias Huck, Viktor Hangya, Alexander Fraser*

    **Venue**: ACL-2019

13. **Lattice-Based Transformer Encoder for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1298/)

    *Fengshun Xiao, Jiangtong Li, Hai Zhao, Rui Wang, Kehai Chen*

    **Venue**: ACL-2019

14. **Improving Neural Machine Translation with Soft Template Prediction.** [paper](https://aclanthology.org/2020.acl-main.531/)

    *Jian Yang, Shuming Ma, Dongdong Zhang, Zhoujun Li, Ming Zhou*

    **Venue**: ACL-2020

15. **Translationese as a Language in “Multilingual” NMT.** [paper](https://aclanthology.org/2020.acl-main.691/)

    *Parker Riley, Isaac Caswell, Markus Freitag, David Grangier*

    **Venue**: ACL-2020

16. **Enhancing Machine Translation with Dependency-Aware Self-Attention.** [paper](https://aclanthology.org/2020.acl-main.147/)

    *Emanuele Bugliarello, Naoaki Okazaki*

    **Venue**: ACL-2020

17. **Content Word Aware Neural Machine Translation.** [paper](https://www.aclweb.org/anthology/2020.acl-main.34)

    *Kehai Chen, Rui Wang, Masao Utiyama, Eiichiro Sumita*

    **Venue**: ACL-2020

18. **Neural Machine Translation with Monolingual Translation Memory.** [paper](https://aclanthology.org/2021.acl-long.567)

    *Deng Cai, Yan Wang, Huayang Li, Wai Lam, Lemao Liu*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/5HR04WW_EmoKy7414rzrZQ) ; [Paper Reading&Interpretation2](https://blog.csdn.net/qq_42341984/article/details/119535281) ; [Paper Reading&Interpretation3](https://zhuanlan.zhihu.com/p/397888408) ; [Paper Reading&Interpretation4](https://zhuanlan.zhihu.com/p/387147408)

### <span id="AttentionMechanism">Attention Mechanism</span>

1. **Modeling Coverage for Neural Machine Translation.** [paper](https://aclanthology.org/P16-1008/)

    *Zhaopeng Tu, Zhengdong Lu, Yang Liu, Xiaohua Liu, Hang Li*

    **Venue**: ACL-2016

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/wnYGIbEuQ3QHQ8X5ElaVoA) ; [Paper Reading&Interpretation2](https://mp.weixin.qq.com/s/kmS8CewYOyEHD_MHolfihw) ; [Paper Reading&Interpretation3](https://blog.csdn.net/u011414416/article/details/51567254) ; [Paper Reading&Interpretation4](https://zhuanlan.zhihu.com/p/22993927)

2. **Incorporating Word Reordering Knowledge into Attention-based Neural Machine Translation.** [paper](https://aclanthology.org/P17-1140)

    *Jinchao Zhang, Mingxuan Wang, Qun Liu, Jie Zhou*

    **Venue**: ACL-2017

3. **Attention Strategies for Multi-Source Sequence-to-Sequence Learning.** [paper](https://aclanthology.org/P17-2031/)

    *Jindřich Libovický, Jindřich Helcl*

    **Venue**: ACL-2017

4. **Attention Focusing for Neural Machine Translation by Bridging Source and Target Embeddings.** [paper](https://aclanthology.org/P18-1164/)

    *Shaohui Kuang, Junhui Li, Antonio Branco, Weihua Luo, Deyi Xiong*

    **Venue**: ACL-2018

    [Paper Reading&Interpretation1](https://blog.csdn.net/Doron15/article/details/83033275?spm=1001.2014.3001.5502)；

5. **Accelerating Neural Transformer via an Average Attention Network.** [paper](https://aclanthology.org/P18-1166/)

    *Biao Zhang, Deyi Xiong, Jinsong Su*

    **Venue**: ACL-2018

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/75796168) ; [Paper Reading&Interpretation2](https://blog.csdn.net/wwx123521/article/details/83238989?spm=1001.2014.3001.5502)

6. **Look Harder: A Neural Machine Translation Model with Hard Attention.** [paper](https://aclanthology.org/P19-1290/)

    *Sathish Reddy Indurthi, Insoo Chung, Sangha Kim*

    **Venue**: ACL-2019

7. **Lattice-Based Transformer Encoder for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1298/)

    *Fengshun Xiao, Jiangtong Li, Hai Zhao, Rui Wang, Kehai Chen*

    **Venue**: ACL-2019

8. **Hard-Coded Gaussian Attention for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.687)

    *Weiqiu You, Simeng Sun, Mohit Iyyer*

    **Venue**: ACL-2020

9. **Learning Source Phrase Representations for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.37/)

    *Hongfei Xu, Josef van Genabith, Deyi Xiong, Qiuhui Liu, Jingyi Zhang*

    **Venue**: ACL-2020

10. **Cascaded Head-colliding Attention.** [paper](https://aclanthology.org/2021.acl-long.45/)

    *Lin Zheng, Zhiyong Wu, Lingpeng Kong*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/jq_wA_nKKJNMffJU1LzUMA)；

11. **Do Context-Aware Translation Models Pay the Right Attention?.** [paper](https://aclanthology.org/2021.acl-long.65/)

    *Kayo Yin, Patrick Fernandes, Danish Pruthi, Aditi Chaudhary, André F. T. Martins, Graham Neubig*

    **Venue**: ACL-2021

### <span id="DomainAdaptation">Domain Adaptation</span>

1. **Can Syntax Help? Improving an LSTM-based Sentence Compression Model for New Domains.** [paper](https://aclanthology.org/P17-1127)

    *Liangguo Wang, Jing Jiang, Hai Leong Chieu, Chen Hui Ong, Dandan Song, Lejian Liao*

    **Venue**: ACL-2017

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_30219017/article/details/86839487)；

2. **Bandit Structured Prediction for Neural Sequence-to-Sequence Learning.** [paper](https://aclanthology.org/P17-1138)

    *Julia Kreutzer, Artem Sokolov, Stefan Riezler*

    **Venue**: ACL-2017

3. **An Empirical Comparison of Domain Adaptation Methods for Neural Machine Translation.** [paper](https://aclanthology.org/P17-2061/)

    *Chenhui Chu, Raj Dabre, Sadao Kurohashi*

    **Venue**: ACL-2017

4. **Sentence Embedding for Neural Machine Translation Domain Adaptation.** [paper](https://aclanthology.org/P17-2089)

    *Rui Wang, Andrew Finch, Masao Utiyama, Eiichiro Sumita*

    **Venue**: ACL-2017

5. **Domain Adaptation of Neural Machine Translation by Lexicon Induction.** [paper](https://aclanthology.org/P19-1286/)

    *Junjie Hu, Mengzhou Xia, Graham Neubig, Jaime Carbonell*

    **Venue**: ACL-2019

6. **Domain Adaptive Inference for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1022/)

    *Danielle Saunders, Felix Stahlberg, Adrià de Gispert, Bill Byrne*

    **Venue**: ACL-2019

7. **Learning a Multi-Domain Curriculum for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.689/)

    *Wei Wang, Ye Tian, Jiquan Ngiam, Yinfei Yang, Isaac Caswell, Zarana Parekh*

    **Venue**: ACL-2020

8. **Multi-Domain Neural Machine Translation with Word-Level Adaptive Layer-wise Domain Mixing.** [paper](https://aclanthology.org/2020.acl-main.165/)

    *Haoming Jiang, Chen Liang, Chong Wang, Tuo Zhao*

    **Venue**: ACL-2020

9. **Reducing Gender Bias in Neural Machine Translation as a Domain Adaptation Problem.** [paper](https://aclanthology.org/2020.acl-main.690/)

    *Danielle Saunders, Bill Byrne*

    **Venue**: ACL-2020

10. **Unsupervised Neural Machine Translation for Low-Resource Domains via Meta-Learning.** [paper](https://aclanthology.org/2021.acl-long.225/)

    *Cheonbok Park, Yunwon Tae, TaeHee Kim, Soyoung Yang, Mohammad Azam Khan, Lucy Park, Jaegul Choo*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_30232405/article/details/120903124)；

11. **Meta-KD: A Meta Knowledge Distillation Framework for Language Model Compression across Domains.** [paper](https://aclanthology.org/2021.acl-long.236/)

    *Haojie Pan, Chengyu Wang, Minghui Qiu, Yichang Zhang, Yaliang Li, Jun Huang*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://nopsled.blog.csdn.net/article/details/119754960?spm=1001.2014.3001.5502)；

12. **Taming Pre-trained Language Models with N-gram Representations for Low-Resource Domain Adaptation.** [paper](https://aclanthology.org/2021.acl-long.259/)

    *Shizhe Diao, Ruijia Xu, Hongjin Su, Yilei Jiang, Yan Song, Tong Zhang*

    **Venue**: ACL-2021

### <span id="TransferLearning">Transfer Learning</span>

1. **One-Shot Neural Cross-Lingual Transfer for Paradigm Completion.** [paper](https://aclanthology.org/P17-1182)

    *Katharina Kann, Ryan Cotterell, Hinrich Schütze*

    **Venue**: ACL-2017

2. **Revisiting Recurrent Networks for Paraphrastic Sentence Embeddings.** [paper](https://aclanthology.org/P17-1190)

    *John Wieting, Kevin Gimpel*

    **Venue**: ACL-2017

3. **Effective Cross-lingual Transfer of Neural Machine Translation Models without Shared Vocabularies.** [paper](https://aclanthology.org/P19-1120/)

    *Yunsu Kim, Yingbo Gao, Hermann Ney*

    **Venue**: ACL-2019

4. **Dynamically Composing Domain-Data Selection with Clean-Data Selection by "Co-Curricular Learning" for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1123/)

    *Wei Wang, Isaac Caswell, Ciprian Chelba*

    **Venue**: ACL-2019

### <span id="Pre-training">Pre-training</span>

1. **Unsupervised Bilingual Word Embedding Agreement for Unsupervised Neural Machine Translation.** [paper](https://aclanthology.org/P19-1119/)

    *Haipeng Sun, Rui Wang, Kehai Chen, Masao Utiyama, Eiichiro Sumita, Tiejun Zhao*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38937984/article/details/102388490?spm=1001.2014.3001.5502)；

2. **BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension.** [paper](https://aclanthology.org/2020.acl-main.703/)

    *Mike Lewis, Yinhan Liu, Naman Goyal, Marjan Ghazvininejad, Abdelrahman Mohamed, Omer Levy, Veselin Stoyanov, Luke Zettlemoyer*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/121788986) ; [Paper Reading&Interpretation2](https://blog.csdn.net/chansonzhang/article/details/120474056?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation3](https://forlogen.blog.csdn.net/article/details/102866116?spm=1001.2014.3001.5502)

3. **Curriculum Pre-training for End-to-End Speech Translation.** [paper](https://aclanthology.org/2020.acl-main.344/)

    *Chengyi Wang, Yu Wu, Shujie Liu, Ming Zhou, Zhenglu Yang*

    **Venue**: ACL-2020

4. **Multilingual Speech Translation from Efficient Finetuning of Pretrained Models.** [paper](https://aclanthology.org/2021.acl-long.68/)

    *Xian Li, Changhan Wang, Yun Tang, Chau Tran, Yuqing Tang, Juan Pino, Alexei Baevski, Alexis Conneau, Michael Auli*

    **Venue**: ACL-2021

5. **Exploiting Language Relatedness for Low Web-Resource Language Model Adaptation: An Indic Languages Study.** [paper](https://aclanthology.org/2021.acl-long.105/)

    *Yash Khemchandani, Sarvesh Mehtani, Vaidehi Patil, Abhijeet Awasthi, Partha Talukdar, Sunita Sarawagi*

    **Venue**: ACL-2021

6. **Breaking the Corpus Bottleneck for Context-Aware Neural Machine Translation with Cross-Task Pre-training.** [paper](https://aclanthology.org/2021.acl-long.222/)

    *Linqing Chen, Junhui Li, Zhengxian Gong, Boxing Chen, Weihua Luo, Min Zhang, Guodong Zhou*

    **Venue**: ACL-2021

7. **Marginal Utility Diminishes: Exploring the Minimum Knowledge for BERT Knowledge Distillation.** [paper](https://aclanthology.org/2021.acl-long.228/)

    *Yuanxin Liu, Fandong Meng, Zheng Lin, Weiping Wang, Jie Zhou*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_41485273/article/details/117822718)；

8. **LeeBERT: Learned Early Exit for BERT with cross-level optimization.** [paper](https://aclanthology.org/2021.acl-long.231/)

    *Wei Zhu*

    **Venue**: ACL-2021

9. **How Good is Your Tokenizer? On the Monolingual Performance of Multilingual Language Models.** [paper](https://aclanthology.org/2021.acl-long.243/)

    *Phillip Rust, Jonas Pfeiffer, Ivan Vulić, Sebastian Ruder, Iryna Gurevych*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/403177621)；

10. **Rejuvenating Low-Frequency Words: Making the Most of Parallel Data in Non-Autoregressive Translation.** [paper](https://aclanthology.org/2021.acl-long.266/)

    *Liang Ding, Longyue Wang, Xuebo Liu, Derek F. Wong, Dacheng Tao, Zhaopeng Tu*

    **Venue**: ACL-2021

11. **VECO: Variable and Flexible Cross-lingual Pre-training for Language Understanding and Generation.** [paper](https://aclanthology.org/2021.acl-long.308/)

    *Fuli Luo, Wei Wang, Jiahao Liu, Yijia Liu, Bin Bi, Songfang Huang, Fei Huang, Luo Si*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/401333337)；

12. **SemFace: Pre-training Encoder and Decoder with a Semantic Interface for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.348)

    *Shuo Ren, Long Zhou, Shujie Liu, Furu Wei, Ming Zhou, Shuai Ma*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_30232405/article/details/120699960)；

13. **Transfer Learning for Sequence Generation: from Single-source to Multi-source.** [paper](https://aclanthology.org/2021.acl-long.446/)

    *Xuancheng Huang, Jingfang Xu, Maosong Sun, Yang Liu*

    **Venue**: ACL-2021

14. **An Exploratory Analysis of Multilingual Word-Level Quality Estimation with Cross-Lingual Transformers.** [paper](https://aclanthology.org/2021.acl-short.55)

    *Tharindu Ranasinghe, Constantin Orasan, Ruslan Mitkov*

    **Venue**: ACL-2021

15. **nmT5 - Is parallel data still relevant for pre-training massively multilingual language models?.** [paper](https://aclanthology.org/2021.acl-short.87)

    *Mihir Kale, Aditya Siddhant, Rami Al-Rfou, Linting Xue, Noah Constant, Melvin Johnson*

    **Venue**: ACL-2021

### <span id="DiversityandFairness">Diversity and Fairness</span>

1. **Generating Diverse Translations with Sentence Codes.** [paper](https://aclanthology.org/P19-1177)

    *Raphael Shu, Hideki Nakayama, Kyunghyun Cho*

    **Venue**: ACL-2019

2. **“You Sound Just Like Your Father” Commercial Machine Translation Systems Include Stylistic Biases.** [paper](https://aclanthology.org/2020.acl-main.154/)

    *Dirk Hovy, Federico Bianchi, Tommaso Fornaciari*

    **Venue**: ACL-2020

3. **Gender bias amplification during Speed-Quality optimization in Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-short.15)

    *Adithya Renduchintala, Denise Diaz, Kenneth Heafield, Xian Li, Mona Diab*

    **Venue**: ACL-2021

### <span id="Robustness">Robustness</span>

1. **Accelerating Neural Transformer via an Average Attention Network.** [paper](https://aclanthology.org/P18-1166/)

    *Biao Zhang, Deyi Xiong, Jinsong Su*

    **Venue**: ACL-2018

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/75796168) ; [Paper Reading&Interpretation2](https://blog.csdn.net/wwx123521/article/details/83238989?spm=1001.2014.3001.5502)

2. **Towards Robust Neural Machine Translation.** [paper](https://aclanthology.org/P18-1163/)

    *Yong Cheng, Zhaopeng Tu, Fandong Meng, Junjie Zhai, Yang Liu*

    **Venue**: ACL-2018

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/417612841) ; [Paper Reading&Interpretation2](https://blog.csdn.net/void_p/article/details/90676771?spm=1001.2014.3001.5502)

3. **Learning Deep Transformer Models for Machine Translation.** [paper](https://aclanthology.org/P19-1176/)

    *Qiang Wang, Bei Li, Tong Xiao, Jingbo Zhu, Changliang Li, Derek F. Wong, Lidia S. Chao*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/NehJOAC0_nOPWES9KsoE4A)；

4. **Robust Neural Machine Translation with Doubly Adversarial Inputs.** [paper](https://aclanthology.org/P19-1425)

    *Yong Cheng, Lu Jiang, Wolfgang Macherey*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/419459265) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/445671515) ; [Paper Reading&Interpretation3](https://blog.csdn.net/crystal_sugar/article/details/104836197?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation4](https://blog.csdn.net/weixin_43301333/article/details/106087909?spm=1001.2014.3001.5502)

5. **Robust Neural Machine Translation with Joint Textual and Phonetic Embedding.** [paper](https://aclanthology.org/P19-1291/)

    *Hairong Liu, Mingbo Ma, Liang Huang, Hao Xiong, Zhongjun He*

    **Venue**: ACL-2019

6. **Effective Adversarial Regularization for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1020)

    *Motoki Sato, Jun Suzuki, Shun Kiyono*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://blog.csdn.net/DragonBark/article/details/103150354?spm=1001.2014.3001.5502)；

7. **A Reinforced Generation of Adversarial Examples for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.319/)

    *Wei Zou, Shujian Huang, Jun Xie, Xinyu Dai, Jiajun Chen*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_42137700/article/details/107297116?spm=1001.2014.3001.5502)；

8. **On the Inference Calibration of Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.278/)

    *Shuo Wang, Zhaopeng Tu, Shuming Shi, Yang Liu*

    **Venue**: ACL-2020

9. **Understanding the Properties of Minimum Bayes Risk Decoding in Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.22/)

    *Mathias Müller, Rico Sennrich*

    **Venue**: ACL-2021

10. **On Compositional Generalization of Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.368)

    *Yafu Li, Yongjing Yin, Yulong Chen, Yue Zhang*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/421451635) ; [Paper Reading&Interpretation2](https://www.bilibili.com/video/BV16P4y1H7uK?from=search&seid=10274723515390347439&spm_id_from=333.337.0.0)

11. **Beyond Noise: Mitigating the Impact of Fine-grained Semantic Divergences on Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.562)

    *Eleftheria Briakou, Marine Carpuat*

    **Venue**: ACL-2021

12. **An Empirical Study on Adversarial Attack on NMT: Languages and Positions Matter.** [paper](https://aclanthology.org/2021.acl-short.58)

    *Zhiyuan Zeng, Deyi Xiong*

    **Venue**: ACL-2021

### <span id="Data-basedMethods">Data-based Methods</span>

1. **Don’t Rule Out Monolingual Speakers: A Method For Crowdsourcing Machine Translation Data.** [paper](https://aclanthology.org/2021.acl-short.139)

    *Rajat Bhatnagar, Ananya Ganesh, Katharina Kann*

    **Venue**: ACL-2021

#### <span id="WordSegmentation">Word Segmentation</span>

1. **Neural Machine Translation of Rare Words with Subword Units.** [paper](https://aclanthology.org/P16-1162)

    *Rico Sennrich, Barry Haddow, Alexandra Birch*

    **Venue**: ACL-2016

    [Paper Reading&Interpretation1](https://blog.csdn.net/zmx1996/article/details/83153311) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/38574684)

2. **Adversarial Multi-Criteria Learning for Chinese Word Segmentation.** [paper](https://aclanthology.org/P17-1110)

    *Xinchi Chen, Zhan Shi, Xipeng Qiu, Xuanjing Huang*

    **Venue**: ACL-2017

    [Paper Reading&Interpretation1](https://blog.csdn.net/appleml/article/details/78408207)；

3. **Neural Joint Model for Transition-based Chinese Syntactic Analysis.** [paper](https://aclanthology.org/P17-1111)

    *Shuhei Kurita, Daisuke Kawahara, Sadao Kurohashi*

    **Venue**: ACL-2017

4. **The Role of Prosody and Speech Register in Word Segmentation: A Computational Modelling Perspective.** [paper](https://aclanthology.org/P17-2028)

    *Bogdan Ludusan, Reiko Mazuka, Mathieu Bernard, Alejandrina Cristia, Emmanuel Dupoux*

    **Venue**: ACL-2017

5. **Challenging Language-Dependent Segmentation for Arabic: An Application to Machine Translation and Part-of-Speech Tagging.** [paper](https://aclanthology.org/P17-2095/)

    *Hassan Sajjad, Fahim Dalvi, Nadir Durrani, Ahmed Abdelali, Yonatan Belinkov, Stephan Vogel*

    **Venue**: ACL-2017

6. **Subword Regularization: Improving Neural Network Translation Models with Multiple Subword Candidates.** [paper](https://aclanthology.org/P18-1007/)

    *Taku Kudo*

    **Venue**: ACL-2018

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/38546218) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/333333666) ; [Paper Reading&Interpretation3](https://mp.weixin.qq.com/s/5z3CMmIR0U9-p2BwJnsYKg) ; [Paper Reading&Interpretation4](https://blog.csdn.net/u014248127/article/details/99998954?spm=1001.2014.3001.5502)

7. **Dynamic Programming Encoding for Subword Segmentation in Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.275/)

    *Xuanli He, Gholamreza Haffari, Mohammad Norouzi*

    **Venue**: ACL-2020

8. **Modeling Word Formation in English–German Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.389/)

    *Marion Weller-Di Marco, Alexander Fraser*

    **Venue**: ACL-2020

9. **A unified approach to sentence segmentation of punctuated text in many languages.** [paper](https://aclanthology.org/2021.acl-long.309/)

    *Rachel Wicks, Matt Post*

    **Venue**: ACL-2021

10. **Vocabulary Learning via Optimal Transport for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.571)

    *Jingjing Xu, Hao Zhou, Chun Gan, Zaixiang Zheng, Lei Li*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_16949707/article/details/118694959) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/420759521) ; [Paper Reading&Interpretation3](https://zhuanlan.zhihu.com/p/390854862) ; [Paper Reading&Interpretation4](https://zhuanlan.zhihu.com/p/388813045)

11. **When is Char Better Than Subword: A Systematic Study of Segmentation Algorithms for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-short.69)

    *Jiahuan Li, Yutong Shen, Shujian Huang, Xinyu Dai, Jiajun Chen*

    **Venue**: ACL-2021

#### <span id="Character-levelNMT">Character-level NMT</span>

#### <span id="DataAugmentation">Data Augmentation</span>

1. **Improving Neural Machine Translation Models with Monolingual Data.** [paper](https://aclanthology.org/P16-1009/)

    *Rico Sennrich, Barry Haddow, Alexandra Birch*

    **Venue**: ACL-2016

    [Paper Reading&Interpretation1](https://blog.csdn.net/feifei3211/article/details/103344445?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/330866548)

2. **Set-Theoretic Alignment for Comparable Corpora.** [paper](https://aclanthology.org/P16-1189)

    *Thierry Etchegoyhen, Andoni Azpeitia*

    **Venue**: ACL-2016

3. **Jointly Learning to Embed and Predict with Multiple Languages.** [paper](https://aclanthology.org/P16-1190)

    *Daniel C. Ferreira, André F. T. Martins, Mariana S. C. Almeida*

    **Venue**: ACL-2016

4. **Creating Training Corpora for NLG Micro-Planners.** [paper](https://aclanthology.org/P17-1017)

    *Claire Gardent, Anastasia Shimorina, Shashi Narayan, Laura Perez-Beltrachini*

    **Venue**: ACL-2017

5. **Efficient Extraction of Pseudo-Parallel Sentences from Raw Monolingual Data Using Word Embeddings.** [paper](https://aclanthology.org/P17-2062)

    *Benjamin Marie, Atsushi Fujita*

    **Venue**: ACL-2017

6. **Data Augmentation for Low-Resource Neural Machine Translation.** [paper](https://aclanthology.org/P17-2090/)

    *Marzieh Fadaee, Arianna Bisazza, Christof Monz*

    **Venue**: ACL-2017

7. **When a Good Translation is Wrong in Context: Context-Aware Machine Translation Improves on Deixis, Ellipsis, and Lexical Cohesion.** [paper](https://aclanthology.org/P19-1116/)

    *Elena Voita, Rico Sennrich, Ivan Titov*

    **Venue**: ACL-2019

8. **Neural Fuzzy Repair: Integrating Fuzzy Matches into Neural Machine Translation.** [paper](https://aclanthology.org/P19-1175/)

    *Bram Bulte, Arda Tezcan*

    **Venue**: ACL-2019

9. **Generalized Data Augmentation for Low-Resource Translation.** [paper](https://aclanthology.org/P19-1579/)

    *Mengzhou Xia, Xiang Kong, Antonios Anastasopoulos, Graham Neubig*

    **Venue**: ACL-2019

10. **Soft Contextual Data Augmentation for Neural Machine Translation.** [paper](https://aclanthology.org/P19-1555/)

    *Fei Gao, Jinhua Zhu, Lijun Wu, Yingce Xia, Tao Qin, Xueqi Cheng, Wengang Zhou, Tie-Yan Liu*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/70122299)；

11. **A Reinforced Generation of Adversarial Examples for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.319/)

    *Wei Zou, Shujian Huang, Jun Xie, Xinyu Dai, Jiajun Chen*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_42137700/article/details/107297116?spm=1001.2014.3001.5502)；

12. **Boosting Neural Machine Translation with Similar Translations.** [paper](https://aclanthology.org/2020.acl-main.144/)

    *Jitao XU, Josep Crego, Jean Senellart*

    **Venue**: ACL-2020

13. **AdvAug: Robust Adversarial Augmentation for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.529/)

    *Yong Cheng, Lu Jiang, Wolfgang Macherey, Jacob Eisenstein*

    **Venue**: ACL-2020

14. **Improving Non-autoregressive Neural Machine Translation with Monolingual Data.** [paper](https://aclanthology.org/2020.acl-main.171/)

    *Jiawei Zhou, Phillip Keung*

    **Venue**: ACL-2020

15. **Tagged Back-translation Revisited: Why Does It Really Work?.** [paper](https://aclanthology.org/2020.acl-main.532/)

    *Benjamin Marie, Raphael Rubino, Atsushi Fujita*

    **Venue**: ACL-2020

16. **Data Augmentation for Text Generation Without Any Augmented Data.** [paper](https://aclanthology.org/2021.acl-long.173/)

    *Wei Bi, Huayang Li, Jiacheng Huang*

    **Venue**: ACL-2021

17. **Self-Training Sampling with Monolingual Data Uncertainty for Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.221/)

    *Wenxiang Jiao, Xing Wang, Zhaopeng Tu, Shuming Shi, Michael Lyu, Irwin King*

    **Venue**: ACL-2021

18. **Cross-language Sentence Selection via Data Augmentation and Rationale Training.** [paper](https://aclanthology.org/2021.acl-long.300/)

    *Yanda Chen, Chris Kedzie, Suraj Nair, Petra Galuscakova, Rui Zhang, Douglas Oard, Kathleen McKeown*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_41485273/article/details/117711905)；

#### <span id="ScheduleStrategy">Schedule Strategy</span>

##### <span id="DataSelection">Data Selection</span>

1. **Target Conditioned Sampling: Optimizing Data Selection for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/P19-1583/)

    *Xinyi Wang, Graham Neubig*

    **Venue**: ACL-2019

2. **Selecting Backtranslated Data from Multiple Sources for Improved Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.359)

    *Xabier Soto, Dimitar Shterionov, Alberto Poncelas, Andy Way*

    **Venue**: ACL-2020

3. **Balancing Training for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.754/)

    *Xinyi Wang, Yulia Tsvetkov, Graham Neubig*

    **Venue**: ACL-2020

##### <span id="CurriculumLearning">Curriculum Learning</span>

1. **Norm-Based Curriculum Learning for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.41/)

    *Xuebo Liu, Houtim Lai, Derek F. Wong, Lidia S. Chao*

    **Venue**: ACL-2020

2. **Uncertainty-Aware Curriculum Learning for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.620/)

    *Yikai Zhou, Baosong Yang, Derek F. Wong, Yu Wan, Lidia S. Chao*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_41997479/article/details/118891253?spm=1001.2014.3001.5502)；

3. **Learning a Multi-Domain Curriculum for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.689/)

    *Wei Wang, Ye Tian, Jiquan Ngiam, Yinfei Yang, Isaac Caswell, Zarana Parekh*

    **Venue**: ACL-2020

4. **Curriculum Pre-training for End-to-End Speech Translation.** [paper](https://aclanthology.org/2020.acl-main.344/)

    *Chengyi Wang, Yu Wu, Shujie Liu, Ming Zhou, Zhenglu Yang*

    **Venue**: ACL-2020

### <span id="Low-resourceNMT">Low-resource NMT</span>

1. **Revisiting Low-Resource Neural Machine Translation: A Case Study.** [paper](https://aclanthology.org/P19-1021/)

    *Rico Sennrich, Biao Zhang*

    **Venue**: ACL-2019

#### <span id="UnsupervisedNMT">Unsupervised NMT</span>

1. **Unsupervised Neural Machine Translation with Weight Sharing.** [paper](https://aclanthology.org/P18-1005/)

    *Zhen Yang, Wei Chen, Feng Wang, Bo Xu*

    **Venue**: ACL-2018

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38937984/article/details/102159541?spm=1001.2014.3001.5502)；

2. **On the Limitations of Unsupervised Bilingual Dictionary Induction.** [paper](https://aclanthology.org/P18-1072/)

    *Anders Søgaard, Sebastian Ruder, Ivan Vulić*

    **Venue**: ACL-2018

3. **Unsupervised Parallel Sentence Extraction with Parallel Segment Detection Helps Machine Translation.** [paper](https://aclanthology.org/P19-1118)

    *Viktor Hangya, Alexander Fraser*

    **Venue**: ACL-2019

4. **Unsupervised Bilingual Word Embedding Agreement for Unsupervised Neural Machine Translation.** [paper](https://aclanthology.org/P19-1119/)

    *Haipeng Sun, Rui Wang, Kehai Chen, Masao Utiyama, Eiichiro Sumita, Tiejun Zhao*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38937984/article/details/102388490?spm=1001.2014.3001.5502)；

5. **Improved Zero-shot Neural Machine Translation via Ignoring Spurious Correlations.** [paper](https://aclanthology.org/P19-1121/)

    *Jiatao Gu, Yong Wang, Kyunghyun Cho, Victor O.K. Li*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38937984/article/details/102406585?spm=1001.2014.3001.5502)；

6. **Generalized Data Augmentation for Low-Resource Translation.** [paper](https://aclanthology.org/P19-1579/)

    *Mengzhou Xia, Xiang Kong, Antonios Anastasopoulos, Graham Neubig*

    **Venue**: ACL-2019

7. **Unsupervised Pivot Translation for Distant Languages.** [paper](https://aclanthology.org/P19-1017/)

    *Yichong Leng, Xu Tan, Tao Qin, Xiang-Yang Li, Tie-Yan Liu*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38937984/article/details/102316524?spm=1001.2014.3001.5502)；

8. **An Effective Approach to Unsupervised Machine Translation.** [paper](https://aclanthology.org/P19-1019/)

    *Mikel Artetxe, Gorka Labaka, Eneko Agirre*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://blog.csdn.net/alzy133/article/details/105419257?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://blog.csdn.net/weixin_38937984/article/details/102297382?spm=1001.2014.3001.5502)

9. **Self-Supervised Neural Machine Translation.** [paper](https://aclanthology.org/P19-1178/)

    *Dana Ruiter, Cristina España-Bonet, Josef van Genabith*

    **Venue**: ACL-2019

10. **Translating Translationese: A Two-Step Approach to Unsupervised Machine Translation.** [paper](https://aclanthology.org/P19-1293/)

    *Nima Pourdamghani, Nada Aldarrab, Marjan Ghazvininejad, Kevin Knight, Jonathan May*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38937984/article/details/102060942?spm=1001.2014.3001.5502)；

11. **Bilingual Lexicon Induction through Unsupervised Machine Translation.** [paper](https://aclanthology.org/P19-1494)

    *Mikel Artetxe, Gorka Labaka, Eneko Agirre*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_38937984/article/details/102220543?spm=1001.2014.3001.5502)；

12. **Knowledge Distillation for Multilingual Unsupervised Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.324/)

    *Haipeng Sun, Rui Wang, Kehai Chen, Masao Utiyama, Eiichiro Sumita, Tiejun Zhao*

    **Venue**: ACL-2020

13. **Bilingual Dictionary Based Neural Machine Translation without Using Parallel Sentences.** [paper](https://aclanthology.org/2020.acl-main.143/)

    *Xiangyu Duan, Baijun Ji, Hao Jia, Min Tan, Min Zhang, Boxing Chen, Weihua Luo, Yue Zhang*

    **Venue**: ACL-2020

14. **A Retrieve-and-Rewrite Initialization Method for Unsupervised Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.320/)

    *Shuo Ren, Yu Wu, Shujie Liu, Ming Zhou, Shuai Ma*

    **Venue**: ACL-2020

15. **Leveraging Monolingual Data with Self-Supervision for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.252/)

    *Aditya Siddhant, Ankur Bapna, Yuan Cao, Orhan Firat, Mia Chen, Sneha Kudugunta, Naveen Arivazhagan, Yonghui Wu*

    **Venue**: ACL-2020

16. **Unsupervised Neural Machine Translation for Low-Resource Domains via Meta-Learning.** [paper](https://aclanthology.org/2021.acl-long.225/)

    *Cheonbok Park, Yunwon Tae, TaeHee Kim, Soyoung Yang, Mohammad Azam Khan, Lucy Park, Jaegul Choo*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://blog.csdn.net/qq_30232405/article/details/120903124)；

#### <span id="Semi-supervisedNMT">Semi-supervised NMT</span>

1. **Semi-Supervised Learning for Neural Machine Translation.** [paper](https://aclanthology.org/P16-1185)

    *Yong Cheng, Wei Xu, Zhongjun He, Wei He, Hua Wu, Maosong Sun, Yang Liu*

    **Venue**: ACL-2016

2. **Multi-space Variational Encoder-Decoders for Semi-supervised Labeled Sequence Transduction.** [paper](https://aclanthology.org/P17-1029)

    *Chunting Zhou, Graham Neubig*

    **Venue**: ACL-2017

#### <span id="EndangeredLanguageStudy">Endangered Language Study</span>

1. **Universal Dependencies Parsing for Colloquial Singaporean English.** [paper](https://aclanthology.org/P17-1159)

    *Hongmin Wang, Yue Zhang, GuangYong Leonard Chan, Jie Yang, Hai Leong Chieu*

    **Venue**: ACL-2017

2. **A Teacher-Student Framework for Zero-Resource Neural Machine Translation.** [paper](https://aclanthology.org/P17-1176)

    *Yun Chen, Yang Liu, Yong Cheng, Victor O.K. Li*

    **Venue**: ACL-2017

3. **Triangular Architecture for Rare Language Translation.** [paper](https://aclanthology.org/P18-1006/)

    *Shuo Ren, Wenhu Chen, Shujie Liu, Mu Li, Ming Zhou, Shuai Ma*

    **Venue**: ACL-2018

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/_SfY-JZsUEKReSoI6qHg9w)；

4. **Adapting High-resource NMT Models to Translate Low-resource Related Languages without Parallel Data.** [paper](https://aclanthology.org/2021.acl-long.66/)

    *Wei-Jen Ko, Ahmed El-Kishky, Adithya Renduchintala, Vishrav Chaudhary, Naman Goyal, Francisco Guzmán, Pascale Fung, Philipp Koehn, Mona Diab*

    **Venue**: ACL-2021

5. **From Machine Translation to Code-Switching: Generating High-Quality Code-Switched Text.** [paper](https://aclanthology.org/2021.acl-long.245/)

    *Ishan Tarunesh, Syamantak Kumar, Preethi Jyothi*

    **Venue**: ACL-2021

6. **Machine Translation into Low-resource Language Varieties.** [paper](https://aclanthology.org/2021.acl-short.16)

    *Sachin Kumar, Antonios Anastasopoulos, Shuly Wintner, Yulia Tsvetkov*

    **Venue**: ACL-2021

7. **Anchor-based Bilingual Word Embeddings for Low-Resource Languages.** [paper](https://aclanthology.org/2021.acl-short.30)

    *Tobias Eder, Viktor Hangya, Alexander Fraser*

    **Venue**: ACL-2021

### <span id="MultilingualNMT">Multilingual NMT</span>

1. **Neural Architectures for Multilingual Semantic Parsing.** [paper](https://aclanthology.org/P17-2007)

    *Raymond Hendy Susanto, Wei Lu*

    **Venue**: ACL-2017

2. **Incorporating Dialectal Variability for Socially Equitable Language Identification.** [paper](https://aclanthology.org/P17-2009)

    *David Jurgens, Yulia Tsvetkov, Dan Jurafsky*

    **Venue**: ACL-2017

3. **A Compact and Language-Sensitive Multilingual Translation Method.** [paper](https://aclanthology.org/P19-1117/)

    *Yining Wang, Long Zhou, Jiajun Zhang, Feifei Zhai, Jingfang Xu, Chengqing Zong*

    **Venue**: ACL-2019

4. **Target Conditioned Sampling: Optimizing Data Selection for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/P19-1583/)

    *Xinyi Wang, Graham Neubig*

    **Venue**: ACL-2019

5. **Balancing Training for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.754/)

    *Xinyi Wang, Yulia Tsvetkov, Graham Neubig*

    **Venue**: ACL-2020

6. **Improving Massively Multilingual Neural Machine Translation and Zero-Shot Translation.** [paper](https://aclanthology.org/2020.acl-main.148/)

    *Biao Zhang, Philip Williams, Ivan Titov, Rico Sennrich*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://blog.csdn.net/jokerxsy/article/details/121392856?spm=1001.2014.3001.5502)；

7. **Knowledge Distillation for Multilingual Unsupervised Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.324/)

    *Haipeng Sun, Rui Wang, Kehai Chen, Masao Utiyama, Eiichiro Sumita, Tiejun Zhao*

    **Venue**: ACL-2020

8. **Language-aware Interlingua for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.150/)

    *Changfeng Zhu, Heng Yu, Shanbo Cheng, Weihua Luo*

    **Venue**: ACL-2020

9. **Leveraging Monolingual Data with Self-Supervision for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.252/)

    *Aditya Siddhant, Ankur Bapna, Yuan Cao, Orhan Firat, Mia Chen, Sneha Kudugunta, Naveen Arivazhagan, Yonghui Wu*

    **Venue**: ACL-2020

10. **Contrastive Learning for Many-to-many Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.21/)

    *Xiao Pan, Mingxuan Wang, Liwei Wu, Lei Li*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://bbs.gpushare.com/topic/761/%E6%9C%BA%E5%99%A8%E7%BF%BB%E8%AF%91-21-7-mrasp2?_=1640584574620)；

11. **Learning Language Specific Sub-network for Multilingual Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.25/)

    *Zehui Lin, Liwei Wu, Mingxuan Wang, Lei Li*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://blog.csdn.net/jokerxsy/article/details/121279106)；

12. **Multilingual Speech Translation from Efficient Finetuning of Pretrained Models.** [paper](https://aclanthology.org/2021.acl-long.68/)

    *Xian Li, Changhan Wang, Yun Tang, Chau Tran, Yuqing Tang, Juan Pino, Alexei Baevski, Alexis Conneau, Michael Auli*

    **Venue**: ACL-2021

13. **Improving Zero-Shot Translation by Disentangling Positional Information.** [paper](https://aclanthology.org/2021.acl-long.101/)

    *Danni Liu, Jan Niehues, James Cross, Francisco Guzmán, Xian Li*

    **Venue**: ACL-2021

14. **Consistency Regularization for Cross-Lingual Fine-Tuning.** [paper](https://aclanthology.org/2021.acl-long.264/)

    *Bo Zheng, Li Dong, Shaohan Huang, Wenhui Wang, Zewen Chi, Saksham Singhal, Wanxiang Che, Ting Liu, Xia Song, Furu Wei*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/XAuPGfscU4szlX3Hb1sneA) ; [Paper Reading&Interpretation2](https://zhuanlan.zhihu.com/p/384664475)

15. **Importance-based Neuron Allocation for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.445/)

    *Wanying Xie, Yang Feng, Shuhao Gu, Dong Yu*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://blog.csdn.net/jokerxsy/article/details/121816932)；

16. **Multilingual Agreement for Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-short.31)

    *Jian Yang, Yuwei Yin, Shuming Ma, Haoyang Huang, Dongdong Zhang, Zhoujun Li, Furu Wei*

    **Venue**: ACL-2021

17. **Modeling Task-Aware MIMO Cardinality for Efficient Multilingual Neural Machine Translation.** [paper](https://aclanthology.org/2021.acl-short.46)

    *Hongfei Xu, Qiuhui Liu, Josef van Genabith, Deyi Xiong*

    **Venue**: ACL-2021

18. **nmT5 - Is parallel data still relevant for pre-training massively multilingual language models?.** [paper](https://aclanthology.org/2021.acl-short.87)

    *Mihir Kale, Aditya Siddhant, Rami Al-Rfou, Linting Xue, Noah Constant, Melvin Johnson*

    **Venue**: ACL-2021

19. **Lightweight Adapter Tuning for Multilingual Speech Translation.** [paper](https://aclanthology.org/2021.acl-short.103)

    *Hang Le, Juan Pino, Changhan Wang, Jiatao Gu, Didier Schwab, Laurent Besacier*

    **Venue**: ACL-2021

### <span id="Document-levelNMT">Document-level NMT</span>

1. **Document Translation vs. Query Translation for Cross-Lingual Information Retrieval in the Medical Domain.** [paper](https://aclanthology.org/2020.acl-main.613/)

    *Shadi Saleh, Pavel Pecina*

    **Venue**: ACL-2020

2. **Using Context in Neural Machine Translation Training Objectives.** [paper](https://aclanthology.org/2020.acl-main.693)

    *Danielle Saunders, Felix Stahlberg, Bill Byrne*

    **Venue**: ACL-2020

3. **A Simple and Effective Unified Encoder for Document-Level Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.321/)

    *Shuming Ma, Dongdong Zhang, Ming Zhou*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://zhuanlan.zhihu.com/p/358639090)；

4. **Contextual Neural Machine Translation Improves Translation of Cataphoric Pronouns.** [paper](https://aclanthology.org/2020.acl-main.530/)

    *KayYen Wong, Sameen Maruf, Gholamreza Haffari*

    **Venue**: ACL-2020

5. **Does Multi-Encoder Help? A Case Study on Context-Aware Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.322)

    *Bei Li, Hui Liu, Ziyang Wang, Yufan Jiang, Tong Xiao, Jingbo Zhu, Tongran Liu, Changliang Li*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://blog.csdn.net/xiao_xian_/article/details/108441933?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://blog.csdn.net/c9Yv2cf9I06K2A9E/article/details/106964479?spm=1001.2014.3001.5502)

6. **G-Transformer for Document-Level Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.267/)

    *Guangsheng Bao, Yue Zhang, Zhiyang Teng, Boxing Chen, Weihua Luo*

    **Venue**: ACL-2021

    [Paper Reading&Interpretation1](https://nopsled.blog.csdn.net/article/details/121034422?spm=1001.2014.3001.5502)；

7. **Modeling Bilingual Conversational Characteristics for Neural Chat Translation.** [paper](https://aclanthology.org/2021.acl-long.444/)

    *Yunlong Liang, Fandong Meng, Yufeng Chen, Jinan Xu, Jie Zhou*

    **Venue**: ACL-2021

8. **Measuring and Increasing Context Usage in Context-Aware Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.505/)

    *Patrick Fernandes, Kayo Yin, Graham Neubig, André F. T. Martins*

    **Venue**: ACL-2021

### <span id="Real-timeNMT">Real-time NMT</span>

1. **Monotonic Infinite Lookback Attention for Simultaneous Machine Translation.** [paper](https://aclanthology.org/P19-1126)

    *Naveen Arivazhagan, Colin Cherry, Wolfgang Macherey, Chung-Cheng Chiu, Semih Yavuz, Ruoming Pang, Wei Li, Colin Raffel*

    **Venue**: ACL-2019

2. **Simultaneous Translation with Flexible Policy via Restricted Imitation Learning.** [paper](https://aclanthology.org/P19-1582/)

    *Baigong Zheng, Renjie Zheng, Mingbo Ma, Liang Huang*

    **Venue**: ACL-2019

    [Paper Reading&Interpretation1](https://mp.weixin.qq.com/s/i70lV_-znoyDhEaU_3yBsw)；

3. **Opportunistic Decoding with Timely Correction for Simultaneous Translation.** [paper](https://aclanthology.org/2020.acl-main.42/)

    *Renjie Zheng, Mingbo Ma, Baigong Zheng, Kaibo Liu, Liang Huang*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_47196664/article/details/106542477?spm=1001.2014.3001.5502)；

4. **Simultaneous Translation Policies: From Fixed to Adaptive.** [paper](https://aclanthology.org/2020.acl-main.254/)

    *Baigong Zheng, Kaibo Liu, Renjie Zheng, Mingbo Ma, Hairong Liu, Liang Huang*

    **Venue**: ACL-2020

### <span id="MultimodalNMT">Multimodal NMT</span>

#### <span id="Speech">Speech</span>

##### <span id="CascadedSpeechTranslation">Cascaded Speech Translation</span>

1. **Lattice Transformer for Speech Translation.** [paper](https://aclanthology.org/P19-1649/)

    *Pei Zhang, Niyu Ge, Boxing Chen, Kai Fan*

    **Venue**: ACL-2019

2. **Multilingual Speech Translation from Efficient Finetuning of Pretrained Models.** [paper](https://aclanthology.org/2021.acl-long.68/)

    *Xian Li, Changhan Wang, Yun Tang, Chau Tran, Yuqing Tang, Juan Pino, Alexei Baevski, Alexis Conneau, Michael Auli*

    **Venue**: ACL-2021

3. **Cascade versus Direct Speech Translation: Do the Differences Still Make a Difference?.** [paper](https://aclanthology.org/2021.acl-long.224/)

    *Luisa Bentivogli, Mauro Cettolo, Marco Gaido, Alina Karakanta, Alberto Martinelli, Matteo Negri, Marco Turchi*

    **Venue**: ACL-2021

4. **Improving Speech Translation by Understanding and Learning from the Auxiliary Text Translation Task.** [paper](https://aclanthology.org/2021.acl-long.328)

    *Yun Tang, Juan Pino, Xian Li, Changhan Wang, Dmitriy Genzel*

    **Venue**: ACL-2021

##### <span id="End-to-EndSpeechTranslation">End-to-End Speech Translation</span>

1. **Joint CTC/attention decoding for end-to-end speech recognition.** [paper](https://aclanthology.org/P17-1048)

    *Takaaki Hori, Shinji Watanabe, John Hershey*

    **Venue**: ACL-2017

    [Paper Reading&Interpretation1](https://blog.csdn.net/pitaojun/article/details/111493883?spm=1001.2014.3001.5502)；

2. **Exploring Phoneme-Level Speech Representations for End-to-End Speech Translation.** [paper](https://aclanthology.org/P19-1179/)

    *Elizabeth Salesky, Matthias Sperber, Alan W Black*

    **Venue**: ACL-2019

3. **Curriculum Pre-training for End-to-End Speech Translation.** [paper](https://aclanthology.org/2020.acl-main.344/)

    *Chengyi Wang, Yu Wu, Shujie Liu, Ming Zhou, Zhenglu Yang*

    **Venue**: ACL-2020

4. **Beyond Sentence-Level End-to-End Speech Translation: Context Helps.** [paper](https://aclanthology.org/2021.acl-long.200/)

    *Biao Zhang, Ivan Titov, Barry Haddow, Rico Sennrich*

    **Venue**: ACL-2021

5. **Lightweight Adapter Tuning for Multilingual Speech Translation.** [paper](https://aclanthology.org/2021.acl-short.103)

    *Hang Le, Juan Pino, Changhan Wang, Jiatao Gu, Didier Schwab, Laurent Besacier*

    **Venue**: ACL-2021

#### <span id="Image">Image</span>

1. **Doubly-Attentive Decoder for Multi-modal Neural Machine Translation.** [paper](https://aclanthology.org/P17-1175)

    *Iacer Calixto, Qun Liu, Nick Campbell*

    **Venue**: ACL-2017

2. **Latent Variable Model for Multi-modal Translation.** [paper](https://aclanthology.org/P19-1642/)

    *Iacer Calixto, Miguel Rios, Wilker Aziz*

    **Venue**: ACL-2019

3. **Distilling Translations with Visual Awareness.** [paper](https://aclanthology.org/P19-1653/)

    *Julia Ive, Pranava Madhyastha, Lucia Specia*

    **Venue**: ACL-2019

4. **A Novel Graph-based Multi-modal Fusion Encoder for Neural Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.273/)

    *Yongjing Yin, Fandong Meng, Jinsong Su, Chulun Zhou, Zhengyuan Yang, Jie Zhou, Jiebo Luo*

    **Venue**: ACL-2020

    [Paper Reading&Interpretation1](https://blog.csdn.net/weixin_40459958/article/details/120625411?spm=1001.2014.3001.5502) ; [Paper Reading&Interpretation2](https://blog.csdn.net/qq874455953/article/details/114949138?spm=1001.2014.3001.5502)

5. **Unsupervised Multimodal Neural Machine Translation with Pseudo Visual Pivoting.** [paper](https://aclanthology.org/2020.acl-main.731/)

    *Po-Yao Huang, Junjie Hu, Xiaojun Chang, Alexander Hauptmann*

    **Venue**: ACL-2020

6. **Multimodal Transformer for Multimodal Machine Translation.** [paper](https://aclanthology.org/2020.acl-main.400/)

    *Shaowei Yao, Xiaojun Wan*

    **Venue**: ACL-2020

7. **Good for Misconceived Reasons: An Empirical Revisiting on the Need for Visual Context in Multimodal Machine Translation.** [paper](https://aclanthology.org/2021.acl-long.480/)

    *Zhiyong Wu, Lingpeng Kong, Wei Bi, Xiang Li, Ben Kao*

    **Venue**: ACL-2021

### <span id="WMT">WMT</span>

#### <span id="Efficiency">Efficiency</span>

#### <span id="Quality Estimation">Quality Estimation</span>

1. **An Exploratory Analysis of Multilingual Word-Level Quality Estimation with Cross-Lingual Transformers.** [paper](https://aclanthology.org/2021.acl-short.55)

    *Tharindu Ranasinghe, Constantin Orasan, Ruslan Mitkov*

    **Venue**: ACL-2021

#### <span id="NewsTranslation">News Translation</span>

### <span id="Survey">Survey</span>

1. **Scientific Credibility of Machine Translation Research: A Meta-Evaluation of 769 Papers.** [paper](https://aclanthology.org/2021.acl-long.566)

    *Benjamin Marie, Atsushi Fujita, Raphael Rubino*

    **Venue**: ACL-2021

