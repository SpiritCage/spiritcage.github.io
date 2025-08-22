+++
author = "Hugo Authors"
title="我的第一个文章"
slug= "first-batch"
date =  "2025-08-22"
description = "文章描述"
math = true
tags = [
    "first",
]
categories = [
    "first"
]
+++

本文提供了可在 Hugo 内容文件中使用的基本 Markdown 语法示例，同时展示了基本 HTML 元素在 Hugo 主题中的 CSS 样式效果。
<!--more-->

## 标题

以下 HTML `<h1>`—`<h6>` 元素代表六个级别的章节标题。`<h1>` 是最高级别的章节，而 `<h6>` 是最低级别。

# H1
## H2
### H3
#### H4
##### H5
###### H6

## 段落

这是一个段落示例。在 Markdown 中，段落是由一个或多个连续的文本行组成，段落之间用一个或多个空行分隔。段落内的换行会被转换为空格，如果需要在段落内强制换行，可以在行末添加两个或更多的空格。

这是另一个段落。Markdown 的段落格式非常简单直观，只需要用空行分隔不同的段落即可。这使得文档的编写和阅读都变得更加容易。

## 引用

引用元素表示从其他来源引用的内容，可以选择性地包含引用来源，引用来源必须在 `footer` 或 `cite` 元素内，也可以选择性地包含内联更改，如注释和缩写。

#### 无来源引用

> 这是一个引用示例，展示了如何在 Markdown 中使用引用格式。
> **注意** 你可以在引用中使用 *Markdown 语法*。

#### 有来源引用

> 不要通过共享内存来通信，而要通过通信来共享内存。<br>
> — <cite>Rob Pike[^1]</cite>

[^1]: 以上引用摘自 Rob Pike 在 2015 年 11 月 18 日 Gopherfest 期间的[演讲](https://www.youtube.com/watch?v=PAAkCSZUG1c)。

## 表格

表格不是核心 Markdown 规范的一部分，但 Hugo 开箱即用地支持它们。

   姓名 | 年龄
--------|------
    张三 | 27
    李四 | 23

#### 表格内的内联 Markdown

| 斜体   | 粗体     | 代码   |
| --------  | -------- | ------ |
| *斜体* | **粗体** | `代码` |

| A列                                                        | B列                                                                                                             | C列                                                                                                                                    | D列                                                 | E列                                                          | F列                                                                    |
|----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------|------------------------------------------------------------|----------------------------------------------------------------------|
| 这是一个很长的表格单元格内容示例。 | 表格可以包含很长的文本内容，Markdown 会自动处理换行和格式。 | 在复杂的表格中，每个单元格都可以包含丰富的文本内容，包括各种格式和标点符号。 | 表格是展示结构化数据的好方法。 | 可以在表格中使用各种 Markdown 语法。 | 表格的列宽会根据内容自动调整，保持良好的可读性。 |

## 代码块

#### 使用反引号的代码块

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

#### 使用四个空格缩进的代码块

    <!doctype html>
    <html lang="en">
    <head>
      <meta charset="utf-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

#### 使用 Hugo 内置高亮 shortcode 的代码块
{{< highlight html >}}
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

#### 差异代码块

```diff
[dependencies.bevy]
git = "https://github.com/bevyengine/bevy"
rev = "11f52b8c72fc3a568e8bb4a4cd1f3eb025ac2e13"
- features = ["dynamic"]
+ features = ["jpeg", "dynamic"]
```

## 列表类型

#### 有序列表

1. 第一项
2. 第二项
3. 第三项

#### 无序列表

* 列表项
* 另一个项目
* 还有一个项目

#### 嵌套列表

* 水果
  * 苹果
  * 橙子
  * 香蕉
* 乳制品
  * 牛奶
  * 奶酪

## 其他元素 — abbr, sub, sup, kbd, mark

<abbr title="图形交换格式">GIF</abbr> 是一种位图图像格式。

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

按 <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>Delete</kbd> 结束会话。

大多数<mark>蝾螈</mark>都是夜行性的，它们捕食昆虫、蠕虫和其他小生物。

## 超链接图片

[![Google](https://www.google.com/images/branding/googlelogo/1x/googlelogo_light_color_272x92dp.png)](https://google.com)