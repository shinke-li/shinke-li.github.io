---
title: "Digraph Inception Convolutional Networks"
collection: publications
permalink: /publication/DICN
excerpt: ''
date: 2020-12-06
venue: 'NeurIPS'
paperurl: ''
citation: 'Zekun Tong, Yuxuan Liang, Changsheng Sun, Xinke Li, David Rosenblum, Andrew Lim.'
#citation: 'Zekun Tong, Yuxuan Liang, Changsheng Sun, Xinke Li, David Rosenblum, Andrew Lim (2021). &quot;Digraph Inception Convolutional Networks.&quot; <i>Advances in Neural Information Processing Systems</i>, 33.'
---
[paper](https://proceedings.neurips.cc/paper/2020/file/cffb6e2288a630c2a787a64ccc67097c-Paper.pdf?ref=https://githubhelp.com)  [code](https://github.com/flyingtango/DiGCN)
## Abstract
Graph Convolutional Networks (GCNs) have shown promising results in modeling graph-structured data. However, they have difficulty with processing digraphs because of two reasons: 1) transforming directed to undirected graph to guarantee the symmetry of graph Laplacian is not reasonable since it not only misleads message passing scheme to aggregate incorrect weights but also deprives the unique characteristics of digraph structure; 2) due to the fixed receptive field in each layer, GCNs fail to obtain multi-scale features that can boost their performance. In this paper, we theoretically extend spectral-based graph convolution to digraphs and derive a simplified form using personalized PageRank. Specifically, we present the Digraph Inception Convolutional Networks (DiGCN) which utilizes digraph convolution and kth-order proximity to achieve larger receptive fields and learn multi-scale features in digraphs. We empirically show that DiGCN can encode more structural information from digraphs than GCNs and help achieve better performance when generalized to other models. Moreover, experiments on various benchmarks demonstrate its superiority against the state-of-the-art methods.
