# Self-Evolving Agent Literature Watch

用于发现与 Self-Evolving LLM Agent 相关、值得后续阅读的论文，并维护候选论文的基本信息。

## 运行方式

仓库提供三个独立动作：

1. **近期论文监控**：发现最近公开的相关论文，记录公开或发表状态以及作者机构；
2. **历史优质论文搜索**：围绕指定方向补充历史论文，记录发表和引用情况；
3. **已有候选信息更新**：核查 `candidates.md` 中已有论文，更新公开和发表信息。

一次运行只执行其中一个动作。

## 快速开始

```text
请在当前仓库执行一次近期论文监控。先读取 AGENTS.md。
```

```text
请在当前仓库搜索 [研究方向] 的历史优质论文。先读取 AGENTS.md。
```

```text
请在当前仓库更新已有候选论文的信息。先读取 AGENTS.md。
```

更多示例见 [`PROMPTS.md`](PROMPTS.md)。

## 仓库结构

| 文件或目录 | 作用 |
| --- | --- |
| [`AGENTS.md`](AGENTS.md) | Agent 任务入口 |
| [`GUIDE.md`](GUIDE.md) | 运行规则 |
| [`PROMPTS.md`](PROMPTS.md) | 可复制提示词 |
| [`STATE.md`](STATE.md) | 各动作的运行记录 |
| [`candidates.md`](candidates.md) | 候选论文总表 |
| [`queries.md`](queries.md) | 检索方向与关键词 |
| [`RUN_REPORT_TEMPLATE.md`](RUN_REPORT_TEMPLATE.md) | 运行报告模板 |
| [`runs/README.md`](runs/README.md) | 运行报告索引 |
