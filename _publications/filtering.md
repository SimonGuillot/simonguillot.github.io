---
title: "Filtering communities in word co-occurrence networks to foster the emergence of meaning"
collection: publications
category: conferences
permalink: /publication/filtering
excerpt: 'In this paper, we investigate how filtering communities detected on word co-occurrence networks can improve performances of the SINr approach.'
venue: 'Conference on Complex Networks and their Applications 2023'
paperurl: 'https://hal.science/hal-04398742'

---

With SINr, we introduced a way to design graph and word embeddings based on community detection. Contrary to deep learning approaches, this approach does not require much compute and wasproven to be at the state-of-the-art for interpretability in the context of
word embeddings. In this paper, we investigate how filtering communities detected on word co-occurrence networks can improve performances of
the approach. Community detection algorithms tend to uncover communities whose size follows a power-law distribution. Naturally, the number of activations per dimensions in SINr follows a power-law: a few dimensions are activated by many words, and many dimensions are activated by a few words. By filtering this distribution, removing part of its head and tail, we show improvement on intrinsic evaluation of the embedding while dividing their dimensionality by five. In addition, we show that these results are stable through several runs, thus defining a subset of distinctive features to describe a given corpus.