---
title:          "TopoLayer: A Universal Neural Network Layer for Advanced Topology Feature Learning on Point Clouds using Persistent Homology"
date:           2025-03-21 00:01:00 +0800
selected:       true
#pub:            ""
#pub_pre:        ""
pub_post:       'Accepted to ICME'
#pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  Point cloud is complex 3D data characterized by its irregularity and unordered structure. In contrast to previous efforts aimed at extracting local geometric information by sophisticated techniques, we delve into the rich topological information of point clouds using persistent homology. First, we introduce two vectorization methods, PPDTF and PDTF, to transform topological information into a format suitable for deep neural networks. Then we propose TopoLayer, a simple but effective and universal neural network layer seamlessly integrated into existing architectures. Integration of TopoLayer, without architectural modifications, significantly improves established models such as PointMLP and PointNet++. For classification on ModelNet40, the class mean accuracy of PointMLP notably improves from 91.3% to 91.8%, surpassing the state-of-the-art PointMixer. Additionally, PointNet++ achieves a remarkable gain of 2.7%. For part segmentation on ShapeNetPart, PointMLP achieves a new state-of-the-art performance with 85.1% Cls.mIoU, while PointNet++ secures a significant 0.9% increase.
cover:  assets/images/covers/2025-TopoLayer.PNG
authors:
  - Zechao Guan
  - Shuai Du
  - Qingshan Liu#

links:
# Paper: https://arxiv.org/abs/2409.19527
  Code: https://github.com/Zechao-Guan/TopoLayer
#   Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
