---
title: "Weaker Than You Think: A Critical Look at Weakly Supervised Learning"
collection: publications
permalink: /publication/acl2023_weaker
excerpt: 'Weaker Than You Think: A Critical Look at Weakly Supervised Learning'
date: 2023-07-22
venue: 'ACL'
paperurl: 'https://aclanthology.org/2023.acl-long.796.pdf'
---
Weakly supervised learning is a popular approach for training machine learning models in low-resource settings. Instead of requesting
high-quality yet costly human annotations, it
allows training models with noisy annotations
obtained from various weak sources. Recently,
many sophisticated approaches have been proposed for robust training under label noise, reporting impressive results. In this paper, we revisit the setup of these approaches and find that
the benefits brought by these approaches are
significantly overestimated. Specifically, we
find that the success of existing weakly supervised learning approaches heavily relies on the
availability of clean validation samples which,
as we show, can be leveraged much more efficiently by simply training on them. After
using these clean labels in training, the advantages of using these sophisticated approaches
are mostly wiped out. This remains true even
when reducing the size of the available clean
data to just five samples per class, making these
approaches impractical. To understand the true
value of weakly supervised learning, we thoroughly analyze diverse NLP datasets and tasks
to ascertain when and why weakly supervised
approaches work. Based on our findings, we
provide recommendations for future research

[Download paper here]([http://academicpages.github.io/files/paper3.pdf](https://aclanthology.org/2023.acl-long.796.pdf))
