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

`当前状态` 写“推荐收录”或“暂时观察”，并在同一单元格记录首次发现 Run ID 和最近核查日期。
