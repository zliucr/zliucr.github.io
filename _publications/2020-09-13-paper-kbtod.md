---
title: "Learning Knowledge Bases with Parameters for Task-Oriented Dialogue Systems"
collection: publications
permalink: /publication/2020-9-13-paper-kbtod
excerpt: ''
date: 2020-9-13
venue: 'Findings of EMNLP-2020'
paperurl: ''
authors: 'Andrea Madotto, Samuel Cahyawijaya, Genta Indra Winata, Yan Xu, <span style="color: #0779e4"><b>Zihan Liu</b></span>, Zhaojiang Lin, Pascale Fung'
paper: https://arxiv.org/pdf/2009.13656.pdf
code: https://github.com/HLTCHKUST/ke-dialogue
citation: ''
---
Task-oriented dialogue systems are either modularized with separate dialogue state tracking (DST) and management steps or end-to-end trainable. In either case, the knowledge base (KB) plays an essential role in fulfilling user requests. Modularized systems rely on DST to interact with the KB, which is expensive in terms of annotation and inference time. End-to-end systems use the KB directly as input, but they cannot scale when the KB is larger than a few hundred entries. In this paper, we propose a method to embed the KB, of any size, directly into the model parameters. The resulting model does not require any DST or template responses, nor the KB as input, and it can dynamically update its KB via fine-tuning. We evaluate our solution in five task-oriented dialogue datasets with small, medium, and large KB size. Our experiments show that end-to-end models can effectively embed knowledge bases in their parameters and achieve competitive performance in all evaluated datasets.

