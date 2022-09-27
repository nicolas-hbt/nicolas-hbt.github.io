---
title: "Knowledge Graph Embeddings for Link Prediction: Beware of Semantics!"
collection: publications
permalink:
excerpt: ''
when: October 2022.
date: October 2022.
year: 2022
authors: <b>Nicolas Hubert</b>, Pierre Monnin, Armelle Brun, and Davy Monticolo
venue: 'DL4KG@ISWC 2022: Workshop on Deep Learning for Knowledge Graphs, held as part of ISWC 2022: the 21st International Semantic Web Conference'
acceptance rate: unknown
paperurl: 'https://hal.archives-ouvertes.fr/hal-03787512/document'
citation:
---
The task of predicting links in knowledge graphs (KGs) can be tackled using knowledge graph embedding models (KGEMs). Such models project entities and relations of a KG into a low-dimensional vector space that preserves as much as possible the properties of the graph. The performance of KGEMs for link prediction is traditionally assessed using rank-based metrics that evaluate the ability of models to give high scores to ground-truth entities. However, other scored entities are left unconsidered by these metrics. This constitutes a shortcoming in some application domains where it may be required to ensure consistency among the top-scored entities. To this aim, in this paper we propose to measure the ability of popular KGEMs to capture the semantic profile of relations. In particular, we use Sem@K, a semantic-oriented metric that assesses whether top-scored entities are semantically valid. Our experiments show that agnostic KGEMs are actually able to learn the semantic profile of relations. This raises the opportunity of using Sem@K as an additional training criterion.
