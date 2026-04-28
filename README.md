# Agent Biz

## 项目是什么

`agent_biz` 是一个基于 Eino 的内部业务背景智能助手项目。  
目标是帮助研发/产运通过自然语言快速理解业务背景，并给出可追溯来源。

## 当前范围（V1）

V1 聚焦“业务背景解释”，优先解决：

1. 回答业务背景问题。
2. 给出答案依据来源。
3. 标注不确定点和资料缺口。

V1 暂不默认支持：

1. 自动执行外部查数操作。
2. 自动写回外部知识库。
3. 无来源前提下给出确定性业务结论。

## 目录约定

- 项目根目录：`/Users/zhouhuaifeng/Code/work/xunlei/ssp/agent_biz`
- 主要文档目录：`docs/`
- Eino 参考代码：`docs/eino/`
- 历史需求文档：`docs/rc_context/`

## 参考资料

官方文档：

- [CloudWeGo Eino Docs](https://www.cloudwego.io/docs/eino/)

本地仓库：

- `docs/eino/eino`
- `docs/eino/eino-ext`
- `docs/eino/eino-examples`

业务资料：

- `work_security_skills`（外部风控技能与知识库，默认只读）
- `docs/rc_context`（历史需求文档）
- `ssp` 代码仓库（实现线索和上下文补充）

## 文档导航

- 执行约束与协作规则：`AGENTS.md`
- 项目总览与边界：`README.md`（本文件）

## 协作原则

1. 小步迭代，保持改动可审阅。
2. 行为变化与文档更新尽量同步。
3. 需求冲突时，以最新用户指令为准。

