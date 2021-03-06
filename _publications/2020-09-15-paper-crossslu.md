---
title: "Cross-lingual Spoken Language Understanding with Regularized Representation Alignment"
collection: publications
permalink: /publication/2020-9-15-paper-crossslu
excerpt: ''
date: 2020-9-15
venue: 'EMNLP-2020'
paperurl: ''
authors: '<span style="color: #0779e4"><b>Zihan Liu</b></span>, Genta Indra Winata, Peng Xu, Zhaojiang Lin, Pascale Fung'
paper: https://arxiv.org/pdf/2009.14510.pdf
code: https://github.com/zliucr/crosslingual-slu
citation: ''
---
Despite the promising results of current cross-lingual models for spoken language understanding systems, they still suffer from imperfect cross-lingual representation alignments between the source and target languages, which makes the performance sub-optimal. To cope with this issue, we propose a regularization approach to further align word-level and sentence-level representations across languages without any external resource. First, we regularize the representation of user utterances based on their corresponding labels. Second, we regularize the latent variable model (Liu et al. 2019) by leveraging adversarial training to disentangle the latent variables. Experiments on the cross-lingual spoken language understanding task show that our model outperforms current state-of-the-art methods in both few-shot and zero-shot scenarios, and our model, trained on a few-shot setting with only 3\% of the target language training data, achieves comparable performance to the supervised training with all the training data.

