---
title: "Neural Data-to-Text Generation via Jointly Learning the Segmentation and Correspondence"
collection: publications
permalink: /publication/acl2020_select
excerpt: 'Neural Data-to-Text Generation via Jointly Learning the Segmentation and Correspondence'
date: 2020-07-22
venue: 'ACL'
paperurl: 'https://aclanthology.org/2020.acl-main.641.pdf'
---
The neural attention model has achieved great success in data-to-text generation tasks. Though usually excelling at producing fluent text, it suffers from the problem of information missing, repetition and “hallucination”. Due to the black-box nature of the neural attention architecture, avoiding these problems in a systematic way is non-trivial. To address this concern, we propose to explicitly segment target text into fragment units and align them with their data correspondences. The segmentation and correspondence are jointly learned as latent variables without any human annotations. We further impose a soft statistical constraint to regularize the segmental granularity. The resulting architecture maintains the same expressive power as neural attention models, while being able to generate fully interpretable outputs with several times less computational cost. On both E2E and WebNLG benchmarks, we show the proposed model consistently outperforms its neural attention counterparts.

[Download paper here](https://aclanthology.org/2020.acl-main.641.pdf)
