# Semantic-Segmentation
List of useful codes and papers for semantic segmentation(weakly)

## code

[pytorch-segmentation-detection](https://github.com/warmspringwinds/pytorch-segmentation-detection) a library for dense inference and training of Convolutional Neural Networks, 68.0%

[rdn](https://github.com/fyu/drn) Dilated Residual Networks, 75.6%, may be the best available semantic segmentation in PyTorch?

[Detectron.pytorch](https://github.com/roytseng-tw/Detectron.pytorch) A pytorch implementation of Detectron. Both training from scratch and inferring directly from pretrained Detectron weights are available. only for coco now

[AdvSemiSeg](https://github.com/hfslyc/AdvSemiSeg) Adversarial Learning for Semi-supervised Semantic Segmentation.  heavily borrowed from a **pytorch DeepLab** implementation ([Link](https://github.com/speedinghzl/Pytorch-Deeplab))

[PyTorch-ENet](https://github.com/davidtvs/PyTorch-ENet) PyTorch implementation of ENet

[tensorflow-deeplab-resnet](https://github.com/DrSleep/tensorflow-deeplab-resnet) Tensorflow implementation of deeplab-resnet(deeplabv2, resnet101-based): complete and detailed

[tensorflow-deeplab-lfov](https://github.com/DrSleep/tensorflow-deeplab-lfov) Tensorflow implementation of deeplab-LargeFOV(deeplabv2, vgg16-based): complete and detailed

[resnet38](https://github.com/itijyou/ademxapp)  Wider or Deeper: Revisiting the ResNet Model for Visual Recognition: implemented using MXNET

## papers
#### random walk
Learning random-walk label propagation for weakly-supervised semantic segmentation: scribble

Convolutional Random Walk Networks for Semantic Image Segmetation: fully, affinity branch(low level)

Soft Proposal Networks for Weakly Supervised Object Localization: attention, semantic affinity

Learning Pixel-level Semantic Affinity with Image-level Supervision for Weakly Supervised Semantic Segmentation: image-level, semantic affinity

## Top works
#### PASCAL VOC2012

| method | val | test       |  notes |
| ------------ | ---------- | ---------- | ---------- |
| [DSRG](https://github.com/speedinghzl/DSRG)<sub>CVPR2018</sub> | 61.4 | 63.2 | deep seeded region growing  |
| [psa](https://github.com/jiwoon-ahn/psa)<sub>CVPR2018</sub> | **61.7** | **63.7** | pixel affinity network |
| [MDC](https://arxiv.org/pdf/1805.04574.pdf)<sub>CVPR2018</sub> | 60.4 | 60.8 | multi-dilated convolution |
| [MCOF](http://3dimage.ee.tsinghua.edu.cn/wx/mcof)<sub>CVPR2018</sub> | 60.3 | 61.2 | iterative, RegionNet(sppx)|
| [DCSP](https://github.com/arslan-chaudhry/dcsp_segmentation)<sub>BMVC2017</sub> | 58.6 | 59.2 | adversarial, TBD|
| [GuidedSeg](https://github.com/coallaoh/GuidedLabelling)<sub>CVPR2017</sub> | 55.7 | 56.7 | saliency, TBD|

#### COCO

## Others
see [this](https://github.com/JackieZhangdx/WeakSupervisedSegmentationList) for more lists and resources. 

## Reading List
#### adversarial
- [ ] generative adversial learning towards Fast weakly supervised detection
- [ ] Adversarial Complementary Learning for Weakly Supervised Object Localization
- [ ] Weakly Supervised Object Discovery by Generative Adversarial & Ranking Networks: arkiv

####
- [ ] Learning to Segment Every Thing
- [ ] Multi-Evidence Filtering and Fusion for Multi-Label Classification, Object Detection and Semantic Segmentation Based on Weakly Supervised Learning

#### generate
- [ ] ScanComplete: Large-Scale Scene Completion and Semantic Segmentation for 3D Scans
- [ ] SeGAN: Segmenting and Generating the Invisible

#### network +
- [ ] Learning a Discriminative Feature Network for Semantic Segmentation
- [ ] Fully Convolutional Adaptation Networks for Semantic Segmentation
- [ ] Context Encoding for Semantic Segmentation
- [ ] Learned Shape-Tailored Descriptors for Segmentation
- [ ] Normalized Cut Loss for Weakly-Supervised CNN Segmentation

#### urban
