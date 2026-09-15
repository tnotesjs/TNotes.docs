# TNotes.docs

## 简介

[TNotes.docs][1] 是 TNotes 的产品说明：Desk 怎么用、知识库长什么样、以及 `tnotes-kb` / `tnotes-ssg` 还剩哪些命令。

主要记录：

- 知识库与笔记的目录约定（`tnotes.json` + `TOC.md` + 平铺笔记）
- Desk 里新建库、写笔记、预览站点
- Markdown 扩展（公式、Mermaid、Swiper、Mindmap、Footprints…）
- GitHub Pages 用 `tnotes-ssg` 构建
- 一些迭代记录和旧 core 归档笔记

日常编辑请用 Desk 打开本仓库，不要再用 `@tnotesjs/core` / VitePress。

## Desk 使用说明

以下参考以 2026-09-15 的 Desk 0.8.2 源码为基线，区分可视化编辑、源码编辑与发布站点；TOC 中暂保留未完成状态，供后续人工审阅。

- [快速上手与阅读入口](notes/0043.%20Desk%20使用说明入口与快速上手.md)
- [Markdown 语法](notes/0044.%20Desk%20支持的%20Markdown%20语法.md) · [扩展语法与组件](notes/0045.%20Desk%20扩展语法与组件.md)
- [Desk 命令与快捷键](notes/0046.%20Desk%20命令与快捷键.md) · [CLI 命令](notes/0047.%20TNotes%20CLI%20命令参考.md)
- [应用设置](notes/0048.%20Desk%20应用设置参考.md) · [知识库与笔记配置](notes/0049.%20知识库与笔记配置参考.md)
- [历史说明修订对照](notes/0050.%20Desk%20历史说明修订对照.md)

旧 core 教程和历史截图仍保留；与上述参考冲突时，以当前实现及对应版本说明为准。

## `TNotes.xxx` 知识库

每个主题一个独立 git 仓库。已迁移的库用 Desk 打开；未迁移的库仍是旧的 VitePress + core 布局。

| 知识库 | 简介 |
| --- | --- |
| [TNotes][] | TNotes 的根知识库，集成所有子库目录信息，提供知识库快速导航功能。 |
| [TNotes.algorithms][] | 算法笔记 |
| [TNotes.c][] | C 语言笔记 |
| [TNotes.canvas][] | canvas 笔记 |
| [TNotes.chrome][] | chrome 笔记 |
| [TNotes.cooking][] | 做饭笔记 |
| [TNotes.docs][] | TNotes 说明文档 |
| [TNotes.egg][] | Egg.js 笔记 |
| [TNotes.electron][] | Electron 笔记 |
| [TNotes.en-notes][] | 英语笔记 |
| [en-words][] | 英语单词词库 |
| [TNotes.footprints][] | 个人足迹 |
| [TNotes.git-notes][] | Git 笔记 |
| [TNotes.github][] | GitHub 笔记 |
| [TNotes.javascript][] | JavaScript 笔记 |
| [TNotes.leetcode][] | LeetCode 笔记 |
| [TNotes.markdown][] | Markdown 笔记 |
| [TNotes.miniprogram][] | 小程序笔记 |
| [TNotes.network][] | 网络笔记 |
| [TNotes.nodejs][] | Node.js 笔记 |
| [TNotes.notes][] | 待整理的笔记 |
| [TNotes.python][] | Python 笔记 |
| [TNotes.react][] | React 笔记 |
| [TNotes.redis][] | Redis 笔记 |
| [TNotes.sql][] | SQL 笔记 |
| [TNotes.svg][] | SVG 笔记 |
| [TNotes.typescript][] | TypeScript 笔记 |
| [TNotes.vite][] | Vite 笔记 |
| [TNotes.vitepress][] | VitePress 笔记 |
| [TNotes.vscode][] | VSCode 笔记 |
| [TNotes.vue][] | Vue 笔记 |
| [TNotes.webpack][] | Webpack 笔记 |

## 引用

- [TNotes.docs - github][1]
- [TNotes.docs - github page][2]
- [desk][3]
- [kb][4]
- [ssg][5]

[1]: https://github.com/tnotesjs/TNotes.docs
[2]: https://tnotesjs.github.io/TNotes.docs/
[3]: https://github.com/tnotesjs/tnotes/tree/main/apps/desk
[4]: https://github.com/tnotesjs/tnotes/tree/main/packages/kb
[5]: https://github.com/tnotesjs/tnotes/tree/main/packages/ssg

<!-- tnotesjs repos link -->

[TNotes]: https://tnotesjs.github.io/TNotes.root/
[TNotes.algorithms]: https://tnotesjs.github.io/TNotes.algorithms/
[TNotes.c]: https://tnotesjs.github.io/TNotes.c/
[TNotes.canvas]: https://tnotesjs.github.io/TNotes.canvas/
[TNotes.chrome]: https://tnotesjs.github.io/TNotes.chrome/
[TNotes.cooking]: https://tnotesjs.github.io/TNotes.cooking/
[TNotes.docs]: https://tnotesjs.github.io/TNotes.docs/
[TNotes.egg]: https://tnotesjs.github.io/TNotes.egg/
[TNotes.electron]: https://tnotesjs.github.io/TNotes.electron/
[TNotes.en-notes]: https://tnotesjs.github.io/TNotes.en-notes/
[en-words]: https://github.com/tnotesjs/en-words
[TNotes.footprints]: https://tnotesjs.github.io/TNotes.footprints/
[TNotes.git-notes]: https://tnotesjs.github.io/TNotes.git-notes/
[TNotes.github]: https://tnotesjs.github.io/TNotes.github/
[TNotes.javascript]: https://tnotesjs.github.io/TNotes.javascript/
[TNotes.leetcode]: https://tnotesjs.github.io/TNotes.leetcode/
[TNotes.markdown]: https://tnotesjs.github.io/TNotes.markdown/
[TNotes.miniprogram]: https://tnotesjs.github.io/TNotes.miniprogram/
[TNotes.network]: https://tnotesjs.github.io/TNotes.network/
[TNotes.nodejs]: https://tnotesjs.github.io/TNotes.nodejs/
[TNotes.notes]: https://tnotesjs.github.io/TNotes.notes/
[TNotes.python]: https://tnotesjs.github.io/TNotes.python/
[TNotes.react]: https://tnotesjs.github.io/TNotes.react/
[TNotes.redis]: https://tnotesjs.github.io/TNotes.redis/
[TNotes.sql]: https://tnotesjs.github.io/TNotes.sql/
[TNotes.svg]: https://tnotesjs.github.io/TNotes.svg/
[TNotes.typescript]: https://tnotesjs.github.io/TNotes.typescript/
[TNotes.vite]: https://tnotesjs.github.io/TNotes.vite/
[TNotes.vitepress]: https://tnotesjs.github.io/TNotes.vitepress/
[TNotes.vscode]: https://tnotesjs.github.io/TNotes.vscode/
[TNotes.vue]: https://tnotesjs.github.io/TNotes.vue/
[TNotes.webpack]: https://tnotesjs.github.io/TNotes.webpack/

<!-- others link -->
