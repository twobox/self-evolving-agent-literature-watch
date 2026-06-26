# 历史筛选记录

本文件记录已经完成实质判断、但未进入有效候选池且未来可能再次出现在检索结果中的论文及其判断理由，供后续运行复用结论、避免重复筛选；只保存具有重复出现或重新评估价值的条目，不记录普通搜索噪声。

“当前判断”建议使用：`排除`、`暂缓` 或 `待重新评估`。

| Paper ID | 论文标题 | 当前判断 | 判断说明 | 首次检查 | 最近核查 | 重新评估条件 |
| -------- | -------- | -------- | -------- | -------- | -------- | ------------ |
| arXiv:2504.19413 | Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory | 暂缓 | 主要评测多会话对话事实与个性化记忆；本轮未发现任务型 Agent 经验复用或持续能力提升的充分证据。 | 2026-06-26 | 2026-06-26 | 新版本增加连续任务流、工具执行或跨任务能力提升实验。 |
| arXiv:2410.10813 | LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory | 暂缓 | 重点是聊天助手的信息提取、时间推理和知识更新，不直接评测 Agent 从任务经验中学习。 | 2026-06-26 | 2026-06-26 | 被扩展为任务执行型 Agent 的经验积累或测试时学习评测。 |
| arXiv:2402.17753 | Evaluating Very Long-Term Conversational Memory of LLM Agents | 暂缓 | LoCoMo 主要评测超长对话记忆和生成，与本轮任务经验复用范围距离较远。 | 2026-06-26 | 2026-06-26 | 出现基于该基准的自演化记忆方法或任务型 Agent 扩展。 |
| arXiv:2502.06975 | Position: Episodic Memory is the Missing Piece for Long-Term LLM Agents | 排除 | 立场与路线图论文，没有新的可执行记忆机制和能力提升实验。 | 2026-06-26 | 2026-06-26 | 作者发布实现该路线图的实证方法论文。 |
| arXiv:2504.15965 | From Human Memory to AI Memory: A Survey on Memory Mechanisms in the Era of LLMs | 排除 | 综合范围过宽，未聚焦 Agent 的经验复用闭环，本轮已有更贴近主题的分类论文。 | 2026-06-26 | 2026-06-26 | 形成专门面向 Self-Evolving Agent 的更新版本或实证框架。 |
| arXiv:2505.03434 | Procedural Memory Is Not All You Need: Bridging Cognitive Gaps in LLM-Based Agents | 排除 | 以概念论证为主，缺少可验证的程序性记忆更新与复用系统。 | 2026-06-26 | 2026-06-26 | 后续版本加入完整系统、任务评测与持续改进证据。 |
| arXiv:2512.12686 | Memoria: A Scalable Agentic Memory Framework for Personalized Conversational AI | 暂缓 | 主要面向会话连续性和用户建模，当前实验不足以支撑任务型 Agent 的持续改进结论。 | 2026-06-26 | 2026-06-26 | 增加任务执行、跨任务迁移或经验复用对照实验。 |
| arXiv:2605.14498 | GroupMemBench: Benchmarking LLM Agent Memory in Multi-Party Conversations | 暂缓 | 聚焦多人会话中的说话者信念和群体记忆，不属于本轮任务经验复用初始范围。 | 2026-06-26 | 2026-06-26 | 被用于评测协作 Agent 的持续学习或跨会话技能积累。 |
| arXiv:2505.16348 | Embodied Agents Meet Personalization: Exploring Memory Utilization for Personalized Assistance | 暂缓 | 评测个性化知识调用，但没有提出经验积累、更新或跨任务复用机制。 | 2026-06-26 | 2026-06-26 | 后续工作加入在线记忆更新和跨任务性能提升机制。 |
