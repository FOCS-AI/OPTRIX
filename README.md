# optrix
- A dataset of publicly available core network topologies
- An analysis-ready dataset of publicly available core optical fibre networks (BT, Internet Topology Zoo, SNDlib, Conus) 

[comment]: < - Source code provides scripts to load and analyze core network dataset>

<!---
- Open Access Networks https://colab.research.google.com/drive/150nUdhXnHzhhF-vzQzaAxKZMa1VudO6o?usp=sharing
- Analysis of Networks Using Graph Metrics and Spectral Metrics https://colab.research.google.com/drive/1fgj_wB547lZuEOSPrlyRFNLtplceCA3L?usp=sharing
- Graph Metrics Analysis of OPtrix dataset https://colab.research.google.com/drive/119xxzyocP2Manm40k4BcGb2MUyfaN16M?usp=sharing
- Graph Metrics Results of Optrix dataset https://docs.google.com/spreadsheets/d/16sZnEqgaBMvUJEP6rhvA6NlxRlGDvNN2GvO_pNgq8yw/edit?usp=sharing
--->

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

<!---
## Types of Files
The code supports loading the following types of files:
- `.adjlist` files: Used to load graphs in adjacency list format.
- `.edgelist` files: Used to load graphs in edge list format.
- `.graphml` files: Used to load graphs in GraphML format.
- `.gexf` files: Used to load graphs in GEXF format.
- `.pickle` files: Used to load graphs in serialized pickle format.
-->
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



## References 
- BT-22 from Strategies for upgrading an operator's backbone network beyond the C-band: Towards multi-band optical networks https://ieeexplore.ieee.org/document/9336212
- SNDlib 1.0—Survivable Network Design Library: https://dl.acm.org/doi/10.5555/1780374.1780385
- CORONET topology https://data.mendeley.com/datasets/p9ky37n727/1
- The Internet Topology Zoo: https://ieeexplore.ieee.org/document/6027859
- Internet Topology Zoo Dataset http://www.topology-zoo.org/
- Making intelligent topology design choices https://ieeexplore.ieee.org/document/9464105

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


<!---
## Small and Large Topologies
**Graphs with 30 nodes or less**

| No. | Name                         | Nodes | Edges | Location | 
|-----|-------------------------------------|-------|-------|-------|
| 1  | 30-Node-ONDPBook-Topology_nodes    | 30    | 36     | US (Check) 
| 2  | abilene                      | 12    | 15     | US     |
| 3  | atlanta                      | 15    | 22     | US     |
| 4  | geant                        | 22    | 36     | Europe     |
| 5  | nobel-eu                     | 28    | 41     | Europe     |
| 6  | nobel-germany                | 17    | 26     | Germany     |
| 7  | nobel-us                     | 14    | 21     | US     |
| 8  | polska                       | 12    | 18     | Poland     |

**Graphs with more than 30 nodes**

| No. | Name                           | Nodes | Edges | Location | 
|-----|-------------------------------------|-------|-------|-------|
| 1  | 60-Node-CONUS-Topology_nodes      | 60    | 79     | US     |
| 2  | 60-Node-ONDPBook-Topology_nodes    | 60    | 77     | US    |
| 3  | CORONET_CONUS_Topology_nodes       | 75    | 99     | US    |
| 4  | CORONET_Global_Topology_nodes      | 100   | 136    | Global    |
| 5  | cost266                           | 37    | 57     | Europe    |
| 6  | france                            | 25    | 45     | France    |
| 7  | germany50                         | 50    | 88     | Germany    |
| 8  | giul39                            | 39    | 86     | Unknown    |
| 9  | india35                           | 35    | 80     | India    |
| 10 | janos-us-ca                       | 39    | 61     | US    |
| 11 | norway                            | 27    | 51     | Norway    |
| 12 | pioro40                           | 40    | 89     | Poland    |
| 13 | sun                               | 27    | 51     | Unknown    |
| 14 | ta1                               | 24    | 51     | Austria    |
| 15 | ta2                               | 65    | 108    | Austria    |
| 16 | zib54                             | 54    | 80     | Unknown    |
| 17 | Darkstrand                        | 28    | 31     | US    |
| 18 | IowaStatewideFiberMap             | 33    | 41     | US     |
| 19 | LambdaNet                         | 42    | 46     | Europe    |
| 20 | PionierL1                         | 36    | 41     | Europe    |
| 21 | VtlWavenet2008                    | 88    | 92     | Europe    |
| 22 | VtlWavenet2011                    | 92    | 96     | Europe    |
| 23 | BT_22                             | 22    | 36     | United Kingdom    |
| 24 | BT_106                            | 106   | 180    | United Kingdom    |

--->


## US Topologies 

| No. |               Name              | Nodes | Edges |
|:---:|:-------------------------------:|:-----:|:-----:|
| 1   | 30-Node-ONDPBook-Topology_nodes | 30    | 36    |
| 2   | abilene                         | 12    | 15    |
| 3   | atlanta                         | 15    | 22    |
| 4   | nobel-us                        | 14    | 21    |
| 5   | 60-Node-CONUS-Topology_nodes    | 60    | 79    |
| 6   | 60-Node-ONDPBook-Topology_nodes | 60    | 77    |
| 7   | CORONET_CONUS_Topology_nodes    | 75    | 99    |
| 8   | janos-us-ca                     | 39    | 61    |
| 9   | Darkstrand                      | 28    | 31    |
| 10  | IowaStatewideFiberMap           | 33    | 41    |

## European Topologies 
| No. |      Name      | Nodes | Edges |
|:---:|:--------------:|:-----:|:-----:|
| 1   | geant          | 22    | 36    |
| 2   | nobel-eu       | 28    | 41    |
| 3   | polska         | 12    | 18    |
| 4   | cost266        | 37    | 57    |
| 5   | france         | 25    | 45    |
| 6   | germany50      | 50    | 88    |
| 7   | ta1            | 24    | 51    |
| 8   | ta2            | 65    | 108   |
| 9   | LambdaNet      | 42    | 46    |
| 10  | PionierL1      | 36    | 41    |
| 11  | VtlWavenet2008 | 88    | 92    |
| 12  | VtlWavenet2011 | 92    | 96    |
| 13  | BT_22          | 22    | 36    |
| 14  | BT_106         | 106   | 180   |


## Unknown Topologies 
| No. |  Name  | Nodes | Edges |
|:---:|:------:|:-----:|:-----:|
| 1   | giul39 | 39    | 86    |
| 2   | sun    | 27    | 51    |
| 3   | zib54  | 54    | 80    |
