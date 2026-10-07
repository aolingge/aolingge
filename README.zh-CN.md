<p align="center">
  <img src="https://raw.githubusercontent.com/aolingge/aolingge/main/assets/profile-cover.png" alt="深蓝、青绿与暖金色的语言学习和开发工具主题插画" width="100%" />
</p>

<h1 align="center">Aolinge</h1>

<p align="center">
  <strong>从日常影音里学语言，用实用工具让开发更清楚。</strong><br />
  语言学习应用 · AI Agent 开发工具 · 优先在本地完成的工作流
</p>

<p align="center">
  <a href="README.md">English</a> · 简体中文 ·
  <a href="#从这里开始">从这里开始</a> · <a href="#精选项目">精选项目</a> ·
  <a href="#完整项目地图">完整项目地图</a> · <a href="mailto:1930668092@qq.com">联系我</a>
</p>

我围绕两件日常会做的事开发工具：**学语言**与**写代码**。这些项目把视频和电脑播放声变成学习材料，整理德语学习路线，也帮助开发者检查配置、仓库和 Coding Agent 的执行过程。

## 从这里开始

| 你想做什么 | 建议入口 |
| --- | --- |
| 用 YouTube 或 Bilibili 学语言 | [YT Dual Subs](https://github.com/aolingge/yt-dual-subs/blob/main/README.zh-CN.md#安装)：安装扩展，用字幕练听力、查词和复习。 |
| 给 Windows 播放声加德语字幕 | [DeutschOverlay](https://github.com/aolingge/DeutschOverlay#下载与安装)：下载应用，选择播放设备。 |
| 找一条德语学习路线 | [deutsch-lernen](https://github.com/aolingge/deutsch-lernen)：中文学习者的 A1–C1 路线、考试准备与资料地图。 |
| 检查 AI Agent 仓库 | [Agent Secret Guard](https://github.com/aolingge/agent-secret-guard#quick-start) 做专项安全检查；[Agent Reliability Kit](https://github.com/aolingge/agent-reliability-kit#quick-start) 汇总仓库状态。 |
| 排查 MCP 连不上 | [MCP Config Doctor](https://github.com/aolingge/mcp-config-doctor#quick-start)：在本地检查语法、启动命令、环境配置与常见错误。 |

## 精选项目

### 语言学习

#### [YT Dual Subs](https://github.com/aolingge/yt-dual-subs)

**把原本就在看的视频变成语言练习。** 在 YouTube 和 Bilibili 同时显示原文与译文，支持悬停查词、当前单词高亮、难句重播、表达收藏和字幕导出。适用于 Chrome、Edge 桌面版；字幕可用条件与翻译服务说明见项目文档。

[安装教程](https://github.com/aolingge/yt-dual-subs/blob/main/README.zh-CN.md#安装) · [English](https://github.com/aolingge/yt-dual-subs)

#### [DeutschOverlay](https://github.com/aolingge/DeutschOverlay)

**为 Windows 11 电脑正在播放的声音显示德语字幕。** 德语显示原文，英语或中文翻译成德语。支持单行或双语字幕、自定义外观和播放设备选择；本地模式可离线处理，另有单独说明的可选 Azure 在线模式。

[下载与设置](https://github.com/aolingge/DeutschOverlay#下载与安装) · [发布版本](https://github.com/aolingge/DeutschOverlay/releases)

#### [deutsch-lernen](https://github.com/aolingge/deutsch-lernen)

**面向中文学习者的德语学习地图。** 将 A1–C1 路线、听说读写训练、考试选择与赴德准备串起来。在线资料站支持筛选、收藏，以及保存在浏览器里的学习计划。

[学习路线](https://github.com/aolingge/deutsch-lernen/blob/main/docs/README.md) · [在线学习站](https://deutsch-lernen-resource-hub.pirostonelsonrx688.workers.dev/)

### 开发工具

#### [Agent Secret Guard](https://github.com/aolingge/agent-secret-guard)

**检查 AI Agent 仓库与 MCP 配置里的常见风险。** 识别疑似凭据、危险命令参数、浏览器或凭据存储引用，以及权限过宽的 GitHub Actions。提供文本、JSON、SARIF 输出，便于本地或 CI 中检查与修复。

[中文说明](https://github.com/aolingge/agent-secret-guard/blob/main/README.zh-CN.md) · [GitHub Action](https://github.com/aolingge/agent-secret-guard-action) · [修复指南](https://github.com/aolingge/agent-secret-guard/blob/main/docs/remediation.md)

#### [Agent Reliability Kit](https://github.com/aolingge/agent-reliability-kit)

**汇总 Coding Agent 使用的仓库健康情况。** 检查 Agent 指令、验证命令、README、CI 权限、工具配置风险和发布准备情况，生成 Markdown、JSON、HTML 报告；还提供团队审查、MCP 注册清单和 n8n 工作流的专项命令。

[快速开始](https://github.com/aolingge/agent-reliability-kit#quick-start) · [项目文档](https://aolingge.github.io/agent-reliability-kit/)

#### [MCP Config Doctor](https://github.com/aolingge/mcp-config-doctor)

**在客户端连不上之前，先找出 MCP 配置问题。** 检查配置结构、启动命令、环境设置与常见凭据泄露，输出终端、JSON 或 Markdown 报告。检查在本地执行；配置诊断不能替代对 MCP 服务本身的安全审查。

[中文说明](https://github.com/aolingge/mcp-config-doctor/blob/main/README.zh-CN.md) · [检查范围](https://github.com/aolingge/mcp-config-doctor#checks)

## 完整项目地图

上面是主要入口，下面这些仓库补齐全部公开项目：

| 项目 | 用途 | 从哪里开始 |
| --- | --- | --- |
| [qingjian-german](https://github.com/aolingge/qingjian-german) | 基于上游青简输入法的 fork，补充汉德释义、词汇等级、生成工具和验证记录。 | [德语扩展说明](https://github.com/aolingge/qingjian-german/blob/german/german/README.md) |
| [agent-run-trace-pack](https://github.com/aolingge/agent-run-trace-pack) | 包装本地命令，记录脱敏输出、退出状态、Git 状态和可审查的执行报告。 | [快速开始](https://github.com/aolingge/agent-run-trace-pack#quick-start) |
| [agent-secret-guard-action](https://github.com/aolingge/agent-secret-guard-action) | 用小型、固定版本的封装把扫描器接入 GitHub Actions。 | [工作流示例](https://github.com/aolingge/agent-secret-guard-action#quick-start) |
| [open-source-portfolio](https://github.com/aolingge/open-source-portfolio) | React + Vite 中英双语作品集，包含项目介绍与 GitHub Pages 部署。 | [在线作品集](https://aolingge.github.io/open-source-portfolio/) |
| [.github](https://github.com/aolingge/.github) | 为采用默认配置的仓库提供共享社区模板与贡献规范。 | [默认文件说明](https://github.com/aolingge/.github#what-belongs-here) |
| [aolingge](https://github.com/aolingge/aolingge) | 当前双语个人主页、项目目录与原创视觉素材。 | [English](README.md) |

## 做事方式

做小而实用的工具，写清安装步骤，用真实截图和实际检查说明功能。公开示例不含凭据与私人数据；各项目文档分别说明运行条件和能力边界。

**语言与工具：** JavaScript / TypeScript · Python · Node.js · Java / Spring Boot · PowerShell

## 联系

[邮箱](mailto:1930668092@qq.com) · [公开仓库](https://github.com/aolingge?tab=repositories&type=public) · [反馈与想法](https://github.com/aolingge/aolingge/issues)

<sub>主页使用专属生成的装饰插画；真实产品截图与技术说明见各项目仓库。</sub>
