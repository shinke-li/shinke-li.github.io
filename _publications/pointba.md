---
title: "PointBA: Towards Backdoor Attacks in 3D Point Cloud"
collection: publications
permalink: /publication/pointba
excerpt: ''
date: 2021-07-22
venue: 'ICCV'
paperurl: ''
citation: 'Xinke Li, Zhirui Chen, Yue Zhao, Zekun Tong, Yabang Zhao, Andrew Lim, Joey Tianyi Zhou (2021). &quot;PointBA: Towards Backdoor Attacks in 3D Point Cloud.&quot; <i>IEEE International Conference on Computer Vision</i>.'
---
[paper](https://arxiv.org/pdf/2103.16074)
## Abstract
3D deep learning has been increasingly more popular for a variety of tasks including many safety-critical applications. However, recently several works raise the security issues of 3D deep models. Although most of them consider adversarial attacks, we identify that backdoor attack is indeed a more serious threat to 3D deep learning systems but remains unexplored. We present the backdoor attacks in 3D point cloud with a unified framework that exploits the unique properties of 3D data and networks. In particular, we design two attack approaches on point cloud: the poison-label backdoor attack (PointPBA) and the clean-label backdoor attack (PointCBA). The first one is straightforward and effective in practice, while the latter is more sophisticated assuming there are certain data inspections. The attack algorithms are mainly motivated and developed by 1) the recent discovery of 3D adversarial samples suggesting the vulnerability of deep models under spatial transformation; 2) the proposed feature disentanglement technique that manipulates the feature of the data through optimization methods and its potential to embed a new task. Extensive experiments show the efficacy of the PointPBA with over 95% success rate across various 3D datasets and models, and the more stealthy PointCBA with around 50% success rate. Our proposed backdoor attack in 3D point cloud is expected to perform as a baseline for improving the robustness of 3D deep models.