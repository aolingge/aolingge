<p align="center">
  <img src="./assets/profile-banner.svg" alt="Aolinge profile banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/aolingge"><img src="https://img.shields.io/badge/GitHub-aolingge-151515?style=flat-square&logo=github" alt="GitHub profile" /></a>
  <a href="https://blog.aolingge.dev"><img src="https://img.shields.io/badge/Blog-aolingge.dev-21A179?style=flat-square&logo=rss&logoColor=white" alt="Blog" /></a>
  <a href="mailto:1930668092@qq.com"><img src="https://img.shields.io/badge/Email-1930668092%40qq.com-D94A38?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <b>重庆大学计算机科学学生</b><br />
  我会把混乱的开发、部署和自动化流程整理成可复用的小工具。
</p>

<p align="center">
  语言： <a href="README.md">English</a> | 简体中文
</p>

---

## 你好，我是 Aolinge

我关注的是把一次性的手工流程变成可以重复运行的工具：清晰的 CLI、实用的后端服务、发布清单，以及能帮助下一个人少踩坑的文档。

现在主要做三类事情：

| 方向 | 我在做什么 |
| --- | --- |
| Agent 安全 | 面向 AI 编程 Agent、MCP 配置和本地自动化仓库的扫描器与安全护栏。 |
| 后端实践 | Java / Spring Boot 服务，强调清晰结构、API 设计和交付记录。 |
| 个人系统 | 本地优先的学习、调研、发布、备份和写作工作流。 |

## 重点项目

<p>
  <b>最新：</b>
  <a href="https://github.com/aolingge/mcp-config-doctor"><b>mcp-config-doctor</b></a>
  · 面向 Claude Desktop、Cursor、Codex 和 Agent 工作流的本地 MCP 配置体检工具。
  <br />
  <code>npx github:aolingge/mcp-config-doctor --config mcp.json</code>
  <br />
  <a href="https://github.com/aolingge/agents-md-doctor"><b>agents-md-doctor</b></a>
  · 面向 AI 编程 Agent 的 AGENTS.md 准备度检查工具。
  <br />
  <code>npx github:aolingge/agents-md-doctor --path AGENTS.md</code>
  <br />
  <a href="https://github.com/aolingge/prompt-yaml-lint"><b>prompt-yaml-lint</b></a>
  · 面向 .prompt.yml 的 Prompt-as-code 质量检查工具。
  <br />
  <code>npx github:aolingge/prompt-yaml-lint review.prompt.yml</code>
</p>

<details open>
<summary><b>AI Agent Mini Tools</b></summary>
<br />

| 工具 | 检查内容 |
| --- | --- |
| [agent-context-budget](https://github.com/aolingge/agent-context-budget) | Agent 上下文体积和仓库说明质量 |
| [agent-env-redactor](https://github.com/aolingge/agent-env-redactor) | Agent 报告和配置片段里的疑似密钥 |
| [mcp-readme-score](https://github.com/aolingge/mcp-readme-score) | MCP README 的安装、配置、权限和安全说明 |
| [skill-md-lint](https://github.com/aolingge/skill-md-lint) | AI Agent `SKILL.md` 的触发、输入、输出和安全边界 |
| [agentignore-check](https://github.com/aolingge/agentignore-check) | `.agentignore` 是否屏蔽私有文件和噪声文件 |
| [repo-context-pack](https://github.com/aolingge/repo-context-pack) | 面向编程 Agent 的仓库上下文包 |
| [agent-ci-doctor](https://github.com/aolingge/agent-ci-doctor) | Agent 收尾前可运行的 CI 命令 |
| [mcp-tool-name-lint](https://github.com/aolingge/mcp-tool-name-lint) | 含糊或高风险 MCP tool 名称 |
| [agent-runbook-check](https://github.com/aolingge/agent-runbook-check) | 排障、验证、回滚和汇报 runbook 覆盖度 |
| [prompt-eval-seed](https://github.com/aolingge/prompt-eval-seed) | Prompt eval 种子的输入、预期、边界和安全说明 |
| [agent-pr-brief](https://github.com/aolingge/agent-pr-brief) | 面向 AI code review 的 PR 说明检查 |
| [mcp-env-template-check](https://github.com/aolingge/mcp-env-template-check) | MCP `.env.example` 完整度和真实 token 风险 |
| [prompt-injection-smoke](https://github.com/aolingge/prompt-injection-smoke) | Agent 工作流里的 prompt injection 冒烟检查 |
| [agent-permission-audit](https://github.com/aolingge/agent-permission-audit) | 文件、shell、浏览器、网络和密钥权限边界 |
| [readme-demo-link-check](https://github.com/aolingge/readme-demo-link-check) | README demo、快速开始、截图和镜像链接 |
| [agent-log-triage](https://github.com/aolingge/agent-log-triage) | AI Agent 失败日志里的可执行排障信号 |
| [repo-release-proof](https://github.com/aolingge/repo-release-proof) | release note 的改动、验证、版本和镜像证明 |
| [agent-task-scope](https://github.com/aolingge/agent-task-scope) | 任务说明里的范围、验收标准、约束和验证 |
| [mcp-manifest-lint](https://github.com/aolingge/mcp-manifest-lint) | MCP manifest 的名称、传输、目标和权限 |
| [ai-changelog-guard](https://github.com/aolingge/ai-changelog-guard) | AI 辅助 changelog 的验证和兼容性说明 |
| [agent-windows-path-doctor](https://github.com/aolingge/agent-windows-path-doctor) | Windows/WSL 路径、引号和跨平台命令风险 |
| [agent-shell-safety-check](https://github.com/aolingge/agent-shell-safety-check) | shell 命令范围、验证和危险操作边界 |
| [mcp-permission-matrix](https://github.com/aolingge/mcp-permission-matrix) | MCP 工具、权限、数据范围和风险矩阵 |
| [prompt-regression-report](https://github.com/aolingge/prompt-regression-report) | prompt 回归报告里的输入、期望、实际输出和结论 |
| [repo-agent-health](https://github.com/aolingge/repo-agent-health) | 仓库是否具备 AI Agent 接手所需健康信号 |
| [agent-tool-risk-score](https://github.com/aolingge/agent-tool-risk-score) | Agent 工具清单里的文件、shell、网络和密钥风险 |
| [mcp-server-smoke-test](https://github.com/aolingge/mcp-server-smoke-test) | MCP server 启动、工具列表、样例调用和失败处理 |
| [readme-install-replay](https://github.com/aolingge/readme-install-replay) | README 安装步骤、前置条件、命令和验证输出 |
| [ci-command-harvest](https://github.com/aolingge/ci-command-harvest) | 仓库说明里的测试、构建、lint 和验证命令 |
| [agent-memory-audit](https://github.com/aolingge/agent-memory-audit) | AI 记忆/规则文件的触发条件、行为、例外和密钥边界 |
| [release-mirror-check](https://github.com/aolingge/release-mirror-check) | GitHub/Gitee/tag/release/验证记录是否完整 |
| [prompt-fixture-pack](https://github.com/aolingge/prompt-fixture-pack) | prompt fixture 是否覆盖正常、边界、失败和期望输出 |
| [agent-context-diff](https://github.com/aolingge/agent-context-diff) | 上下文差异里的新增、删除、风险、验证和影响范围 |
| [repo-onboarding-check](https://github.com/aolingge/repo-onboarding-check) | 新贡献者安装、运行、测试、贡献和求助路径 |
| [ai-pr-risk-labeler](https://github.com/aolingge/ai-pr-risk-labeler) | PR 描述是否足够支持 AI 辅助改动风险标签 |

</details>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>student-deploy-kit</h3>
      <p>面向学生和独立开发者的部署工具包：Nginx 配置、Spring Boot systemd 脚本、前端部署、Docker Compose、VPS 安全和故障排查文档。</p>
      <p>
        <a href="https://github.com/aolingge/student-deploy-kit"><b>Repository</b></a>
        ·
        <a href="https://github.com/aolingge/student-deploy-kit/releases/tag/v0.1.0"><b>Release</b></a>
      </p>
      <p><code>bash scripts/validate.sh</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>open-source-portfolio</h3>
      <p>一个以部署和项目证据为核心的开源作品集模板，使用 GitHub Pages 发布，适合学生和独立开发者展示真实项目。</p>
      <p>
        <a href="https://github.com/aolingge/open-source-portfolio"><b>Repository</b></a>
        ·
        <a href="https://aolingge.github.io/open-source-portfolio/"><b>Live site</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>oss-readme-check</h3>
      <p>一个零依赖 CLI，用来检查 README 是否适合开源发布：快速开始、视觉锚点、多语言入口、贡献路径、安全边界、首次成功验证。</p>
      <p>
        <a href="https://github.com/aolingge/oss-readme-check"><b>Repository</b></a>
        ·
        <a href="https://github.com/aolingge/oss-readme-check/releases/tag/v0.1.0"><b>Release</b></a>
      </p>
      <p><code>npx oss-readme-check --path README.md</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>vps-deploy-doctor</h3>
      <p>一个只读 VPS 部署诊断工具，用来检查 Nginx、systemd、端口、Docker、防火墙、磁盘、内存和日志，适合学生项目上线排障。</p>
      <p>
        <a href="https://github.com/aolingge/vps-deploy-doctor"><b>Repository</b></a>
        ·
        <a href="https://github.com/aolingge/vps-deploy-doctor/releases/tag/v0.1.0"><b>Release</b></a>
      </p>
      <p><code>bash bin/vps-deploy-doctor.sh --service demo-api</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>agent-secret-guard</h3>
      <p>一个面向 Agent 时代仓库的 5 分钟安全检查工具，用来发现 MCP token、过宽文件系统权限、浏览器 profile 暴露和 GitHub Actions 风险。</p>
      <p>
        <a href="https://github.com/aolingge/agent-secret-guard"><b>Repository</b></a>
        ·
        <a href="https://www.npmjs.com/package/agent-secret-guard"><b>npm</b></a>
      </p>
      <p><code>npx agent-secret-guard scan . --fail-on high</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>Project factory</h3>
      <p>一个本地开源项目工厂工作流，用来创建、打包、记录和迭代 GitHub 项目，同时把草稿、发布物料和私有笔记留在公开仓库之外。</p>
      <p>
        <a href="https://github.com/aolingge"><b>Project index</b></a>
      </p>
    </td>
  </tr>
</table>

## 技术栈

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3572A5?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-b07219?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Vue-42b883?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" alt="PowerShell" />
</p>

## 我的工作方式

- 让第一次运行尽量无聊：短命令、清晰默认值、少隐藏步骤。
- 把文档当成产品的一部分，而不是最后补的说明。
- 对凭据、浏览器 profile 和 Agent 权限保持安全边界。
- 发布时留下可复用的清单和记录，方便后续维护。

---

<p align="center">
  <b>Make it clean. Make it reusable. Make it easy to ship.</b><br />
  <sub>Chongqing City · Chongqing University · open-source notes, tools, and experiments</sub>
</p>
