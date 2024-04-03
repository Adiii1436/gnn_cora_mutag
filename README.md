## Graph Neural Networks - CORA & MUTAG DATASET

Graph Neural Networks (GNNs) offer exceptional capabilities for analyzing and understanding graph-structured data. Their ability to learn from intricate relationships between nodes makes them invaluable across domains like social analysis, knowledge graph reasoning, the life sciences and even recommender systems. 

## What you'll find here:

- **Node Classification (Cora Dataset)**: Accurately categorize scientific publications based on their content. Dive into a citation network where documents are nodes and citations define the edges.
- **Graph Classification (MUTAG Dataset)**: Analyze chemical compounds and predict their mutagenic effects with models that learn directly from molecular structures (atoms as nodes, bonds as edges).

## Key Concepts Demonstrated:
- **Node Embeddings**: Learn how GNNs generate compact representations of nodes, capturing key characteristics and relationships.
- **Message Passing**: Understand the fundamental mechanism by which GNNs aggregate information from neighboring nodes
- **Graph-Level Embeddings**: Explore how to condense the information of an entire graph into a single representation for classification tasks.

## Node Classification
Node classification is a supervised machine learning task where a Deep Graph Neural Network is used to predict labels for nodes in a graph. The process works like this: first, the network generates unique representations (embeddings) for each node. Then, these embeddings are fed into a Multi-Layer Perceptron (MLP) that makes the final label predictions.

## Cora Dataset
The Cora dataset consists of 2708 scientific publications classified into one of seven classes. The citation network consists of 5429 links. Each publication in the dataset is described by a 0/1-valued word vector indicating the absence/presence of the corresponding word from the dictionary. The dictionary consists of 1433 unique words. Nodes represent documents and edges represent citation links.

<p align="center"><img src="https://github.com/NickKaparinos/Graph-Neural-Network-Projects/blob/master/Images/cora/cora-graph" alt="drawing" width="500"/></p>

## Graph Classification
Graph classification is a supervised learning task where a Deep Graph Neural Network predicts a label for an entire graph. First, the network creates embeddings (representations) for each node in the graph. These embeddings are then combined (pooled) and analyzed by a Multi-Layer Perceptron (MLP) to determine the graph's overall label.

## MUTAG Dataset
The MUTAG dataset consists of 188 chemical compounds divided into two classes according to their mutagenic effect on a bacterium. The chemical data was obtained from http://cdb.ics.uci.edu and converted to graphs, where vertices represent atoms and edges represent chemical bonds. Explicit hydrogen atoms have been removed and vertices are labeled by atom type and edges by bond type (single, double, triple or aromatic).
<p float="left">
  <img src="https://github.com/NickKaparinos/Graph-Neural-Network-Projects/blob/master/Images/mutag/mutag_graph0.png" width="32.9%" /> 
  <img src="https://github.com/NickKaparinos/Graph-Neural-Network-Projects/blob/master/Images/mutag/mutag_graph1.png" width="32.9%" />
  <img src="https://github.com/NickKaparinos/Graph-Neural-Network-Projects/blob/master/Images/mutag/mutag_graph2.png" width="32.9%" />
</p>
