---
title: "Unbiased Directed Object Attention Graph for Object Navigation"
collection: publications
permalink: /publication/doa
excerpt: 'Dang, Ronghao and Shi, Zhuofan and **Wang, Liuyi** and He, Zongtao and Liu, Chengju and Chen, Qijun'
date: 2022-02-17
venue: 'Proceedings of the 30th ACM International Conference on Multimedia'
paperurl: 'https://arxiv.org/abs/2204.04421'
citation: ''
---

Object navigation tasks require agents to locate specific objects in unknown environments based on visual information. Previously, graph convolutions were used to implicitly explore the relationships between objects. However, due to differences in visibility among objects, it is easy to generate biases in object attention. Thus, in this paper, we propose a directed object attention (DOA) graph to guide the agent in explicitly learning the attention relationships between objects, thereby reducing the object attention bias. In particular, we use the DOA graph to perform unbiased adaptive object attention (UAOA) on the object features and unbiased adaptive image attention (UAIA) on the raw images, respectively. To distinguish features in different branches, a concise adaptive branch energy distribution (ABED) method is proposed. We assess our methods on the AI2-Thor dataset. Compared with the state-of-the-art (SOTA) method, our method reports 7.4%, 8.1% and 17.6% increase in success rate (SR), success weighted by path length (SPL) and success weighted by action efficiency (SAE), respectively.
