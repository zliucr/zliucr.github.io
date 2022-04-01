---
title: "Multi-Stage Prompting for Knowledgeable Dialogue Generation"
collection: publications
permalink: /publication/2022-03-15-paper-msdp
excerpt: ''
date: 2022-03-15
venue: 'Findings of ACL 2022'
paperurl: ''
authors: '<span style="color: #0779e4"><b>Zihan Liu</b></span>, Mostofa Patwary, Ryan Prenger, Shrimai Prabhumoye, Wei Ping, Mohammad Shoeybi, Bryan Catanzaro'
code: 'https://github.com/NVIDIA/Megatron-LM'
paper: 'https://arxiv.org/pdf/2203.08745.pdf'
citation: ''
---
Existing knowledge-grounded dialogue systems typically use finetuned versions of a pretrained language model (LM) and large-scale knowledge bases. These models typically fail to generalize on topics outside of the knowledge base, and require maintaining separate potentially large checkpoints each time finetuning is needed. In this paper, we aim to address these limitations by leveraging the inherent knowledge stored in the pretrained LM as well as its powerful generation ability. We propose a multi-stage prompting approach to generate knowledgeable responses from a single pretrained LM. We first prompt the LM to generate knowledge based on the dialogue context. Then, we further prompt it to generate responses based on the dialogue context and the previously generated knowledge. Results show that our knowledge generator outperforms the state-of-theart retrieval-based model by 5.8% when combining knowledge relevance and correctness. In addition, our multi-stage prompting outperforms the finetuning-based dialogue model in terms of response knowledgeability and engagement by up to 10% and 5%, respectively. Furthermore, we scale our model up to 530 billion parameters and show that larger LMs improve the generation correctness score by up to 10%, and response relevance, knowledgeability and engagement by up to 10%.

[Paper PDF](https://arxiv.org/pdf/2203.08745.pdf)
