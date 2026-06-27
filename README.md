# Self-Evolving Agent Literature Watch

用于持续发现、筛选、去重和跟踪 Self-Evolving LLM Agent 及相邻研究方向的论文。

每次完整运行都会留下不可变的 Markdown 报告，同时更新当前候选池、历史筛选记录和运行状态。

## 快速开始

在支持仓库读写的 Agent 中打开本仓库，复制下面的提示词即可执行一次完整运行：

```text
在当前仓库执行一次完整的论文监控运行，先读取 AGENTS.md。
```

首次运行没有既有增量起点时，会初始化首份运行记录，并选择一个有限范围执行历史补漏；后续运行通常同时执行增量监控和一个有限历史补漏任务。需要指定补漏方向、仅检查重要更新或只讨论方案时，参见 [`PROMPTS.md`](PROMPTS.md)。

## 仓库结构

| 文件或目录 | 作用 |
| --- | --- |
| [`AGENTS.md`](AGENTS.md) | Agent 进入仓库后的任务入口和执行要求 |
| [`GUIDE.md`](GUIDE.md) | 论文监控目标、检索方法、筛选规则和完整运行协议 |
| [`PROMPTS.md`](PROMPTS.md) | 可直接复制的日常运行提示词和使用示例 |
| [`STATE.md`](STATE.md) | 当前执行进度、增量监控截止日期和下一轮建议 |
| [`candidates.md`](candidates.md) | 去重后的有效候选总表及其当前状态。 避免重复监控浪费时间。 |
| [`SCREENING_LOG.md`](SCREENING_LOG.md) | 用于记录已完成判断但未进入候选池的论文及其理由。 避免重复监控浪费时间。 |
| [`queries.md`](queries.md) | 静态检索方向、关键词池和建议轮换顺序。可根据实际情况优化，相当于指明研究方向。 |
| [`RUN_REPORT_TEMPLATE.md`](RUN_REPORT_TEMPLATE.md) | 单次运行报告的规范模板 |
| [`runs/README.md`](runs/README.md) | 历次运行报告的索引入口 |

## 核心原则

仓库同时维护三类信息：

1. **规则**：`GUIDE.md` 定义应该怎么运行；
2. **状态**：`STATE.md`、`candidates.md` 和 `SCREENING_LOG.md` 记录目前做到哪里；
3. **证据**：`runs/` 保存每一次实际执行结果。

报告回答“本次发现了什么”，候选总表回答“目前有哪些候选论文以及它们处于什么状态”。

## 一次完整运行

一次完整运行应当：

1. 读取规则、状态、候选池、历史筛选记录和检索方向；
2. 执行增量监控，并选择一个有限范围的历史补漏任务；
3. 在 `runs/YYYY/` 中新增本次报告；
4. 更新 `candidates.md`、`SCREENING_LOG.md` 和 `STATE.md`，并将本次运行追加到 `runs/README.md` 的运行索引。
5. 检查去重、状态和统计数字是否一致。

具体要求以 [`GUIDE.md`](GUIDE.md) 中的“单次完整运行事务”为准。
