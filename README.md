# cytokine_networks
Cytokine networks based on transcriptomics data deposited to the CytoSig database.

Statistically significant cytokine-cytokine associations generated from transcriptomics data deposited to the CytoSig database. The interactions were generated by CytoSig's significance analysis (two-sided Wilcoxon signed-rank test comparing the logFC values from multiple studies). Putative intracellular signalling paths (see corresponding edge table columns - subgraph_png and subgraph_tsv) were genrated using NicheNet (model version v2).

The networks can be [interactively accessed under the following NDEx link.](https://www.ndexbio.org/viewer/networks/5503d3ad-1763-11ef-9621-005056ae23aa)

The networks can be accessed by:
- opening cytokine_network_cytosig.cys using Cytoscape
- parsing cytokine_network_cytosig.tsv programmatically using appropriate libraries and programming languages (igraph, NetworkX etc.)
