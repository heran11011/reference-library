# 设计与界面

[← 全部分类](../)

把动效、排版、灵感参考、交互 demo 和网页体验验收放在一起。

| 项目源码 | 适合借什么 | 原作者 |
|---|---|---|
| **[emil-ui-skills](emil-ui-skills)** | 缓动、动效打断、手机触摸、长标题与极端内容测试 | [emilkowalski/skills](https://github.com/emilkowalski/skills) |
| **[cabinet](cabinet)** | 将参考图拆成具体手法、锚点、理由和迁移边界 | [pxx-design/cabinet](https://github.com/pxx-design/cabinet) |
| **[web-quality-skills](web-quality-skills)** | 图片/字体加载、性能、布局稳定、键盘和无障碍 | [addyosmani/web-quality-skills](https://github.com/addyosmani/web-quality-skills) |
| [gsap-skills](gsap-skills) | GSAP 官方时间线、多元素编排、滚动动画与清理 | [greensock/gsap-skills](https://github.com/greensock/gsap-skills) |
| [mengto-design-skills](mengto-design-skills) | 现成交互 demo、HTML/录屏参考拆解、Three.js 材质 | [MengTo/Skills](https://github.com/MengTo/Skills) |
| [design-sense](design-sense) | 阅读列、中英文字体、层级、留白与风格判断 | [pxx-design/design-sense](https://github.com/pxx-design/design-sense) |

## 怎么选

- 已有页面，想让操作更自然：先看 **Emil**。
- 喜欢一个参考，但说不清怎么用：看 **Cabinet**。
- 验收图片、字体、手机操作和页面稳定性：看 **Web Quality**。
- 多个元素需要复杂协同：参考 **GSAP**，不必因此更换现有动画实现。
- 学真实材质、网格变形或做独立互动实验：看 **MengTo** 的具体 demo，不全套搬进首页。
- 打磨长文排版：参考 **Design Sense**，但个人站不必照搬品牌的全部限制。

## 特别注意

- Cabinet 的代码和手法文本为 MIT，附带参考图/视频不是。其默认安装器还会改全局 hooks 并在 macOS 加后台 watcher，运行前另审。
- MengTo 的纸张材质有真实卷角，但不是完整翻页书组件；作者报告其示例 GPU 内存约 100 MB，未在此复测，不建议整套用于手机首页。
- Design Sense 的 Anthropic 规则强调纸不浮起，与实体抽纸交互并不完全一致；只取适用部分。
- Web Quality 含 SEO 模块，可以只用性能和无障碍部分。

这些是 Git 子模块，点击项目目录会进入固定提交的源码。所有作者与许可信息保持在原项目中。
