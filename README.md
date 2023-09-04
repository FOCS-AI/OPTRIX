# optrix
A dataset of publicly available core network topologies

# dataset-core-networks
- An analysis-ready dataset of publicly available core optical fibre networks (BT, Internet Topology Zoo, SNDlib, Conus) 
- Source code provides scripts to load and analyze core network dataset.

## Requirements
- NetworkX: A Python library for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.
- NumPy: A fundamental package for scientific computing with Python.
- Matplotlib: A plotting library for creating static, animated, and interactive visualizations in Python.
- Pickle: A module for serializing and deserializing Python objects.

  

## Types of Networks
The code provides a collection of networks from different datasets. Currently, it includes the following datasets:
- SNDLib: A collection of network topologies used for network optimization problems.
- ITZ: A collection of network topologies from the Internet Topology Zoo Dataset.
- BT: British Telecommunication's Core Network BT-22 Published Online

## Types of Files
The code supports loading the following types of files:
- `.adjlist` files: Used to load graphs in adjacency list format.
- `.edgelist` files: Used to load graphs in edge list format.
- `.graphml` files: Used to load graphs in GraphML format.
- `.gexf` files: Used to load graphs in GEXF format.
- `.pickle` files: Used to load graphs in serialized pickle format.

<!---
| 30-Node-ONDPBook       |              30 |              36 |
| 60-Node-CONUS-Topology_nodes           |              60 |              79 |
| 60-Node-ONDPBook-Topology_nodes        |              60 |              77 |
| CORONET_CONUS_Topology_nodes           |              75 |              99 |
| CORONET_Global_Topology_nodes          |             100 |             136 |

-->
## Open Network Datasets
| Name                                   | Number of Nodes | Number of Edges |
|----------------------------------------|-----------------|-----------------|
| BT-22                                  | 22              | 35              |
| abilene                                |              12 |              15 |
| atlanta                                |              15 |              22 |
| cost266                                |              37 |              57 |
| france                                 |              25 |              45 |
| geant                                  |              22 |              36 |
| germany50                              |              50 |              88 |
| giul39                                 |              39 |              86 |
| india35                                |              35 |              80 |
| janos-us-ca                            |              39 |              61 |
| nobel-eu                               |              28 |              41 |
| nobel-germany                          |              17 |              26 |
| nobel-us                               |              14 |              21 |
| norway                                 |              27 |              51 |
| pioro40                                |              40 |              89 |
| polska                                 |              12 |              18 |
| sun                                    |              27 |              51 |
| ta1                                    |              24 |              51 |
| ta2                                    |              65 |             108 |
| zib54                                  |              54 |              80 |
| Bestel                                 |              84 |             101 | 
| Darkstrand                             |              28 |              31 | 
| Dial Telecom                           |             193 |             151 |
| euNetworks                             |              15 |              19 |
| INS IXC Services                       |              33 |              41 | 
| Intellifiber                           |              73 |              97 | 
| Interroute                             |             110 |             158 |
| ITC Deltacom                           |             113 |             183 | 
| Kentucky Datalink                      |             754 |             899 |
| Lambdanet                              |              42 |              46 | 
| Nextgen                                |              17 |              20 |
| OTEGlobe                               |              93 |             106 | 
| US Signal                              |              63 |              79 | 
| Viatel                                 |              88 |              92 | 
| Viatel                                 |              92 |              96 | 
| FUNET                                  |              26 |              31 | 
| OPTOSUNET                              |              26 |              49 | 
| PIONIER                                |              36 |              41 | 
| RoEduNet                               |              48 |              52 | 
| SWITCH                                 |              74 |              92 | 



<!---
Cite as: 

```
@misc{githubGitHubFOCSAIoptrix,
	author = {Akanksha Ahuja},
	title = { Optrix: {A} Dataset of Core Optical Network Topologies},
	howpublished = {\url{https://github.com/FOCS-AI/optrix}},
	year = {2023}
}
'''
--->

