# Reference Library · 参考资料库

把值得学习和复用的开源项目与阅读资料按用途放在一起。

这些项目来自各自原作者，已 fork 到 [heran11011](https://github.com/heran11011)。本仓库用 **Git 子模块** 分类收纳：在 GitHub 上点目录即可进入对应项目源码；不是把他人的代码改署名，也不是把全部源码重复复制一份。

## 分类入口

| 分类 | 子模块数量 | 内容 |
|---|---:|---|
| **[设计与界面](design/)** | **6** | 动效、灵感拆解、阅读排版、交互 demo、网页性能与无障碍 |
| [内容与排版](content/) | 1 | HTML / Markdown / DOCX 整理流水线 |
| [工程与 Agent](engineering/) | 1 | 工具执行、权限、技能加载与上下文管理；另收 1 份协作指南 PDF |
| [产品与需求](product/) | 1 | PRD 评审、增量更新与验收模板 |

**先从设计开始：** [Emil 的 UI 技能](design/emil-ui-skills)、[Cabinet 灵感库](design/cabinet)、[Web Quality 验收技能](design/web-quality-skills)。

## 阅读资料

- [Finding Your Unknowns · 非官方读书笔记 PDF](engineering/guides/claude-fable-finding-your-unknowns.pdf)：在实现前、中、后发现需求盲点与隐含假设的协作方法。原文、来源及许可说明见 [指南目录](engineering/guides/)。

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
