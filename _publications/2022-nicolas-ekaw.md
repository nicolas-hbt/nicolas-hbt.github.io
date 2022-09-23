---
title: "New Strategies for Training Knowledge Graph Embeddings: the Recommendation Case"
collection: publications
permalink:
excerpt: ''
when: September 2022
date: September 2022
year: 2022
authors: <b>Nicolas Hubert</b>, Pierre Monnin, Armelle Brun, and Davy Monticolo
venue: '23rd International Conference on Knowledge Engineering and Knowledge Management (EKAW)'
acceptance rate: 19% (11/57 full research papers)
paperurl: 'https://hal.inria.fr/hal-03722881/document'
citation:
---
Knowledge graph embedding models encode elements of a graph into a low-dimensional space that supports several downstream tasks. This work is concerned with the recommendation task, which we approach as a link prediction task on a single target relation performed in the embedding space. Training an embedding model requires negative sampling, which consists in corrupting the head or the tail of positive triples to generate negative ones. Although knowledge graph embedding models and negative sampling have extensively been investigated for link prediction, their combined use for performing recommendations over knowledge graphs remains largely unexplored in the literature. In this work, we propose two specialization strategies for training embedding models and perform knowledge graph-based recommendations. Both strategies first train an embedding model on the whole knowledge graph. Then, during a specialization phase, a dedicated negative sampling scheme is applied to refine the pre-trained model. Experimental results on two public datasets demonstrate that a simple strategy which refines a pre-trained model by sampling random negative tails for the target relation proves to be very effective. This strategy significantly improves performance with respect to traditional rank-based evaluation metrics as well as a newly introduced metric that reflects the semantic validity of the top-ranked candidate entities.
