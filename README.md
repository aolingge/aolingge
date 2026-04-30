<p align="center">
  <img src="./assets/profile-banner.svg" alt="Aolinge profile banner" width="100%" />
</p>

<h1 align="center">Aolinge</h1>

<p align="center">
  <a href="https://github.com/aolingge"><img src="https://img.shields.io/badge/GitHub-aolingge-151515?style=flat-square&logo=github" alt="GitHub profile" /></a>
  <a href="mailto:1930668092@qq.com"><img src="https://img.shields.io/badge/Email-1930668092%40qq.com-D94A38?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <b>Computer Science student at Chongqing University</b><br />
  Building local-first tools for AI-agent repositories, MCP safety, and repeatable software delivery.
</p>

<p align="center">
  English | <a href="README.zh-CN.md">简体中文</a>
</p>

---

## Focus

I turn fragile development workflows into small tools that are easy to run,
review, and ship again. My current work is centered on three areas:

| Area | What I build |
| --- | --- |
| AI-agent reliability | CLIs that check repo instructions, secrets, CI, MCP configs, run traces, and release readiness before an agent marks work as done. |
| Local automation | Repeatable scripts and workflow kits for Windows-first development, deployment checks, and safe long-running agent tasks. |
| Practical backend and delivery | Java / Spring Boot practice projects, deployment notes, and portfolio material with clear verification paths. |

## Start Here

| Project | Use it for | First command |
| --- | --- | --- |
| [agent-secret-guard](https://github.com/aolingge/agent-secret-guard) | Fast safety scan for AI-agent repos, MCP configs, browser profile paths, and risky GitHub Actions permissions. | `npx agent-secret-guard scan . --fail-on high` |
| [mcp-config-doctor](https://github.com/aolingge/mcp-config-doctor) | Diagnose MCP config files before an AI client fails to connect. | `npx mcp-config-doctor --config mcp.json` |
| [agent-reliability-kit](https://github.com/aolingge/agent-reliability-kit) | One report for AI-agent repo readiness, README quality, CI, secrets, MCP, n8n, and release risk. | `npx agent-reliability-kit scan .` |
| [repo-release-proof](https://github.com/aolingge/repo-release-proof) | Check whether release notes prove what changed, how it was verified, and where it was published. | `npx github:aolingge/repo-release-proof --path RELEASE.md` |

## Portfolio

| Project | Why it matters |
| --- | --- |
| [agent-symphony-kit](https://github.com/aolingge/agent-symphony-kit) | Local-first task files, preflight checks, gate reports, and workflow contracts for coding agents. |
| [agent-run-trace-pack](https://github.com/aolingge/agent-run-trace-pack) | Redacted, reviewable trace packs for agent and shell runs. |
| [open-source-portfolio](https://github.com/aolingge/open-source-portfolio) | A GitHub Pages portfolio template focused on proof, deployment, and service clarity. |
| [student-deploy-kit](https://github.com/aolingge/student-deploy-kit) | Beginner-friendly deployment material for Nginx, Spring Boot, frontend apps, Docker, VPS security, and troubleshooting. |
| [vps-deploy-doctor](https://github.com/aolingge/vps-deploy-doctor) | Read-only VPS diagnostics for Nginx, systemd, ports, Docker, firewall, disk, memory, and logs. |

## Available For

I take a small number of focused launch-readiness audits for public or
shareable AI-agent, MCP, GitHub Actions, and local automation repositories.

| Service | Deliverable |
| --- | --- |
| AI Agent Repo Safety Audit | A 24-hour Markdown risk summary covering agent instructions, MCP args, local credential paths, browser profile exposure, CI permissions, and practical fixes. |
| Fix PR | A scoped pull request that moves risky examples toward safer defaults after an audit. |
| Local automation hardening | A review of repo docs, workflows, and scripts before public release or handoff. |

Send a public repository link by email or GitHub. Do not send production
secrets, cookies, private keys, or live credentials.

## Toolbox

TypeScript, JavaScript, Node.js, Python, Java, Spring Boot, GitHub Actions, PowerShell.

## Working Style

- Make the first run boring: short commands, clear defaults, and concrete output.
- Keep reports local-first and careful around secrets, browser profiles, and account material.
- Treat documentation as part of the product, not a cleanup step.
- Prefer small, inspectable tools that compose into a stronger workflow.

---

<p align="center">
  <b>Clean workflows. Local-first safety. Reusable delivery.</b><br />
  <sub>Chongqing City · Chongqing University · open-source notes, tools, and experiments</sub>
</p>
