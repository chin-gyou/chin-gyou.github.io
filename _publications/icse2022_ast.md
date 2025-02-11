---
title: "AST-trans: code summarization with efficient tree-structured attention"
collection: publications
permalink: /publication/icse2022_ast
excerpt: 'AST-trans: code summarization with efficient tree-structured attention'
date: 2022-05-22
venue: 'ICSE'
paperurl: 'https://par.nsf.gov/servlets/purl/10343375'
---
Code summarization aims to generate brief natural language descriptions for source codes. The state-of-the-art approaches follow
a transformer-based encoder-decoder architecture. As the source
code is highly structured and follows strict grammars, its Abstract
Syntax Tree (AST) is widely used for encoding structural information. However, ASTs are much longer than the corresponding
source code. Existing approaches ignore the size constraint and
simply feed the whole linearized AST into the encoders. We argue
that such a simple process makes it difficult to extract the truly useful dependency relations from the overlong input sequence. It also
incurs significant computational overhead since each node needs
to apply self-attention to all other nodes in the AST. To encode
the AST more effectively and efficiently, we propose AST-Trans
in this paper which exploits two types of node relationships in
the AST: ancestor-descendant and sibling relationships. It applies
the tree-structured attention to dynamically allocate weights for
relevant nodes and exclude irrelevant nodes based on these two
relationships. We further propose an efficient implementation to
support fast parallel computation for tree-structure attention. On
the two code summarization datasets, experimental results show
that AST-Trans significantly outperforms the state-of-the-arts while
being times more efficient than standard transformers

[Download paper here](https://par.nsf.gov/servlets/purl/10343375)
