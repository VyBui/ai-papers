# AI Papers and Notes

## Paper Notes

- [Guided Anchoring](notes/guided_anchoring.md)
- [Cascade R-CNN](notes/cascade_rcnn.md)
- [Hybrid Task Cascade](notes/htc.md)
- [RetinaNet/Focal Loss](notes/retinanet.md)
- [Light-Head R-CNN](notes/lighthead_rcnn.md)
- [Data Distillation](notes/data_distillation.md)
- [YOLO v1](notes/yolo.md)

## Read but no notes


- [Fast R-CNN](https://arxiv.org/abs/1504.08083). April 2015
- [Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks](https://arxiv.org/abs/1506.01497). June 2015
- [Mask R-CNN](https://arxiv.org/abs/1703.06870). March 2017
- [MegDet: A Large Mini-Batch Object Detector](https://arxiv.org/abs/1711.07240). Nov 2017. Introduced SyncBN
- [[FPN] Feature Pyramid Networks for Object Detection](https://arxiv.org/abs/1612.03144). Dec 2016.
- [TF-Replicator: Distributed Machine Learning For Researchers](https://arxiv.org/pdf/1902.00465.pdf)
- [Accurate, Large Minibatch SGD: Training ImageNet in 1 Hour](https://arxiv.org/abs/1706.02677). June 2017. Facebook. ResNet time-to-train SotA. Paper with Linear Scaling Rule: scale LR linearly with batch size
- [Highly Scalable Deep Learning Training System with Mixed-Precision: Training ImageNet in Four Minutes](https://arxiv.org/abs/1807.11205) July 2018. Tencent. ResNet time-to-train SotA 
- [ImageNet/ResNet-50 Training in 224 Seconds](https://arxiv.org/abs/1811.05233). Nov 2018. Sony. ResNet time-to-train SotA
- [Large Batch Training of Convolutional Networks](https://arxiv.org/abs/1708.03888). Layer-wise adaptive rate scaling (LARS)
- [[SENet] Squeeze-and-Excitation Networks](https://arxiv.org/abs/1709.01507). Sept 2017.
- [Cyclical Learning Rates for Training Neural Networks](https://arxiv.org/abs/1506.01186). June 2015
- [Don't Decay the Learning Rate, Increase the Batch Size](https://arxiv.org/abs/1711.00489). Nov 2017.
- [[ResNet] Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385). Dec 2015
- [Memory-Efficient Backpropagation Through Time](https://arxiv.org/abs/1606.03401). June 2016
- [In-Place Activated BatchNorm for Memory-Optimized Training of DNNs](https://arxiv.org/abs/1712.02616). Dec 2017
- [Training Deep Nets with Sublinear Memory Cost](https://arxiv.org/abs/1604.06174.pdf)
- [Group Normalization](https://arxiv.org/abs/1803.08494). March 2018
- [[C3D] Learning Spatiotemporal Features with 3D Convolutional Networks](https://arxiv.org/abs/1412.0767)
- [[OFF] Optical Flow Guided Feature: A Fast and Robust Motion Representation for Video Action Recognition](https://arxiv.org/abs/1711.11152)
- [[I3D] Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset](https://arxiv.org/abs/1705.07750). May 2017. DeepMind
- [DistInit: Learning Video Representations without a Single Labeled Video](https://arxiv.org/pdf/1901.09244.pdf). Jan 2019. CMU + Facebook + Dartmouth + ArgoAI
- [What Makes a Video a Video: Analyzing Temporal Information in Video Understanding Models and Dataset](http://ai.stanford.edu/~dahuang/papers/cvpr18-fb.pdf). FAIR. CVPR 2018
- [A Closer Look at Spatiotemporal Convolutions for Action Recognition](https://research.fb.com/publications/a-closer-look-at-spatiotemporal-convolutions-for-action-recognition/). FAIR, CVPR 2018
- [Mask Scoring R-CNN](https://arxiv.org/pdf/1903.00241.pdf). Mar 2019. Horizon Robotics. Mask RCNN + scoring block that learns quality of predictions. Beats MaskRCNN accuracy.
- [FishNet: A Versatile Backbone for Image, Region, and Pixel Level Prediction](https://arxiv.org/abs/1901.03495). Jan 2019. Best new backbone? Resnet+ accuracy with fewer params. Part of SotA entry COCO Object Detection 2018
- [[Transformer] Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- [NAS-FPN: Learning Scalable Feature Pyramid Architecture for Object Detection](https://arxiv.org/abs/1904.07392). Apr 2019. Google Brain.
- [Large-Batch Training for LSTM and Beyond](https://arxiv.org/abs/1901.08256). Jan 2019. Google + UC Berkely + UCLA
- [Reducing BERT Pre-Training Time from 3 Days to 76 Minutes](https://arxiv.org/abs/1904.00962). Apr 2019. Google + UC Berkely + UCLA. Many overlapping authors with 'Large-Batch Training for LSTM and Beyond'
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/pdf/1810.04805.pdf). Google LM, Oct 2018 SotA (pre MT-DNN which uses BERT to set new SotA)
- [Stochastic Gradient Push for Distributed Deep Learning](https://research.fb.com/publications/stochastic-gradient-push-for-distributed-deep-learning/). FAIR, NeurIPs 2018
- [Deep Learning on Graphs: A Survey](https://arxiv.org/pdf/1812.04202.pdf) Dec 2018. Tsinghua University
- [Yet Another Accelerated SGD: ResNet-50 Training on ImageNet in 74.7 seconds](https://arxiv.org/pdf/1903.12650.pdf). Mar 2019. Fujitsu
- [Graph Neural Networks: A Review of Methods and Applications](https://arxiv.org/pdf/1812.08434.pdf). July 2019. Tsinghua University, Tencent

## Unread Papers

#### High Priority

- [Faster Training of Mask R-CNN by Focusing on Instance Boundaries](https://arxiv.org/pdf/1809.07069.pdf). Mar 2019. BMW
- [Transformer-XL: Attentive Language Models Beyond A Fixed-Length Context](https://arxiv.org/pdf/1901.02860.pdf). Jan 2019 SotA. Pre-GPT-2. CMU + Google Brain
- [[ODENet] Neural Ordinary Differential Equations](https://arxiv.org/pdf/1806.07366.pdf). NeurIPS 2018 best paper, time-series.
- [AlphaStar](https://deepmind.com/blog/alphastar-mastering-real-time-strategy-game-starcraft-ii/). DeepMind. Starcraft II RL agent that reaches ~95% percentile of human players.
- [[YOLOv2] YOLO9000: Better, Faster, Stronger](https://arxiv.org/abs/1612.08242). Dec 2016
- [YOLOv3: An Incremental Improvement](https://arxiv.org/abs/1804.02767) April 2018
- [Deformable Convolutional Networks](https://arxiv.org/abs/1703.06211). June 2017
- [Deformable ConvNets v2: More Deformable, Better Results](https://arxiv.org/abs/1811.11168). Nov 2018
- [R-FCN: Object Detection via Region-based Fully Convolutional Networks](https://arxiv.org/abs/1605.06409). May 2016. Object detection
- [[PANet] Path Aggregation Network for Instance Segmentation](https://arxiv.org/abs/1803.01534) . March 2018. FPN top-down path + new bottom-up path. [Referenced from HTC paper literature review]
- [DeNet: Scalable Real-time Object Detection with Directed Sparse Sampling](https://arxiv.org/abs/1703.10295). object detection is estimating a very large but extremely sparse bounding box dependent probability distribution
- [Speeding up Deep Learning with Transient Servers](https://arxiv.org/pdf/1903.00045.pdf). Feb 2019. WPI, Chinese Academy of Sciences
- [A Structured Model For Action Detection](https://arxiv.org/pdf/1812.03544.pdf). Feb 2019. CMU, Google. SotA on AVA dataset (according to abstract.)
- [Lingvo: a Modular and Scalable Framework for Sequence-to-Sequence Modeling](https://arxiv.org/pdf/1902.08295.pdf). Feb 2019. Google (presumably). https://github.com/tensorflow/lingvo
- [FIXUP INITIALIZATION: RESIDUAL LEARNING WITHOUT NORMALIZATION](https://arxiv.org/pdf/1901.09321.pdf). Jan 2019. Work done at Facebook.
- [Scale-Aware Trident Networks for Object Detection](https://arxiv.org/pdf/1901.01892.pdf). Mar 2019. University of Chinese Academy of Sciences, TuSimple. SotA COCO object detection
- [Temporal Shift Module for Efficient Video Understanding](https://arxiv.org/pdf/1811.08383.pdf). Nov 2018. MIT
- [Libra R-CNN: Towards Balanced Learning for Object Detection](https://arxiv.org/pdf/1904.02701.pdf). Apr 2019. Zhejiang University, The Chinese University of Hong Kong, SenseTime Research, The University of Sydney


#### Medium Priority


- [[PlanNet] Learning Latent Dynamics for Planning from Pixels](https://arxiv.org/abs/1811.04551) ([blog](https://ai.googleblog.com/2019/02/introducing-planet-deep-planning.html)). Google. A Deep Planning Network for Reinforcement Learning 
- [[GPT] Improving Language Understanding by Generative Pre-Training](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf).  OpenAI LM, June 2018 SotA (pre BERT). Minimal benchmark overlap with ELMo
- [[GPT-2] Language Models are Unsupervised Multitask Learners](https://d4mucfpksywv.cloudfront.net/better-language-models/language-models.pdf). Feb 2019 SotA, Multi-task NLP
- [[MT-DNN] Multi-Task Deep Neural Networks for Natural Language Understanding](https://arxiv.org/abs/1901.11504). , Microsoft. BERT + Multi-task model. Feb 2019 SotA, Multi-task NLP (comparison with GPT-2 unknown) 
- [[NASNet] Learning Transferable Architectures for Scalable Image Recognition](https://arxiv.org/abs/1707.07012) ([blog](https://ai.googleblog.com/2017/11/automl-for-large-scale-image.html)). Google Brain. July 2017.
- [Training Deep Neural Networks with 8-bit Floating Point Numbers](https://arxiv.org/abs/1812.08011). IBM Watson. December 2018
- [LAG: Lazily Aggregated Gradient for Communication-Efficient Distributed Learning](https://arxiv.org/abs/1805.09965). NeurIPs 2018
- [GradiVeQ: Vector Quantization for Bandwidth-Efficient Gradient Aggregation in Distributed CNN Training](https://arxiv.org/abs/1811.03617). NeurIPs 2018
- [Large-Scale Study of Curiosity-Driven Learning](https://pathak22.github.io/large-scale-curiosity/resources/largeScaleCuriosity2018.pdf). OpenAI
- [You May Not Need Attention](https://arxiv.org/abs/1810.13409)
- [Human-level performance in first-person multiplayer games with population-based deep reinforcement learning](https://arxiv.org/abs/1807.01281) ([blog](https://deepmind.com/blog/capture-the-flag/)). Jul 2018. Have agents play each other
- [CRAFT: Complementary Recommendations Using Adversarial Feature Transformer](https://arxiv.org/abs/1804.10871). Amazon.com. April 2018.
- [SSD: Single Shot MultiBox Detector](https://arxiv.org/abs/1512.02325). Dec 2015 
- [FEDERATED LEARNING FOR MOBILE KEYBOARD PREDICTION](https://arxiv.org/pdf/1811.03604.pdf). Feb 2019. Google.
- [ConvNet Architecture Search for Spatiotemporal Feature Learning](https://arxiv.org/pdf/1708.05038.pdf). Aug 2017. FB + Columbia
- [Rethinking Spatiotemporal Feature Learning: Speed-Accuracy Trade-offs in Video Classification](https://arxiv.org/pdf/1712.04851.pdf) July 2018. Google + UCSD
- [50 Years of Test (Un)fairness: Lessons for Machine Learning](https://arxiv.org/pdf/1811.10104.pdf). Dec 2018. Google
- [Scalable Deep Learning on Distributed Infrastructures: Challenges, Techniques and Tools](https://arxiv.org/pdf/1903.11314.pdf). Mar 2019. Technical University of Munich
- [GS3D: An Efficient 3D Object Detection Framework for Autonomous Driving](https://arxiv.org/pdf/1903.10955.pdf). Mar 2019. CUHK + SenseTime + University Sydney + Beihang University
- [nuScenes: A multimodal dataset for autonomous driving](https://arxiv.org/pdf/1903.11027.pdf). Mar 2019. nuTonomy
- [DetNAS: Neural Architecture Search on Object Detection](https://arxiv.org/pdf/1903.10979.pdf). Mar 2019. Chinese Academy of Science + Megvii
- [Large-scale interactive object segmentation with human annotators](https://arxiv.org/pdf/1903.10830.pdf). Mar 2019. Google
- [TensorFlow Eager: A Multi-Stage, Python-Embedded DSL for Machine Learning](https://arxiv.org/abs/1903.01855). Feb 2019. Google Brain
- [Compressed Video Action Recognition](https://arxiv.org/pdf/1712.00636.pdf). Dec 2017. CVPR 2018. UT Austin + Amazon + A9 + USC + CMU
- [DetNet: A Backbone network for Object Detection](https://arxiv.org/abs/1804.06215). April 2018
- [[ResNeXt] Aggregated Residual Transformations for Deep Neural Networks](https://arxiv.org/abs/1611.05431). Nov 2016.
- [[LASER] Massively Multilingual Sentence Embeddings for Zero-Shot Cross-Lingual Transfer and Beyond](https://arxiv.org/abs/1812.10464) ([blog](https://code.fb.com/ai-research/laser-multilingual-sentence-embeddings/)). Dec 2018.
- [MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications](https://arxiv.org/abs/1704.04861). Google. Apr 2017
- [MobileNetV2: Inverted Residuals and Linear Bottlenecks](https://arxiv.org/abs/1801.04381). Google. Jan 2018.
- [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597). May 2015
- [[MVCNN] Multi-view Convolutional Neural Networks for 3D Shape Recognition](https://arxiv.org/abs/1505.00880). May 2015
- [Measuring the Effects of Data Parallelism on Neural Network Training](https://arxiv.org/abs/1811.03600)
- [Optimal Algorithms for Non-Smooth Distributed Optimization in Networks](https://arxiv.org/abs/1806.00291). NeurIPS 2018 best paper 
- [Speed/accuracy trade-offs for modern convolutional object detectors](https://arxiv.org/abs/1611.10012). Nov 2016


#### Unprioritized


- [CondenseNet: An Efficient DenseNet using Learned Group Convolutions](https://research.fb.com/publications/condensenet-an-efficient-densenet-using-learned-group-convolutions/). FAIR, CVPR 2018
- [Deep Spatio-Temporal Random Fields for Efficient Video Segmentation](https://research.fb.com/publications/deep-spatio-temporal-random-fields-for-efficient-video-segmentation/). FAIR, CVPR 2018
- [Detail-Preserving Pooling in Deep Networks](https://research.fb.com/publications/detail-preserving-pooling-in-deep-networks/). FAIR, CVPR 2018
- [Detect-and-Track: Efficient Pose Estimation in Videos](https://research.fb.com/publications/detect-and-track-efficient-pose-estimation-in-videos/). FAIR, CVPR 2018
- [Detecting and Recognizing Human-Object Interactions](https://research.fb.com/publications/detecting-and-recognizing-human-object-interactions/). FAIR, CVPR 2018
- [LAMV: Learning to align and match videos with kernelized temporal layers](https://research.fb.com/publications/lamv-learning-to-align-and-match-videos-with-kernelized-temporal-layers/). FAIR, CVPR 2018
- [Learning to Segment Every Thing](https://research.fb.com/publications/learning-to-segment-every-thing/). FAIR, CVPR 2018
- [What Makes a Video a Video: Analyzing Temporal Information in Video Understanding Models and Datasets](https://research.fb.com/publications/what-makes-a-video-a-video-analyzing-temporal-information-in-video-understanding-models-and-datasets/). FAIR, CVPR 2018
- [Revisiting Self-Supervised Visual Representation Learning](https://arxiv.org/pdf/1901.09005.pdf). Google Brain
- [Self-Driving Cars: A Survey](https://arxiv.org/pdf/1901.04407.pdf)
- [Non-delusional Q-learning and Value Iteration](https://papers.nips.cc/paper/8200-non-delusional-q-learning-and-value-iteration.pdf). NeurIPS 2018 best paper
- [Learning Unsupervised Learning Rules](https://arxiv.org/pdf/1804.00222.pdf). Google Brain, meta-learning, mid 2018
- [Spherical CNNs](https://openreview.net/pdf?id=Hkbd5xZRb). ICLR 2018 Best Paper
- [Continuous Adaptation Via Meta-Learing In Nonstationary And Competitive Environments](https://openreview.net/pdf?id=Sk2u1g-0-). ICLR 2018 Best Paper
- [On the Convergence of Adam and Beyond ](https://openreview.net/forum?id=ryQu7f-RZ). ICLR 2018 Best Paper
- [GLUE: A Multi-Task Benchmark and Analysis Platform for Natural Language Understanding](https://www.nyu.edu/projects/bowman/glue.pdf)
- [[DecaNLP] The Natural Language Decathlon: Multitask Learning as Question Answering](https://arxiv.org/abs/1806.08730). Benchmark task
- [[ELMo] Deep contextualized word representations](https://arxiv.org/pdf/1802.05365.pdf). Mar 2018 SotA (pre BERT). Minimal benchmark overlap with GPT.
- [Universal Transformers](https://arxiv.org/abs/1807.03819). July 2018
- [[MS-CNN] A Unified Multi-scale Deep Convolutional Neural Network for Fast Object Detection](https://arxiv.org/abs/1607.07155). Multi-scale object detection. FPN related?
- [[AttractioNet] Attend Refine Repeat: Active Box Proposal Generation via In-Out Localization](https://arxiv.org/abs/1606.04446). Multi-stage procedure for generating accurate object proposals. Attend-and-refine module to update bounding box locations iteratively. [References from HTC paper literature review]  
- [CRAFT Objects from Images](https://arxiv.org/abs/1604.03239). Incorporates cascade structure into RPN. [References from HTC paper literature review]
- [A Comprehensive Survey of Deep Learning for Image Captioning](https://arxiv.org/pdf/1810.04020.pdf)
- [[Instance-FCN] Instance-sensitive Fully Convolutional Networks](https://arxiv.org/abs/1603.08678). Detection based, instance segmentation. [References from HTC paper literature review]
- [[MNC] Instance-aware Semantic Segmentation via Multi-task Network Cascades](https://arxiv.org/abs/1512.04412) Dec 2015. Detection based, instance segmentation. Three subtasks (instance localization, mask prediction, object categorization) trained in cascade manner [References from HTC paper literature review]
- [[FCIS] Fully Convolutional Instance-aware Semantic Segmentation](https://arxiv.org/abs/1611.07709) Nov 2016. Detection based, instance segmentation. Extends InstanceFCN. Fully convolutional [References from HTC paper literature review]
- MaskLab, DeepMask, SharpMask (detection based, instance segmentation) [References from HTC paper literature review]
- Multi-region CNN (iteratize localization mechanism that alternates between box scoring and location refinement) [References from HTC paper literature review]
- IoUNet (performs progressive bounding box refinement, even though not presenting a cascade structure explicitly) [References from HTC paper literature review]
- CC-Net (rejects easy RoIs at shallow layers) [References from HTC paper literature review]
- A convolutional neural network cascade for face detection (proposes to operate at multiple resolutions to reject simple samples) [Referenced from HTC paper literature review]
- [COCO-Stuff: Thing and Stuff Classes in Context](https://arxiv.org/pdf/1612.03716.pdf). COCO dataset augmentation with pixelwise stuff annotations. Things are classes like 'cars', 'bikes'. Stuff is :'sky', 'grass'.
- Atrous Spatial Pyramid Pooling (ASPP)
- Global Convolutional Network (GCN)
- SoftNMS 
- [[A3C] Asynchronous Methods for Deep Reinforcement Learning](https://arxiv.org/pdf/1602.01783.pdf) DeepMind. RL.
- D4PG (RL)
- [StarCraft AI Competitions, Bots and Tournament Manager Software](https://www.researchgate.net/publication/329202945_StarCraft_AI_Competitions_Bots_and_Tournament_Manager_Software)
- [StarCraft II: A New Challenge for Reinforcement Learning](https://arxiv.org/abs/1708.04782). The Starcraft II learning environment
- [Deep reinforcement learning with relational inductive biases](https://openreview.net/forum?id=HkxaFoC9KQ). DeepMind. ICLR 2019. Starcraft II minigame SotA.
- [Counterfactual Multi-Agent Policy Gradients](https://arxiv.org/abs/1705.08926). Mid-late 2017
- [A Unified Game-Theoretic Approach to Multiagent Reinforcement Learning](https://arxiv.org/pdf/1711.00832.pdf). DeepMind. Nov 2017
- [IMPALA: Scalable Distributed Deep-RL with Importance Weighted Actor-Learner Architectures](https://arxiv.org/abs/1802.01561). DeepMind. Feb 2018.
- [Self-Imitation Learning](https://arxiv.org/abs/1806.05635). RL. Google Brain. June 2018. "a simple off-policy actor-critic algorithm"
- [Generative Adversarial Self-Imitation Learning](https://arxiv.org/abs/1812.00950) Dec 2018. Google Brain
- [POLICY DISTILLATION](https://arxiv.org/pdf/1511.06295.pdf). DeepMind. Jan 2016.
- [Re-evaluating Evaluation](https://arxiv.org/abs/1806.02643). DeepMind. NeurIPS 2018. RL.
- [AlphaZero](https://arxiv.org/pdf/1712.01815.pdf) ([blog](https://deepmind.com/blog/alphazero-shedding-new-light-grand-games-chess-shogi-and-go])). Chess, self-playing
- AlphaFold ([blog](https://deepmind.com/blog/alphafold/))
- [Demystifying Parallel and Distributed Deep Learning: An In-Depth Concurrency Analysis](https://arxiv.org/abs/1802.09941). Feb 2018. 
- [FBNet: Hardware-Aware Efficient ConvNet Design via Differentiable Neural Architecture Search](https://arxiv.org/abs/1812.03443). Dec 2018
- [Random Search and Reproducibility for Neural Architecture Search](https://arxiv.org/abs/1902.07638). Feb 2019. CMU
- [Deep Object-Centric Policies for Autonomous Driving](https://arxiv.org/pdf/1811.05432.pdf). Mar 2019. UC Berkeley
- [Accelerating Self-Play Learning in Go](https://arxiv.org/pdf/1902.10565.pdf). Mar 2019. Jane Street
- [Representation Flow for Action Recognition](https://arxiv.org/pdf/1810.01455.pdf). Mar 2019, Indiana University. Abstract claim advantage in computational speed and 'performance'
- [Multimodal Trajectory Predictions for Autonomous Driving using Deep Convolutional Networks](https://arxiv.org/pdf/1809.10732.pdf). Mar 2019. Uber ATG
- [Continuous Integration of Machine Learning Models with ease.ml/ci: Towards a Rigorous Yet Practical Treatment](https://arxiv.org/pdf/1903.00278.pdf). Mar 2019. Many authors: ETH Zurich, Alibaba Group, Huawei Technologies, Modulos AG, Microsoft Research
- [Object Recognition in Deep Convolutional Neural Networks is Fundamentally Different to That in Humans](https://arxiv.org/pdf/1903.00258.pdf). Mar 2019. University of Aberdeen, University of Essex. psychology dept.
- [Double Quantization for Communication-Efficient Distributed Optimization](https://arxiv.org/pdf/1805.10111.pdf). Mar 2019. Tsinghua University, Tencent AI 
- [RESTRUCTURING BATCH NORMALIZATION TO ACCELERATE CNN TRAINING](https://arxiv.org/pdf/1807.01702.pdf). Mar 2019. Seoul National University and Samsung. SysML
- [Characterizing Activity on the Deep and Dark Web](https://arxiv.org/pdf/1903.00156.pdf). Mar 2019. USC, Georgia Tech. Interesting data set.
- [Video Extrapolation with an Invertible Linear Embedding](https://arxiv.org/pdf/1903.00133.pdf). Mar 2019. BYU. Predict future video frames.
- [Video Summarization via Actionness Ranking](https://arxiv.org/pdf/1903.00110.pdf). Mar 2019. University of Central Florida, Center for Research in Computer Vision (CRCV).
- [Actor and Action Video Segmentation from a Sentence](https://arxiv.org/pdf/1803.07485.pdf). Mar 2018. University of Amsterdam
- [Diagnosing Bottlenecks in Deep Q-learning Algorithms](https://arxiv.org/pdf/1902.10250.pdf). Feb 2019. UC Berkeley
- [BERT for Joint Intent Classification and Slot Filling](https://arxiv.org/pdf/1902.10909.pdf). Feb 2019. Alibaba.
- [Efficient Video Classification Using Fewer Frames](https://arxiv.org/pdf/1902.10640.pdf). Feb 2019. Indian Institute of Technology Madras, NVIDIA Bangalore
- [An End-to-End Network for Panoptic Segmentation](https://arxiv.org/pdf/1903.05027.pdf). Mar 2019. Zhejiang University, Megvii. 'Promising results' on COCO Panoptic
- [Two-Stream Oriented Video Super-Resolution for Action Recognition](https://arxiv.org/pdf/1903.05577.pdf). Mar 2019. University of Science and Technology of China
- [SimpleDet: A Simple and Versatile Distributed Framework for Object Detection and Instance Recognition](https://arxiv.org/pdf/1903.05831.pdf). Mar 2019. MXNet (w/ extra C++ ops) object detection development framework.
- [Deep learning for time series classification: a review](https://arxiv.org/pdf/1809.04356.pdf). Mar 2019. 
- [ADAPTIVE COMMUNICATION STRATEGIES TO ACHIEVE THE BEST ERROR-RUNTIME TRADE-OFF IN LOCAL-UPDATE SGD](https://arxiv.org/pdf/1810.08313.pdf). Mar 2019. SysML. CMU
- [Real time backbone for semantic segmentation](https://arxiv.org/pdf/1903.06922.pdf). Mar 2019. 
- [Learning Correspondence from the Cycle-consistency of Time](https://arxiv.org/pdf/1903.07593.pdf). Mar 2019. CMU + UC-Berkeley "We introduce a self-supervised method for learning visual correspondence from unlabeled video"
- [Scaling Human Activity Recognition to edge devices](https://arxiv.org/pdf/1903.07563.pdf). Mar 2019. UCSD. Looks at I3D and TSM
- [Understanding the Limitations of CNN-based Absolute Camera Pose Regression](https://arxiv.org/pdf/1903.07504.pdf). Mar 2019. Chalmers University of Technology, TU Munich, ETH Zurich, Microsoft
- [IVANET: LEARNING TO JOINTLY DETECT AND SEGMENT OBJETS WITH THE HELP OF LOCAL TOP-DOWN MODULES](https://arxiv.org/pdf/1903.07360.pdf). Mar 2019. Northeastern University (of Shenyang, Liaoning province, China)
- [In Defense of Pre-trained ImageNet Architectures for Real-time Semantic Segmentation of Road-driving Images](https://arxiv.org/pdf/1903.08469.pdf). Mar 2019. University of Zagreb
- [Cloze-driven Pretraining of Self-attention Networks](https://arxiv.org/pdf/1903.07785.pdf). Mar 2019. FAIR. "We present a new approach for pretraining a bi-directional transformer model that provides significant performance gains across a variety of language understanding problems"
- [TICTAC: ACCELERATING DISTRIBUTED DEEP LEARNING WITH COMMUNICATION SCHEDULING](https://arxiv.org/abs/1803.03288). Mar 2018. SysML 2019. University of Illinois at UrbanaChampaign
- [PipeDream: Fast and Efficient Pipeline Parallel DNN Training](https://arxiv.org/pdf/1806.03377.pdf). June 2018. Microsoft Research + Carnegie Mellon University + Stanford University
- [PRIORITY-BASED PARAMETER PROPAGATION FOR DISTRIBUTED DNN TRAINING](https://www.sysml.cc/doc/2019/75.pdf). SysML 2019. University of British Columbia + Vector Institute + CMU + University of Toronto
- [BLUECONNECT: DECOMPOSING ALL-REDUCE FOR DEEP LEARNING ON HETEROGENEOUS NETWORK HIERARCHY](https://www.sysml.cc/doc/2019/130.pdf). SysML 2019. IBM
- [BEYOND DATA AND MODEL PARALLELISM FOR DEEP NEURAL NETWORKS](https://www.sysml.cc/doc/2019/16.pdf). SysML 2019. Stanford (Matei Zaharia)
- [3LC: Lightweight and Effective Traffic Compression for Distributed Machine Learning](https://arxiv.org/abs/1802.07389). Feb 2018. SysML 2019. CMU + Intel
- [CATDET: CASCADED TRACKED DETECTOR FOR EFFICIENT OBJECT DETECTION FROM VIDEO](https://arxiv.org/abs/1810.00434). Sep 2018. SysML 2019. Stanford + NVIDIA
- [AdaScale: Towards Real-time Video Object Detection Using Adaptive Scaling](https://arxiv.org/abs/1902.02910). Feb 2019. SysML 2019. CMU
- [Restructuring Batch Normalization to Accelerate CNN Training](https://arxiv.org/abs/1807.01702). March 2019. SysML 2019. Seoul National University + Samsung
- [Bandana: Using Non-volatile Memory for Storing Deep Learning Models](https://arxiv.org/abs/1811.05922). Nov 2018. SysML 2019. Stanford + Facebook
- [Mini-batch Serialization: CNN Training with Inter-layer Data Reuse](https://arxiv.org/abs/1810.00307). Sep 2018. SysML 2019. UT Austin + UMich + Duke
- [DATA VALIDATION FOR MACHINE LEARNING](https://www.sysml.cc/doc/2019/167.pdf). SysML 2019. Google + KAIST
- [KERNEL MACHINES THAT ADAPT TO GPUS FOR EFFECTIVE LARGE BATCH TRAINING](https://arxiv.org/abs/1806.06144). June 2018. SysML 2019. Ohio State
- [Looking Fast and Slow: Memory-Guided Mobile Video Object Detection](https://arxiv.org/pdf/1903.10172.pdf). Mar 2019. Cornell + Google
- [Adversarial Joint Image and Pose Distribution Learning for Camera Pose Regression and Refinement](https://arxiv.org/pdf/1903.06646.pdf). Mar 2019. Technical University of Munich + Siemens AG + Johns Hopkins University
- [Spiking-YOLO: Spiking Neural Network for Real-time Object Detection](https://arxiv.org/pdf/1903.06530.pdf). Mar 2019.  Seoul National University
- [Few-Shot Learning-Based Human Activity Recognition](https://arxiv.org/pdf/1903.10416.pdf). Mar 2019. UMass Amherst
- [Fast Interactive Object Annotation with Curve-GCN](https://arxiv.org/pdf/1903.06874.pdf). Mar 2019. University of Toronto + Vector Institute + NVIDIA
- [BLVD: Building A Large-scale 5D Semantics Benchmark for Autonomous Driving](https://arxiv.org/pdf/1903.06405.pdf). Mar 2019.  Xian Jiaotong University + Chang’an University
- [Two-Stream Oriented Video Super-Resolution for Action Recognition](https://arxiv.org/pdf/1903.05577.pdf). Mar 2019. University of Science and Technology of China
- [Activation Analysis of a Byte-Based Deep Neural Network for Malware Classification](https://arxiv.org/pdf/1903.04717.pdf). Mar 2019. FireEye
- [ShapeShifter: Robust Physical Adversarial Attack on Faster R-CNN Object Detector](https://arxiv.org/pdf/1804.05810.pdf). Sep 2018. Georgia Tech + Intel
- [Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them](https://arxiv.org/pdf/1903.03862.pdf). Mar 2019. Bar-Ilan University + Allen Institute for Artificial Intelligence
- [Improving image classifiers for small datasets by learning rate adaptations](https://arxiv.org/pdf/1903.10726.pdf). Mar 2019. UTokyo + exMedio Inc. Faster (and therefore cheaper) training
- [Reducing the dilution: An analysis of the information sensitiveness of capsule network with a practical solution](https://arxiv.org/pdf/1903.10588.pdf). Mar 2019. hust.edu.cn
- [Self-Supervised Learning via Conditional Motion Propagation](https://arxiv.org/pdf/1903.11412.pdf). Mar 2019. CUHK - SenseTime Joint Lab, Nanyang Technological University
- [Deep Learning based Pedestrian Detection at Distance in Smart Cities](https://arxiv.org/pdf/1812.00876.pdf). Northumbria University + Imam Mohammed ibn Saud Islamic University + Lancaster
- [Hearing your touch: A new acoustic side channel on smartphones](https://arxiv.org/pdf/1903.11137.pdf). Mar 2019. Soundwaves from tapping can be used to determine values being typed 
- [Simple Applications of BERT for Ad Hoc Document Retrieval](https://arxiv.org/pdf/1903.10972.pdf). Mar 2019. University of Waterloo
- [LaserNet: An Efficient Probabilistic 3D Object Detector for Autonomous Driving](https://arxiv.org/pdf/1903.08701.pdf). Mar 2019. Uber ATG
- [All You Need is a Few Shifts: Designing Efficient Convolutional Neural Networks for Image Classification](https://arxiv.org/pdf/1903.05285.pdf). Mar 2019. Hikvision Research Institute
- [[FE-Net] Progressive Sparse Local Attention for Video Object Detection](https://arxiv.org/pdf/1903.09126.pdf). Mar 2019. NLPR,CASIA + Horizon Robotics
- [[OANet] An End-to-End Network for Panoptic Segmentation](https://arxiv.org/pdf/1903.05027.pdf). Mar 2019. Zhejiang University + Megvii Inc. (Face++) + Huazhong University of Science and Technology + Peking University + The University of Tokyo


- [[CapsuleNet] Dynamic Routing Between Capsules](https://arxiv.org/pdf/1710.09829.pdf). Nov 2017. Google Brain. (Hinton)
- [A Multi-Horizon Quantile Recurrent Forecaster](https://arxiv.org/pdf/1711.11053.pdf). June 2018. Amazon Forecasting
- [DFANet: Deep Feature Aggregation for Real-Time Semantic Segmentation](https://arxiv.org/pdf/1904.02216.pdf), April 2019. Megvii. Good speed/accuracy balance
- [Fence GAN: Towards Better Anomaly Detection](https://arxiv.org/pdf/1904.01209.pdf). April 2019. 
- [Distilling Task-Specific Knowledge from BERT into Simple Neural Networks](https://arxiv.org/pdf/1903.12136.pdf). Mar 2019. UWaterloo
- [FVNet: 3D Front-View Proposal Generation for Real-Time Object Detection from Point Clouds](https://arxiv.org/pdf/1903.10750.pdf). Mar 2019. Shanghai Jiao Tong University, Deakin University + Youtu Lab, Tencent
- [Robust Neural Networks using Randomized Adversarial Training](https://arxiv.org/pdf/1903.10219.pdf). Mar 2019. PSL, Universite Paris-Dauphine, Wavestone 3CEA, Universite Paris-Saclay, Facebook AI Research
- [Dynamics of Pedestrian Crossing Decisions Based on Vehicle Trajectories in Large-Scale Simulated and Real-World Data](https://arxiv.org/pdf/1904.04202.pdf). Apr 2019. MIT, Toyota Collaborative Safety Research Center
- [ASAP: Architecture Search, Anneal and Prune](https://arxiv.org/pdf/1904.04123.pdf). Apr 2019. DAMO Academy, Alibaba Group, School of Electrical Engineering, Tel-Aviv University Tel-Aviv, Israel
- [Self-Supervised Learning via Conditional Motion Propagation](https://arxiv.org/pdf/1903.11412.pdf). Apr 2019. CUHK - SenseTime Joint Lab, The Chinese University of Hong Kong, Nanyang Technological University
- [Scalable Deep Learning on Distributed Infrastructures: Challenges, Techniques and Tools](https://arxiv.org/pdf/1903.11314.pdf). Mar 2019. Technical University of Munich, Germany, Technical University of Munich, Germany
- [Training Quantized Network with Auxiliary Gradient Module](https://arxiv.org/pdf/1903.11236.pdf). Mar 2019. The University of Adelaide, Australia, Australian Centre for Robotic Vision, South China University of Technology, China
- [Few-Shot Learning-Based Human Activity Recognition](https://arxiv.org/pdf/1903.10416.pdf). Mar 2019. UMass Amherst
- [ShopSign: a Diverse Scene Text Dataset of Chinese Shop Signs in Street Views](https://arxiv.org/pdf/1903.10412.pdf). Mar 2019. North China University of Water, Henan University, South China University of Technology
- [MetaPruning: Meta Learning for Automatic Neural Network Channel Pruning](https://arxiv.org/pdf/1903.10258.pdf). Apr 2019. Hong Kong University of Science and Technology, Tsinghua University, Megvii Inc (Face++), Huazhong University of Science and Technology
- [Meta Filter Pruning to Accelerate Deep Convolutional Neural Networks](https://arxiv.org/pdf/1904.03961.pdf). Apr 2019. CAI, University of Technology Sydney, JD.com
- [ShapeMask: Learning to Segment Novel Objects by Refining Shape Priors](https://arxiv.org/pdf/1904.03239.pdf). Apr 2019. UC Berkeley, Google Brain
- [High-level Semantic Feature Detection: A New Perspective for Pedestrian Detection](https://arxiv.org/pdf/1904.02948.pdf). Apr 2019. ATR, College of Electronic Science, National University of Defense Technology, Changsha, China, CBSR & NLPR, Institute of Automation, Chinese Academy of Sciences, Beijing, China, Inception Institute of Artificial Intelligence (IIAI), Abu Dhabi, UAE, Horizon Robotics Inc., Beijing ,China
- [FLightNNs: Lightweight Quantized Deep Neural Networks for Fast and Accurate Inference](https://arxiv.org/pdf/1904.02835.pdf). Apr 2019. CMU
- [A Systematic Literature Review about the impact of Artificial Intelligence on Autonomous Vehicle Safety](https://arxiv.org/pdf/1904.02697.pdf). Early 2019. Ericsson, Safety Analysis Group from Polytechnic School of University of São Paulo,
- [UU-Nets Connecting Discriminator and Generator for Image to Image Translation](https://arxiv.org/pdf/1904.02675.pdf). Apr 2019. National University of Singapore
- [On Direct Distribution Matching for Adapting Segmentation Networks](https://arxiv.org/pdf/1904.02657.pdf). Apr 2019. CentraleSupelec-CNRS-Universite Paris Sud, ETS, Montreal Institute for Learning Algorithms (Mila), Universite de Montreal
- [Signal-to-Noise Ratio: A Robust Distance Metric for Deep Metric Learning](https://arxiv.org/pdf/1904.02616.pdf). Apr 2019. Beijing University of Posts and Telecommunications, 2AI Labs (Didi Chuxing), Syracuse University
- [White-to-Black: Efficient Distillation of Black-Box Adversarial Attacks](https://arxiv.org/pdf/1904.02405.pdf). Apr 2019. Tel-Aviv University, Allen Institute for Artificial Intelligence
- [Modeling Vocabulary for Big Code Machine Learning](https://arxiv.org/pdf/1904.01873.pdf). Apr 2019. Free University of Bozen-Bolzano
- [Patchwork: A Patch-wise Attention Network for Efficient Object Detection and Segmentation in Video Streams](https://arxiv.org/pdf/1904.01784.pdf). Apr 2019. Google
- [Boosting segmentation with weak supervision from image-to-image translation](https://arxiv.org/pdf/1904.01636.pdf). Apr 2019. Ecole Polytechnique de Montreal, Mila, NVIDIA
- [Habitat: A Platform for Embodied AI Research](https://arxiv.org/pdf/1904.01201.pdf). Apr 2019. Facebook AI Research, Facebook Reality Labs, Georgia Institute of Technology, Simon Fraser University, Intel Labs, UC Berkeley
- [Res2Net: A New Multi-scale Backbone Architecture](https://arxiv.org/pdf/1904.01169.pdf). Apr 2019. Nankai University, UC Merced, Oxford University
- [Video Object Segmentation using Space-Time Memory Networks](https://arxiv.org/pdf/1904.00607.pdf). Apr 2019. Yonsei University, Adobe Research
- [BENCHMARKING NEURAL NETWORK ROBUSTNESS TO COMMON CORRUPTIONS AND PERTURBATIONS](https://arxiv.org/pdf/1903.12261.pdf). Mar 2019. UC Berkeley, Oregon State University.
- [Large-scale interactive object segmentation with human annotators](https://arxiv.org/pdf/1903.10830.pdf). Mar 2019. Google
- [Reducing BERT Pre-Training Time from 3 Days to 76 Minutes](https://arxiv.org/pdf/1904.00962.pdf). Apr 2019. Googlel UC Berkeley, UCLA
- [SpecAugment: A Simple Data Augmentation Method for Automatic Speech Recognition](https://arxiv.org/pdf/1904.08779.pdf). Apr 2019. Google Brain
- [Image2StyleGAN: How to Embed Images Into the StyleGAN Latent Space?](https://arxiv.org/pdf/1904.03189.pdf). Apr 2019. KAUST
- [DADA: Depth-aware Domain Adaptation in Semantic Segmentation](https://arxiv.org/pdf/1904.01886.pdf). Apr 2019. valeo.ai, Sorbonne University
- [HoloGAN: Unsupervised learning of 3D representations from natural images](https://arxiv.org/pdf/1904.01326.pdf). Apr 2019. University of Bath, Lambda Labs, Twitter
- [Cascade Feature Aggregation for Human Pose Estimation](https://arxiv.org/pdf/1902.07837.pdf). Apr 2019. Ping An Technology
- [Show, Attend and Translate: Unpaired Multi-Domain Image-to-Image Translation with Visual Attention](https://arxiv.org/pdf/1811.07483.pdf). Apr 2019. Shanghai Jiao Tong University
- [Referring to Objects in Videos using Spatio-Temporal Identifying Descriptions](https://arxiv.org/pdf/1904.03885.pdf). Apr 2019. UMaryland
- [TensorMask: A Foundation for Dense Object Segmentation](https://arxiv.org/pdf/1903.12174.pdf). Mar 2019. FAIR
- [T-Net: Parametrizing Fully Convolutional Nets with a Single High-Order Tensor](https://arxiv.org/pdf/1904.02698.pdf). Apr 2019. Samsung AI Center,


- [YOLACT Real-time Instance Segmentation](https://arxiv.org/pdf/1904.02689.pdf). Apr 2019. University of California, Davis
- [Fine-tune BERT for Extractive Summarization](https://arxiv.org/pdf/1903.10318.pdf). Mar 2019. University of Edinburgh
- [Improving image classifiers for small datasets by learning rate adaptations](https://arxiv.org/pdf/1903.10726.pdf). Mar 2019. UTokyo, exMedio Inc


- [FoveaBox: Beyond Anchor-based Object Detector](https://arxiv.org/pdf/1904.03797.pdf). Apr 2019.  Tsinghua University, ByteDance AI Lab, University of Pennsylvania
- [Fast video object segmentation with Spatio-Temporal GANs](https://arxiv.org/pdf/1903.12161.pdf). Mar 2019. ETH Zurich, CSIC-UPC



- [ThunderNet: Towards Real-time Generic Object Detection](https://arxiv.org/pdf/1903.11752.pdf). Mar 2019. National University of Defense Technology, Megvii Inc. (Face++)


- [FCOS: Fully Convolutional One-Stage Object Detection](https://arxiv.org/pdf/1904.01355.pdf). Apr 2019. The University of Adelaide
- [Accurate Monocular 3D Object Detection via Color-Embedded 3D Reconstruction for Autonomous Driving](https://arxiv.org/pdf/1903.11444.pdf). Apr 2019. Dalian University of Technology, The University of Sydney
- [Video Relationship Reasoning using Gated Spatio-Temporal Energy Graph](https://arxiv.org/pdf/1903.10547.pdf). Mar 2019. Carnegie Mellon University, Allen Institute for AI, University of Washington. CVPR 2019?


- [Dense Intrinsic Appearance Flow for Human Pose Transfer](https://arxiv.org/pdf/1903.11326.pdf). Mar 2019. CUHK-SenseTime Joint Lab, The Chinese University of Hong Kong, Robotics Institute, Carnegie Mellon University, Nanyang Technological University



- [DetNAS: Neural Architecture Search on Object Detection](https://arxiv.org/pdf/1903.10979.pdf). Mar 2019. Chinese Academy of Sciences, Megvii Inc
- [Spatiotemporal CNN for Video Object Segmentation](https://arxiv.org/pdf/1904.02363.pdf). Apr 2019. UCAS, JD Digits, CAS
- [FastFCN: Rethinking Dilated Convolution in the Backbone for Semantic Segmentation](https://arxiv.org/pdf/1903.11816.pdf). Mar 2019. Chinese Academy of Sciences, Deepwise AI Lab
- [GS3D: An Efficient 3D Object Detection Framework for Autonomous Driving](https://arxiv.org/pdf/1903.10955.pdf). Mar 2019. The Chinese University of Hong Kong, SenseTime Research, The University of Sydney, Beihang University


- [Adaptive NMS: Refining Pedestrian Detection in a Crowd](https://arxiv.org/pdf/1904.03629.pdf). Apr 2019. Beihang University
- [A CLOSER LOOK AT FEW-SHOT CLASSIFICATION](https://arxiv.org/pdf/1904.04232.pdf). Apr 2019. CMU, GeorgiaTech, National Taiwan University, Virginia Tech. ICLR 2019
- [Relational Action Forecasting](https://arxiv.org/pdf/1904.04231.pdf). Apr 2019. Google Research, UMaryland


- [Exploring Randomly Wired Neural Networks for Image Recognition](https://arxiv.org/pdf/1904.01569.pdf). Apr 2019. FAIR (Ross Girshick, Kaiming He)
- [DPOD: 6D Pose Object Detector and Refiner](https://arxiv.org/pdf/1902.11020.pdf). Apr 2019. Technical University of Munich, Siemens Corporate Technology
- [Memory In Memory: A Predictive Neural Network for Learning Higher-Order Non-Stationarity from Spatiotemporal Dynamics](https://arxiv.org/pdf/1811.07490.pdf). Apr 2019. Tsinghua University
- [Unsupervised learning of action classes with continuous temporal embedding](https://arxiv.org/pdf/1904.04189.pdf). Apr 2019. University of Bonn, MIT-IBM Watson Lab


- [Accelerated Neural Networks on OpenCL Devices Using SYCL-DNN](https://arxiv.org/pdf/1904.04174.pdf). Apr 2019. Codeplay Software 
- [MOTS: Multi-Object Tracking and Segmentation](https://arxiv.org/pdf/1902.03604.pdf). Apr 2019. RWTH Aachen University, MPI for Intelligent Systems and University of Tubingen
- [Learning GAN fingerprints towards Image Attribution](https://arxiv.org/pdf/1811.08180.pdf). University of Maryland, Max Planck Institute for Informatics, CISPA Helmholtz Center for Information Security, Saarland Informatics Campus,
- [Pose2Seg: Detection Free Human Instance Segmentation](https://arxiv.org/pdf/1803.10683.pdf). Apr 2019. Tsinghua University, BNRist, Cardiff University, Tencent AI Lab
- [Weakly Supervised Semantic Segmentation of Satellite Images](https://arxiv.org/pdf/1904.03983.pdf). Apr 2019. Qwant Research
- [Machine Learning for Forecasting Mid Price Movement using Limit Order Book Data](https://arxiv.org/pdf/1809.07861.pdf). Apr 2019. Aristotle University of Thessaloniki, Tampere University of Technology, Aarhus University
- [Kervolutional Neural Networks](https://arxiv.org/pdf/1904.03955.pdf). Apr 2019. Nanyang Technological University, State University of New York at Buffalo
- [A Generative Map for Image-based Camera Localization](https://arxiv.org/pdf/1902.11124.pdf). Apr 2019. fortiss GmbH, Technical University of Munich
- [Generalized Intersection over Union: A Metric and A Loss for Bounding Box Regression](https://arxiv.org/pdf/1902.09630.pdf). Apr 2019. Stanford, The University of Adelaide, Aibee Inc
- [MINI-BATCH SERIALIZATION: CNN TRAINING WITH INTER-LAYER DATA REUSE](https://arxiv.org/pdf/1810.00307.pdf). Apr 2019. The University of Texas at Austin, University of Michigan, Duke University
- [LeanResNet: A Low-cost yet Effective Convolutional Residual Networks](https://arxiv.org/pdf/1904.06952.pdf). Apr 2019. Ben Gurion University, Emory University, University of British Columbia
- [Exploiting Event Log Data-Attributes in RNN Based Prediction](https://arxiv.org/pdf/1904.06895.pdf). Apr 2019. Aalto University, University of Helsinki,  QPR Software, Helsinki Institute for Information Technology 
- [DuBox: No-Prior Box Objection Detection via Residual Dual Scale Detectors](https://arxiv.org/pdf/1904.06883.pdf). Apr 2019. Baidu
- [Reinforcement Learning with Probabilistic Guarantees for Autonomous Driving](https://arxiv.org/pdf/1904.07189.pdf). Apr 2019. Stanford, KTH Royal Institute of Technology, Honda Research Institute
- [Scene-LSTM: A Model for Human Trajectory Prediction](https://arxiv.org/pdf/1808.04018.pdf). Apr 2019. University of Colorado Denver
- [AttoNets: Compact and Efficient Deep Neural Networks for the Edge via Human-Machine Collaborative Design](https://arxiv.org/pdf/1903.07209.pdf). Apr 2019. University of Waterloo, Waterloo Artificial Intelligence Institute, DarwinAI Corp
- [Painting on Placement: Forecasting Routing Congestion using Conditional Generative Adversarial Nets](https://arxiv.org/pdf/1904.07077.pdf). Apr 2019. Cornell
- [MorphNet: Fast & Simple Resource-Constrained Structure Learning of Deep Networks](https://arxiv.org/pdf/1711.06798.pdf). Nov 2018. Google, MIT, GATech

- [MnasNet: Platform-Aware Neural Architecture Search for Mobile](https://arxiv.org/pdf/1807.11626.pdf). July 2018. Google. 
- [QuaterNet: A Quaternion-based Recurrent Model for Human Motion](https://arxiv.org/pdf/1805.06485.pdf). May 2018. École Polytechnique Fédérale de Lausanne, FAIR

- [Dataset Distillation](https://arxiv.org/abs/1811.10959). Nov 2018. FAIR + MIT + UC Berkeley. Compress dataset into few synthetic distilled images. Train on distilled images with close to original performance.
- [Scalable Logo Recognition using Proxies](https://arxiv.org/pdf/1811.08009.pdf). Nov 2018. Amazon

- [LEARNING TO REPRESENT EDITS](https://openreview.net/pdf?id=BJl6AjC5F7). ICLR 2019. CMU + Microsoft


- [IMAGENET-TRAINED CNNS ARE BIASED TOWARDS TEXTURE; INCREASING SHAPE BIAS IMPROVES ACCURACY AND ROBUSTNESS](https://openreview.net/pdf?id=Bygh9j09KX). ICLR 2019. University of Tubingen
- [A CLOSER LOOK AT DEEP LEARNING HEURISTICS: LEARNING RATE RESTARTS, WARMUP AND DISTILLATION](https://openreview.net/pdf?id=r14EOsCqKX). ICLR 2019. Salesforce Research
- [Failing Loudly: An Empirical Study of Methods for Detecting Dataset Shift](https://arxiv.org/pdf/1810.11953.pdf). Jan 2019. Technical University of Munich, CMU


- [Similarity of Neural Network Representations Revisited](https://arxiv.org/pdf/1905.00414.pdf). ICML 2019. May 2019. Google Brain. Geoffrey Hinton.


- [Security for Distributed Deep Neural Networks - Towards Data Confidentiality & Intellectual Property Protection](https://arxiv.org/pdf/1907.04246.pdf). July 2019. SAP, University of Potsdam,  City of Antibes Juan-les-Pins
- [Which Algorithmic Choices Matter at Which Batch Sizes? Insights From a Noisy Quadratic Model](https://arxiv.org/pdf/1907.04164.pdf). Jul 2019. UToronto, Vector Institute, Google Brain, DeepMind
- [Multivariate Time Series Imputation with Variational Autoencoders](https://arxiv.org/pdf/1907.04155.pdf). July 2019. ETH Zurich, UC Irvine


- [The What-If Tool: Interactive Probing of Machine Learning Models](https://arxiv.org/pdf/1907.04135.pdf). July 2019. Google AI. 
- [A Unified Framework of Online Learning Algorithms for Training Recurrent Neural Networks](https://arxiv.org/pdf/1907.02649.pdf). July 2019. NYU.
- [Genetic Network Architecture Search](https://arxiv.org/pdf/1907.02871.pdf). July 2019. Tel Aviv University.

- [The Evolved Transformer](https://arxiv.org/pdf/1901.11117.pdf). May 2019. ICML 2019. Google Brain.
- [Making Study Populations Visible through Knowledge Graphs](https://arxiv.org/pdf/1907.04358.pdf). July 2019. Rensselaer Polytechnic Institute, IBM Research
- [DOB-Net: Actively Rejecting Unknown Excessive Time-Varying Disturbances](https://arxiv.org/pdf/1907.04514.pdf). July 2019. University of Technology, Sydney
- [Two-Stream Adaptive Graph Convolutional Networks for Skeleton-Based Action Recognition](https://arxiv.org/pdf/1805.07694.pdf). July 2019. Chinese Academy of Sciences,
- [MODEL DEVELOPMENT PROCESS](https://arxiv.org/pdf/1907.04461.pdf). July 2019. Warsaw University of Technology & University of Warsaw


- [GluonCV and GluonNLP: Deep Learning in Computer Vision and Natural Language Processing](https://arxiv.org/pdf/1907.04433.pdf). July 2019. UMichigan, Amazon, Hong Kong University of Science and Technology
- [Recipe1M+: A Dataset for Learning Cross-Modal Embeddings for Cooking Recipes and Food Images](https://arxiv.org/pdf/1810.06553.pdf). July 2019. MIT, Qatar Computing Research Institute, Universitat Politecnica de Catalunya
- [M3D-GAN: Multi-Modal Multi-Domain Translation with Universal Attention](https://arxiv.org/pdf/1907.04378.pdf). July 2019. SUNY Buffalo, Microsoft
- [On Designing Machine Learning Models for Malicious Network Traffic Classification](https://arxiv.org/pdf/1907.04846.pdf). July 2019. Northeastern University
- [Sparse Networks from Scratch: Faster Training without Losing Performance](https://arxiv.org/pdf/1907.04840.pdf). July 2019. UWashington
- [BAM! Born-Again Multi-Task Networks for Natural Language Understanding](https://arxiv.org/pdf/1907.04829.pdf). July 2019, Google Brain, Stanford. Quoc V. Le
- [ReQA: An Evaluation for End-to-End Answer Retrieval Models](https://arxiv.org/pdf/1907.04780.pdf). July 2019. Google.
- [Analyzing and learning the language for different types of harassment](https://arxiv.org/pdf/1811.00644.pdf). July 2019. University of Dayton, University of Leipzig, Wright State University
- [SynthCity: A large scale synthetic point cloud](https://arxiv.org/pdf/1907.04758.pdf). July 2019. University College London

- [Material Based Object Tracking in Hyperspectral Videos: Benchmark and Algorithms](https://arxiv.org/pdf/1812.04179.pdf). July 2019. Unknown affiliation
- [Label Aware Graph Convolutional Network Not All Edges Deserve Your Attention](https://arxiv.org/pdf/1907.04707.pdf). July 2019. Unknown affiliation
- [Actions Speak Louder than Goals: Valuing Player Actions in Soccer](https://arxiv.org/pdf/1802.07127.pdf). July 2019. SciSports, KU Leuven
- [Multi-Person tracking by multi-scale detection in Basketball scenarios](https://arxiv.org/pdf/1907.04637.pdf). July 2019. Universitat Pompeu Fabra, FC Barcelona
- [VIDEO ACTION RECOGNITION VIA NEURAL ARCHITECTURE SEARCHING](https://arxiv.org/pdf/1907.04632.pdf). July 2019. University of Oulu, Xi’an Jiaotong University
- [Single-Camera Basketball Tracker through Pose and Semantic Feature Fusion](https://arxiv.org/pdf/1906.02042.pdf). July 2019. Universitat Pompeu Fabra, FC Barcelona
- [Learning to Reason with Relational Video Representation for Question Answering](https://arxiv.org/pdf/1907.04553.pdf). July 2019. Deakin University
- [Multi-layer Attention Mechanism for Speech Keyword Recognition](https://arxiv.org/pdf/1907.04536.pdf). July 2019. Sichuan University, Rutgers University
- [The Role of Cooperation in Responsible AI Development](https://arxiv.org/pdf/1907.04534.pdf). July 2019. OpenAI
- [Software Engineering for Machine Learning: A Case Study](https://www.microsoft.com/en-us/research/uploads/prod/2019/03/amershi-icse-2019_Software_Engineering_for_Machine_Learning.pdf). March 2019. Microsoft
- [SATNet: Bridging deep learning and logical reasoning using a differentiable satisfiability solver](https://arxiv.org/pdf/1905.12149.pdf). May 2019. ICML 2019. CMU, USC, Bosch Center for Artificial Intelligence
- [Generative Adversarial Networks: A Survey and Taxonomy](https://arxiv.org/pdf/1906.01529.pdf). June 2019. Dublin City University, Intel. 
- [Stand-Alone Self-Attention in Vision Models](https://arxiv.org/pdf/1906.05909.pdf). June 2019. Google Brain.


- [Stacked Capsule Autoencoders](https://arxiv.org/pdf/1906.06818.pdf). June 2019. Oxford, Google Brain, DeepMind. Geoffrey Hinton.
- [Practical Deep Learning with Bayesian Principles](https://arxiv.org/pdf/1906.02506.pdf). June 2019. Tokyo Institute of Technology, University of Cambridge, Indian Institute of Technology, University of Osnabrück, RIKEN Center for AI Project
- [Visualizing and Measuring the Geometry of BERT](https://arxiv.org/pdf/1906.02715.pdf). June 2019. Google Research.
- [Butterfly Transform: An Efficient FFT Based Neural Architecture Design](https://arxiv.org/pdf/1906.02256.pdf). June 2019. UWashington, Allen Institute for AI



- [MMDetection: Open MMLab Detection Toolbox and Benchmark](https://arxiv.org/pdf/1906.07155.pdf). June 2019. The Chinese University of Hong Kong, Zhejiang University, The University of Sydney, SenseTime Research, Hong Kong University of Science and Technology, Microsoft Research Asia, Beijing Institute of Technology, Nanjing University, Huazhong University of Science and Technology, Peking University, Sun Yat-sen University, Northeastern University, Nanyang Technological University
- [What Does BERT Look At? An Analysis of BERT’s Attention](https://arxiv.org/pdf/1906.04341.pdf). June 2019. Stanford, FAIR. 
- [Self-Supervised Exploration via Disagreement](https://arxiv.org/pdf/1906.04161.pdf). June 2019. ICML 2019. UC Berkeley, CMU, FAIR
- [Automated Machine Learning: State-of-The-Art and Open Challenges](https://arxiv.org/pdf/1906.02287.pdf). June 2019. University of Tartu, Estonia


- [A Study of BFLOAT16 for Deep Learning Training](https://arxiv.org/pdf/1905.12322.pdf). June 2019. Intel, Facebook


- [Network Deconvolution](https://arxiv.org/pdf/1905.11926.pdf). June 2019. UMaryland. (Remove pixel-wise and channel-wise correlation. Better convergence, no batch norm)


- [[GROVER] Defending Against Neural Fake News](https://arxiv.org/pdf/1905.12616.pdf). May 2019. UWashington, Allen Institute for AI.
- [Deep Semi-Supervised Anomaly Detection](https://arxiv.org/pdf/1906.02694.pdf). June 2019. Technical University of Berlin, Technical University of Kaiserslautern, Singapore University of Technology & Design, b-it Bonn-Aachen, Korea University, Max Planck Institute for Informatics, University of Southern California
- [Deep Reinforcement Learning for Cyber Security](https://arxiv.org/pdf/1906.05799.pdf). June 2019. Deakin University, Harvard


- [Is Attention Interpretable?](https://arxiv.org/pdf/1906.03731.pdf). June 2019. UWashington, Allen Institute for AI.
- [PyRobot: An Open-source Robotics Framework for Research and Benchmarking](https://arxiv.org/pdf/1906.08236.pdf). June 2019. FAIR, CMU
- [Language as an Abstraction for Hierarchical Deep Reinforcement Learning](https://arxiv.org/pdf/1906.07343.pdf). June 2019. Google Research
- [Deep ReLU Networks Have Surprisingly Few Activation Patterns](https://arxiv.org/pdf/1906.00904.pdf). June 2019. FAIR, UPenn
- [Attention Is (not) All You Need for Commonsense Reasoning](https://arxiv.org/pdf/1905.13497.pdf). May 2019. SAP
- [What Kind of Language Is Hard to Language-Model?](https://arxiv.org/pdf/1906.04726.pdf). June 2019. Johns Hopkins University,  City University of New York, Google


- [Does Object Recognition Work for Everyone?](https://arxiv.org/pdf/1906.02659.pdf). June 2019. FAIR.
- [DeepShift: Towards Multiplication-Less Neural Networks](https://arxiv.org/pdf/1905.13298.pdf). June 2019. Huawei (Reduce compute required on mobile devices)
- [GANALYZE: TOWARD VISUAL DEFINITIONS OF COGNITIVE IMAGE PROPERTIES](https://arxiv.org/pdf/1906.10112.pdf). June 2019. MIT
- [From Clustering to Cluster Explanations via Neural Networks](https://arxiv.org/pdf/1906.07633.pdf). June 2019. Berlin Institute of Technology,  Fraunhofer Heinrich Hertz Institute
- [Graph Convolutional Transformer: Learning the Graphical Structure of Electronic Health Records](https://arxiv.org/pdf/1906.04716.pdf). June 2019. Google, DeepMind


- [Four Things Everyone Should Know to Improve Batch Normalization](https://arxiv.org/pdf/1906.03548.pdf). June 2019. University of Auckland
- [Exploiting Uncertainty of Loss Landscape for Stochastic Optimization](https://arxiv.org/pdf/1905.13200.pdf). May 2019. UToronto
- [Graph Normalizing Flows](https://arxiv.org/pdf/1905.13177.pdf). May 2019. UToronto Vector Institute, Google
- [Emergence of Object Segmentation in Perturbed Generative Models](https://arxiv.org/pdf/1905.12663.pdf). May 2019. University of Bern
- [Supervised Learning in Spiking Neural Networks with Phase-Change Memory Synapses](https://arxiv.org/pdf/1905.11929.pdf). May 2019. New Jersey Institute of Technology, IBM Research, Ecole Polytechnique Federale de Lausanne (EPFL).
- [Image-based 3D Object Reconstruction: State-of-the-Art and Trends in the Deep Learning Era](https://arxiv.org/pdf/1906.06543.pdf). June 2019. Tianjin University,  University of Western Australia, Murdoch University, University of South Australia
- [A Survey on Deep Learning Architectures for Image-based Depth Reconstruction](https://arxiv.org/pdf/1906.06113.pdf). June 2019. Murdoch University


- [Grid R-CNN Plus: Faster and Better](https://arxiv.org/pdf/1906.05688.pdf). June 2019. SenseTime, CUHK, Beihang University.


- [GluonTS: Probabilistic Time Series Models in Python](https://arxiv.org/pdf/1906.05264.pdf). June 2019. AWS


- [NAS-FCOS: Fast Neural Architecture Search for Object Detection](https://arxiv.org/pdf/1906.04423.pdf). June 2019. Northwestern Polytechnical University, China, The University of Adelaide
- [Analyzing the Structure of Attention in a Transformer Language Model](https://arxiv.org/pdf/1906.04284.pdf). June 2019. PARC, MIT CSAIL
- [DiCENet: Dimension-wise Convolutions for Efficient Networks](https://arxiv.org/pdf/1906.03516.pdf). June 2019. UWashington, Allen Institute for AI (AI2).


- [Bad Global Minima Exist and SGD Can Reach Them](https://arxiv.org/pdf/1906.02613.pdf). June 2019. University of Wisconsin–Madison, University of California Santa Cruz


- [The Secrets of Machine Learning: Ten Things You Wish You Had Known Earlier to be More Effective at Data Analysis](https://arxiv.org/pdf/1906.01998.pdf). June 2019. Duke University


- [Text-based Editing of Talking-head Video](https://arxiv.org/pdf/1906.01524.pdf). June 2019. Stanford, Max Planck Institute for Informatics, Princeton, Adobe. 
- [Learning to solve the credit assignment problem](https://arxiv.org/pdf/1906.00889.pdf). June 2019. UPenn
- [Fashion Editing with Multi-scale Attention Normalization](https://arxiv.org/pdf/1906.00884.pdf). June 2019. Sun Yat-sen University, Petuum Inc, ByteDance AI Lab
- [Time Series Anomaly Detection Using Convolutional Neural Networks and Transfer Learning](https://arxiv.org/pdf/1905.13628.pdf). May 2019. Arundo Analytics
- [A Lightweight Recurrent Network for Sequence Modeling](https://arxiv.org/pdf/1905.13324.pdf). May 2019. University of Edinburgh, University of Zurich
- [Graph Neural Tangent Kernel: Fusing Graph Neural Networks with Graph Kernels](https://arxiv.org/pdf/1905.13192.pdf). May 2019. CMU, Zhejiang University, MIT.
- [Learning Navigation Subroutines by Watching Videos](https://arxiv.org/pdf/1905.12612.pdf). May 2019. UC Berkeley, FAIR, UIUC
- [Unsupervised Learning from Video with Deep Neural Embeddings](https://arxiv.org/pdf/1905.11954.pdf). May 2019. Sanford, MIT. "We show that VIE-trained networks substantially advance the state of the art in unsupervised learning from video datastreams, both for action recognition in the Kinetics dataset, and object recognition in the ImageNet dataset."
- [Show, Match and Segment: Joint Learning of Semantic Matching and Object Co-segmentation](https://arxiv.org/pdf/1906.05857.pdf). June 2019. Academia Sinica, University of California, Merced, VA Tech


- [CVPR19 Tracking and Detection Challenge: How crowded can it get?](https://arxiv.org/pdf/1906.04567.pdf). June 2019. TUM Munich, University of Adelaide, ETH Zurich
- [Distilling Object Detectors with Fine-grained Feature Imitation](https://arxiv.org/pdf/1906.03609.pdf). June 2019. National University of Singapore, Huawei Noah’s Ark Lab


- [Detecting Kissing Scenes in a Database of Hollywood Films](https://arxiv.org/pdf/1906.01843.pdf). June 2019. Stanford
- [Efficient 8-Bit Quantization of Transformer Neural Machine Language Translation Model](https://arxiv.org/pdf/1906.00532.pdf). June 2019. ICML 2019. Intel.
- [Dimensionality compression and expansion in Deep Neural Networks](https://arxiv.org/pdf/1906.00443.pdf). June 2019. UWashington, Harvard, Université de Montréal
- [Data Augmentation for Object Detection via Progressive and Selective Instance-Switching](https://arxiv.org/pdf/1906.00358.pdf). June 2019. Harbin Institute of Technology, China, Tianjin University, China



- [Explainability Techniques for Graph Convolutional Networks](https://arxiv.org/pdf/1905.13686.pdf). May 2019. ICML 2019.  KTH (Royal Institute of Technology), Stockholm, Sweden
- [Hierarchical Transformers for Multi-Document Summarization](https://arxiv.org/pdf/1905.13164.pdf). May 2019. University of Edinburgh
- [CMRNet: Camera to LiDAR-Map Registration](https://arxiv.org/pdf/1906.10109.pdf). June 2019. Universita degli Studi di Milano, Albert-Ludwigs-Universitat Freiburg
- [Modeling AGI Safety Frameworks with Causal Influence Diagrams](https://arxiv.org/pdf/1906.08663.pdf). June 2019. DeepMind
- [Submodular Batch Selection for Training Deep Neural Networks](https://arxiv.org/pdf/1906.08771.pdf). June 2019. Indian Institute of Technology Hyderabad


- [Cascade R-CNN: High Quality Object Detection and Instance Segmentation](https://arxiv.org/pdf/1906.09756.pdf). June 2019. UC San Diego. Improvements to Cascade R-CNN for segmentation + Implementations
- [A Tensorized Transformer for Language Modeling](https://arxiv.org/pdf/1906.09777.pdf). June 2019. Tianjin University, Microsoft Research Asia,  Beijing Institute of Technology
- [SkyNet: A Champion Model for DAC-SDC on Low Power Object Detection](https://arxiv.org/pdf/1906.10327.pdf). June 2019. Univ. of Illinois at Urbana-Champaign, IBM T. J. Watson Research Center, Inspirit IoT. Extremely light-weight (1.82 MB of params)
- [Lifelong Learning Starting From Zero](https://arxiv.org/pdf/1906.09852.pdf). June 2019. Chalmers University of Technology, Dynamic Topologies Sweden AB. "We present a deep neural-network model for lifelong learning inspired by several forms of neuroplasticity."
- [A computational model of early language acquisition from audiovisual experiences of young infants ](https://arxiv.org/pdf/1906.09832.pdf). June 2019. Tampere University, Finland, Aalto University, Finland.


- [ESNet: An Efficient Symmetric Network for Real-time Semantic Segmentation](https://arxiv.org/pdf/1906.09826.pdf). June 2019. National Engineering Research Center of Communications and Networking, Nanjing, University of Posts and Telecommunications, Nanjing. "state-of-the-art results in terms of speed and accuracy trade-off for realtime semantic segmentation on CityScapes dataset."
- [Emotionally-Aware Chatbots: A Survey](https://arxiv.org/pdf/1906.09774.pdf). June 2019. University of Turin


- [XLNet: Generalized Autoregressive Pretraining for Language Understanding](https://arxiv.org/pdf/1906.08237.pdf). June 2019. CMU, Google Brain. Quoc V. Le


- [EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks](https://arxiv.org/pdf/1905.11946.pdf). June 2019. ICML 2019. Google Brain. Quoc V. Le
- [Follow the Attention: Combining Partial Pose and Object Motion for Fine-Grained Action Detection](https://arxiv.org/pdf/1905.04430.pdf). June 2019.  The University of Adelaide


- [Gradient Noise Convolution (GNC): Smoothing Loss Function for Distributed Large-Batch SGD](https://arxiv.org/pdf/1906.10822.pdf). June 2019. Toshiba, The University of Tokyo, RIKEN
- [A Framework for Evaluating Agricultural Ontologies](https://arxiv.org/pdf/1906.10450.pdf). May 2019. Tel-Aviv University, Ben Gurion University of the Negev
- [SwiftNet: Using Graph Propagation as Meta-knowledge to Search Highly Representative Neural Architectures](https://arxiv.org/pdf/1906.08305.pdf). June 2019. Duke, Qualcomm AI Research, University of Nevada
- [Norm-Preservation: Why Residual Networks Can Become Extremely Deep?](https://arxiv.org/pdf/1805.07477.pdf). June 2019. UCF
- [Entropy-based Dynamic Time Warping Similarity Measures for Financial Time Series Analysis](https://arxiv.org/pdf/1902.09947.pdf). June 2019. Central University of Finance and Economics, Beijing, Southern University of Science and Technology, Guangzhou, Hefei University, University of York.
- [Active Learning Solution on Distributed Edge Computing](https://arxiv.org/pdf/1906.10718.pdf). June 2019. Technical University of Denmark.
- [Learning Fair and Transferable Representations](https://arxiv.org/pdf/1906.10673.pdf). June 2019. Universitá di Pisa, AWS, Istituto Italiano di Tecnologia, UCL
- [On Multi-Agent Learning in Team Sports Games](https://arxiv.org/pdf/1906.10124.pdf). June 2019. ICML 2019. EA Sports
- [Age and gender bias in pedestrian detection algorithms](https://arxiv.org/pdf/1906.10490.pdf). June 2019. Oxford
- [The PhotoBook Dataset: Building Common Ground through Visually-Grounded Dialogue](https://arxiv.org/pdf/1906.01530.pdf). June 2019. University of Amsterdam, Tilburg University
- [Canonicalizing Knowledge Base Literals](https://arxiv.org/pdf/1906.11180.pdf). June 2019. Oxford, The Alan Turing Institute, University of Oslo


- [Learning Data Augmentation Strategies for Object Detection](https://arxiv.org/pdf/1906.11172.pdf). June 2019. Google Brain
- [On the Coherence of Fake News Articles](https://arxiv.org/pdf/1906.11126.pdf). June 2019. University Institute of Engineering and Technology, Chandigarh, India, Queen’s University Belfast, University of Calicut.
- [Instance Segmentation by Jointly Optimizing Spatial Embeddings and Clustering Bandwidth](https://arxiv.org/pdf/1906.11109.pdf). June 2019. KU Leuven.
- [Privacy Preserving QoE Modeling using Collaborative Learning](https://arxiv.org/pdf/1906.09248.pdf). June 2019. Ericsson Research, Blekinge Inst. of Tech.
- [Sharing Attention Weights for Fast Transformer](https://arxiv.org/pdf/1906.11024.pdf). June 2019. Northeastern University, Shenyang, China, NiuTrans Co., Kunming University of Science and Technology, CAS, Beijing.
- [GAN-Knowledge Distillation for one-stage Object Detection](https://arxiv.org/pdf/1906.08467.pdf). June 2019. Startdt AI Lab, Zeusee Technology.
- [End-to-End 3D-PointCloud Semantic Segmentation for Autonomous Driving](https://arxiv.org/pdf/1906.10964.pdf). June 2019. Valeo
- [Autonomous Exploration, Reconstruction, and Surveillance of 3D Environments Aided by Deep Learning](https://arxiv.org/pdf/1809.06025.pdf). June 2019. UT Austin
- [Does Learning Require Memorization? A Short Tale about a Long Tail](https://arxiv.org/pdf/1906.05271.pdf). June 2019. Google Brain.
- [BAYHENN: Combining Bayesian Deep Learning and Homomorphic Encryption for Secure DNN Inference](https://arxiv.org/pdf/1906.00639.pdf). June 2019. Peking University, Ant Financial Services Group
- [Small Data Challenges in Big Data Era: A Survey of Recent Progress on Unsupervised and Semi-Supervised Methods](https://arxiv.org/pdf/1903.11260.pdf). March 2019. Laboratory for MAchine Perception and LEarning (MAPLE lab), Huawei Cloud, University of Rochester.
- [DFANet: Deep Feature Aggregation for Real-Time Semantic Segmentation](https://arxiv.org/pdf/1904.02216.pdf). Apr 2019. Megvii. "Experiments on Cityscapes and CamVid datasets demonstrate the superior performance of DFANet with 8× less FLOPs and 2× faster than the existing state-of-the-art real-time semantic segmentation methods while providing comparable accuracy"
- [Fence GAN: Towards Better Anomaly Detection](https://arxiv.org/pdf/1904.01209.pdf). Apr 2019. Hwa Chong Institution. Bioinformatics Institute, Agency for Science, Technology and Research (A*STAR), National University of Singapore.
- [Distilling Task-Specific Knowledge from BERT into Simple Neural Networks](https://arxiv.org/pdf/1903.12136.pdf). Mar 2019. UWaterloo
- [FVNet: 3D Front-View Proposal Generation for Real-Time Object Detection from Point Clouds](https://arxiv.org/pdf/1903.10750.pdf). Mar 2019. Shanghai Jiao Tong University, Deakin University, Youtu Lab [Tencent]
- [Robust Neural Networks using Randomized Adversarial Training](https://arxiv.org/pdf/1903.10219.pdf). Mar 2019. Universite Paris-Dauphine, Waveston, Universite Paris-Saclay, Facebook AI Research
- [ASAP: Architecture Search, Anneal and Prune](https://arxiv.org/pdf/1904.04123.pdf). Apr 2019. Alibaba, Tel-Aviv University


- [Pyramid Mask Text Detector](https://arxiv.org/pdf/1903.11800.pdf). Mar 2019. SenseTime, CUHK, Beihang University
- [Self-Supervised Learning via Conditional Motion Propagation](https://arxiv.org/pdf/1903.11412.pdf). Apr 2019. CUHK-SenseTime Joint Lab, Nanyang Technological University.
- [Scalable Deep Learning on Distributed Infrastructures: Challenges, Techniques and Tools](https://arxiv.org/pdf/1903.11314.pdf). Mar 2019. Technical University Munich (TUM)
- [Training Quantized Network with Auxiliary Gradient Module](https://arxiv.org/pdf/1903.11236.pdf). Mar 2019. The University of Adelaide, Australian Centre for Robotic Vision, South China University of Technology 
- [Few-Shot Learning-Based Human Activity Recognition](https://arxiv.org/pdf/1903.10416.pdf). Mar 2019. University of Massachusetts Amherst
- [ShopSign: a Diverse Scene Text Dataset of Chinese Shop Signs in Street Views](https://arxiv.org/pdf/1903.10412.pdf). Mar 2019. Henan University, North China University of Water, South China University of Technology
- [MetaPruning: Meta Learning for Automatic Neural Network Channel Pruning](https://arxiv.org/pdf/1903.10258.pdf). Apr 2019. Hong Kong University of Science and Technology, Tsinghua University, Megvii Inc (Face++), Huazhong University of Science and Technology
- [Meta Filter Pruning to Accelerate Deep Convolutional Neural Networks](https://arxiv.org/pdf/1904.03961.pdf). Apr 2019. University of Technology Sydney, JD.com
- [ShapeMask: Learning to Segment Novel Objects by Refining Shape Priors](https://arxiv.org/pdf/1904.03239.pdf). Apr 2019. Google Brain, UC Berkeley
- [High-level Semantic Feature Detection: A New Perspective for Pedestrian Detection](https://arxiv.org/pdf/1904.02948.pdf). Apr 2019. National University of Defense Technology (Changsha, China), Chinese Academy of Sciences, Inception Institute of Artificial Intelligence (IIAI, Abu Dhabi, UAE), Horizon Robotics Inc. (Beijing, China)
- [FLightNNs: Lightweight Quantized Deep Neural Networks for Fast and Accurate Inference](https://arxiv.org/pdf/1904.02835.pdf). Apr 2019. CMU
- [A Systematic Literature Review about the impact of Artificial Intelligence on Autonomous Vehicle Safety](https://arxiv.org/pdf/1904.02697.pdf). Apr 2019.  Polytechnic School of University of São Paulo, Ericsson
- [UU-Nets Connecting Discriminator and Generator for Image to Image Translation](https://arxiv.org/pdf/1904.02675.pdf). Apr 2019. National University of Singapore.
- [On Direct Distribution Matching for Adapting Segmentation Networks](https://arxiv.org/pdf/1904.02657.pdf). Apr 2019. CentraleSupelec-CNRS-Universite Paris Sud, ETS (Canada), Universite de Montreal 
- [Signal-to-Noise Ratio: A Robust Distance Metric for Deep Metric Learning](https://arxiv.org/pdf/1904.02616.pdf). Apr 2019. Beijing University of Posts and Telecommunications, Didi Chuxing, Syracuse University
- [White-to-Black: Efficient Distillation of Black-Box Adversarial Attacks](https://arxiv.org/pdf/1904.02405.pdf). Apr 2019. Tel-Aviv University, AI2
- [Modeling Vocabulary for Big Code Machine Learning](https://arxiv.org/pdf/1904.01873.pdf). Apr 2019. Free University of Bozen-Bolzano
- [Patchwork: A Patch-wise Attention Network for Efficient Object Detection and Segmentation in Video Streams](https://arxiv.org/pdf/1904.01784.pdf). Apr 2019. Google.
- [Boosting segmentation with weak supervision from image-to-image translation](https://arxiv.org/pdf/1904.01636.pdf). Apr 2019.Ecole Polytechnique de Montreal, Mila, NVIDIA
- [Habitat: A Platform for Embodied AI Research](https://arxiv.org/pdf/1904.01201.pdf). Apr 2019. Facebook AI Research, Facebook Reality Labs, Georgia Institute of Technology, Simon Fraser University, Intel, UC Berkeley 
- [Res2Net: A New Multi-scale Backbone Architecture](https://arxiv.org/pdf/1904.01169.pdf). Apr 2019. Nankai University, UC Merced, Oxford
- [Video Object Segmentation using Space-Time Memory Networks](https://arxiv.org/pdf/1904.00607.pdf). Apr 2019. Yonsei University, Adobe Research
- [BENCHMARKING NEURAL NETWORK ROBUSTNESS TO COMMON CORRUPTIONS AND PERTURBATIONS](https://arxiv.org/pdf/1903.12261.pdf). Mar 2019. Oregon State University, UC Berkeley.
- [Large-scale interactive object segmentation with human annotators](https://arxiv.org/pdf/1903.10830.pdf). Mar 2019. Google. 
- [Reducing BERT Pre-Training Time from 3 Days to 76 Minutes](https://arxiv.org/pdf/1904.00962.pdf). Apr 2019. Google, UC Berkeley, UCLA
- [SpecAugment: A Simple Data Augmentation Method for Automatic Speech Recognition](https://arxiv.org/pdf/1904.08779.pdf). Apr 2019. Google Brain. Quoc V. Le
- [Image2StyleGAN: How to Embed Images Into the StyleGAN Latent Space?](https://arxiv.org/pdf/1904.03189.pdf). Apr 2019. KAUST
- [DADA: Depth-aware Domain Adaptation in Semantic Segmentation](https://arxiv.org/pdf/1904.01886.pdf). Apr 2019. Valeo, Sorbonne University. 
- [HoloGAN: Unsupervised learning of 3D representations from natural images](https://arxiv.org/pdf/1904.01326.pdf). Apr 2019.  University of Bath, Lambda Labs, Twitter
- [Cascade Feature Aggregation for Human Pose Estimation](https://arxiv.org/pdf/1902.07837.pdf). Apr 2019. Ping An Technology (Shenzhen) Co
- [Show, Attend and Translate: Unpaired Multi-Domain Image-to-Image Translation with Visual Attention](https://arxiv.org/pdf/1811.07483.pdf). Apr 2019. Shanghai Jiao Tong University
- [Referring to Objects in Videos using Spatio-Temporal Identifying Descriptions](https://arxiv.org/pdf/1904.03885.pdf). Apr 2019. UMaryland.
- [TensorMask: A Foundation for Dense Object Segmentation](https://arxiv.org/pdf/1903.12174.pdf). Mar 2019. FAIR. Xinlei Chen + Ross Girshick + Kaiming He + Piotr Dollar
- [Libra R-CNN: Towards Balanced Learning for Object Detection](https://arxiv.org/pdf/1904.02701.pdf). Apr 2019. Zhejiang University CUHK, SenseTime Research, The University of Sydney. Code available.
- [T-Net: Parametrizing Fully Convolutional Nets with a Single High-Order Tensor](https://arxiv.org/pdf/1904.02698.pdf). Apr 2019. Samsung
- [YOLACT Real-time Instance Segmentation](https://arxiv.org/pdf/1904.02689.pdf). Apr 2019. UC Davis
- [Fine-tune BERT for Extractive Summarization](https://arxiv.org/pdf/1903.10318.pdf). Mar 2019. University of Edinburgh
- [Improving image classifiers for small datasets by learning rate adaptations](https://arxiv.org/pdf/1903.10726.pdf). Mar 2019. University of Tokyo, exMedio Inc.
- [FoveaBox: Beyond Anchor-based Object Detector](https://arxiv.org/pdf/1904.03797.pdf). Apr 2019. Tsinghua University, ByteDance, UPenn
- [Fast video object segmentation with Spatio-Temporal GANs](https://arxiv.org/pdf/1903.12161.pdf). Mar 2019. ETH Zurich, CSIC-UPC
- [ThunderNet: Towards Real-time Generic Object Detection](https://arxiv.org/pdf/1903.11752.pdf). Mar 2019. National University of Defense Technology, Megvii Inc. (Face++)
- [FCOS: Fully Convolutional One-Stage Object Detection](https://arxiv.org/pdf/1904.01355.pdf). Apr 2019. The University of Adelaide
- [Video Relationship Reasoning using Gated Spatio-Temporal Energy Graph](https://arxiv.org/pdf/1903.10547.pdf). Mar 2019. Carnegie Mellon University, AI2, University of Washington
- [Dense Intrinsic Appearance Flow for Human Pose Transfer](https://arxiv.org/pdf/1903.11326.pdf). Mar 2019. CUHK-SenseTime Joint Lab, CMU, Nanyang Technological University
- [DetNAS: Neural Architecture Search on Object Detection](https://arxiv.org/pdf/1903.10979.pdf). Mar 2019. Chinese Academy of Sciences, Megvii Inc
- [Spatiotemporal CNN for Video Object Segmentation](https://arxiv.org/pdf/1904.02363.pdf). Apr 2019. UCAS, JD Digits, CAS
- [FastFCN: Rethinking Dilated Convolution in the Backbone for Semantic Segmentation](https://arxiv.org/pdf/1903.11816.pdf). Mar 2019.  Chinese Academy of Sciences, Deepwise AI Lab.
- [GS3D: An Efficient 3D Object Detection Framework for Autonomous Driving](https://arxiv.org/pdf/1903.10955.pdf). Mar 2019. CUHK, SenseTime Research, The University of Sydney, Beihang University
- [Adaptive NMS: Refining Pedestrian Detection in a Crowd](https://arxiv.org/pdf/1904.03629.pdf). Apr 2019. Beihang University
- [A CLOSER LOOK AT FEW-SHOT CLASSIFICATION](https://arxiv.org/pdf/1904.04232.pdf). Apr 2019. ICLR 2019. CMU, GATech, VATech, National Taiwan University
- [Relational Action Forecasting](https://arxiv.org/pdf/1904.04231.pdf). Apr 2019. Google, UMaryland
- [Exploring Randomly Wired Neural Networks for Image Recognition](https://arxiv.org/pdf/1904.01569.pdf). Apr 2019. FAIR. Saining Xie + Alexander Kirillov + Ross Girshick + Kaiming He
- [DPOD: 6D Pose Object Detector and Refiner](https://arxiv.org/pdf/1902.11020.pdf). Apr 2019. TUM, Siemens Corporate Technology
- [Memory In Memory: A Predictive Neural Network for Learning Higher-Order Non-Stationarity from Spatiotemporal Dynamics](https://arxiv.org/pdf/1811.07490.pdf). Apr 2019. Tsinghua University.
- [Unsupervised learning of action classes with continuous temporal embedding](https://arxiv.org/pdf/1904.04189.pdf). University of Bonn, MIT-IMB Watson Lab
- [Accelerated Neural Networks on OpenCL Devices Using SYCL-DNN](https://arxiv.org/pdf/1904.04174.pdf). IWOCL 19, Codeplay Software
- [MOTS: Multi-Object Tracking and Segmentation](https://arxiv.org/pdf/1902.03604.pdf). Apr 2019. RWTH Aachen University, MPI for Intelligent Systems and University of Tubingen
- [Learning GAN fingerprints towards Image Attribution](https://arxiv.org/pdf/1811.08180.pdf). Apr 2019. UMaryland, Max Planck Institute for Informatics, CISPA Helmholtz Center for Information Security
- [Pose2Seg: Detection Free Human Instance Segmentation](https://arxiv.org/pdf/1803.10683.pdf). Apr 2019. Tsinghua University, BNRist, Cardiff University, Tencent AI Lab
- [Weakly Supervised Semantic Segmentation of Satellite Images](https://arxiv.org/pdf/1904.03983.pdf). Apr 2019. Qwant Research
- [Machine Learning for Forecasting Mid Price Movement using Limit Order Book Data](https://arxiv.org/pdf/1809.07861.pdf). Apr 2019. Aristotle University of Thessaloniki, Tampere University of Technology, Aarhus University
- [Kervolutional Neural Networks](https://arxiv.org/pdf/1904.03955.pdf). Apr 2019. Nanyang Technological University, SUNY Buffalo
- [A Generative Map for Image-based Camera Localization](https://arxiv.org/pdf/1902.11124.pdf). Apr 2019. fortiss GmbH, TUM
- [Generalized Intersection over Union: A Metric and A Loss for Bounding Box Regression](https://arxiv.org/pdf/1902.09630.pdf). Apr 2019. Stanford, The University of Adelaide, Aibee Inc
- [MINI-BATCH SERIALIZATION: CNN TRAINING WITH INTER-LAYER DATA REUSE](https://arxiv.org/pdf/1810.00307.pdf). Apr 2019. SysML 2019. UT Austin, UMich, Duke.
- [LeanResNet: A Low-cost yet Effective Convolutional Residual Networks](https://arxiv.org/pdf/1904.06952.pdf). Apr 2019. Ben Gurion University, Emory University, University of British Columbia
- [Human-Guided Learning of Column Networks: Augmenting Deep Learning with Advice](https://arxiv.org/pdf/1904.06950.pdf). Apr 2019. UT Dallas
- [Exploiting Event Log Data-Attributes in RNN Based Prediction](https://arxiv.org/pdf/1904.06895.pdf). Apr 2019. Aalto University, University of Helsinki, QPR Software, HIIT Helsinki Institute for Information Technology
- [DuBox: No-Prior Box Objection Detection via Residual Dual Scale Detectors](https://arxiv.org/pdf/1904.06883.pdf). Apr 2019. Baidu.
- [Improving interactive reinforcement learning: What makes a good teacher?](https://arxiv.org/pdf/1904.06879.pdf). Apr 2019. University of Hamburg, Universidad Central de Chile, Osaka University
- [Optimized Skeleton-based Action Recognition via Sparsified Graph Regression](https://arxiv.org/pdf/1811.12013.pdf). Apr 2019. Peking University
- [Reinforcement Learning with Probabilistic Guarantees for Autonomous Driving](https://arxiv.org/pdf/1904.07189.pdf). Apr 2019. Stanford, KTH Royal Institute of Technology, Honda Research Institute.
- [Scene-LSTM: A Model for Human Trajectory Prediction](https://arxiv.org/pdf/1808.04018.pdf). Apr 2019. University of Colorado Denver
- [AttoNets: Compact and Efficient Deep Neural Networks for the Edge via Human-Machine Collaborative Design](https://arxiv.org/pdf/1903.07209.pdf). Apr 2019. UWaterloo, Waterloo Artificial Intelligence Institute, DarwinAI Corp.
- [Painting on Placement: Forecasting Routing Congestion using Conditional Generative Adversarial Nets](https://arxiv.org/pdf/1904.07077.pdf). Apr 2019. Cornell.
- [From Bilingual to Multilingual Neural Machine Translation by Incremental Training](https://arxiv.org/pdf/1907.00735.pdf). July 2019. Universitat Politecnica de Catalunya
- [Meet Up! A Corpus of Joint Activity Dialogues in a Visual Environment](https://arxiv.org/pdf/1907.05084.pdf). July 2019. University of Potsdam, Bielefeld University
- [A Two-Stage Method for Text Line Detection in Historical Documents](https://arxiv.org/pdf/1802.03345.pdf). July 2019. University of Rostock
- [Wasserstein-Fisher-Rao Document Distance](https://arxiv.org/pdf/1904.10294.pdf). July 2019. Tsinghua University
- [BlazeFace: Sub-millisecond Neural Face Detection on Mobile GPUs](https://arxiv.org/pdf/1907.05047.pdf). July 2019. Google Research
- [Making AI Forget You: Data Deletion in Machine Learning](https://arxiv.org/pdf/1907.05012.pdf). July 2019. Stanford.
- [Semi-supervised Feature-Level Attribute Manipulation for Fashion Image Retrieval](https://arxiv.org/pdf/1907.05007.pdf), July 2019. Search Solutions Inc. (Korea),  Naver Corp. (Korea)
- [Two-stream Spatiotemporal Feature for Video QA Task](https://arxiv.org/pdf/1907.05006.pdf). July 2019. Unknown affiliation
- [Object Detection in Video with Spatial-temporal Context Aggregation](https://arxiv.org/pdf/1907.04988.pdf). July 2019. Huazhong University of Science and Technology, Horizon Robotics
- [SocialGCN: An Efficient Graph Convolutional Network based Model for Social Recommendation](https://arxiv.org/pdf/1811.02815.pdf). July 2019. Hefei University of Technology, Missouri University of Science and Technology, Microsoft Research Asia.
- [GraphSAINT: Graph Sampling Based Inductive Learning Method](https://arxiv.org/pdf/1907.04931.pdf). July 2019. USC, US Army Research Lab-West
- [Massively Multilingual Neural Machine Translation in the Wild: Findings and Challenges](https://arxiv.org/pdf/1907.05019.pdf). July 2019. Google AI
- [Privileged Features Distillation for E-Commerce Recommendations](https://arxiv.org/pdf/1907.05171.pdf). July 2019. Alibaba
- [Time2Vec: Learning a Vector Representation of Time](https://arxiv.org/pdf/1907.05321.pdf). July 2019. Borealis AI
- [Language Modeling with Deep Transformers](https://arxiv.org/pdf/1905.04226.pdf). July 2019. RWTH Aachen University, AppTek GmbH
- [On-field player workload exposure and knee injury risk monitoring via deep learning](https://arxiv.org/pdf/1809.08016.pdf). July 2019. The University of Western Australia, Griffith University, Auckland University of Technology
- [Weakly Supervised Person Re-ID: Differentiable Graphical Learning and A New Benchmark](https://arxiv.org/pdf/1904.03845.pdf). July 2019. Sun Yat-sen University, Guangzhou.
- [Learning to learn with quantum neural networks via classical neural networks](https://arxiv.org/pdf/1907.05415.pdf). July 2019. Google, University of Waterloo, UMich.
- [Incrementalizing RASA’s Open-Source Natural Language Understanding Pipeline](https://arxiv.org/pdf/1907.05403.pdf). July 2019. Boise State University.
- [Performance Boundary Identification for the Evaluation of Automated Vehicles using Gaussian Process Classification](https://arxiv.org/pdf/1907.05364.pdf). July 2019. Coventry University
- [Adversarial Objects Against LiDAR-Based Autonomous Driving Systems](https://arxiv.org/pdf/1907.05418.pdf). July 2019. UMich, Baidu, University of Illinois at Urbana-Champaign
- [Double-Head RCNN: Rethinking Classification and Localization for Object Detection](https://arxiv.org/pdf/1904.06493.pdf). May 2019. Northeastern University, Microsoft
- [Modern Deep Reinforcement Learning Algorithms](https://arxiv.org/pdf/1906.10025.pdf). June 2019. Closer to short textbook than paper.
- [Encoding Database Schemas with Relation-Aware Self-Attention for Text-to-SQL Parsers](https://arxiv.org/pdf/1906.11790.pdf). June 2019. UC Berkeley
- [Stolen Memories: Leveraging Model Memorization for Calibrated White-Box Membership Inference](https://arxiv.org/pdf/1906.11798.pdf). June 2019. CMU
- [Fast Training of Sparse Graph Neural Networks on Dense Hardware](https://arxiv.org/pdf/1906.11786.pdf). June 2019. University of Cambridge, MPI Tübingen, Google Brain, DeepMind
- [VideoBERT: A Joint Model for Video and Language Representation Learning](https://arxiv.org/pdf/1904.01766.pdf). Apr 2019. Google
- [DEEP MULTI-SCALE VIDEO PREDICTION BEYOND MEAN SQUARE ERROR](https://arxiv.org/pdf/1511.05440.pdf). Nov 2015. ICLR 2016. NYU, FAIR. Yann LeCun
- [Zoom to Learn, Learn to Zoom](https://arxiv.org/pdf/1905.05169.pdf). May 2019. UC Berkeley, HKUST, Intel Labs
- [Graph Convolutional Gaussian Processes](https://arxiv.org/pdf/1905.05739.pdf). May 2019. Imperial College London. ICML 2019.
- [Learnable Triangulation of Human Pose](https://arxiv.org/pdf/1905.05754.pdf). May 2019. Samsung Moscow, Skolkovo Institute of Science and Technology (Moscow).
- [How to Fine-Tune BERT for Text Classification?](https://arxiv.org/pdf/1905.05583.pdf). May 2019. Fudan University (Shanghai)
- [Graph U-Nets](https://arxiv.org/pdf/1905.05178.pdf). May 2019. Texas A&M. ICML 2019.
- [BayesNAS: A Bayesian Approach for Neural Architecture Search](https://arxiv.org/pdf/1905.04919.pdf). May 2019. ICML 2019. Delft University of Technology (Netherlands), University College London
- [Video Instance Segmentation](https://arxiv.org/pdf/1905.04804.pdf). May 2019. ByteDance, UIUC, Adobe. Introduces "a new computer vision task, named video instance segmentation" with a YouTube-based benchmark and "a novel algorithm called MaskTrack R-CNN for this task"
- [Learning What and Where to Transfer](https://arxiv.org/pdf/1905.05901.pdf). May 2019. KAIST. ICML 2019.
- [VideoGraph: Recognizing Minutes-Long Human Activities in Videos](https://arxiv.org/pdf/1905.05143.pdf). May 2019. University of Amsterdam
- [Understanding and Utilizing Deep Neural Networks Trained with Noisy Labels](https://arxiv.org/pdf/1905.05040.pdf). May 2019. CUHK and Tencent
- [BERT Rediscovers the Classical NLP Pipeline](https://arxiv.org/pdf/1905.05950.pdf). May 2019. Google, Brown.  "We find that the model represents the steps of the traditional NLP pipeline in an interpretable and localizable way, and that the regions responsible for each step appear in the expected sequence: POS tagging, parsing, NER, semantic roles, then coreference"
- [Efficient Ladder-style DenseNets for Semantic Segmentation of Large Images](https://arxiv.org/pdf/1905.05661.pdf). May 2019. University of Zagreb. "allow training at megapixel resolution on commodity hardware."
- [Few-Shot Viewpoint Estimation](https://arxiv.org/pdf/1905.04957.pdf). May 2019. UC Merced, NVIDIA
- [ISBNet: Instance-aware Selective Branching Network](https://arxiv.org/pdf/1905.04849.pdf). May 2019. National University of Singapore. Change the model complexity at inference time depending on the input. "ISBNet takes only 12.45% parameters and 45.79% FLOPs of the state-of-the-art efficient network ShuffleNetV2 with comparable accuracy"
- [The Materials Science Procedural Text Corpus: Annotating Materials Synthesis Procedures with Shallow Semantic Structures](https://arxiv.org/pdf/1905.06939.pdf). May 2019. UMass Amherst, MIT.
- [Collaborative Global-Local Networks for Memory-Efficient Segmentation of Ultra-High Resolution Images](https://arxiv.org/pdf/1905.06368.pdf). May 2019. Texas A&M. "resolution up to 30 million pixels)"
- [WHAT DO YOU LEARN FROM CONTEXT? PROBING FOR SENTENCE STRUCTURE IN CONTEXTUALIZED WORD REPRESENTATIONS](https://arxiv.org/pdf/1905.06316.pdf). May 2019. Google AI Language, Johns Hopkins University, Swarthmore College, New York University, Brown University
- [3D SEMANTIC SCENE COMPLETION FROM A SINGLE DEPTH IMAGE USING ADVERSARIAL TRAINING](https://arxiv.org/pdf/1905.06231.pdf). May 2019. RWTH Aachen University, Universtiy of Bonn. 
- [Neural Query Language: A Knowledge Base Query Language for Tensorflow](https://arxiv.org/pdf/1905.06209.pdf). May 2019. Google.
- [Rethinking the Usage of Batch Normalization and Dropout in the Training of Deep Neural Networks](https://arxiv.org/pdf/1905.05928.pdf). May 2019. Tencent, CUHK, Nankai University
- [Task-Driven Modular Networks for Zero-Shot Compositional Learning](https://arxiv.org/pdf/1905.05908.pdf). May 2019. CMU, FAIR. "One of the hallmarks of human intelligence is the ability to compose learned knowledge into novel concepts which can be recognized without a single training example"
- [DARNet: Deep Active Ray Network for Building Segmentation](https://arxiv.org/pdf/1905.05889.pdf). May 2019. University of Toronto, Vector Institute, Uber ATG Toronto, NVIDIA
- [Sparse Sequence-to-Sequence Models](https://arxiv.org/pdf/1905.05702.pdf). May 2019. Instituto de Telecomunicacoes (Lisbon), Unbabel
- [Entity-Relation Extraction as Multi-Turn Question Answering](https://arxiv.org/pdf/1905.05529.pdf). May 2019. Shannon AI, Stanford
- [Cognitive Graph for Multi-Hop Reading Comprehension at Scale](https://arxiv.org/pdf/1905.05460.pdf). May 2019. Tsinghua University, Alibaba
- [Diversify and Match: A Domain Adaptive Representation Learning Paradigm for Object Detection](https://arxiv.org/pdf/1905.05396.pdf). May 2019. KAIST.
- [A Survey of Multilingual Neural Machine Translation](https://arxiv.org/pdf/1905.05395.pdf). May 2019. NICT (Kyoto), Osaka University, Microsoft Hyderabad
- [A Context-and-Spatial Aware Network for Multi-Person Pose Estimation](https://arxiv.org/pdf/1905.05355.pdf). May 2019. ByteDance, Southeast University (Nanjing)
- [Mega-Reward: Achieving Human-Level Play without Extrinsic Rewards](https://arxiv.org/pdf/1905.04640.pdf). May 2019. Oxford, Beihang University, Hebei University of Technology
- [GCNet: Non-local Networks Meet Squeeze-Excitation Networks and Beyond](https://arxiv.org/pdf/1904.11492.pdf). Apr 2019. Tsinghua University, Hong Kong University of Science and Technology, Microsoft Research Asia
- [Unsupervised Data Augmentation](https://arxiv.org/pdf/1904.12848.pdf). Apr 2019. Google Brain, CMU. "on the IMDb text classification dataset, with only 20 labeled examples, UDA outperforms the state-of-the-art model trained on 25,000 labeled examples". Quoc V. Le [HighPri]
- [Attention Augmented Convolutional Networks](https://arxiv.org/pdf/1904.09925.pdf). Apr 2019. Google Brain. Quoc V Le. "Attention Augmentation leads to consistent improvements in image classification on ImageNet and object detection on COCO across many different models and scales" [HighPri]
- [MixMatch: A Holistic Approach to Semi-Supervised Learning](https://arxiv.org/pdf/1905.02249.pdf). May 2019. Google. Ian Goodfellow. [HighPri]
- [Adversarial Examples Are Not Bugs, They Are Features](https://arxiv.org/pdf/1905.02175.pdf). May 2019. MIT
- [Similarity of Neural Network Representations Revisited](https://arxiv.org/pdf/1905.00414.pdf). May 2019. Google Brain. UMich, ICML 2019. Geoffrey Hinton
- [The Effect of Network Width on Stochastic Gradient Descent and Generalization: an Empirical Study](https://arxiv.org/pdf/1905.03776.pdf). May 2019. Google Brain, DeepMind. ICML 2019. Quoc V le. [HighPri]
- [Local Relation Networks for Image Recognition](https://arxiv.org/pdf/1904.11491.pdf). Apr 2019. Microsoft Research Asia, Tsinghua University
- [Making Convolutional Networks Shift-Invariant Again](https://arxiv.org/pdf/1904.11486.pdf). Apr 2019. Adobe. 
- [Searching for MobileNetV3](https://arxiv.org/pdf/1905.02244.pdf). May 2019. Google, Google Brain. Quoc V Le. [HighPri]
- [Deep Learning for Audio Signal Processing](https://arxiv.org/pdf/1905.00078.pdf). Apr 2019. Aalborg University Copenhagen, Google, Tampere University and CNRS LIS/Université de Toulon/Austrian Research Institute for Artificial Intelligence. Review of techniques (speech, music, environmental sound)
- [Challenges of Real-World Reinforcement Learning](https://arxiv.org/pdf/1904.12901.pdf). Apr 2019. ICML 2019. Google Brain, DeepMind. [HighPri]
- [RepPoints: Point Set Representation for Object Detection](https://arxiv.org/pdf/1904.11490.pdf). Apr 2019. Peking University, Tsinghua University, Microsoft Research Asia. Anchor-free object detection
- [Learning Loss for Active Learning](https://arxiv.org/pdf/1905.03677.pdf). May 2019. Lunit Inc (S. Korea), KAIST
- [Language Models with Transformers](https://arxiv.org/pdf/1904.09408.pdf). Apr 2019. AWS (Mu, Smola)
- [Meta-learning of Sequential Strategies](https://arxiv.org/pdf/1905.03030.pdf). May 2019. DeepMind Technical Report. "In this report we review memory-based metalearning as a tool for building sample-efficient strategies that learn from past experience to adapt to any task within a target class"
- [Unified Language Model Pre-training for Natural Language Understanding and Generation](https://arxiv.org/pdf/1905.03197.pdf). May 2019. Microsoft Research
- [Adversarial Training for Free!](https://arxiv.org/pdf/1904.12843.pdf). Apr 2019. UMaryland, United States Naval Academy
- [Spatial-Temporal Relation Networks for Multi-Object Tracking](https://arxiv.org/pdf/1904.11489.pdf). Apr 2019.  Microsoft Research Asia
- [You Only Propagate Once: Accelerating Adversarial Training via Maximal Principle](https://arxiv.org/pdf/1905.00877.pdf). May 2019. Peking University
- [Self-supervised Learning for Video Correspondence Flow](https://arxiv.org/pdf/1905.00875.pdf). May 2019. Oxford
- [Learn Stereo, Infer Mono: Siamese Networks for Self-Supervised, Monocular, Depth Estimation](https://arxiv.org/pdf/1905.00401.pdf). May 2019. Tel Aviv University, The Open University of Israel
- [Segmentations is All You Need](https://arxiv.org/pdf/1904.13300.pdf). May 2019. Hebei University of Technology, Oxford, Hunan Agricultural University, SnowCloud.ai. "We propose a new paradigm of the detection task that is anchor-box free and NMS free" "as the basis of RPN, NMS cannot solve the problem of low recall in complicated occlusion situation". COCO AP slightly worse than Cascade R-CNN, improved AR.
- [Embedding Human Knowledge in Deep Neural Network via Attention Map](https://arxiv.org/pdf/1905.03540.pdf). May 2019. Chubu University, ABEJA Inc
- [Surprising Effectiveness of Few-Image Unsupervised Feature Learning](https://arxiv.org/pdf/1904.13132.pdf). Apr 2019. Visual Geometry Group (Oxford)
- [Neural Path Planning: Fixed Time, Near-Optimal Path Generation via Oracle Imitation](https://arxiv.org/pdf/1904.11102.pdf). Apr 2019. UC San Diego
- [MASS: Masked Sequence to Sequence Pre-training for Language Generation](https://arxiv.org/pdf/1905.02450.pdf). May 2019. ICML 2019. Nanjing University of Science and Technology , Microsoft Research. "the-art accuracy (37.5 in terms of BLEU score) on the unsupervised English-French translation"
- [Few-Shot Unsupervised Image-to-Image Translation](https://arxiv.org/pdf/1905.01723.pdf). May 2019. NVIDIA, Cornell University, Aalto University
- [Deconstructing Lottery Tickets: Zeros, Signs, and the Supermask](https://arxiv.org/pdf/1905.01067.pdf). May 2019. Uber
- [THE LOTTERY TICKET HYPOTHESIS: FINDING SPARSE, TRAINABLE NEURAL NETWORKS](https://arxiv.org/pdf/1803.03635.pdf). Mar 2019. ICLR 2019 Best Paper. MIT CSAIL.
- [Stabilizing the Lottery Ticket Hypothesis](https://arxiv.org/pdf/1903.01611.pdf). Jun 2019. MIT CSAIL, University of Cambridge, Element AI, University of Toronto, Vector Institute
- [Batch Normalization is a Cause of Adversarial Vulnerability](https://arxiv.org/pdf/1905.02161.pdf). May 2019. University of Guelph, Vector Institute, University of Waterloo, Perimeter Institute for Theoretical Physics, University College London, Google Brain.
- [Fast User-Guided Video Object Segmentation by Interaction-and-Propagation Networks](https://arxiv.org/pdf/1904.09791.pdf). May 2019. Yonsei University, Adobe Research
- [Generating Long Sequences with Sparse Transformers](https://arxiv.org/pdf/1904.10509.pdf). Apr 2019. OpenAI
- [Billion-scale semi-supervised learning for image classification](https://arxiv.org/pdf/1905.00546.pdf). May 2019. Facebook AI. "one billion unlabelled images, our learned vanilla ResNet-50 achieves 81.2% top-1 accuracy on Imagenet benchmark."
- [Single Image Portrait Relighting](https://arxiv.org/pdf/1905.00824.pdf). May 2019. UC San Diego, Google
- [Do Transformer Attention Heads Provide Transparency in Abstractive Summarization?](https://arxiv.org/pdf/1907.00570.pdf). July 2019. University of Amsterdam, De Persgroep
- [Learning Representations from Imperfect Time Series Data via Tensor Rank Regularization](https://arxiv.org/pdf/1907.01011.pdf). July 2019. CMU, , RIKEN Center for Artificial Intelligence Project
- [REPRESENTATION, EXPLORATION AND RECOMMENDATION OF MUSIC PLAYLISTS](https://arxiv.org/pdf/1907.01098.pdf). July 2019. Arizona State University
- [Real-time Claim Detection from News Articles and Retrieval of Semantically-Similar Factchecks](https://arxiv.org/pdf/1907.02030.pdf). July 2019. Logically.co.uk
- [HO-3D: A Multi-User, Multi-Object Dataset for Joint 3D Hand-Object Pose Estimation](https://arxiv.org/pdf/1907.01481.pdf). July 2019. Graz University of Technology,  Universite de Bordeaux
- [Language2Pose: Natural Language Grounded Pose Forecasting](https://arxiv.org/pdf/1907.01108.pdf). July 2019. CMU
- [XNect: Real-time Multi-person 3D Human Pose Estimation with a Single RGB Camera](https://arxiv.org/pdf/1907.00837.pdf). July 2019. Max Planck Institute for Informatics, EPFL, University of Saarland
- [Combining Q&A Pair Quality and Question Relevance Features on Community-based Question Retrieval](https://arxiv.org/pdf/1907.02031.pdf). July 2019. Wuhan University of Technology
- [Constructing large scale biomedical knowledge bases from scratch with rapid annotation of interpretable patterns](https://arxiv.org/pdf/1907.01417.pdf). July 2019. BenevolentAI
- [Going Deeper with Point Networks](https://arxiv.org/pdf/1907.00960.pdf). July 2019. University College London. Point cloud processing
- [Collecting Indicators of Compromise from Unstructured Text of Cybersecurity Articles using Neural-Based Sequence Labelling](https://arxiv.org/pdf/1907.02636.pdf). July 2019. Tencent
- [Single-Path Mobile AutoML: Efficient ConvNet Design and NAS Hyperparameter Optimization](https://arxiv.org/pdf/1907.00959.pdf). July 2019. CMU, Microsoft, Harbin Institute of Technology
- [Time Series Anomaly Detection with Variational Autoencoders](https://arxiv.org/pdf/1907.01702.pdf). July 2019. Harbin Institute of Technology
- [How we do things with words: Analyzing text as social and cultural data](https://arxiv.org/pdf/1907.01468.pdf). July 2019. Alan Turing Institute (UK), Utrecht University (NL), University of Warwick, Carnegie Mellon University, Georgia Institute of Technology, Cornell University, Leiden University (NL), University of London
- [LumièreNet: Lecture Video Synthesis from Audio](https://arxiv.org/pdf/1907.02253.pdf). July 2019. Udacity AI
- [Graph-based Knowledge Distillation by Multi-head Self-attention Network](https://arxiv.org/pdf/1907.02226.pdf). July 2019. Inha University (Korea)
- [Proposal, Tracking and Segmentation (PTS): A Cascaded Network for Video Object Segmentation](https://arxiv.org/pdf/1907.01203.pdf). July 2019. Horizon Robotics, Huazhong University of Science and Technology
- [The ApolloScape Open Dataset for Autonomous Driving and its Application](https://arxiv.org/pdf/1803.06184.pdf). July 2019. Baidu
- [SEntiMoji: An Emoji-Powered Learning Approach for Sentiment Analysis in Software Engineering](https://arxiv.org/pdf/1907.02202.pdf). July 2019. Peking University, UMich
- [Extraction and Analysis of Fictional Character Networks: A Survey](https://arxiv.org/pdf/1907.02704.pdf). July 2019. Laboratoire Informatique d’Avignon
- [Data Encoding for Byzantine-Resilient Distributed Optimization](https://arxiv.org/pdf/1907.02664.pdf). July 2019. UCLA, City University of Hong Kong
- [Diffprivlib: The IBM Dierential Privacy Library](https://arxiv.org/pdf/1907.02444.pdf). July 2019. IBM
- [C3 Framework: An Open-source PyTorch Code for Crowd Counting](https://arxiv.org/pdf/1907.02724.pdf). July 2019. Northwestern Polytechnical University, Xi’an, Zhejiang University
- [Real-time Dynamic Object Detection for Autonomous Driving using Prior 3D-Maps](https://arxiv.org/pdf/1809.11036.pdf). July 2019.  AKKA Technologies,  INRIA Paris, Spleenlab, Valeo Vision Systems
- [Visual Appearance Analysis of Forest Scenes for Monocular SLAM](https://arxiv.org/pdf/1907.02824.pdf). July 2019. University of Edinburgh
- [Wireless Federated Distillation for Distributed Edge Learning with Heterogeneous Data](https://arxiv.org/pdf/1907.02745.pdf). July 2019. KAIST, Kings College London
- [Detecting and Diagnosing Adversarial Images with Class-Conditional Capsule Reconstructions](https://arxiv.org/pdf/1907.02957.pdf). July 2019. Google Brain, UC San Diego. Geoffrey Hinton
- [Data Poisoning against Differentially-Private Learners: Attacks and Defenses](https://arxiv.org/pdf/1903.09860.pdf). July 2019. University of Wisconsin–Madison
- [ByRDiE: Byzantine-resilient Distributed Coordinate Descent for Decentralized Learning](https://arxiv.org/pdf/1708.08155.pdf). July 2019. Rutgers University–New Brunswick
- [Improved local search for graph edit distance](https://arxiv.org/pdf/1907.02929.pdf). July 2019. Normandie Univ, Free University of Bozen-Bolzano
- [Visus: An Interactive System for Automatic Machine Learning Model Building and Curation](https://arxiv.org/pdf/1907.02889.pdf). July 2019. NYU
- [Multi-lingual Intent Detection and Slot Filling in a Joint BERT-based Model](https://arxiv.org/pdf/1907.02884.pdf). July 2019. Almawave
- [SCOPS: Self-Supervised Co-Part Segmentation](https://arxiv.org/pdf/1905.01298.pdf). May 2019. UC Merced, NVIDIA
- [Seamless Scene Segmentation](https://arxiv.org/pdf/1905.01220.pdf). May 2019. Mapilllary. State-of-the-art results on Cityscapes, Indian Driving Dataset and Mapillary Vistas
- [26ms Inference Time for ResNet-50: Towards Real-Time Execution of all DNNs on Smartphone](https://arxiv.org/pdf/1905.00571.pdf). May 2019. ICML 2019. College of William & Mary, Northeastern. "CADNN outperforms all the state-of-the-art dense DNN execution frameworks like TensorFlow Lite and TVM"
- [Learn to synthesize and synthesize to learn](https://arxiv.org/pdf/1905.00286.pdf). May 2019. Ecole Polytechnique Fderale de Lausanne, Istanbul Technical University, , University of Lausanne. Face image synthesis
- [Graph Matching Networks for Learning the Similarity of Graph Structured Objects](https://arxiv.org/pdf/1904.12787.pdf). May 2019. ICML 2019. DeepMind, Google [HighPri]
- [DAC: The Double Actor-Critic Architecture for Learning Options](https://arxiv.org/pdf/1904.12691.pdf). May 2019. Oxford
- [Safe Reinforcement Learning with Scene Decomposition for Navigating Complex Urban Environments](https://arxiv.org/pdf/1904.11483.pdf). Apr 2019. Stanford, Honda Research Institute
- [Sensor Fusion for Joint 3D Object Detection and Semantic Segmentation](https://arxiv.org/pdf/1904.11466.pdf). Apr 2019. Uber ATG.
- [Differentiable Pruning Method for Neural Networks](https://arxiv.org/pdf/1904.10921.pdf). Apr 2019. Samsung, Texas A&M
- [Language Modeling with Deep Transformers](https://arxiv.org/pdf/1905.04226.pdf). May 2019. RWTH Aachen University, AppTek. "We explore multi-layer autoregressive Transformer models in language modeling for speech recognition"
- [Survey on Evaluation Methods for Dialogue Systems](https://arxiv.org/pdf/1905.04071.pdf). May 2019. Zurich University of Applied Sciences, Universidad Nacional de Educacion a Distancia, University of the Basque Country, Universite Paris Saclay
- [What Do Single-view 3D Reconstruction Networks Learn?](https://arxiv.org/pdf/1905.03678.pdf). May 2019. University of Freiburg, Intel Labs
- [UNIVERSAL SOUND SEPARATION](https://arxiv.org/pdf/1905.03330.pdf). May 2019. Google, Mitsubishi Electric Research Laboratories
- [Deep Flow-Guided Video Inpainting](https://arxiv.org/pdf/1905.02884.pdf). May 2019. CUHK, Nanyang
- [Information-Theoretic Considerations in Batch Reinforcement Learning](https://arxiv.org/pdf/1905.00360.pdf). May 2019. ICML 2019. UIUC
- [Survey on Automated Machine Learning](https://arxiv.org/pdf/1904.12054.pdf). Apr 2019. USU Software AG, University of Stuttgart
- [VoVNet: An Energy and GPU-Computation Efficient Backbone Network for Real-Time Object Detection](https://arxiv.org/pdf/1904.09730.pdf). Apr 2019. ETRI
- [From GAN to WGAN](https://arxiv.org/pdf/1904.08994.pdf). Apr 2019. OpenAI
- [[TENet] Trinity of Pixel Enhancement: a Joint Solution for Demosaicking, Denoising and Super-Resolution](https://arxiv.org/pdf/1905.02538.pdf). May 2019. SenseTime, CAS. [HighPri]
- [FaceShapeGene: A Disentangled Shape Representation for Flexible Face Image Editing](https://arxiv.org/pdf/1905.01920.pdf). May 2019. Tsinghua University, Tencent
- [From Video Game to Real Robot: The Transfer between Action Spaces](https://arxiv.org/pdf/1905.00741.pdf). May 2019. University of Eastern Finland, Aalto University
- [RetinaFace: Single-stage Dense Face Localisation in the Wild](https://arxiv.org/pdf/1905.00641.pdf). May 2019. Imperial College London, InsightFace, Middlesex University London, FaceSoft
- [ResNet Can Be Pruned 60×: Introducing Network Purification and Unused Path Removal (P-RM) after Weight Pruning](https://arxiv.org/pdf/1905.00136.pdf). Apr 2019. ICML 2019. Northeastern
- [Deferred Neural Rendering: Image Synthesis using Neural Textures](https://arxiv.org/pdf/1904.12356.pdf). Apr 2019. Technical University of Munich, Stanford University
- [HAR-Net: Joint Learning of Hybrid Attention for Single-stage Object Detection](https://arxiv.org/pdf/1904.11141.pdf). Apr 2019. Tsinghua University
- [Real-time Intent Prediction of Pedestrians for Autonomous Ground Vehicles via Spatio-Temporal DenseNet](https://arxiv.org/pdf/1904.09862.pdf). Apr 2019. Deakin University
- [BERTSCORE: Evaluating Text Generation with BERT](https://arxiv.org/pdf/1904.09675.pdf). Apr 2019. Cornell, ASAPP Inc
- [Constant-Time Machine Translation with Conditional Masked Language Models](https://arxiv.org/pdf/1904.09324.pdf). Apr 2019. FAIR
- [Video Object Segmentation and Tracking: A Survey](https://arxiv.org/pdf/1904.09172.pdf). Apr 2019. China University of Mining and Technology, Nanyang Technological University
- [[RefineDet] Single-Shot Refinement Neural Network for Object Detection](https://arxiv.org/pdf/1711.06897.pdf). Nov 2017. CAS, University of Chinese Academy of Sciences, GE Global Research. Realtime detection. COCO State of the Art
- [AdaNet: A Scalable and Flexible Framework for Automatically Learning Ensembles](https://arxiv.org/pdf/1905.00080.pdf). Apr 2019. Google, Duke, Courant Institute of Mathematical Sciences
- [Survey of Dropout Methods for Deep Neural Networks](https://arxiv.org/pdf/1904.13310.pdf). Apr 2019. UToronto
- [Real numbers, data science and chaos: How to fit any dataset with a single parameter](https://arxiv.org/pdf/1904.12320.pdf). Apr 2019. SAP Labs. 
- [Face Video Generation from a Single Image and Landmarks](https://arxiv.org/pdf/1904.11521.pdf). Apr 2019. Imperial College London, University of Oulu
- [LADN: Local Adversarial Disentangling Network for Facial Makeup and De-Makeup](https://arxiv.org/pdf/1904.11272.pdf). Apr 2019. Hong Kong University of Science and Technology, University of Illinois Urbana-Champaign, Tencent Youtu
- [NeurIPS 2019 Competition: The MineRL Competition on Sample Efficient Reinforcement Learning using Human Priors](https://arxiv.org/pdf/1904.10079.pdf). Apr 2019. CMU, Microsoft Research, UMaryland, AICrowd, Queen Mary University of London. "The primary goal of the competition is to foster the development of algorithms which can efficiently leverage human demonstrations to drastically reduce the number of samples needed to solve complex, hierarchical, and sparse environments"
- [The Curious Case of Neural Text Degeneration](https://arxiv.org/pdf/1904.09751.pdf). Apr 2019. UWashington, AI^2
- [Generative Exploration and Exploitation](https://arxiv.org/pdf/1904.09605.pdf). Apr 2019. Peking University
- [LATTE: Accelerating LiDAR Point Cloud Annotation via Sensor Fusion, One-Click Annotation, and Tracking](https://arxiv.org/pdf/1904.09085.pdf). Apr 2019. UC Berkeley
- [Beto, Bentz, Becas: The Surprising Cross-Lingual Effectiveness of BERT](https://arxiv.org/pdf/1904.09077.pdf). Apr 2019. Johns Hopkins University
- [Are We Really Making Much Progress? A Worrying Analysis of Recent Neural Recommendation Approaches](https://arxiv.org/pdf/1907.06902.pdf). July 2019. Politecnico di Milano, University of Klagenfurt
- [Self Organizing Supply Chains for Micro-Prediction: Present and Future uses of the ROAR Protocol](https://arxiv.org/pdf/1907.07514.pdf). ICML 2019. JP Morgan Chase
- [Bag of Tricks for Image Classification with Convolutional Neural Networks](https://arxiv.org/pdf/1812.01187.pdf). Dec 2018. AWS. Mu [HighPri]
- [Gated-SCNN: Gated Shape CNNs for Semantic Segmentation](https://arxiv.org/pdf/1907.05740.pdf). July 2019. NVIDIA, University of Waterloo, University of Toronto, Vector Institute
- [Counterfactual Learning from Logs for Improved Ranking of E-Commerce Products](https://arxiv.org/pdf/1907.10409.pdf). July 2019. IBM Russia, Technische Universität München, Mercateo Germany
- [Make Skeleton-based Action Recognition Model Smaller, Faster and Better](https://arxiv.org/pdf/1907.09658.pdf). July 2019.  Nara Institute of Science and Technology (Japan), RIKEN, Kyoto University
- [Effortless Deep Training for Traffic Sign Detection Using Templates and Arbitrary Natural Images](https://arxiv.org/pdf/1907.09679.pdf). July 2019. Instituto Federal do Esp´ırito Santo, University of Trento
- [A-MAL: Automatic Motion Assessment Learning from Properly Performed Motions in 3D Skeleton Videos](https://arxiv.org/pdf/1907.10004.pdf). July 2019. The University of Haifa
- [Construct Dynamic Graphs for Hand Gesture Recognition via Spatial-Temporal Attention](https://arxiv.org/pdf/1907.08871.pdf). July 2019. Rutgers University, University of Delaware, University of Rochester
- [Incremental Transformer with Deliberation Decoder for Document Grounded Conversations](https://arxiv.org/pdf/1907.08854.pdf). July 2019. Huazhong University of Science and Technology,  WeChat AI (Tencent), CAS,  Northeastern University (China) [HighPri]
- [I Stand With You: Using Emojis to Study Solidarity in Crisis Events](https://arxiv.org/pdf/1907.08326.pdf). July 2019. UNC Charlotte
- [GPU-Accelerated Atari Emulation for Reinforcement Learning](https://arxiv.org/pdf/1907.08467.pdf). July 2019. NVIDIA. CUDA port of Atari Learning Environment
- [Multi-Task Regression-based Learning for Autonomous Unmanned Aerial Vehicle Flight Control within Unstructured Outdoor Environments](https://arxiv.org/pdf/1907.08320.pdf). July 2019. Durham University
- [Generic Prediction Architecture Considering both Rational and Irrational Driving Behaviors](https://arxiv.org/pdf/1907.10170.pdf). July 2019. UC Berkeley
- [Federated Learning Systems: Vision, Hype and Reality for Data Privacy and Protection](https://arxiv.org/pdf/1907.09693.pdf). July 2019. National University of Singapore
- [Multi-Class Lane Semantic Segmentation using Efficient Convolutional Networks](https://arxiv.org/pdf/1907.09438.pdf). July 2019. National Chiao Tung University, Industrial Technology Research Institute (Taiwan)
- [Visualizing the Invisible: Occluded Vehicle Segmentation and Recovery](https://arxiv.org/pdf/1907.09381.pdf). July 2019. Unknown affiliation
- [DetectFusion: Detecting and Segmenting Both Known and Unknown Dynamic Objects in Real-time SLAM](https://arxiv.org/pdf/1907.09127.pdf). July 2019. Keio University, Graz University of Technology, VRVis Research Center
- [Cross-Domain Car Detection Using Unsupervised Image-to-Image Translation: From Day to Night](https://arxiv.org/pdf/1907.08719.pdf). July 2019. Universidade Federal do Esp´ırito Santo, Instituto Federal do Esp´ırito Santo, University of Trento
- [Interpretable Modelling of Driving Behaviors in Interactive Driving Scenarios based on Cumulative Prospect Theory](https://arxiv.org/pdf/1907.08707.pdf). July 2019. UC Berkeley
- [Fairness-Aware Ranking in Search & Recommendation Systems with Application to LinkedIn Talent Search](https://arxiv.org/pdf/1905.01989.pdf). July 2019. LinkedIn
- [SDNet: Semantically Guided Depth Estimation Network](https://arxiv.org/pdf/1907.10659.pdf). July 2019.  Goethe University,  NTNU Trondheim
- [The autofeat Python Library for Automated Feature Engineering and Selection](https://arxiv.org/pdf/1901.07329.pdf). July 2019. Technische Universität Berlin, BASF SE
- [SpanBERT: Improving Pre-training by Representing and Predicting Spans](https://arxiv.org/pdf/1907.10529.pdf). July 2019. University of Washington, Princeton, FAIR.
- [Semi-Supervised Tensor Factorization for Node Classification in Complex Social Networks](https://arxiv.org/pdf/1907.10416.pdf). July 2019. NCSR Demokritos
- [Efficient GAN-based method for cyber-intrusion detection](https://arxiv.org/pdf/1904.02426.pdf). July 2019. Shanghai Jiao Tong University
- [Translator2Vec: Understanding and Representing Human Post-Editors](https://arxiv.org/pdf/1907.10362.pdf). July 2019. Unbabel & Instituto de Telecomunicacoes
- [MixNet: Mixed Depthwise Convolutional Kernels](https://arxiv.org/pdf/1907.09595.pdf). July 2019. Google Brain. Quoc V Le. [HighPri]
- [Trading via Image Classification](https://arxiv.org/pdf/1907.10046.pdf). July 2019. JP Morgan AI Research [HighPri]. CV on timeseries graphs during trading to replicate how traders work.
- [Analyzing the Variety Loss in the Context of Probabilistic Trajectory Prediction](https://arxiv.org/pdf/1907.10178.pdf). July 2019. Georg-August-Universitat Gottingen, Volkswagen Group of America
- [Introduction to Neural Network based Approaches for Question Answering over Knowledge Graphs](https://arxiv.org/pdf/1907.09361.pdf). July 2019. University of Bonn, Fraunhofer IAIS, University of Bochum
- [Trends in Integration of Vision and Language Research: A Survey of Tasks, Datasets, and Methods](https://arxiv.org/pdf/1907.09358.pdf). July 2019. Saarland University
- [ChromaGAN: An Adversarial Approach for Picture Colorization](https://arxiv.org/pdf/1907.09837.pdf). July 2019. University Pompeu Fabra
- [Graph Reasoning Networks for Visual Question Answering](https://arxiv.org/pdf/1907.09815.pdf). July 2019. University of Sydney
- [Similarity-Preserving Knowledge Distillation](https://arxiv.org/pdf/1907.09682.pdf). July 2019. Simon Fraser University, Borealis AI
- [Techniques for Automated Machine Learning](https://arxiv.org/pdf/1907.08908.pdf). July 2019. Texas A&M. Suvey-esque
- [From Big to Small: Multi-Scale Local Planar Guidance for Monocular Depth Estimation](https://arxiv.org/pdf/1907.10326.pdf). July 2019. Hanyang University
- [Real-time Event Detection on Social Data Streams](https://arxiv.org/pdf/1907.11229.pdf). July 2019. Twitter [HighPri]
- [Speech Model Pre-training for End-to-End Spoken Language Understanding](https://arxiv.org/pdf/1904.03670.pdf). July 2019. Universite de Montreal / Mila, Fluent.ai, CIFAR Fellow
- [Toward Explainable Fashion Recommendation](https://arxiv.org/pdf/1901.04870.pdf). July 2019. Tohoku University
- [Robustness properties of Facebook’s ResNeXt WSL models](https://arxiv.org/pdf/1907.07640.pdf). July 2019. NYU
- [Semisupervised Adversarial Neural Networks for Cyber Security Transfer Learning](https://arxiv.org/pdf/1907.11129.pdf). July 2019. Commonwealth Computer Research, Inc.
- [A Modern Take on the Bias-Variance Tradeoff in Neural Networks](https://arxiv.org/pdf/1810.08591.pdf). July 2019. Mila, Université de Montréal
- [Accurate and Robust Eye Contact Detection During Everyday Mobile Device Interactions](https://arxiv.org/pdf/1907.11115.pdf). July 2019. ETH Zürich, University of Stuttgart
- [GRAPH NEURAL LASSO FOR DYNAMIC NETWORK REGRESSION](https://arxiv.org/pdf/1907.11114.pdf). July 2019. FSU
- [SlimYOLOv3: Narrower, Faster and Better for Real-Time UAV Applications](https://arxiv.org/pdf/1907.11093.pdf). July 2019. Beijing Institute of Technology
- [Importance-Aware Semantic Segmentation with Efficient Pyramidal Context Network for Navigational Assistant Systems](https://arxiv.org/pdf/1907.11066.pdf).  July 2019. Zhejiang University
- [DropAttention: A Regularization Method for Fully-Connected Self-Attention Networks](https://arxiv.org/pdf/1907.11065.pdf). July 2019. Fudan University, MILA.
- [Recent Advances in Open Set Recognition: A Survey](https://arxiv.org/pdf/1811.08581.pdf). July 2019.  Nanjing University of Aeronautics and Astronautics. Open Set: "A more realistic scenario is open set recognition (OSR), where incomplete knowledge of the world exists at training time, and unknown classes can be submitted to an algorithm during testing, requiring the classifiers to not only accurately classify the seen classes, but also effectively deal with the unseen ones"
- [Dynamic Input for Deep Reinforcement Learning in Autonomous Driving](https://arxiv.org/pdf/1907.10994.pdf). July 2019. University of Freiburg, BMWGroup, Unterschleissheim, Cluster of Excellence BrainLinks-BrainTools
- [Weakly Supervised Recognition of Surgical Gestures](https://arxiv.org/pdf/1907.10993.pdf). July 2019. UCL, Universita di Verona,  Politecnico di Milano
- [CROSS ATTENTION NETWORK FOR SEMANTIC SEGMENTATION](https://arxiv.org/pdf/1907.10958.pdf). July 2019. The University of Manchester
- [Coin.AI: A Proof-of-Useful-Work Scheme for Blockchain-Based Distributed Deep Learning](https://arxiv.org/pdf/1903.09800.pdf). July 2019. Universidad Carlos III of Madrid. [HighPri]
- [ET-Net: A Generic Edge-aTtention Guidance Network for Medical Image Segmentation](https://arxiv.org/pdf/1907.10936.pdf). July 2019. Tianjin University, Inception Institute of Artificial Intelligence
- [DNNVM : END-TO-END COMPILER LEVERAGING HETEROGENEOUS OPTIMIZATIONS ON FPGA-BASED CNN ACCELERATORS](https://arxiv.org/pdf/1902.07463.pdf). July 2019. Xilinx (Beijing),  Tsinghua University
- [The Truly Deep Graph Convolutional Networks for Node Classification](https://arxiv.org/pdf/1907.10903.pdf). July 2019. Tencent. [HighPri]
- [Optuna: A Next-generation Hyperparameter Optimization Framework](https://arxiv.org/pdf/1907.10902.pdf). July 2019. Preferred Networks, Inc. [HighPri]
- [Submission to ActivityNet Challenge 2019: Task B Spatio-temporal Action Localization](https://arxiv.org/pdf/1907.10837.pdf). July 2019. SK Telecom.  "using only RGB sequential images"
- [Using Database Rule for Weak Supervised Text-to-SQL Generation](https://arxiv.org/pdf/1907.00620.pdf). July 2019. Rokid AI Lab, China Electronic Technology Group Corporation Information Science Academy. 
- [Green AI](https://arxiv.org/pdf/1907.10597.pdf). July 2019. AI^2, CMU, UWashington. Huge computational costs has environmental impact. Green AI suggest adding efficiency as an evaluation criterion and reporting price of development and running models. [HighPri]
- [An Effective Approach to Unsupervised Machine Translation](https://arxiv.org/pdf/1902.01313.pdf). July 2019. University of the Basque Country
- [Benchmarking TPU, GPU, and CPU Platforms for Deep Learning](https://arxiv.org/pdf/1907.10701.pdf). July 2019. Harvard. [HighPri]
- [Self-Supervised Vision-Based Detection of the Active Speaker as Support for Socially-Aware Language Acquisition](https://arxiv.org/pdf/1711.08992.pdf). July 2019. USC, KTH Royal Institute of Technology NTNU Norwegian University of Science and Technology
- [Querying Knowledge via Multi-Hop English Questions](https://arxiv.org/pdf/1907.08176.pdf). July 2019. Stony Brook University.
- [OCC: A Smart Reply System for Eicient In-App Communications](https://arxiv.org/pdf/1907.08167.pdf). July 2019. Uber.  OCC=one-click-chat
- [Audits as Evidence: Experiments, Ensembles, and Enforcement](https://arxiv.org/pdf/1907.06622.pdf). July 2019. UC Berkeley, NBER. "We develop tools for utilizing correspondence experiments to detect illegal discrimination by individual employers"
- [A SURVEY OF DATA QUALITY MEASUREMENT AND MONITORING TOOLS](https://arxiv.org/pdf/1907.08138.pdf). July 2019. Johannes Kepler University Linz, Software Competence Center Hagenberg. [HighPri]
- [Self-supervised Training of Proposal-based Segmentation via Background Prediction](https://arxiv.org/pdf/1907.08051.pdf). July 2019. EPFL, Balgrist University Hospital, University of Zurich
- [ACTNET: end-to-end learning of feature activations and multi-stream aggregation for effective instance image retrieva](https://arxiv.org/pdf/1907.05794.pdf). July 2019.  University of Surrey. 
- [∂P: A Differentiable Programming System to Bridge Machine Learning and Scientific Computing](https://arxiv.org/pdf/1907.07587.pdf). July 2019. Julia Computing, MIT, Invenia Labs
- [Automatic Grading of Individual Knee Osteoarthritis Features in Plain Radiographs using Deep Convolutional Neural Networks](https://arxiv.org/pdf/1907.08020.pdf). July 2019. University of Oulu, Oulu University Hospital
- [ELG: An Event Logic Graph](https://arxiv.org/pdf/1907.08015.pdf). July 2019. Harbin Institute of Technology. [HighPri]
- [Real-Time Driver State Monitoring Using a CNN Based Spatio-Temporal Approach](https://arxiv.org/pdf/1907.08009.pdf). July 2019. Intel, Technical University of Munich
- [Deep Neural Models for Medical Concept Normalization in User-Generated Texts](https://arxiv.org/pdf/1907.07972.pdf). July 2019. Kazan Federal University, Samsung. "medical concept normalization problem, i.e., the problem of mapping a health-related entity mention in a free-form text to a concept in a controlled vocabulary"
- [FOSNet: An End-to-End Trainable Deep Neural Network for Scene Recognition](https://arxiv.org/pdf/1907.07570.pdf). July 2019.  Yonsei University (Seoul). "Scene recognition is an image recognition problem aimed at predicting the category of the place at which the image is taken"
- [A Computer Vision Application for Assessing Facial Acne Severity from Selfie Images](https://arxiv.org/pdf/1907.07901.pdf). July 2019. Microsoft Research.
- [Asynch-SGBDT: Train a Stochastic Gradient Boosting Decision Tree in an Asynchronous Parallel Manner](https://arxiv.org/pdf/1804.04659.pdf). July 2019. CAS, University of Chinese Academy of Sciences, WiseUranium corp
- [Visual-based Autonomous Driving Deployment from a Stochastic and Uncertainty-aware Perspective](https://arxiv.org/pdf/1903.00821.pdf). July 2019.  Hong Kong University of Science and Technology
- [Understanding Video Content: Efficient Hero Detection and Recognition for the Game "Honor of Kings"](https://arxiv.org/pdf/1907.07854.pdf). July 2019. Tencent 
- [An Adaptive Approach for Anomaly Detector Selection and Fine-Tuning in Time Series](https://arxiv.org/pdf/1907.07843.pdf). July 2019. Alibaba. [HighPri]
- [Evaluation Uncertainty in Data-Driven Self-Driving Testing](https://arxiv.org/pdf/1904.09306.pdf). July 2019. UMich, CMU, Columbia
- [OmniNet: A unified architecture for multi-modal multi-task learning](https://arxiv.org/pdf/1907.07804.pdf). July 2019. IBM, University of Amsterdam
- [Learning Latent Events from Network Message Logs](https://arxiv.org/pdf/1804.03346.pdf). July 2019. AT&T Labs
- [Learning Privately over Distributed Features: An ADMM Sharing Approach](https://arxiv.org/pdf/1907.07735.pdf). July 2019. University of Alberta, University of Kent
- [Lane Detection and Classification using Cascaded CNNs](https://arxiv.org/pdf/1907.01294.pdf). July 2019. University of Bologna, University of Parma, Universidad Carlos III de Madrid
- [Simple, Fast, Accurate Intent Classification and Slot Labeling for Goal-Oriented Dialogue Systems](https://arxiv.org/pdf/1903.08268.pdf). July 2019. Amazon AI, Stanford [HighPri]
- [Gated Recurrent Neural Network Approach for Multilabel Emotion Detection in Microblogs](https://arxiv.org/pdf/1907.07653.pdf). July 2019. University of Moratuwa, La Trobe University Victoria
- [NeurAll: Towards a Unified Visual Perception Model for Automated Driving](https://arxiv.org/pdf/1902.03589.pdf). July 2019. Valeo Vision Systems, UMich-Dearborn
- [SoilingNet: Soiling Detection on Automotive Surround-View Cameras](https://arxiv.org/pdf/1905.01492.pdf). July 2019. Valeo. Determine if camera is soiled by environment (dirt, water, etc)
- [RGB and LiDAR fusion based 3D Semantic Segmentation for Autonomous Driving](https://arxiv.org/pdf/1906.00208.pdf). July 2019. Valeo, Cairo University.
- [Mitigating Uncertainty in Document Classification](https://arxiv.org/pdf/1907.07590.pdf). July 2019. Virginia Tech, NEC Laboratories America, Inc
- [Processing Megapixel Images with Deep Attention-Sampling Models](https://arxiv.org/pdf/1905.03711.pdf). July 2019. Idiap Research Institute (Switzerland), EPFL
- [AquaSight: Automatic Water Impurity Detection Utilizing Convolutional Neural Networks](https://arxiv.org/pdf/1907.07573.pdf). July 2019. TJHSST, UMaryland
- [Self-Attentive Hawkes Processes](https://arxiv.org/pdf/1907.07561.pdf). July 2019. UCL. "Asynchronous events on the continuous time domain, e.g., social media actions and stock transactions, occur frequently in the world. The ability to recognize occurrence patterns of event sequences is crucial to predict which type of events will happen next and when. A de facto standard mathematical framework to do this is the Hawkes process.  In order to enhance expressivity of multivariate Hawkes processes, conventional statistical methods and deep recurrent networks have been employed to modify its intensity function. The former is highly interpretable and requires small size of training data but relies on correct model design while the latter has less dependency on prior knowledge and is more powerful in capturing complicated patterns. We leverage pros and cons of these models and propose a self-attentive Hawkes process (SAHP). The proposed method adapts self-attention to fit the intensity function of Hawkes processes. This design has two benefits: (1) compared with conventional statistical methods, the SAHP is more powerful to identify complicated dependency relationships between temporal events; (2) compared with deep recurrent networks, the self-attention mechanism is able to capture longer historical information, and is more interpretable because the learnt attention weight tensor shows contributions of each historical event ''
- [Augmented Autoencoders: Implicit 3D Orientation Learning for 6D Object Detection](https://arxiv.org/pdf/1902.01275.pdf). July 2019. German Aerospace Center, Technical University of Munich.
- [Natural Adversarial Examples](https://arxiv.org/pdf/1907.07174.pdf). July 2019. UC Berkeley, UWashington, UChicago. ImageNet-A dataset of naturally occuring adversarial examples (classification accuracy degrades on the examples across multiple models).
- [Understanding Deep Learning Techniques for Image Segmentation](https://arxiv.org/pdf/1907.06119.pdf). July 2019. 
- [Efficient Video Generation on Complex Datasets](https://arxiv.org/pdf/1907.06571.pdf). July 2019. DeepMind.
- [Batch-Shaped Channel Gated Networks](https://arxiv.org/pdf/1907.06627.pdf). July 2019. Qualcomm AI Research
- [Facebook FAIR’s WMT19 News Translation Task Submission](https://arxiv.org/pdf/1907.06616.pdf). July 2019. FAIR. Uses `FAIRSEQ`
- [Agglomerative Attention](https://arxiv.org/pdf/1907.06607.pdf). July 2019. Low resource cost approach to attention for transformers
- [Benchmarking Robustness in Object Detection: Autonomous Driving when Winter is Coming](https://arxiv.org/pdf/1907.07484.pdf). July 2019. University of Tubingen, International Max Planck Research School for Intelligent Systems
- [On the “steerability” of generative adversarial networks](https://arxiv.org/pdf/1907.07171.pdf). July 2019. MIT CSAIL
- [Truck Traffic Monitoring with Satellite Images](https://arxiv.org/pdf/1907.07660.pdf). July 2019. CMU, ETH Zürich
- [Learning End-to-End Goal-Oriented Dialog with Maximal User Task Success and Minimal Human Agent Use](https://arxiv.org/pdf/1907.07638.pdf). July 2019. UMich, Intel, Amazon Alexa-AI Research
- [Explaining Classifiers with Causal Concept Effect (CaCE)](https://arxiv.org/pdf/1907.07165.pdf). July 2019. Google Brain, Technion.
- [Efficient Segmentation: Learning Downsampling Near Semantic Boundaries](https://arxiv.org/pdf/1907.07156.pdf). July 2019. University of Waterloo, Facebook, TAL Education (China)
- [Real-time Hair Segmentation and Recoloring on Mobile GPUs](https://arxiv.org/pdf/1907.06740.pdf). July 2019. Google.
- [IMPROVED HYBRID LAYERED IMAGE COMPRESSION USING DEEP LEARNING AND TRADITIONAL CODECS](https://arxiv.org/pdf/1907.06566.pdf). July 2019. Xi’an Jiaotong University, Simon Fraser University
- [Measuring the Transferability of Adversarial Examples](https://arxiv.org/pdf/1907.06291.pdf). July 2019. University of Edinburgh
- [A Divide-and-Conquer Approach Towards Understanding Deep Networks](https://arxiv.org/pdf/1907.06194.pdf). July 2019.  Friedrich-Alexander University Erlangen-Nurnberg, Erlangen Graduate School in Advanced Optical Technologies
- [FoodX-251: A Dataset for Fine-grained Food Classification](https://arxiv.org/pdf/1907.06167.pdf). July 2019. SRI International, Google, Cornell Tech. 251 categories, 118k training images.
- [Clustering Activity-Travel Behavior Time Series using Topological Data Analysis](https://arxiv.org/pdf/1907.07603.pdf). July 2019. University of Connecticut
- [News Cover Assessment via Multi-task Learning](https://arxiv.org/pdf/1907.07581.pdf). July 2019. Tencent.
- [A Survey on Explainable Artificial Intelligence (XAI): towards Medical XAI](https://arxiv.org/pdf/1907.07374.pdf). July 2019. Unknown affiliation
- [Probing Neural Network Comprehension of Natural Language Arguments](https://arxiv.org/pdf/1907.07355.pdf). July 2019. National Cheng Kung University (Taiwan)
- [Fake News Detection as Natural Language Inference](https://arxiv.org/pdf/1907.07347.pdf). July 2019. National Cheng Kung University (Taiwan)
- [How much real data do we actually need: Analyzing object detection performance using synthetic and real data](https://arxiv.org/pdf/1907.07061.pdf). July 2019. ICML Workshop on AI for Autonomous Driving 2019. Sensor Cortek Inc., University of Ottawa, Valeo AI
- [A Unified Deep Framework for Joint 3D Pose Estimation and Action Recognition from a Single RGB Camera](https://arxiv.org/pdf/1907.06968.pdf). July 2019. Cerema Research Center (France), Informatics Research Institute of Toulouse, Aparnix (Chile), Cortexica Vision Systems Ltd. (London), Vingroup Big Data Institute (Vietnam)
- [Cascade RetinaNet: Maintaining Consistency for Single-Stage Object Detection](https://arxiv.org/pdf/1907.06881.pdf). July 2019. CAS, University of Chinese Academy of Sciences, CAS Center for Excellence in Brain Science and Intelligence Technology
- [Separable Convolutional LSTMs for Faster Video Segmentation](https://arxiv.org/pdf/1907.06876.pdf). July 2019.  Ulm University.
- [Multi-scale Graph-based Grading for Alzheimer’s Disease Prediction](https://arxiv.org/pdf/1907.06625.pdf). July 2019. Univ. Bordeaux, Universitat Politècnia de València
- [The Many AI Challenges of Hearthstone](https://arxiv.org/pdf/1907.06562.pdf). July 2019. New Jersey Institute of Technology, NYU
- [Asking Clarifying Questions in Open-Domain Information-Seeking Conversations](https://arxiv.org/pdf/1907.06554.pdf). July 2019. Università della Svizzera italiana (USI), UMass Amherst
- [Federated Reinforcement Distillation with Proxy Experience Memory](https://arxiv.org/pdf/1907.06536.pdf). July 2019. Yonsei University, University of Oulu. RL learn from experience while preserving the privacy of actual experiences
- [Sequence Level Semantics Aggregation for Video Object Detection](https://arxiv.org/pdf/1907.06390.pdf). July 2019. McGill University, TuSimple, University of Chinese Academy of Sciences, CASIA, CAS
- [Exploring Deep Anomaly Detection Methods Based on Capsule Net](https://arxiv.org/pdf/1907.06312.pdf). July 2019. University of Ottawa, Queen's University, National Research Council Canada
- [AUTOMATIC REPAIR AND TYPE BINDING OF UNDECLARED VARIABLES USING NEURAL NETWORKS](https://arxiv.org/pdf/1907.06205.pdf). July 2019. Iowa State University
- [Towards Generation of Visual Attention Map for Source Code](https://arxiv.org/pdf/1907.06182.pdf). July 2019. Nara Institute of Science and Technology,
- [ALFA: Agglomerative Late Fusion Algorithm for Object Detection](https://arxiv.org/pdf/1907.06067.pdf). July 2019. Kazan Federal University (Russia), Czech Technical University in Prague. "agglomerative clustering of object detector predictions" (runs on top of multiple detectors, e.g. SSD and Faster R-CNN)
- [Bringing Giant Neural Networks Down to Earth with Unlabeled Data](https://arxiv.org/pdf/1907.06065.pdf). July 2019. Peking University, SenseTime, The University of Sydney
- [M3D-RPN: Monocular 3D Region Proposal Network for Object Detection](https://arxiv.org/pdf/1907.06038.pdf). July 2019. Michigan State University. [HighPri]
- [Motion Planning Networks: Bridging the Gap Between Learning-based and Classical Motion Planners](https://arxiv.org/pdf/1907.06013.pdf). July 2019. UC San Diego
- [Sparse Networks from Scratch: Faster Training without Losing Performance](https://arxiv.org/pdf/1907.04840.pdf). July 2019. UWashington
- [Adversarial Objects Against LiDAR-Based Autonomous Driving Systems](https://arxiv.org/pdf/1907.05418.pdf). July 2019. University of Michigan, Baidu, University of Illinois at Urbana-Champaign
- [R-TRANSFORMER: RECURRENT NEURAL NETWORK ENHANCED TRANSFORMER](https://arxiv.org/pdf/1907.05572.pdf). July 2019. Michigan State University, TAL Education Group [HighPri]
- [Understanding Neural Networks via Feature Visualization: A survey](https://arxiv.org/pdf/1904.08939.pdf). Apr 2019. Auburn University, Uber AI Labs, University of Wyoming. [HighPri]
- [Neuroscore: A Brain-inspired Evaluation Metric for Generative Adversarial Networks](https://arxiv.org/pdf/1905.04243.pdf). May 2019. Dublin City University, Intel. 
- [EdgeSegNet: A Compact Network for Semantic Segmentation](https://arxiv.org/pdf/1905.04222.pdf). May 2019. ICML 2019. University of Waterloo, DarwinAI Corp., Waterloo Artificial Intelligence Institute. "EdgeSegNet is well-suited for low-power edge scenarios"
- [Learning to Parse Wireframes in Images of Man-Made Environments](https://faculty.ist.psu.edu/zzhou/paper/CVPR18-Wireframe.pdf). CVPR 2018. ShanghaiTech University, The Pennsylvania State University, UC Berkeley. "The wireframe (see Fig. 1) contains all salient straight lines and their junctions of the scene that encode efficiently and accurately large-scale geometry and object shapes."
- [End-to-End Wireframe Parsing](https://arxiv.org/pdf/1905.03246.pdf). May 2019. UC Berkeley.
- [Learning to Reconstruct 3D Manhattan Wireframes from a Single Image](https://arxiv.org/pdf/1905.07482.pdf). May 2019. UC Berkeley, Adobe Research
- [UNDERSTANDING ATTENTION IN GRAPH NEURAL NETWORKS](https://arxiv.org/pdf/1905.02850.pdf). May 2019. ICLR 2019 Workshop on Representation Learning on Graphs and Manifolds. University of Guelph, Vector Institute for Artificial Intelligence, Canada CIFAR AI Chair
- [MULTIMODAL SEMANTIC ATTENTION NETWORK FOR VIDEO CAPTIONING](https://arxiv.org/pdf/1905.02963.pdf). May 2019. University of Science and Technology of China, CAS, CAS Center for Excellence in Brain Science and Intelligence Technology





















