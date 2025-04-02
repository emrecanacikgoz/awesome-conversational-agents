# 💫 Awsome Conversational Agents
[![Paper](https://img.shields.io/badge/arXiv-Paper-red.svg)](https://arxiv.org/abs/2502.08820)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![PR Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/emrecanacikgoz/conversational-agents-survey/pulls)

**[A Desideratum for Conversational Agents: Capabilities, Challenges, and Future Directions](https://emrecanacikgoz.github.io/CoALM/)**<br>
[Emre Can Acikgoz](https://emrecanacikgoz.github.io/), [Cheng Qian](https://qiancheng0.github.io/), [Hongru Wang](https://rulegreen.github.io/), [Vardhan Dongre](https://vardhandongre.github.io/), [Xiusi Chen](https://xiusic.github.io/), [Heng Ji](https://blender.cs.illinois.edu/hengji.html), [Dilek Hakkani-Tür](https://siebelschool.illinois.edu/about/people/faculty/dilek), [Gokhan Tur](https://siebelschool.illinois.edu/about/people/faculty/gokhan)

Recent advances in Large Language Models (LLMs) have propelled conversational AI from traditional dialogue systems into sophisticated agents capable of autonomous actions, contextual awareness, and multi-turn interactions with users. Yet, fundamental questions about their capabilities, limitations, and paths forward remain open. This survey paper presents a desideratum for next-generation Conversational Agents—*what has been achieved*, *what challenges persist*, and *what must be done for more scalable systems that approach human-level intelligence*. To that end, we systematically analyze LLM-driven Conversational Agents by organizing their capabilities into three primary dimensions: (i) **Reasoning**—logical, systematic thinking inspired by human intelligence for decision making, (ii) **Monitoring**—encompassing self-awareness and user interaction monitoring, and (iii) **Control**—focusing on tool utilization and policy following. Building upon this, we introduce a novel taxonomy by classifying recent work on Conversational Agents around our proposed desideratum. We identify critical research gaps and outline key directions, including **realistic evaluations**, **long-term multi-turn reasoning skills**, **self-evolution capabilities**, **collaborative and multi-agent task completion**, **personalization**, and **proactivity**. This work aims to provide a structured foundation, highlight existing limitations, and offer insights into potential future research directions for Conversational Agents, ultimately advancing progress toward Artificial General Intelligence (AGI).


# 📝 Conversational Agent Papers
- [Table of Content (ToC)](#table-of-content-toc)
   - [1. Reasoning](#1-reasoning)
     - [1.1 General Reasoning](#11-general-reasoning)
     - [1.2 Agentic Prompting](#12-agentic-prompting)
   - [2. Monitor](#2-monitor)
     - [2.1 Self Awareness](#21-self-awareness)
        - [2.1.1 Self-Impose Capability ](#211-self-impose-capability)
        - [2.1.2 Self-Correction ](#212-self-correction)
     - [2.2 User and Interaction Monitoring](#22-user-and-interaction-monitoring)
        - [2.2.1 User State Tracking ](#221-user-state-tracking)
        - [2.2.2 Personalization and Persona ](#222-personalization-and-persona)
        - [2.2.3 Emotion and Sentiment ](#223-emotion-and-sentiment)
   - [3. Control](#3-control)
     - [3.1 Tool Utilization](#31-tool-utilization)
        - [3.1.1 Tool Selection](#311-tool-selection)
        - [3.1.2 Tool Execution](#312-tool-execution)
     - [3.2 Policy Learning and Following](#32-policy-learning-and-following)

## 1. Reasoning

### 1.1 General Reasoning
- [2022/01] **Chain-of-thought prompting elicits reasoning in large language models** *Jason Wei et al. NeurIPS 2022.* [[paper](https://arxiv.org/abs/2201.11903)]
- [2022/03] **Self-Consistency Improves Chain of Thought Reasoning in Language Models** *Xuezhi Wang et al. ICLR 2023.* [[paper](https://arxiv.org/abs/2203.11171)]
- [2023/03] **Self-refine: Iterative refinement with self-feedback** *Aman Madaan et al. NeurIPS 2023.* [[paper](https://arxiv.org/abs/2303.17651) / [code](https://github.com/madaan/self-refine)]
- [2023/08] **Graph of thoughts: Solving elaborate problems with large language models** *Maciej Besta et al. AAAI 2024.* [[paper](https://arxiv.org/abs/2308.09687) / [code](https://github.com/spcl/graph-of-thoughts)]
- [2023/08] **Cue-CoT: Chain-of-thought Prompting for Responding to In-depth Dialogue Questions with LLMs** *Hongru Wang et al. EMNLP 2023 Findings.* [[paper](https://arxiv.org/abs/2305.11792) / [code](https://github.com/ruleGreen/Cue-CoT)]

### 1.2 Agentic Prompting
- [2022/10] **ReAct: Synergizing Reasoning and Acting in Language Models** *Shunyu Yao et al. ICLR 2023.* [[paper](https://arxiv.org/abs/2210.03629) / [code](https://github.com/ysymyth/ReAct)]
- [2023/03] **Art: Automatic multi-step reasoning and tool-use for large language models** *Bhargavi Paranjape et al. arXiv.* [[paper](https://arxiv.org/abs/2303.09014) / [code](https://github.com/bhargaviparanjape/language-programmes/)]
- [2023/03] **Reflexion: Language Agents with Verbal Reinforcement Learning** *Noah Shinn et al. NeurIPS 2023.* [[paper](https://arxiv.org/abs/2303.11366) / [code](https://github.com/noahshinn/reflexion)]
- [2023/05] **Tree of Thoughts: Deliberate Problem Solving with Large Language Models** *Shunyu Yao et al. NeurIPS 2023.* [[paper](https://arxiv.org/abs/2305.10601) / [code](https://github.com/princeton-nlp/tree-of-thought-llm)]
- [2023/05] **MultiTool-CoT: GPT-3 Can Use Multiple External Tools with Chain of Thought Prompting** *Tatsuro Inaba et al. ACL 2023.* [[paper](https://arxiv.org/abs/2305.16896) / [code](https://github.com/tatsuropfgt/MultiTool-CoT)]
- [2023/05] **ChatCoT: Tool-Augmented Chain-of-Thought Reasoning on Chat-based Large Language Models** *Zhipeng Chen et al. EMNLP 2023 Findings.* [[paper](https://arxiv.org/abs/2305.14323) / [code](https://github.com/RUCAIBox/ChatCoT)]
- [2023/10] **Language Agent Tree Search Unifies Reasoning, Acting, and Planning in Language Models** *Andy Zhou et al. ICML 2024.* [[paper](https://arxiv.org/abs/2310.04406) / [code](https://github.com/lapisrocks/LanguageAgentTreeSearch)]
- [2023/10] **ToolChain*: Efficient Action Space Navigation in Large Language Models with A* Search** *Yuchen Zhuang et al. ICLR 2024.* [[paper](https://arxiv.org/abs/2310.13227)]
- [2024/11] **ReSpAct: Harmonizing Reasoning, Speaking, and Acting Towards Building Large Language Model-Based Conversational AI Agents** *Vardhan Dongre et al. arXiv 2024.* [[paper](https://arxiv.org/abs/2411.00927) / [code](https://github.com/vardhandongre/Respact)]


## 2. Monitor

### 2.1 Self Awareness

#### 2.1.1 Self-Impose Capability 
- [2024/02] **Self-DC: When to Reason and When to Act? Self Divide-and-Conquer for Compositional Unknown Questions** *Hongru Wang et al. arXiv.* [[paper](https://arxiv.org/abs/2402.13514)]
- [2025/02] **SMART: Self-Aware Agent for Tool Overuse Mitigations** *Cheng Qian et al. arXiv.* [[paper](https://arxiv.org/abs/2502.11435) / [code](https://github.com/qiancheng0/Open-SMARTAgent)]
- [2025/02] **Adaptive Tool Use in Large Language Models with Meta-Cognition Trigger** *Wenjun Li et al. arXiv.* [[paper](https://arxiv.org/abs/2502.12961)]
- [2025/03] **Agentic Knowledgeable Self-awareness** *Shuofei Qiao et al. ICLR 2025 Workshop.* [[paper](https://openreview.net/forum?id=PGdSLjYwMT)]


#### 2.1.2 Self-Correction 
- [2023/03] **Self-refine: Iterative refinement with self-feedback** *Aman Madaan et al. NeurIPS 2023.* [[paper](https://arxiv.org/abs/2303.17651) / [code](https://github.com/madaan/self-refine)]
- [2023/03] **Reflexion: Language Agents with Verbal Reinforcement Learning** *Noah Shinn et al. NeurIPS 2023.* [[paper](https://arxiv.org/abs/2303.11366) / [code](https://github.com/noahshinn/reflexion)]
- [2024/03] **Trial and Error: Exploration-Based Trajectory Optimization for LLM Agents** *Yifan Song et al. ACL 2024.* [[paper](https://arxiv.org/abs/2403.02502) / [code](https://github.com/Yifan-Song793/ETO)]
- [2024/06] **Watch Every Step! LLM Agent Learning via Iterative Step-Level Process Refinement** *Weimin Xiong et al. EMNLP 2024.* [[paper](https://arxiv.org/abs/2406.11176) / [code](https://github.com/WeiminXiong/IPR)]
- [2025/01] **AgentRefine: Enhancing Agent Generalization through Refinement Tuning** *Dayuan Fu et al. ICLR 2025.* [[paper](https://arxiv.org/abs/2501.01702) / [code](https://github.com/Fu-Dayuan/AgentRefine)]
- [2025/01] **Agent-R: Training Language Model Agents to Reflect via Iterative Self-Training** *Siyu Yuan et al. arXiv 2025.* [[paper](https://arxiv.org/abs/2501.11425) / [code](https://github.com/bytedance/Agent-R)]
 
 
### 2.2 User and Interaction Monitoring

#### 2.2.1 User State Tracking 
- [2022/03] **In-Context Learning for Few-Shot Dialogue State Tracking** *Yushi Hu et al. EMNLP 2022 Findings.* [[paper](https://arxiv.org/abs/2203.08568) / [code](https://github.com/Yushi-Hu/IC-DST)]
- [2023/10] **Towards LLM-driven Dialogue State Tracking** *Yujie Feng et al. EMNLP 2023.* [[paper](https://arxiv.org/abs/2310.14970) / [code](https://github.com/WoodScene/LDST)]
- [2023/04] **Are LLMs All You Need for Task-Oriented Dialogue?** *Vojtěch Hudeček et al. SIGDIAL 2023.* [[paper](https://arxiv.org/abs/2304.06556) / [code](https://github.com/vojtsek/to-llm-bot)]
- [2023/11] **Clarify When Necessary: Resolving Ambiguity Through Interaction with LMs** *Michael J.Q. Zhang et al. CoRR 2023.* [[paper](https://arxiv.org/abs/2311.09469)]
- [2024/02] **Large Language Models as Zero-shot Dialogue State Tracker through Function Calling** *Zekun Li et al. ACL 2024.* [[paper](https://arxiv.org/abs/2402.10466) / [code](https://github.com/facebookresearch/FnCTOD)]
- [2024/02] **Tell Me More! Towards Implicit User Intention Understanding of Language Model Driven Agents** *Cheng Qian et al. ACL 2024.* [[paper](https://arxiv.org/abs/2402.09205) / [code](https://github.com/OpenBMB/Tell_Me_More)]
- [2024/03] **STaR-GATE: Teaching Language Models to Ask Clarifying Questions** *Chinmaya Andukuri et al. COLM 2024.* [[paper](https://arxiv.org/abs/2403.19154) / [code](https://github.com/scandukuri/assistant-gate)]
- [2024/04] **Unsupervised End-to-End Task-Oriented Dialogue with LLMs: The Power of the Noisy Channel** *Brendan King et al. EMNLP 2024.* [[paper](https://arxiv.org/abs/2404.15219) / [code](https://github.com/jlab-nlp/nc_latent_tod)]
- [2024/09] **Learning to Ask: When LLM Agents Meet Unclear Instruction** *Wenxuan Wang et al. CoRR 2024.* [[paper](https://arxiv.org/abs/2409.00557)]
- [2025/02] **Can a Single Model Master Both Multi-turn Conversations and Tool Use? CoALM: A Unified Conversational Agentic Language Model** *Emre Can Acikgoz et al. arXiv 2025.* [[paper](https://arxiv.org/abs/2502.08820) / [code](https://github.com/oumi-ai/oumi/tree/main/configs/projects/coalm)]
- [2025/03] **AskToAct: Enhancing LLMs Tool Use via Self-Correcting Clarification** *Xuan Zhang et al. arXiv 2025.* [[paper](https://www.arxiv.org/abs/2503.01940)]

#### 2.2.2 Personalization and Persona
- [2022/10] **Personalized Dialogue Generation with Persona-Adaptive Attention** *Qiushi Huang et al. AAAI 2023.* [[paper](https://arxiv.org/abs/2210.15088) / [code](https://github.com/hqsiswiliam/persona-adaptive-attention)]
- [2023/12] **Beyond Candidates: Adaptive Dialogue Agent Utilizing Persona and Knowledge** *Jungwoo Lim et al. EMNLP 2023 Findings.* [[paper](https://aclanthology.org/2023.findings-emnlp.534/) / [code](https://github.com/dlawjddn803/BeCand)]
- [2023/08] **CharacterChat: Learning towards Conversational AI with Personalized Social Support** *Quan Tu et al. arXiv 2023.* [[paper](https://arxiv.org/abs/2308.10278) / [code](https://github.com/morecry/CharacterChat)]
- [2024/02] **Democratizing Large Language Models via Personalized Parameter-Efficient Fine-tuning** *Zhaoxuan Tan et al. CoRR 2023.* [[paper](https://arxiv.org/abs/2402.04401) / [code](https://github.com/TamSiuhin/OPPU)]
- [2024/06] **Personalized Pieces: Efficient Personalized Large Language Models through Collaborative Efforts** *Zhaoxuan Tan et al. EMNLP 2024.* [[paper](https://arxiv.org/abs/2406.10471) / [code](https://github.com/TamSiuhin/Per-Pcs)]

#### 2.2.3 Emotion and Sentiment
- [2018/11] **Towards Empathetic Open-domain Conversation Models: a New Benchmark and Dataset** *Hannah Rashkin et al. ACL 2019.* [[paper](https://arxiv.org/abs/1811.00207) / [code](https://github.com/facebookresearch/EmpatheticDialogues)]
- [2021/06] **Towards Emotional Support Dialog Systems** *Jungwoo Lim et al. ACL 201 Findings.* [[paper](https://arxiv.org/abs/2106.01144) / [code](https://github.com/thu-coai/Emotional-Support-Conversation)]
- [2022/05] **D4: a Chinese Dialogue Dataset for Depression-Diagnosis-Oriented Chat** *Binwei Yao et al. EMNLP 2022.* [[paper](https://arxiv.org/abs/2205.11764) / [code](https://github.com/BigBinnie/D4_baseline)]
- [2023/08] **Reasoning before Responding: Integrating Commonsense-based Causality Explanation for Empathetic Response Generation** *Yahui Fu et al. SIGDIAL 2023.* [[paper](https://arxiv.org/abs/2308.00085)]

 
## 3. Control

### 3.1 Tool Utilization

#### 3.1.1 Tool Selection
- [2022/05] **TALM: Tool Augmented Language Models** *Aaron Parisi et al. arXiv.* [[paper](https://arxiv.org/abs/2205.12255)]
- [2023/02] **Toolformer: Language Models Can Teach Themselves to Use Tools** *Timo Schick et al. NeurIPS 2023.* [[paper](https://arxiv.org/abs/2302.04761)]
- [2023/05] **Gorilla: Large Language Model Connected with Massive APIs** *Shishir G. Patil et al. NeurIPS 2024.* [[paper](https://arxiv.org/abs/2305.15334) / [code](https://github.com/ShishirPatil/gorilla)]
- [2023/06] **ToolAlpaca: Generalized Tool Learning for Language Models with 3000 Simulated Cases** *Qiaoyu Tang et al. arXiv.* [[paper](https://arxiv.org/abs/2306.05301) / [code](https://github.com/tangqiaoyu/ToolAlpaca)]
- [2023/05] **CREATOR: Tool Creation for Disentangling Abstract and Concrete Reasoning of Large Language Models** *Cheng Qian et al. EMNLP 2023 Findings.* [[paper](https://arxiv.org/abs/2305.14318) / [code](https://github.com/qiancheng0/CREATOR)]
- [2023/05] **Large Language Models as Tool Makers** *Tianle Cai et al. ICLR 2024.* [[paper](https://arxiv.org/abs/2305.17126) / [code](https://github.com/ctlllll/LLM-ToolMaker)]
- [2024/09] **xLAM: A Family of Large Action Models to Empower AI Agent Systems** *Jianguo Zhang et al. arXiv.* [[paper](https://arxiv.org/abs/2409.03215) / [code](https://github.com/SalesforceAIResearch/xLAM)]
- [2024/10] **Hammer: Robust Function-Calling for On-Device Language Models via Function Masking** *Qiqiang Lin et al. ICLR 2025.* [[paper](https://arxiv.org/abs/2410.04587) / [code](https://github.com/MadeAgents/Hammer)]

#### 3.1.2 Tool Execution
- [2023/10] **AgentTuning: Enabling Generalized Agent Abilities for LLMs** *Aohan Zeng et al. ACL 2024 Findings.* [[paper](https://arxiv.org/abs/2310.12823) / [code](https://github.com/THUDM/AgentTuning)]
- [2024/03] **Agent-FLAN: Designing Data and Methods of Effective Agent Tuning for Large Language Models** *Zehui Chen et al. ACL 2024 Findings.* [[paper](https://arxiv.org/abs/2403.12881) / [code](https://github.com/InternLM/Agent-FLAN)]
- [2024/02] **Large Language Models as Zero-shot Dialogue State Tracker through Function Calling** *Zekun Li et al. ACL 2024.* [[paper](https://arxiv.org/abs/2402.10466) / [code](https://github.com/facebookresearch/FnCTOD)]
- [2024/09] **ToolACE: Winning the Points of LLM Function Calling** *Weiwen Liu et al. ICLR 2025.* [[paper](https://arxiv.org/abs/2409.00920)]
- [2025/02] **Can a Single Model Master Both Multi-turn Conversations and Tool Use? CoALM: A Unified Conversational Agentic Language Model** *Emre Can Acikgoz et al. arXiv 2025.* [[paper](https://arxiv.org/abs/2502.08820) / [code](https://github.com/oumi-ai/oumi/tree/main/configs/projects/coalm)]

### 3.2 Policy Learning and Following

- [2016/04] **A Network-based End-to-End Trainable Task-oriented Dialogue System** *Tsung-Hsien Wen et al. ACL 2017.* [[paper](https://arxiv.org/abs/1604.04562)]
- [2018/01] **Deep Dyna-Q: Integrating Planning for Task-Completion Dialogue Policy Learning** *Baolin Peng et al. ACL 2018.* [[paper](https://arxiv.org/abs/1801.06176) / [code](https://github.com/MiuLab/DDQ)]
- [2022/04] **Dynamic Dialogue Policy for Continual Reinforcement Learning** *Tsung-Hsien Wen et al. COLING 2022.* [[paper](https://arxiv.org/abs/2204.05928)]
- [2023/05] **SGP-TOD: Building Task Bots Effortlessly via Schema-Guided LLM Prompting** *Xiaoying Zhang et al. EMNLP 2023 Findings.* [[paper](https://arxiv.org/abs/2305.09067) / [code](https://github.com/zhangxy-2019/sgp-tod)]
- [2023/04] **Are LLMs All You Need for Task-Oriented Dialogue?** *Vojtěch Hudeček et al. SIGDIAL 2023.* [[paper](https://arxiv.org/abs/2304.06556) / [code](https://github.com/vojtsek/to-llm-bot)]
- [2024/06] **FlowBench: Revisiting and Benchmarking Workflow-Guided Planning for LLM-based Agents** *Ruixuan Xiao et al. EMNLP 2024 Findings.* [[paper](https://arxiv.org/abs/2406.14884) / [code](https://github.com/Justherozen/FlowBench)]
- [2024/08] **Rethinking Task-Oriented Dialogue Systems: From Complex Modularity to Zero-Shot Autonomous Agent** *Heng-Da Xu et al. ACL 2024.* [[paper](https://aclanthology.org/2024.acl-long.152/) / [code](https://github.com/DaDaMrX/AutoTOD)]

<!-- ## 5. Surveys
- [2023/03] **A Survey of Large Language Models** *Wayne Xin Zhao et al. arXiv.* [[paper](https://arxiv.org/abs/2303.18223)]

- [2023/08] **A Survey on Large Language Model based Autonomous Agents** *Lei Wang et al. arXiv.* [[paper](https://arxiv.org/abs/2308.11432)]

- [2023/09] **The Rise and Potential of Large Language Model Based Agents: A Survey** *Zhiheng Xi et al. arXiv.* [[paper](https://arxiv.org/abs/2309.07864)]

- [2023/09] **An In-depth Survey of Large Language Model-based Artificial Intelligence Agents** *Pengyu Zhao et al. arXiv.* [[paper](https://arxiv.org/abs/2309.14365)]

- [2023/09] **Natural Language based Context Modeling and Reasoning for Ubiquitous Computing with Large Language Models: A Tutoria** *Haoyi Xiong et al. arXiv.* [[paper](https://arxiv.org/abs/2309.15074)]
 -->
