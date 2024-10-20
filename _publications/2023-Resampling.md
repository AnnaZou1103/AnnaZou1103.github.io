---
title: "On the Influence of Data Resampling for Deep Learning-Based Log Anomaly Detection: Insights and Recommendations"
collection: publications
permalink: /publication/2023-Resampling
# excerpt: 'This paper on arxiv.'
# date: 2022-08-02
# venue: ''
citation: 'X. Ma, <b>H. Zou</b>, J. Keung, P. He, Y. Li, X. Yu, F. Sarro, arXiv preprint arXiv:2405.03489, 2024.'
---

<b>Keywords</b>: Deep Learning-Based Anomaly Detection, Data Resampling Techniques, Class Imbalance, Empirical Analysis

Numerous Deep Learning (DL)-based approaches have gained attention in software Log Anomaly Detection (LAD), yet class imbalance in training data remains a challenge, with anomalies often comprising less than 1\% of datasets like Thunderbird. Existing DLLAD methods may underperform in severely imbalanced datasets. Although data resampling has proven effective in other software engineering tasks, it has not been explored in LAD.
This study aims to fill this gap by providing an in-depth analysis of the impact of diverse data resampling methods on existing DLLAD approaches from two distinct perspectives. Firstly, we assess the performance of these DLLAD approaches across four datasets with different levels of class imbalance, and we explore the impact of resampling ratios of normal to abnormal data on DLLAD approaches. Secondly, we evaluate the effectiveness of the data resampling methods when utilizing optimal resampling ratios of normal to abnormal data. Our findings indicate that oversampling methods generally outperform undersampling and hybrid sampling methods. Data resampling on raw data yields superior results compared to data resampling in the feature space. 
These improvements are attributed to the increased attention given to important tokens.
By exploring the resampling ratio of normal to abnormal data, we suggest generating more data for minority classes through oversampling while removing less data from majority classes through undersampling. 
In conclusion, our study provides valuable insights into the intricate relationship between data resampling methods and DLLAD. By addressing the challenge of class imbalance, researchers and practitioners can enhance DLLAD performance.

This paper is on arxiv.

[Download paper here](https://arxiv.org/abs/2405.03489)