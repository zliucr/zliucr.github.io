---
title: "Continual Mixed-Language Pre-Training for Extremely Low-Resource Neural Machine Translation"
collection: publications
permalink: /publication/2021-05-09-paper-cptnmt
excerpt: ''
date: 2021-05-09
venue: 'Findings of ACL 2021'
paperurl: ''
authors: '<span style="color: #0779e4"><b>Zihan Liu*</b></span>, Genta Indra Winata, Pascale Fung'
paper: https://arxiv.org/abs/2105.03953
code: https://github.com/zliucr/cpt-nmt
citation: ''
---
The data scarcity in low-resource languages has become a bottleneck to building robust neural machine translation systems. Fine-tuning a multilingual pre-trained model (e.g., mBART (Liu et al., 2020)) on the translation task is a good approach for low-resource languages; however, its performance will be greatly limited when there are unseen languages in the translation pairs. In this paper, we present a continual pre-training (CPT) framework on mBART to effectively adapt it to unseen languages. We first construct noisy mixed-language text from the monolingual corpus of the target language in the translation pair to cover both the source and target languages, and then, we continue pre-training mBART to reconstruct the original monolingual text. Results show that our method can consistently improve the fine-tuning performance upon the mBART baseline, as well as other strong baselines, across all tested low-resource translation pairs containing unseen languages. Furthermore, our approach also boosts the performance on translation pairs where both languages are seen in the original mBART's pre-training.

