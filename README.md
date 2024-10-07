# conversational-agents-survey
Paper lists for "Conversational Agents: A Survey of Advances, Challenges, and Future Directions"

# 💫 Introduction
The development of conversational agents has always been an area of keen interest within artificial intelligence (AI) research, representing a significant step towards creating interactive systems capable of human-like understanding, communication, and acting. Conversational agents are chat-based AI systems that aim to interact with users in a human-like manner by understanding their input, engaging in meaningful communication, and performing actions based on the user’s intent and context.

In recent years, the emergence of Large Language Models (LLMs) has further accelerated the progress of Conversational Agents. LLMs now serve as the backbone of many state-of-the-art conversational systems, seamlessly integrating with APIs and databases to perform complex multi-step tasks, such as restaurant reservations or calling a taxi. This integration allows agents to interact with external services, access up-to-date information, and ensure task completion by providing users with more dynamic, context-driven, and reliable experiences.

This paper presents a thorough survey of the recent advancements, challenges, and future research directions in the scope of conversational agents. We begin by establishing a taxonomy that categorizes conversational agents according to their prompting strategies, training data formats, fine-tuning methods, and evaluation protocols. Next, we discuss recent breakthroughs in natural language understanding, dialogue management, and response generation by highlighting the contributions of LLMs in these areas and how agents can relate those. Subsequently, we examine various challenges that remain, such as handling multi-turn and multi-agent interactions, the personalization of dialogues, and addressing safety concerns. Finally, we outline potential future directions, such as the integration of cleaner and more advanced datasets,improved training strategies for agentic purposes and the development of more holistic evaluation frameworks for conversational agents.

This survey provides a comprehensive overview of the current state of conversational agents, shedding light on the strides made with LLMs, addressing key challenges, and outlining future directions to guide the continued evolution of intelligent, context-aware dialogue systems.

# 📝 Papers

## 1. Tools
- [2023/02] **Toolformer: Language Models Can Teach Themselves to Use Tools** *Timo Schick et al. arXiv.* [[paper](https://arxiv.org/abs/2302.04761)]
  - TODO
- [2023/04] **Tool Learning with Foundation Models** *Yujia Qin et al. arXiv.* [[paper](https://arxiv.org/abs/2304.08354)]
  - TODO
- [2023/07] **ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs** *Yujia Qin et al. arXiv.* [[paper](https://arxiv.org/abs/2307.16789)]
  - TODO

## 2. Prompting
- [2020/05] **Language Models are Few-Shot Learners** *Tom B. Brown et al. arXiv.* [[paper](https://arxiv.org/abs/2005.14165)]
  - This work pioneered Few-Shot Learning, paving the way for the concept of In-Context Learning through prompting strategies.
- [2022/01] **Chain-of-Thought Prompting Elicits Reasoning in Large Language Models** *Jason et al. arXiv.* [[paper](https://arxiv.org/abs/2201.11903)]
  - This work improved LLM reasonong by generating a step-by-step reasoning as an intermediate step to arrive final answer for complex tasks.
- [2022/10] **ReAct: Synergizing Reasoning and Acting in Language Models** *Shunyu Yao et al. arXiv.* [[paper](https://arxiv.org/abs/2210.03629)]
  - This work proposed to generate both the reasoning and action traces for agent-based task completion tasks.
- [2023/05] **Tree of Thoughts: Deliberate Problem Solving with Large Language Models** *Shunyu Yao et al. arXiv.* [[paper](https://arxiv.org/abs/2305.10601)]
  - TODO

## 3. Fine-tuning
- [2023/10] **AgentTuning: Enabling Generalized Agent Abilities for LLMs** *Aohan Zeng et al. arXiv.* [[paper](https://arxiv.org/abs/2310.12823)]
  - TODO
- [2023/10] **FireAct: Toward Language Agent Fine-tuning** *Baian Chen et al. arXiv.* [[paper](https://arxiv.org/abs/2310.05915)]
  - TODO
- [2024/02] **Executable Code Actions Elicit Better LLM Agents** *Xingyao Wang et al. arXiv.* [[paper](https://arxiv.org/abs/2402.01030)]
  - TODO
- [2024/03] **Agent-FLAN: Designing Data and Methods of Effective Agent Tuning for Large Language Models** *Zehui Chen et al. arXiv.* [[paper](https://arxiv.org/abs/2403.12881)]
  - TODO

## 4. Benchmarks
- [2018/09] **HotpotQA: A Dataset for Diverse, Explainable Multi-hop Question Answering** *Zhilin Yang et al. arXiv.* [[paper](https://arxiv.org/abs/1809.09600)]
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

## 6. Agents
- [2023/07] **A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis** *Izzeddin Gur et al. arXiv.* [[paper](https://arxiv.org/abs/2307.12856)]
  - TODO
- [2023/07] **A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis** *Izzeddin Gur et al. arXiv.* [[paper](https://arxiv.org/abs/2307.12856)]
  - TODO
