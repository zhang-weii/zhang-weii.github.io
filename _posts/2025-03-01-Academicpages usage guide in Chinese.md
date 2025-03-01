---
title: '学术主页使用指南(Academicpages usage guide in Chinese)'
date: 2025-03-01
permalink: /posts/2025/03/blog-post-5/
tags:
  - Academicpages
  - usage guide
  - CV
---

这是中文版学术主页使用指南，旨在搭建一个托管在 [Github](http://github.com) 的学术主页。通过开源项目 [Academicpages](https://github.com/academicpages/academicpages.github.io) 和 [Github](http://github.com) 的 [GitHub pages](https://pages.github.com) 服务我们可以搭建一个**免费**和**高度定制**的学术主页。

# 生成学术主页

1. 注册一个 GitHub 帐户。
2. Fork 开源项目 [Academicpages](https://github.com/academicpages/academicpages.github.io) 来创建副本，并且重命名为“[您的 GitHub 用户名].github.io”。
3. 点击仓库上方的 Settings，点击左侧的 Pages，修改 Branch 为 master/root,然后 save。
4. 一会儿之后，可以在本页看到， Your site is live at https://[您的 GitHub 用户名].github.io。
5. 进入生成的网址，就看到了原仓库的模板主页，下面介绍各部分如何使用和修改。

# 修改学术主页
## 修改 Site Author & Your Name Site Title
![Site Author & Your Name Site Title](/images/Blog Posts/Blog Posts 1/Site Author & Your Name Site Title.png)
* 1区个人信息由_config.yml决定：修改/隐藏/显示
* 2区homepage由_config.yml决定：修改
* 3区导航栏由_data/navigation.yml决定：修改/隐藏/显示
* 4区主页由_pages/about.md决定：字体/链接/图片

## 修改 Publications
![Publications](/images/Blog Posts/Blog Posts 1/Publications.png)
* 1区由_config.yml中的谷歌学术显示决定显示
* 2区的期刊由_publications决定：数量/内容/下载地址
* 2区的会议由_publications决定：数量/内容/下载地址

## 修改 Talks
![Talks](/images/Blog Posts/Blog Posts 1/Talks.png)
* 由_talks决定：数量/内容

## 修改 Teaching
![Teaching](/images/Blog Posts/Blog Posts 1/Teaching.png)
* 由_teaching决定：数量/内容

## 修改 Portfolio
![Portfolio](/images/Blog Posts/Blog Posts 1/Portfolio.png)
* 由_portfolio决定：数量/内容

## 修改 Blog Posts
![Blog Posts](/images/Blog Posts/Blog Posts 1/Blog Posts.png)
* 由_posts决定：数量/内容

## 修改 CV
![CV](/images/Blog Posts/Blog Posts 1/CV.png)
* 由_pages/cv.md决定

## 修改 Guide
![Guide](/images/Blog Posts/Blog Posts 1/Guide.png)
* 由_pages/markdown.md决定

## 修改 SHARE ON
![SHARE ON](/images/Blog Posts/Blog Posts 1/SHARE ON.png)
* 可以直接用
