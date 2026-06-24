---
title: "SINr: a python package to train interpretable word and graph embeddings"
collection: publications
category: conferences
permalink: /publication/frccs
excerpt: 'This paper introduces the package SINr, allowing to learn by design interpretable word and graph embeddings.'
venue: 'French Regional Conference on Complex Systems'
paperurl: '10.5281/zenodo.7957531'

---

In this paper, we introduce the SINr Python package to train word and graph embeddings. The SINr approach is based on community detection: a vector for a node is built upon the distribution of its connections through the communities detected on the graph at hand. Because of this, the algorithm runs very fast, and does not require GPUs to proceed. Furthermore, the dimensions of the embedding space are interpretable, those are based on the communities extracted. The package is distributed under Cecill-2.1 license and is available on Github and pypi. 