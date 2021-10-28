# Archive

## 通用物体检测

通过物体检测是指多个类别物体检测，通常用的数据集有pascal voc/coco/object 365

物体检测性能提升，一般主要通过数据增强、改进Backbone、改进FPN、改进检测头、改进loss、改进后处理等6个常用手段

### generalized object detection

* [2021] Dynamic Head: Unifying Object Detection Heads with Attentions
* [2021] End to End Object Detection with Fully Convolutional Network
* [2021] Anchor DETR: Query Design for Transformer-Based Detector
* [2021] Conditional DETR for Fast Training Convergence
* [2021] Deformable DETR: Deformable  Transformers for End-to-End Object Detection
* [2021] Fast Convergence of DETR with Spatially Modulated Co-Attention
* [2021] Centernetv2: Probabilistic two-stage detection
* [2020] RelationNet++: Bridging Visual Representations for Object Detection via Transformer Decoder
* [2020] End-to-End Object Detection with Transformers
* [2019] FCOS: Fully Convolutional One-Stage Object Detection
* [2019] Objects as Points
* [2018] Relation Networks for Object Detection
* [2018] CornerNet: Detecting Objects as Paired Keypoints
* [2018] Focal Loss for Dense Object Detection
* [2017] Cascade R-CNN Delving into High Quality Object Detection
* [2015] Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks
* [2015] Fast R-CNN
* [2014] Spatial Pyramid Pooling in Deep Convolutional Networks for Visual Recognition
* [2014] Rich feature hierarchies for accurate object detection and semantic segmentation

### backbone
[已看]

* [2021] Swin Transformer: Hierarchical Vision Transformer using Shifted Windows
* [2021] An Image Is Worth 16X16 Words: Transformer For Image Recognition At Scale
* [2015] Deep Residual Learning for Image Recognition
------------------------------------------------------------------------------------------
[未看]
* ECA Net Efficient Channel Attention for Deep Convolutional Neural Networks
* CSWin Transformer A General Vision Transformer Backbone with Cross-Shaped Windows
* CROSSFORMER a versatile vision transformer based on cross-scale attention

### nick-fpn

* [2021] You Only Look One-level Feature
* [2021] GraphFPN: Graph Feature Pyramid Network for Object Detection
* [2020] DetectoRS: Detecting Objects with Recursive Feature Pyramid and Switchable Atrous Convolution
* [2020] Feature Pyramid Transformer
* [2020] Feature Pyramid Grids
* [2020] EfficientDet: Scalable and Efficient Object Detection
* [2019] Learning Spatial Fusion for Single-Shot Object Detection
* [2019] NAS-FPN: Learning Scalable Feature Pyramid Architecture for Object Detection
* [2019] Auto-FPN: Automatic Network Architecture Adaptation for Object Detection Beyond Classification
* [2019] Libra R-CNN: Towards Balanced Learning for Object Detection(Balanced Feature Pyramids)
* [2019] CARAFE Content-Aware ReAssembly of FEatures
* [2018] Path Aggregation Network for Instance Segmentation
* [2017] Beyond Skip Connections: Top-Down Modulation for Object Detection
* [2017] Feature Pyramid Networks for Object Detection

### long-tailed

* [2021] Adaptive Class Suppression Loss for Long-Tail Object Detection
* [2021] Seesaw Loss for Long-Tailed Instance Segmentation
* [2020] Equalization loss for long-tailed object recognition

### sample imbalance

* [2020] Generalized Focal Loss V2 Learning Reliable Localization Quality Estimation for Dense Object Detection
* [2019] Libra R-CNN: Towards Balanced Learning for Object Detection
* [2018] Focal Loss for Dense Object Detection

### label assignment

* [2021] LLA: Loss-aware Label Assignment for Dense Pedestrian Detection
* [2021] OTA: Optimal Transport Assignment for Object Detection
* [2020] Dynamic R-CNN: Towards High Quality Object Detection via Dynamic Training
* [2020] FoveaBox Beyound Anchor-Based Object Detection.pdf
* [2020] AutoAssign: Differentiable Label Assignment for Dense Object Detection
* [2020] ATSS：Bridging the Gap Between Anchor-based and Anchor-free Detection via Adaptive Training Sample Selection
* [2020] Probabilistic Anchor Assignment with IoU Prediction for Object Detection
* [2019] FreeAnchor: Learning to Match Anchors for Visual Object Detection
* [2019] Feature Selective Anchor-Free Module for Single-Shot Object Detection
* [2015] What makes for effective detection proposals?

### dense detection

* [2021] VarifocalNet: An IoU-aware Dense Object Detector
* [2021] IterDet: Iterative Scheme for Object Detection in Crowded Environments(密集行人检测)
* [2020] Detection in Crowded Scenes: One Proposal, Multiple Predictions(密集行人检测)
* [2020] PS-RCNN_Detecting_Secondary_Human_Instances_in_a_Crowd_via_Primary_Object_Suppression(密集行人检测)
* [2020] NMS by Representative Region: Towards Crowded Pedestrian Detection by Proposal Pairing(密集行人检测)
* [2020] Repulsion Loss: Detecting Pedestrians in a Crowd(密集行人检测)

### small scale detection

### task misalignment

* [2021] TOOD: Task-aligned One-stage Object Detection
* [2020] Localize to Classify and Classify to Localize: Mutual Guidance in Object Detection
* [2020] Revisiting the Sibling Head in Object Detector
* [2018] Learning Region Features for Object Detection

### 后处理：nms

* [2021] What Makes for End-to-End Object Detection?
* [2021] WBF: Weighted boxes fusion: Ensembling boxes from different object detection models
* [2020] NMS by Representative Region: Towards Crowded Pedestrian Detection by Proposal Pairing(密集行人检测)
* [2017] soft-nms: Improving Object Detection With One Line of Code
* [2017] CAD: Scale Invariant Framework for Real-Time Object Detection

### data augmentation

* [2020] Simple Copy-Paste is a Strong Data Augmentation Method for Instance Segmentation

### unsupervised

* [2021] UP-DETR: Unsupervised Pre-training for Object Detection with Transformers
* [2021] DetCo: Unsupervised Contrastive Learning for Object Detection

### semi-supervised

* [2021] End-to-End Semi-supervised Object Detection with Soft Teacher
* [2021] Instant teaching An End to End semi-supervised object detection framework
* [2021] unbiased teacher for semi-supervised object detection

### self-supervised

* [2021] Self-EMD Self-Supervised Object Detection without ImageNet

### Active learning

* [2021] Consistency-based Active Learning for Object Detection
* [2021] Active Learning for Deep Object Detection via Probalilistic Modeling

### Meta Learning-Few-Shot Learning

* [2021] Meta-DETR: Few-Shot Object Detection via Unified Image-Level Meta-Learning
* [2020] Incremental_Few-Shot_Object_Detection_CVPR_2020_paper
* [2020] Few-shot Object Detection with Attention-RPN and Mullti-Relation Detector
* [2020] Few-shot Object Detection and Viewpoint Estimation for Objects in the Wild
* [2020] Cooperating_RPNs_Improve_Few-Shot_Object_Detectio
* [2020] Frustratingly Simple Few-Shot Object Detection
* [2020] Multi-Scale Positive Sample Refinement for Few-Shot Object Detection
* [2020] Meta-Rcnn Meta Learning for few-shot Object detection
* [2019] Few-shot Object Detection via Feature Reweighting
* [2019] Meta-Learning_to_Detect_Rare_Objects_ICCV_2019_paper
* [2019] Meta_R-CNN_Towards_General_Solver_for_Instance-Level_Low-Shot_Learning_ICCV_2019_paper
* [2018] LSTD: A Low-Shot Transfer Detector for Object Detection

### Self-distillation

* [2021] LGD Label-guided Self-distillation for Object Detection

### Continual Learning/Lifelong Learning

* [2021] Towards_Open_World_Object_Detection_CVPR_2021_paper

### yolo

* [2021] YOLOX: Exceeding YOLO Series in 2021
* [2021] Scaled-YOLOv4: Scaling Cross Stage Partial Network
* [2020] YOLOv4: Optimal Speed and Accuracy of Object Detection
* [2019] YOLO Nano: a Highly Compact You Only Look Once Convolutional Neural Network for Object Detection
* [2018] YOLOv3: An Incremental Improvement
* [2016] YOLOV2: YOLO9000: Better, Faster, Stronger
* [2016] YOLOV1: You Only Look Once:Unified, Real-Time Object Detection

### 多模态

* [2021] MDETR - Modulated Detection for End-to-End Multi-Modal Understanding

---
