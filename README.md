# Network-Science-project

This project is an analytical exploration of my ego network derived from the social platform [vk.com](https://vk.com/). The network consists of my friends as nodes (excluding my own profile) and their mutual friendships as edges. The data was collected using the VK API. 

The main results and visualizations are shown in the [presentation](https://github.com/thecrazymage/Network-Science-project/blob/main/results.pdf), and the detailed results along with the source code for the project are available in the [Jupyter Notebook](https://github.com/thecrazymage/Network-Science-project/blob/main/source.ipynb).


## Project content

**Network summary:**
- Network source and a description of preprocessing steps.
- Type of graph: directed/undirected, heterogeneous/homogeneous, weighted/unweighted, etc.
- Node/Edge attributes.
- Number of nodes and edges.
- Diameter and radius.
- Clustering coefficients (global, average local, histogram).
- Average path length and its histogram.
- Degree distribution, and fitted models by regression/MLE/KS-test.
- A gorgeous network layout.

**Structural Analysis:**
- The closest random graph model to my social network. Real-world network properties on ER, BA, WS graph models and my network, with a comparison of results..
- Degree/Closeness/Betweenness/Katz/Eigenvector centralities, and a description of the top nodes for each centrality measure.
- Page-Rank in the case of a directed network, and a description of top nodes.
- A correlation comparison of the centralities.
- Assortative mixing by node attributes and node degree.
- Node structural equivalence/similarity measures.

**Community Detection:**
- Clique search and k-cores visualization.
- The best results of various community detection algorithms in terms of interpretation and the modularity criterion.