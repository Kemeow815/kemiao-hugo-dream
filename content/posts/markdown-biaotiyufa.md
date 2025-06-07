---
title: Markdown-标题语法 | 技术分享
date: 2025-02-12T18:15:57+08:00
lastmod: 2025-02-12T19:11:57+08:00
author: 克喵爱吃卤面
avatar: /img/kemiao.jpg
authorlink: https://www.kemiao.online
cover: https://cdn.jsdelivr.net/gh/kmfx/tuchuang@main/img/biaotiyufa.png
images:
  - /img/kemiao.jpg
categories:
  - 技术分享
tags:
  - Markdown
  - 速查表
  - 标题语法
# nolastmod: true
# math: true
draft: false
---

> 原文位置: https://markdown.com.cn/basic-syntax/headings.html

# Markdown 标题语法
要创建标题，请在单词或短语前面添加井号 (#) 。`#` 的数量代表了标题的级别。例如，添加三个 `#` 表示创建一个三级标题 (`<h3>`) (例如：`### My Header`)。

| Markdown语法      | HTML                       | 预览效果                |
| ----------------- | -------------------------- | ----------------------- |
| `# Heading level 1` | &lt;h1&gt;Heading level 1&lt;/h1&gt; | {{< raw >}}<h1>Heading level 1</h1>{{</ raw >}}|
| `## Heading level 2` | &lt;h2&gt;Heading level 1&lt;/h2&gt; | {{< raw >}}<h2>Heading level 2</h2>{{</ raw >}} |
| `### Heading level 3` | &lt;h3&gt;Heading level 1&lt;/h3&gt; | {{< raw >}}<h3>Heading level 3</h3>{{</ raw >}} |
| `#### Heading level 4` | &lt;h4&gt;Heading level 1&lt;/h4&gt; | {{< raw >}}<h4>Heading level 4</h4>{{</ raw >}} |
| `##### Heading level 5` | &lt;h5&gt;Heading level 1&lt;/h5&gt; | {{< raw >}}<h5>Heading level 5</h5>{{</ raw >}} |
| `###### Heading level 6` | &lt;h6&gt;Heading level 1&lt;/h6&gt; | {{< raw >}}<h6>Heading level 6</h6>{{</ raw >}} |

## 可选语法
还可以在文本下方添加任意数量的 == 号来标识一级标题，或者 -- 号来标识二级标题。

| Markdown语法                            | HTML                       | 预览效果 |
| --------------------------------------- | -------------------------- | ---------------------------------------- |
| `Heading level 1`{{< raw >}}<br>{{</ raw >}} `===============` | {{< raw >}}&lt;h1&gt;Heading level 1&lt;/h1&gt;{{</ raw >}} | <h1>Heading level 1</h1>                 |
| `Heading level 2`{{< raw >}}<br>{{</ raw >}}`---------------`   | {{< raw >}}&lt;h2&gt;Heading level 2&lt;/h2&gt;{{</ raw >}} | <h2>Heading level 2</h2>                 |

## 最佳实践
不同的 **Markdown** 应用程序处理 `#` 和标题之间的空格方式并不一致。为了兼容考虑，请用一个空格在 `#` 和标题之间进行分隔。

| ✅  Do this           | ❌  Don't do this    |
| -------------------- | ------------------- |
| `# Here's a Heading` | `#Here's a Heading` |
