<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=620&lines=Java+backend+%2B+AI+agents;Agent+Harness+%C2%B7+Tool+Loop+%C2%B7+Sandbox;Java+%C2%B7+Go+%C2%B7+Spring+AI+%C2%B7+MCP" alt="Typing SVG" />

**Java 后端 + AI Agent**：做团队协作式的云端 Agent 工作台——自研工具循环、Docker 沙箱里跑命令、多层记忆贯穿群聊与项目。

</div>

## 🔭 Focus

- **Agent Harness**：自研工具循环，默认 30 轮、单步并行多个工具，可后台派生子 Agent，运行中可取消
- **沙箱执行**：用户命令在临时 Docker 容器内执行，带核数 / 内存配额与空闲回收，项目数据卷持久化工作区与 Git
- **多层记忆与知识**：项目共享记忆、群记忆、Agent 私有记忆分开存，配合群聊历史检索、Skill 与附件
- **编码 Agent（Go）**：从零写命令行 Agent，Anthropic / OpenAI-compatible 双协议后端，权限确认、Plan Mode、上下文压缩、MCP 工具扩展
- **Java 后端**：Spring Boot 单体同时承载 IM、Agent 调度与沙箱管理，MySQL / Redis 支撑状态，SSE 续传与 WebSocket 实时推送

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

**Agent**：Tool Loop · Sub-Agent · MCP · Memory · Skill　**后端**：Java 21 · Spring Boot · MyBatis-Plus · MySQL · Redis　**AI**：Spring AI · DeepSeek / OpenAI 兼容 · 向量检索

## 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Hiiii113/Hiiii113/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/Hiiii113/Hiiii113/output/github-snake.svg" alt="Contribution snake" />
</picture>
