# Reinforcement Learning on Graph: A Survey
This open-source library is available to summarize several years of research papers on graph reinforcement learning for the convenience of researchers.

For any ideas and literature on graph reinforcement learning, please contact me.



Mingshuo Nie,

Northeastern University, China.

E: niemingshuo@stumail.neu.edu.cn



# Citation

If you find this work useful in your research, please consider citing:

> @article{mingshuo2022reinforcement,
>      title={Reinforcement Learning on Graph: A Survey},
>      author={Mingshuo, Nie and Dongming, Chen and Dongqi, Wang},
>      journal={arXiv preprint arXiv:2204.06127},
>      year={2022}
>    }


# Reinforcement learning methods

All the reinforcement learning methods used in the literature are as follows.

| RL method                           | Abbr.     | Year | Paper                                                        |
| ----------------------------------- | --------- | ---- | ------------------------------------------------------------ |
| Markov Decision Process             | MDP       | \    | \                                                            |
| Monte Carlo Tree Search             | MCTS      | \    | \                                                            |
| Bernoulli Multi-armed Bandit        | BMAB      | 2005 | [Paper](https://link.springer.com/chapter/10.1007/11564096_42) |
| Q-learning                          | QL        | 1992 | [Paper](https://link.springer.com/article/10.1007/BF00992698) |
| Deep Q-learning Network             | DQN       | 2015 | [Paper](https://www.nature.com/articles/nature14236?wm=book_wap_0005) |
| Double DQN                          | DDQN      | 2016 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/10295) |
| Cascaded DQN                        | CDQN      | 2019 | [Paper](http://proceedings.mlr.press/v97/chen19f.html)       |
| Actor-Critic                        | AC        | 1999 | [Paper](https://proceedings.neurips.cc/paper/1999/hash/6449f44a102fde848669bdd9eb6b76fa-Abstract.html) |
| Advantage Actor-Critic              | A2C       | 2016 | [Paper](http://proceedings.mlr.press/v48/mniha16.html?ref=https://githubhelp.com) |
| Asynchronous Advantage Actor-Critic | A3C       | 2016 | [Paper](http://proceedings.mlr.press/v48/mniha16.html?ref=https://githubhelp.com) |
| Deep Deterministic Policy Gradient  | DDPG      | 2016 | [Paper](https://arxiv.org/pdf/1509.02971.pdf)                |
| proximal policy optimization        | PPO       | 2017 | [Paper](https://arxiv.org/abs/1707.06347)                    |
| neural fitted Q-iteration           | NFQI      | 2005 | [Paper](https://link.springer.com/chapter/10.1007/11564096_32) |
| REINFORCE                           | REINFORCE | 1992 | [Paper](https://link.springer.com/article/10.1007/BF00992696) |



# 2022

| Year | Venue                   | Model              | Title                                                        | Algorithm    | Paper                                                        | Code                                            |
| ---- | ----------------------- | ------------------ | ------------------------------------------------------------ | ------------ | ------------------------------------------------------------ | ----------------------------------------------- |
| 2022 | IEEE TPAMI              | DRL-DBSCAN         | Reinforced, Incremental and Cross-lingual Event Detection From Social Messages | MarGNN       | [Paper](https://ieeexplore.ieee.org/abstract/document/9693189) | [Code](https://github.com/RingBDStack/FinEvent) |
| 2022 | IEEE TKDE               | RTGNN              | Multi-view Tensor Graph Neural Networks Through Reinforced Aggregation | MDP          | [Paper](https://ieeexplore.ieee.org/abstract/document/9711926) | [Code](https://github.com/RingBDStack/RTGNN)    |
| 2022 | IEEE TKDE               | LUCE               | Lifelong Property Price Prediction: A Case Study for the Toronto Real Estate Market | MDP          | [Paper](https://ieeexplore.ieee.org/abstract/document/9551724) | [Code](https://github.com/RingBDStack/LUCE)     |
| 2022 | arXiv                   | BN-GNN             | Deep Reinforcement Learning Guided Graph Neural Networks for Brain Network Analysis | DDQN         | [Paper](https://arxiv.org/abs/2203.10093)                    | \                                               |
| 2022 | ICLR                    | G2RL               | Graph-Enhanced Exploration for Goal-oriented Reinforcement Learning | QL           | [Paper](https://openreview.net/forum?id=rlYiXFdSy70)         | \                                               |
| 2022 | ICLR                    | AGILE              | Know Your Action Set: Learning Action Relations for Reinforcement Learning | PPO\DQN\CDQN | [Paper](https://openreview.net/forum?id=MljXVdp4A3N)         | [Code](https://github.com/clvrai/agile)         |
| 2022 | ICLR                    | MAPSRL-2           | Reinforcement Learning under a Multi-agent Predictive State Representation Model: Method and Theory | QL           | [Paper](https://openreview.net/forum?id=PLDOnFoVm4)          | \                                               |
| 2022 | ICLR                    | SWAT               | Structure-Aware Transformer Policy for Inhomogeneous Multi-Task Reinforcement Learning | AC           | [Paper](https://openreview.net/forum?id=fy_XRVHqly)          | \                                               |
| 2022 | Knowledge-Based Systems | RF                 | Dynamic knowledge graph reasoning based on deep reinforcement learning | AC           | [Paper](https://www.sciencedirect.com/science/article/pii/S0950705122000697?casa_token=YRS68VhBqL4AAAAA:n4gEsG6hkXM5F8K_NZJkI6UywZthFrNrKlVX7oWezOoMOu8dETUS1O6Ra_aMHbKq8RuWx_oX8GGf) | \                                               |
| 2022 | arXiv                   | two-step hybrid RL | Learning Two-Step Hybrid Policy for Graph-Based Interpretable Reinforcement Learning | MDP          | [Paper](https://arxiv.org/abs/2201.08520)                    | \                                               |
| 2022 | arXiv                   | GTA-RL             | Solving Dynamic Graph Problems with Multi-Attention Deep Reinforcement Learning | REINFORCE    | [Paper](https://arxiv.org/abs/2201.04895)                    | [Code](https://github.com/udeshmg/GTA-RL)       |
| 2022 | arXiv                   | AdRumor-RL         | Interpretable and Effective Reinforcement Learning for Attacking against Graph-based Rumor Detection | DQN          | [Paper](https://arxiv.org/abs/2201.05819)                    | \                                               |
| 2022 | arXiv                   | GraphAug           | Automated Data Augmentations for Graph Classification        | MDP          | [Paper](https://arxiv.org/abs/2202.13248)                    | \                                               |
| 2022 | Applied Intelligence    | RLPath             | RLPath: a knowledge graph link prediction method using reinforcement learning based attentive relation path searching and representation learning | MDP          | [Paper](https://link.springer.com/article/10.1007/s10489-021-02672-0) |                                                 |

# 2021

| Year | Venue                                                        | Model         | Title                                                        | Algorithm      | Paper                                                        | Code                                                         |
| ---- | ------------------------------------------------------------ | ------------- | ------------------------------------------------------------ | -------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2021 | IEEE ICDM                                                    | ACE-HGNN      | ACE-HGNN: Adaptive Curvature Exploration Hyperbolic Graph Neural Network | Nash Q-leaning | [Paper](https://ieeexplore.ieee.org/abstract/document/9679192) | \                                                            |
| 2021 | ICML                                                         | SubgraphX     | On Explainability of Graph Neural Networks via Subgraph Explorations | MCTS           | [Paper](http://proceedings.mlr.press/v139/yuan21c/yuan21c.pdf) | [Code](https://github.com/divelab/DIG)                       |
| 2021 | WWW                                                          | SUGAR         | SUGAR: Subgraph Neural Network with Reinforcement Pooling and Self-Supervised Mutual Information Mechanism | QL             | [Paper](https://arxiv.org/pdf/2101.08170.pdf)                | [Code](https://github.com/RingBDStack/SUGAR)                 |
| 2021 | IJCAI                                                        | CORL          | Ordering-Based Causal Discovery with Reinforcement Learning  | MDP            | [Paper](https://www.ijcai.org/proceedings/2021/0491.pdf)     | [Code](https://github.com/huawei-noah/trustworthyAI/tree/master/gcastle) |
| 2021 | ACM Transactions on Information Systems                      | RioGNN        | Reinforced Neighborhood Selection Guided Multi-Relational Graph Neural Networks | MDP            | [Paper](https://arxiv.org/pdf/2104.07886.pdf)                | [Code](https://github.com/safe-graph/RioGNN)                 |
| 2021 | ICML                                                         | RLGN          | Controlling Graph Dynamics with Reinforcement Learning and Graph Neural Networks | PPO            | [Paper](https://proceedings.mlr.press/v139/meirom21a.html)   | \                                                            |
| 2021 | arXiv                                                        | RL            | Reinforcement Learning for Flexibility Design Problems       | MDP            | [Paper](https://arxiv.org/pdf/2101.00355.pdf)                | \                                                            |
| 2021 | Computer‐Aided Civil and Infrastructure Engineering          | GCQ           | Graph neural network and reinforcement learning for multi-agent cooperative control of connected autonomous vehicles | DQN            | [Paper](https://onlinelibrary.wiley.com/doi/epdf/10.1111/mice.12702) | \                                                            |
| 2021 | International Journal of Production Research                 | Park et al.   | Learning to schedule job-shop problems: representation and policy learning using graph neural network and reinforcement learning | PPO            | [Paper](https://www.tandfonline.com/doi/full/10.1080/00207543.2020.1870013?casa_token=6j5GWWqozjMAAAAA%3Aw3DWo-6pgXMdmDjviMzGwjTbof25eJwhi8-hTQMWvEGi6Xu3UlMDecq5pWVKavc2V1uql9gZQNIk) | \                                                            |
| 2021 | Information Sciences                                         | Dynamic graph | Dynamic graph convolutional network for long-term traffic flow prediction with reinforcement learning | PPO            | [Paper](https://www.sciencedirect.com/science/article/pii/S0020025521006976?casa_token=8A0IzshO2lIAAAAA:ZfMgxzJCeofWVPhXKwzP2dKeUYSrhUpvYp6gg-A8m4ywidIDQPaLscd9YInZJ6m9pSDQVNj_yg) | \                                                            |
| 2021 | 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP) | AttnPath      | Incorporating Graph Attention Mechanism into Knowledge Graph Reasoning Based on Deep Reinforcement Learning | MDP            | [Paper](https://aclanthology.org/D19-1264/)                  | \                                                            |
| 2021 | IJCAI                                                        | RLH           | Reasoning like human: Hierarchical reinforcement learning for knowledge graph reasoning | MDP            | [Paper](https://www.ijcai.org/Proceedings/2020/0267.pdf)     | \                                                            |
| 2021 | IEEE Communications Letters                                  | DeepOpt       | Combining Deep Reinforcement Learning With Graph Neural Networks for Optimal VNF Placement | REINFORCE      | [Paper](https://ieeexplore.ieee.org/abstract/document/9201405) | \                                                            |
| 2021 | ACM SIGIR                                                    | UNICORN       | Unified conversational recommendation policy learning via graph-based reinforcement learning | DDQN           | [Paper](https://dl.acm.org/doi/abs/10.1145/3404835.3462913?casa_token=Ix1wg9PKFQMAAAAA:NcPx2lHhkyjctqruT0NeAgSI4Adlr3tcAKmdDXE9yF0EezK4JOiSD-tqyqaHkw-GCLoZIUJs044-nTI) | \                                                            |
| 2021 | IEEE Transactions on Intelligent Transportation Systems      | IG-RL         | IG-RL: Inductive Graph Reinforcement Learning for Massive-Scale Traffic Signal Control | MDP            | [Paper](https://ieeexplore.ieee.org/abstract/document/9405489) | [Code](https://github.com/FXDevailly/IG-RL)                  |
| 2021 | Neurocomputing                                               | MGRL          | MGRL: Graph neural network based inference in a Markov network with reinforcement learning for visual navigation | A2C            | [Paper](https://www.sciencedirect.com/science/article/pii/S0925231220312583?casa_token=lIjL9LYKxMsAAAAA:b5yF5zkYm4LVlFbzngRr4z6hno92cW9fF8zY3jf5KA2tRHUhdPMl0zG6IJaM1hcUFEtIAnzkuA) | \                                                            |
| 2021 | IEEE Transactions on Intelligent Transportation Systems      | SAGE-Garph    | Deep Reinforcement Learning With Graph Representation for Vehicle Repositioning | DDQN           | [Paper](https://ieeexplore.ieee.org/abstract/document/9592687) | \                                                            |
| 2021 | arXiv                                                        | TITer         | TimeTraveler: Reinforcement Learning for Temporal Knowledge Graph Forecasting | REINFORCE      | [Paper](https://arxiv.org/abs/2109.04101)                    | [Code](https://github.com/JHL-HUST/TITer/)                   |
| 2021 | IEEE Internet of Things Journal                              | GRLO          | Graph Reinforcement Learning based Task offloading for Multi-access Edge Computing | AC             | [Paper](https://ieeexplore.ieee.org/abstract/document/9592681) | \                                                            |
| 2021 | arXiv                                                        | SparRL        | SparRL: Graph Sparsification via Deep Reinforcement Learning | MDP            | [Paper](https://arxiv.org/abs/2112.01565)                    | [Code](https://github.com/rwickman/SparRL-PyTorch)           |
| 2021 | The 10th International Joint Conference on Knowledge Graphs  | PAAR          | Multi-hop Knowledge Graph Reasoning Based on Hyperbolic Knowledge Graph Embedding and Reinforcement Learning | MDP            | [Paper](https://dl.acm.org/doi/abs/10.1145/3502223.3502224?casa_token=xxZacBuT3tcAAAAA:YLCYLZlqj_W4J7lsXx03GA9lehdSAZVNoRAlXOSjgueLrHM2jkAdcFaCByLiGSNQv8xsbp1SJ6rJ) | [Code](https://github.com/seukgcode/PAAR)                    |
| 2021 | arXiv                                                        | Vulcan        | Vulcan: Solving the Steiner Tree Problem with Graph Neural Networks and Deep Reinforcement Learning | DDQN           | [Paper](https://arxiv.org/abs/2111.10810)                    | \                                                            |
| 2021 | KSEM                                                         | Zheng et al.  | Hierarchical Policy Network with Multi-agent for Knowledge Graph Reasoning Based on Reinforcement Learning | REINFORCE      | [Paper](https://link.springer.com/chapter/10.1007/978-3-030-82136-4_36) | \                                                            |

# 2020

| Year | Venue                                            | Model              | Title                                                        | Algorithm  | Paper                                                        | Code                                                         |
| ---- | ------------------------------------------------ | ------------------ | ------------------------------------------------------------ | ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2020 | KDD                                              | Policy-GNN         | Policy-GNN: Aggregation Optimization for Graph Neural Networks | DQN        | [Paper](https://dl.acm.org/doi/pdf/10.1145/3394486.3403088)  | [Code](https://github.com/lhenry15/Policy-GNN)               |
| 2020 | IJCAI                                            | eGCN               | Dynamic Electronic Toll Collection via Multi-Agent Deep Reinforcement Learning with Edge-Based Graph Convolutional Networks | MDP        | [Paper](https://www.ijcai.org/Proceedings/2019/0635.pdf)     | \                                                            |
| 2020 | WWW                                              | NIPA               | Adversarial Attacks on Graph Neural Networks via Node Injections: A Hierarchical Reinforcement Learning Approach | DQN        | [Paper](https://par.nsf.gov/servlets/purl/10146600)          | \                                                            |
| 2020 | CIKM                                             | CARE-GNN           | Enhancing Graph Neural Network-based Fraud Detectors against Camouflaged Fraudsters | BMAB       | [Paper](https://arxiv.org/pdf/2008.08692.pdf)                | [Code](https://github.com/YingtongDou/CARE-GNN)              |
| 2020 | arXiv                                            | RL-HGNN            | Reinforcement Learning Enhanced Heterogeneous Graph Neural Network | DQN        | [Paper](https://arxiv.org/pdf/2010.13735.pdf)                | \                                                            |
| 2020 | ICLR                                             | RL-BIC             | Causal Discovery with Reinforcement Learning                 | AC         | [Paper](https://arxiv.org/pdf/1906.04477v4.pdf)              | [Code](https://github.com/huawei-noah/trustworthyAI/tree/master/Causal_Structure_Learning/Causal_Discovery_RL) |
| 2020 | ICLR                                             | RL-based Graph2Seq | Reinforcement Learning Based Graph-to-Sequence Model for Natural Question Generation | REINFORCE  | [Paper](https://arxiv.org/pdf/1908.04942.pdf)                | [Code](https://github.com/hugochan/RL-based-Graph2Seq-for-NQG) |
| 2020 | IEEE Journal on Selected Areas in Communications | A3C+GCN            | Automatic Virtual Network Embedding: A Deep Reinforcement Learning Approach With Graph Convolutional Networks | A3C        | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9060910&tag=1) | \                                                            |
| 2020 | ICLR                                             | DGN                | Graph Convolutional Reinforcement Learning                   | QL         | [Paper](https://openreview.net/pdf?id=HkxdQkSYDB)            | [Code](https://github.com/PKU-AI-Edge/DGN/)                  |
| 2020 | ACM SIGIR                                        | KGQR               | Interactive Recommender System via Knowledge Graph-enhanced Reinforcement Learning | DQN        | [Paper](https://dl.acm.org/doi/abs/10.1145/3397271.3401174?casa_token=jnHUbUyBhvEAAAAA:P3O0wQTjYDIbf2-p0iWjPUq_-LDF2swf-lK05JX-8GAwg8B_Lr5knQ59MLTr-cm9UMf622HldX4) | \                                                            |
| 2020 | Journal of cheminformatics                       | DeepGraphMolGen    | DeepGraphMolGen, a multi-objective, computational strategy for generating molecules with desirable properties: a graph convolution and reinforcement learning approach | PPO        | [Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00454-3) | [Code](https://github.com/dbkgroup/prop_gen)                 |
| 2020 | 57th ACM/IEEE Design Automation Conference (DAC) | GCN-RL             | GCN-RL Circuit Designer: Transferable Transistor Sizing with Graph Neural Networks and Reinforcement Learning | AC         | [Paper](https://ieeexplore.ieee.org/abstract/document/9218757) | \                                                            |
| 2020 | arXiv                                            | KG-A2C             | Graph Constrained Reinforcement Learning for Natural Language Action Spaces | A2C        | [Paper](https://arxiv.org/abs/2001.08837)                    | [Code](https://github.com/rajammanabrolu/KG-A2C)             |
| 2020 | ACM SIGKDD                                       | IMUP               | Incremental Mobile User Profiling: Reinforcement Learning with Spatial Knowledge Graph for Modeling Event Streams | DQN        | [Paper](https://dl.acm.org/doi/abs/10.1145/3394486.3403128?casa_token=MZ4zRpTEOq0AAAAA:K0HSMNZ-bb8VDNFZpvmybQI5rYtZmMS2hphDgmMgJheQu1WqBvton-Nl0P_gP7RzNMRqNOYT_u0) | \                                                            |
| 2020 | Knowledge-Based Systems                          | ADRL               | ADRL: An attention-based deep reinforcement learning framework for knowledge graph reasoning | AC         | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705120302525) | \                                                            |
| 2020 | Knowledge-Based Systems                          | GRL                | GRL: Knowledge graph completion with GAN-based reinforcement learning | DDPG       | [Paper](https://www.sciencedirect.com/science/article/pii/S0950705120305505?casa_token=tIbI7j3_I-YAAAAA:vEYPcA1cJZE8KHZJpY3phmz4RhZdfscI7yzTX0SbnVqcXHRIc0wFgBqG8qZFbId5QDrq4ZnsUyFd) | \\                                                           |
| 2020 | IEEE Access                                      | NAKASHIMA et al.   | Deep Reinforcement Learning-Based Channel Allocation for Wireless LANs With Graph Convolutional Networks | DDQN       | [Paper](https://ieeexplore.ieee.org/abstract/document/8993737) | \                                                            |
| 2020 | IEEE Access                                      | SILVA et al.       | Temporal Graph Traversals Using Reinforcement Learning With Proximal Policy Optimization | PPO        | [Paper](https://ieeexplore.ieee.org/abstract/document/9055369) | \                                                            |
| 2020 | IEEE Access                                      | Wang et al.        | Risk-Aware Identification of Highly Suspected COVID-19 Cases in Social IoT: A Joint Graph Theory and Reinforcement Learning Approach | Q-learning | [Paper](https://ieeexplore.ieee.org/abstract/document/9121230) | \                                                            |
| 2020 | KDD                                              | XGNN               | XGNN: Towards Model-Level Explanations of Graph Neural Networks | MDP        | [Paper](https://dl.acm.org/doi/abs/10.1145/3394486.3403085)  | \                                                            |
| 2020 | NeurIPS                                          | GPA                | Graph Policy Network for Transferable Active Learning on Graphs | MDP        | [Paper](https://proceedings.neurips.cc/paper/2020/hash/73740ea85c4ec25f00f9acbd859f861d-Abstract.html) | [Code](https://github.com/ShengdingHu/GraphPolicyNetworkActiveLearning) |
| 2020 | AAAI/ACM Conference on AI                        | GAEA               | GAEA: Graph Augmentation for Equitable Access via Reinforcement Learning | MDP        | [Paper](https://ui.adsabs.harvard.edu/abs/2020arXiv201203900S/abstract) | [Code](https://github.com/salesforce/GAEA)                   |

# 2019

| Year | Venue                                                        | Model             | Title                                                        | Algorithm | Paper                                                        | Code                                                         |
| ---- | ------------------------------------------------------------ | ----------------- | ------------------------------------------------------------ | --------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2019 | CIKM                                                         | CompNet           | Order-free Medicine Combination Prediction with Graph Convolutional Reinforcement Learning | DQN       | [Paper](https://staff.fnwi.uva.nl/m.derijke/wp-content/papercite-data/pdf/wang-2019-order-free.pdf) | [Code](https://github.com/WOW5678/CompNet)                   |
| 2019 | AISTATS                                                      | GRPI              | Representation Learning on Graphs: A Reinforcement Learning Application | MDP       | [Paper](http://proceedings.mlr.press/v89/madjiheurem19a/madjiheurem19a.pdf) | [Code](https://github.com/LASP-UCL/Graph-RL)                 |
| 2019 | arXiv                                                        | DRL+GNN           | Deep Reinforcement Learning meets Graph Neural Networks: exploring a routing optimization use case | DQN       | [Paper](https://arxiv.org/pdf/1910.07421v2.pdf)              | [Code](https://github.com/knowledgedefinednetworking/DRL-GNN) |
| 2019 | arXiv                                                        | AGNN              | Auto-GNN: Neural Architecture Search of Graph Neural Networks | REINFORCE | [Paper](https://arxiv.org/pdf/1909.03184.pdf)                | \                                                            |
| 2019 | NeurIPS                                                      | GMETAEXP          | Learning Transferable Graph Exploration                      | MDP       | [Paper](https://proceedings.neurips.cc/paper/2019/file/afe434653a898da20044041262b3ac74-Paper.pdf) | \                                                            |
| 2019 | KDD                                                          | GTPN              | Graph Transformation Policy Network for Chemical Reaction Prediction | A2C       | [Paper](https://arxiv.org/pdf/1812.09441.pdf)                | \                                                            |
| 2019 | arXiv                                                        | GPN               | Combinatorial Optimization by Graph Pointer Networks and Hierarchical Reinforcement Learning | REINFORCE | [Paper](https://arxiv.org/abs/1911.04936)                    | [Code](https://github.com/qiang-ma/graph-pointer-network)    |
| 2019 | *IEEE Transactions on Network and Service Management*        | DDPG-HFA          | A Deep Reinforcement Learning Approach for VNF Forwarding Graph Embedding | DDPG      | [Paper](https://ieeexplore.ieee.org/abstract/document/8873660) | \                                                            |
| 2019 | ICDE                                                         | RQL               | Adaptive Dynamic Bipartite Graph Matching: A Reinforcement Learning Approach | QL        | [Paper](https://ieeexplore.ieee.org/abstract/document/8731455) | \                                                            |
| 2019 | Acta Astronautica                                            | Das-Stuart et al. | Rapid trajectory design in complex environments enabled by reinforcement learning and graph search strategies | MDP       | [Paper](https://www.sciencedirect.com/science/article/pii/S0094576518304156) | \                                                            |
| 2019 | arXiv                                                        | Ekar              | Ekar: An Explainable Method for Knowledge Aware Recommendation | MDP       | [Paper](https://ui.adsabs.harvard.edu/abs/2019arXiv190609506S/abstract) | \                                                            |
| 2019 | arXiv                                                        | RL-VAE            | Decoding Molecular Graph Embeddings with Reinforcement Learning | MDP       | [Paper](https://arxiv.org/abs/1904.08915)                    | \                                                            |
| 2019 | International Symposium on Problems of Redundancy in Information and Control Systems (RED) | MAGNet            | MAGNet: Multi-agent Graph Network for Deep Multi-agent Reinforcement Learning | AC        | [Paper](https://ieeexplore.ieee.org/abstract/document/9003345) | \                                                            |
| 2019 | ACM SIGIR                                                    | PGPR              | Reinforcement Knowledge Graph Reasoning for Explainable Recommendation | REINFORCE | [Paper](https://dl.acm.org/doi/abs/10.1145/3331184.3331203?casa_token=rH-9rqcddjIAAAAA:HNQM9AflQOpCcSNZfjXMAFCZCEP7bmcHzeFTm3Zyoj5l63ryhmmWgVcliQ5iOJTyfQVY65HCsGpJLzM) | [Code](https://github.com/orcax/PGPR)                        |
| 2019 | arXiv                                                        | NIPA              | Node Injection Attacks on Graphs via Reinforcement Learning  | DQN       | [Paper](https://arxiv.org/abs/1909.06543)                    | \                                                            |
| 2019 | DRL4KDD                                                      | Rel4KC            | Rel4KC: A Reinforcement Learning Agent for Knowledge Graph Completion and Validation | MDP       | [Paper](http://www.cse.msu.edu/~zhaoxi35/DRL4KDD/1.pdf)      | [Code](https://github.com/xlindii/Rel4KC)                    |
| 2019 | arXiv                                                        | ReWatt            | Attacking Graph Convolutional Networks via Rewiring          | MDP       | [Paper](https://arxiv.org/abs/1906.03750)                    | \                                                            |
| 2019 | ICDM                                                         | GDPNet            | Learning Robust Representations with Graph Denoising Policy Network | MDP       | [Paper](https://ieeexplore.ieee.org/abstract/document/8970731) | \                                                            |

# 2018

| Year | Venue                                                        | Model          | Title                                                        | Algorithm                                            | Paper                                                        | Code                                                      |
| ---- | ------------------------------------------------------------ | -------------- | ------------------------------------------------------------ | ---------------------------------------------------- | ------------------------------------------------------------ | --------------------------------------------------------- |
| 2018 | arXiv                                                        | DGN            | Graph Convolutional Reinforcement Learning for Multi-Agent Cooperation | DQN                                                  | [Paper](https://arxiv.org/pdf/1810.09202v1.pdf)              | [Code](https://github.com/PKU-AI-Edge/DGN)                |
| 2018 | ICML                                                         | RL-S2V         | Adversarial Attack on Graph Structured Data                  | Q-learning                                           | [Paper](http://proceedings.mlr.press/v80/dai18b/dai18b.pdf)  | -                                                         |
| 2018 | NeurIPS                                                      | GCPN           | Graph convolutional policy network for goal-directed molecular graph generation | MDP                                                  | [Paper](https://arxiv.org/pdf/1806.02473.pdf)                | [Code](https://github.com/bowenliu16/rl_graph_generation) |
| 2018 | ICLR                                                         | NerveNet       | NerveNet: Learning Structured Policy with Graph Neural Networks | PPO                                                  | [Paper](https://openreview.net/pdf?id=S1sqHMZCb)             | \                                                         |
| 2018 | arXiv                                                        | KG-DQN         | Playing Text-Adventure Games with Graph-Based Deep Reinforcement Learning | DQN                                                  | [Paper](https://arxiv.org/pdf/1812.01628.pdf)                | [Code](https://github.com/rajammanabrolu/KG-DQN)          |
| 2018 | COLING                                                       | Chen et al.    | Structured Dialogue Policy with Graph Neural Networks        | REINFORCE                                            | [Paper](https://aclanthology.org/C18-1107.pdf)               | \                                                         |
| 2018 | arXiv                                                        | Hamrick et al. | Relational inductive bias for physical construction in humans and machines | Q-learning                                           | [Paper](https://arxiv.org/pdf/1806.01203.pdf)                | \                                                         |
| 2018 | AAAI                                                         | ASNets         | Action Schema Networks: Generalised Policies with Deep Learning | MDP                                                  | [Paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17207/16202) | [Code](https://github.com/qxcv/asnets)                    |
| 2018 | PMLR                                                         | Zhang et al.   | Fully Decentralized Multi-Agent Reinforcement Learning with Networked Agents. | Actor-Critic                                         | [Paper](http://proceedings.mlr.press/v80/zhang18n.html)      | \                                                         |
| 2018 | International Conference on Intelligent Transportation       | NFQI           | Traffic Signal Control Based on Reinforcement Learning with Graph Convolutional Neural Nets | NFQI                                                 | [Paper](https://ieeexplore.ieee.org/abstract/document/8569301) | \                                                         |
| 2018 | IEEE International Conference on Data Mining Workshops (ICDMW) | MARLPaR        | Path Reasoning over Knowledge Graph: A Multi-agent and Reinforcement Learning Based Method | MDP                                                  | [Paper](https://ieeexplore.ieee.org/abstract/document/8637433) | \                                                         |
| 2018 | IEEE International Conference on Big Data (Big Data)         | Obara et al.   | Deep Reinforcement Learning Approach for Train Rescheduling Utilizing Graph Theory | DQN                                                  | [Paper](https://ieeexplore.ieee.org/abstract/document/8622214) | \                                                         |
| 2018 | ICLR                                                         | ReinforceWalk  | ReinforceWalk: Learning to Walk in Graph with Monte Carlo Tree Search | MCTS                                                 | [Paper](https://openreview.net/pdf?id=HJCRT81DM)             | \                                                         |
| 2018 | Conference on Empirical Methods in Natural Language Processing | Lin et al.     | Multi-Hop Knowledge Graph Reasoning with Reward Shaping      | REINFORCE                                            | [Paper](https://arxiv.org/abs/1808.10568)                    | \                                                         |
| 2018 | arXiv                                                        | MolGAN         | MolGAN: An implicit generative model for small molecular graphs | MDP                                                  | [Paper](https://arxiv.org/abs/1805.11973)                    | \                                                         |
| 2018 | ACM SIGKDD                                                   | GAM            | Graph Classification using structural attention              | Partially Observable Markov Decision Process (POMDP) | [Paper](https://dl.acm.org/doi/abs/10.1145/3219819.3219980)  | \                                                         |

# 2017

| List | Year | Venue | Model    | Title                                                        | Algorithm | Paper                                                        | Code                                                 |
| ---- | ---- | ----- | -------- | ------------------------------------------------------------ | --------- | ------------------------------------------------------------ | ---------------------------------------------------- |
| o    | 2017 | NIPS  | S2V-DQN  | Learning Combinatorial Optimization Algorithms over Graphs   | QL        | [Paper](https://proceedings.neurips.cc/paper/2017/file/d9896106ca98d3d05b8cbdf4fd8b13a1-Paper.pdf) | [Code](https://github.com/Hanjun-Dai/graph_comb_opt) |
| o    | 2017 | arXiv | Deeppath | Deeppath: A reinforcement learning method for knowledge graph reasoning | DQN       | [Paper](https://arxiv.org/abs/1707.06690)                    | [Code](https://github.com/xwhan/DeepPath)            |
| o    | 2017 | ICLR  | MINERVA  | Go for a Walk and Arrive at the Answer: Reasoning Over Paths in Knowledge Bases using Reinforcement Learning | REINFORCE | [Paper](https://arxiv.org/abs/1711.05851)                    | [Code](https://github.com/shehzaadzd/MINERVA)        |
| o    | 2017 | arXiv | KBGAN    | KBGAN: Adversarial Learning for Knowledge Graph Embeddings   | REINFORCE | [Paper](https://arxiv.org/abs/1711.04071)                    | [Code](https://github.com/cai-lw/KBGAN)              |
