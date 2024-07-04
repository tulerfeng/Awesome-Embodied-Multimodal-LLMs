<div align="center">
    <h1>Awesome Embodied Multimodal LLMs <br> (Vison-Language-Action Models)</h1>
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg"/></a>
    <img src=https://img.shields.io/github/stars/tulerfeng/Awesome-Embodied-Multimodal-LLMs.svg?style=social >
</div>

This is a collection of research papers about Embodied Multimodal Large Language Models (VLA models).

If you would like to include your paper or update any details (e.g., code urls, conference information), please feel free to submit a pull request or email me. Any advice is also welcome.




## Table of Contents
- [Awesome-Embodied-Multimodal-LLMs](#Awesome-Embodied-Multimodal-LLMs)
  - [Overview](#Overview-of-Embodied-Multimodal-LLMs)
  - [Models](#Models)
  - [Datasets & Benchmark](#Datasets-&-Benchmark)



## Overview



Embodied Multimodal LLMs integrate vision information and action outputs into large language models (LLMs). Leveraging the rich knowledge and strong reasoning capabilities of LLMs, these models excel in interactively following human instructions, comprehensively understanding the real world, and effectively conducting various embodied tasks. They hold great potential to achieve Artificial General Intelligence (AGI).



## Models

| Title                                                        |                        Introduction                         |    Date    |                             Code                             |
| :----------------------------------------------------------- | :---------------------------------------------------------: | :--------: | :----------------------------------------------------------: |
| [![Star](https://img.shields.io/github/stars/openvla/openvla.svg?style=social&label=Star)]() <br/>[OpenVLA: An Open-Source Vision-Language-Action Model](https://arxiv.org/abs/2406.09246) |   <img width="700" alt="image" src="figures/openvla.png">   | 2024-06-13 |         [Github](https://github.com/openvla/openvla)         |
| [![Star](https://img.shields.io/github/stars/changhaonan/A3VLM.svg?style=social&label=Star)]() <br/>[A3VLM: Actionable Articulation-Aware Vision Language Model](https://arxiv.org/abs/2406.07549) |    <img width="700" alt="image" src="figures/a3vlm.png">    | 2024-06-11 |        [Github](https://github.com/changhaonan/A3VLM)        |
| [![Publish](https://img.shields.io/badge/Conference-ICML'24-blue)]()<br/>[Embodied CoT Distillation From LLM To Off-the-shelf Agents](https://openreview.net/pdf?id=M4Htd52HMH) |    <img width="700" alt="image" src="figures/deder.png">    | 2024-05-02 |                              -                               |
| [![Publish](https://img.shields.io/badge/Conference-ICML'24-blue)]()<br/>[RoboMP$^2$: A Robotic Multimodal Perception-Planning Framework with Multimodal Large Language Models](https://arxiv.org/abs/2404.04929) |   <img width="200" alt="image" src="figures/robomp2.png">   | 2024-04-07 |                              -                               |
| [![Star](https://img.shields.io/github/stars/UMass-Foundation-Model/3D-VLA.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-ICML'24-blue)]()<br/>[3D-VLA: A 3D Vision-Language-Action Generative World Model](https://arxiv.org/abs/2403.09631) |    <img width="700" alt="image" src="figures/3dvla.png">    | 2024-03-14 |  [Github](https://github.com/UMass-Foundation-Model/3D-VLA)  |
| [![Star](https://img.shields.io/github/stars/qizekun/ShapeLLM.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-ECCV'24-blue)]()<br/>[ShapeLLM: Universal 3D Object Understanding for Embodied Interaction](https://arxiv.org/abs/2402.17766) |  <img width="700" alt="image" src="figures/shapellm.png">   | 2024-02-27 |        [Github](https://github.com/qizekun/ShapeLLM)         |
| [![Publish](https://img.shields.io/badge/Conference-RSS'24-blue)]()<br/>[NaVid: Video-based VLM Plans the Next Step for Vision-and-Language Navigation](https://arxiv.org/abs/2402.15852) |    <img width="500" alt="image" src="figures/navid.png">    | 2024-02-24 |                              -                               |
| [![Star](https://img.shields.io/github/stars/UMass-Foundation-Model/MultiPLY.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-CVPR'24-blue)]()<br/>[MultiPLY: A Multisensory Object-Centric Embodied Large Language Model in 3D World](https://arxiv.org/abs/2401.08577) |  <img width="700" alt="image" src="figures/multiply.png">   | 2024-01-16 | [Github](https://github.com/UMass-Foundation-Model/MultiPLY) |
| [![Star](https://img.shields.io/github/stars/clorislili/ManipLLM.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-CVPR'24-blue)]()<br/>[ManipLLM: Embodied Multimodal Large Language Model for Object-Centric Robotic Manipulation](https://arxiv.org/abs/2312.16217) |  <img width="700" alt="image" src="figures/manipllm.png">   | 2023-12-24 |       [Github](https://github.com/clorislili/ManipLLM)       |
| [![Star](https://img.shields.io/github/stars/IranQin/MP5.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-CVPR'24-blue)]()<br/>[MP5: A Multi-modal Open-ended Embodied System in Minecraft via Active Perception](https://arxiv.org/abs/2312.07472) |     <img width="700" alt="image" src="figures/mp5.png">     | 2023-12-12 |           [Github](https://github.com/IranQin/MP5)           |
| [![Star](https://img.shields.io/github/stars/zd11024/NaviLLM.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-CVPR'24-blue)]()<br/>[Towards Learning a Generalist Model for Embodied Navigation](https://arxiv.org/abs/2312.02010) |   <img width="700" alt="image" src="figures/navillm.png">   | 2023-12-04 |         [Github](https://github.com/zd11024/NaviLLM)         |
| [![Star](https://img.shields.io/github/stars/Open3DA/LL3DA.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-CVPR'24-blue)]()<br/>[LL3DA: Visual Interactive Instruction Tuning for Omni-3D Understanding, Reasoning, and Planning](https://arxiv.org/abs/2311.18651) |    <img width="700" alt="image" src="figures/ll3da.png">    | 2023-11-30 |          [Github](https://github.com/Open3DA/LL3DA)          |
| [![Star](https://img.shields.io/github/stars/embodied-generalist/embodied-generalist.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-ICML'24-blue)]()<br>[An Embodied Generalist Agent in 3D World](https://arxiv.org/abs/2311.12871) |     <img width="700" alt="image" src="figures/leo.png">     | 2023-11-18 |      [Github](https://github.com/IST-DASLab/sparsegpt)       |
| [![Star](https://img.shields.io/github/stars/apple/ml-llarp.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-ICLR'24-blue)]()<br/>[Large Language Models as Generalizable Policies for Embodied Tasks](https://arxiv.org/abs/2310.17722) |    <img width="700" alt="image" src="figures/llarp.png">    | 2023-10-26 |         [Github](https://github.com/apple/ml-llarp)          |
| [![Publish](https://img.shields.io/badge/Conference-CoRL'23-blue)]()<br/>[RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control](https://arxiv.org/abs/2307.15818) |     <img width="700" alt="image" src="figures/rt2.png">     | 2023-07-28 |                              -                               |
| [![Star](https://img.shields.io/github/stars/UMass-Foundation-Model/Co-LLM-Agents.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-ICLR'24-blue)]()<br/>[Building Cooperative Embodied Agents Modularly with Large Language Models](https://arxiv.org/abs/2307.02485) |    <img width="700" alt="image" src="figures/coela.png">    | 2023-07-05 | [Github](https://github.com/UMass-Foundation-Model/Co-LLM-Agents) |
| [![Star](https://img.shields.io/github/stars/EmbodiedGPT/EmbodiedGPT_Pytorch.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-NeurIPS'24-blue)]()<br/>[EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought](https://arxiv.org/abs/2305.15021) | <img width="700" alt="image" src="figures/embodiedgpt.png"> | 2023-05-24 | [Github](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch) |
| [![Publish](https://img.shields.io/badge/Conference-ICML'23-blue)]()<br/>[PaLM-E: An Embodied Multimodal Language Model](https://arxiv.org/abs/2303.03378) |    <img width="700" alt="image" src="figures/palme.png">    | 2023-03-06 |                              -                               |









## Datasets & Benchmark

| Title                                                        |                         Introduction                         |    Date    |                           Code                           |
| :----------------------------------------------------------- | :----------------------------------------------------------: | :--------: | :------------------------------------------------------: |
| [![Star](https://img.shields.io/github/stars/facebookresearch/open-eqa.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-CVPR'24-blue)]()<br/>[OpenEQA: Embodied Question Answering in the Era of Foundation Models](https://openaccess.thecvf.com/content/CVPR2024/papers/Majumdar_OpenEQA_Embodied_Question_Answering_in_the_Era_of_Foundation_Models_CVPR_2024_paper.pdf) |   <img width="700" alt="image" src="figures/openeqa.png">    | 2024-06-17 |  [Github](https://github.com/facebookresearch/open-eqa)  |
| [![Star](https://img.shields.io/github/stars/PhyScene/PhyScene.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-CVPR'24-blue)]()<br/>[PhyScene: Physically Interactable 3D Scene Synthesis for Embodied AI](https://arxiv.org/pdf/2404.09465) |    <img width="700" alt="image" src="figures/physcn.png">    | 2024-04-15 | [Github](https://github.com/PhyScene/PhyScene/tree/main) |
| [![Star](https://img.shields.io/github/stars/OpenRobotLab/EmbodiedScan.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-CVPR'24-blue)]()<br/>[EmbodiedScan: A Holistic Multi-Modal 3D Perception Suite Towards Embodied AI](https://arxiv.org/abs/2312.16170) | <img width="700" alt="image" src="figures/embodiedscan.png"> | 2023-12-26 |  [Github](https://github.com/OpenRobotLab/EmbodiedScan)  |
| [![Star](https://img.shields.io/github/stars/allenai/Holodeck.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-CVPR'24-blue)]()<br/>[Holodeck: Language Guided Generation of 3D Embodied AI Environments](https://arxiv.org/abs/2312.09067) |   <img width="300" alt="image" src="figures/holodeck.png">   | 2023-12-14 |      [Github](https://github.com/allenai/Holodeck)       |
| [![Publish](https://img.shields.io/badge/Conference-ICLR'24-blue)]()<br/>[Learning Interactive Real-World Simulators](https://arxiv.org/abs/2310.06114) |    <img width="300" alt="image" src="figures/unisim.png">    | 2023-10-09 |                            -                             |
| [![Star](https://img.shields.io/github/stars/OpenRobotLab/EmbodiedScan.svg?style=social&label=Star)]() [![Publish](https://img.shields.io/badge/Conference-FMDM@NeurIPS'23-blue)]()<br/>[Towards End-to-End Embodied Decision Making via Multi-modal Large Language Model: Explorations with GPT4-Vision and Beyond](https://arxiv.org/abs/2310.02071) |   <img width="200" alt="image" src="figures/pca-eval.png">   | 2023-10-3  |    [Github](https://github.com/pkunlp-icler/PCA-EVAL)    |


















