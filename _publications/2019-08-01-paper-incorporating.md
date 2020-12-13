---
title: "Incorporating Word and Subword Units in Unsupervised Machine Translation Using Language Model Rescoring"
collection: publications
permalink: /publication/2019-08-01-paper-incorporating
excerpt: ''
date: 2019-08-01
venue: 'Proceedings of the Fourth Conference on Machine Translation (WMT-2019) in conjunction with ACL'
paperurl: ''
authors: '<span style="color: #0779e4"><b>Zihan Liu*</b></span>, Yan Xu*, Genta Indra Winata and Pascale Fung '
paper: http://www.statmt.org/wmt19/pdf/WMT0027.pdf
citation: ''
---
This paper describes CAiRE’s submission to the unsupervised machine translation track ofthe WMT’19 news shared task from Germanto Czech. We leverage a phrase-based statistical machine translation (PBSMT) modeland a pre-trained language model to combine word-level neural machine translation (NMT) and subword-level NMT models without using any parallel data. We propose to solve the morphological richness problem of languages by training byte-pair encoding (BPE) embeddings for German and Czech separately, and they are aligned using MUSE (Conneau et al., 2018). To ensure the fluency and consistency of translations, a rescoring mechanism is proposed that reuses the pre-trained language model to select the translation candidates generated through beam search. Moreover, a series of pre-processing and post-processing approaches are applied to improve the quality of final translations.

[Paper PDF](http://www.statmt.org/wmt19/pdf/WMT0027.pdf)

Recommended citation: Liu, Z., Xu, Y., Winata, G. I., & Fung, P. (2019). Incorporating Word and Subword Units in Unsupervised Machine Translation Using Language Model Rescoring. Proceedings of the Fourth Conference on Machine Translation.