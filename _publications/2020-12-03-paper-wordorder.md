---
title: "On the Importance of Word Order Information in Cross-lingual Sequence Labeling"
collection: publications
permalink: /publication/2020-12-03-paper-wordorder
excerpt: ''
date: 2020-12-03
venue: 'AAAI-2021'
paperurl: ''
authors: '<span style="color: #0779e4"><b>Zihan Liu</b></span>, Genta Indra Winata, Samuel Cahyawijaya, Andrea Madotto, Zhaojiang Lin, Pascale Fung'
paper: https://arxiv.org/abs/2001.11164
code:
citation: ''
---
Cross-lingual models trained on source language tasks possess the capability to transfer to target languages directly. However, since word order variances generally exist in different languages, cross-lingual models that overfit into the word order of the source language could have sub-optimal performance in target languages. In this paper, we hypothesize that reducing the word order information fitted into the models can improve the adaptation performance in target languages. To verify this hypothesis, we introduce several methods to make models encode less word order information of the source language and test them based on cross-lingual word embeddings and the pre-trained multilingual model. Experimental results on three sequence labeling tasks (i.e., part-of-speech tagging, named entity recognition, and slot filling tasks) show that reducing word order information injected into the model can achieve better zero-shot cross-lingual performance. Further analysis illustrates that fitting excessive or insufficient word order information into the model results in inferior cross-lingual performance. Moreover, our proposed methods can also be applied to strong cross-lingual models and further improve their performance.

