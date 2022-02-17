# Discovering-Sentimental-Interaction-via-Graph-Convolutional-Network-for-Visual-Sentiment-Prediction

## Introduction
This paper addresses the problem of visual sentiment analysis based on graph convolutional networks and convolutional neural networks. Inspired by the principles of human emotion and observation, we find that each type of interaction among objects in the image has an essential impact on sentiment. We present a framework that consists of two branches for sentimental interaction representations learning. First of all, we design an algorithm to build a graph model on popular affective datasets without category information annotated based on panoptic segmentation information. As an essential part of the graph model, we define the objects in the images as nodes and calculate the edges between nodes in the graph model according to sentimental value of each objects. According to the effect of brightness on sentiment, we select brightness and texture features as node features. A stacked GCN model is used to generate the relational features describing the interaction results of objects and integrate them with the visual features extracted by VGGNet to realize the classification of image sentiment. Experimental results show the effectiveness of our method on five popular datasets. Furthermore, making more effective utilizing of objects interaction information remains a challenging problem.

## Prerequisites
- Python 3.6
- PyTorch ≥ 1.2.0
- CUDA 10.0

## Installation
- Original datasets ([Download URL](https://pan.baidu.com/s/1bZ8BgtwrHhKahWXsL9kfWA), Extraction code: ba6o)
- Code (To be uploaded)

## Citation
```
@article{wu2021discovering,
  title={Discovering Sentimental Interaction via Graph Convolutional Network for Visual Sentiment Prediction},
  author={Wu, Lifang and Zhang, Heng and Deng, Sinuo and Shi, Ge and Liu, Xu},
  journal={Applied Sciences},
  volume={11},
  number={4},
  pages={1404},
  year={2021},
  publisher={Multidisciplinary Digital Publishing Institute}
}
```
