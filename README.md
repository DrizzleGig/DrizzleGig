# 你好，我是 DrizzleGig（细雨歌）👋

> DSH 插件作者。正在做 **DSH-novel** 系列：让 AI 更好地写长篇小说。

---

## 在做的事

**DSH-novel** 是一套给长篇小说用的 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) 插件。每个只管一件事，默认关闭、不写正文，可以单装，也可以组合。

| 插件 | 管什么 | 一句话 | 版本 |
|:--|:--|:--|:--|
| 🧭 **拍板** · [beat](https://github.com/DrizzleGig/dsh-novel-beat) | 该发生什么 | 关键剧情不交给模型顺手决定：在影响走向的岔路停下来，给 2–4 个真不同的走向和代价，你选完写进全书账本。 | [![npm](https://img.shields.io/npm/v/dsh-novel-beat)](https://www.npmjs.com/package/dsh-novel-beat) |
| 🌫️ **褪色** · [fade](https://github.com/DrizzleGig/dsh-novel-fade) | 还记得什么 | 近章重点记，旧事逐步淡。写完沉淀事件卡，写前只拿 1400 字简报，原文只存不用。 | [![npm](https://img.shields.io/npm/v/dsh-novel-fade)](https://www.npmjs.com/package/dsh-novel-fade) |
| 📖 **同人** · [fanfic](https://github.com/DrizzleGig/dsh-novel-fanfic) | 原著与本作是什么 | 原著 canon 和本作设定分开记账；写前编成场景契约，写完只指出「在哪、凭什么、跟哪条冲突」。 | [![npm](https://img.shields.io/npm/v/dsh-novel-fanfic)](https://www.npmjs.com/package/dsh-novel-fanfic) |
| 🖋️ **文风** · [voice](https://github.com/DrizzleGig/dsh-novel-voice) | 谁在说、怎么说 | 导入喜欢的作品，提炼四层风格档案；写前 600 字简报，写后把 AI 味定位到句子。 | [![npm](https://img.shields.io/npm/v/dsh-novel-voice)](https://www.npmjs.com/package/dsh-novel-voice) |
| 🎬 **指挥** · `conductor` | 这一章先做什么 | 计划中：排一章的流程、算上下文预算、记执行证据。 | — |

现在 beat / fade / fanfic / voice 四个已经能单独装。下一步是让它们互相读得懂——先做 `conductor`（一章的流程与预算），最后整合成 `dsh-novel-Pro`。

- 更早的 **env-probe**：在对话输入框下方实时显示会话 ID / 语言 / 时区 / 视口尺寸，并提供 `env_probe` 工具，让 AI 直接读到自己在什么环境里跑。
- 目标没变：让 AI 不只是「回答问题」，而是能真正接手这台机器上的实际工作。

## 工具箱

`Windows 11` · `Node.js 24` · `pnpm` · `git` · `VS Code` · `DeepSeek Harness`

## 联系

Issues 和 Discussions 都开着，欢迎来聊插件、聊长篇写作、聊怎么把日常自动化掉。

Asia/Shanghai · 中文 / English
