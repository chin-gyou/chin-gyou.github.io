---
title: "xPQA: Cross-lingual Product Question Answering in 12 languages"
collection: publications
permalink: /publication/acl2023_xpqa
excerpt: 'xPQA: Cross-lingual Product Question Answering in 12 languages'
date: 2023
venue: 'ACL'
paperurl: 'https://aclanthology.org/2023.acl-industry.12.pdf'
---
Product Question Answering (PQA) systems
are key in e-commerce applications to provide
responses to customers’ questions as they shop
for products. While existing work on PQA focuses mainly on English, in practice there is
need to support multiple customer languages
while leveraging product information available
in English. To study this practical industrial
task, we present xPQA, a large-scale annotated cross-lingual PQA dataset in 12 languages
across 9 branches, and report results in (1) candidate ranking, to select the best English candidate containing the information to answer
a non-English question; and (2) answer generation, to generate a natural-sounding nonEnglish answer based on the selected English
candidate. We evaluate various approaches involving machine translation at runtime or offline, leveraging multilingual pre-trained LMs,
and including or excluding xPQA training data.
We find that (1) In-domain data is essential as
cross-lingual rankers trained on other domains
perform poorly on the PQA task; (2) Candidate
ranking often prefers runtime-translation approaches while answer generation prefers multilingual approaches; (3) Translating offline to
augment multilingual models helps candidate
ranking mainly on languages with non-Latin
scripts; and helps answer generation mainly on
languages with Latin scripts. Still, there remains a significant performance gap between
the English and the cross-lingual test sets

[Download paper here](https://aclanthology.org/2023.acl-industry.12.pdf)
