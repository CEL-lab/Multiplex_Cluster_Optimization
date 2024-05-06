# Enhancing Power Network Resilience through Adaptive Multiplex Clustering Techniques

## Introduction
This repository contains the implementation of advanced clustering techniques in multiplex power networks aimed at enhancing the resilience and efficiency of electrical power distribution systems. The project utilizes a mathematical model to optimize the clustering of nodes across multiple layers of the network, minimizing the maximum diameter of clusters to ensure robust network performance under various conditions.

## Model
The model is designed to handle multiplex power networks, where each layer represents different connectivity protocols or power flow scenarios. The objective is to minimize the maximum diameter of the clusters formed in these networks, facilitating improved resilience and efficiency. The model introduces a set of decision variables, constraints, and an objective function that are detailed in the project's documentation.

## Data
The dataset used in this project includes:
- **Nodes**: Represents the points of distribution or junctions within the power network. Each node is a critical point in the network where power is relayed or distributed.
- **Edges**: Represents the connections between nodes. Each edge indicates the presence of a power line or a transmission link between two nodes.

These files are subsets of the larger dataset available from [SciGRID](https://www.power.scigrid.de/pages/downloads.html), which has been simplified to include only 50 nodes for ease of analysis.

## Code
The repository includes a Jupyter Notebook that outlines the complete process from network construction to solving the clustering model:
- **Network Construction**: Constructs the multiplex network structure from the provided node and edge data.
- **Model Solving**: Applies the mathematical model using AMPL (A Mathematical Programming Language) to solve for the optimal clustering of nodes.

The code is designed to be executed in a Google Colab environment, leveraging its computational resources and ease of use for complex mathematical modeling and data visualization.

## How to Use
1. **Clone the Repository**: Clone this repository to your local machine or open it directly in Google Colab.
2. **Explore the Data**: Review the node and edge data to understand the network structure.
3. **Run the Notebook**: Execute the Jupyter Notebook from start to finish to replicate the model solving process and view the results.

## Contribution
Contributions to this project are welcome. You can contribute by improving the code, expanding the dataset, or suggesting new clustering algorithms.

## License
This project is released under the MIT License.
