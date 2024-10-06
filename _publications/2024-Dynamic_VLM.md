---
title: "Towards Dynamic and Realistic Evaluation of Multi-modal Large Language Model"
collection: publications
permalink: /publication/2024-Dynamic_VLM
#excerpt: 'This paper is under review.'
# date: 2022-08-02
# venue: ''
citation: '<b>H. Zou</b>, Y. Li, Z. Xiao. (Extended Abstract). GenBench workshop 2024.'
---

Hallucinations in the multimodal domain occur when a model provides information that contradicts the content of an image. Existing benchmarks for evaluating hallucinations in current Multi-modal Large Language Models (MLLMs) often adopt a static captioning or question-answering format, which deviates from the realistic use of the MLLMs in downstream tasks. To address these limitations, we propose to evaluate MLLMs in a dynamic and multi-turn way to close the realism gap. Our approach involves an evaluator agent engaging in evaluative conversation, generating diverse contextually relevant questions and their follow-ups. The framework features a context module and a question generation module, enabling the evaluator to mimic human-like questioning in real work tasks while assuring the quality of the evaluation. Comparison with single-turn question-answering or captioning evaluation methods demonstrates that our approach identified more hallucination issues in VLMs and covered more aspects of the visual content.

This paper accepted as an extended abstract for GenBench workshop 2024.