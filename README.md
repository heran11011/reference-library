# Reference Library · 参考资料库

按用途收纳值得学习和复用的资料，方便查找设计方法、内容工具、Agent 教程、需求模板和模型管理工具。

目前收录 **15 项资料：14 个公开项目 + 1 份 PDF**。每项都有直达链接和一句话介绍；详细使用建议与风险说明放在各分类目录。

## 分类导航

| 分类 | 资料数量 | 关键词 |
|---|---:|---|
| [设计与界面](#设计与界面) | 7 | 动效、灵感拆解、材质、字体、性能、无障碍 |
| [内容与排版](#内容与排版) | 1 | HTML、Markdown、DOCX、文档归档 |
| [工程与 Agent](#工程与-agent) | 5 | 工具执行、权限、技能加载、上下文、记忆检索、需求盲点 |
| [产品与需求](#产品与需求) | 1 | PRD、MVP、异常状态、验收标准 |
| [模型与账号工具](#模型与账号工具) | 1 | API 路由、模型切换、已有账号、配额管理 |

## 设计与界面

| 资料链接 | 类型 | 一句话介绍 |
|---|---|---|
| [Emil UI Skills · emil-ui-skills](https://github.com/heran11011/emil-ui-skills) | 交互与动效技能 | 提供缓动、动效打断、手机触摸和极端内容的设计与评审方法，适合让已有界面的操作更自然。 |
| [Cabinet · cabinet](https://github.com/heran11011/cabinet) | 设计参考拆解工具 | 将参考图拆成具体设计手法、使用理由和迁移边界，帮助把“喜欢这个感觉”转成可用的设计判断。 |
| [Web Quality Skills · web-quality-skills](https://github.com/heran11011/web-quality-skills) | 网页质量验收技能 | 提供图片与字体加载、页面性能、布局稳定性、键盘操作和无障碍的检查方法，适合上线前验收。 |
| [GSAP Skills · gsap-skills](https://github.com/heran11011/gsap-skills) | 动画实现技能 | 提供 GSAP 时间线、多元素编排、滚动动画和性能处理的实现指导，适合复杂协同动效。 |
| [MengTo Design Skills · mengto-design-skills](https://github.com/heran11011/mengto-design-skills) | 设计技能与交互示例 | 收录交互 demo、HTML 与录屏参考拆解及 Three.js 材质示例，适合学习纸张卷角等独立视觉实验。 |
| [Design Sense · design-sense](https://github.com/heran11011/design-sense) | 视觉规范与设计技能 | 提供阅读列、中英文字体、留白、层级及风格规则，适合打磨长文排版与视觉一致性。 |
| [PRISM · PRISM-collect-your-inspo](https://github.com/heran11011/PRISM-collect-your-inspo) | 视觉灵感分析工具 | 从图片或网站提取配色、字体、布局和动效并导出设计参考，README 声称 MIT 但未发现 LICENSE 文件，复用前需确认许可。 |

[分类说明与使用边界 →](design/)

## 内容与排版

| 资料链接 | 类型 | 一句话介绍 |
|---|---|---|
| [Huashu MD / HTML · huashu-md-html](https://github.com/heran11011/huashu-md-html) | 内容转换工具 | 将公开 HTML 正文整理为 Markdown，并支持 Markdown 转 HTML 与 DOCX，适合内容归档和阅读排版。 |

[分类说明与使用边界 →](content/)

## 工程与 Agent

| 资料链接 | 类型 | 一句话介绍 |
|---|---|---|
| [Learn Claude Code · learn-claude-code](https://github.com/heran11011/learn-claude-code) | Agent 开发教程 | 用教学源码讲解工具执行、权限审批、按需技能加载和上下文压缩，适合理解 Agent 与 Skill 背后的运行机制。 |
| [T3 Code 中文版 · t3code-zh](https://github.com/heran11011/t3code-zh) | Agent 控制界面核查资料 | 保留 Javey-Li 的中文 fork，参考其管理本机编程 Agent 的界面与中文化方案，仅核实元数据和 README，未安装或实测。 |
| [dsh-superagent · dsh-superagent-prototype](https://github.com/heran11011/dsh-superagent-prototype) | 自动化 Agent 原型核查资料 | 保留 Javey-Li 的好友 fork，参考其 GitHub / 飞书触发任务和部署契约，仅核实元数据和 README，未安装或实测且非正式 DeepSeek 产品。 |
| [Claude-mem · claude-mem](https://github.com/heran11011/claude-mem) | 跨会话记忆与检索工具 | 自动提供跨会话记忆与检索，会采集提示词和工具记录并触发额外观察模型调用，仅收纳公开源码，未安装接入。 |
| [Finding Your Unknowns · PDF](engineering/guides/claude-fable-finding-your-unknowns.pdf) | 非官方读书笔记 | 介绍如何通过盲点检查、原型、访谈、参考和实现记录，在动手前后逐步澄清需求与隐含假设。 |

[分类说明与使用边界 →](engineering/) · [PDF 来源、原文与许可说明 →](engineering/guides/)

## 产品与需求

| 资料链接 | 类型 | 一句话介绍 |
|---|---|---|
| [PRD Writer · prd-writer](https://github.com/heran11011/prd-writer) | 需求文档技能 | 提供 PRD 评审、已有文档增量融合、MVP、异常状态、字段和验收模板，适合补齐需求稿与控制范围。 |

[分类说明与使用边界 →](product/)

## 模型与账号工具

| 资料链接 | 类型 | 一句话介绍 |
|---|---|---|
| [magpie](https://github.com/heran11011/magpie) | API 路由与配额管理工具 | 为已有模型服务和账号提供 API 路由、模型切换与配额管理，不会赠送会员或新增订阅额度。 |

[分类说明与使用边界 →](tools/)

## 链接与版本说明

- 上表的项目链接进入已 fork 到 [heran11011](https://github.com/heran11011) 的仓库，方便直接浏览。
- 各分类目录使用 **Git 子模块** 指向固定提交，保留原作者、来源和独立更新关系，不重复复制整份源码。
- 原项目地址、分类路径和已核查提交见 [sources.json](sources.json)；PDF 来源单独记录在 [指南目录](engineering/guides/)。
- 2026-11-18 新增的 magpie、T3 Code 中文版、dsh-superagent 和 PRISM 仅核实公开元数据与 README，不代表完成源码安全审查。
- 这里收纳的是不同类型的参考资源，不是一套统一的 Design System，也不表示全部已安装或实测。

## 本地使用

只下载合集索引：

```bash
git clone https://github.com/heran11011/reference-library.git
cd reference-library
```

按需取一份源码，例如动效技能：

```bash
git submodule update --init design/emil-ui-skills
```

需要所有项目源码时：

```bash
git submodule update --init --recursive
```

有些项目带图片、视频和大量 demo，全部下载会明显大于这个索引仓库，建议先按需下载。

## 更新方式

合集固定记录一个已核查的源码提交。原 fork 更新后，先检查改动，再更新对应子模块并提交合集：

```bash
git submodule update --init design/emil-ui-skills
git submodule update --remote design/emil-ui-skills
git add design/emil-ui-skills
git commit -m "chore: update Emil UI reference"
```

`--remote` 读取的是自己的 fork 分支，不会自动把原作者的新提交同步进自己的 fork；原作者更新需先同步 fork。本次记录的路径、上游、分支及提交见 [sources.json](sources.json)。今后更新子模块时，也应更新对应来源记录。

## 借鉴边界

- 子模块保留各项目独立的 Git 历史、版权与许可。具体许可以每个项目为准。
- **MIT 代码许可不等于图片、字体、角色或品牌商标授权。** Cabinet 的打包参考图片/视频不在 MIT 范围内，不直接拿来当自己的素材。
- skill 是工作方法，不是安全认证。教程的权限审批不等于沙箱，依赖也需要另审。
- 此处收纳不意味着已经安装或实测全部项目。挑选与当前任务相关的一份阅读，不把整套规则无差别加载。
- 本仓库只收公开来源，不放账号凭证、内部业务资料或私人会话。

本仓库的原创索引说明采用 MIT；各子模块和第三方 PDF 等资料不因此获得 MIT 授权，仍遵守各自原有权利及许可。
