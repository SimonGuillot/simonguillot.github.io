---
title: "Sparser is better: one step closer to word embedding interpretability"
collection: publications
category: conferences
permalink: /publication/sparser
excerpt: 'In this paper we consider the sparsification - i.e restricting the vectors to their top k components - of interpretable word vectors to allow the analysis of the interpretability of word vectors themselves, instead of being limited to the interpretability of individual dimensions. '
venue: 'Internation Workshop of Computational Semantics (IWCS 2023)'
paperurl: 'https://aclanthology.org/2023.iwcs-1.13/'
---

Sparse word embeddings models (SPINE, SINr) are designed to embed words in interpretable dimensions. An interpretable dimension is such that a human can interpret the semantic (or syntactic) relations between words active for a dimension. These models are useful for critical downstream tasks in natural language processing (e.g. medical or legal NLP), and digital humanities applications. This work extends interpretability at the vector level with a more manageable number of activated dimensions following recommendations from psycholinguistics. Subsequently, one of the key criteria to an interpretable model is sparsity: in order to be interpretable, not every word should be represented by all the features of the model, especially if humans have to interpret these features and their relations. This raises one question: to which extent is sparsity sustainable with regard to performance? We thus introduce a sparsification procedure to evaluate its impact on two interpretable methods (SPINE and SINr) to tend towards sustainable vector interpretability. We also introduce stability as a new criterion to interpretability. Our stability evaluations show little albeit non-zero variation for SPINE and SINr embeddings. We then show that increasing sparsity does not necessarily interfere with performance. These results are encouraging and pave the way towards intrinsically interpretable word vectors.
