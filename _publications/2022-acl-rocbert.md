---
title: "RoCBert: Robust Chinese Bert with Multimodal Contrastive Pretraining"
collection: publications
permalink: /publication/2022-acl-rocbert
excerpt: 'RoCBert: Robust Chinese Bert with Multimodal Contrastive Pretraining'
date: 2022-07-22
venue: 'ACL'
paperurl: 'https://aclanthology.org/2022.acl-long.65.pdf'
---
Large-scale pretrained language models have
achieved SOTA results on NLP tasks. However, they have been shown vulnerable to adversarial attacks especially for logographic languages like Chinese. In this work, we propose
ROCBERT: a pretrained Chinese Bert that is
robust to various forms of adversarial attacks
like word perturbation, synonyms, typos, etc.
It is pretrained with the contrastive learning objective which maximizes the label consistency
under different synthesized adversarial examples. The model takes as input multimodal
information including the semantic, phonetic
and visual features. We show all these features
are important to the model robustness since the
attack can be performed in all the three forms.
Across 5 Chinese NLU tasks, ROCBERT outperforms strong baselines under three blackbox adversarial algorithms without sacrificing
the performance on clean testset. It also performs the best in the toxic content detection
task under human-made attacks.

[Download paper here](http://academicpages.github.io/files/paper1.pdf)
