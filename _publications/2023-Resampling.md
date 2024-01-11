---
title: "On the Influence of Data Resampling for Deep Learning-Based Anomaly Detection: Insights and Recommendations"
collection: publications
permalink: /publication/2023-Resampling
# excerpt: 'This paper is publishied on IEEE Transactions on Reliability.'
# date: 2022-08-02
# venue: 'IEEE Transactions on Reliability'
# citation: 'X. Ma, J. W. Keung, X. Yu, <b>H. Zou</b>, J. Zhang, and Y. Li, &quot;AttSum: A Deep Attention-Based Summarization Model for Bug Report Title Generation&quot;, IEEE Transactions on Reliability, pp. 1–15, 2023, doi: 10.1109/TR.2023.3236404.'
---

<b>Keywords</b>: Deep Learning-Based Anomaly Detection, Log Anomaly Detection, Data Resampling Techniques, Class Imbalance, Empirical Analysis

Numerous Deep Learning (DL)-based approaches have garnered considerable attention in the field of software anomaly detection (AD). However, a practical challenge persists: The prevalent issue of class imbalance in the public data commonly used to train the DL models. This imbalance is characterized by a substantial disparity in the number of abnormal log sequences compared to normal ones, for example, anomalies represent less than 1% of one of the most popular datasets, namely the Thunderbird dataset.
Previous research has indicated that existing DLAD approaches may exhibit unsatisfactory performance, particularly when confronted with datasets featuring severe class imbalances. Mitigating class imbalance through data resampling has proven effective for other software engineering tasks, however it has been unexplored for AD thus far.
This study aims to fill this gap by providing an in-depth analysis of the impact of diverse data resampling techniques on existing DLAD approaches from two distinct perspectives. Firstly, we assess the performance of these DLAD approaches and evaluate the effectiveness of data resampling techniques when utilizing predefined desired ratios of normal to abnormal data. Secondly, we explore the implications of varying desired ratios within different resampling techniques, accompanied by practical recommendations.
Our findings indicate that, overall, oversampling techniques outperform undersampling and hybrid sampling techniques. Specifically, simple random sampling directly applied to raw data exhibits superior performance compared to other techniques conducted in the feature space. Interestingly, undersampling techniques do not effectively alleviate the issue of data imbalance. To maximize the effectiveness of resampling for existing DLAD approaches, we recommend adopting an oversampling method with a lower desired ratio. This approach narrows the gap between the counts of normal and abnormal data by creating more minority data. For undersampling methods, we recommend employing a larger desired ratio to mitigate the disparity between the quantities of the two classes while minimizing information loss.
In conclusion, our study provides valuable insights into the intricate relationship between data resampling techniques and DLAD. By addressing the challenge of class imbalance, researchers and practitioners can enhance the performance of DLAD approaches in anomaly detection tasks.

This paper is under review.