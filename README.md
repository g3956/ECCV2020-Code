# ECCV2020-Code
ECCV 2020 论文开源项目合集，同时欢迎各位大佬提交issue，分享ECCV 2020开源项目

关于往年CV顶会论文（如CVPR 2020、ICCV 2019、ECCV 2018）以及其他优质CV论文和大盘点，详见： https://github.com/amusi/daily-paper-computer-vision 

- [CNN](#CNN)
- [图像分类](#Image-Classification)
- [2D目标检测](#Object-Detection)
- [3D目标检测](#3D-Object-Detection)
- [视频目标检测](#Video-Object-Detection)
- [语义分割](#Semantic-Segmentation)
- [实例分割](#Instance-Segmentation)
- [单/多目标跟踪](#Object-Tracking)
- [GAN](#GAN)
- [NAS](#NAS)
- [3D点云（分类/分割/配准/补全等）](#3D-PointCloud)
- [Re-ID](#Re-ID)
- [显著性检测](#Saliency)
- [模型压缩（剪枝/知识蒸馏等）](#Model-Compression)
- [视频理解/行为识别/行为检测](#Action-Recognition)
- [超分辨率](#Super-Resolution)
- [去模糊](#Deblurring)
- [图像补全](#Image-Inpainting)
- [图像检索](#Image-Retrieval)
- [车道线检测](#Lane-Detection)
- [轨迹预测](#TP)
- [数据集](#Datasets)
- [其他](#Others)
- [不确定中没中](#Not-Sure)

<a name="CNN"></a>

# CNN

**Dynamic Group Convolution for Accelerating Convolutional Neural Networks**

- 论文：https://arxiv.org/abs/2007.04242
- 代码：https://github.com/zhuogege1943/dgc

**Learning to Learn Parameterized Classification Networks for Scalable Input Images**

- 论文：暂无

- 代码：https://github.com/d-li14/SAN

**Rethinking Bottleneck Structure for Efficient Mobile Network Design**

- 论文：https://arxiv.org/abs/2007.02269
- 代码：https://github.com/zhoudaquan/rethinking_bottleneck_design

**MutualNet: Adaptive ConvNet via Mutual Learning from Network Width and Resolution**

- 论文：Oral
- 论文：https://arxiv.org/abs/1909.12978
- 代码：https://github.com/taoyang1122/MutualNet

**PSConv: Squeezing Feature Pyramid into One Compact Poly-Scale Convolutional Layer**

- 论文：暂无
- 代码：https://github.com/d-li14/PSConv

<a name="Image-Classification"></a>

# 图像分类

**Learning to Learn Parameterized Classification Networks for Scalable Input Images**

- 论文：暂无

- 代码：https://github.com/d-li14/SAN

**Learning To Classify Images Without Labels**

- 论文：https://arxiv.org/abs/2005.12320
- 代码：https://github.com/wvangansbeke/Unsupervised-Classification

<a name="Object-Detection"></a>

# 2D目标检测

**HoughNet: Integrating near and long-range evidence for bottom-up object detection**

- 论文：https://arxiv.org/abs/2007.02355
- 代码：https://github.com/nerminsamet/houghnet

**OS2D: One-Stage One-Shot Object Detection by Matching Anchor Features**

- 论文：https://arxiv.org/abs/2003.06800

- 代码：https://github.com/aosokin/os2d

**End-to-End Object Detection with Transformers**

- Oral

- 论文：https://ai.facebook.com/research/publications/end-to-end-object-detection-with-transformers
- 代码：https://github.com/facebookresearch/detr

**Dynamic R-CNN: Towards High Quality Object Detection via Dynamic Training**

- 论文：https://arxiv.org/abs/2004.06002

- 代码：https://github.com/hkzhang95/DynamicRCNN 

## 遥感旋转目标检测

**Arbitrary-Oriented Object Detection with Circular Smooth Label**

- 论文：https://arxiv.org/abs/2003.05597
- 代码：https://github.com/Thinklab-SJTU/CSL_RetinaNet_Tensorflow

<a name="3D-Object-Detection"></a>

# 3D目标检测

**EPNet: Enhancing Point Features with Image Semantics for 3D Object Detection**

- 论文：暂无
- 代码：https://github.com/happinesslz/EPNet

<a name="Video-Object-Detection"></a>

# 视频目标检测

**Learning Where to Focus for Efficient Video Object Detection**

- 主页：https://jiangzhengkai.github.io/LSTS/
- 论文：暂无
- 代码：https://github.com/jiangzhengkai/LSTS

<a name="Semantic-Segmentation"></a>

# 语义分割

**SegFix: Model-Agnostic Boundary Refinement for Segmentation**

- 论文：https://arxiv.org/abs/2007.04269

- 代码：https://github.com/openseg-group/openseg.pytorch

**Mining Cross-Image Semantics for Weakly Supervised Semantic Segmentation**

- Oral
- 代码：https://github.com/GuoleiSun/MCIS_wsss
- 论文下载链接：https://arxiv.org/abs/2007.01947

 **Improving Semantic Segmentation via Decoupled Body and Edge Supervision**

- 论文：https://zhouchenlin.github.io/Publications/2020-ECCV-Semantic.pdf

- 代码：https://github.com/lxtGH/DecoupleSegNets

<a name="Instance-Segmentation"></a>

# 实例分割

**Conditional Convolutions for Instance Segmentation**

- Oral
- 论文：https://arxiv.org/abs/2003.05664
- 代码：https://github.com/aim-uofa/AdelaiDet/blob/master/configs/CondInst/README.md

**SOLO: Segmenting Objects by Locations**

- 论文：https://arxiv.org/abs/1912.04488
- 代码：https://github.com/WXinlong/SOLO

- 知乎话题：https://www.zhihu.com/question/360594484

<a name="Object-Tracking"></a>

# 单/多目标跟踪

**Ocean: Object-aware Anchor-Free Tracking**

- 论文：https://arxiv.org/abs/2006.10721

- 代码：https://github.com/researchmm/TracKit

## 多目标跟踪

**Ocean: Object-aware Anchor-Free Tracking**

- 论文：https://arxiv.org/abs/2006.10721

- 代码：https://github.com/researchmm/TracKit

**TAO: A Large-Scale Benchmark for Tracking Any Object**

- 主页：http://taodataset.org/
- 论文：https://arxiv.org/abs/2005.10356
- 代码：https://github.com/TAO-Dataset/tao

**Segment as Points for Efficient Online Multi-Object Tracking and Segmentation**

- Oral
- 论文：https://arxiv.org/abs/2007.01550
- 代码：https://github.com/detectRecog/PointTrack
- 数据集：https://github.com/detectRecog/PointTrack

<a name="GAN"></a>

# GAN

**XingGAN for Person Image Generation**

- 论文：暂无
- 代码：https://github.com/Ha0Tang/XingGAN

<a name="NAS"></a>

# NAS

**Rethinking Bottleneck Structure for Efficient Mobile Network Design**

- 论文：https://arxiv.org/abs/2007.02269
- 代码：https://github.com/zhoudaquan/rethinking_bottleneck_design

**Fair DARTS: Eliminating Unfair Advantages in Differentiable Architecture Search**

- 论文：https://arxiv.org/abs/1911.12126
- 代码：https://github.com/xiaomi-automl/fairdarts

<a name="3D-PointCloud"></a>

# 3D点云（分类/分割/配准/补全等）

**A Closer Look at Local Aggregation Operators in Point Cloud Analysis**

- 论文：https://arxiv.org/abs/2007.01294
- 代码：https://github.com/zeliu98/CloserLook3D

## 3D点云补全

**Multimodal Shape Completion via Conditional Generative Adversarial Networks**

- 论文：https://arxiv.org/abs/2003.07717
- 代码：https://github.com/ChrisWu1997/Multimodal-Shape-Completion

**GRNet: Gridding Residual Network for Dense Point Cloud Completion**

- 论文：https://arxiv.org/abs/2006.03761
- 代码：https://github.com/hzxie/GRNet

<a name="Re-ID"></a>

# Re-ID

**Robust Re-Identification by Multiple Views Knowledge Distillation**

- 论文：https://arxiv.org/abs/2007.04174
- 代码：https://github.com/aimagelab/VKD

**Multiple Expert Brainstorming for Domain Adaptive Person Re-identification**

- 论文：https://arxiv.org/abs/2007.01546

- 代码：https://github.com/YunpengZhai/MEB-Net

<a name="Saliency"></a>

# 显著性检测

**Cross-Modal Weighting Network for RGB-D Salient Object Detection**

- 论文：暂无

- 代码：https://github.com/MathLee/CMWNet

**BBS-Net: RGB-D Salient Object Detection with a Bifurcated Backbone Strategy Network**

- 论文：暂无
- 代码：https://github.com/DengPingFan/BBS-Net

**Highly Efficient Salient Object Detection with 100K Parameters**

- 论文：https://arxiv.org/abs/2003.05643
- 代码：https://github.com/MCG-NKU/Sal100K

<a name="Model-Compression"></a>

# 模型压缩（剪枝/知识蒸馏等）

**EagleEye: Fast Sub-net Evaluation for Efficient Neural Network Pruning**

- 论文：https://arxiv.org/abs/2007.02491
- 代码：https://github.com/anonymous47823493/EagleEye

<a name="Action-Recognition"></a>

# 视频理解/行为识别/行为检测

**Asynchronous Interaction Aggregation for Action Detection**

- 论文：https://arxiv.org/abs/2004.07485

- 代码：https://github.com/MVIG-SJTU/AlphAction 

<a name="Super-Resolution"></a>

# 超分辨率

## 图像超分辨率

**Spatial-Angular Interaction for Light Field Image Super-Resolution**

- 论文：https://arxiv.org/abs/1912.07849
- 代码：https://github.com/YingqianWang/LF-InterNet 

**Invertible Image Rescaling**

- 论文：https://arxiv.org/abs/2005.05650
- 代码：https://github.com/pkuxmq/Invertible-Image-Rescaling

<a name="Deblurring"></a>

# 去模糊

**End-to-end Interpretable Learning of Non-blind Image Deblurring**

- 论文：https://arxiv.org/abs/2007.01769
- 代码：暂无（即将出来）

<a name="Image-Inpainting"></a>

# 图像补全

**Rethinking Image Inpainting via a Mutual Encoder-Decoder with Feature Equalizations**

- Oral
- 论文：暂无
- 代码：https://github.com/KumapowerLIU/ECCV2020oralRethinking-Image-Inpainting-via-a-Mutual-Encoder-Decoder-with-Feature-Equalizations

# 图像检索

**Self-supervising Fine-grained Region Similarities for Large-scale Image Localization**

- 主页：https://yxgeee.github.io/projects/sfrs
- 论文下载链接：https://arxiv.org/abs/2006.03926

- 代码：https://github.com/yxgeee/SFRS

 Image Retrieval <a name="Lane-Detection"></a>

# 车道线检测

**Ultra Fast Structure-aware Deep Lane Detection**

- 论文：https://arxiv.org/abs/2004.11757

- 代码：https://github.com/cfzd/Ultra-Fast-Lane-Detection
- 论文解读：https://mp.weixin.qq.com/s/TYzDx8R1oUbVr0FxGnFspQ

 **Gen-LaneNet: a generalized and scalable approach for 3D lane detection** 

- 论文：https://arxiv.org/abs/2003.10656
- 代码：https://github.com/yuliangguo/Pytorch_Generalized_3D_Lane_Detection
- 数据集：https://github.com/yuliangguo/3D_Lane_Synthetic_Dataset

<a name="TP"></a>

# 轨迹预测

**SimAug: Learning Robust Representations from 3D Simulation for Pedestrian Trajectory Prediction in Unseen Cameras**

- 论文：https://arxiv.org/abs/2004.02022
- 代码：https://github.com/JunweiLiang/Multiverse

<a name="Datasets"></a>

# 数据集

**Segment as Points for Efficient Online Multi-Object Tracking and Segmentation**

- Oral
- 论文：https://arxiv.org/abs/2007.01550
- 代码：https://github.com/detectRecog/PointTrack
- 数据集：https://github.com/detectRecog/PointTrack

 **Gen-LaneNet: a generalized and scalable approach for 3D lane detection** 

- 论文：https://arxiv.org/abs/2003.10656
- 代码：https://github.com/yuliangguo/Pytorch_Generalized_3D_Lane_Detection
- 数据集：https://github.com/yuliangguo/3D_Lane_Synthetic_Dataset

**TAO: A Large-Scale Benchmark for Tracking Any Object**

- 主页：http://taodataset.org/
- 论文：https://arxiv.org/abs/2005.10356
- 代码：https://github.com/TAO-Dataset/tao

**Structured3D: A Large Photo-realistic Dataset for Structured 3D Modeling**

- 主页：[http://structured3d-dataset.org](http://structured3d-dataset.org/)
- 论文：https://arxiv.org/abs/1908.00222
- 代码：https://github.com/bertjiazheng/Structured3D 

**AiR: Attention with Reasoning Capability**

- 论文：暂无

- 代码：https://github.com/szzexpoi/AiR
- 数据集：https://github.com/szzexpoi/AiR

<a name="Others"></a>

# 其他

**GIQA: Generated Image Quality Assessment**

- 论文：https://arxiv.org/abs/2003.08932
- 代码：https://github.com/cientgu/GIQA

**Structured3D: A Large Photo-realistic Dataset for Structured 3D Modeling**

- 主页：[http://structured3d-dataset.org](http://structured3d-dataset.org/)
- 论文：https://arxiv.org/abs/1908.00222
- 代码：https://github.com/bertjiazheng/Structured3D 

**AiR: Attention with Reasoning Capability**

- 论文：暂无

- 代码：https://github.com/szzexpoi/AiR
- 数据集：https://github.com/szzexpoi/AiR

**Square Attack: a query-efficient black-box adversarial attack via random search**

- 论文：https://arxiv.org/abs/1912.00049
- 代码：https://github.com/max-andr/square-attack

<a name="Not-Sure"></a>

# 不确定中没中

**Relation Aware Panoptic Segmentation**

- 论文：暂无
- 代码：https://github.com/RAPNet/RAP

**Spatial-Angular Interaction for Light Field Image Super-Resolution**

- 论文：暂无
- 代码：https://github.com/YingqianWang/LF-InterNet

**TVR: A Large-Scale Dataset for Video-Subtitle Moment Retrieval**

- 论文：https://arxiv.org/abs/2001.09099
- 代码：https://github.com/jayleicn/TVRetrieval
- 代码：https://github.com/jayleicn/TVCaption

**Self-supervising Fine-grained Region Similarities for IBL**

- 论文：暂无
- 代码： https://github.com/ID2191/ECCV2020 

https://github.com/lelechen63/eccv2020

