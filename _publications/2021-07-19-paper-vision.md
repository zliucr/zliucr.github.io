---
title: "Vision Guided Generative Pre-trained Language Models for Multimodal Abstractive Summarization"
collection: publications
permalink: /publication/2021-07-19-paper-vision
excerpt: ''
date: 2021-07-19
venue: 'EMNLP 2021'
paperurl: ''
authors: 'Tiezheng Yu, Wenliang Dai, <span style="color: #0779e4"><b>Zihan Liu</b></span>, Pascale Fung'
paper: https://aclanthology.org/2021.emnlp-main.326.pdf
code: https://github.com/HLTCHKUST/VG-GPLMs
citation: ''
---
Multimodal abstractive summarization (MAS) models that summarize videos (vision modality) and their corresponding transcripts (text modality) are able to extract the essential information from massive multimodal data on the Internet. Recently, large-scale generative pre-trained language models (GPLMs) have been shown to be effective in text generation tasks. However, existing MAS models cannot leverage GPLMs' powerful generation ability. To fill this research gap, we aim to study two research questions: 1) how to inject visual information into GPLMs without hurting their generation ability; and 2) where is the optimal place in GPLMs to inject the visual information? In this paper, we present a simple yet effective method to construct vision guided (VG) GPLMs for the MAS task using attention-based add-on layers to incorporate visual information while maintaining their original text generation ability. Results show that our best model significantly surpasses the prior state-of-the-art model by 5.7 ROUGE-1, 5.3 ROUGE-2, and 5.1 ROUGE-L scores on the How2 dataset, and our visual guidance method contributes 83.6% of the overall improvement. Furthermore, we conduct thorough ablation studies to analyze the effectiveness of various modality fusion methods and fusion locations.

