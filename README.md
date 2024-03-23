# Network-Science-project

This project aims to analyse my ego network from the social network vk.com, where the nodes are my friends (except me) and the edges are friendships. The data was collected using the VK API. The results are shown in the [presentation](https://github.com/thecrazymage/Network-Science-project/blob/main/results.pdf).


### Project content

Network summary:
- Network source and the description of preprocessing steps.
- Type of the graph: directed/undirected, heterogeneous/homogeneous, weighted/unweighted, etc.
- Node/Edge attributes.
- Number of nodes and edges.
- Diameter, radius.
- Clustering coefficient (global, average local, histogram).
- Average path length (histogram).
- Degree distribution, fitted models by regression/MLE/KS-test.
- Gorgeous network layout.

Structural Analysis:
- The closest random graph model to my social network. Real-world network properties on ER, BA, WS graph models and my network, comparing results.
- Degree/Closeness/Betweenness/Katz/Eigenvector centralities, top nodes description.
- Page-Rank in a case of directed network, top nodes description.
- Correlation comparison of centralities.
- Assortative mixing by node attributes and node degree.
- Node structural equivalence/similarity.

Community Detection:
- Clique search, k-cores visualization.
- Best results of various community detection algorithms in terms of interpretation and modularity criterion.