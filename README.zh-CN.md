<p align="center">
  <img src="./assets/profile-banner.svg" alt="Aolinge profile banner" width="100%" />
</p>

<h1 align="center">Aolinge</h1>

<p align="center">
  <a href="https://aolingge.dev"><img src="https://img.shields.io/badge/Website-aolingge.dev-0D6B72?style=flat-square&logo=firefoxbrowser&logoColor=white" alt="Website" /></a>
  <a href="https://github.com/aolingge"><img src="https://img.shields.io/badge/GitHub-aolingge-151515?style=flat-square&logo=github" alt="GitHub profile" /></a>
  <a href="mailto:1930668092@qq.com"><img src="https://img.shields.io/badge/Email-1930668092%40qq.com-D94A38?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <b>重庆大学计算机科学学生</b><br />
  关注 AI Agent 仓库可靠性、MCP 安全和可重复的软件交付流程。
</p>

<p align="center">
  <a href="README.md">English</a> | 简体中文
</p>

---

## 关注方向

我会把容易失控的一次性开发流程整理成可以重复运行、容易审查、方便交付的小工具。目前主要做三类事情：

中心站：[aolingge.dev](https://aolingge.dev) · 项目页：[aolingge.dev/projects](https://aolingge.dev/projects/) · 博客 RSS：[blog.aolingge.dev/feed](https://blog.aolingge.dev/feed/)

| 方向 | 我在做什么 |
| --- | --- |
| AI Agent 仓库可靠性 | 检查仓库指令、secret、CI、MCP 配置、运行 trace 和发布前风险的 CLI 工具。 |
| 本地自动化 | 面向 Windows 优先开发、部署检查和长任务 Agent 循环的脚本与工作流工具包。 |
| 后端与交付实践 | Java / Spring Boot 项目、部署记录、作品集和可验证的交付材料。 |

## 从这里开始

| 项目 | 适合做什么 | 第一条命令 |
| --- | --- | --- |
| [agent-secret-guard](https://github.com/aolingge/agent-secret-guard) | 快速扫描 AI Agent 仓库、MCP 配置、浏览器 profile 路径和 GitHub Actions 权限风险。 | `npx agent-secret-guard scan . --fail-on high` |
| [mcp-config-doctor](https://github.com/aolingge/mcp-config-doctor) | 在 AI 客户端连接失败前检查 MCP 配置。 | `npx mcp-config-doctor --config mcp.json` |
| [agent-reliability-kit](https://github.com/aolingge/agent-reliability-kit) | 给 AI Agent 仓库生成 readiness、README、CI、secret、MCP、n8n 和发布风险报告。 | `npx agent-reliability-kit scan .` |
| [repo-release-proof](https://github.com/aolingge/repo-release-proof) | 检查 release note 是否说明了改动、验证方式和发布位置。 | `npx github:aolingge/repo-release-proof --path RELEASE.md` |

## 作品集

| 项目 | 价值 |
| --- | --- |
| [agent-symphony-kit](https://github.com/aolingge/agent-symphony-kit) | 为 coding agent 提供本地任务文件、预检、验证报告和 workflow contract。 |
| [agent-run-trace-pack](https://github.com/aolingge/agent-run-trace-pack) | 记录 Agent 或 shell 运行过程，生成脱敏、可审查的 trace。 |
| [open-source-portfolio](https://github.com/aolingge/open-source-portfolio) | 一个以项目证据、部署能力和服务清晰度为核心的 GitHub Pages 作品集模板。 |
| [student-deploy-kit](https://github.com/aolingge/student-deploy-kit) | 面向学生的部署材料：Nginx、Spring Boot、前端、Docker、VPS 安全和故障排查。 |
| [vps-deploy-doctor](https://github.com/aolingge/vps-deploy-doctor) | 只读 VPS 诊断工具，检查 Nginx、systemd、端口、Docker、防火墙、磁盘、内存和日志。 |

## 可合作事项

我优先接少量公开或可分享仓库的发布前检查，范围主要是 AI Agent、MCP、GitHub Actions 和本地自动化。

| 服务 | 交付内容 |
| --- | --- |
| AI Agent Repo Safety Audit | 24 小时内给一份 Markdown 风险摘要，覆盖 agent instructions、MCP args、本地凭据路径、浏览器 profile、CI 权限和可执行修复建议。 |
| Fix PR | 审计后提交一个范围明确的修复 PR，把高风险示例改成更安全的默认配置。 |
| 本地自动化加固 | 在公开发布或交付前，检查仓库文档、workflow 和脚本里的安全边界。 |

可以通过邮箱或 GitHub 发送公开仓库链接。不要发送生产密钥、Cookie、私钥或真实可用凭据。

## 技术栈

TypeScript、JavaScript、Node.js、Python、Java、Spring Boot、GitHub Actions、PowerShell。

## 做事方式

- 第一条命令要简单，默认值要清楚，输出要能直接行动。
- 报告默认本地优先，谨慎处理 secret、浏览器 profile 和账号材料。
- 文档是产品的一部分，不是最后补上的说明。
- 优先做小而透明、可以组合进更大工作流的工具。

---

<p align="center">
  <b>Clean workflows. Local-first safety. Reusable delivery.</b><br />
  <sub>重庆 · 重庆大学 · 开源笔记、工具和实验</sub>
</p>
