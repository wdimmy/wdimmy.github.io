---
title: "HQTimer: A Hybrid Q-Learning-Based Timeout Mechanism in Software-Defined Networks"
collection: publications
permalink: /publications/journal
excerpt: 
date: 2018-11-20
venue: 'IEEE Transactions on Network and Service Management'
paperurl: 
citation: 
---

[[PDF]](https://ieeexplore.ieee.org/document/8600383)

<pre style="background-color: rgb(230,230,230);white-space: pre-wrap;">
<font size="1">
@ARTICLE{8600383,
author={Q. {Li} and N. {Huang} and D. {Wang} and X. {Li} and Y. {Jiang} and Z. {Song}},
journal={IEEE Transactions on Network and Service Management},
title={HQTimer: A Hybrid ${Q}$ -Learning-Based Timeout Mechanism in Software-Defined Networks},
year={2019},
volume={16},
number={1},
pages={153-166},
keywords={learning (artificial intelligence);programming languages;software defined networking;HQTimer;hybrid Q-learning-based timeout mechanism;software-defined networking;SDN;data plane programming languages;fine-grained control;limited flow table space;wildcard rules;rule dependency problem;OpenFlow;Control systems;Semantics;Aerospace electronics;Process control;Computer languages;Hardware;Indexes;SDN;timeout mechanism;Q-learning;rule dependency problem},
doi={10.1109/TNSM.2018.2890754},
ISSN={},
month={March},}
</font>
</pre>

## Abstract
Software-defined networking (SDN) has enabled flexible control over the network by leveraging data plane programming languages such as OpenFlow. However, this fine-grained control is potentially at odds with data plane performance due to the high storage load and limited flow table space of SDN switches. Wildcard rules and timeout mechanisms are the main approaches to relieve the load. However, wildcard rules introduce the rule dependency problem, which poses obstacles to preserve the semantics of network policies and design the timeout mechanism. Therefore, exploiting the limited flow table effectively as well as designing a safe timeout mechanism become the main challenge. In this paper, we propose HQTimer: a hybrid Q-learning-based timeout mechanism in SDN. HQTimer employs a hybrid timeout mechanism and a Q-learning-based adaptation logic. HQTimer is safe, as its timeout mechanism ensures the forwarding logic is not violated by the rule dependency problem. HQTimer is adaptive, as it assigns different timeout values to different rules according to the traffic dynamics and the data plane performance based on Q-learning. The extensive experiments based on real and synthetic workloads show that HQTimer achieves both a higher table-hit rate and a lower overflow number compared with existing timeout mechanisms. Specifically, in contrast to a well-tuned, static idle timeout mechanism, HQTimer improves the table-hit rate from 97.6% to 99.4% while decreasing the overflow number by 83.8%.