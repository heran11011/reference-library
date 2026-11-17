# 工程与 Agent

[← 全部分类](../)

| 项目源码 | 用途 | 原作者 |
|---|---|---|
| [learn-claude-code](learn-claude-code) | 从写 skill 进阶到工具执行、权限审批、按需技能加载和上下文压缩 | [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) |
| [T3 Code 中文版](t3code-zh) | 核查 Javey-Li 中文 fork 的本机编程 Agent 控制界面与中文化方案 | [Javey-Li/t3code-zh](https://github.com/Javey-Li/t3code-zh) |
| [dsh-superagent](dsh-superagent-prototype) | 核查 Javey-Li 好友 fork 的 GitHub / 飞书任务触发与部署契约研究原型 | [Javey-Li/dsh-superagent-prototype](https://github.com/Javey-Li/dsh-superagent-prototype) |

## 阅读指南

| 资料 | 用途 | 来源 |
|---|---|---|
| [Finding Your Unknowns · PDF](guides/claude-fable-finding-your-unknowns.pdf) | 通过盲点检查、原型、访谈、参考和实现记录，逐步澄清需求与隐含假设 | 非官方读书笔记；[官方原文](https://claude.com/blog/a-field-guide-to-claude-fable-finding-your-unknowns)作者为 Thariq Shihipar |

[查看 PDF 的来源与许可说明 →](guides/)

## 使用边界

适合读教学源码和做隔离实验，不是开箱即用的安全生产底座。权限课使用 shell 命令和字符串/正则拦截，不等于文件/网络隔离沙箱；历史归档、模型请求和工具输出也有数据边界。先用虚拟资料，依赖与宿主兼容性另审。

- T3 Code 中文版与 dsh-superagent 本次仅核实公开元数据和 README，作为核查资料收纳；未安装、未实测，也未在此完成源码安全审查。
- 两项均保留 Javey-Li 的 fork，不改用其上游；各 fork 的默认分支实际提交固定在子模块和来源记录中。
- T3 Code 中文 fork 的 README 提醒其中文 Beta 未公证，且与官方版 / Nightly 共用数据目录；不要将收纳理解为可以直接覆盖现有安装。
- dsh-superagent 的 README 明确其为研究原型、非正式 DeepSeek 产品；GitHub / 飞书触发和自动执行涉及权限、凭证及用户数据，配置与部署需另行核查。
