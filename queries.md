# 检索方向与关键词池

本文件维护可轮换的检索空间。每次运行应结合 `STATE.md` 选择若干增量查询，并指定一个有限范围的历史补漏方向。

## 直接主题

- self-evolving agent
- self-improving agent
- agent learning from experience
- experiential learning agent
- continually improving language agent

## 记忆与经验

- agent memory update
- experience replay language agent
- reasoning memory agent
- procedural memory agent
- experience reuse agent
- long-term agent memory learning

## 上下文、Prompt 与 Harness

- self-improving harness
- harness optimization LLM agent
- prompt evolution agent
- context optimization agent
- system prompt self-improvement

## 轨迹、工作流与技能

- trajectory refinement agent
- reusable agent trajectories
- workflow memory agent
- agent skill evolution
- skill library language agent

## 强化学习与参数更新

- agent reinforcement learning from experience
- cross-task agent reinforcement learning
- continual learning language agent
- test-time learning agent
- agent weight update from feedback

## 合成任务与环境

- synthetic task generation agent learning
- curriculum generation language agent
- environment generation for agents
- self-generated training tasks agent

## 诊断与评测

- self-improving agent benchmark
- agent memory benchmark
- continual agent evaluation
- agent adaptation boundary
- agent learning diagnosis

## 建议轮换顺序

本节只提供静态的覆盖顺序建议，不记录实际执行状态。已覆盖方向、最近运行和下一次历史补漏建议统一由 `STATE.md` 维护；每次运行实际使用的查询、来源和时间范围写入对应运行报告。

| 顺序 | 方向 | 建议用途 |
| ---: | --- | --- |
| 1 | Agent Memory 与 Experience Reuse | 首次基线优先 |
| 2 | Harness 与 Agent Skills | 首次基线优先 |
| 3 | Agent RL 与参数更新 | 后续基线或历史补漏 |
| 4 | 轨迹、工作流与技能复用 | 后续基线或历史补漏 |
| 5 | 合成任务与训练环境 | 后续基线或历史补漏 |
| 6 | 诊断、边界与评测 | 后续基线或历史补漏 |

Agent 应以 `STATE.md` 中的实际覆盖情况和下一次运行建议为准，在必要时调整上述顺序。除非检索空间本身发生变化，完整运行不需要修改本文件。
