---
title: "PASTS: Progress-Aware Spatio-Temporal Transformer Speaker For Vision-and-
Language Navigation"
collection: publications
permalink: /publication/pasts
excerpt: 'Liuyi Wang, Chengju Liu, Zongtao He, Shu Li, Qingqing Yan, Huiyi Chen, Qijun Chen'
date: 2023-11-09
venue: 'Engineering Applications of Artificial Intelligence'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0952197623016718'
citation: ''
---

Vision-and-language navigation (VLN) is a crucial but challenging cross-modal navigation task. One powerful technique to enhance the generalization performance in VLN is the use of an independent speaker model to provide pseudo instructions for data augmentation. However, current speaker models based on Long-Short Term Memory (LSTM) lack the ability to attend to features relevant at different locations and time steps. To address this, we propose a novel progress-aware spatio-temporal transformer speaker (PASTS) model that uses the transformer as the core of the network. PASTS uses a spatio-temporal encoder to fuse panoramic representations and encode intermediate connections through steps. Besides, to avoid the misalignment problem that could result in incorrect supervision, a speaker progress monitor (SPM) is proposed to enable the model to estimate the progress of instruction generation and facilitate more fine-grained caption results. Additionally, a multifeature dropout (MFD) strategy is introduced to alleviate overfitting. The proposed PASTS is flexible to be combined with existing VLN models. The experimental results demonstrate that PASTS outperforms previous speaker models and successfully improves the performance of previous VLN models, achieving state-of-the-art performance on the standard Room-to-Room (R2R) dataset.
