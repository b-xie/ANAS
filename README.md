# ANAS
ANAS: Asymptotic NAS for Large-scale Proxyless Search and Multi-task Transfer Learning

This repository contains the official implementation for our manuscript "ANAS: Asymptotic NAS for Large-scale Proxyless Search and Multi-task Transfer Learning".

## Introduction
Neural Architecture Search (NAS) is an excellent solution to design a lightweight network for researchers to obtain a trade-off between accuracy and speed, releasing researchers from the tedious mechanical trials. However, the main shortcoming of NAS is high and unstable memory consumption of the search work, especially for large-scale tasks. In this study, we proposed an Asymptotic Neural Architecture Search network (ANAS) that achieved a deep neural network search for large-scale tasks with the economical and stable memory consumption. ANAS reduced the peak value of memory consumption by an asymptotic way, kept the memory consumption stable by the linkage change of a series of key indexes, and used the pruning technique and efficient search candidate operations to decrease the total memory consumption, achieving the large-scale proxyless search and multi-task transfer tasks. We implemented multiple tasks (classification and segmentation) on multiple datasets (CIFAR10, CIFAR100, ImageNet, CamVid, and Cityscapes). The ANAS achieved a good trade-off between accuracy and speed.
