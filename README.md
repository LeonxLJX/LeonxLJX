# LeonxLJX · 刘鑫

**Agent 基础设施工程师** — 专注 MCP / Agent Harness / Eval 与会话可观测，TypeScript 为主，Rust 加分。

远程 · 开源贡献者 · 自由职业

---

## 正在做的事

给 AI coding agent 补上它们缺的那层基础设施——不是又一个「套壳 LLM」，而是让 agent 工程真正可维护、可观测、可记忆的底座：

- **长期记忆**：跨会话记住代码库的决策 / 约束 / API 事实
- **会话可观测**：把任意 agent 日志归一成事件流，算成本、找悬空调用
- **提示词工程**：把 prompt 当代码——版本化、类型化、可测试
- **项目规范**：给中文主流 UI 库写能让 agent 不再「跟组件库对着干」的 DESIGN.md

## 项目（各打一个垂直缺口，非套壳）

| 项目 | 定位 | 状态 |
|---|---|---|
| [agent-trace](https://github.com/LeonxLJX/agent-trace) | harness 中立会话可观测：双格式解析 + 成本估算 + 悬空调用检测 + 离线 viewer | ✅ 可用 |
| [codegraph-memory](https://github.com/LeonxLJX/codegraph-memory) | coding agent 本地代码记忆层，JSON + BM25-lite，零依赖 | ✅ 可用 |
| [prompt-forge](https://github.com/LeonxLJX/prompt-forge) | 提示词模板引擎：类型化变量 + total compiler + 24 内置 + CLI | ✅ 可用 |
| [design-specs-web](https://github.com/LeonxLJX/design-specs-web) | 6 个中文主流 UI 库 DESIGN.md 规范包 + compose CLI | ✅ 可用 |
| [web-engineer-skills](https://github.com/LeonxLJX/web-engineer-skills) | 12 个前端工程 Agent 技能库（SKILL.md） | ✅ 可用 |
| [dsh-mcp-market](https://github.com/LeonxLJX/dsh-mcp-market) | DeepSeek Harness × MCP 桥接：目录 + 安装器 | ✅ 可用 |

## 开源贡献

- **DeepSeek Harness**（`dsh-plugin` 生态）：MCP 集成
- **ant-design**：[#59199](https://github.com/ant-design/ant-design/pull/59199) class 组件回归守卫（AST 扫描接入 lint 链）
- **apache/hudi**：[#19832](https://github.com/apache/hudi/pull/19832) 持久化索引类型
- **langchainjs**：[#11518](https://github.com/langchain-ai/langchainjs/pull/11518)

## 技术栈

`TypeScript` · `Node.js` · `Vue 3` · `React / Next.js` · `PostgreSQL` · `Redis` · `Rust` · `MCP` · `RAG / LLM`

## 联系

- GitHub：[@LeonxLJX](https://github.com/LeonxLJX)
- Email：liuzhaoxing373@gmail.com
