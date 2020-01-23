---
title: "Learning to Distribute Vocabulary Indexing for Scalable Visual Search"
date: 2013-01-01
publishDate: 2019-12-29T23:55:04.509575Z
authors: ["Rongrong Ji", "Ling-Yu Duan", "Jie Chen", "Lexing Xie", "Hongxun Yao", "Wen Gao"]
publication_types: ["2"]
abstract: "In recent years, there is an ever-increasing research focus on Bag-of-Words based near duplicate visual search paradigm with inverted indexing. One fundamental yet unexploited challenge is how to maintain the large indexing structures within a single server subject to its memory constraint, which is extremely hard to scale up to millions or even billions of images. In this paper, we propose to parallelize the near duplicate visual search architecture to index millions of images over multiple servers, including the distribution of both visual vocabulary and the corresponding indexing structure. We optimize the distribution of vocabulary indexing from a machine learning perspective, which provides a “memory light” search paradigm that leverages the computational power across multiple servers to reduce the search latency. Especially, our solution addresses two essential issues: “What to distribute” and “How to distribute”. “What to distribute” is addressed by a “lossy” vocabulary Boosting, which discards both frequent and indiscriminating words prior to distribution. “How to distribute” is addressed by learning an optimal distribution function, which maximizes the uniformity of assigning the words of a given query to multiple servers. We validate the distributed vocabulary indexing scheme in a real world location search system over 10 million landmark images. Comparing to the state-of-the-art alternatives of single-server search (5), (6), (16) and distributed search (23), our scheme has yielded a significant gain of about 200% speedup at comparable precision by distributing only 5% words. We also report excellent robustness even when partial servers crash."
featured: false
publication: "*Multimedia, IEEE Transactions on*"
---

