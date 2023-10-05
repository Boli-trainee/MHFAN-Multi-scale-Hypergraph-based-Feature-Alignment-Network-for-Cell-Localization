# MHFAN-Multi-scale-Hypergraph-based-Feature-Alignment-Network-for-Cell-Localization
The code of paper: Multi-scale Hypergraph-based Feature Alignment Network for Cell Localization


## Abstruct
Cell localization in medical pathology image analysis is a challenging task due to the significant variation in cell shape, size and color shades. Existing localization methods continue to tackle these challenges separately, frequently facing complications where these difficulties intersect and adversely impact model performance. In this paper, these challenges are first reframed as issues of feature misalignment between cell images and location maps, which are then collectively addressed. Specifically, we propose a feature alignment model based on a multi-scale hypergraph attention network. The model considers local regions in the feature map as nodes and utilizes a learnable similarity metric to construct hypergraphs at various scales. We then utilize a hypergraph convolutional network to aggregate the features associated with the nodes and achieve feature alignment between the cell images and location maps. Furthermore, we introduce a stepwise adaptive fusion module to fuse features at different levels effectively and adaptively. The comprehensive experimental results demonstrate the effectiveness of our proposed multi-scale hypergraph attention module in addressing the issue of feature misalignment, and our model achieves state-of-the-art performance across various cell localization datasets.

## Overview
![3](https://github.com/Boli-trainee/MHFAN-Model/assets/83391363/a2d6526a-4fce-4b46-850e-5b69a7f5a96a)

## Dataset reference
The data processing process refers to the paper:
```
@article{li2023exponential,
  title={Exponential Distance Transform Maps for Cell Localization},
  author={Li, Bo and Chen, Jie and Yi, Hang and Feng, Min and Yang, Yongquan and Bu, Hong},
  year={2023},
  publisher={TechRxiv}
}
```
