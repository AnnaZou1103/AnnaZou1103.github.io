---
title: "ATTSUM: A Deep Attention-Based Summarization Model for Bug Report Title Generation"
collection: publications
permalink: /publication/2022-ATTSUM
excerpt: 'This paper is publishied on IEEE Transactions on Reliability.'
# date: 2022-08-02
# venue: 'IEEE Transactions on Reliability'
citation: 'X. Ma, J. W. Keung, X. Yu, <b>H. Zou</b>, J. Zhang and Y. Li, in IEEE Transactions on Reliability, 2023.'
---

<b>Keywords</b>: Text Summarization, Bug Reports, Title Generation, Transformers, Deep Learning

Concise and precise bug report titles help software developers to capture the highlights of the bug report quickly. Unfortunately, it is common that bug reporters do not create high-quality bug report titles. Recent LSTM-based Seq2Seq models such as iTAPE were proposed to generate bug report titles automatically, but such an approach employs GloVe for text representation, which is difficult for capturing the accurate semantic information of bug reports, and LSTM cannot draw the global dependencies among tokens effectively. This article proposes a deep attention-based summarization model (i.e., ATTSUM) to generate high-quality bug report titles. Specifically, the ATTSUM model employs the encoder-decoder framework, which utilizes the RoBERTa to encode the bug report bodies to capture contextual semantic information better, the stacked Transformer decoder to automatically generate titles, and the copy mechanism to handle the rare token problem. To validate the effectiveness of ATTSUM, we conduct automatic and manual evaluations on 333,563 “< body, title >” pairs of bug reports and perform a practical analysis of its ability to improve low- quality titles. The result shows that ATTSUM is superior to the state-of-the-art baselines by a substantial margin both on automatic evaluation metrics (e.g., by 3.4%-58.8% in terms of ROUGE in F1, and by 7.7%-42.3% in terms of BLEU) and all human-set modalities (e.g., by 1.9%-57.5% in terms of Accuracy, Comprehensiveness, and Lucidity). Moreover, we analyze the impact of the training data size on ATTSUM and the results imply that our approach is robust enough to generate much better titles.

This paper is publishied on IEEE Transactions on Reliability.

[Download paper here](http://annazou1103.github.io/files/ATTSUM.pdf)