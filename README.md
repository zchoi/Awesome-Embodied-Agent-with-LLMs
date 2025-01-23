# 🤖 Awesome-Embodied-Agent-with-LLMs [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
> This is a curated list of "Embodied AI or agent with Large Language Models" research which is maintained by [haonan](https://github.com/zchoi).
<img src="https://user-images.githubusercontent.com/7837172/44953557-0fb54e80-aec9-11e8-9d38-2388bc70c5c5.png" width=15% align="right" /> 

Watch this repository for the latest updates and **feel free to raise pull requests if you find some interesting papers**!


## News🔥
[2024/08/01] Created a new board about social agent and role-playing. 🧑‍🧑‍🧒‍🧒  <br>
[2024/06/28] Created a new board about agent self-evolutionary research. 🤖 <br>
[2024/06/07] Add **Mobile-Agent-v2**, a mobile device operation assistant with effective navigation via multi-agent collaboration. 🚀 <br>
[2024/05/13] Add "**Learning Interactive Real-World Simulators**"——outstanding paper award in ICLR 2024 🥇.<br>
[2024/04/24] Add "**A Survey on Self-Evolution of Large Language Models**", a systematic survey on self-evolution in LLMs! 💥<br>
[2024/04/16] Add some CVPR 2024 papers. <br>
[2024/04/15] Add **MetaGPT**, accepted for oral presentation (top 1.2%) at ICLR 2024, **ranking #1** in the LLM-based Agent category. 🚀 <br>
[2024/03/13] Add **CRADLE**, an interesting paper exploring LLM-based agent in Red Dead Redemption II！🎮


## Table of Contents 🍃
- [Survey](#survey)
- [Social Agent](#social-agent)
- [Self-Evolving Agents](#self-evolving-agents)
- [Advanced Agent Applications](#advanced-agent-applications)
- [LLMs with RL or World Model](#llms-with-rl-or-world-model)
- [Planning and Manipulation or Pretraining](#planning-and-manipulation-or-pretraining)
- [Multi-Agent Learning and Coordination](#multi-agent-learning-and-coordination)
- [Vision and Language Navigation](#vision-and-language-navigation)
- [Detection](#detection)
- [3D Grounding](#3d-grounding)
- [Interactive Embodied Learning](#interactive-embodied-learning)
- [Rearrangement](#rearrangement)
- [Benchmark](#benchmark)
- [Simulator](#simulator)
- [Others](#others)

## Trend and Imagination of LLM-based Embodied Agent
<p align="center">
    <img src="trend.png" width="54%">
    <img src="Genshin.jpg" width="43%">
    <span><b>Figure 1. Trend of Embodied Agent with LLMs.<sup>[1]</sup></b></span>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
    <span><b>Figure 2. An envisioned Agent society.<sup>[2]</sup></b></span>
</p>

## Methods

> ### Survey

* [**A Survey on Vision-Language-Action Models for Embodied AI**](https://arxiv.org/pdf/2405.14093) [**arXiv 2024.03**]<br>
The Chinese University of Hong Kong, Huawei Noah’s Ark Lab

* [**Large Multimodal Agents: A Survey**](https://arxiv.org/pdf/2402.15116) [**arXiv 2024.02**] [[**Github**](https://github.com/jun0wanan/awesome-large-multimodal-agents)]<br>
Junlin Xie<sup>♣♡</sup> Zhihong Chen<sup>♣♡</sup> Ruifei Zhang<sup>♣♡</sup> Xiang Wan<sup>♣</sup> Guanbin Li<sup>♠</sup><br>
<sup>♡</sup>The Chinese University of Hong Kong, Shenzhen <sup>♣</sup>Shenzhen Research Institute of Big Data, <sup>♠</sup>Sun Yat-sen University

* [**A Survey on Self-Evolution of Large Language Models**](https://arxiv.org/pdf/2404.14387.pdf) [**arXiv 2024.01**]<br>
Key Lab of HCST (PKU), MOE; School of Computer Science, Peking University, Alibaba Group, Nanyang Technological University

* [**Agent AI: Surveying the Horizons of Multimodal Interaction**](https://arxiv.org/pdf/2401.03568.pdf) [**arXiv 2024.01**]<br>
Stanford University, Microsoft Research, Redmond, University of California, Los Angeles, University of Washington, Microsoft Gaming

* [**Igniting Language Intelligence: The Hitchhiker’s Guide From Chain-of-Thought Reasoning to Language Agents**](https://arxiv.org/pdf/2311.11797.pdf) [**arXiv 2023.11**]<br>
Shanghai Jiao Tong University, Amazon Web Services, Yale University

* [**The Rise and Potential of Large Language Model Based Agents: A Survey**](https://arxiv.org/pdf/2309.07864.pdf) [**arXiv 2023.09**]<br>
Fudan NLP Group, miHoYo Inc

* [**A Survey on LLM-based Autonomous Agents**](https://arxiv.org/pdf/2308.11432.pdf) [**arXiv 2023,08**] <br>
Gaoling School of Artificial Intelligence, Renmin University of China


> ### Social Agent

> ### Self-Evolving Agents

* [**Meta-Control: Automatic Model-based Control System Synthesis for Heterogeneous Robot Skills**](https://arxiv.org/pdf/2405.11380) [**CoRL 2024**] [[**Project page**](https://meta-control-paper.github.io/)]<br>
Tianhao Wei<sup>1*</sup>, Liqian Ma<sup>12*</sup>, Rui Chen<sup>1</sup>, Weiye Zhao<sup>1</sup>, Changliu Liu<sup>1</sup><br>
<sup>*</sup>Equal Contribution <sup>1</sup>Carnegie Mellon University <sup>2</sup>Tsinghua University


* [**AGENTGYM: Evolving Large Language Model-based Agents across Diverse Environments**](https://arxiv.org/pdf/2406.04151) [**arXiv 2024.06**] [[**Github**](https://github.com/WooooDyy/AgentGym)] [[**Project page**](https://agentgym.github.io/)] <br>
Fudan NLP Lab & Fudan Vision and Learning Lab

* [**Interactive Evolution: A Neural-Symbolic Self-Training Framework For Large Language Models**](https://arxiv.org/pdf/2406.11736) [**arXiv 2024.06**] [[**Github**](https://github.com/xufangzhi/ENVISIONS)]<br>
Fangzhi Xu<sup>♢♡</sup>, Qiushi Sun<sup>2, ♡</sup>, Kanzhi Cheng<sup>1</sup>, Jun Liu<sup>♢</sup>, Yu Qiao♡, Zhiyong Wu<sup>♡</sup> <br>
<sup>♢</sup>Xi’an Jiaotong University, <sup>♡</sup>Shanghai Artificial Intelligence Laboratory, <sup>1</sup>The University of Hong Kong, <sup>2</sup>Nanjing Univerisity

* [**Symbolic Learning Enables Self-Evolving Agents**](https://arxiv.org/pdf/2406.18532) [**arXiv 2024.06**] [[**Github**](https://github.com/aiwaves-cn/agents)]<br>
Wangchunshu Zhou, Yixin Ou, Shengwei Ding, Long Li, Jialong Wu, Tiannan Wang, Jiamin Chen, Shuai Wang, Xiaohua Xu, Ningyu Zhang, Huajun Chen, Yuchen Eleanor Jiang<br>
AIWaves Inc.
https://meta-control-paper.github.io/
> ### Advanced Agent Applications

* [**Meta-Control: Automatic Model-based Control System Synthesis for Heterogeneous Robot Skills**](https://arxiv.org/pdf/2405.11380) [**CoRL 2024**] [[**Project page**](https://meta-control-paper.github.io/)]<br>
Tianhao Wei<sup>1*</sup>, Liqian Ma<sup>12*</sup>, Rui Chen<sup>1</sup>, Weiye Zhao<sup>1</sup>, Changliu Liu<sup>1</sup>
<sup>*</sup>Equal Contribution <sup>1</sup>Carnegie Mellon University <sup>2</sup>Tsinghua University


* [**Embodied-agents**] [[**Github**](https://github.com/mbodiai/embodied-agents)] <br>
Seamlessly integrate state-of-the-art transformer models into robotics stacks.

* [**Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration**](https://arxiv.org/pdf/2406.01014) [**arXiv 2024**] [[**Github**](https://github.com/X-PLUG/MobileAgent/tree/main/Mobile-Agent-v2)]<br>
Junyang Wang<sup>1</sup>, Haiyang Xu<sup>2</sup>, Haitao Jia<sup>1</sup>, Xi Zhang<sup>2</sup>, Ming Yan<sup>2</sup>, Weizhou Shen<sup>2</sup>, Ji Zhang<sup>2</sup>, Fei Huang<sup>2</sup>, Jitao Sang<sup>1</sup><br>
<sup>1</sup>Beijing Jiaotong University <sup>2</sup>Alibaba Group

* [**Mobile-Agent: The Powerful Mobile Device Operation Assistant Family**](https://arxiv.org/pdf/2406.01014) [**ICLR 2024 Workshop LLM Agents**] [[**Github**](https://github.com/X-PLUG/MobileAgent/tree/main/Mobile-Agent-v2)]<br>
Junyang Wang<sup>1</sup>, Haiyang Xu<sup>2</sup>, Jiabo Ye<sup>2</sup>, Ming Yan<sup>2</sup>, Weizhou Shen<sup>2</sup>, Ji Zhang<sup>2</sup>, Fei Huang<sup>2</sup>, Jitao Sang<sup>1</sup><br>
<sup>1</sup>Beijing Jiaotong University <sup>2</sup>Alibaba Group

* [**Machinascript-for-robots**] [[**Github**](https://github.com/babycommando/machinascript-for-robots)] <br>
Build LLM-powered robots in your garage with MachinaScript For Robots!

* [**DiffAgent: Fast and Accurate Text-to-Image API Selection with Large Language Model**](https://arxiv.org/pdf/2404.01342) [**CVPR 2024**] [[**Github**](https://github.com/OpenGVLab/DiffAgent)] <br>
Lirui Zhao<sup>1,2</sup> Yue Yang<sup>2,4</sup> Kaipeng Zhang<sup>2</sup> Wenqi Shao<sup>2</sup>, Yuxin Zhang<sup>1</sup>, Yu Qiao<sup>2</sup>, Ping Luo<sup>2,3</sup> Rongrong Ji<sup>1</sup><br>
<sup>1</sup>Xiamen University, <sup>2</sup>OpenGVLab, Shanghai AI Laboratory <sup>3</sup>The University of Hong Kong, <sup>4</sup>Shanghai Jiao Tong University


* [**MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework**](https://openreview.net/forum?id=VtmBAGCN7o) [**ICLR 2024 (oral)**]<br>
DeepWisdom, AI Initiative, King Abdullah University of Science and Technology, Xiamen University, The Chinese University of Hong Kong, Shenzhen, Nanjing University, University of Pennsylvania, University of California, Berkeley, The Swiss AI Lab IDSIA/USI/SUPSI

* [**AppAgent: Multimodal Agents as Smartphone Users**](https://arxiv.org/pdf/2312.13771.pdf) [[**Project page**](https://appagent-official.github.io/)] [[**Github**](https://github.com/mnotgod96/AppAgent)] <br>
Chi Zhang∗ ZhaoYang∗ JiaxuanLiu∗ YuchengHan XinChen Zebiao Huang BinFu GangYu†<br>
Tencent

> ### LLMs with RL or World Model

* [**KALM: Knowledgeable Agents by Offline Reinforcement Learning from Large Language Model Rollouts**](https://openreview.net/attachment?id=sFyTZEqmUY&name=pdf) [**NeurIPS 2024**] [[**Project Page**](https://kalmneurips2024.github.io)]<br>
Jing-Cheng Pang, Si-Hang Yang, Kaiyuan Li, Jiaji Zhang, Xiong-Hui Chen, Nan Tang, Yang Yu<br>
<sup>1</sup>Nanjing University, <sup>2</sup>Polixir.ai

* [**Learning Interactive Real-World Simulators**](https://openreview.net/attachment?id=sFyTZEqmUY&name=pdf) [**ICLR 2024 (Outstanding Papers)**] [[**Project Page**](https://universal-simulator.github.io/unisim/)]<br>
Sherry Yang<sup>1,2</sup>, Yilun Du<sup>3</sup>, Kamyar Ghasemipour<sup>2</sup>, Jonathan Tompson<sup>2</sup>, Leslie Kaelbling<sup>3</sup>, Dale Schuurmans<sup>2</sup>, Pieter Abbeel<sup>1</sup><br>
<sup>1</sup>UC Berkeley, <sup>2</sup>Google DeepMind, <sup>3</sup>MIT

* [**Robust agents learn causal world models**](https://openreview.net/attachment?id=pOoKI3ouv1&name=pdf) [**ICLR 2024**]<br>
Jonathan Richens*, TomEveritt <br>
Google DeepMind

* [**Embodied Multi-Modal Agent trained by an LLM from a Parallel TextWorld**](https://arxiv.org/pdf/2311.16714.pdf) [**CVPR 2024**] [[**Github**](https://github.com/stevenyangyj/Emma-Alfworld)]<br>
Yijun Yang<sup>154</sup>, Tianyi Zhou<sup>2</sup>, Kanxue Li<sup>3</sup>, Dapeng Tao<sup>3</sup>, Lvsong Li<sup>4</sup>, Li Shen<sup>4</sup>, Xiaodong He<sup>4</sup>, Jing Jiang<sup>5</sup>, Yuhui Shi<sup>1</sup><br>
<sup>1</sup>Southern University of Science and Technology, <sup>2</sup>University of Maryland, College Park, <sup>3</sup>Yunnan University, <sup>4</sup>JD Explore Academy, <sup>5</sup>University of Technology Sydney

* [**Leveraging Pre-trained Large Language Models to Construct and Utilize World Models for Model-based Task Planning**](https://openreview.net/forum?id=zDbsSscmuj) [**NeurIPS 2023**] [[**Project Page**](https://guansuns.github.io/pages/llm-dm/)][[**Github**](https://github.com/GuanSuns/LLMs-World-Models-for-Planning)]<br>
Lin_Guan<sup>1</sup>, Karthik Valmeekam<sup>1</sup>, Sarath Sreedharan<sup>2</sup>, Subbarao Kambhampati<sup>1</sup><br>
<sup>1</sup>School of Computing & AI Arizona State University Tempe, AZ, <sup>2</sup>Department of Computer Science Colorado State University Fort Collins, CO

* [**Eureka: Human-Level Reward Design via Coding Large Language Models**](https://eureka-research.github.io/assets/eureka_paper.pdf) [**NeurIPS 2023 Workshop ALOE Spotlight**] [[**Project page**](https://eureka-research.github.io/)] [[**Github**](https://github.com/eureka-research/Eureka)] <br>
Jason Ma<sup>1,2</sup>, William Liang<sup>2</sup>, Guanzhi Wang<sup>1,3</sup>, De-An Huang<sup>1</sup>,
Osbert Bastani<sup>2</sup>, Dinesh Jayaraman<sup>2</sup>, Yuke Zhu<sup>1,4</sup>, Linxi "Jim" Fan<sup>1</sup>, Anima Anandkumar<sup>1,3</sup><br>
<sup>1</sup>NVIDIA; <sup>2</sup>UPenn; <sup>3</sup>Caltech; <sup>4</sup>UT Austin

* [**RLAdapter: Bridging Large Language Models to Reinforcement Learning in Open Worlds**](https://openreview.net/pdf?id=3s4fZTr1ce) [**arXiv 2023**] <br>

* [**Can Language Agents Be Alternatives to PPO? A Preliminary Empirical Study on OpenAI Gym**](https://openreview.net/pdf?id=F0q880yOgY) [**arXiv 2023**] <br>

* [**RoboGPT: An intelligent agent of making embodied long-term decisions for daily instruction tasks**](https://openreview.net/pdf?id=x4fm4T2tjM) [**arXiv 2023**] <br>

* [**Aligning Agents like Large Language Models**](https://openreview.net/pdf?id=kQqZVayz07) [**arXiv 2023**] <br>

* [**AMAGO: Scalable In-Context Reinforcement Learning for Adaptive Agents**](https://openreview.net/pdf?id=M6XWoEdmwf) [**ICLR 2024 spotlight**] <br>

* [**STARLING: Self-supervised Training of Text-based Reinforcement Learning Agent with Large Language Models**](https://openreview.net/pdf?id=LXiG2WqKXR) [**arXiv 2023**] <br>

* [**Text2Reward: Dense Reward Generation with Language Models for Reinforcement Learning**](https://openreview.net/pdf?id=tUM39YTRxH) [**ICLR 2024 spotlight**] <br>

* [**Leveraging Large Language Models for Optimised Coordination in Textual Multi-Agent Reinforcement Learning**](https://openreview.net/pdf?id=1PPjf4wife) [**arXiv 2023**] <br>

* [**Online Continual Learning for Interactive Instruction Following Agents**](https://openreview.net/pdf?id=7M0EzjugaN) [**ICLR 2024**] <br>

* [**ADAPTER-RL: Adaptation of Any Agent using Reinforcement Learning**](https://openreview.net/pdf?id=LVp217SAtb) [**arXiv 2023**] <br>

* [**Language Reward Modulation for Pretraining Reinforcement Learning**](https://openreview.net/pdf?id=SWRFC2EupO) [**arXiv 2023**] <br>

* [**Informing Reinforcement Learning Agents by Grounding Natural Language to Markov Decision Processes**](https://openreview.net/pdf?id=P4op21eju0) [**arXiv 2023**] <br>

* [**Learning to Model the World with Language**](https://openreview.net/pdf?id=eWLOoaShEH) [**arXiv 2023**] <br>

* [**MAMBA: an Effective World Model Approach for Meta-Reinforcement Learning**](https://openreview.net/pdf?id=1RE0H6mU7M) [**ICLR 2024**] <br>


* [**Language Reward Modulation for Pretraining Reinforcement Learning**](https://arxiv.org/pdf/2308.12270.pdf) [**arXiv 2023**] [[**Github**](https://github.com/ademiadeniji/lamp)]<br>
Ademi Adeniji, Amber Xie, Carmelo Sferrazza, Younggyo Seo, Stephen James, Pieter Abbeel<br>
<sup>1</sup>UC Berkeley

* [**Guiding Pretraining in Reinforcement Learning with Large Language Models**](https://openreview.net/attachment?id=63704LH4v5&name=pdf) [**ICML 2023**] <br>
Yuqing Du<sup>1*</sup>, Olivia Watkins<sup>1*</sup>, Zihan Wang<sup>2</sup>, Cedric Colas ´<sup>3,4</sup>, Trevor Darrell<sup>1</sup>, Pieter Abbeel<sup>1</sup>, Abhishek Gupta<sup>2</sup>, Jacob Andreas<sup>3</sup><br>
<sup>1</sup>Department of Electrical Engineering and Computer Science, University of California, Berkeley, USA <sup>2</sup>University of Washington, Seattle <sup>3</sup>Massachusetts Institute of Technology, Computer Science and Artificial Intelligence Laboratory <sup>4</sup>
Inria, Flowers Laboratory.

> ### Planning and Manipulation or Pretraining

* [**Meta-Control: Automatic Model-based Control System Synthesis for Heterogeneous Robot Skills**](https://arxiv.org/pdf/2405.11380) [**CoRL 2024**] [[**Project page**](https://meta-control-paper.github.io/)]<br>
Tianhao Wei<sup>1*</sup>, Liqian Ma<sup>12*</sup>, Rui Chen<sup>1</sup>, Weiye Zhao<sup>1</sup>, Changliu Liu<sup>1</sup>
<sup>*</sup>Equal Contribution <sup>1</sup>Carnegie Mellon University <sup>2</sup>Tsinghua University

* [**Voyager: An Open-Ended Embodied Agent with Large Language Models**](https://openreview.net/attachment?id=pAMNKGwja6&name=pdf) [**NeurIPS 2023 Workshop ALOE Spotlight**] [[**Project page**](https://voyager.minedojo.org/)] [[**Github**]](https://github.com/MineDojo/Voyager) <br>
Guanzhi Wang<sup>1,2</sup>, Yuqi Xie<sup>3</sup>, Yunfan Jiang<sup>4</sup>, Ajay Mandlekar<sup>1</sup>, Chaowei Xiao<sup>1,5</sup>, Yuke Zhu<sup>1,3</sup>, Linxi Fan<sup>1</sup>, Anima Anandkumar<sup>1,2</sup>
<sup>1</sup>NVIDIA, <sup>2</sup>Caltech, <sup>3</sup>UT Austin, <sup>4</sup>Stanford, <sup>5</sup>UW Madison

* [**Agent-Pro: Learning to Evolve via Policy-Level Reflection and Optimization**](https://arxiv.org/abs/2402.17574) [**ACL 2024**][[**Github**](https://github.com/zwq2018/Agent-Pro)] <br>
Wenqi Zhang, Ke Tang, Hai Wu, Mengna Wang, Yongliang Shen, Guiyang Hou, Zeqi Tan, Peng Li, Yueting Zhuang, Weiming Lu

* [**Self-Contrast: Better Reflection Through Inconsistent Solving Perspectives**](https://arxiv.org/abs/2401.02009) [**ACL 2024**] <br>
Wenqi Zhang, Yongliang Shen, Linjuan Wu, Qiuying Peng, Jun Wang, Yueting Zhuang, Weiming Lu

* [**MineDreamer: Learning to Follow Instructions via Chain-of-Imagination for Simulated-World Control**](https://arxiv.org/pdf/2403.12037.pdf) [**arXiv 2024**] [[**Project Page**](https://sites.google.com/view/minedreamer/main)] <br>
  Enshen Zhou<sup>1,2</sup> Yiran Qin<sup>1,3</sup> Zhenfei Yin<sup>1,4</sup> Yuzhou Huang<sup>3</sup> Ruimao Zhang<sup>3</sup> Lu Sheng<sup>2</sup> Yu Qiao<sup>1</sup>  Jing Shao<sup>1</sup><br>
  <sup>1</sup>Shanghai Artificial Intelligence Laboratory, <sup>2</sup>The Chinese University of Hong Kong, Shenzhen, <sup>3</sup>Beihang University, <sup>4</sup>The University of Sydney

* [**MP5: A Multi-modal Open-ended Embodied System in Minecraft via Active Perception**](https://arxiv.org/pdf/2312.07472.pdf) [**CVPR 2024**] [[**Project Page**](https://iranqin.github.io/MP5.github.io/)] <br>
  Yiran Qin<sup>1,2</sup> Enshen Zhou<sup>1,3</sup> Qichang Liu<sup>1,4</sup> Zhenfei Yin<sup>1,5</sup> Lu Sheng<sup>3</sup> Ruimao Zhang<sup>2</sup> Yu Qiao<sup>1</sup>  Jing Shao<sup>1</sup><br>
  <sup>1</sup>Shanghai Artificial Intelligence Laboratory, <sup>2</sup>The Chinese University of Hong Kong, Shenzhen, <sup>3</sup>Beihang University, <sup>4</sup>Tsinghua University, <sup>5</sup>The University of Sydney


* [**RILA: Reflective and Imaginative Language Agent for Zero-Shot Semantic Audio-Visual Navigation**](https://peihaochen.github.io/files/publications/RILA.pdf) [**CVPR 2024**] <br>
Zeyuan Yang<sup>1</sup>, LIU JIAGENG, Peihao Chen<sup>2</sup>, Anoop Cherian<sup>3</sup>, Tim Marks, Jonathan Le Roux<sup>4</sup>, Chuang Gan<sup>5</sup>
<sup>1</sup>Tsinghua University, <sup>2</sup>South China University of Technology, <sup>3</sup>Mitsubishi Electric Research Labs (MERL), <sup>4</sup>Mitsubishi Electric Research Labs, <sup>5</sup>MIT-IBM Watson AI Lab 

* [**Towards General Computer Control: A Multimodal Agent for Red Dead Redemption II as a Case Study**](https://arxiv.org/pdf/2403.03186.pdf) [**arXiv 2024**] [[**Project Page**]](https://baai-agents.github.io/Cradle/) [[**Code**]](https://baai-agents.github.io/Cradle/) <br>
Weihao Tan<sup>2</sup>, Ziluo Ding<sup>1</sup>, Wentao Zhang<sup>2</sup>, Boyu Li<sup>1</sup>, Bohan Zhou<sup>3</sup>, Junpeng Yue<sup>3</sup>, Haochong Xia<sup>2</sup>, Jiechuan Jiang<sup>3</sup>, Longtao Zheng<sup>2</sup>, Xinrun Xu1, Yifei Bi<sup>1</sup>, Pengjie Gu<sup>2</sup>,<br>
<sup>1</sup>Beijing Academy of Artificial Intelligence (BAAI), China; <sup>2</sup>Nanyang Technological University, Singapore; <sup>3</sup>School of Computer Science, Peking University, China

* [**See and Think: Embodied Agent in Virtual Environment**](https://arxiv.org/pdf/2311.15209.pdf) [**arXiv 2023**] <br>
 Zhonghan Zhao<sup>1*</sup>, Wenhao Chai<sup>2*</sup>, Xuan Wang<sup>1*</sup>, Li Boyi<sup>1</sup>, Shengyu Hao<sup>1</sup>, Shidong Cao<sup>1</sup>, Tian Ye<sup>3</sup>, Jenq-Neng Hwang<sup>2</sup>, Gaoang Wang<sup>1</sup><br>
<sup>1</sup>Zhejiang University <sup>1</sup>University of Washington <sup>1</sup>Hong Kong University of Science and Technology (GZ)

* [**Agent Instructs Large Language Models to be General Zero-Shot Reasoners**](https://arxiv.org/pdf/2310.03710.pdf) [**arXiv 2023**] <br>
Nicholas Crispino<sup>1</sup>, Kyle Montgomery<sup>1</sup>, Fankun Zeng<sup>1</sup>, Dawn Song<sup>2</sup>, Chenguang Wang<sup>1</sup><br>
<sup>1</sup>Washington University in St. Louis, <sup>2</sup>UC Berkeley

* [**JARVIS-1: Open-world Multi-task Agents with Memory-Augmented Multimodal Language Models**](https://neurips.cc/virtual/2023/79171https://arxiv.org/abs/2311.05997) [**NeurIPS 2023**] [[**Project Page**](https://craftjarvis-jarvis1.github.io/)] <br>
  Zihao Wang<sup>1,2</sup> Shaofei Cai<sup>1,2</sup> Anji Liu<sup>3</sup> Yonggang Jin<sup>4</sup> Jinbing Hou<sup>4</sup> Bowei Zhang<sup>5</sup> Haowei Lin<sup>1,2</sup> Zhaofeng He<sup>4</sup> Zilong Zheng<sup>6</sup> Yaodong Yang<sup>1</sup> Xiaojian Ma<sup>6†</sup> Yitao Liang<sup>1†</sup><br>
  <sup>1</sup>Institute for Artificial Intelligence, Peking University, <sup>2</sup>School of Intelligence Science and Technology, Peking University, <sup>3</sup>Computer Science Department, University of California, Los Angeles, <sup>4</sup>Beijing University of Posts and Telecommunications, <sup>5</sup>School of Electronics Engineering and Computer Science, Peking University, <sup>6</sup>Beijing Institute for General Artificial Intelligence (BIGAI)

* [**Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents**](https://arxiv.org/abs/2302.01560) [**NeurIPS 2023**]<br>
  Zihao Wang<sup>1,2</sup> Shaofei Cai<sup>1,2</sup> Guanzhou Chen<sup>3</sup> Anji Liu<sup>4</sup> Xiaojian Ma<sup>4</sup> Yitao Liang<sup>1,5†</sup><br>
  <sup>1</sup>Institute for Artificial Intelligence, Peking University, <sup>2</sup>School of Intelligence Science and Technology, Peking University, <sup>3</sup>School of Computer Science, Beijing University of Posts and Telecommunications, <sup>4</sup>Computer Science Department, University of California, Los Angeles, <sup>5</sup>Beijing Institute for General Artificial Intelligence (BIGAI)

* [**CAMEL: Communicative Agents for “Mind” Exploration of Large Scale Language Model Society**](https://arxiv.org/pdf/2303.17760.pdf) [**NeurIPS 2023**] [[**Github**](https://link.zhihu.com/?target=https%3A//github.com/camel-ai/camel)] [[**Project page**](https://www.camel-ai.org/)]<br>
Guohao Li, Hasan Abed Al Kader Hammoud, Hani Itani, Dmitrii Khizbullin, Bernard Ghanem<br>
<sup>1</sup>King Abdullah University of Science and Technology (KAUST)

* [**Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents**](https://arxiv.org/pdf/2201.07207.pdf) [**arXiv 2022**] [[**Github**](https://github.com/huangwl18/language-planner)] [[**Project page**](https://wenlong.page/language-planner/)] <br>
Wenlong Huang<sup>1</sup>, Pieter Abbeel<sup>1</sup>, Deepak Pathak<sup>2</sup>, Igor Mordatch<sup>3</sup><br>
<sup>1</sup>UC Berkeley, <sup>2</sup>Carnegie Mellon University, <sup>3</sup>Google

* [**FILM: Following Instructions in Language with Modular Methods**](https://openreview.net/pdf?id=qI4542Y2s1D) [**ICLR 2022**] [[**Github**](https://github.com/soyeonm/FILM)] [[**Project page**](https://gary3410.github.io/TaPA/)] <br>
So Yeon Min<sup>1</sup>, Devendra Singh Chaplot<sup>2</sup>, Pradeep Ravikumar<sup>1</sup>, Yonatan Bisk<sup>1</sup>, Ruslan Salakhutdinov<sup>1</sup><br>
<sup>1</sup>Carnegie Mellon University <sup>2</sup>Facebook AI Research

* [**Embodied Task Planning with Large Language Models**](https://arxiv.org/pdf/2307.01848.pdf) [**arXiv 2023**] [[**Github**](https://github.com/Gary3410/TaPA)] [[**Project page**](https://gary3410.github.io/TaPA/)] [[**Demo**](https://huggingface.co/spaces/xuxw98/TAPA)] [[**Huggingface Model**](https://huggingface.co/Gary3410/pretrain_lit_llama)] <br>
Zhenyu Wu<sup>1</sup>, Ziwei Wang<sup>2,3</sup>, Xiuwei Xu<sup>2,3</sup>, Jiwen Lu<sup>2,3</sup>, Haibin Yan<sup>1*</sup><br>
<sup>1</sup>School of Automation, Beijing University of Posts and Telecommunications,
<sup>2</sup>Department of Automation, Tsinghua University,
<sup>3</sup>Beijing National Research Center for Information Science and Technology

* [**SPRING: GPT-4 Out-performs RL Algorithms by Studying Papers and Reasoning**](https://arxiv.org/pdf/2305.15486.pdf) [**arXiv 2023**] <br>
Yue Wu<sup>1,4*</sup>
, Shrimai Prabhumoye<sup>2</sup>
, So Yeon Min<sup>1</sup>
, Yonatan Bisk<sup>1</sup>
, Ruslan Salakhutdinov<sup>1</sup>
,Amos Azaria<sup>3</sup>
, Tom Mitchell<sup>1</sup>
, Yuanzhi Li<sup>1,4</sup><br>
<sup>1</sup>Carnegie Mellon University, <sup>2</sup>NVIDIA, <sup>3</sup>Ariel University, <sup>4</sup>Microsoft Research

* [**PONI: Potential Functions for ObjectGoal Navigation
with Interaction-free Learning**](https://openaccess.thecvf.com/content/CVPR2022/papers/Ramakrishnan_PONI_Potential_Functions_for_ObjectGoal_Navigation_With_Interaction-Free_Learning_CVPR_2022_paper.pdf) [**CVPR 2022 (Oral)**] [[**Project page**](https://vision.cs.utexas.edu/projects/poni/)] [[**Github**](https://github.com/srama2512/PONI)] <br>
Santhosh Kumar Ramakrishnan<sup>1,2</sup>, Devendra Singh Chaplot<sup>1</sup>, Ziad Al-Halah<sup>2</sup>
Jitendra Malik<sup>1,3</sup>, Kristen Grauman<sup>1,2</sup><br>
<sup>1</sup>Facebook AI Research, <sup>2</sup>UT Austin, <sup>3</sup>UC Berkeley

* [**Moving Forward by Moving Backward: Embedding Action Impact over Action Semantics**](https://openreview.net/pdf?id=vmjctNUSWI) [**ICLR 2023**] [[**Project page**](https://prior.allenai.org/projects/action-adaptive-policy)] [[**Github**](https://github.com/KuoHaoZeng/AAP)] <br>
Kuo-Hao Zeng<sup>1</sup>, Luca Weihs<sup>2</sup>, Roozbeh Mottaghi<sup>1</sup>, Ali Farhadi<sup>1</sup><br>
<sup>1</sup>Paul G. Allen School of Computer Science & Engineering, University of Washington,
<sup>2</sup>PRIOR @ Allen Institute for AI

* [**Modeling Dynamic Environments with Scene Graph Memory**](https://openreview.net/attachment?id=NiUxS1cAI4&name=pdf) [**ICML 2023**] <br>
Andrey Kurenkov<sup>1</sup>, Michael Lingelbach<sup>1</sup>, Tanmay Agarwal<sup>1</sup>, Emily Jin<sup>1</sup>, Chengshu Li<sup>1</sup>, Ruohan Zhang<sup>1</sup>, Li Fei-Fei<sup>1</sup>, Jiajun Wu<sup>1</sup>, Silvio Savarese<sup>2</sup>, Roberto Mart´ın-Mart´ın<sup>3</sup><br>
<sup>1</sup>Department of Computer Science, Stanford University
<sup>2</sup>Salesforce AI Research <sup>3</sup>Department of Computer Science, University of Texas at Austin.

* [**Reasoning with Language Model is Planning with World Model**](https://arxiv.org/pdf/2305.14992.pdf) [**arXiv 2023**] <br>
Shibo Hao<sup>∗♣</sup>, Yi Gu<sup>∗♣</sup>, Haodi Ma<sup>♢</sup>, Joshua Jiahua Hong<sup>♣</sup>, Zhen Wang<sup>♣ ♠</sup>,
Daisy Zhe Wang<sup>♢</sup>, Zhiting Hu<sup>♣</sup><br>
<sup>♣</sup>UC San Diego, <sup>♢</sup>University of Florida,
<sup>♠</sup>Mohamed bin Zayed University of Artificial Intelligence

* [**Do As I Can, Not As I Say: Grounding Language in Robotic Affordances**](https://arxiv.org/pdf/2204.01691.pdf) [**arXiv 2022**]<br>
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

* [**Language Models Meet World Models: Embodied Experiences Enhance Language Models**](https://arxiv.org/pdf/2305.10626.pdf) [**arXiv 2023**] [![](https://img.shields.io/github/stars/szxiangjn/world-model-for-language-model?style=social&label=Code+Stars)](https://github.com/szxiangjn/world-model-for-language-model) [[**Twitter**](https://twitter.com/szxiangjn/status/1659399771126370304)]<br>
Jiannan Xiang<sup>∗♠</sup>, Tianhua Tao<sup>∗♠</sup>, Yi Gu<sup>♠</sup>, Tianmin Shu<sup>♢</sup>,
Zirui Wang<sup>♠</sup>, Zichao Yang<sup>♡</sup>, Zhiting Hu<sup>♠</sup><br>
<sup>♠</sup>UC San Diego, <sup>♣</sup>UIUC, <sup>♢</sup>MIT, <sup>♡</sup>Carnegie Mellon University

* [**AlphaBlock: Embodied Finetuning for Vision-Language Reasoning in Robot Manipulation**](https://arxiv.org/pdf/2305.18898.pdf) [**arXiv 2023**] [[**Video**](https://www.youtube.com/watch?v=ayAzID1_qQk)]<br>
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

* [**Code as Policies: Language Model Programs for Embodied Control**](https://arxiv.org/pdf/2209.07753) [**arXiv 2023**] [[**Project page**](https://code-as-policies.github.io/)] [[**Github**](https://code-as-policies.github.io)] [[**Blog**](https://ai.googleblog.com/2022/11/robots-that-write-their-own-code.html)] [[**Colab**](https://colab.research.google.com/drive/124TE4TsGYyrvduzeDclufyvwcc2qbbrE)]<br>
Jacky Liang, Wenlong Huang, Fei Xia, Peng Xu, Karol Hausman, Brian Ichter, Pete Florence, Andy Zeng<br>
Robotics at Google

* [**3D-LLM: Injecting the 3D World into Large Language Models**](https://arxiv.org/abs/2307.12981) [**arXiv 2023**] [![](https://img.shields.io/github/stars/UMass-Foundation-Model/3D-LLM?style=social&label=Code+Stars)](https://github.com/UMass-Foundation-Model/3D-LLM) <br>
<sup>1</sup>Yining Hong, <sup>2</sup>Haoyu Zhen, <sup>3</sup>Peihao Chen, <sup>4</sup>Shuhong Zheng, <sup>5</sup>Yilun Du, <sup>6</sup>Zhenfang Chen, <sup>6,7</sup>Chuang Gan <br>
<sup>1</sup>UCLA       <sup>2</sup> SJTU       <sup>3</sup> SCUT       <sup>4</sup> UIUC       <sup>5</sup> MIT       <sup>6</sup>MIT-IBM Watson AI Lab       <sup>7</sup> Umass Amherst

* [**VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models**](https://arxiv.org/abs/2307.05973) [**arXiv 2023**] [[**Project page**](https://voxposer.github.io/)] [[**Online Demo**](https://www.youtube.com/watch?v=Yvn4eR05A3M)]<br>
Wenlong Huang<sup>1</sup>, Chen Wang<sup>1</sup>, Ruohan Zhang<sup>1</sup>, Yunzhu Li<sup>1,2</sup>, Jiajun Wu<sup>1</sup>, Li Fei-Fei<sup>1</sup> <br>
<sup>1</sup>Stanford University <sup>2</sup>University of Illinois Urbana-Champaign

* [**Palm-e: An embodied multimodal language mode**](https://arxiv.org/pdf/2303.03378.pdf) [**ICML 2023**] [[**Project page**](https://palm-e.github.io)]<br>
<sup>1</sup>Robotics at Google <sup>2</sup>TU Berlin 3Google Research    

* [**Large Language Models as Commonsense Knowledge for Large-Scale Task Planning**](https://arxiv.org/pdf/2305.14078.pdf) [**arXiv 2023**] <br>
Zirui Zhao Wee Sun Lee David Hsu <br>
School of Computing National University of Singapore

* [**An Embodied Generalist Agent in 3D World**](https://arxiv.org/abs/2311.12871) [**ICML 2024**] <br>
Jiangyong Huang, Silong Yong, Xiaojian Ma, Xiongkun Linghu, Puhao Li, Yan Wang, Qing Li, Song-Chun Zhu, Baoxiong Jia, Siyuan Huang
Beijing Institute for General Artificial Intelligence (BIGAI)   

> ###  Multi-Agent Learning and Coordination

* [**Building Cooperative Embodied Agents Modularly with Large Language Models**](https://openreview.net/forum?id=EnXJfQqy0K) [**ICLR 2024**] [[**Project page**](https://vis-www.cs.umass.edu/Co-LLM-Agents/)] [[**Github**](https://github.com/UMass-Foundation-Model/Co-LLM-Agents/)]<br>
Hongxin Zhang<sup>1*</sup>, Weihua Du<sup>2*</sup>, Jiaming Shan<sup>3</sup>, Qinhong Zhou<sup>1</sup>, Yilun Du<sup>4</sup>, Joshua B. Tenenbaum<sup>4</sup>, Tianmin Shu<sup>4</sup>, Chuang Gan<sup>1,5</sup><br>
<sup>1</sup>University of Massachusetts Amherst, <sup>2</sup>Tsinghua University, <sup>3</sup>Shanghai Jiao Tong University, <sup>4</sup>MIT, <sup>5</sup>MIT-IBM Watson AI Lab


* [**War and Peace (WarAgent): Large Language Model-based Multi-Agent Simulation of World Wars**](https://arxiv.org/pdf/2311.17227.pdf) [**arXiv 2023**]<br>
Wenyue Hua<sup>1*</sup>, Lizhou Fan<sup>2*</sup>, Lingyao Li<sup>2</sup>, Kai Mei<sup>1</sup>, Jianchao Ji<sup>1</sup>, Yingqiang Ge<sup>1</sup>, Libby Hemphill<sup>2</sup>, Yongfeng Zhang<sup>1</sup><br>
<sup>1</sup>Rutgers University, <sup>2</sup>University of Michigan

* [**MindAgent: Emergent Gaming Interaction**](https://arxiv.org/abs/2309.09971) [**arXiv 2023**]<br> Ran Gong<sup>*1†</sup> Qiuyuan Huang<sup>*2‡</sup> Xiaojian Ma<sup>*1</sup> Hoi Vo<sup>3</sup> Zane Durante<sup>†4</sup> Yusuke Noda<sup>3</sup> Zilong Zheng<sup>5</sup> Song-Chun Zhu<sup>15678</sup> Demetri Terzopoulos<sup>1</sup> Li Fei-Fei<sup>4</sup> Jianfeng Gao<sup>2</sup><br><sup>1</sup>UCLA; <sup>2</sup>Microsoft Research, Redmond; <sup>3</sup>Xbox Team, Microsoft; <sup>4</sup>Stanford; <sup>5</sup>BIGAI; <sup>6</sup>PKU; <sup>7</sup>THU; <sup>8</sup>UCLA

* [**Demonstration-free Autonomous Reinforcement Learning via Implicit and Bidirectional Curriculum**](https://openreview.net/attachment?id=BMO1vLKq7D&name=pdf) [**ICML 2023**]<br>
Jigang Kim<sup>*1,2</sup> Daesol Cho<sup>*1,2</sup> H. Jin Kim<sup>1,3</sup><br>
<sup>1</sup>Seoul National University, <sup>2</sup>Artificial Intelligence Institute of Seoul National University (AIIS), <sup>3</sup>Automation and Systems Research Institute (ASRI).<br>
***Note: This paper mainly focuses on reinforcement learning for Embodied AI.***

* [**Adaptive Coordination in Social Embodied Rearrangement**](https://openreview.net/attachment?id=BYEsw113sz&name=pdf) [**ICML 2023**]<br>
Andrew Szot<sup>1,2</sup> Unnat Jain<sup>1</sup> Dhruv Batra<sup>1,2</sup> Zsolt Kira<sup>2</sup> Ruta Desai<sup>1</sup> Akshara Rai<sup>1</sup><br>
<sup>1</sup>Meta AI <sup>2</sup>Georgia Institute of Technology.

> ### Vision and Language Navigation

* [**IndoorSim-to-OutdoorReal: Learning to Navigate Outdoors without any Outdoor Experience**](http://arxiv.org/abs/2305.01098) [**arXiv 2023**] <br>
Joanne Truong<sup>1,2</sup>, April Zitkovich<sup>1</sup>, Sonia Chernova<sup>2</sup>, Dhruv Batra<sup>2,3</sup>, Tingnan Zhang<sup>1</sup>, Jie Tan<sup>1</sup>, Wenhao Yu<sup>1</sup><br>
<sup>1</sup>Robotics at Google <sup>2</sup>Georgia Institute of Technology <sup>3</sup>Meta AI


* [**ESC: Exploration with Soft Commonsense Constraints for Zero-shot Object Navigation**](https://openreview.net/attachment?id=GydFM0ZEXY&name=pdf) [**ICML 2023**] <br>
Kaiwen Zhou<sup>1</sup>, Kaizhi Zheng<sup>1</sup>, Connor Pryor<sup>1</sup>, Yilin Shen<sup>2</sup>, Hongxia Jin<sup>2</sup>, Lise Getoor<sup>1</sup>, Xin Eric Wang<sup>1</sup><br>
<sup>1</sup>University of California, Santa Cruz <sup>2</sup>Samsung Research America.


* [**NavGPT: Explicit Reasoning in Vision-and-Language
Navigation with Large Language Models**](https://arxiv.org/pdf/2305.16986.pdf) [**arXiv 2023**] <br>
Gengze Zhou<sup>1</sup> Yicong Hong<sup>2</sup> Qi Wu<sup>1</sup> <br>
<sup>1</sup>The University of Adelaide <sup>2</sup>The Australian National University


* [**Instruct2Act: Mapping Multi-modality Instructions to Robotic Actions with Large Language Model**](https://arxiv.org/pdf/2305.11176.pdf) [**arXiv 2023**] [[**Github**](https://github.com/OpenGVLab/Instruct2Act)]    
Siyuan Huang<sup>1,2</sup> Zhengkai Jiang<sup>4</sup> Hao Dong<sup>3</sup> Yu Qiao<sup>2</sup> Peng Gao<sup>2</sup> Hongsheng Li<sup>5</sup> <br>
<sup>1</sup>Shanghai Jiao Tong University, <sup>2</sup>Shanghai AI Laboratory, <sup>3</sup>CFCS, School of CS, PKU,
<sup>4</sup>University of Chinese Academy of Sciences, <sup>5</sup>The Chinese University of Hong Kong

> ### Detection
* [**DetGPT: Detect What You Need via Reasoning**](https://arxiv.org/pdf/2305.14167.pdf) [**arXiv 2023**] <br>
Renjie Pi<sup>1∗</sup> Jiahui Gao<sup>2*</sup> Shizhe Diao<sup>1∗</sup> Rui Pan<sup>1</sup> Hanze Dong<sup>1</sup> Jipeng Zhang<sup>1</sup> Lewei Yao<sup>1</sup> Jianhua Han<sup>3</sup> Hang Xu<sup>2</sup>
Lingpeng Kong<sup>2</sup> Tong Zhang<sup>1</sup> <br>
<sup>1</sup>The Hong Kong University of Science and Technology <sup>2</sup>The University of Hong Kong 3Shanghai Jiao Tong University

> ### 3D Grounding
* [**LLM-Grounder: Open-Vocabulary 3D Visual Grounding with Large Language Model as an Agent**](https://arxiv.org/pdf/2309.12311.pdf) [**arXiv 2023**]  <br>
Jianing Yang<sup>1,*</sup>, Xuweiyi Chen<sup>1,*</sup>, Shengyi Qian<sup>1</sup>, Nikhil Madaan, Madhavan Iyengar<sup>1</sup>, David F. Fouhey<sup>1,2</sup>, Joyce Chai<sup>1</sup><br>
<sup>1</sup>University of Michigan, <sup>2</sup>New York University

* [**3D-VisTA: Pre-trained Transformer for 3D Vision and Text Alignment**](https://arxiv.org/abs/2308.04352) [**ICCV 2023**] <br>
Ziyu Zhu, Xiaojian Ma, Yixin Chen, Zhidong Deng, Siyuan Huang, Qing Li
Beijing Institute for General Artificial Intelligence (BIGAI) 


> ### Interactive Embodied Learning

* [**Meta-Control: Automatic Model-based Control System Synthesis for Heterogeneous Robot Skills**](https://arxiv.org/pdf/2405.11380) [**CoRL 2024**] [[**Project page**](https://meta-control-paper.github.io/)]<br>
Tianhao Wei<sup>1*</sup>, Liqian Ma<sup>12*</sup>, Rui Chen<sup>1</sup>, Weiye Zhao<sup>1</sup>, Changliu Liu<sup>1</sup>
<sup>*</sup>Equal Contribution <sup>1</sup>Carnegie Mellon University <sup>2</sup>Tsinghua University


* [**Grounding Large Language Models in Interactive Environments with Online Reinforcement Learning**](https://openreview.net/attachment?id=feXm8GbxWU&name=pdf) [**ICML 2023**]  <br>
Thomas Carta<sup>1*</sup>, Clement Romac ´<sup>1,2</sup>, Thomas Wolf<sup>2</sup>, Sylvain Lamprier<sup>3</sup>, Olivier Sigaud<sup>4</sup>, Pierre-Yves Oudeyer<sup>1</sup><br>
<sup>1</sup>Inria (Flowers), University of Bordeaux, <sup>2</sup>Hugging Face, <sup>3</sup>Univ Angers, LERIA, SFR MATHSTIC,
F-49000, <sup>4</sup>Sorbonne University, ISIR

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

* [**SmartPlay: A Benchmark for LLMs as Intelligent Agents**](https://openreview.net/pdf?id=0IOX0YcCdTn) [**ICLR 2024**]  [[**Github**](https://github.com/microsoft/SmartPlay)] <br> 
Yue Wu<sup>1,2</sup>, Xuan Tang<sup>1</sup>, Tom Mitchell<sup>1</sup>, Yuanzhi Li<sup>1,2</sup>
<sup>1</sup>Carnegie Mellon University, <sup>2</sup>Microsoft Research

* [**RoboGen: Towards Unleashing Infinite Data for Automated Robot Learning via Generative Simulation**](https://arxiv.org/pdf/2311.01455.pdf) [**arXiv 2023**] [[**Project page**](https://robogen-ai.github.io/)] [[**Github**](https://github.com/Genesis-Embodied-AI/RoboGen)] <br> 
Yufei Wang<sup>1</sup>, Zhou Xian<sup>1</sup>, Feng Chen<sup>2</sup>, Tsun-Hsuan Wang<sup>3</sup>, Yian Wang<sup>4</sup>, Katerina Fragkiadaki<sup>1</sup>, Zackory Erickson<sup>1</sup>, David Held<sup>1</sup>, Chuang Gan<sup>4,5</sup> <br>
<sup>1</sup>CMU, <sup>2</sup>Tsinghua IIIS, <sup>3</sup>MIT CSAIL, <sup>4</sup>UMass Amherst, <sup>5</sup>MIT-IBM AI Lab

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
* [**LEGENT: Open Platform for Embodied Agents**](https://arxiv.org/pdf/2404.18243) [**ACL 2024**] [[**Project page**](https://docs.legent.ai/)] [[**Github**](https://github.com/thunlp/LEGENT)]<br>
Tsinghua University<br>

* [**AI2-THOR: An Interactive 3D Environment for Visual AI**](https://arxiv.org/abs/1712.05474) [**arXiv 2022**] [[**Project page**](http://ai2thor.allenai.org/)] [[**Github**](https://github.com/allenai/ai2thor)]<br> 
Allen Institute for AI, University of Washington, Stanford University, Carnegie Mellon University<br>

* [**iGibson, a Simulation Environment for Interactive Tasks in Large Realistic Scenes**](https://ieeexplore.ieee.org/document/9636667) [**IROS 2021**] [[**Project page**](https://svl.stanford.edu/igibson/)] [[**Github**](https://link.zhihu.com/?target=https%3A//github.com/StanfordVL/iGibson/releases/tag/1.0.0)]<br> 
Bokui Shen*, Fei Xia* et al.<br>

* [**Habitat: A Platform for Embodied AI Research**](https://openaccess.thecvf.com/content_ICCV_2019/papers/Savva_Habitat_A_Platform_for_Embodied_AI_Research_ICCV_2019_paper.pdf) [**ICCV 2019**] [[**Project page**](https://aihabitat.org/)] [[**Habitat-Sim**](https://github.com/facebookresearch/habitat-sim)] [[**Habitat-Lab**](https://github.com/facebookresearch/habitat-lab)] [[**Habitat Challenge**](https://github.com/facebookresearch/habitat-challenge)]<br> 
Facebook AI Research, Facebook Reality Labs, Georgia Institute of Technology, Simon Fraser University, Intel Labs, UC Berkeley<br>

* [**Habitat 2.0: Training Home Assistants to Rearrange their Habitat**](https://scontent.fhkg4-2.fna.fbcdn.net/v/t39.8562-6/10000000_254710466627524_1145871437139214759_n.pdf?_nc_cat=106&ccb=1-7&_nc_sid=ad8a9d&_nc_ohc=ui4K7s8ek_sAX8DLtW0&_nc_ht=scontent.fhkg4-2.fna&oh=00_AfCXUgrrxo_0G2trCUecPU_JeiF0ZwkxGGpiPPUHHk3XCw&oe=64F38AD0) [**NeurIPS 2021**] [[**Project page**](https://research.facebook.com/publications/habitat-2-0-training-home-assistants-to-rearrange-their-habitat/#:~:text=Habitat%202.0%3A%20Training%20Home%20Assistants%20to%20Rearrange%20their,AI%20stack%20%E2%80%93%20data%2C%20simulation%2C%20and%20benchmark%20tasks.)]<br> 
Facebook AI Research, Georgia Tech, Intel Research, Simon Fraser University, UC Berkeley

> ### Others

* [**Least-to-Most Prompting Enables Complex Reasoning in Large Language Models**](https://arxiv.org/pdf/2205.10625) [**ICLR 2023**] <br>
Google Research, Brain Team

* [**React: Synergizing reasoning and acting in language models**](https://arxiv.org/pdf/2210.03629.pdf) [**ICLR 2023**] [![](https://img.shields.io/github/stars/ysymyth/ReAct?style=social&label=Code+Stars)](https://github.com/ysymyth/ReAct) <br>
Shunyu Yao<sup>1∗</sup>, Jeffrey Zhao<sup>2</sup>, Dian Yu<sup>2</sup>, Nan Du<sup>2</sup>, Izhak Shafran<sup>2</sup>, Karthik Narasimhan<sup>1</sup>, Yuan Cao<sup>2</sup> <br>
<sup>1</sup>Department of Computer Science, Princeton University <sup>2</sup>, Google Research, Brain team

* [**Algorithm of Thoughts: Enhancing Exploration of Ideas in Large Language Models**](https://arxiv.org/pdf/2308.10379.pdf) [**arXiv 2023**] <br>
Virginia Tech, Microsoft

* [**Graph of Thoughts: Solving Elaborate Problems with Large Language Models**](https://arxiv.org/abs/2308.09687.pdf) [**arXiv 2023**] <br>
ETH Zurich, Cledar, Warsaw University of Technology

* [**Tree of Thoughts: Deliberate Problem Solving with Large Language Models**](https://arxiv.org/pdf/2305.10601.pdf) [**arXiv 2023**] <br>
Shunyu Yao<sup>1</sup>, Dian Yu<sup>2</sup>, Jeffrey Zhao<sup>2</sup>, Izhak Shafran<sup>2</sup>, Thomas L. Griffiths<sup>1</sup>, Yuan Cao<sup>2</sup>, Karthik Narasimhan<sup>1</sup> <br>
<sup>1</sup>Princeton University, <sup>2</sup>Google DeepMind

* [**Chain-of-Thought Prompting Elicits Reasoning in Large Language Models**](https://arxiv.org/pdf/2201.11903.pdf) [**NeurIPS 2022**] <br>
Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma,
Brian Ichter, Fei Xia, Ed H. Chi, Quoc V. Le, Denny Zhou<br>
Google Research, Brain Team

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

* [**Distilling Internet-Scale Vision-Language Models into Embodied Agents**](https://openreview.net/pdf?id=6vVkGnEpP7) [**ICML 2023**] <br>
Theodore Sumers<sup>1∗</sup> Kenneth Marino<sup>2</sup> Arun Ahuja<sup>2</sup> Rob Fergus<sup>2</sup> Ishita Dasgupta<sup>2</sup> <br>

* [**LISA: Reasoning Segmentation via Large Language Model**](https://arxiv.org/pdf/2308.00692.pdf) [**arXiv 2023**] [[**Github**](https://github.com/dvlab-research/LISA)] [[**Huggingface Models**](https://huggingface.co/xinlai)] [[**Dataset**](https://drive.google.com/drive/folders/125mewyg5Ao6tZ3ZdJ-1-E3n04LGVELqy?usp=sharing)] [[**Online Demo**](http://103.170.5.190:7860/)]     
TXin Lai<sup>1</sup> Zhuotao Tian<sup>2</sup> Yukang Chen<sup>1</sup> Yanwei Li<sup>1</sup> Yuhui Yuan<sup>3</sup> Shu Liu<sup>2</sup> Jiaya Jia<sup>1,2</sup> <br>
<sup>1</sup>The Chinese University of Hong Kong <sup>2</sup>SmartMore <sup>3</sup>MSRA<br>

* [**Meta-Control: Automatic Model-based Control System Synthesis for Heterogeneous Robot Skills**](https://arxiv.org/pdf/2405.11380) [**CoRL 2024**] [[**Project page**](https://meta-control-paper.github.io/)]<br>
Tianhao Wei<sup>1*</sup>, Liqian Ma<sup>12*</sup>, Rui Chen<sup>1</sup>, Weiye Zhao<sup>1</sup>, Changliu Liu<sup>1</sup>
<sup>*</sup>Equal Contribution <sup>1</sup>Carnegie Mellon University <sup>2</sup>Tsinghua University

<!--## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=zchoi/Awesome-Embodied-Agent-with-LLMs&type=Date)](https://star-history.com/#zchoi/Awesome-Embodied-Agent-with-LLMs&Date)-->


> ### Acknowledge

[1] Trend pic from this [repo](https://github.com/Paitesanshi/LLM-Agent-Survey/tree/main).<br>
[2] Figure from this paper: [The Rise and Potential of Large Language Model Based Agents: A Survey](https://arxiv.org/pdf/2309.07864.pdf).
