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
