---
title: "/data/ssd0/w61/CrystalSixone.github.io/_publications/doa copy.md"
collection: publications
permalink: /publication/res-sts
excerpt: '**Wang, Liuyi** and He, Zongtao and Dang, Ronghao and Chen, Huiyi and Liu, Chengju and Chen, Qijun'
date: 2023-07-17
venue: 'IEEE Transactions on Circuits and Systems for Video Technology'
paperurl: 'https://ieeexplore.ieee.org/document/10004992'
citation: ''
---

It is a rather practical but difficult task to find a specified target object via autonomous exploration based on natural language descriptions in an unstructured environment. Since the human-annotated data is expensive to gather for the goal-oriented vision-language navigation (GVLN) task, the size of the standard dataset is inadequate, which has significantly limited the accuracy of previous techniques. In this work, we aim to improve the robustness and generalization of the navigator by dynamically providing high-quality pseudo-instructions using a proposed RES-StS paradigm. Specifically, we establish a referring expression speaker (RES) to predict descriptive instructions for the given path to the goal object. Based on an environment-and-object fusion (EOF) module, RES derives spatial representations from the input trajectories, which are subsequently encoded by a number of transformer layers. Additionally, given that the quality of the pseudo labels is important for data augmentation while the limited dataset may also hinder RES learning, we propose to equip RES with a more effective generation ability by using the self-training approach. A trajectory-instruction matching scorer (TIMS) network based on contrastive learning is proposed to selectively use rehearsal of prior knowledge. Finally, all network modules in the system are integrated by suggesting a multi-stage training strategy, allowing them to assist one another and thus enhance performance on the GVLN task. Experimental results demonstrate the effectiveness of our approach. Compared with the SOTA methods, our method improves SR, SPL, and RGS by 4.72%, 2.55%, and 3.45% respectively, on the REVERIE dataset, and 4.58%, 3.75% and 3.14% respectively, on the SOON dataset.
