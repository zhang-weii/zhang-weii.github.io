---
permalink: /markdown/
title: "Markdown 指南"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## 标题

创建标题，在单词或短语前面添加井号。井号的数量代表了标题的级别。例如，添加三个井号即创建一个三级标题 (<h3>) (例如：### XXX)。

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

斜体标签应使文本*斜体*。

```
斜体标签应使文本*斜体*。
```

## 块引用

> 现在是引用。

```
> 现在是引用。
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

使用 `.btn` 类时，使任何文字更加突出。

```
使用 `.btn` 类时，使任何文字更加突出。
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

这是一个[链接](http://github.com "Github")。

```
这是一个[链接](http://github.com "Github")。
```

## 脚注

这是一个单行脚注[^1]， 这是一个多行脚注[^2]。

[^1]: 这是一个单行脚注。

[^2]: 这是一个多行脚注。

    缩进以将它们包含在同一脚注中。

    `{我的代码}`

    缩进以将它们包含在同一脚注中。

```
这是一个单行脚注[^1]， 这是一个多行脚注[^2]。

[^1]: 这是一个单行脚注。

[^2]: 这是一个多行脚注。

    缩进以将它们包含在同一脚注中。

    `{我的代码}`

    缩进以将它们包含在同一脚注中。
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

这个标签表示<ins>插入</ins>的文本。

```
这个标签表示<ins>插入</ins>的文本。
```

### 地址标签

<address>
  东川路800号<br /> 闵行区<br /> 上海市
</address>

```
<address>
  东川路800号<br /> 闵行区<br /> 上海市
</address>
```

### 缩写标签

The abbreviation SJTU stands for "Shanghai Jiao Tong University".

*[SJTU]: Shanghai Jiao Tong University

```
The abbreviation SJTU stands for "Shanghai Jiao Tong University".

*[SJTU]: Shanghai Jiao Tong University
```

### 细节标签

<details>
  <summary>默认关闭</summary>
  豫章故郡，洪都新府
</details>

<details open>
  <summary>默认打开</summary>
  星分翼轸，地接衡庐
</details>

### 预格式化标签

下面是一个预格式化文本

<pre>
上海交通大学 {
  饮水思源
  爱国荣校
  苟利国家生死以 岂因祸福避趋之
}
</pre>

### 下标标签

H<sub>2</sub>O

```
H<sub>2</sub>O
```

### 上标标签

E = MC<sup>2</sup>

```
E = MC<sup>2</sup>
```

### 变量标签

变量 <var>X</var>

```
变量 <var>X</var>
```

***
**脚注**

以下是本页的脚注内容, 脚注位置在 <a href="#脚注">脚注</a>.
