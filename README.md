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
| :----------------------------------------------------------- | :---------------------------------------------------------: | :--------: | :----------------------------------------------------------: 
| <br/>[VLM-3R: Vision-Language Models Augmented with Instruction-Aligned 3D Reconstruction](https://arxiv.org/pdf/2505.20279) |   <img width="700" alt="image" src="imgs/VLM-3R.png">   | 2025-05 |    [Github](https://github.com/VITA-Group/VLM-3R)   |
| <br/>[LLaVA-4D: Embedding SpatioTemporal Prompt into LMMs for 4D Scene Understanding](https://arxiv.org/abs/2505.12253) |   <img width="700" alt="image" src="imgs/LLaVA-4D.png">   | 2025-05 |        -    |
| <br/>[SSR: Enhancing Depth Perception in Vision-Language Models via Rationale-Guided Spatial Reasoning](https://arxiv.org/abs/2505.12448) |   <img width="700" alt="image" src="imgs/SSR.png">   | 2025-05 |    [Github](https://yliu-cs.github.io/SSR)        |
| <br/>[Perspective-Aware Reasoning in Vision-Language Models via Mental Imagery Simulation](https://arxiv.org/pdf/2504.17207) |   <img width="700" alt="image" src="imgs/APC.png">   | 2025-04 |     [Github](https://apc-vlm.github.io/)     |
| <br/>[SpaceR: Reinforcing MLLMs in Video Spatial Reasoning](https://arxiv.org/abs/2504.01805) |   <img width="700" alt="image" src="imgs/SpaceR.png">   | 2025-04 |          [Github](https://github.com/OuyangKun10/SpaceR)         |
| <br/>[Embodied-R: Collaborative Framework for Activating Embodied Spatial Reasoning in Foundation Models via Reinforcement Learning](https://arxiv.org/abs/2504.12680) |   <img width="700" alt="image" src="imgs/Embodied-R.png">   | 2025-04 |          [Github](https://github.com/EmbodiedCity/Embodied-R.code)   |
| <br/>[SpatialReasoner: Towards Explicit and Generalizable 3D Spatial Reasoning](https://arxiv.org/abs/2504.20024) |   <img width="700" alt="image" src="imgs/SpatialReasoner.png">   | 2025-04 |  [Github](https://spatial-reasoner.github.io/) |
| <br/>[ROSS3D: Reconstructive Visual Instruction Tuning with 3D-Awareness](https://arxiv.org/pdf/2504.01901) |   <img width="700" alt="image" src="imgs/Ross3D.png">   | 2025-04 |      [Github](https://github.com/haochen-wang409/ross3d)   |
| <br/>[SpaRE: Enhancing Spatial Reasoning in Vision-Language Models with Synthetic Data](https://arxiv.org/abs/2504.20648) |   <img width="700" alt="image" src="imgs/SpaRE.png">   | 2025-04 |      -     |
| <br/>[Visual Agentic AI for Spatial Reasoning with a Dynamic API](https://arxiv.org/pdf/2502.06787) |   <img width="700" alt="image" src="imgs/VADAR.png">   | 2025-02 |         [Github](https://glab-caltech.github.io/vadar/)         |
| <br/>[SpatialCoT: Advancing Spatial Reasoning through Coordinate Alignment and Chain-of-Thought for Embodied Task Planning](https://arxiv.org/abs/2501.10074) |   <img width="700" alt="image" src="imgs/SpatialCoT.jpg">   | 2025-01 |         [Github](https://spatialcot.github.io/)         |
| [![Star](https://img.shields.io/github/stars/AnjieCheng/SpatialRGPT.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-NIPS'24-blue)]()<br/>[SpatialRGPT: Grounded Spatial Reasoning in Vision Language Models](https://arxiv.org/abs/2406.01584) |   <img width="700" alt="image" src="imgs/SpatialRGPT.png">   | 2024-06 |         [Github](https://github.com/AnjieCheng/SpatialRGPT)         |
[![Star](https://img.shields.io/github/stars/BAAI-DCAI/SpatialBot.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-ICRA'24-blue)]()[SpatialBot: Precise Spatial Understanding with Vision Language Models](https://arxiv.org/abs/2406.13642) |   <img width="700" alt="image" src="imgs/SpatialBot.png">   | 2024-06 |       [Github](https://github.com/BAAI-DCAI/SpatialBot)     |
|  [![Publish](https://img.shields.io/badge/Conference-CVPR'24-blue)]()<br/>[Learning to Localize Objects Improves Spatial Reasoning in Visual-LLMs](https://arxiv.org/abs/2404.07449) |   <img width="700" alt="image" src="imgs/local.png">   | 2024-04 |         [Github](https://github.com/kahnchana/locvlm)         |
|  [![Publish](https://img.shields.io/badge/Conference-ICLR'24-blue)]()<br/>[Can Transformers Capture Spatial Relations between Objects?](https://arxiv.org/abs/2403.00729) |   <img width="700" alt="image" src="imgs/SpatialSense.png">   | 2024-03 |  [Github](https://github.com/AlvinWen428/spatial-relation-benchmark) |
| [![Star](https://img.shields.io/github/stars/remyxai/VQASynth.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-CVPR'24-green)]()<br/>[SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities](https://arxiv.org/abs/2401.12168) |   <img width="700" alt="image" src="imgs/SpatialVLM.jpg">  | 2024-01 | [Github](https://github.com/remyxai/VQASynth)|
|  <br/>[Proximity QA: Unleashing the Power of Multi-Modal Large Language Models for Spatial Proximity Analysis](https://arxiv.org/abs/2401.17862) |   <img width="700" alt="image" src="imgs/ProximityQA.png">   | 2024-01 |         [Github](https://github.com/NorthSummer/ProximityQA)         |
| <br/>[3DAxiesPrompts: Unleashing the 3D Spatial Task Capabilities of GPT-4V](https://arxiv.org/abs//2312.09738) |   <img width="700" alt="image" src="imgs/Axies.png">   | 2023-12 |    -   |


### Text based
| Title                                                        |                        Introduction                         |    Date    |                             Code                             |
| :----------------------------------------------------------- | :---------------------------------------------------------: | :--------: | :----------------------------------------------------------: |
| <br/>[Imagine while Reasoning in Space: Multimodal Visualization-of-Thought](https://arxiv.org/abs/2501.07542) |   <img width="700" alt="image" src="imgs/MVoT.png">   | 2025-01 |   -       |
| <br/>[Dspy-based Neural-Symbolic Pipeline to Enhance Spatial Reasoning in LLMs](https://arxiv.org/abs/2411.18564) |   <img width="700" alt="image" src="imgs/ASP.png">   | 2024-11 |       -       |
|  [![Publish](https://img.shields.io/badge/Conference-NIPS'24-blue)]()<br/>[Sparkle: Mastering Basic Spatial Capabilities in Vision Language Models Elicits Generalization to Composite Spatial Reasoning](https://arxiv.org/abs/2410.16162) |   <img width="700" alt="image" src="imgs/Sparkle.png">   | 2024-10 |     -     |
|  [![Publish](https://img.shields.io/badge/Conference-ACL'24-blue)]()<br/>[SpaRC and SpaRP: Spatial Reasoning Characterization and Path Generation for Understanding Spatial Reasoning Capability of Large Language Models](https://arxiv.org/abs/2406.04566) |   <img width="700" alt="image" src="imgs/SpaRP.png">   | 2024-06 |         [Github](https://github.com/UKPLab/acl2024-sparc-and-sparp)         |
|  [![Publish](https://img.shields.io/badge/Conference-EMNLP'24-blue)]()<br/>[Beyond Lines and Circles: Unveiling the Geometric Reasoning Gap in Large Language Models](https://arxiv.org/abs/2402.03877) |   <img width="700" alt="image" src="imgs/Geometric.png">   | 2024-02 |       -       |
|  [![Publish](https://img.shields.io/badge/Conference-AAAI'24-blue)]()<br/>[Advancing Spatial Reasoning in Large Language Models: An In-Depth Evaluation and Enhancement Using the StepGame Benchmark](https://arxiv.org/abs/2401.03991) |   <img width="700" alt="image" src="imgs/StepGame.png">   | 2024-01 |      [Github](https://github.com/Fangjun-Li/SpatialLM-StepGame)    |
## Datasets & Benchmark
### Visual based
| Title                                                        |                         Introduction                         |    Date    |                           Code                           |
| :----------------------------------------------------------- | :----------------------------------------------------------: | :--------: | :------------------------------------------------------: |
|  <br/>[Multi-SpatialMLLM: Multi-Frame Spatial Understanding with Multi-Modal Large Language Models](https://arxiv.org/pdf/2505.17015) |   <img width="700" alt="image" src="imgs/Multi-SpatialMLLM.png">   | 2025-05 |             [Github](https://runsenxu.com/projects/Multi-SpatialMLLM)  
|  <br/>[SpatialScore: Towards Unified Evaluation for Multimodal Spatial Understanding](https://arxiv.org/pdf/2505.17012) |   <img width="700" alt="image" src="imgs/SpatialScore.png">   | 2025-05 |  [Github](https://haoningwu3639.github.io/SpatialScore) 
|  <br/>[Visuospatial Cognitive Assistant](https://arxiv.org/pdf/2505.12312) |   <img width="700" alt="image" src="imgs/ViCA.png">   | 2025-05 |             [Github](https://huggingface.co/nkkbr/ViCA) 
|  <br/>[Are Multimodal Large Language Models Ready for Omnidirectional Spatial Reasoning?](https://arxiv.org/pdf/2505.11907) |   <img width="700" alt="image" src="imgs/OmniSR.png">   | 2025-05 | [Github](https://huggingface.co/datasets/UUUserna/OSR-Bench) 
|  <br/>[SITE: towards Spatial Intelligence Thorough Evaluation](https://arxiv.org/pdf/2505.05456) |   <img width="700" alt="image" src="imgs/SITE.png">   | 2025-05 |   [Github](https://wenqi-wang20.github.io/SITE-Bench.github.io/)  
|  <br/>[CameraBench: Towards Understanding Camera Motions in Any Video](http://arxiv.org/abs/2504.15376) |   <img width="700" alt="image" src="imgs/CameraBench.png">   | 2025-04 |  [Github](https://linzhiqiu.github.io/papers/camerabench/)  
|  <br/>[Seeing from Another Perspective: Evaluating Multi-View Understanding in MLLMs](http://arxiv.org/abs/2504.15280) |   <img width="700" alt="image" src="imgs/All-Angle.png">  | 2025-04 | [Github](https://danielchyeh.github.io/All-Angles-Bench/) 
|  <br/>[From Flatland to Space:Teaching Vision-Language Models to Perceive and Reason in 3D](https://arxiv.org/abs/2503.11094) |   <img width="700" alt="image" src="imgs/PAR.png">   | 2025-03 | [Github](https://fudan-zvg.github.io/spar) 
|  <br/>[Open3DVQA: A Benchmark for Comprehensive Spatial Reasoning with Multimodal Large Language Model in Open Space](https://arxiv.org/abs/2503.11094) |   <img width="700" alt="image" src="imgs/Open3DVQA.png">   | 2025-03 |             [Github](https://github.com/WeichenZh/Open3DVQA)
|  <br/>[STI-Bench: Are MLLMs Ready for Precise Spatial-Temporal World Understanding?](http://arxiv.org/abs/2503.23765) |   <img width="700" alt="image" src="imgs/STI-Bench.png">   | 2025-03 |             [Github](https://mint-sjtu.github.io/STI-Bench.io/)      
|  <br/>[CoSpace: Benchmarking Continuous Space Perception Ability for Vision-Language Models](https://arxiv.org/abs/2503.14161) |   <img width="700" alt="image" src="imgs/CoSpace.png">   | 2025-03 |             [Github](https://github.com/THUNLP-MT/CoSpace/)   
|  <br/>[Mind the Gap: Benchmarking Spatial Reasoning in Vision-Language Models](https://arxiv.org/pdf/2503.19707) |   <img width="700" alt="image" src="imgs/SRBench.png">   | 2025-03 |    [Github](https://github.com/stogiannidis/srbench)
|  <br/>[LEGO-Puzzles: How Good Are MLLMs at Multi-Step Spatial Reasoning?](http://arxiv.org/abs/2503.19990) |   <img width="700" alt="image" src="imgs/LEGO.png">   | 2025-03 |            - 
|  <br/>[iVISPAR — An Interactive Visual-Spatial Reasoning Benchmark for VLMs](https://arxiv.org/abs/2502.03214) |   <img width="700" alt="image" src="imgs/iVISPAR.png">   | 2025-02 | [Github](https://github.com/SharkyBamboozle/iVISPAR)  |
|  <br/>[Defining and Evaluating Visual Language Models' Basic Spatial Abilities: A Perspective from Psychometrics](http://arxiv.org/abs/2502.11859) |   <img width="700" alt="image" src="imgs/BSA.png">   | 2025-02 |    -          |
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
|  [![Publish](https://img.shields.io/badge/Conference-NIPS'24-blue)]()<br/>[Is A Picture Worth A Thousand Words? Delving Into Spatial Reasoning for Vision Language Models](https://arxiv.org/abs/2406.14852) |   <img width="700" alt="image" src="imgs/SpatialEval.png">   | 2024-06 |      [Github](https://github.com/jiayuww/SpatialEval)      |     -  |
|  [![Publish](https://img.shields.io/badge/Conference-IJCAI'24-blue)]()<br/>[GSR-Bench: A Benchmark for Grounded Spatial Reasoning Evaluation via Multimodal LLMs](https://arxiv.org/abs/2406.13246) |   <img width="700" alt="image" src="imgs/GSR.png">   | 2024-06 |             -      |
|  [![Publish](https://img.shields.io/badge/Conference-IJCAI'24-blue)]()<br/>[Reframing Spatial Reasoning Evaluation in Language Models: A Real-World Simulation Benchmark for Qualitative Reasoning](https://arxiv.org/abs/2405.15064) |   <img width="700" alt="image" src="imgs/RoomSpace.png">   | 2024-05 |             [Github](https://github.com/Fangjun-Li/RoomSpace)          |
|   [![Publish](https://img.shields.io/badge/Conference-ACL'22-blue)]()[![Star](https://img.shields.io/github/stars/xxxiaol/spatial-commonsense.svg?style=social&label=Star)]()<br/>[Things not Written in Text: Exploring Spatial Commonsense from Visual Signals](https://arxiv.org/abs/2203.08075) |   <img width="700" alt="image" src="imgs/common.png">   | 2022-03 |   [Github](https://github.com/xxxiaol/spatial-commonsense)
|  [![Publish](https://img.shields.io/badge/Conference-CVPR'20-blue)]()<br/>[SPARE3D: ADataset for SPAtial REasoning on Three-View Line Drawings](https://arxiv.org/abs/2003.14034) |   <img width="700" alt="image" src="imgs/SPARE3D.jpg">   | 2020-03 |             [Github](https://github.com/ai4ce/spare3d)          |
### Text based
| Title                                                        |                         Introduction                         |    Date    |                           Code                           |
| :----------------------------------------------------------- | :----------------------------------------------------------: | :--------: | :------------------------------------------------------: |
|  <br/>[Do Multimodal Language Models Really Understand Direction? A Benchmark for Compass Direction Reasoning](https://arxiv.org/abs/2412.16599) |   <img width="700" alt="image" src="imgs/CDR.png">   | 2024-12 |      -
|  <br/>[GRASP: A Grid-Based Benchmark for Evaluating Commonsense Spatial Reasoning](https://arxiv.org/abs/2407.01892) |   <img width="700" alt="image" src="imgs/grasp.png">   | 2024-07 |  -   |

## Findings
| Title                                                        |                         Introduction                         |    Date    |                           Code                           |
| :----------------------------------------------------------- | :----------------------------------------------------------: | :--------: | :------------------------------------------------------: |
|  <br/>[A Call for New Recipes to Enhance Spatial Reasoning in MLLMs](https://arxiv.org/pdf/2504.15037) |   <img width="700" alt="image" src="imgs/call.png">   | 2025-03 |     [Github](https://aka.ms/GeneralAI)   |
|  <br/>[Why Is Spatial Reasoning Hard for VLMs? An Attention Mechanism Perspective on Focus Areas](https://arxiv.org/abs/2503.01773) |   <img width="700" alt="image" src="imgs/AdaptVIS.png">   | 2025-03 |     [Github](https://github.com/shiqichen17/AdaptVis)   |
|  <br/>[Beyond Semantics: Rediscovering Spatial Awareness in Vision-Language Models](https://arxiv.org/abs/2503.17349) |   <img width="700" alt="image" src="imgs/spatialaware.png">   | 2025-03 |     [Github](https://user074.github.io/respatialaware/)   |

## Applications
| Title                                                        |                         Introduction                         |    Date    |                           Code                           |
| :----------------------------------------------------------- | :----------------------------------------------------------: | :--------: | :------------------------------------------------------: |
|  <br/>[SpatialPrompting: Keyframe-driven Zero-Shot Spatial Reasoning with Off-the-Shelf Multimodal Large Language Models](https://arxiv.org/pdf/2505.04911) |   <img width="700" alt="image" src="imgs/SpatialPrompting.png">   | 2025-05 |   - |
|  <br/>[InSpire: Vision-Language-Action Models with Intrinsic Spatial Reasoning](https://arxiv.org/pdf/2505.13888) |   <img width="700" alt="image" src="imgs/InSpire.png">   | 2025-05 |     [Github](https://koorye.github.io/proj/Inspire) |
|  <br/>[EmbodiedVSR: Dynamic Scene Graph-Guided Chain-of-Thought Reasoning for Visual Spatial Tasks](https://arxiv.org/pdf/2503.11089) |   <img width="700" alt="image" src="imgs/EmbodiedVSR.png">   | 2025-03 |   - |
|  <br/>[SOFAR: Language-Grounded Orientation Bridges Spatial Reasoning and Object Manipulation](https://arxiv.org/pdf/2502.13143) |   <img width="700" alt="image" src="imgs/SoFar.png">   | 2025-02 |     [Github](https://qizekun.github.io/sofar) |
|  <br/>[ReasonGrounder: LVLM-Guided Hierarchical Feature Splatting for Open-Vocabulary 3D Visual Grounding and Reasoning](https://arxiv.org/abs/2503.23297) |   <img width="700" alt="image" src="imgs/ReasonGrounder.png">   | 2025-03 |     [Github](https://zhenyangliu.github.io/ReasonGrounder/) |
|  <br/>[VL-Nav: Real-time Vision-Language Navigation with Spatial Reasoning](https://arxiv.org/abs/2502.0093) |   <img width="700" alt="image" src="imgs/VL-Nav.png">   | 2025-02 |     -  |
|  <br/>[SpatialVLA: Exploring Spatial Representations for Visual-Language-Action Models](https://arxiv.org/abs/2501.15830) |   <img width="700" alt="image" src="imgs/SpatialVLA.png">   | 2025-01 |      [Github](https://github.com/SpatialVLA/SpatialVLA)  |
|  <br/>[EMMA-X:AnEmbodied Multimodal Action Model with Grounded Chain of Thought and Look-ahead Spatial Reasoning](https://arxiv.org/abs/2412.11974) |   <img width="700" alt="image" src="imgs/EmmaX.png">   | 2024-12 |      [Github](https://github.com/declare-lab/Emma-X)  |
|  [![Publish](https://img.shields.io/badge/Conference-CVPR'24-blue)]()<br/>[Know Your Neighbors: Improving Single-View Reconstruction via Spatial Vision-Language Reasoning](https://arxiv.org/abs/2404.03658) |   <img width="700" alt="image" src="imgs/KYN.png">   | 2024-04 |     [Github](https://github.com/ruili3/Know-Your-Neighbors)     |
|  [![Publish](https://img.shields.io/badge/Conference-WACV'24-blue)]()<br/>[Improving Vision-and-Language Reasoning via Spatial Relations Modeling](https://arxiv.org/abs/2311.05298) |   <img width="700" alt="image" src="imgs/OPR.png">   | 2023-11 |    -     |
