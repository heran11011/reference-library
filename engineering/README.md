# 工程与 Agent

[← 全部分类](../)

| 项目源码 | 用途 | 原作者 |
|---|---|---|
| [learn-claude-code](learn-claude-code) | 从写 skill 进阶到工具执行、权限审批、按需技能加载和上下文压缩 | [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) |

## 阅读指南

| 资料 | 用途 | 来源 |
|---|---|---|
| [Finding Your Unknowns · PDF](guides/claude-fable-finding-your-unknowns.pdf) | 通过盲点检查、原型、访谈、参考和实现记录，逐步澄清需求与隐含假设 | 非官方读书笔记；[官方原文](https://claude.com/blog/a-field-guide-to-claude-fable-finding-your-unknowns)作者为 Thariq Shihipar |

[查看 PDF 的来源与许可说明 →](guides/)

## 使用边界

适合读教学源码和做隔离实验，不是开箱即用的安全生产底座。权限课使用 shell 命令和字符串/正则拦截，不等于文件/网络隔离沙箱；历史归档、模型请求和工具输出也有数据边界。先用虚拟资料，依赖与宿主兼容性另审。
