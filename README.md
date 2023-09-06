# Embodied-Agent-with-LLMs 🤖
This is a curated list of "Embodied AI or robot with Large Language Models" research which is maintained by [haonan](https://github.com/zchoi). Watch this repository for the latest updates!

## Table of Contents 🍃
- [Planning and Manipulation or Pretraining](#planning-and-manipulation-or-pretraining)
- [Multi-Agent Learning and Coordination](#multi-agent-learning-and-coordination)
- [Vision and Language Navigation](#vision-and-language-navigation)
- [Detection](#detection)
- [Interactive Embodied Learning](#interactive-embodied-learning)
- [Rearrangement](#rearrangement)
- [Benchmark](#benchmark)
- [Simulator](#simulator)
- [Others](#others)
  
## Trend of LLM-based Embodied Agent
<p align="center">
    <img src=trend.png >
    <span><b>Figure 1. Growth Development of Embodied Agent with Large Language Models.<sup>[1]</sup></b></span>
</p>

## Methods

> ### Planning and Manipulation or Pretraining


* [**Moving Forward by Moving Backward: Embedding Action Impact over Action Semantics**](https://openreview.net/pdf?id=vmjctNUSWI) [**ICLR 2023**] [[**Project page**](https://prior.allenai.org/projects/action-adaptive-policy)] [[**Github**](https://github.com/KuoHaoZeng/AAP)] <br>
Kuo-Hao Zeng<sup>1</sup>, Luca Weihs<sup>2</sup>, Roozbeh Mottaghi<sup>1</sup>, Ali Farhadi<sup>1</sup><br>
<sup>1</sup>Paul G. Allen School of Computer Science & Engineering, University of Washington,
<sup>2</sup>PRIOR @ Allen Institute for AI


* [**Modeling Dynamic Environments with Scene Graph Memory**](https://openreview.net/attachment?id=NiUxS1cAI4&name=pdf) [**ICML 2023**] <br>
Andrey Kurenkov<sup>1</sup>, Michael Lingelbach<sup>1</sup>, Tanmay Agarwal<sup>1</sup>, Emily Jin<sup>1</sup>, Chengshu Li<sup>1</sup>, Ruohan Zhang<sup>1</sup>, Li Fei-Fei<sup>1</sup>, Jiajun Wu<sup>1</sup>, Silvio Savarese<sup>2</sup>, Roberto Mart´ın-Mart´ın<sup>3</sup><br>
<sup>1</sup>Department of Computer Science, Stanford University
<sup>2</sup>Salesforce AI Research <sup>3</sup>Department of Computer Science, University of Texas at Austin.

* [**Reasoning with Language Model is Planning with World Model**](https://arxiv.org/pdf/2305.14992.pdf) [**Arxiv 2023**] <br>
Shibo Hao<sup>∗♣</sup>, Yi Gu<sup>∗♣</sup>, Haodi Ma<sup>♢</sup>, Joshua Jiahua Hong<sup>♣</sup>, Zhen Wang<sup>♣ ♠</sup>,
Daisy Zhe Wang<sup>♢</sup>, Zhiting Hu<sup>♣</sup><br>
<sup>♣</sup>UC San Diego, <sup>♢</sup>University of Florida,
<sup>♠</sup>Mohamed bin Zayed University of Artificial Intelligence

* [**Do As I Can, Not As I Say: Grounding Language in Robotic Affordances**](https://arxiv.org/pdf/2204.01691.pdf) [**Arxiv 2022**]<br>
Robotics at Google, Everyday Robots

* [**Do Embodied Agents Dream of Pixelated Sheep?: Embodied Decision Making using Language Guided World Modelling**](https://openreview.net/attachment?id=Rm5Qi57C5I&name=pdf) [**ICML 2023**]<br>
Kolby Nottingham<sup>1</sup> Prithviraj Ammanabrolu<sup>2</sup> Alane Suhr<sup>2</sup>
Yejin Choi<sup>3,2</sup> Hannaneh Hajishirzi<sup>3,2</sup> Sameer Singh<sup>1,2</sup> Roy Fox<sup>1</sup><br>
<sup>1</sup>Department of Computer Science, University of California
Irvine <sup>2</sup>Allen Institute for Artificial
Intelligence
<sup>3</sup>Paul G. Allen School of
Computer Science

* [**Context-Aware Planning and Environment-Aware Memory for Instruction Following Embodied Agents**](https://arxiv.org/pdf/2308.07241v2.pdf) [**ICCV 2023**]<br>
Byeonghwi Kim Jinyeon Kim Yuyeong Kim<sup>1,*</sup> Cheolhong Min Jonghyun Choi<sup>†</sup><br>
Yonsei University <sup>1</sup>Gwangju Institute of Science and Technology

* [**Inner Monologue: Embodied Reasoning through Planning with Language Models**](https://openreview.net/pdf?id=3R3Pz5i0tye) [**CoRL 2022**] [[**Project page**](https://innermonologue.github.io/)]<br>
Robotics at Google

* [**Language Models Meet World Models: Embodied Experiences Enhance Language Models**](https://arxiv.org/pdf/2305.10626.pdf) [**Arxiv 2023**] [![](https://img.shields.io/github/stars/szxiangjn/world-model-for-language-model?style=social&label=Code+Stars)](https://github.com/szxiangjn/world-model-for-language-model) [[**Twitter**](https://twitter.com/szxiangjn/status/1659399771126370304)]<br>
Jiannan Xiang<sup>∗♠</sup>, Tianhua Tao<sup>∗♠</sup>, Yi Gu<sup>♠</sup>, Tianmin Shu<sup>♢</sup>,
Zirui Wang<sup>♠</sup>, Zichao Yang<sup>♡</sup>, Zhiting Hu<sup>♠</sup><br>
<sup>♠</sup>UC San Diego, <sup>♣</sup>UIUC, <sup>♢</sup>MIT, <sup>♡</sup>Carnegie Mellon University

* [**AlphaBlock: Embodied Finetuning for Vision-Language Reasoning in Robot Manipulation**](https://arxiv.org/pdf/2305.18898.pdf) [**Arxiv 2023**] [[**Video**](https://www.youtube.com/watch?v=ayAzID1_qQk)]<br>
Chuhao Jin<sup>1*</sup>
, Wenhui Tan<sup>1*</sup>
, Jiange Yang<sup>2*</sup>
, Bei Liu3<sup>†</sup>
, Ruihua Song<sup>1</sup>
, Limin Wang<sup>2</sup>
, Jianlong Fu<sup>3†</sup><br>
<sup>1</sup>Renmin University of China, <sup>2</sup>Nanjing University,
<sup>3</sup>Microsoft Research

* [**A Persistent Spatial Semantic Representation for High-level Natural Language Instruction Execution**](https://openreview.net/pdf?id=NeGDZeyjcKa) [**CoRL 2021**] [![](https://img.shields.io/github/stars/valtsblukis/hlsm?style=social&label=Code+Stars)](https://github.com/valtsblukis/hlsm)  [[**Project page**](https://hlsm-alfred.github.io/)] [[**Poster**](https://openreview.net/attachment?id=NeGDZeyjcKa&name=poster)]<br>
Valts Blukis<sup>1,2</sup>, Chris Paxton<sup>1</sup>, Dieter Fox<sup>1,3</sup>, Animesh Garg<sup>1,4</sup>, Yoav Artzi<sup>2</sup><br>
<sup>1</sup>NVIDIA <sup>2</sup>Cornell University <sup>3</sup>University of Washington <sup>4</sup>University of Toronto, Vector Institute


* [**LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models**](https://arxiv.org/pdf/2212.04088.pdf) [**ICCV 2023**] [[**Project page**](https://dki-lab.github.io/LLM-Planner/)] [[**Github**](https://github.com/OSU-NLP-Group/LLM-Planner)]<br>
Chan Hee Song<sup>1</sup>, Jiaman Wu<sup>1</sup>, Clayton Washington<sup>1</sup>, Brian M. Sadler<sup>2</sup>, Wei-Lun Chao<sup>1</sup>, Yu Su<sup>1</sup><br>
<sup>1</sup>The Ohio State University, <sup>2</sup>DEVCOM ARL


* [**Code as Policies: Language Model Programs for Embodied Control**](https://arxiv.org/pdf/2209.07753) [**Arxiv 2023**] [[**Project page**](https://code-as-policies.github.io/)] [[**Github**](https://code-as-policies.github.io)] [[**Blog**](https://ai.googleblog.com/2022/11/robots-that-write-their-own-code.html)] [[**Colab**](https://colab.research.google.com/drive/124TE4TsGYyrvduzeDclufyvwcc2qbbrE)]<br>
Jacky Liang, Wenlong Huang, Fei Xia, Peng Xu, Karol Hausman, Brian Ichter, Pete Florence, Andy Zeng<br>
Robotics at Google


* [**3D-LLM: Injecting the 3D World into Large Language Models**](https://arxiv.org/abs/2307.12981) [**Arxiv 2023**] [![](https://img.shields.io/github/stars/UMass-Foundation-Model/3D-LLM?style=social&label=Code+Stars)](https://github.com/UMass-Foundation-Model/3D-LLM) <br>
<sup>1</sup>Yining Hong, <sup>2</sup>Haoyu Zhen, <sup>3</sup>Peihao Chen, <sup>4</sup>Shuhong Zheng, <sup>5</sup>Yilun Du, <sup>6</sup>Zhenfang Chen, <sup>6,7</sup>Chuang Gan <br>
<sup>1</sup>UCLA       <sup>2</sup> SJTU       <sup>3</sup> SCUT       <sup>4</sup> UIUC       <sup>5</sup> MIT       <sup>6</sup>MIT-IBM Watson AI Lab       <sup>7</sup> Umass Amherst

* [**VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models**](https://arxiv.org/abs/2307.05973) [**Arxiv 2023**] [[**Project page**](https://voxposer.github.io/)] [[**Online Demo**](https://www.youtube.com/watch?v=Yvn4eR05A3M)]<br>
Wenlong Huang<sup>1</sup>, Chen Wang<sup>1</sup>, Ruohan Zhang<sup>1</sup>, Yunzhu Li<sup>1,2</sup>, Jiajun Wu<sup>1</sup>, Li Fei-Fei<sup>1</sup> <br>
<sup>1</sup>Stanford University <sup>2</sup>University of Illinois Urbana-Champaign

* [**Palm-e: An embodied multimodal language mode**](https://arxiv.org/pdf/2303.03378.pdf) [**ICML 2023**] [[**Project page**](https://palm-e.github.io)]<br>
<sup>1</sup>Robotics at Google <sup>2</sup>TU Berlin 3Google Research    

* [**Large Language Models as Commonsense Knowledge for Large-Scale Task Planning**](https://arxiv.org/pdf/2305.14078.pdf) [**Arxiv 2023**] <br>
Zirui Zhao Wee Sun Lee David Hsu <br>
School of Computing National University of Singapore


> ###  Multi-Agent Learning and Coordination

* [**Demonstration-free Autonomous Reinforcement Learning via Implicit and Bidirectional Curriculum**](https://openreview.net/attachment?id=BMO1vLKq7D&name=pdf) [**ICML 2023**]<br>
Jigang Kim<sup>*1,2</sup> Daesol Cho<sup>*1,2</sup> H. Jin Kim<sup>1,3</sup><br>
<sup>1</sup>Seoul National University, <sup>2</sup>Artificial Intelligence Institute of Seoul National University (AIIS), <sup>3</sup>Automation and Systems Research Institute (ASRI).<br>
***Note: This paper mainly focuses on reinforcement learning for Embodied AI.***

* [**Adaptive Coordination in Social Embodied Rearrangement**](https://openreview.net/attachment?id=BYEsw113sz&name=pdf) [**ICML 2023**]<br>
Andrew Szot<sup>1,2</sup> Unnat Jain<sup>1</sup> Dhruv Batra<sup>1,2</sup> Zsolt Kira<sup>2</sup> Ruta Desai<sup>1</sup> Akshara Rai<sup>1</sup><br>
<sup>1</sup>Meta AI <sup>2</sup>Georgia Institute of Technology.

> ### Vision and Language Navigation

* [**ESC: Exploration with Soft Commonsense Constraints for Zero-shot Object Navigation**](https://openreview.net/attachment?id=GydFM0ZEXY&name=pdf) [**ICML 2023**] <br>
Kaiwen Zhou<sup>1</sup>, Kaizhi Zheng<sup>1</sup>, Connor Pryor<sup>1</sup>, Yilin Shen<sup>2</sup>, Hongxia Jin<sup>2</sup>, Lise Getoor<sup>1</sup>, Xin Eric Wang<sup>1</sup>
<sup>1</sup>University of California, Santa Cruz <sup>2</sup>Samsung Research America.


* [**NavGPT: Explicit Reasoning in Vision-and-Language
Navigation with Large Language Models**](https://arxiv.org/pdf/2305.16986.pdf) [**Arxiv 2023**] <br>
Gengze Zhou<sup>1</sup> Yicong Hong<sup>2</sup> Qi Wu<sup>1</sup> <br>
<sup>1</sup>The University of Adelaide <sup>2</sup>The Australian National University


* [**Instruct2Act: Mapping Multi-modality Instructions to Robotic Actions with Large Language Model**](https://arxiv.org/pdf/2305.11176.pdf) [**Arxiv 2023**] [[**Github**](https://github.com/OpenGVLab/Instruct2Act)]    
Siyuan Huang<sup>1,2</sup> Zhengkai Jiang<sup>4</sup> Hao Dong<sup>3</sup> Yu Qiao<sup>2</sup> Peng Gao<sup>2</sup> Hongsheng Li<sup>5</sup> <br>
<sup>1</sup>Shanghai Jiao Tong University, <sup>2</sup>Shanghai AI Laboratory, <sup>3</sup>CFCS, School of CS, PKU,
<sup>4</sup>University of Chinese Academy of Sciences, <sup>5</sup>The Chinese University of Hong Kong

> ### Detection
* [**DetGPT: Detect What You Need via Reasoning**](https://arxiv.org/pdf/2305.14167.pdf) [**Arxiv 2023**] <br>
Renjie Pi<sup>1∗</sup> Jiahui Gao<sup>2*</sup> Shizhe Diao<sup>1∗</sup> Rui Pan<sup>1</sup> Hanze Dong<sup>1</sup> Jipeng Zhang<sup>1</sup> Lewei Yao<sup>1</sup> Jianhua Han<sup>3</sup> Hang Xu<sup>2</sup>
Lingpeng Kong<sup>2</sup> Tong Zhang<sup>1</sup> <br>
<sup>1</sup>The Hong Kong University of Science and Technology <sup>2</sup>The University of Hong Kong 3Shanghai Jiao Tong University

> ### Interactive Embodied Learning

* [**Learning Affordance Landscapes for
Interaction Exploration in 3D Environments**](https://arxiv.org/pdf/2008.09241.pdf) [**NeurIPS 2020**] [![](https://img.shields.io/github/stars/facebookresearch/interaction-exploration?style=social&label=Code+Stars)](https://github.com/facebookresearch/interaction-exploration) [[Project page](https://vision.cs.utexas.edu/projects/interaction-exploration/)] <br>
Tushar Nagarajan, Kristen Grauman<br>
UT Austin and Facebook AI Research, UT Austin and Facebook AI Research

* [**Embodied Question Answering in Photorealistic Environments with Point Cloud Perception**](https://arxiv.org/abs/1904.03461) [**CVPR 2019 (oral)**] [[**Slides**](https://embodiedqa.org/slides/eqa_matterport.slides.pdf)]<br>
Erik Wijmans<sup>1†</sup>, Samyak Datta<sup>1</sup>, Oleksandr Maksymets<sup>2†</sup>, Abhishek Das<sup>1</sup>, Georgia Gkioxari<sup>2</sup>, Stefan Lee<sup>1</sup>, Irfan Essa<sup>1</sup>, Devi Parikh<sup>1,2</sup>, Dhruv Batra<sup>1,2</sup> <br>
<sup>1</sup>Georgia Institute of Technology, <sup>2</sup>Facebook AI Research

* [**Multi-Target Embodied Question Answering**](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yu_Multi-Target_Embodied_Question_Answering_CVPR_2019_paper.pdf) [**CVPR 2019**] <br>
Licheng Yu<sup>1</sup>, Xinlei Chen<sup>3</sup>, Georgia Gkioxari<sup>3</sup>, Mohit Bansal<sup>1</sup>, Tamara L. Berg<sup>1,3</sup>, Dhruv Batra<sup>2,3</sup><br>
<sup>1</sup>University of North Carolina at Chapel Hill <sup>2</sup>Georgia Tech 3Facebook AI

* [**Neural Modular Control for Embodied Question Answering**](https://arxiv.org/abs/1810.11181) [**CoRL 2018 (Spotlight)**] [[**Project page**](https://embodiedqa.org/)] [[**Github**](https://github.com/facebookresearch/EmbodiedQA)]<br>
Abhishek Das<sup>1</sup>,Georgia Gkioxari<sup>2</sup>, Stefan Lee<sup>1</sup>, Devi Parikh<sup>1,2</sup>, Dhruv Batra<sup>1,2</sup><br>
<sup>1</sup>Georgia Institute of Technology <sup>2</sup>Facebook AI Research

* [**Embodied Question Answering**](https://embodiedqa.org/paper.pdf) [**CVPR 2018 (oral)**] [[**Project page**](https://embodiedqa.org/)] [[**Github**](https://github.com/facebookresearch/EmbodiedQA)]<br>
Abhishek Das<sup>1</sup>, Samyak Datta<sup>1</sup>, Georgia Gkioxari2<sup>2</sup>, Stefan Lee<sup>1</sup>, Devi Parikh<sup>2,1</sup>, Dhruv Batra<sup>2</sup> <br>
<sup>1</sup>Georgia Institute of Technology, <sup>2</sup>Facebook AI Research

> ### Rearrangement
* [**A Simple Approach for Visual Room Rearrangement: 3D Mapping and Semantic Search**](https://openreview.net/pdf?id=fGG6vHp3W9W) [**ICLR 2023**] <br> 
<sup>1</sup>Brandon Trabucco, <sup>2</sup>Gunnar A Sigurdsson, <sup>2</sup>Robinson Piramuthu, <sup>2,3</sup>Gaurav S. Sukhatme, <sup>1</sup>Ruslan Salakhutdinov<br>
<sup>1</sup>CMU, <sup>2</sup>Amazon Alexa AI, <sup>3</sup>University of Southern California

> ### Benchmark


* [**ALFWorld: Aligning Text and Embodied Environments for Interactive Learning**](https://openreview.net/pdf?id=0IOX0YcCdTn) [**ICLR 2021**] [[**Project page**](https://alfworld.github.io/)] [[**Github**](https://github.com/alfworld/alfworld)] <br> 
Mohit Shridhar<sup>†</sup> Xingdi Yuan<sup>♡</sup> Marc-Alexandre Côté<sup>♡</sup>
Yonatan Bisk<sup>‡</sup> Adam Trischler<sup>♡</sup> Matthew Hausknecht<sup>♣</sup><br>
<sup>‡</sup>University of Washington <sup>♡</sup>Microsoft Research, Montréal
<sup>‡</sup>Carnegie Mellon University <sup>♣</sup>Microsoft Research


* [**ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks**](https://arxiv.org/pdf/1912.01734.pdf) [**CVPR 2020**] [[**Project page**](https://askforalfred.com/)] [[**Github**](https://github.com/askforalfred/alfred)] <br> 
Mohit Shridhar<sup>1</sup>
Jesse Thomason<sup>1</sup> Daniel Gordon<sup>1</sup> Yonatan Bisk<sup>1,2,3</sup>
Winson Han<sup>3</sup> Roozbeh Mottaghi<sup>1,3</sup> Luke Zettlemoyer<sup>1</sup> Dieter Fox<sup>1,4</sup><br>
<sup>1</sup>Paul G. Allen School of Computer Sci. & Eng., Univ. of Washington,
<sup>2</sup>Language Technologies Institute @ Carnegie Mellon University,
<sup>3</sup>Allen Institute for AI,
<sup>4</sup>NVIDIA<br>

* [**VIMA: Robot Manipulation with Multimodal Prompts**](https://vimalabs.github.io/assets/vima_paper.pdf) [**ICML 2023**] [[**Project page**](https://vimalabs.github.io/)] [[**Github**](https://github.com/vimalabs/VIMA)] [[**VIMA-Bench**](https://github.com/vimalabs/VimaBench)] <br> 
Yunfan Jiang<sup>1</sup> Agrim Gupta<sup>1†</sup> Zichen Zhang<sup>2†</sup> Guanzhi Wang<sup>3,4†</sup> Yongqiang Dou<sup>5</sup> Yanjun Chen<sup>1</sup>
Li Fei-Fei<sup>1</sup> Anima Anandkumar<sup>3,4</sup> Yuke Zhu<sup>3,6‡</sup> Linxi Fan<sup>3‡</sup><br>

* [**SQA3D: Situated Question Answering in 3D Scenes**](https://arxiv.org/pdf/2210.07474.pdf) [**ICLR 2023**] [[**Project page**](https://sqa3d.github.io/)] [[**Slides**](http://web.cs.ucla.edu/~xm/file/sqa3d_iclr23_slides.pdf)] [[**Github**](https://github.com/SilongYong/SQA3D)]<br> 
Xiaojian Ma<sup>2</sup> Silong Yong<sup>1,3*</sup> Zilong Zheng<sup>1</sup> Qing Li<sup>1</sup> Yitao Liang<sup>1,4</sup> Song-Chun Zhu<sup>1,2,3,4</sup> Siyuan Huang<sup>1</sup><br>
<sup>1</sup>Beijing Institute for General Artificial Intelligence (BIGAI) <sup>2</sup>UCLA <sup>3</sup>Tsinghua University <sup>4</sup>Peking University

* [**IQA: Visual Question Answering in Interactive Environments**](https://openaccess.thecvf.com/content_cvpr_2018/papers/Gordon_IQA_Visual_Question_CVPR_2018_paper.pdf) [**CVPR 2018**] [[**Github**](https://github.com/danielgordon10/thor-iqa-cvpr-2018)] [[**Demo video (YouTube)**](https://www.youtube.com/watch?v=pXd3C-1jr98&feature=youtu.be)]<br>
Danie<sup>1</sup> Gordon1 Aniruddha Kembhavi<sup>2</sup> Mohammad Rastegari<sup>2,4</sup> Joseph Redmon<sup>1</sup> Dieter Fox<sup>1,3</sup> Ali Farhadi<sup>1,2</sup> <br>
<sup>1</sup>Paul G. Allen School of Computer Science, University of Washington <sup>2</sup>Allen Institute for Artificial Intelligence <sup>3</sup>Nvidia <sup>4</sup>Xnor.ai

* [**Env-QA: A Video Question Answering Benchmark for Comprehensive Understanding of Dynamic Environments**](https://openaccess.thecvf.com/content/ICCV2021/papers/Gao_Env-QA_A_Video_Question_Answering_Benchmark_for_Comprehensive_Understanding_of_ICCV_2021_paper.pdf) [**ICCV 2021**] [[**Project page**](https://envqa.github.io/#Overview)] [[**Github**](https://github.com/maybelu9/env-qa)]<br>
Difei Gao<sup>1,2</sup>, Ruiping Wang<sup>1,2,3</sup>, Ziyi Bai<sup>1,2</sup>, Xilin Chen<sup>1</sup>, <br>
<sup>1</sup>Key Laboratory of Intelligent Information Processing of Chinese Academy of Sciences (CAS),
Institute of Computing Technology, CAS,
<sup>2</sup>University of Chinese Academy of Sciences, <sup>3</sup>Beijing Academy of Artificial Intelligence

> ### Simulator
* [**AI2-THOR: An Interactive 3D Environment for Visual AI**](https://arxiv.org/abs/1712.05474) [**Arxiv 2022**] [[**Project page**](http://ai2thor.allenai.org/)] [[**Github**](https://github.com/allenai/ai2thor)]<br> 
Allen Institute for AI, University of Washington, Stanford University, Carnegie Mellon University<br>

* [**iGibson, a Simulation Environment for Interactive Tasks in Large Realistic Scenes**](https://ieeexplore.ieee.org/document/9636667) [**IROS 2021**] [[**Project page**](https://svl.stanford.edu/igibson/)] [[**Github**](https://link.zhihu.com/?target=https%3A//github.com/StanfordVL/iGibson/releases/tag/1.0.0)]<br> 
Bokui Shen*, Fei Xia* et al.<br>

* [**Habitat: A Platform for Embodied AI Research**](https://openaccess.thecvf.com/content_ICCV_2019/papers/Savva_Habitat_A_Platform_for_Embodied_AI_Research_ICCV_2019_paper.pdf) [**ICCV 2019**] [[**Project page**](https://aihabitat.org/)] [[**Habitat-Sim**](https://github.com/facebookresearch/habitat-sim)] [[**Habitat-Lab**](https://github.com/facebookresearch/habitat-lab)] [[**Habitat Challenge**](https://github.com/facebookresearch/habitat-challenge)]<br> 
Facebook AI Research, Facebook Reality Labs, Georgia Institute of Technology, Simon Fraser University, Intel Labs, UC Berkeley<br>

* [**Habitat 2.0: Training Home Assistants to Rearrange their Habitat**](https://scontent.fhkg4-2.fna.fbcdn.net/v/t39.8562-6/10000000_254710466627524_1145871437139214759_n.pdf?_nc_cat=106&ccb=1-7&_nc_sid=ad8a9d&_nc_ohc=ui4K7s8ek_sAX8DLtW0&_nc_ht=scontent.fhkg4-2.fna&oh=00_AfCXUgrrxo_0G2trCUecPU_JeiF0ZwkxGGpiPPUHHk3XCw&oe=64F38AD0) [**NeurIPS 2021**] [[**Project page**](https://research.facebook.com/publications/habitat-2-0-training-home-assistants-to-rearrange-their-habitat/#:~:text=Habitat%202.0%3A%20Training%20Home%20Assistants%20to%20Rearrange%20their,AI%20stack%20%E2%80%93%20data%2C%20simulation%2C%20and%20benchmark%20tasks.)]<br> 
Facebook AI Research, Georgia Tech, Intel Research, Simon Fraser University, UC Berkeley

> ### Others

* [**MINEDOJO: Building Open-Ended Embodied Agents with Internet-Scale Knowledge**](https://proceedings.neurips.cc/paper_files/paper/2022/file/74a67268c5cc5910f64938cac4526a90-Paper-Datasets_and_Benchmarks.pdf) [**NeurIPS 2022**] [[Github](https://github.com/MineDojo/MineDojo)] [![](https://img.shields.io/github/stars/MineDojo/MineDojo?style=social&label=Code+Stars)](https://github.com/MineDojo/MineDojo) [[Project page](https://minedojo.org/)] [[Knowledge Base](https://minedojo.org/knowledge_base.html)] <br>
Linxi Fan<sup>1</sup>
, Guanzhi Wang<sup>2∗</sup>
, Yunfan Jiang<sup>3*</sup>
, Ajay Mandlekar<sup>1</sup>
, Yuncong Yang<sup>4</sup>
,
Haoyi Zhu<sup>5</sup>
, Andrew Tang<sup>4</sup>
, De-An Huang<sup>1</sup>
, Yuke Zhu<sup>1,6†</sup>
, Anima Anandkumar<sup>1,2†</sup><br>
<sup>1</sup>NVIDIA, <sup>2</sup>Caltech, <sup>3</sup>Stanford, <sup>4</sup>Columbia, <sup>5</sup>SJTU, <sup>6</sup>UT Austin

* [**A Survey on LLM-based Autonomous Agents**](https://arxiv.org/pdf/2308.11432.pdf) [**Arxiv 2023**] <br>
Gaoling School of Artificial Intelligence, Renmin University of China

* [**Distilling Internet-Scale Vision-Language Models into Embodied Agents**](https://openreview.net/pdf?id=6vVkGnEpP7) [**ICML 2023**] <br>
Theodore Sumers<sup>1∗</sup> Kenneth Marino<sup>2</sup> Arun Ahuja<sup>2</sup> Rob Fergus<sup>2</sup> Ishita Dasgupta<sup>2</sup> <br>

* [**LISA: Reasoning Segmentation via Large Language Model**](https://arxiv.org/pdf/2308.00692.pdf) [**Arxiv 2023**] [[**Github**](https://github.com/dvlab-research/LISA)] [[**Huggingface Models**](https://huggingface.co/xinlai)] [[**Dataset**](https://drive.google.com/drive/folders/125mewyg5Ao6tZ3ZdJ-1-E3n04LGVELqy?usp=sharing)] [[**Online Demo**](http://103.170.5.190:7860/)]     
TXin Lai<sup>1</sup> Zhuotao Tian<sup>2</sup> Yukang Chen<sup>1</sup> Yanwei Li<sup>1</sup> Yuhui Yuan<sup>3</sup> Shu Liu<sup>2</sup> Jiaya Jia<sup>1,2</sup> <br>
<sup>1</sup>The Chinese University of Hong Kong <sup>2</sup>SmartMore <sup>3</sup>MSRA<br>

* [**React: Synergizing reasoning and acting in language models**](https://arxiv.org/pdf/2210.03629.pdf) [**ICLR 2023**] [![](https://img.shields.io/github/stars/ysymyth/ReAct?style=social&label=Code+Stars)](https://github.com/ysymyth/ReAct) <br>
Shunyu Yao<sup>1∗</sup>, Jeffrey Zhao<sup>2</sup>, Dian Yu<sup>2</sup>, Nan Du<sup>2</sup>, Izhak Shafran<sup>2</sup>, Karthik Narasimhan<sup>1</sup>, Yuan Cao<sup>2</sup> <br>
<sup>1</sup>Department of Computer Science, Princeton University <sup>2</sup>, Google Research, Brain team

> ### Acknowledge

[1] Trend pic from this repo: [A Survey on LLM-based Autonomous Agents](https://github.com/Paitesanshi/LLM-Agent-Survey/tree/main)
