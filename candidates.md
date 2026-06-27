# 候选论文总表

本文件保存去重后的有效候选及其当前状态。去重以规范化论文标题为准，忽略大小写、首尾空格、连续空格和常见标点差异。

## 当前状态

- 推荐收录
- 暂时观察

## 候选记录

| 论文 | 发表情况 | 相关方向 | 核心贡献 | 判断理由 | 当前状态 |
| --- | --- | --- | --- | --- | --- |
| [From Player to Master: Enhancing Test-Time Learning of LLM Agents via Reinforcement Learning over Memory](https://arxiv.org/abs/2606.08656) | 2026-06-07；ICML 2026 已接收（作者备注） | 方法；记忆更新；跨回合 | MemoPilot 用多轮 GRPO、逐回合奖励和优势估计训练记忆更新策略。 | 机制直接且有正式会议接收；在连续博弈中明显优于记忆基线。 | 推荐收录（首次发现：2026-06-27-01；最近核查：2026-06-27） |
| [AdaMEM: Test-Time Adaptive Memory for Language Agents](https://arxiv.org/abs/2606.05684) | 2026-06-04；ICML 2026（作者备注） | 方法；轨迹与策略记忆；长程任务 | 结合离线长期轨迹记忆和在线短期策略记忆，并以 STEP-MFT 学习逐步策略。 | 在 ALFWorld、WebShop、HotpotQA 上稳定超过静态记忆基线。 | 推荐收录（首次发现：2026-06-27-01；最近核查：2026-06-27） |
| [Scaling Self-Evolving Agents via Parametric Memory](https://arxiv.org/abs/2606.04536) | 2026-06-03；arXiv 预印本 | 方法；显式记忆与快速参数更新；跨回合 | TMEM 将经验同时压缩为文本记忆并在线吸收到 LoRA fast weights。 | 突破只在 prompt 空间保存经验的范式，多类长期任务结果积极。 | 推荐收录（首次发现：2026-06-27-01；最近核查：2026-06-27） |
| [Managing Procedural Memory in LLM Agents: Control, Adaptation, and Evaluation](https://arxiv.org/abs/2606.23127) | 2026-06-22；arXiv 预印本 | 评测；程序性技能；跨任务/角色/模型 | AFTER 含 382 个企业任务、6 类角色和 22 项技能，评测技能演化与迁移。 | 同时测局部提升、迁移和过拟合，对 Harness 与 Agent Skills 也有价值。 | 推荐收录（首次发现：2026-06-27-01；最近核查：2026-06-27） |
| [Evo-Memory: Benchmarking LLM Agent Test-time Learning with Self-Evolving Memory](https://arxiv.org/abs/2511.20857) | 2025-11-25；2026-05-18 更新；arXiv 预印本 | 评测与方法；自演化记忆；连续任务流 | 统一实现十余种记忆模块，并提出 ExpRAG 与 ReMem。 | 覆盖 10 个数据集，把评测从静态回忆推进到持续更新与复用。 | 推荐收录（首次发现：2026-06-27-01；最近核查：2026-06-27） |
| [Memory-R1: Enhancing Large Language Model Agents to Manage and Utilize Memories via Reinforcement Learning](https://arxiv.org/abs/2508.19828) | 2025-08-27；2026-01-14 更新；arXiv 预印本 | 方法；记忆增删改查与利用；跨会话 | 以 RL 训练 Memory Manager 执行 ADD、UPDATE、DELETE、NOOP。 | 在三个长期记忆基准和多个模型规模上验证，训练样本较少。 | 推荐收录（首次发现：2026-06-27-01；最近核查：2026-06-27） |
| [How Memory Management Impacts LLM Agents: An Empirical Study of Experience-Following Behavior](https://arxiv.org/abs/2505.16067) | 2025-05-21；2025-10-10 更新；arXiv 预印本 | 诊断；经验加入与删除；长期性能 | 揭示 experience-following、错误传播和错配经验回放。 | 提供受控实验与记忆质量管理结论，补足失败模式和能力边界。 | 推荐收录（首次发现：2026-06-27-01；最近核查：2026-06-27） |
| [Agent Workflow Memory](https://arxiv.org/abs/2409.07429) | 2024-09-11；arXiv 预印本 | 方法；工作流记忆；跨任务/网站/领域 | 从轨迹归纳可复用工作流，在线或离线注入 Agent 记忆。 | 在 Mind2Web 与 WebArena 上有较大提升，并验证多种分布外泛化。 | 推荐收录（首次发现：2026-06-27-01；最近核查：2026-06-27） |
| [ExpeL: LLM Agents Are Experiential Learners](https://arxiv.org/abs/2308.10144) | 2023-08-20；AAAI-24 已接收 | 方法；经验与自然语言洞见；跨任务 | 自动收集经验、抽取可复用洞见并在后续推理中调用。 | 主题高度直接且有优秀会议接收，是经验学习的重要基线。 | 推荐收录（首次发现：2026-06-27-01；最近核查：2026-06-27） |
| [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366) | 2023-03-20；2023-10-10 更新；arXiv 预印本 | 方法；反思性情景记忆；跨回合 | 把任务反馈转成语言反思并保存在 episodic memory 中供后续尝试复用。 | 虽超出三年范围，但属于试错记忆与后续改进的必要基础工作。 | 推荐收录（首次发现：2026-06-27-01；最近核查：2026-06-27） |
| [Live-Evo: Online Evolution of Agentic Memory from Continuous Feedback](https://arxiv.org/abs/2602.02369) | 2026-02-02；arXiv 预印本 | 方法；经验库与元指南；在线反馈 | 用持续反馈强化有用经验并衰减误导或过时经验。 | 在线流和遗忘机制很相关，但证据场景仍较集中。 | 暂时观察（首次发现：2026-06-27-01；最近核查：2026-06-27） |
| [When Continual Learning Moves to Memory: A Study of Experience Reuse in LLM Agents](https://arxiv.org/abs/2604.27003) | 2026-04-29；arXiv 预印本；working in progress | 诊断；表示与检索组织；连续任务 | 分析前向迁移、遗忘和负迁移之间的权衡。 | 问题和实验有价值，但作者明确标注仍在进行中。 | 暂时观察（首次发现：2026-06-27-01；最近核查：2026-06-27） |
| [Infini Memory: Maintainable Topic Documents for Long-Term LLM Agent Memory](https://arxiv.org/abs/2606.10677) | 2026-06-09；arXiv 预印本 | 系统；主题文档记忆；跨会话 | 以可维护主题文档支持合并、事实修订和多步读取。 | 长期记忆结果积极，但经验复用和持续能力提升证据仍偏弱。 | 暂时观察（首次发现：2026-06-27-01；最近核查：2026-06-27） |
| [Evolving Agents in the Dark: Retrospective Harness Optimization via Self-Preference](https://arxiv.org/abs/2606.05922) | 2026-06-04；2026-06-10 更新；arXiv 预印本 | 方法；Harness、技能与工具；跨任务 | 从历史轨迹提取自验证和自一致性信号，以自偏好生成并筛选 Harness 更新。 | 无需外部标签，在软件工程、终端和知识工作基准上持续提升。 | 推荐收录（首次发现：2026-06-27-02；最近核查：2026-06-27） |
| [Self-Harness: Harnesses That Improve Themselves](https://arxiv.org/abs/2606.09498) | 2026-06-08；arXiv 预印本 | 方法；Harness 代码与指令；跨任务 | 从执行轨迹挖掘模型特定弱点，提出最小 Harness 修改并通过回归测试筛选。 | 三种不同模型的 held-out Terminal-Bench-2.0 表现均显著提高。 | 推荐收录（首次发现：2026-06-27-02；最近核查：2026-06-27） |
| [SkillHone: A Harness for Continual Agent Skill Evolution Through Persistent Decision History](https://arxiv.org/abs/2606.08671) | 2026-06-07；2026-06-23 更新；arXiv 预印本 | 方法与系统；技能及决策历史；跨会话 | 保存诊断、修改、证据、拒绝方案和结果，使后续 Agent 继承技能演化依据。 | 明确支持跨会话继续优化，并在研究和工具任务上报告稳定提升。 | 推荐收录（首次发现：2026-06-27-02；最近核查：2026-06-27） |
| [SkillOpt: Executive Strategy for Self-Evolving Agent Skills](https://arxiv.org/abs/2605.23904) | 2026-05-22；2026-05-25 更新；arXiv 预印本 | 方法；Skill 文档；跨模型与跨 Harness | 以有界编辑、拒绝缓冲和严格验证门控训练冻结 Agent 的外部 Skill 状态。 | 覆盖六个基准、七种模型和三种 Harness，并验证跨环境迁移。 | 推荐收录（首次发现：2026-06-27-02；最近核查：2026-06-27） |
| [SkillOS: Learning Skill Curation for Self-Evolving Agents](https://arxiv.org/abs/2605.06614) | 2026-05-07；arXiv 预印本 | 方法；SkillRepo；连续任务流 | 用强化学习训练技能整理器，根据累计经验更新冻结执行 Agent 的外部 SkillRepo。 | 直接学习长期技能整理策略，并报告跨模型和跨领域泛化。 | 推荐收录（首次发现：2026-06-27-02；最近核查：2026-06-27） |
| [Meta-Harness: End-to-End Optimization of Model Harnesses](https://arxiv.org/abs/2603.28052) | 2026-03-30；arXiv 预印本 | 方法；Harness 源码与上下文管理；跨模型 | 外循环 Agent 读取历史候选源码、轨迹和得分，持续搜索更优 Harness 代码。 | 覆盖分类、数学推理和 Agent 编程，说明完整 Harness 可自动工程化。 | 推荐收录（首次发现：2026-06-27-02；最近核查：2026-06-27） |
| [Gödel Agent: A Self-Referential Agent Framework for Recursive Self-Improvement](https://arxiv.org/abs/2410.04444) | 2024-10-06；ACL 2025 主会（arXiv 作者备注） | 方法；Agent 逻辑与代码；递归改进 | 在高层目标约束下修改自身逻辑和行为，不依赖固定人工优化例程。 | 主题直接，覆盖数学和复杂 Agent 任务，并具有主会发表证据。 | 推荐收录（首次发现：2026-06-27-02；最近核查：2026-06-27） |
| [Darwin Godel Machine: Open-Ended Evolution of Self-Improving Agents](https://arxiv.org/abs/2505.22954) | 2025-05-29；2026-03-12 更新；arXiv 预印本 | 方法；Agent 代码、工具与控制流；开放式演化 | 维护多样 Agent 档案，由 Agent 修改已有代码并通过编程基准验证后保留。 | SWE-bench 与 Polyglot 均大幅提升，展示代码级自修改和开放式搜索。 | 推荐收录（首次发现：2026-06-27-02；最近核查：2026-06-27） |
| [Automated Design of Agentic Systems](https://arxiv.org/abs/2408.08435) | 2024-08-15；2025-03-02 更新；arXiv 预印本 | 方法与框架；Agent 代码和工作流；跨领域 | 提出 ADAS，并以 Meta Agent Search 在不断增长的 Agent 档案上搜索新设计。 | 是自动 Agent 设计的框架性工作，并报告跨领域和跨模型迁移。 | 推荐收录（首次发现：2026-06-27-02；最近核查：2026-06-27） |
| [Voyager: An Open-Ended Embodied Agent with Large Language Models](https://arxiv.org/abs/2305.16291) | 2023-05-25；arXiv 预印本 | 系统；可执行技能库与自动课程；跨任务 | 持续生成、修正和存储可组合代码技能，并在新 Minecraft 世界检索复用。 | 略超出三年范围，但属于 Agent Skills 和开放式终身学习的必要基础工作。 | 推荐收录（首次发现：2026-06-27-02；最近核查：2026-06-27） |
| [Self-Taught Optimizer (STOP): Recursively Self-Improving Code Generation](https://arxiv.org/abs/2310.02304) | 2023-10-03；COLM 2024 会议论文（arXiv Comments） | 方法；脚手架程序；递归改进 | 用语言模型增强的 improver 改写自身代码，再优化下游程序。 | 发表质量和历史价值较高，但实验任务较少，尚非完整递归自我改进。 | 暂时观察（首次发现：2026-06-27-02；最近核查：2026-06-27） |
| [Language Agents as Optimizable Graphs](https://arxiv.org/abs/2402.16823) | 2024-02-26；ICML 2024（arXiv 作者备注） | 方法；Prompt 与 Agent 编排图；任务级优化 | 将 Agent 表示为计算图，并自动优化节点 Prompt 和图连接关系。 | 形式统一且会议质量较高，但持续跨任务积累机制不够明确。 | 暂时观察（首次发现：2026-06-27-02；最近核查：2026-06-27） |
| [GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning](https://arxiv.org/abs/2507.19457) | 2025-07-25；ICLR 2026 Oral（arXiv 作者备注） | 方法；Prompt 与复合 AI 系统；跨任务 | 从少量轨迹反思失败、提出 Prompt 更新，并用 Pareto 搜索组合互补经验。 | 发表质量和结果很强，但不一定形成部署后的持续 Agent 演化。 | 暂时观察（首次发现：2026-06-27-02；最近核查：2026-06-27） |
| [AFlow: Automating Agentic Workflow Generation](https://arxiv.org/abs/2410.10762) | 2024-10-14；2025-04-15 更新；arXiv 预印本 | 方法；代码化工作流；任务级优化 | 用蒙特卡洛树搜索、代码修改、树状经验和执行反馈迭代生成工作流。 | 与 Harness 优化直接相关，但主要证据是给定基准上的离线搜索。 | 暂时观察（首次发现：2026-06-27-02；最近核查：2026-06-27） |

`当前状态` 写“推荐收录”或“暂时观察”，并在同一单元格记录首次发现 Run ID 和最近核查日期。
