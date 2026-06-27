# 候选论文总表

| 序号 | 论文标题 | 一句话介绍 | 首次公开或发表状态 | 作者机构情况 | 引用 | 用户备注 |
| :--: | --- | --- | --- | --- | --- | --- |
| 1 | [SkillOS: Learning Skill Curation for Self-Evolving Agents](https://arxiv.org/abs/2605.06614) | 通过强化学习训练独立技能策展器，使其依据历史轨迹持续插入、更新和删除 SkillRepo 中的技能，并在不同执行器与任务上实现迁移。 | 2026-05-07 首次公开于 arXiv | Google Cloud AI Research；UIUC；MIT |  |  |
| 2 | [SkillMaster: Toward Autonomous Skill Mastery in LLM Agents](https://arxiv.org/abs/2605.08693) | 通过轨迹驱动的技能审查、反事实效用评估和 DualAdv-GRPO，联合学习任务执行与技能创建、修订和选择。 | 2026-05-09 首次公开于 arXiv（2026-05-12 更新） | 公开摘要页未列明 |  |  |
| 3 | [EvolveMem: Self-Evolving Memory Architecture via AutoResearch for LLM Agents](https://arxiv.org/abs/2605.13941) | 将记忆检索配置暴露为可优化动作空间，由诊断与元分析模块根据失败日志自动演化检索架构并在退化时回滚。 | 2026-05-13 首次公开于 arXiv | 公开摘要页未列明 |  |  |
| 4 | [SkillOpt: Executive Strategy for Self-Evolving Agent Skills](https://arxiv.org/abs/2605.23904) | 把 Agent 技能文档视为冻结模型的外部可训练状态，用受限文本编辑、验证门控和拒绝编辑记忆稳定优化跨 Harness 技能。 | 2026-05-22 首次公开于 arXiv（2026-05-25 更新） | Microsoft；上海交通大学；同济大学；复旦大学 |  |  |
| 5 | [MUSE-Autoskill: Self-Evolving Agents via Skill Creation, Memory, Management, and Evaluation](https://arxiv.org/abs/2605.27366) | 以创建、记忆、管理、评测和精炼的统一生命周期维护可复用技能，并用技能级记忆积累跨任务经验。 | 2026-05-26 首次公开于 arXiv | 字节跳动；Rochester Institute of Technology |  |  |
| 6 | [SkillRevise: Improving LLM-Authored Agent Skills via Trace-Conditioned Skill Revision](https://arxiv.org/abs/2606.01139) | 从执行轨迹诊断初始技能缺陷，检索通用修复原则并通过重新执行与验证门控迭代保留更有效的技能版本。 | 2026-05-31 首次公开于 arXiv（2026-06-17 更新至 v3） | 公开摘要页未列明 |  |  |
| 7 | [SkillAdaptor: Self-Adapting Skills for LLM Agents from Trajectories](https://arxiv.org/abs/2606.01311) | 在失败轨迹中定位首个可操作错误步骤并归因到具体技能，以接受检查约束训练免更新，实现更稳定的局部技能维护。 | 2026-05-31 首次公开于 arXiv（Work in progress） | 公开摘要页未列明 |  |  |
| 8 | [Agent Memory: Characterization and System Implications of Stateful Long-Horizon Workloads](https://arxiv.org/abs/2606.06448) | 从系统视角刻画长期有状态 Agent 记忆的构建、检索与生成成本，并总结面向新鲜度、延迟和规模化管理的设计建议。 | 2026-06-04 首次公开于 arXiv | 公开摘要页未列明 |  |  |
| 9 | [Bayesian-Agent: Posterior-Guided Skill Evolution for LLM Agent Harnesses](https://arxiv.org/abs/2606.08348) | 把技能与 SOP 作为带不确定性的假设，基于验证轨迹维护后验并触发补丁、拆分、压缩、退役或探索等可审计操作。 | 2026-06-06 首次公开于 arXiv | IDEA Research；香港科技大学（广州）；DataArcTech |  |  |
| 10 | [Are We Ready For An Agent-Native Memory System?](https://arxiv.org/abs/2606.24775) | 从数据管理视角拆解 Agent 记忆的存储、抽取、检索路由和维护模块，比较动态更新下的效果、成本与稳定性。 | 2026-06-23 首次公开于 arXiv | 公开摘要页未列明 |  |  |
| 11 | [Forget to Improve: On-Device LLM-Agent Continual Learning via Budget-Curated Memory](https://arxiv.org/abs/2606.25115) | 以单位字节净价值统一决定经验记忆的保留、共享和信任，在受限设备上兼顾持续学习、资源预算与抗投毒。 | 2026-06-23 首次公开于 arXiv | 公开摘要页未列明 |  |  |

## 填写规则

- 论文标题使用完整标题，并尽量链接到论文页面；
- 一句话介绍根据标题和摘要概括；
- 首次公开或发表状态记录公开或正式发表信息，例如“2026-05-12 首次公开于 arXiv”或“ICML 2026”；
- 作者机构使用简短名称，例如“清华大学；腾讯”；
- 引用填写检索时查到的数值，未查到则留空；按单一可用来源记录即可，后续是否刷新由具体任务决定；
- 用户备注保持原样；
- 同一论文只保留一条记录，按规范化标题去重。
