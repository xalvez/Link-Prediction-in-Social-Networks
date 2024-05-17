# Link-Prediction-in-Social-Networks
link prediction in social network using GNN model 

{about the dataset}
Facebook Large Page-Page Network

Description

This webgraph is a page-page graph of verified Facebook sites. Nodes represent official Facebook pages while the links are mutual likes between sites. Node features are extracted from the site descriptions that the page owners created to summarize the purpose of the site. This graph was collected through the Facebook Graph API in November 2017 and restricted to pages from 4 categories which are defined by Facebook. These categories are: politicians, governmental organizations, television shows and companies. The task related to this dataset is multi-class node classification for the 4 site categories.

- Directed: No.
- Node features: Yes.
- Edge features: No.
- Node labels: Yes. Binary-labeled.
- Temporal: No.

|   | Facebook  |
|---|---|
| Nodes |22,470   | 
| Edges | 171,002  |
| Density |  0.001 | 
| Transitvity | 0.232| 

Possible tasks

- Multi-class node classification
- Link prediction
- Community detection
- Network visualization


{about the project} 

This project explores the application of Graph Neural Networks (GNNs) to the task of link prediction in social networks. Link prediction aims to determine whether a connection between two nodes in a network will form or not, a critical challenge in social network analysis for applications such as friend recommendation and information flow prediction. 
Our approach utilizes GNN models, which effectively leverage node features and topological structure to learn node representations that are conducive to predicting potential links. Specifically, we employ a variety of GNN architectures, including Graph Convolutional Networks (GCNs), Graph Attention Networks (GATs), and more recent innovations such as GraphSAGE, to encode the nodes based on their features and their neighbors’ information.

We test our models on multiple real-world datasets, measuring the accuracy of predicted links using metrics such as AUC-ROC and precision. Additionally, we compare the performance of GNN models against traditional link prediction algorithms like Common Neighbors and Adamic-Adar to establish benchmarks.

The project also investigates the effects of hyperparameter tuning, the impact of different types of node features, and the robustness of GNN models against varying network sizes and densities. The outcomes of this research contribute to understanding the capabilities of GNNs in the context of social network analysis and provide insights into effective strategies for enhancing link prediction accuracy.
By harnessing the power of GNNs, this project aims to offer a sophisticated tool for social network analysis that can adapt to the intricate and dynamic nature of social connections, paving the way for more accurate and useful applications in social media and other related fields.


