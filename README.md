# Awesome Long-tailed Recognition [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

![](https://img.shields.io/badge/Number-60-green)

A curated list of long-tailed recognition and related resources.

Please feel free to pull requests or open an issue to add papers.


### :high_brightness: Updated 2021-10-03

---

## Table of Contents

- [Type of Long-tailed Recognition](#type-of-long-tailed-recognition)

- [Long-tailed Recognition](#Long-tailed-Recognition)
  - [2021 Venues](#2021)
  - [2020 Venues](#2020)
  - [2019 Venues](#2019)
  - [2018 Venues](#2018)
  - [2017 Venues](#2017)
  - [2016 Venues](#2016)
  - [Previous Venues](#2010-2014)
  - [arXiv](#arxiv)
 
- [Awesome Surveys](#awesome-surveys)

- [Awesome Blogs](#awesome-blogs)

- [Imbalanced Learning](#imbalanced-learning)


### Type of Long-tailed Recognition

| Type        | `OS`          | `US`           | `CBS`                   | `CLW`                 | `SLW`                  | `TL`              | `Other`     |
|:----------- |:-------------:|:--------------:|:----------------------: |:---------------------:|:----------------------:|:-----------------:|:-----------:|
| Explanation | Over Sampling | Under Sampling | Class-balanced Sampling | Class-level Weighting | Sample-level Weighting | Transfer Learning | other types |



### 2021

| Title    | Venue    | Type     | Code     | Star     |
|:-------- |:--------:|:--------:|:--------:|:--------:|
[Label-Imbalanced and Group-Sensitive Classification under Overparameterization](https://arxiv.org/pdf/2103.01550.pdf) | NeurIPS | `CLW`     | -   |
[Long-tail Learning via Logit Adjustment](https://arxiv.org/pdf/2007.07314.pdf) | ICLR | `CLW`     | -   |
[LONG-TAILED RECOGNITION BY ROUTING DIVERSE DISTRIBUTION-AWARE EXPERTS](https://arxiv.org/pdf/2010.01809.pdf) | ICLR | `Other`     | -   |
[Bag of Tricks for Long-Tailed Visual Recognition with Deep Convolutional Neural Networks](https://cs.nju.edu.cn/wujx/paper/AAAI2021_Tricks.pdf) | AAAI | `Other`     | -   |
[PML: Progressive Margin Loss for Long-tailed Age Classification](https://arxiv.org/pdf/2103.02140.pdf) | CVPR | `CLW`     | -   |
[Distribution Alignment: A Unified Framework for Long-tail Visual Recognition](https://arxiv.org/pdf/2103.16370.pdf) | CVPR | `Other`     | -   |
[Contrastive Learning based Hybrid Networks for Long-Tailed Image Classification](https://arxiv.org/pdf/2103.14267) | CVPR | `Other`     | -   |
[Improving Calibration for Long-Tailed Recognition](https://arxiv.org/pdf/2104.00466.pdf) | CVPR | `Other`     | -   |








### 2020

| Title    | Venue    | Type     | Code     | Star     |
|:-------- |:--------:|:--------:|:--------:|:--------:|
| [Rethinking the Value of Labels for Improving Class-Imbalanced Learning](https://arxiv.org/pdf/2006.07529.pdf) | NeurIPS | `Other` | [PyTorch(Author)](https://github.com/YyzHarry/imbalanced-semi-self)   |  `153`  |
| [Balanced Meta-Softmax for Long-Tailed Visual Recognition](https://arxiv.org/pdf/2007.10740.pdf) | NeurIPS | `CLW`     | [PyTorch(Author)](https://github.com/jiawei-ren/BalancedMetaSoftmax)   |
| [Long-Tailed Classification by Keeping the Good and Removing the Bad Momentum Causal Effect](https://arxiv.org/pdf/2009.12991.pdf) | NeurIPS | `Other`     | [PyTorch(Author)](https://github.com/KaihuaTang/Long-Tailed-Recognition.pytorch)   |
| [Forest R-CNN: Large-Vocabulary Long-Tailed Object Detection and Instance Segmentation](https://arxiv.org/pdf/2008.05676.pdf) | ACM-MM | `Other`     | [PyTorch(Author)](https://github.com/JialianW/Forest_RCNN)   |
| [Mitigating Dataset Imbalance via Joint Generation and Classification](https://arxiv.org/pdf/2008.05524.pdf) | ECCV-W | `Other`     | [PyTorch(Author)](https://github.com/AadSah/ImbalanceCycleGAN)   |
| [Seesaw Loss for Long-Tailed Instance](https://arxiv.org/pdf/2008.10032.pdf) | ECCV-W | `Other`     | -   |
| [Balanced Activation for Long-tailed Visual Recognition](https://arxiv.org/pdf/2008.11037.pdf) | ECCV-W | `Other`     | -   |
| [Imbalanced Continual Learning with Partitioning Reservoir Sampling](https://arxiv.org/pdf/2009.03632.pdf) | ECCV | `Other`     | [PyTorch(Author)](https://github.com/cdjkim/PRS)   |
| [Feature Space Augmentation for Long-Tailed Data](https://arxiv.org/pdf/2008.03673.pdf) | ECCV | `Aug`     | -   |
| [The Devil is in Classification A Simple Framework for Long-tail Instance Segmentation](https://arxiv.org/pdf/2007.11978.pdf) | ECCV | `Aug`     | -   |
| [Distribution-Balanced Loss for Multi-Label Classification in Long-Tailed Datasets](https://arxiv.org/pdf/2007.09654.pdf) | ECCV | `CLW`     | [PyTorch(Author)](https://github.com/wutong16/DistributionBalancedLoss)   | `91`  |
| [Solving Long-tailed Recognition with Deep Realistic Taxonomic Classifier](https://arxiv.org/pdf/2007.09898.pdf) | ECCV | `Other`     | -   |
| [Learning From Multiple Experts_Self-paced Knowledge Distillation for Long-tailed Classification](https://arxiv.org/pdf/2001.01536.pdf) | ECCV | `TL`     | -   |
| [Rethinking Class-Balanced Methods for Long-Tailed Visual Recognition from a Domain Adaptation Perspective](https://arxiv.org/pdf/2003.10780.pdf) | CVPR | `CLW`     | -   |
| [Equalization Loss for Long-Tailed Object Recognition](https://arxiv.org/pdf/2003.05176.pdf) | CVPR | `CLW` `SLW`     | [PyTorch(Author)](https://github.com/tztztztztz/eql.detectron2)   | `116`  |
| [Domain Balancing: Face Recognition on Long-Tailed Domains](https://arxiv.org/pdf/2003.13791.pdf) | CVPR | `Other`     | -   |
| [BBN: Bilateral-Branch Network with Cumulative Learning for Long-Tailed Visual Recognition](https://arxiv.org/pdf/1912.02413.pdf) | CVPR | `Other`     | [PyTorch(Author)](https://github.com/Megvii-Nanjing/BBN)  | `360`  |
| [Deep Representation Learning on Long-tailed Data: A Learnable Embedding](https://arxiv.org/pdf/2002.10826.pdf) | CVPR | `TL`     | -   |
| [Inflated Episodic Memory with Region Self-Attention for Long-Tailed Visual Recognition](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhu_Inflated_Episodic_Memory_With_Region_Self-Attention_for_Long-Tailed_Visual_Recognition_CVPR_2020_paper.pdf) | CVPR | `Other`     | -   |
| [Overcoming Classiﬁer Imbalance for Long-tail Object Detection with Balanced Group Softmax](https://arxiv.org/pdf/2006.10408.pdf) | CVPR | `Other`     | [PyTorch(Author)](https://github.com/FishYuLi/BalancedGroupSoftmax)   |
| [M2m: Imbalanced Classification via Major-to-minor Translation](https://arxiv.org/pdf/2004.00431.pdf) | CVPR | `TL`     | [PyTorch(Author)](https://github.com/alinlab/M2m)   |
| [Deep Generative Model for Robust Imbalance Classification](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Deep_Generative_Model_for_Robust_Imbalance_Classification_CVPR_2020_paper.pdf) | CVPR | `Other`     | [TensorFlow(Author)](https://github.com/lvyilin/DGC)   |
| [Learning to Segment the Tail](https://arxiv.org/pdf/2004.00900.pdf) | CVPR | `Other`     | -   |
| [Decoupling Representation and Classifier for Long-Tailed Recognition](https://arxiv.org/pdf/1910.09217.pdf) | ICLR | `Other`  | [PyTorch(Author)](https://github.com/facebookresearch/classifier-balancing)  | `354`  |



### 2019

| Title    | Venue    | Type     | Code     | Star     |
|:-------- |:--------:|:--------:|:--------:|:--------:|
| [The Devil is in Classification: A Simple Framework for Long-tail Instance Segmentation](https://arxiv.org/pdf/2007.11978.pdf) | ECCV | `Other`    | -   |
| [Class-Balanced Loss Based on Effective Number of Samples](https://arxiv.org/pdf/1901.05555.pdf) | CVPR | `CLR`     | [TensorFlow(Author)](https://github.com/richardaecn/class-balanced-loss) [PyTorch(3rd)](https://github.com/vandit15/Class-balanced-loss-pytorch)  | `390/409`  |
| [Striking the Right Balance with Uncertainty](https://arxiv.org/pdf/1901.07590.pdf) | CVPR | `CLW` `SLW`     | -   |
| [Feature Transfer Learning for Face Recognition with Under-Represented Data](https://arxiv.org/pdf/1803.09014.pdf) | CVPR | `TL`     | [PyTorch(3rd)](https://github.com/PLLin/FTL_net)   |
| [Large-Scale Long-Tailed Recognition in an Open World](https://arxiv.org/pdf/1904.05160.pdf) | CVPR | `TL`     | [PyTorch(Author)](https://github.com/zhmiao/OpenLongTailRecognition-OLTR)   | `523`  |
| [Unequal-training for Deep Face Recognition with Long-tailed Noisy Data](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhong_Unequal-Training_for_Deep_Face_Recognition_With_Long-Tailed_Noisy_Data_CVPR_2019_paper.pdf) | CVPR | `TL`     | [MxNet(Author)](https://github.com/zhongyy/Unequal-Training-for-Deep-Face-Recognition-with-Long-Tailed-Noisy-Data)   |
| [Learning for Tail Label Data: A Label-Specific Feature Approach](https://www.ijcai.org/Proceedings/2019/0533.pdf) | IJCAI | `Other`     | -   |
| [Dynamic Curriculum Learning for Imbalanced Data Classification](https://arxiv.org/pdf/1901.06783.pdf) | ICCV | `S` `W`     | -   |
| [Learning Imbalanced Datasets with Label-Distribution-Aware Margin Loss](https://arxiv.org/pdf/1906.07413.pdf) | NeurIPS | `CLW`     | [PyTorch(Author)](https://github.com/kaidic/LDAM-DRW)   | `233`  |
| [Meta-Weight-Net_Learning an Explicit Mapping for Sample Weighting](https://arxiv.org/pdf/1902.07379.pdf) | NeurIPS | `SLW`     | [PyTorch(Author)](https://github.com/xjtushujun/meta-weight-net) [PyTorch(3rd)](https://github.com/robertcedergren/Meta-Weight-Net-Learning-an-Explicit-Mapping-For-Sample-Weighting)  | `133/1`  |



### 2018

| Title    | Venue    | Type     | Code     | Star     |
|:-------- |:--------:|:--------:|:--------:|:--------:|
| [Large Scale Fine-Grained Categorization and Domain-Specific Transfer](https://arxiv.org/pdf/1806.06193.pdf) | CVPR | `TL`     | [TensorFlow(Author)](https://github.com/richardaecn/cvpr18-inaturalist-transfer)   | `146`  |
| [Learning to Reweight Examples for Robust Deep Learning](https://arxiv.org/pdf/1803.09050.pdf) | ICML | `CLW`     | [TensorFlow(Author)](https://github.com/uber-research/learning-to-reweight-examples) [PyTorch(3rd)](https://github.com/danieltan07/learning-to-reweight-examples)  | `188/222`  |
| [Clustering and Learning from Imbalanced Data](https://arxiv.org/pdf/1811.00972.pdf) | NeurIPS-W | `OS`     | -   |



### 2017

| Title    | Venue    | Type     | Code     | Star     |
|:-------- |:--------:|:--------:|:--------:|:--------:|
| [Class Rectification Hard Mining for Imbalanced Deep Learning](https://arxiv.org/pdf/1712.03162.pdf) | ICCV | `CLW`     | -   |
| [Focal Loss for Dense Object Detection](https://arxiv.org/pdf/1708.02002.pdf) | ICCV | `SLW`     | [PyTorch(Author)](https://github.com/facebookresearch/detectron2)   |
| [Range Loss for Deep Face Recognition with Long-Tailed Training Data](https://arxiv.org/pdf/1611.08976.pdf) | ICCV | `SLW`     | [PyTorch(3rd)](https://github.com/shaoniangu/RangeLoss-Pytorch-ReID)   |
| [Learning to Model the Tail](https://papers.nips.cc/paper/7278-learning-to-model-the-tail.pdf) | NeurIPS | `TL`     | -   |


### 2016

| Title    | Venue    | Type     | Code     | Star     |
|:-------- |:--------:|:--------:|:--------:|:--------:|
| [Factors in Finetuning Deep Model for Object Detection with Long-tail Distribution](https://arxiv.org/pdf/1601.05150.pdf) | CVPR | `Other`     | -   |
| [Learning Deep Representation for Imbalanced Classification](https://openaccess.thecvf.com/content_cvpr_2016/papers/Huang_Learning_Deep_Representation_CVPR_2016_paper.pdf) | CVPR | `CBS`     | -   |
| [Learning to Learn: Model Regression Networks for Easy Small Sample Learning](https://www.ri.cmu.edu/pub_files/2016/10/yuxiongw_eccv16_learntolearn.pdf) | ECCV | `TL`     | -   |



### Previous Venues

| Title    | Venue    | Type     | Code     | Star     |
|:-------- |:--------:|:--------:|:--------:|:--------:|
| [Inverse Random under Sampling for Class Imbalance Problem and its Application to Multi-label Classification](https://www.sciencedirect.com/science/article/abs/pii/S0031320312001471?via%3Dihub) | PR | `US`     | -   |
| [Classification of Imbalanced Data by Combining the Complementary Neural Network and SMOTE Algorithm](https://www.researchgate.net/publication/221140314_Classification_of_Imbalanced_Data_by_Combining_the_Complementary_Neural_Network_and_SMOTE_Algorithm) | ICONIP | `US`     | [PyTorch(Author)]()   |
| [Borderline-SMOTE: A New Over-Sampling Method in Imblanced Data Sets Learning](https://sci2s.ugr.es/keel/keel-dataset/pdfs/2005-Han-LNCS.pdf) | ICIC | `OS`     | -   |
| [SMOTE: Synthetic Minority Over-sampling Technique](https://arxiv.org/pdf/1106.1813.pdf) | JAIR | `OS`     | -   |



### arXiv

| Title    | Date     | Type     | Code     | Star     |
|:-------- |:--------:|:--------:|:--------:|:--------:|
| [Convolution and Convolution-root Properties of Long-tailed Distributions](https://arxiv.org/pdf/1501.07458.pdf) | 2015.01.29 | `Other`     | -   |   |
| [Deep Active Learning over the Long Tail](https://arxiv.org/pdf/1711.00941.pdf) | 2017.11.02 | ``     | -   |   |
| [Adjusting Decision Boundary for Class Imbalanced Learning](https://arxiv.org/pdf/1912.01857.pdf) | 2019.12.04 | ``     | [Pytorch(Author)](https://github.com/feidfoe/AdjustBnd4Imbalance)
| [Long-tail Visual Relationship Recognition with a Visiolinguistic Hubless Loss](https://arxiv.org/pdf/2004.00436.pdf) | 2020.03.25 | ``     | -   |   |
| [Long-tail Learning with Class Descriptors](https://arxiv.org/pdf/2004.02235.pdf) | 2020.04.05 | ``     | [TensorFlow(Author)](https://github.com/dvirsamuel/DRAGON)
| [Long-Tailed Recognition Using Class-Balanced Experts](https://arxiv.org/pdf/2004.03706.pdf) | 2020.04.07 | ``     | -   |
| [Interaction Matching for Long-Tail Multi-Label Classification](https://arxiv.org/pdf/2005.08805.pdf) | 2020.05.18 | ``     | -   |   |
| [EL: An Early-Exiting Framework for Long-tailed Classification](https://arxiv.org/pdf/2006.11979.pdf) | 2020.06.22 | ``     | -   |   |
| [Heteroskedastic and Imbalanced Deep Learning with Adaptive Regularization](https://arxiv.org/pdf/2006.15766.pdf) | 2020.06.29 | ``     | -   |   |
| [Remix: Rebalanced Mixup](https://arxiv.org/pdf/2007.03943.pdf) | 2020.07.08 | `Aug`     | -   |   |
| [Balanced Meta-Softmax for Long-Tailed Visual Recognition](https://arxiv.org/pdf/2007.10740.pdf) | 2020.07.21 | ``     | -   |   |
| [SeismoGlow: Data Augmentation for the Class Imbalance Problem](https://arxiv.org/pdf/2007.12229.pdf) | 2020.07.23 | `Aug`     | -   |   |
| [Meta Feature Modulator for Long-tailed Recognition](https://arxiv.org/pdf/2008.03428.pdf) | 2020.08.08 | `Meta`     | -   |   |
| []() | 2020.08.10 | ``     | -   |   |
| []() | 2020.08.10 | ``     | -   |   |
| []() | 2020.08.10 | ``     | -   |   |
| []() | 2020.08.10 | ``     | -   |   |
| []() | 2020.08.10 | ``     | -   |   |


## Awesome Surveys
- []() and []()



## Awesome Blogs
- []() and []()



## Imbalanced Learning
| Title    | Venue    | Type     | Code     |
|:-------- |:--------:|:--------:|:--------:|
| [Learning from Imbalanced Data](https://www.sci-hub.pl/10.1109/tkde.2008.239) | TKDE | ``     | -   |
