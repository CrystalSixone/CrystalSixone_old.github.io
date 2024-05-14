---
title: "Causality-based Cross-Modal Representation Learning for Vision-and-Language Navigation"
collection: publications
permalink: /publication/causalVLN
excerpt: '**Liuyi Wang**, Zongtao He, Ronghao Dang, Huiyi Chen, Chengju Liu, Qijun Chen'
date: 2024-03-06
venue: 'Arxiv'
paperurl: 'https://arxiv.org/pdf/2403.03405'
citation: ''
---

Vision-and-Language Navigation (VLN) has gained significant research interest in recent years due to its potential applications in real-world scenarios. However, existing VLN methods struggle with the issue of spurious associations, resulting in poor generalization with a significant performance gap between seen and unseen environments. In this paper, we tackle this challenge by proposing a unified framework CausalVLN based on the causal learning paradigm to train a robust navigator capable of learning unbiased feature representations. Specifically, we establish reasonable assumptions about confounders for vision and language in VLN using the structured causal model (SCM). Building upon this, we propose an iterative backdoor-based representation learning (IBRL) method that allows for the adaptive and effective intervention on confounders. Furthermore, we introduce the visual and linguistic backdoor causal encoders to enable unbiased feature expression for multi-modalities during training and validation, enhancing the agent's capability to generalize across different environments. Experiments on three VLN datasets (R2R, RxR, and REVERIE) showcase the superiority of our proposed method over previous state-of-the-art approaches. Moreover, detailed visualization analysis demonstrates the effectiveness of CausalVLN in significantly narrowing down the performance gap between seen and unseen environments, underscoring its strong generalization capability.
