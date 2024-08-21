# PPI Networks Project

This repository contains the implementation and analysis of the **PPI Networks** project, carried out as part of a Master's program. The project focuses on understanding, modeling, and analyzing Protein-Protein Interaction (PPI) networks using subgraph matching techniques, which are crucial for uncovering insights into biological processes.

## Project Overview

**Protein-Protein Interaction (PPI) Networks** are graphical representations of the physical interactions between proteins within a cell. These networks are fundamental in biology as they enhance our understanding of cellular processes and associated diseases.

**Subgraph Matching** is a widely-used technique for finding isomorphic patterns between two graphs. In the context of PPI networks, this technique is applied to network alignment, enabling the identification of similar proteins across different PPI networks.

This project involves:

1. **PPI Network Construction**: Explaining the construction of PPI networks from experimental or predictive data.
2. **Network Analysis**: Discussing key concepts and measures like connectivity degrees, clusters, and motifs used in analyzing these networks.
3. **Subgraph Matching Technique**: Exploring the steps in detecting similar motifs between two PPI networks, from finding isomorphic subgraphs to measuring the similarity between identified motifs.
4. **Used Python Libraries**: Presenting commonly used Python libraries for implementing subgraph matching in PPI networks, detailing their functionalities, advantages, and limitations.
5. **Python Code Implementation**

## Python Code Implementation

The implementation of the PPI Networks project is carried out in a Jupyter Notebook and includes the following key components:

### 1. **Libraries and Tools**
   - **NetworkX**: Used for constructing and analyzing the PPI networks.
   - **Pandas**: Employed to load and manipulate the dataset.
   - **NumPy**: Utilized for numerical operations and data manipulation.
   - **Matplotlib**: Leveraged to visualize the PPI networks.
   - **Isomorphism Module from NetworkX**: Used for implementing the subgraph matching techniques.

### 2. **Data Loading and Preparation**
   - The dataset is loaded from a `.tsv` file into a Pandas DataFrame.
   - The data is then cleaned, with the first line used as column names and any empty rows removed.

### 3. **PPI Network Construction**
   - The DataFrame contains interaction data, including protein names and interaction scores.
   - This data is used to construct the PPI network using NetworkX, where proteins are represented as nodes, and interactions as edges.

### 4. **Subgraph Matching**
   - The isomorphism algorithms, such as Ullmann and VF2, are applied to identify similar motifs between different PPI networks.
   - This process helps in finding common patterns and understanding critical signaling pathways within biological networks.

### 5. **Visualization**
   - The constructed PPI networks and matched subgraphs are visualized using Matplotlib, providing an intuitive understanding of the network's structure and key interactions.

### 6. **Results**
   - The analysis results, including the identification of key proteins and motifs, are documented, offering insights into the biological significance of the PPI networks studied.

## Full Documentation

Detailed documentation of the project, including methodologies, results, discussions, and conclusions, is provided in the accompanying PDF file: **[Rapport.pdf]**.

## How to Use

1. Clone the repository.
2. Navigate to the project directory.
3. Open the `ppi.ipynb` file in Jupyter Notebook to explore the code and reproduce the analyses.
4. Follow the instructions in the PDF to reproduce the analyses or extend the work.

