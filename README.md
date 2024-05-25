# About Project

## Dolphins Social Network Analysis using NetworkX

**DOMAIN**: Network Analysis, Data Science, Graph Theory

## Description
The project "Dolphins Social Network Analysis using NetworkX" focuses on utilizing the NetworkX library in Python to perform comprehensive analysis of network structures. NetworkX is a powerful tool for creating, manipulating, and studying complex networks, making it particularly valuable in understanding various types of relationships and connections in datasets, such as social networks, communication networks, biological networks, and more.

## HW/SW Requirements
- **Hardware**: A standard personal computer with sufficient processing power and memory.
- **Software**: Python programming environment (Anaconda distribution recommended), NetworkX library installed (can be installed using `pip install networkx`), Jupyter Notebook or any other Python IDE.

## Technology
The project employs the NetworkX library, which is a Python package used for the creation, manipulation, and analysis of complex networks or graphs. NetworkX provides a variety of functions and algorithms to study network characteristics, including centrality measures, connectivity analysis, community detection, and visualization.

## Objective
The main objective of this project is to demonstrate the capabilities of the NetworkX library in analyzing and understanding the structural properties of networks. By using various network analysis techniques, the project aims to showcase how to extract valuable insights and patterns from real-world network data.

## Data Source
The file `dolphins.gml` contains an undirected social network of frequent associations between 62 dolphins in a community living off Doubtful Sound, New Zealand, as compiled by Lusseau et al. (2003). Please cite the following source when using this data:

> D. Lusseau, K. Schneider, O. J. Boisseau, P. Haase, E. Slooten, and S. M. Dawson, "The bottlenose dolphin community of Doubtful Sound features a large proportion of long-lasting associations," *Behavioral Ecology and Sociobiology*, vol. 54, pp. 396-405, 2003.

## Targeted Outcomes
- **Data Loading and Network Creation**: Load network data from various sources (e.g., CSV files, APIs, databases), and create network structures using NetworkX.
- **Descriptive Analysis**: Calculate and analyze basic network metrics such as node and edge counts, average degree, density, and more.
- **Centrality Measures**: Compute and interpret centrality measures like degree centrality, betweenness centrality, and eigenvector centrality to identify important nodes within the network.
- **Connectivity Analysis**: Explore network connectivity by identifying connected components, isolates, and articulation points.
- **Community Detection**: Apply community detection algorithms (e.g., Louvain, Girvan-Newman) to uncover clusters or communities within the network.
- **Visualization**: Visualize the network structure using NetworkX's built-in visualization tools or external libraries like Matplotlib.

## Key Features of the Project

- **Importing Necessary Libraries**: Utilized libraries like NetworkX and Matplotlib for network analysis and visualization.

- **Data Loading and Network Creation**: Loaded network data from a GML file and created network structures using NetworkX.

- **Network Visualization**: Visualized the network structure using NetworkX's built-in visualization tools and Matplotlib.

- **Descriptive Analysis**: Calculated and analyzed basic network metrics such as node and edge counts, average degree, density, diameter, and clustering coefficient.

- **Centrality Measures**: Computed and interpreted various centrality measures to identify important nodes within the network:
  - Degree Centrality
  - Betweenness Centrality
  - Eigenvector Centrality
  - Closeness Centrality
  - Load Centrality

- **Influential Nodes Analysis**: Identified and visualized the most influential nodes based on different centrality measures.

- **Connectivity Analysis**: Explored network connectivity by identifying connected components, isolates, and articulation points.

- **Community Detection**: Applied different community detection algorithms to uncover clusters or communities within the network:
  - Louvain Algorithm
  - Girvan-Newman Algorithm
  - Label Propagation Algorithm

- **Community Visualization**: Visualized the communities detected by different algorithms using distinct colors for better differentiation and analysis.