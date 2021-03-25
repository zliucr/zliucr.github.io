---
title: "Multimodal End-to-End Sparse Model for Emotion Recognition"
collection: publications
permalink: /publication/2021-03-22-paper-multimodal
excerpt: ''
date: 2021-03-22
venue: 'NAACL-2021'
paperurl: ''
authors: 'Wenliang Dai, Samuel Cahyawijaya, <span style="color: #0779e4"><b>Zihan Liu</b></span>, Pascale Fung'
paper: https://arxiv.org/pdf/2103.09666
code: https://github.com/wenliangdai/Multimodal-End2end-Sparse
citation: ''
---
Existing works on multimodal affective computing tasks, such as emotion recognition, generally adopt a two-phase pipeline, first extracting feature representations for each single modality with hand-crafted algorithms and then performing end-to-end learning with the extracted features. However, the extracted features are fixed and cannot be further fine-tuned on different target tasks, and manually finding feature extraction algorithms does not generalize or scale well to different tasks, which can lead to sub-optimal performance. In this paper, we develop a fully end-to-end model that connects the two phases and optimizes them jointly. In addition, we restructure the current datasets to enable the fully end-to-end training. Furthermore, to reduce the computational overhead brought by the end-to-end model, we introduce a sparse cross-modal attention mechanism for the feature extraction. Experimental results show that our fully end-to-end model significantly surpasses the current state-of-the-art models based on the two-phase pipeline. Moreover, by adding the sparse cross-modal attention, our model can maintain performance with around half the computation in the feature extraction part.

