<div align="center">
    <h1>Awesome Spatial Intelligence in LLM/VLM</h1>
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg"/></a>
    <img src=https://img.shields.io/github/stars/yyyybq/Awesome-Spatial-Reasoning.svg?style=social >
</div>

This is a collection of research papers about Spatial Intelligence in LLM or VLM.

If you would like to include your paper or update any details (e.g., code urls, conference information), please feel free to submit a pull request or email me. Any advice is also welcome.




## Table of Contents
- [Awesome-Spatial-Reasoning](#Awesome-Spatial-Reasoning)
  - [Overview](#Overview-of-Embodied-Multimodal-LLMs)
  - [Methods](#Methods)
  - [Datasets & Benchmark](#Datasets-&-Benchmark)
  - [Applications](#Applications)



## Overview



Spatial thinking is the foundation of abstract thought. Human uses spatial thinking everywhere (math, 
social network, flow chart, mind map). It's also important for LLM or VLM to build spatial cognition ability to perceive and interact with surroundings. We evaluate spatial ability based on text, single or multi-view images, 3d image or video as input. We enhance spatial ability with visual prompt, text input, image input or image input with 3D.




## Methods
### Visual based
| Title                                                        |                        Introduction                         |    Date    |                             Code                             |
| :----------------------------------------------------------- | :---------------------------------------------------------: | :--------: | :----------------------------------------------------------: |
| <br/>[SpatialCoT: Advancing Spatial Reasoning through Coordinate Alignment and Chain-of-Thought for Embodied Task Planning](https://arxiv.org/abs/2501.10074) |   <img width="700" alt="image" src="imgs/SpatialCoT.jpg">   | 2025-01 |         [Github](https://spatialcot.github.io/)         |
|  [![Publish](https://img.shields.io/badge/Conference-NIPS'24-blue)]()<br/>[Sparkle: Mastering Basic Spatial Capabilities in Vision Language Models Elicits Generalization to Composite Spatial Reasoning](https://arxiv.org/abs/2410.16162) |   <img width="700" alt="image" src="imgs/vot_banner.png">   | 2024-10 |     -     |
| [![Star](https://img.shields.io/github/stars/AnjieCheng/SpatialRGPT.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-NIPS'24-blue)]()<br/>[SpatialRGPT: Grounded Spatial Reasoning in Vision Language Models](https://arxiv.org/abs/2406.01584) |   <img width="700" alt="image" src="imgs/SpatialRGPT.png">   | 2024-06 |         [Github](https://github.com/AnjieCheng/SpatialRGPT)         |
[![Star](https://img.shields.io/github/stars/BAAI-DCAI/SpatialBot.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-ICRA'24-blue)]()[SpatialBot: Precise Spatial Understanding with Vision Language Models](https://arxiv.org/abs/2406.13642) |   <img width="700" alt="image" src="imgs/SpatialBot.png">   | 2024-06 |         [Github](https://github.com/BAAI-DCAI/SpatialBot)         |
|  [![Publish](https://img.shields.io/badge/Conference-CVPR'24-blue)]()<br/>[Learning to Localize Objects Improves Spatial Reasoning in Visual-LLMs](https://arxiv.org/abs/2404.07449) |   <img width="700" alt="image" src="imgs/local.png">   | 2024-04 |         [Github](https://github.com/kahnchana/locvlm)         |
|  [![Publish](https://img.shields.io/badge/Conference-ICLR'24-blue)]()<br/>[Can Transformers Capture Spatial Relations between Objects?](https://arxiv.org/abs/2403.00729) |   <img width="700" alt="image" src="imgs/SpatialSense.png">   | 2024-03 |         [Github](https://github.com/AlvinWen428/spatial-relation-benchmark)         |
| [![Star](https://img.shields.io/github/stars/remyxai/VQASynth.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-CVPR'24-green)]()<br/>[SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities](https://arxiv.org/abs/2401.12168) |   <img width="700" alt="image" src="imgs/SpatialVLM.jpg">   | 2024-01 |         [Github](https://github.com/remyxai/VQASynth)         |
|  <br/>[Proximity QA: Unleashing the Power of Multi-Modal Large Language Models for Spatial Proximity Analysis](https://arxiv.org/abs/2401.17862) |   <img width="700" alt="image" src="imgs/ProximityQA.png">   | 2024-01 |         [Github](https://github.com/NorthSummer/ProximityQA)         |
| <br/>[3DAxiesPrompts: Unleashing the 3D Spatial Task Capabilities of GPT-4V](https://arxiv.org/abs//2312.09738) |   <img width="700" alt="image" src="imgs/Axies.png">   | 2023-12 |    -   |


### Text based
| Title                                                        |                        Introduction                         |    Date    |                             Code                             |
| :----------------------------------------------------------- | :---------------------------------------------------------: | :--------: | :----------------------------------------------------------: |
| <br/>[Imagine while Reasoning in Space: Multimodal Visualization-of-Thought](https://arxiv.org/abs/2501.07542) |   <img width="700" alt="image" src="imgs/MVoT.png">   | 2025-01 |   -       |
| <br/>[Dspy-based Neural-Symbolic Pipeline to Enhance Spatial Reasoning in LLMs](https://arxiv.org/abs/2411.18564) |   <img width="700" alt="image" src="imgs/ASP.png">   | 2024-11 |       -       |
|  [![Publish](https://img.shields.io/badge/Conference-ACL'24-blue)]()<br/>[SpaRC and SpaRP: Spatial Reasoning Characterization and Path Generation for Understanding Spatial Reasoning Capability of Large Language Models](https://arxiv.org/abs/2406.04566) |   <img width="700" alt="image" src="imgs/SpaRP.png">   | 2024-06 |         [Github](https://github.com/UKPLab/acl2024-sparc-and-sparp)         |
|  [![Publish](https://img.shields.io/badge/Conference-EMNLP'24-blue)]()<br/>[Beyond Lines and Circles: Unveiling the Geometric Reasoning Gap in Large Language Models](https://arxiv.org/abs/2402.03877) |   <img width="700" alt="image" src="imgs/Geometric.png">   | 2024-02 |       -       |
|  [![Publish](https://img.shields.io/badge/Conference-AAAI'24-blue)]()<br/>[Advancing Spatial Reasoning in Large Language Models: An In-Depth Evaluation and Enhancement Using the StepGame Benchmark](https://arxiv.org/abs/2401.03991) |   <img width="700" alt="image" src="imgs/StepGame.png">   | 2024-01 |      [Github](https://github.com/Fangjun-Li/SpatialLM-StepGame)    |
## Datasets & Benchmark
### Visual based
| Title                                                        |                         Introduction                         |    Date    |                           Code                           |
| :----------------------------------------------------------- | :----------------------------------------------------------: | :--------: | :------------------------------------------------------: |
|  <br/>[iVISPAR — An Interactive Visual-Spatial Reasoning Benchmark for VLMs](https://arxiv.org/abs/2502.03214) |   <img width="700" alt="image" src="imgs/iVISPAR.png">   | 2025-02 |             [Github](https://github.com/SharkyBamboozle/iVISPAR)          |
|  <br/>[SAT: Spatial Aptitude Training for Multimodal Language Models](https://arxiv.org/abs/2412.07755) |   <img width="700" alt="image" src="imgs/sat.png">   | 2024-12 |             [Github](https://arijitray1993.github.io/SAT/)          |
| <br/>[SPHERE: A Hierarchical Evaluation on Spatial Perception and Reasoning for Vision-Language Models](https://arxiv.org/abs/2412.12693) |   <img width="700" alt="image" src="imgs/SPHERE.png">   | 2024-12 |             [Github](https://github.com/Fangjun-Li/RoomSpace)          |
|  <br/>[3DSRBench: A Comprehensive 3D Spatial Reasoning Benchmark](https://arxiv.org/abs/2412.07825) |   <img width="700" alt="image" src="imgs/3DSRBench.png">   | 2024-12 |             [Github](https://3dsrbench.github.io/)          |
|  [![Star](https://img.shields.io/github/stars/vision-x-nyu/thinking-in-space.svg?style=social&label=Star)]()<br/>[Thinking in Space: How Multimodal Large Language Models See, Remember and Recall Spaces](https://arxiv.org/abs/2412.14171) |   <img width="700" alt="image" src="imgs/Think_in_space.png">   | 2024-12 |             [Github](https://github.com/vision-x-nyu/thinking-in-space)          |
|  <br/>[RoboSpatial: Teaching Spatial Understanding to 2D and 3D Vision-Language Models for Robotics](https://arxiv.org/abs/2411.16537) |   <img width="700" alt="image" src="imgs/RoboSpatial.png">   | 2024-11 |         -   |
|  [![Publish](https://img.shields.io/badge/Conference-EMNLP'24-blue)]()<br/>[An Empirical Analysis on Spatial Reasoning Capabilities of Large Multimodal Models](https://arxiv.org/abs/2411.06048) |   <img width="700" alt="image" src="imgs/SpatialMM.png">   | 2024-11 |  -     |
|  [![Publish](https://img.shields.io/badge/Conference-ICLR'25-blue)]()<br/>[Do Vision-Language Models Represent Space and How? Evaluating Spatial Frame of Reference Under Ambiguities](https://arxiv.org/abs/2410.17385) |   <img width="700" alt="image" src="imgs/Comfort.png">   | 2024-10 |             [Github](https://github.com/sled-group/COMFORT)          | 
|  <br/>[R2D3:ImpartingSpatial Reasoning by Reconstructing 3D Scenes from 2D Images](https://openreview.net/pdf?id=Ku4lylDpjq) |   <img width="700" alt="image" src="imgs/R2D3.png">   | 2024-10 |             [Github](https://github.com/arijitray1993/r2d3/)          | 
|  [![Publish](https://img.shields.io/badge/Conference-EMNLP'24-blue)]()<br/>[Reasoning Paths with Reference Objects Elicit Quantitative Spatial Reasoning in Large Vision-Language Models](https://arxiv.org/abs/2409.09788) |   <img width="700" alt="image" src="imgs/Q.png">   | 2024-09 |             [Github](https://github.com/andrewliao11/Q-Spatial-Bench-code)          |          -     |
|  [![Publish](https://img.shields.io/badge/Conference-NIPSW'24-blue)]()<br/>[Can Vision Language Models Learn from Visual Demonstrations of Ambiguous Spatial Reasoning?](https://arxiv.org/abs/2409.17080) |   <img width="700" alt="image" src="imgs/SVAT.png">   | 2024-09 |       -     |
|  [![Publish](https://img.shields.io/badge/Conference-ACL'24-blue)]()<br/>[EmbSpatial-Bench: Benchmarking Spatial Understanding for Embodied Tasks with Large Vision-Language Models](https://arxiv.org/abs/2406.05756) |   <img width="700" alt="image" src="imgs/Emb.png">   | 2024-06 |             [Github](https://github.com/mengfeidu/EmbSpatial-Bench)          |
|  [![Publish](https://img.shields.io/badge/Conference-EMNLP'24-blue)]()<br/>[TopViewRS: Vision-Language Models as Top-View Spatial Reasoners](https://arxiv.org/abs/2406.05756) |   <img width="700" alt="image" src="imgs/Topviewers.png">   | 2024-06 |             [Github](https://github.com/cambridgeltl/topviewrs)          |
|  [![Publish](https://img.shields.io/badge/Conference-NIPS'24-blue)]()<br/>[Is A Picture Worth A Thousand Words? Delving Into Spatial Reasoning for Vision Language Models](https://arxiv.org/abs/2406.14852) |   <img width="700" alt="image" src="imgs/worth.png">   | 2024-06 |      [Github](https://github.com/jiayuww/SpatialEval)      |     -  |
|  [![Publish](https://img.shields.io/badge/Conference-IJCAI'24-blue)]()<br/>[GSR-Bench: A Benchmark for Grounded Spatial Reasoning Evaluation via Multimodal LLMs](https://arxiv.org/abs/2406.13246) |   <img width="700" alt="image" src="imgs/GSR.png">   | 2024-06 |             -      |
|  [![Publish](https://img.shields.io/badge/Conference-IJCAI'24-blue)]()<br/>[Reframing Spatial Reasoning Evaluation in Language Models: A Real-World Simulation Benchmark for Qualitative Reasoning](https://arxiv.org/abs/2405.15064) |   <img width="700" alt="image" src="imgs/RoomSpace.png">   | 2024-05 |             [Github](https://github.com/Fangjun-Li/RoomSpace)          |
|   [![Publish](https://img.shields.io/badge/Conference-ACL'22-blue)]()[![Star](https://img.shields.io/github/stars/xxxiaol/spatial-commonsense.svg?style=social&label=Star)]()<br/>[Things not Written in Text: Exploring Spatial Commonsense from Visual Signals](https://arxiv.org/abs/2203.08075) |   <img width="700" alt="image" src="imgs/common.png">   | 2022-03 |   [Github](https://github.com/xxxiaol/spatial-commonsense)
|  [![Publish](https://img.shields.io/badge/Conference-CVPR'20-blue)]()<br/>[SPARE3D: ADataset for SPAtial REasoning on Three-View Line Drawings](https://arxiv.org/abs/2003.14034) |   <img width="700" alt="image" src="imgs/SPARE3D.jpg">   | 2020-03 |             [Github](https://github.com/ai4ce/spare3d)          |
### Text based
| Title                                                        |                         Introduction                         |    Date    |                           Code                           |
| :----------------------------------------------------------- | :----------------------------------------------------------: | :--------: | :------------------------------------------------------: |
|  <br/>[Do Multimodal Language Models Really Understand Direction? A Benchmark for Compass Direction Reasoning](https://arxiv.org/abs/2412.16599) |   <img width="700" alt="image" src="imgs/CDR.png">   | 2024-12 |      -
|  <br/>[GRASP: A Grid-Based Benchmark for Evaluating Commonsense Spatial Reasoning](https://arxiv.org/abs/2407.01892) |   <img width="700" alt="image" src="imgs/grasp.png">   | 2024-07 |  -   |

## Applications
| Title                                                        |                         Introduction                         |    Date    |                           Code                           |
| :----------------------------------------------------------- | :----------------------------------------------------------: | :--------: | :------------------------------------------------------: |
|  [![Publish](https://img.shields.io/badge/Conference-WACV'24-blue)]()<br/>[Improving Vision-and-Language Reasoning via Spatial Relations Modeling](https://arxiv.org/abs/2311.05298) |   <img width="700" alt="image" src="imgs/OPR.png">   | 2023-11 |    -     |
|  [![Publish](https://img.shields.io/badge/Conference-CVPR'24-blue)]()<br/>[Know Your Neighbors: Improving Single-View Reconstruction via Spatial Vision-Language Reasoning](https://arxiv.org/abs/2404.03658) |   <img width="700" alt="image" src="imgs/KYN.png">   | 2024-04 |     [Github](https://github.com/ruili3/Know-Your-Neighbors)     |
|  <br/>[VL-Nav: Real-time Vision-Language Navigation with Spatial Reasoning](https://arxiv.org/abs/2502.0093) |   <img width="700" alt="image" src="imgs/VL-Nav.png">   | 2025-02 |     -  |
|  <br/>[EMMA-X:AnEmbodied Multimodal Action Model with Grounded Chain of Thought and Look-ahead Spatial Reasoning](https://arxiv.org/abs/2412.11974) |   <img width="700" alt="image" src="imgs/EmmaX.png">   | 2024-12 |     (https://github.com/declare-lab/Emma-X)  |
|  <br/>[SpatialVLA: Exploring Spatial Representations for Visual-Language-Action Models](https://arxiv.org/abs/2501.15830) |   <img width="700" alt="image" src="imgs/SpatialVLA.png">   | 2025-01 |     (https://github.com/SpatialVLA/SpatialVLA)  |

