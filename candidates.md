# 候选论文总表

| 序号 | 论文标题 | 一句话介绍 | 首次公开或发表状态 | 作者机构情况 | 引用 | 用户备注 |
| :--: | --- | --- | --- | --- | --- | --- |
| 1 | [SkillOS: Learning Skill Curation for Self-Evolving Agents](https://arxiv.org/abs/2605.06614) | 通过强化学习训练独立技能策展器，使其依据历史轨迹持续插入、更新和删除 SkillRepo 中的技能，并在不同执行器与任务上实现迁移。 | 2026-05-07 首次公开于 arXiv | Google Cloud AI Research；UIUC；MIT |  |  |
| 2 | [SkillMaster: Toward Autonomous Skill Mastery in LLM Agents](https://arxiv.org/abs/2605.08693) | 通过轨迹驱动的技能审查、反事实效用评估和 DualAdv-GRPO，联合学习任务执行与技能创建、修订和选择。 | 2026-05-09 首次公开于 arXiv（2026-05-12 更新） | Shandong University；Zhongguancun Academy；Tsinghua University；Southeast University；University of Science and Technology of China |  |  |
| 3 | [EvolveMem: Self-Evolving Memory Architecture via AutoResearch for LLM Agents](https://arxiv.org/abs/2605.13941) | 将记忆检索配置暴露为可优化动作空间，由诊断与元分析模块根据失败日志自动演化检索架构并在退化时回滚。 | 2026-05-13 首次公开于 arXiv | UNC-Chapel Hill；UC Berkeley；UCSC |  |  |
| 4 | [SkillOpt: Executive Strategy for Self-Evolving Agent Skills](https://arxiv.org/abs/2605.23904) | 把 Agent 技能文档视为冻结模型的外部可训练状态，用受限文本编辑、验证门控和拒绝编辑记忆稳定优化跨 Harness 技能。 | 2026-05-22 首次公开于 arXiv（2026-05-25 更新） | Microsoft；上海交通大学；同济大学；复旦大学 |  |  |
| 5 | [MUSE-Autoskill: Self-Evolving Agents via Skill Creation, Memory, Management, and Evaluation](https://arxiv.org/abs/2605.27366) | 以创建、记忆、管理、评测和精炼的统一生命周期维护可复用技能，并用技能级记忆积累跨任务经验。 | 2026-05-26 首次公开于 arXiv | 字节跳动；Rochester Institute of Technology |  |  |
| 6 | [SkillRevise: Improving LLM-Authored Agent Skills via Trace-Conditioned Skill Revision](https://arxiv.org/abs/2606.01139) | 从执行轨迹诊断初始技能缺陷，检索通用修复原则并通过重新执行与验证门控迭代保留更有效的技能版本。 | 2026-05-31 首次公开于 arXiv（2026-06-17 更新至 v3） | Hong Kong University of Science and Technology；Harbin Institute of Technology；Harbin Institute of Technology, Shenzhen；Nanjing University；University of Hong Kong |  |  |
| 7 | [SkillAdaptor: Self-Adapting Skills for LLM Agents from Trajectories](https://arxiv.org/abs/2606.01311) | 在失败轨迹中定位首个可操作错误步骤并归因到具体技能，以接受检查约束训练免更新，实现更稳定的局部技能维护。 | 2026-05-31 首次公开于 arXiv（Work in progress） | Zhejiang University；Ant Digital Technologies, Ant Group；Zhejiang University–Ant Group Joint Laboratory of Knowledge Graph |  |  |
| 8 | [Agent Memory: Characterization and System Implications of Stateful Long-Horizon Workloads](https://arxiv.org/abs/2606.06448) | 从系统视角刻画长期有状态 Agent 记忆的构建、检索与生成成本，并总结面向新鲜度、延迟和规模化管理的设计建议。 | 2026-06-04 首次公开于 arXiv | Stanford University；KU Leuven；MIT；Independent Researcher |  |  |
| 9 | [Bayesian-Agent: Posterior-Guided Skill Evolution for LLM Agent Harnesses](https://arxiv.org/abs/2606.08348) | 把技能与 SOP 作为带不确定性的假设，基于验证轨迹维护后验并触发补丁、拆分、压缩、退役或探索等可审计操作。 | 2026-06-06 首次公开于 arXiv | IDEA Research；香港科技大学（广州）；DataArcTech |  |  |
| 10 | [Are We Ready For An Agent-Native Memory System?](https://arxiv.org/abs/2606.24775) | 从数据管理视角拆解 Agent 记忆的存储、抽取、检索路由和维护模块，比较动态更新下的效果、成本与稳定性。 | 2026-06-23 首次公开于 arXiv | Shanghai Jiao Tong University；Tsinghua University；MemTensor (Shanghai) Technology |  |  |
| 11 | [Forget to Improve: On-Device LLM-Agent Continual Learning via Budget-Curated Memory](https://arxiv.org/abs/2606.25115) | 以单位字节净价值统一决定经验记忆的保留、共享和信任，在受限设备上兼顾持续学习、资源预算与抗投毒。 | 2026-06-23 首次公开于 arXiv | South Dakota State University；Virginia Commonwealth University |  |  |
| 12 | [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366) | 将环境反馈转写为语言反思并存入情景记忆，在不更新模型参数的情况下让 Agent 从多次尝试中改进决策。 | 2023-03-20 首次公开于 arXiv | Northeastern University；MIT；Princeton University |  |  |
| 13 | [Self-Refine: Iterative Refinement with Self-Feedback](https://arxiv.org/abs/2303.17651) | 让同一 LLM 反复生成反馈并修订输出，形成无需额外训练的自我反馈—改进循环，为后续反思型 Agent 提供通用机制。 | 2023-03-30 首次公开于 arXiv | Carnegie Mellon University；Allen Institute for AI；University of Washington；NVIDIA；UC San Diego；Google Research |  |  |
| 14 | [Voyager: An Open-Ended Embodied Agent with Large Language Models](https://arxiv.org/abs/2305.16291) | 以自动课程、可复用代码技能库和执行反馈驱动的迭代提示，在 Minecraft 中实现开放式终身技能积累与迁移。 | 2023-05-25 首次公开于 arXiv | NVIDIA；Caltech；UT Austin；Stanford University；UW–Madison |  |  |
| 15 | [AdaPlanner: Adaptive Planning from Feedback with Language Models](https://arxiv.org/abs/2305.16653) | 根据环境反馈在计划内外动态修订计划，并把成功计划沉淀为少样本技能示例，提升后续任务的规划效率。 | 2023-05-26 首次公开于 arXiv | Georgia Institute of Technology |  |  |
| 16 | [Large Language Models Are Semi-Parametric Reinforcement Learning Agents](https://arxiv.org/abs/2306.07929) | 以长期经验记忆保存跨回合成功与失败，并用记忆级强化学习更新经验选择，使冻结 LLM Agent 持续演化。 | 2023-06-09 首次公开于 arXiv | Shanghai Jiao Tong University；Suzhou Laboratory |  |  |
| 17 | [Retroformer: Retrospective Large Language Agents with Policy Gradient Optimization](https://arxiv.org/abs/2308.02151) | 训练回顾模型从失败根因和环境奖励中生成提示修订，通过策略梯度持续优化 Agent 的决策提示。 | 2023-08-04 首次公开于 arXiv | Salesforce Research |  |  |
| 18 | [ExpeL: LLM Agents Are Experiential Learners](https://arxiv.org/abs/2308.10144) | 从训练任务轨迹中自动归纳自然语言经验原则，并在推理时检索原则与相似经历，实现无需参数更新的跨任务经验迁移。 | 2023-08-20 首次公开于 arXiv；AAAI 2024 | Tsinghua University |  |  |
| 19 | [Language Agent Tree Search Unifies Reasoning, Acting, and Planning in Language Models](https://arxiv.org/abs/2310.04406) | 将蒙特卡洛树搜索、语言模型价值评估、外部反馈和失败反思结合，在单任务搜索过程中迭代改进推理与行动轨迹。 | 2023-10-06 首次公开于 arXiv | University of Illinois Urbana-Champaign；Lapis Labs |  |  |
| 20 | [CLIN: A Continually Learning Language Agent for Rapid Task Adaptation and Generalization](https://arxiv.org/abs/2310.10134) | 持续更新以因果抽象为核心的文本记忆，使冻结模型在不同任务和环境间累积经验并快速适应。 | 2023-10-16 首次公开于 arXiv | Allen Institute for AI；University of Arizona；University of Pennsylvania |  |  |
| 21 | [Empowering Large Language Model Agents through Action Learning](https://arxiv.org/abs/2402.15809) | 从失败任务中迭代创建和修订 Python 动作函数，扩展 Agent 的开放动作空间并把经验转化为可复用技能。 | 2024-02-24 首次公开于 arXiv | Peking University；ByteDance；University of Hong Kong |  |  |
| 22 | [Large Language Models Can Self-Improve At Web Agent Tasks](https://arxiv.org/abs/2405.20309) | 用 Agent 自己生成的 WebArena 轨迹构造合成训练数据并微调基础模型，验证 Agent 能通过自生成经验提高长程网页任务能力。 | 2024-05-30 首次公开于 arXiv | University of Pennsylvania；ExtensityAI；Johannes Kepler University Linz；NXAI |  |  |
| 23 | [Agent Workflow Memory](https://arxiv.org/abs/2409.07429) | 从离线或在线交互轨迹中归纳可复用工作流，并在后续任务中选择性检索，提升跨任务和跨网站泛化。 | 2024-09-11 首次公开于 arXiv | Carnegie Mellon University；MIT |  |  |
| 24 | [DynaSaur: Large Language Agents Beyond Predefined Actions](https://arxiv.org/abs/2411.01747) | 允许 Agent 在线生成、组合并积累通用程序动作，在现有工具缺失或失败时形成可复用的新动作能力。 | 2024-11-04 首次公开于 arXiv；COLM 2025 | University of Maryland；Adobe Research |  |  |
| 25 | [WebEvolver: Enhancing Web Agent Self-Improvement with Coevolving World Model](https://arxiv.org/abs/2504.21024) | 让网页 Agent 与世界模型共同演化，由世界模型生成训练数据并执行前瞻模拟，突破自主学习中的探索停滞。 | 2025-04-23 首次公开于 arXiv；EMNLP 2025 Main Conference | Tencent AI Lab |  |  |
| 26 | [Memento: Fine-tuning LLM Agents without Fine-tuning LLMs](https://arxiv.org/abs/2508.16153) | Memento 以情景记忆和可学习案例选择策略构建在线强化学习循环，通过记忆读写让 Agent 无需更新底座模型即可持续适应。 | 2025-08-22 首次公开于 arXiv（2025-08-25 更新至 v2） | UCL AI Centre；Huawei Noah’s Ark Lab；Jilin University；Institute of Automation, CAS |  |  |
| 27 | [Learning on the Job: An Experience-Driven Self-Evolving Agent for Long-Horizon Tasks](https://arxiv.org/abs/2510.08002) | 用分层记忆组织轨迹反思形成的结构化经验，使长程任务 Agent 在工作中持续学习并将经验迁移到新任务。 | 2025-10-09 首次公开于 arXiv | Central South University；Shanghai AI Laboratory；Fudan University；Shanghai Innovation Institute；Zhejiang University |  |  |
| 28 | [Remember Me, Refine Me: A Dynamic Procedural Memory Framework for Experience-Driven Agent Evolution](https://arxiv.org/abs/2512.10696) | 通过多维经验蒸馏、情境自适应复用和效用驱动的增删机制，让程序记忆从静态归档转为持续演化的经验池。 | 2025-12-11 首次公开于 arXiv（2026-04-15 更新至 v2） | Shanghai Jiao Tong University；Tongyi Lab, Alibaba Group |  |  |
| 29 | [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) | 构建带观察、反思和规划记忆流的生成式 Agent，使其在沙盒社会中积累经历并形成长期一致行为。 | 2023-04 首次公开于 arXiv；UIST 2023 |  |  |  |
| 30 | [MemoryBank: Enhancing Large Language Models with Long-Term Memory](https://arxiv.org/abs/2305.10250) | 用遗忘曲线驱动的长期记忆存储、检索和更新机制，使对话 Agent 能持续记住用户信息并适应关系变化。 | 2023-05 首次公开于 arXiv |  |  |  |
| 31 | [MemGPT: Towards LLMs as Operating Systems](https://arxiv.org/abs/2310.08560) | 借鉴操作系统的分层内存与分页机制，让 Agent 自主在上下文和外部存储间搬运信息以支持长期任务。 | 2023-10 首次公开于 arXiv |  |  |  |
| 32 | [A Human-Inspired Reading Agent with Gist Memory of Very Long Contexts](https://arxiv.org/abs/2402.09727) | 让阅读 Agent 将长文档压缩成情景式 gist memory，并在需要时主动回查原文，扩展可处理的有效上下文。 | 2024-02 首次公开于 arXiv |  |  |  |
| 33 | [MEMORYLLM: Towards Self-Updatable Large Language Models](https://arxiv.org/abs/2402.04624) | 在模型内部加入可持续更新的潜空间记忆池，使部署后的模型能够反复写入新知识并长期保持。 | 2024-02 首次公开于 arXiv |  |  |  |
| 34 | [A Survey on the Memory Mechanism of Large Language Model based Agents](https://arxiv.org/abs/2404.13501) | 系统梳理 LLM Agent 的记忆写入、管理、检索与评测，为经验积累和自进化研究提供统一分类。 | 2024-04 首次公开于 arXiv |  |  |  |
| 35 | [HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models](https://arxiv.org/abs/2405.14831) | 以知识图谱和个性化 PageRank 模拟海马体索引，实现跨文档、多跳关联的长期记忆检索。 | 2024-05 首次公开于 arXiv；NeurIPS 2024 |  |  |  |
| 36 | [Evaluating Very Long-Term Conversational Memory of LLM Agents](https://arxiv.org/abs/2402.17753) | 提出 LoCoMo 长期多会话基准，检验 Agent 对跨数十会话事实、时间和因果关系的持续记忆能力。 | 2024-02 首次公开于 arXiv |  |  |  |
| 37 | [LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory](https://arxiv.org/abs/2410.10813) | 从信息提取、多会话推理、时间推理、知识更新和拒答五方面评测长期交互记忆。 | 2024-10 首次公开于 arXiv |  |  |  |
| 38 | [A-MEM: Agentic Memory for LLM Agents](https://arxiv.org/abs/2502.12110) | 借鉴卡片盒方法让 Agent 自动生成记忆属性、建立链接并动态重组，使记忆结构随经验演化。 | 2025-02 首次公开于 arXiv |  |  |  |
| 39 | [Lifelong Learning of Large Language Model based Agents: A Roadmap](https://arxiv.org/abs/2501.07278) | 从感知、记忆和行动模块总结 Agent 终身学习路线，归纳持续适应、知识保留和跨任务迁移问题。 | 2025-01 首次公开于 arXiv |  |  |  |
| 40 | [Memento No More: Coaching AI Agents to Master Multiple Tasks via Hints Internalization](https://arxiv.org/abs/2502.01562) | 通过反复尝试和提示内化，把外部指导逐步蒸馏进 Agent 的上下文策略，使其掌握多任务技能。 | 2025-02 首次公开于 arXiv |  |  |  |
| 41 | [Contextual Experience Replay for Self-Improvement of Language Agents](https://arxiv.org/abs/2506.06698) | 从历史轨迹中合成与当前状态相关的经验片段，形成动态回放缓冲区以提升网页 Agent 的自我改进效率。 | 2025-06 首次公开于 arXiv |  |  |  |
| 42 | [Evo-Memory: Benchmarking LLM Agent Test-time Learning with Self-Evolving Memory](https://arxiv.org/abs/2511.20857) | 用连续任务流评测 Agent 在测试期更新记忆、复用经验和避免退化的能力，并提供可演化记忆基线。 | 2025-11 首次公开于 arXiv |  |  |  |
| 43 | [WebCoach: Self-Evolving Web Agents with Cross-Session Memory Guidance](https://arxiv.org/abs/2511.12997) | 通过跨会话记忆总结和策略指导，让网页 Agent 从此前任务的成功与失败中持续修正后续行为。 | 2025-11 首次公开于 arXiv |  |  |  |
| 44 | [Intrinsic Memory Agents: Heterogeneous Multi-Agent LLM Systems through Structured Contextual Memory](https://arxiv.org/abs/2508.08997) | 为多 Agent 系统维护角色对齐的结构化内生记忆，在长期协作中保持职责一致并聚焦任务相关经验。 | 2025-08 首次公开于 arXiv |  |  |  |
| 45 | [Training LLM-Based Agents with Synthetic Self-Reflected Trajectories and Partial Masking](https://arxiv.org/abs/2505.20023) | 利用自反思修正后的合成轨迹和局部损失屏蔽训练 Agent，降低错误轨迹传播并提高数据效率。 | 2025-05 首次公开于 arXiv |  |  |  |
| 46 | [Self-Generated In-Context Examples Improve LLM Agents for Sequential Decision-Making Tasks](https://arxiv.org/abs/2505.00234) | 让 Agent 生成并选择成功轨迹作为上下文示例，在不依赖人工规则的情况下改进序列决策。 | 2025-05 首次公开于 arXiv |  |  |  |
| 47 | [InSTA: Towards Internet-Scale Training For Agents](https://arxiv.org/abs/2502.06776) | 自动生成网页任务、完成轨迹并判定成功，构建可扩展的 Agent 训练数据生产闭环。 | 2025-02 首次公开于 arXiv |  |  |  |
| 48 | [WebRL: Training LLM Web Agents via Self-Evolving Online Curriculum Reinforcement Learning](https://arxiv.org/abs/2411.02337) | 用自演化在线课程、结果奖励模型和强化学习，使开源网页 Agent 持续生成适合自身能力的训练任务。 | 2024-11 首次公开于 arXiv |  |  |  |
| 49 | [WebAgent-R1: Training Web Agents via End-to-End Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2505.16421) | 直接在多轮网页交互中以结果奖励训练 Agent，并通过多样轨迹生成和测试时扩展提升长程决策。 | 2025-05 首次公开于 arXiv |  |  |  |
| 50 | [SAC-GLAM: Improving Online RL for LLM agents with Soft Actor-Critic and Hindsight Relabeling](https://arxiv.org/abs/2410.12481) | 将离策略 Soft Actor-Critic 和事后目标重标记引入 LLM Agent，复用失败经验改进在线学习。 | 2024-10 首次公开于 arXiv |  |  |  |
| 51 | [ProgRM: Build Better GUI Agents with Progress Rewards](https://arxiv.org/abs/2505.18121) | 训练进度奖励模型为 GUI Agent 提供密集的中间反馈，缓解只依赖最终成败信号的学习困难。 | 2025-05 首次公开于 arXiv |  |  |  |
| 52 | [Agent0: Unleashing Self-Evolving Agents from Zero Data via Tool-Integrated Reasoning](https://arxiv.org/abs/2511.16043) | 从零人工数据出发，让课程 Agent 与执行 Agent 共同演化任务和工具推理能力。 | 2025-11 首次公开于 arXiv |  |  |  |
| 53 | [Reinforcement Learning for Self-Improving Agent with Skill Library](https://arxiv.org/abs/2512.17102) | 提出 SAGE，通过技能增强的轨迹采样与奖励训练 Agent 学会调用和扩展技能库。 | 2025-12 首次公开于 arXiv |  |  |  |
| 54 | [AutoFlow: Automated Workflow Generation for Large Language Model Agents](https://arxiv.org/abs/2407.12821) | 把 Agent 工作流表示成自然语言程序，并通过搜索与反馈自动生成适配不同模型的执行流程。 | 2024-07 首次公开于 arXiv |  |  |  |
| 55 | [FlowBench: Revisiting and Benchmarking Workflow-Guided Planning for LLM-based Agents](https://arxiv.org/abs/2406.14884) | 系统评测不同形式和粒度的工作流知识如何影响 Agent 规划，为工作流学习提供统一测试平台。 | 2024-06 首次公开于 arXiv |  |  |  |
| 56 | [Learning to Use Tools via Cooperative and Interactive Agents](https://arxiv.org/abs/2403.03031) | 用规划、调用、观察等协作 Agent 分解工具学习流程，并依据执行反馈迭代校准工具选择。 | 2024-03 首次公开于 arXiv |  |  |  |
| 57 | [Small LLMs Are Weak Tool Learners: A Multi-LLM Agent](https://arxiv.org/abs/2401.07324) | 将规划、工具调用和结果总结拆给不同模型，并通过分阶段训练提高小模型的工具学习能力。 | 2024-01 首次公开于 arXiv |  |  |  |
| 58 | [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761) | 让语言模型自监督生成并筛选 API 调用示例，从而在极少人工监督下学会何时及如何使用工具。 | 2023-02 首次公开于 arXiv |  |  |  |
| 59 | [Gorilla: Large Language Model Connected with Massive APIs](https://arxiv.org/abs/2305.15334) | 通过 API 文档检索与专项微调提升模型调用大规模工具的准确性，并减少接口幻觉。 | 2023-05 首次公开于 arXiv |  |  |  |
| 60 | [ART: Automatic multi-step reasoning and tool-use for large language models](https://arxiv.org/abs/2303.09014) | 从任务库自动检索多步推理和工具使用示例，并允许模型组合与修订程序化解决过程。 | 2023-03 首次公开于 arXiv |  |  |  |
| 61 | [CREATOR: Tool Creation for Disentangling Abstract and Concrete Reasoning of Large Language Models](https://arxiv.org/abs/2305.14318) | 让模型自主创建可执行工具，将抽象推理和具体计算分离，并从执行结果中修正工具与答案。 | 2023-05 首次公开于 arXiv |  |  |  |
| 62 | [ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs](https://arxiv.org/abs/2307.16789) | 通过自动指令生成、路径搜索和执行验证构造大规模真实 API 轨迹，训练通用工具调用 Agent。 | 2023-07 首次公开于 arXiv |  |  |  |
| 63 | [AnyTool: Self-Reflective, Hierarchical Agents for Large-Scale API Calls](https://arxiv.org/abs/2402.04253) | 以分层 API 检索、求解和失败自反思机制，在万级工具空间中持续调整调用计划。 | 2024-02 首次公开于 arXiv |  |  |  |
| 64 | [FireAct: Toward Language Agent Fine-tuning](https://arxiv.org/abs/2310.05915) | 用多任务、多提示方式产生的 Agent 轨迹微调语言模型，系统验证轨迹训练对泛化、鲁棒性和效率的提升。 | 2023-10 首次公开于 arXiv |  |  |  |
| 65 | [AgentTuning: Enabling Generalized Agent Abilities for LLMs](https://arxiv.org/abs/2310.12823) | 将高质量交互轨迹与通用指令混合训练，使开源模型获得跨环境规划、记忆和工具使用能力。 | 2023-10 首次公开于 arXiv |  |  |  |
| 66 | [Agent-FLAN: Designing Data and Methods of Effective Agent Tuning for Large Language Models](https://arxiv.org/abs/2403.12881) | 拆分格式遵循与 Agent 推理能力，配合负样本设计提升 Agent 微调效果并抑制工具幻觉。 | 2024-03 首次公开于 arXiv |  |  |  |
| 67 | [AgentGym: Evolving Large Language Model-based Agents across Diverse Environments](https://arxiv.org/abs/2406.04151) | 提供多环境交互平台、轨迹库和 AgentEvol 方法，使 Agent 在跨任务探索中进行可扩展自进化。 | 2024-06 首次公开于 arXiv |  |  |  |
| 68 | [AgentBank: Towards Generalized LLM Agents via Fine-Tuning on 50000+ Interaction Trajectories](https://arxiv.org/abs/2410.07706) | 汇集五万余条多环境交互轨迹并研究规模化轨迹微调，提升 Agent 技能的跨任务泛化。 | 2024-10 首次公开于 arXiv |  |  |  |
| 69 | [AgentInstruct: Toward Generative Teaching with Agentic Flows](https://arxiv.org/abs/2407.03502) | 用可组合 Agent 流程从原始文档和代码自动生成大规模高质量训练数据，支持工具使用等新能力教学。 | 2024-07 首次公开于 arXiv |  |  |  |
| 70 | [Agent Q: Advanced Reasoning and Learning for Autonomous AI Agents](https://arxiv.org/abs/2408.07199) | 结合引导式树搜索、自我批评和离策略偏好优化，让 Agent 从成功与失败交互轨迹中迭代学习。 | 2024-08 首次公开于 arXiv |  |  |  |
| 71 | [WebArena: A Realistic Web Environment for Building Autonomous Agents](https://arxiv.org/abs/2307.13854) | 提供可复现的真实网站环境和长程任务，以执行结果衡量 Agent 在复杂网页操作中的持续改进。 | 2023-07 首次公开于 arXiv；ICLR 2024 |  |  |  |
| 72 | [VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks](https://arxiv.org/abs/2401.13649) | 扩展真实网页环境到图文混合任务，检验多模态 Agent 的视觉理解、规划和执行能力。 | 2024-01 首次公开于 arXiv |  |  |  |
| 73 | [Mind2Web: Towards a Generalist Agent for the Web](https://arxiv.org/abs/2306.06070) | 收集跨 137 个真实网站的开放任务与操作轨迹，为通用网页 Agent 的训练和跨域泛化提供基础。 | 2023-06 首次公开于 arXiv；NeurIPS 2023 |  |  |  |
| 74 | [AgentBench: Evaluating LLMs as Agents](https://arxiv.org/abs/2308.03688) | 在八类交互环境中统一评测 Agent 的长期推理、决策和指令遵循，分析典型失败模式。 | 2023-08 首次公开于 arXiv；ICLR 2024 |  |  |  |
| 75 | [GAIA: a benchmark for General AI Assistants](https://arxiv.org/abs/2311.12983) | 用需要推理、浏览、多模态和工具使用的真实问题评测通用助手，为 Agent 能力演化提供综合目标。 | 2023-11 首次公开于 arXiv；ICLR 2024 |  |  |  |
| 76 | [AgentBoard: An Analytical Evaluation Board of Multi-turn LLM Agents](https://arxiv.org/abs/2401.13178) | 除最终成功率外引入过程进度指标，支持对多轮 Agent 的规划、行动和失败阶段进行细粒度诊断。 | 2024-01 首次公开于 arXiv |  |  |  |
| 77 | [WorkArena: How Capable Are Web Agents at Solving Common Knowledge Work Tasks?](https://arxiv.org/abs/2403.07718) | 在企业软件中构建常见知识工作任务，提供可交互训练环境和执行评测以衡量工作型 Agent。 | 2024-03 首次公开于 arXiv |  |  |  |
| 78 | [OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments](https://arxiv.org/abs/2404.07972) | 在真实桌面操作系统和多应用工作流中评测 Agent，为计算机使用能力的训练和迭代提供统一环境。 | 2024-04 首次公开于 arXiv；NeurIPS 2024 |  |  |  |
| 79 | [SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770) | 以真实 GitHub 问题和代码仓库检验软件工程 Agent 的定位、修改、执行和跨文件推理能力。 | 2023-10 首次公开于 arXiv；ICLR 2024 |  |  |  |
| 80 | [The BrowserGym Ecosystem for Web Agent Research](https://arxiv.org/abs/2412.05467) | 统一多个网页基准的观察、动作和评测接口，降低 Agent 训练、比较和行为分析的实验成本。 | 2024-12 首次公开于 arXiv |  |  |  |
| 81 | [WorkArena++: Towards Compositional Planning and Reasoning-based Common Knowledge Work Tasks](https://arxiv.org/abs/2407.05291) | 在 WorkArena 上加入组合式知识工作任务，重点检验跨应用规划、检索和推理能力。 | 2024-07 首次公开于 arXiv |  |  |  |
| 82 | [AgentRewardBench: Evaluating Automatic Evaluations of Web Agent Trajectories](https://arxiv.org/abs/2504.08942) | 以专家标注轨迹评测自动奖励模型和 LLM 评审器，为 Agent 训练中的可靠反馈信号提供基准。 | 2025-04 首次公开于 arXiv |  |  |  |
| 83 | [An Illusion of Progress? Assessing the Current State of Web Agents](https://arxiv.org/abs/2504.01382) | 通过在线真实网站和人类对齐评审重新评估网页 Agent，揭示静态基准可能高估改进幅度。 | 2025-04 首次公开于 arXiv |  |  |  |
| 84 | [Large Language Models as Optimizers](https://arxiv.org/abs/2309.03409) | 将历史候选提示及其得分写入元提示，让 LLM 迭代提出并评估更优指令，为 Agent 的 Prompt 与 Harness 黑盒优化提供基础范式。 | 2023-09-07 首次公开于 arXiv；ICLR 2024 | Google DeepMind |  |  |
| 85 | [EvoPrompt: Connecting LLMs with Evolutionary Algorithms Yields Powerful Prompt Optimizers](https://arxiv.org/abs/2309.08532) | 将 LLM 与遗传算法、差分进化等演化算子结合，在离散自然语言空间中持续生成、筛选和改进 Prompt。 | 2023-09-15 首次公开于 arXiv；ICLR 2024 |  |  |  |
| 86 | [Promptbreeder: Self-Referential Self-Improvement Via Prompt Evolution](https://arxiv.org/abs/2309.16797) | 同时演化任务 Prompt 和负责改写 Prompt 的变异 Prompt，形成自指式的提示优化循环。 | 2023-09-28 首次公开于 arXiv |  |  |  |
| 87 | [CRAFT: Customizing LLMs by Creating and Retrieving from Specialized Toolsets](https://arxiv.org/abs/2309.17428) | 从训练样例自动生成、验证、抽象和去重可复用代码工具，并在推理时检索调用，为 Agent 建立可扩展的任务专用技能库。 | 2023-09-29 首次公开于 arXiv；ICLR 2024 | University of Illinois Urbana-Champaign |  |  |
| 88 | [Self-Taught Optimizer (STOP): Recursively Self-Improving Code Generation](https://arxiv.org/abs/2310.02304) | 让调用 LLM 的改进器程序递归优化自身脚手架代码，并用下游效用筛选更好的改进策略，直接探索可自我改写的 Agent Harness。 | 2023-10-03 首次公开于 arXiv；COLM 2024 | Microsoft Research；Stanford University |  |  |
| 89 | [DSPy: Compiling Declarative Language Model Calls into Self-Improving Pipelines](https://arxiv.org/abs/2310.03714) | 将 LM Pipeline 抽象为参数化声明式模块，并通过编译器自动收集示例和优化组合，使推理链与 Agent Loop 可按指标自举改进。 | 2023-10-05 首次公开于 arXiv | Stanford University |  |  |
| 90 | [Eureka: Human-Level Reward Design via Coding Large Language Models](https://arxiv.org/abs/2310.12931) | 用编码 LLM 对奖励函数进行进化搜索，并结合执行统计和反思持续改写奖励代码，使 Agent 通过强化学习自动获得复杂技能。 | 2023-10-19 首次公开于 arXiv；ICLR 2024 | NVIDIA；University of Pennsylvania；Caltech；UT Austin |  |  |
| 91 | [Language Agents as Optimizable Graphs](https://arxiv.org/abs/2402.16823) | 将单 Agent 与多 Agent 协作统一表示为可优化计算图，同时学习节点提示和图连接，自动改进推理流程与协作拓扑。 | 2024-02-26 首次公开于 arXiv；ICML 2024 | KAUST AI Initiative；Swiss AI Lab IDSIA / USI / SUPSI |  |  |
| 92 | [Agent-Pro: Learning to Evolve via Policy-Level Reflection and Optimization](https://arxiv.org/abs/2402.17574) | 把长程交互轨迹和动态信念压缩为可优化的行为准则与世界模型，并通过策略级反思和深度优先搜索持续升级 Agent Prompt。 | 2024-02-27 首次公开于 arXiv；ACL 2024 Main | Zhejiang University；Institute of Software, CAS；University of Chinese Academy of Sciences |  |  |
| 93 | [Optimizing Instructions and Demonstrations for Multi-Stage Language Model Programs](https://arxiv.org/abs/2406.11695) | 在缺少模块级标签和梯度时，联合优化多阶段 LM 程序各模块的自由文本指令与少样本示例，为复杂 Agent Pipeline 提供端到端 Prompt 优化器。 | 2024-06-17 首次公开于 arXiv；EMNLP 2024 | Stanford University；Basis Research Institute；KTH Royal Institute of Technology；UC Berkeley |  |  |

## 填写规则

- 论文标题使用完整标题，并尽量链接到论文页面；
- 一句话介绍根据标题和摘要概括；
- 首次公开或发表状态记录公开或正式发表信息，例如“2026-05-12 首次公开于 arXiv”或“ICML 2026”；
- 作者机构情况以论文首页列出的机构为准，使用简短名称；未核实则留空；
- 引用填写检索时查到的数值，未查到则留空；按单一可用来源记录即可，后续是否刷新由具体任务决定；
- 用户备注保持原样；
- 同一论文只保留一条记录，按规范化标题去重。
