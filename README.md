# 你好，我是 DrizzleGig（细雨歌）👋

DSH（[DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness)）插件作者，正在做 **DSH-novel** 系列：一套给长篇小说用的 AI 写作工具。每个插件只管一件事：剧情怎么定、旧事怎么记、原著与本作怎么分、文风怎么学；默认关闭，不写正文，可以单装，也可以组合。

我关心的不只是「AI 能不能写」，而是它能不能在几十万字里记住该记住的、尊重已经定下的设定、写出作者想要的风格，并在关键处让作者拍板。**AI 可以承担更多工作，但故事的方向、取舍与最终判断，应该始终掌握在作者手中。**

> Hi, I'm DrizzleGig, a DSH (DeepSeek Harness) plugin author building **DSH-novel** — a set of tools for long-form fiction with AI. Each plugin does one job: plot decisions, long-term memory, canon, or style. They're off by default and never write the prose themselves. I care less about whether AI can write and more about whether it can stay coherent across a very long story, respect what's already established, write in the voice the author wants, and let the author make the calls that matter. AI can do more of the work; the story should still belong to the person who imagines it.

---

## 在做的事

| 插件 | 管什么 | 一句话 | 版本 / 状态 |
|:--|:--|:--|:--|
| 🧭 **拍板** · [beat](https://github.com/DrizzleGig/dsh-novel-beat) | 该发生什么 | 关键剧情不交给模型顺手决定：在影响走向的岔路停下来，给 2–4 个真不同的走向和代价，你选完写进全书账本。 | [![npm](https://img.shields.io/npm/v/dsh-novel-beat)](https://www.npmjs.com/package/dsh-novel-beat) |
| 🌫️ **褪色** · [fade](https://github.com/DrizzleGig/dsh-novel-fade) | 还记得什么 | 近章重点记，旧事逐步淡。写完沉淀事件卡，写前只拿 1400 字简报，原文只存不用。 | [![npm](https://img.shields.io/npm/v/dsh-novel-fade)](https://www.npmjs.com/package/dsh-novel-fade) |
| 📖 **同人** · [fanfic](https://github.com/DrizzleGig/dsh-novel-fanfic) | 原著与本作是什么 | 原著 canon 和本作设定分开记账；写前编成场景契约，写完只指出「在哪、凭什么、跟哪条冲突」。 | [![npm](https://img.shields.io/npm/v/dsh-novel-fanfic)](https://www.npmjs.com/package/dsh-novel-fanfic) |
| 🖋️ **文风** · [voice](https://github.com/DrizzleGig/dsh-novel-voice) | 谁在说、怎么说 | 导入喜欢的作品，提炼四层风格档案；写前 600 字简报，写后把 AI 味定位到句子。 | [![npm](https://img.shields.io/npm/v/dsh-novel-voice)](https://www.npmjs.com/package/dsh-novel-voice) |
| 🎬 **指挥** · `conductor` | 这一章先做什么 | 排一章的流程、算上下文预算、记执行证据。 | 计划中 |

## 现在 / 下一步

beat / fade / fanfic / voice 四个已经发布。接下来做 `conductor`——把一章的流程、上下文预算和执行证据排出来；五个稳定后，整合成 `dsh-novel-Pro`。

## 其他工具

另一个小工具 **env-probe**：在对话输入框下方实时显示会话 ID / 语言 / 时区 / 视口尺寸，并提供 `env_probe` 工具，让 AI 直接读到自己在什么环境里跑。

## 工具箱

`Windows 11` · `Node.js 24` · `pnpm` · `git` · `VS Code` · `DeepSeek Harness`

## 联系

Issues 和 Discussions 都开着，欢迎来聊插件、聊长篇写作，或者聊聊你正在写的那本书。

Asia/Shanghai · 中文 / English
