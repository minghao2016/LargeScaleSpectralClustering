# Large-Scale Spectral Clustering on Graphs
===============

Spectral Clustering has become an widely used technique to detect complex shapes and manifold structure on graph data.
In the past few years, many previous works on this method reported good experimental results on some challenging 
clustering problems.

However, as data grows in scale, which is common in today's era of Big Data, the classical Spectral Clustering 
algorithm becomes almost impossible to apply because of its computational cost.

In this paper, we provide a review of some of the main methods to tackle this issue. We focus on the two costly aspects of the algorithm: the construction of the graph itself from vectorial data and the eigendecomposition of the corresponding Laplacian matrix.

Then, we propose an implementation of Large-Scale Spectral Clustering, both on artificial and real data.


===============

<sup>*Guillaume Salha*

<sup>*École Normale Supérieure de Cachan*

<sup>*Master 2 Mathematics, Vision, Learning (MVA)*

<sup>*Fall 2015*
