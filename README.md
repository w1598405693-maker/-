# 倪海厦研习

个人研习倪海厦相关公开资料的独立项目。目标仓库：[w1598405693-maker/-](https://github.com/w1598405693-maker/-)。

## 首批预览

包含项目规则、项目内技能入口、ChatGPT 项目指令和固定版本来源索引，按需检索外部公开资料。本次未导入完整上游知识库，不代表已完整学习或核验全部课程。

在支持仓库级技能的 Codex 环境中，从本仓库开始工作，再明确调用 `$nihaixia-study`。宿主可能需要重新发现文件；创建 GitHub 文件不会自动在 ChatGPT 全局注册技能。

在独立 ChatGPT 项目中使用 [项目指令](docs/PROJECT_INSTRUCTIONS.md)，并连接本仓库资料。文件与指令隔离不能替代账号记忆、连接和权限设置。

| 路径 | 用途 |
| --- | --- |
| `AGENTS.md` | 本仓库隔离和变更规则 |
| `.agents/skills/nihaixia-study/SKILL.md` | 明确调用的研习流程 |
| `.agents/skills/nihaixia-study/agents/openai.yaml` | 展示信息及禁止隐式调用配置 |
| `.agents/skills/nihaixia-study/references/sources.md` | 固定提交的来源索引 |
| `docs/PROJECT_INSTRUCTIONS.md` | ChatGPT 项目指令建议 |
| `docs/decisions/0001-project-isolation.md` | 隔离决定与适用边界 |

## 验收边界

- 回答区分原话、作者整理和 AI 归纳，附确切来源。
- 资料未取得、未核验或互相冲突时如实说明。
- 跨项目请求先核对范围，避免跨项目加载或写入。
- 排盘未完成程序接入前，不报告虚构结果。
- 修改先预览，再 PR，未经同意不合并。

上游版本、状态和使用条件见 [来源索引](.agents/skills/nihaixia-study/references/sources.md)。
