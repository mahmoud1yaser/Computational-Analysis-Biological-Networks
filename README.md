# Protein-Protein Interactions Biological Network
### Project Idea
You are required to analyze a biological network of protein-protein interactions (PPIs) using the NetworkX python package. Helpful information about networks (graphs) and this package can be found in the NetworkX Reference.
- You can get your own PPIs network or you can use the interactome titled “PathLinker_2018_human-ppi-weighted-cap0_75.txt”.
    - This file represents a directed interactome: each interaction starts from the tail node to the
    head node.
    - This file represents each PPI in one line of four pieces of information (columns).
        - First: the tail/source/start protein node.
        - Second: the head/destination/end protein node.
        - Third: the interaction confidence. It has a range from 0 to 1. The higher this value, the more probable this interaction to happen.
        - Fourth: the method used to identify this interaction.
        - Each protein is represented by its UniProt ID.
- Your analysis can include, but not limited to, the following:
    - Construct a graph (biological network) from the above interactome.
    - Given two proteins, list the acyclic shortest path(s) between these two nodes in a text file.
        - Provide the total path score.
        - Provide the weight of each interaction in the path(s).
        - If more than one path, report all the paths.
        - Use NetworkX and matplotlib to draw the sub-network formed by these shortest paths.
    - Given one protein, list all the directly connected proteins to it in a text file.
        - Report the degree (number of connections) of this protein in a separate line.
        - Provide each connected protein in a line with its corresponding interaction weight.
    - Given a set of proteins:
        - Draw a histogram for the proteins degree.
        - Rank these proteins from the highly connected to the least in a text file, where each line is a protein and its corresponding degree.
    - Provide a conversion map between the protein UniProt ID and its gene name.
        - You can be provided by one protein ID or a set of protein IDs, and then you need to get their corresponding gene names.
    - Convert the above graph as an unweighted graph and save it using the adjacency matrix method. You need to search for it.