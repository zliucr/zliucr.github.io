---
title: "AdaptSum: Towards Low-Resource Domain Adaptation for Abstractive Summarization"
collection: publications
permalink: /publication/2021-03-25-paper-adaptsum
excerpt: ''
date: 2021-03-25
venue: 'NAACL-2021'
paperurl: ''
authors: '<span style="color: #0779e4"><b>Zihan Liu*</b></span>, Tiezheng Yu*, Pascale Fung'
paper: https://arxiv.org/pdf/2103.11332
code: https://github.com/TysonYu/AdaptSum
citation: ''
---
State-of-the-art abstractive summarization models generally rely on extensive labeled data, which lowers their generalization ability on domains where such data are not available. In this paper, we present a study of domain adaptation for the abstractive summarization task across six diverse target domains in a low-resource setting. Specifically, we investigate the second phase of pre-training on large-scale generative models under three different settings: 1) source domain pre-training; 2) domain-adaptive pre-training; and 3) task-adaptive pre-training. Experiments show that the effectiveness of pre-training is correlated with the similarity between the pre-training data and the target domain task. Moreover, we find that continuing pre-training could lead to the pre-trained model's catastrophic forgetting, and a learning method with less forgetting can alleviate this issue. Furthermore, results illustrate that a huge gap still exists between the low-resource and high-resource settings, which highlights the need for more advanced domain adaptation methods for the abstractive summarization task.
