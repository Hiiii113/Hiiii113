<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=640&lines=Java+backend+%2B+agent+engineering;Tool+loop+%C2%B7+Docker+sandbox+%C2%B7+Memory;Agents+that+push+real+branches" alt="Typing SVG" />

**Java 后端 + Agent 工程**：把 Agent 做成项目成员——群里 @ 它，它在 Docker 沙箱里改完代码，把分支推回 GitHub。

</div>

## 🔭 Focus

- **群聊里的 Agent**：Agent 是项目成员，有项目内独立 ID、私有记忆和权限；只有被 @ 的消息才启动运行，多群、提及、回复、已读都在一个 Spring Boot 单体里
- **工具循环与子 Agent**：自研 harness 默认最多 30 轮，单步最多 4 个工具并行，可后台派生 8 个子 Agent，运行中能按消息取消
- **Docker 沙箱**：用户命令跑在临时容器里（2 核 / 4 GiB），空闲回收；项目数据目录持久化 memory、worktree 和 Git
- **三层记忆**：项目 `memory.md`、群记忆、Agent 私有记忆分开存，配上跨群历史检索、Skill 与附件
- **交付闭环**：团队装一次 GitHub App，Agent 就能读 PR / Issue、拉代码、推分支（不自动建 PR）；SSE 断点续传 + WebSocket 推实时事件

## 🧩 Featured Projects

| 项目 | 说明 | 技术 |
| --- | --- | --- |
| [qgents](https://github.com/Hiiii113/qgents) | 团队群聊里的 Agent 工作台：@ 一个 Agent，它在 Docker 沙箱里执行命令、改代码，把分支推回 GitHub | Java 21 · Spring Boot · Spring AI · docker-java |
| [qgents-frontend](https://github.com/Hiiii113/qgents-frontend) | qgents 的 Web 端：群聊、项目设置、Skill / Memory 与仓库管理；后端由相邻的 qgents 仓库提供 | React 19 · TypeScript · Ant Design 6 |
| [mini-claude-go](https://github.com/Hiiii113/mini-claude-go) | 用 Go 从零写的命令行编码 Agent：Anthropic / OpenAI 兼容双协议、权限确认、Plan Mode、上下文压缩、MCP 扩展 | Go · MCP · Tool Calling |
| [SmartNote](https://github.com/Hiiii113/SmartNote) | 智能笔记：文件夹管理 + 多人实时编辑 + 好友私聊 + AI 助手，后端负责权限、实时同步与 AI 编排 | Java 17 · Spring Boot · MyBatis-Plus · WebSocket |

## 🌱 Recent PR

- **[qgents#9](https://github.com/Hiiii113/qgents/pull/9)** <sub>已合并</sub> — 项目内多 Agent、群记忆与群聊审批：282 个文件，测试用例从 501 涨到 673

## 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,mysql,redis,docker,go,git,linux&perline=8" alt="Tech stack" />
</p>

**Agent**：Sub-Agent · MCP · Memory · Skill　**后端**：Java 21 · Spring Boot · MyBatis-Plus · MySQL · Redis

## 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hiiii113/Hiiii113/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/Hiiii113/Hiiii113/output/github-snake.svg" alt="Contribution snake" />
</picture>
