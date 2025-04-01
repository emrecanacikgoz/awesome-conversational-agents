# 💫 Awsome Conversational Agents
[![Paper](https://img.shields.io/badge/arXiv-Paper-red.svg)](https://arxiv.org/abs/2502.08820)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![PR Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](https://github.com/emrecanacikgoz/conversational-agents-survey/pulls)

**[A Desideratum for Conversational Agents: Capabilities, Challenges, and Future Directions](https://emrecanacikgoz.github.io/CoALM/)**
[Emre Can Acikgoz](https://emrecanacikgoz.github.io/), [Cheng Qian](https://qiancheng0.github.io/), [Hongru Wang](https://rulegreen.github.io/), [Vardhan Dongre](https://vardhandongre.github.io/), [Xiusi Chen](https://xiusic.github.io/), [Heng Ji](https://blender.cs.illinois.edu/hengji.html), [Dilek Hakkani-Tür](https://siebelschool.illinois.edu/about/people/faculty/dilek), [Gokhan Tur](https://siebelschool.illinois.edu/about/people/faculty/gokhan)

Recent advances in Large Language Models (LLMs) have propelled conversational AI from traditional dialogue systems into sophisticated agents capable of autonomous actions, contextual awareness, and multi-turn interactions with users. Yet, fundamental questions about their capabilities, limitations, and paths forward remain open. This survey paper presents a desideratum for next-generation Conversational Agents—*what has been achieved*, *what challenges persist*, and *what must be done for more scalable systems that approach human-level intelligence*. To that end, we systematically analyze LLM-driven Conversational Agents by organizing their capabilities into three primary dimensions: (i) **Reasoning**—logical, systematic thinking inspired by human intelligence for decision making, (ii) **Monitoring**—encompassing self-awareness and user interaction monitoring, and (iii) **Control**—focusing on tool utilization and policy following. Building upon this, we introduce a novel taxonomy by classifying recent work on Conversational Agents around our proposed desideratum. We identify critical research gaps and outline key directions, including **realistic evaluations**, **long-term multi-turn reasoning skills**, **self-evolution capabilities**, **collaborative and multi-agent task completion**, **personalization**, and **proactivity**. This work aims to provide a structured foundation, highlight existing limitations, and offer insights into potential future research directions for Conversational Agents, ultimately advancing progress toward Artificial General Intelligence (AGI).


# 📝 Conversational Agent Papers

## 1. Reasoning

### 1.1 General Reasoning
- [2022/01] **Chain-of-thought prompting elicits reasoning in large language models** *Jason Wei et al. NeurIPS 2022.* [[paper](https://arxiv.org/abs/2201.11903)]
  - TODO
- [2022/03] **Self-Consistency Improves Chain of Thought Reasoning in Language Models** *Xuezhi Wang et al. ICLR 2023.* [[paper](https://arxiv.org/abs/2203.11171)]
  - TODO
- [2023/03] **Self-refine: Iterative refinement with self-feedback** *Aman Madaan et al. NeurIPS 2023.* [[paper](https://arxiv.org/abs/2303.17651)]
  - TODO
- [2023/08] **Graph of thoughts: Solving elaborate problems with large language models** *Maciej Besta et al. AAAI 2024.* [[paper](https://arxiv.org/abs/2308.09687)]
  - TODO
- [2023/08] **Cue-CoT: Chain-of-thought Prompting for Responding to In-depth Dialogue Questions with LLMs** *Hongru Wang et al. EMNLP 2023 Findings.* [[paper](https://arxiv.org/abs/2305.11792)]
  - TODO

### 1.2 Agentic Prompting
- [2022/10] **ReAct: Synergizing Reasoning and Acting in Language Models** *Shunyu Yao et al. ICLR 2023.* [[paper](https://arxiv.org/abs/2210.03629)]
  - TODO
- [2023/03] **Art: Automatic multi-step reasoning and tool-use for large language models** *Bhargavi Paranjape et al. arXiv.* [[paper](https://arxiv.org/abs/2303.09014)]
  - TODO
- [2023/03] **Reflexion: Language Agents with Verbal Reinforcement Learning** *Noah Shinn et al. NeurIPS 2023.* [[paper](https://arxiv.org/abs/2303.11366)]
  - TODO
- [2023/05] **Tree of Thoughts: Deliberate Problem Solving with Large Language Models** *Shunyu Yao et al. NeurIPS 2023.* [[paper](https://arxiv.org/abs/2305.10601)]
  - TODO
- [2023/05] **MultiTool-CoT: GPT-3 Can Use Multiple External Tools with Chain of Thought Prompting** *Tatsuro Inaba et al. ACL 2023.* [[paper](https://arxiv.org/abs/2305.16896)]
  - TODO
- [2023/05] **ChatCoT: Tool-Augmented Chain-of-Thought Reasoning on Chat-based Large Language Models** *Zhipeng Chen et al. EMNLP 2023 Findings.* [[paper](https://arxiv.org/abs/2305.14323)]
  - TODO
- [2023/10] **Language Agent Tree Search Unifies Reasoning, Acting, and Planning in Language Models** *Andy Zhou et al. ICML 2024.* [[paper](https://arxiv.org/abs/2310.04406)]
  - TODO
- [2023/10] **ToolChain*: Efficient Action Space Navigation in Large Language Models with A* Search** *Yuchen Zhuang et al. ICLR 2024.* [[paper](https://arxiv.org/abs/2310.13227)]
  - TODO
- [2024/11] **ReSpAct: Harmonizing Reasoning, Speaking, and Acting Towards Building Large Language Model-Based Conversational AI Agents** *Vardhan Dongre et al. arXiv 2024.* [[paper](https://arxiv.org/abs/2411.00927)]
  - TODO

## 2. Monitor

### 2.1 Self Awareness

#### 2.1.1 Self-Impose Capability 
- [2024/02] **Self-DC: When to Reason and When to Act? Self Divide-and-Conquer for Compositional Unknown Questions** *Hongru Wang et al. arXiv.* [[paper](https://arxiv.org/abs/2402.13514)]
  - TODO
- [2025/02] **SMART: Self-Aware Agent for Tool Overuse Mitigations** *Cheng Qian et al. arXiv.* [[paper](https://arxiv.org/abs/2502.11435)]
  - TODO
- [2025/02] **Adaptive Tool Use in Large Language Models with Meta-Cognition Trigger** *Wenjun Li et al. arXiv.* [[paper](https://arxiv.org/abs/2502.12961)]
  - TODO
- [2025/03] **Agentic Knowledgeable Self-awareness** *Shuofei Qiao et al. ICLR 2025 Workshop.* [[paper](https://openreview.net/forum?id=PGdSLjYwMT)]
  - TODO

#### 2.1.2 Self-Correction 
- [2023/03] **Self-refine: Iterative refinement with self-feedback** *Aman Madaan et al. NeurIPS 2023.* [[paper](https://arxiv.org/abs/2303.17651)]
  - TODO
- [2023/03] **Reflexion: Language Agents with Verbal Reinforcement Learning** *Noah Shinn et al. NeurIPS 2023.* [[paper](https://arxiv.org/abs/2303.11366)]
  - TODO
- [2024/03] **Trial and Error: Exploration-Based Trajectory Optimization for LLM Agents** *Yifan Song et al. ACL 2024.* [[paper](https://arxiv.org/abs/2403.02502)]
  - TODO
- [2024/06] **Watch Every Step! LLM Agent Learning via Iterative Step-Level Process Refinement** *Weimin Xiong et al. EMNLP 2024.* [[paper](https://arxiv.org/abs/2406.11176)]
  - TODO
- [2025/01] **AgentRefine: Enhancing Agent Generalization through Refinement Tuning** *Dayuan Fu et al. ICLR 2025.* [[paper](https://arxiv.org/abs/2501.01702)]
  - TODO
- [2025/01] **Agent-R: Training Language Model Agents to Reflect via Iterative Self-Training** *Siyu Yuan et al. arXiv 2025.* [[paper](https://arxiv.org/abs/2501.11425)]
  - TODO


### 2.2 User & Interaction Monitoring

#### 2.2.1 User State Tracking 
- [2022/03] **In-Context Learning for Few-Shot Dialogue State Tracking** *Yushi Hu et al. EMNLP 2022 Findings.* [[paper](https://arxiv.org/abs/2203.08568)]
  - TODO
- [2023/10] **Towards LLM-driven Dialogue State Tracking** *Yujie Feng et al. EMNLP 2023.* [[paper](https://arxiv.org/abs/2310.14970)]
  - TODO
- [2023/04] **Are LLMs All You Need for Task-Oriented Dialogue?** *Vojtěch Hudeček et al. SIGDIAL 2023.* [[paper](https://arxiv.org/abs/2304.06556)]
  - TODO
- [2023/11] **Clarify When Necessary: Resolving Ambiguity Through Interaction with LMs** *Michael J.Q. Zhang et al. CoRR 2023.* [[paper](https://arxiv.org/abs/2311.09469)]
  - TODO
- [2024/02] **Large Language Models as Zero-shot Dialogue State Tracker through Function Calling** *Zekun Li et al. ACL 2024.* [[paper](https://arxiv.org/abs/2402.10466)]
  - TODO
- [2024/02] **Tell Me More! Towards Implicit User Intention Understanding of Language Model Driven Agents** *Cheng Qian et al. ACL 2024.* [[paper](https://arxiv.org/abs/2402.09205)]
  - TODO
- [2024/03] **STaR-GATE: Teaching Language Models to Ask Clarifying Questions** *Chinmaya Andukuri et al. COLM 2024.* [[paper](https://arxiv.org/abs/2403.19154)]
  - TODO
- [2024/04] **Unsupervised End-to-End Task-Oriented Dialogue with LLMs: The Power of the Noisy Channel** *Brendan King et al. EMNLP 2024.* [[paper](https://arxiv.org/abs/2404.15219)]
  - TODO
- [2024/09] **Learning to Ask: When LLM Agents Meet Unclear Instruction** *Wenxuan Wang et al. CoRR 2024.* [[paper](https://arxiv.org/abs/2409.00557)]
  - TODO
- [2025/02] **Can a Single Model Master Both Multi-turn Conversations and Tool Use? CoALM: A Unified Conversational Agentic Language Model** *Emre Can Acikgoz et al. arXiv 2025.* [[paper](https://arxiv.org/abs/2502.08820)]
  - TODO
- [2025/03] **AskToAct: Enhancing LLMs Tool Use via Self-Correcting Clarification** *Xuan Zhang et al. arXiv 2025.* [[paper](https://www.arxiv.org/abs/2503.01940)]
  - TODO

#### 2.2.2 Personalization and Persona
- [2022/10] **Personalized Dialogue Generation with Persona-Adaptive Attention** *Qiushi Huang et al. AAAI 2023.* [[paper](https://arxiv.org/abs/2210.15088)]
  - TODO
- [2023/12] **Beyond Candidates: Adaptive Dialogue Agent Utilizing Persona and Knowledge** *Jungwoo Lim et al. EMNLP 2023 Findings.* [[paper](https://aclanthology.org/2023.findings-emnlp.534/)]
  - TODO
- [2023/08] **CharacterChat: Learning towards Conversational AI with Personalized Social Support** *Quan Tu et al. arXiv 2023.* [[paper](https://arxiv.org/abs/2308.10278)]
  - TODO
- [2024/02] **Democratizing Large Language Models via Personalized Parameter-Efficient Fine-tuning** *Zhaoxuan Tan et al. CoRR 2023.* [[paper](https://arxiv.org/abs/2402.04401)]
  - TODO
- [2024/06] **Personalized Pieces: Efficient Personalized Large Language Models through Collaborative Efforts** *Zhaoxuan Tan et al. EMNLP 2024.* [[paper](https://arxiv.org/abs/2406.10471)]
  - TODO

#### 2.2.3 Emotion and Sentiment
- [2018/11] **Towards Empathetic Open-domain Conversation Models: a New Benchmark and Dataset** *Hannah Rashkin et al. ACL 2019.* [[paper](https://arxiv.org/abs/1811.00207)]
  - TODO
- [2021/06] **Towards Emotional Support Dialog Systems** *Jungwoo Lim et al. ACL 201 Findings.* [[paper](https://arxiv.org/abs/2106.01144)]
  - TODO
- [2022/05] **D4: a Chinese Dialogue Dataset for Depression-Diagnosis-Oriented Chat** *Binwei Yao et al. EMNLP 2022.* [[paper](https://arxiv.org/abs/2205.11764)]
  - TODO
- [2023/08] **Reasoning before Responding: Integrating Commonsense-based Causality Explanation for Empathetic Response Generation** *Yahui Fu et al. SIGDIAL 2023.* [[paper](https://arxiv.org/abs/2308.00085)]
  - TODO



## 4. Benchmarks
- [2018/09] **HotpotQA: A Dataset for Diverse, Explainable Multi-hop Question Answering** *Zhilin Yang et al. ACL 2019.* [[paper](https://arxiv.org/abs/1809.09600)]
  - TODO
- [2020/10] **ALFWorld: Aligning Text and Embodied Environments for Interactive Learning** *Mohit Shridhar et al. arXiv.* [[paper](https://arxiv.org/abs/2010.03768)]
  - TODO
- [2021/01] **Did Aristotle Use a Laptop? A Question Answering Benchmark with Implicit Reasoning Strategies** *Mor Geva et al. arXiv.* [[paper](https://arxiv.org/abs/2101.02235)]
  - TODO
- [2022/02] **MiniWob++: A data-driven approach for learning to control computers** *Peter C Humphreys et al. arXiv.* [[paper](https://arxiv.org/abs/2202.08137)]
  - TODO
- [2022/03] **ScienceWorld: Is your Agent Smarter than a 5th Grader?** *Ruoyao Wang et al. arXiv.* [[paper](https://arxiv.org/abs/2203.07540)]
  - TODO
- [2022/07] **WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents** *Shunyu Yao et al. arXiv.* [[paper](https://arxiv.org/abs/2207.01206)]
  - TODO
- [2022/10] **Measuring and Narrowing the Compositionality Gap in Language Models** *Ofir Press et al. arXiv.* [[paper](https://arxiv.org/abs/2210.03350)]
  - TODO
- [2023/06] **Mind2Web: Towards a Generalist Agent for the Web** *Xiang Deng et al. arXiv.* [[paper](https://arxiv.org/abs/2306.06070)]
  - TODO
- [2023/08] **AgentBench: Evaluating LLMs as Agents** *Xiao Liu et al. arXiv.* [[paper](https://arxiv.org/abs/2308.03688)]
  - TODO
- [2023/07] **WebArena: A Realistic Web Environment for Building Autonomous Agents** *Shuyan Zhou et al. arXiv.* [[paper](https://arxiv.org/abs/2307.13854)]
  - TODO
- [2023/09] **MINT: Evaluating LLMs in Multi-turn Interaction with Tools and Language Feedback** *Xingyao Wang et al. arXiv.* [[paper](https://arxiv.org/abs/2309.10691)]
  - TODO
- [2023/12] **T-Eval: Evaluating the Tool Utilization Capability of Large Language Models Step by Step** *Zehui Chen et al. arXiv.* [[paper](https://arxiv.org/abs/2312.14033)]
  - TODO
- [2024/10] **Agent Arena: Evaluating and Comparing LLM Agents Across Models, Tools, and Frameworks** *Nithik Yekollu et al. arXiv.* [[blog](https://gorilla.cs.berkeley.edu/blogs/14_agent_arena.html)]
  - TODO

## 5. Surveys
- [2023/03] **A Survey of Large Language Models** *Wayne Xin Zhao et al. arXiv.* [[paper](https://arxiv.org/abs/2303.18223)]
  - TODO
- [2023/08] **A Survey on Large Language Model based Autonomous Agents** *Lei Wang et al. arXiv.* [[paper](https://arxiv.org/abs/2308.11432)]
  - TODO
- [2023/09] **The Rise and Potential of Large Language Model Based Agents: A Survey** *Zhiheng Xi et al. arXiv.* [[paper](https://arxiv.org/abs/2309.07864)]
  - TODO
- [2023/09] **An In-depth Survey of Large Language Model-based Artificial Intelligence Agents** *Pengyu Zhao et al. arXiv.* [[paper](https://arxiv.org/abs/2309.14365)]
  - TODO
- [2023/09] **Natural Language based Context Modeling and Reasoning for Ubiquitous Computing with Large Language Models: A Tutoria** *Haoyi Xiong et al. arXiv.* [[paper](https://arxiv.org/abs/2309.15074)]
  - TODO

## 6. Agents
- [2023/07] **A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis** *Izzeddin Gur et al. arXiv.* [[paper](https://arxiv.org/abs/2307.12856)]
  - TODO
- [2023/10] **Agent Instructs Large Language Models to be General Zero-Shot Reasoners** *Nicholas Crispino et al. arXiv.* [[paper](https://arxiv.org/abs/2310.03710)]
  - TODO
- [2023/04] **Generative Agents: Interactive Simulacra of Human Behavior** *Joon Sung Park et al. arXiv.* [[paper](https://arxiv.org/abs/2304.03442)]
  - TODO
- [2023/05] **SwiftSage: A Generative Agent with Fast and Slow Thinking for Complex Interactive Tasks** *Bill Yuchen Lin et al. arXiv.* [[paper](https://arxiv.org/abs/2305.17390)]
  - TODO
- [2023/08] **AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation** *Qingyun Wu et al. arXiv.* [[paper](https://arxiv.org/abs/2308.08155)]
  - TODO
- [2023/09] **AutoAgents: A Framework for Automatic Agent Generation** *Guangyao Che et al. arXiv.* [[paper](https://arxiv.org/abs/2309.17288)]
  - TODO
- [2023/10] **OpenAgents: An Open Platform for Language Agents in the Wild** *Tianbao Xie et al. arXiv.* [[paper](https://arxiv.org/abs/2310.10634)]
  - TODO
- [2023/10] **Agent Instructs Large Language Models to be General Zero-Shot Reasoners** *Nicholas Crispino et al. arXiv.* [[paper](https://arxiv.org/abs/2310.03710)]
  - TODO
- [2023/10] **Adapting LLM Agents with Universal Feedback in Communication** *Kuan Wang et al. arXiv.* [[paper](https://arxiv.org/abs/2310.01444)]
  - TODO
- [2024/04] **ClinicalAgent: Clinical Trial Multi-Agent System with Large Language Model-based Reasoning** *Ling Yue et al. arXiv.* [[paper](https://arxiv.org/abs/2404.14777)]
  - TODO
- [2024/05] **AgentClinic: a multimodal agent benchmark to evaluate AI in simulated clinical environments** *Samuel Schmidgall et al. arXiv.* [[paper](https://arxiv.org/abs/2405.07960)]
  - TODO
