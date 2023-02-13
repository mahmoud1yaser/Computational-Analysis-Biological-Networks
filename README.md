# Analyzing the Protein-Protein Interaction Network

  - [Brief Description](#brief-description)
  - [Features](#features)
  - [Construct biological network from the above interactome](#construct-biological-network-from-the-above-interactome)
  - [Draw the sub-network for acyclic shortest path(s) between two nodes](#draw-the-sub-network-for-acyclic-shortest-paths-between-two-nodes)
  - [Drawing a histogram for a set of protein’s degree](#drawing-a-histogram-for-a-set-of-proteins-degree)
  - [Constructing the adjacency matrix](#constructing-the-adjacency-matrix)
  - [Team Members](#team-members)
## Brief Description
Analyzing a biological network of protein-protein interactions __(PPIs)__ using the NetworkX python package, and construct a graph from the interactome and perform various analyses on the network, including finding the shortest path between two proteins, identifying directly connected proteins, ranking proteins based on their degree, converting UniProt IDs to gene names.

## Features
> 1. Construct a graph (biological network) from the interactome ["PathLinker_2018_human-ppi-weighted-cap0_75.txt"](https://github.com/Ibrahim-Youssef/localized-pathlinker/tree/master/Data) .
> 2. List the acyclic shortest path(s) between two proteins (nodes) in a text file.
> 3. List all the directly connected proteins to one protein in a text file.
> 4. Draw a histogram for a set of protein’s degree and rank these proteins from the highly connected to the least in a text file.
> 5. Provide a conversion map between the protein UniProt ID and its gene name. 
> 6. Convert the above graph as an unweighted graph and save it using the adjacency matrix
method.

## Construct biological network from the above interactome:
![Biological Network](images\output.png)

## Draw the sub-network for acyclic shortest path(s) between two nodes:
![Sub-Network formed by these shortest paths](images\shortest_paths_subnetwork.png)

## Drawing a histogram for a set of protein’s degree:
![Histogram](images\histogram_proteins_set.png)

## constructing the adjacency matrix:
![Adjacency Matrix](images\adjacency_matrix.png)



## Team Members
  |                                                             | 
  | ----------------------------------------------------------- | 
  | [Abdelrahman Ali](https://github.com/abdelrahman-ali123)    |
  | [Mahmoud Yaser](https://github.com/mahmoud1yaser)           |
  | [Omar Saad](https://github.com/Omar-Saad-ELGharbawy)        | 
  | [Nevein Mohamed](https://github.com/NeveenMohamed)          |
  

```
            Ibrahim Mohamed Youssef, PhD
                Assistant Professor
```
### Fall 22, SBE3031 - Advanced Topics in Medical Informatics
