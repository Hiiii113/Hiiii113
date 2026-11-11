<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=620&lines=Backend+engineer+building+AI+agents;Java+%C2%B7+Go+%C2%B7+MCP+%C2%B7+RAG;Tool+Calling+%C2%B7+Context+Compaction" alt="Typing SVG" />

**Java / Go 后端，方向是 AI Agent**：从零写一个编码 Agent，把模型能力接进真实业务，顺手修 upstream 的坑。

</div>

## 🔭 Focus

- **从零实现编码 Agent**：Go 单二进制 CLI，Anthropic / OpenAI-compatible 双协议后端，文件读写、精确编辑、正则搜索、Shell、网页读取全套工具
- **Agent 的边界处理**：权限确认、Plan Mode、上下文压缩、会话恢复，长任务不会一次就把窗口烧完
- **可扩展性**：MCP JSON-RPC 2.0 stdio 接入外部工具，另有项目记忆、Skills、子 Agent
- **Java 后端**：Spring Boot 业务与权限、WebSocket 实时同步、缓存与数据一致性
- **Spring AI 落地**：智能路由分发闲聊 / 摘要 / 检索，AI 自主调用工具读用户自己的笔记，向量语义检索可回溯到原文

## 🧩 Featured Projects

| 项目 | 说明 | 技术 |
| --- | --- | --- |
| [mini-claude-go](https://github.com/Hiiii113/mini-claude-go) | 用 Go 从头实现的命令行编码 Agent，Windows / Linux / macOS 单二进制运行，支持双协议后端与 MCP 工具扩展 | Go · MCP · Tool Calling · Agent Loop |
| [SmartNote](https://github.com/Hiiii113/SmartNote) | 智能笔记应用：文件夹式管理 + 多人实时编辑 + 好友与私聊 + AI 助手；后端负责权限、实时同步与 AI 编排 | Java 17 · Spring Boot · MyBatis-Plus · Spring AI · WebSocket |
| [NekoSportsWorldTool-Plus](https://github.com/Hiiii113/NekoSportsWorldTool-Plus) | 基于上游 v0.4.1 的缺陷修复分支：修正点位判定 payload、跑过未上报点位、Windows TLS 证书导致的登录失败 | Rust · 协议实现 · 单文件 GUI / CLI |

## 🌱 Open Source

- **[ChaosPainter-pjz/SiYuan_FeishuStyle#3](https://github.com/ChaosPainter-pjz/SiYuan_FeishuStyle/pull/3)** <sub>已合并</sub> — 修复浅色主题下的样式错位，让主题在 light mode 下可正常使用

## 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,go,spring,mysql,redis,docker,git,linux,rust&perline=9" alt="Tech stack" />
</p>

**Agent**：Tool Calling · MCP · Context Compaction · Skill　**后端**：Spring Boot · MyBatis-Plus · Sa-Token · WebSocket　**AI**：Spring AI · 向量检索 · 模型路由

## 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hiiii113/Hiiii113/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/Hiiii113/Hiiii113/output/github-snake.svg" alt="Contribution snake" />
</picture>
