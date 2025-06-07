---
title: Markdown-速查表
date: 2025-02-11T18:15:57+08:00
lastmod: 2025-02-11T19:11:57+08:00
author: 克喵爱吃卤面
avatar: /img/kemiao.jpg
authorlink: https://www.kemiao.online
cover: https://cdn.jsdelivr.net/gh/kmfx/tuchuang@main/img/markdown.png
images:
  - /img/kemiao.jpg
categories:
  - 技术分享
tags:
  - Markdown
  - 速查表
  - 语法
# nolastmod: true
# math: true
draft: false
---

> 原文位置: <https://markdown.com.cn/cheat-sheet.html#%E6%80%BB%E8%A7%88>

# 总览

Markdown 速查表提供了所有 **Markdown**
语法元素的基本解释。如果你想了解某些语法元素的更多信息，请参阅更详细的
**基本语法** 和 **扩展语法**.

## 基本语法

这些是 **John Gruber** 的原始设计文档中列出的元素。所有 **Markdown**
应用程序都支持这些元素。

| 元素 | Markdown 语法 |
|----|----|
| 标题（Heading） | \# H1 一级标题{{< raw >}}<br>{{</ raw >}} \## H2 二级标题{{< raw >}}<br>{{</ raw >}} \### H3 三级标题 |
| 粗体（Bold） | \*\*bold text\*\* |
| 斜体（Italic） | \*italicized text\* |
| 引用块（Blockquote） | \> blockquote |
| 有序列表（Ordered List） | 1\. First item{{< raw >}}<br>{{</ raw >}} 2. Second item{{< raw >}}<br>{{</ raw >}} 3. Third item |
| 无序列表（Unordered List） | \- First item{{< raw >}}<br>{{</ raw >}} - Second item{{< raw >}}<br>{{</ raw >}} - Third item |
| 代码（Code） | \`code\` |
| 分隔线（Horizontal Rule） | `---` |
| 链接（Link） | \[title\](<https://www.example.com>) |
| 图片（Image） | \![alt text\](image.jpg) |

## 扩展语法

这些元素通过添加额外的功能扩展了基本语法。但是，并非所有 **Markdown**
应用程序都支持这些元素。

| 元素 | Markdown 语法 |
|:--:|:---|
| 表格（Table） | {{< raw >}}<code>| Syntax | Description |</code>{{< raw >}}<br>{{</ raw >}}<code>| -----------  |  -----------  |</code>{{< raw >}}<br>{{</ raw >}}<code>| Header  |  Title  |</code>{{< raw >}}<br>{{</ raw >}}<code>| Paragraph | Text |</code>{{</ raw >}} |
| 代码块（Fenced Code Block） | {{< raw >}}<code>```</code>{{< raw >}}<br>{{</ raw >}}<code>{</code>{{< raw >}}<br>{{</ raw >}}<code>"firstName": "John",</code>{{< raw >}}<br>{{</ raw >}}<code>"lastName": "Smith",</code><br/><code>"age": 25</code>{{< raw >}}<br>{{</ raw >}}<code>}</code>{{< raw >}}<br>{{</ raw >}}<code>```</code>{{</ raw >}} |
| 脚注（Footnote） | Here’s a sentence with a footnote. `[^1]`{{< raw >}}<br/>{{</ raw >}}`[^1]`: This is the footnote. |
| 标题编号（Heading ID） | \### My Great Heading {#custom-id} |
| 定义列表（Definition List） | term{{< raw >}}<br/>{{</ raw >}}: definition |
| 任务列表（Task List）| `- [x] Write the press release`{{< raw >}}<br/>{{</ raw >}}`- [ ] Update the website`{{< raw >}}<br/>{{</ raw >}}`- [ ] Contact the media` |
