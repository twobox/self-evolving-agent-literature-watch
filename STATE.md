---
state_schema_version: 1
last_updated: 2026-06-26
monitoring_status: not_started
last_successful_run_id: null
last_successful_run_date: null
incremental_covered_through: null
---

# Monitoring State

本文件是当前执行进度的唯一状态来源。实际已覆盖方向、最近运行和下一次历史补漏建议等动态状态统一在此维护；`queries.md` 只保存静态检索空间与建议轮换顺序。运行时必须保留以下标题、字段名和表格列，只更新字段值或新增规范表格行。

## 1. 当前执行状态

| 字段 | 当前值 |
| --- | --- |
| 状态结构版本 | `1` |
| 监控状态 | `not_started` |
| 基线状态 | `not_started` |
| 最近一次成功运行 ID | 无 |
| 最近一次成功运行日期 | 无 |
| 增量覆盖截止日期 | 无 |
| 当前指南版本 | `1.1` |
| 最近更新时间 | `2026-06-26` |

监控状态使用：`not_started`、`baseline_in_progress`、`active` 或 `paused`。基线状态使用：`not_started`、`in_progress` 或 `completed`。

## 2. 基线与历史补漏覆盖

| 覆盖方向 | 覆盖状态 | 最近运行 ID | 说明 |
| --- | --- | --- | --- |
| Agent Memory 与 Experience Reuse | `not_started` | 无 | 首次基线优先 |
| Harness 与 Agent Skills | `not_started` | 无 | 首次基线优先 |
| Agent RL 与参数更新 | `not_started` | 无 | 后续补漏 |
| 轨迹、工作流与技能复用 | `not_started` | 无 | 后续补漏 |
| 合成任务与训练环境 | `not_started` | 无 | 后续补漏 |
| 诊断、边界与评测 | `not_started` | 无 | 后续补漏 |

覆盖状态使用：`not_started`、`partial` 或 `completed`。本表记录已经实际检查的覆盖进度；可用检索词和静态轮换顺序由 `queries.md` 维护。

## 3. 待跟踪论文

| Paper ID | 待跟踪事项 | 重新核查条件 | 加入运行 ID |
| --- | --- | --- | --- |

当前无待跟踪论文。

## 4. 下一次运行建议

| 字段 | 当前值 |
| --- | --- |
| 建议运行模式 | `baseline` |
| 建议增量起始日期 | 不适用，尚未完成首次运行 |
| 建议历史补漏方向 | Agent Memory 与 Experience Reuse |
| 优先待跟踪论文 | 无 |
| 备注 | 首次完整运行应建立初始候选池、首份运行报告和运行索引记录 |

## 5. 更新规则

- 每次完整运行结束后，同时更新 YAML 头部与“当前执行状态”中的对应值，两处必须一致。
- “最近一次成功运行 ID”必须与 `runs/README.md` 中的 Run ID 及实际报告文件名一致。
- 只有完整运行实际覆盖到的日期，才能写入“增量覆盖截止日期”。
- 基线或补漏只完成部分范围时，将对应覆盖状态写为 `partial`，不得直接标记为 `completed`。
- 实际覆盖进度和下一次历史补漏建议只在本文件更新，不得把 `queries.md` 改造成运行状态文件。
- 没有待跟踪论文时保留空表和“当前无待跟踪论文”，不要删除本节。
- 不得另建表达相同含义的状态段落、表格或状态文件。
