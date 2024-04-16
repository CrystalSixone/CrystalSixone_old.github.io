---
title: "HoloParser: Holistic Visual Parsing for Real-time Semantic Segmentation in Autonomous Driving"
collection: publications
permalink: /publication/holoParser
excerpt: 'Li, Shu and Yan, Qingqing and Shi, Wenbo and **Wang, Liuyi** and Liu, Chengju and Chen, Qijun'
date: 2022-01-17
venue: 'IEEE Transactions on Instrumentation and Measurement'
paperurl: 'https://ieeexplore.ieee.org/document/9963573'
citation: ''
---

Existing real-time semantic segmentation models usually pursue lower inference costs by compressing spatial resolution, reducing the number of feature extraction layers, or simplifying the high-resolution generation process. This inevitably leads to huge information loss and ultimately affects segmentation accuracy. To address the problem, a HoloParser is proposed to learn and parse the input image from a holistic perspective of the entire segmentation pipeline. First, in the image preprocessing part, the often-overlooked problem of structural information loss in fast downsampling is highlighted and studied. For this, a nonstrided fast downsampling (NFD) module is devised for holo-structure retention. Second, for the resolution change processes in segmentation networks, the spatial correlation between up/down-samplings is revisited and focused. And a lossless sample pair (LSP) is proposed for holo-correlation modeling and retrieving. Third, in feature extraction, after reconsidering the necessity and redundancy of multiscale learning, a distributed pyramid learning (DPL) module is proposed for lightweight holo-feature extraction with composite receptive fields (RFs). Finally, for the high-resolution output generation, a parallel resolution maintenance (PRM) module is put forward via high-low semantics aggregation across stages for holo-semantics utilization. Extensive experiments demonstrate the effectiveness and superiority of the proposed modules. The HoloParser achieves state-of-the-art performance in real-time semantic segmentation, which reports 76.45% mIoU at 280+ frames/s on the Cityscapes dataset.
