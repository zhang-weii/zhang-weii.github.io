---
permalink: /markdown/
title: "Markdown"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---


# Markdown 指南

## 标题

要创建标题，请在单词或短语前面添加井号 (#) 。井号的数量代表了标题的级别。例如，添加三个井号即创建一个三级标题 (<h3>) (例如：### My Header)。

# 标题一

```
# 标题一
```

## 标题二

```
## 标题二
```

### 标题三

```
### 标题三
```

## 分隔线

---

```
---
```

## 强调标签

### 粗体

此标签显示**粗体**文本。

```
此标签显示**粗体**文本。
```

### 斜体

强调标签应使文本*斜体*。

```
强调标签应使文本*斜体*。
```

## 块引用

单行块引用：

```
> 引用很酷。
```

## 注意

**小心！** 可以通过将 `{: .notice}` 附加到段落来添加注意。
{: .notice}

```
**小心！** 可以通过将 `{: .notice}` 附加到段落来添加注意。
{: .notice}
```

## 定义列表

定义列表一标题
:   定义列表一

定义列表二标题
:   定义列表二

```
定义列表一标题
:   定义列表一

定义列表二标题
:   定义列表二
```

## 无序列表（嵌套）

  - 列表项目一 
      - 列表项目一 
          - 列表项目一 
          - 列表项目二
      - 列表项目二
  - 列表项目二

```
  - 列表项目一 
      - 列表项目一 
          - 列表项目一 
          - 列表项目二
      - 列表项目二
  - 列表项目二
```

## 有序列表（嵌套）

  1. 列表项目一 
      1. 列表项目一 
          1. 列表项目一
          2. 列表项目二
      2. 列表项目二
  2. 列表项目二

```
  1. 列表项目一 
      1. 列表项目一 
          1. 列表项目一
          2. 列表项目二
      2. 列表项目二
  2. 列表项目二
```

## 表格

| 标题1 | 标题2 | 标题3 |
|:--------|:-------:|--------:|
| 项目1   | 项目2   | 项目3   |
| 项目4   | 项目5   | 项目6   |

```
| 标题1 | 标题2 | 标题3 |
|:--------|:-------:|--------:|
| 项目1   | 项目2   | 项目3   |
| 项目4   | 项目5   | 项目6   |
```

## 代码/按钮

应用 `.btn` 类时，使任何文字更加突出。

```
应用 `.btn` 类时，使任何文字更加突出。
```

## 代码块

```
    <html>
      <head>
      </head>
    </html>
```

```
\```
    <html>
      <head>
      </head>
    </html>
\```
```

## 链接

这是一个[链接](http://github.com "Github")的例子。

```
这是一个[链接](http://github.com "Github")的例子。
```

## 脚注

这是一个简单的脚注[^1]， 这是一个更长的脚注[^bignote]。

[^1]: 这是第一个脚注。

[^bignote]: 这是一个有多个段落和代码的。

    缩进段落以将它们包含在脚注中。

    `{我的代码}`

    添加尽可能多的段落。

```
这是一个简单的脚注[^1]， 这是一个更长的脚注[^bignote]。

[^1]: 这是第一个脚注。

[^bignote]: 这是一个有多个段落和代码的。

    缩进段落以将它们包含在脚注中。

    `{我的代码}`

    添加尽可能多的段落。
```

## 图片

![500x300.png](/images/500x300.png)

```
![500x300.png](/images/500x300.png)
```

## HTML 标签

### 删除标签

这个标签可以让你<strike>删除</strike>文本。

```
这个标签可以让你<strike>删除</strike>文本。
```

### 插入标签

此标记应表示<ins>插入</ins>的文本。

```
此标记应表示<ins>插入</ins>的文本。
```

### 地址标签

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

```
<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>
```

### 缩写标签

The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets

```
The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets
```

### 代码标签

```python
print('Hello World!')
```

```
\```python
print('Hello World!')
\```
```

### 细节标签

<details>
  <summary>Collapsed by default</summary>
  This section was collapsed by default!
</details>

```HTML
<details>
  <summary>Collapsed by default</summary>
  This section was collapsed by default!
</details>
```

```
\```HTML
<details>
  <summary>Collapsed by default</summary>
  This section was collapsed by default!
</details>
\```
```

或者

<details open>
  <summary>Open by default</summary>
  This section is open by default thanks to open in the &lt;details open&gt; tag!
</details>

```
<details open>
  <summary>Open by default</summary>
  This section is open by default thanks to open in the &lt;details open&gt; tag!
</details>
```

### 预格式化标签

This tag styles large blocks of code.

<pre>
.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

```
<pre>
.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>
```

### 引用标签

<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer

```
<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer
```

### 下标标签

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

```
Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.
```

### 上标标签

Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.

```
Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.
```

### 变量标签

This allows you to denote <var>variables</var>.

```
This allows you to denote <var>variables</var>.
```

***
**脚注**

The footnotes in the page will be returned following this line, return to the section on <a href="#脚注">Markdown Footnotes</a>.
