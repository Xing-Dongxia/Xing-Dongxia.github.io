---
title: 【双语系列】双语博客设置
description: 双语系列设置
slug: DL_post1
date: 2023-09-07 00:00:00+0000
categories:
    - Double Language
tags:
    - Hugo
---

双语系列的第一篇文章，通过简单的适配，同一篇文章可以切换中英两个版本：

这个是Hugo theme 的一个功能，在我使用的这个主题：[**stack**](https://github.com/CaiJimmy/hugo-theme-stack)中适用，其他主题需要却定是否定义了这一功能。当然也可能是Hugo自适应的功能。

如果你使用的是和我一样的主题，在使用相同配置文件的条件下，只要在不同语言对应根目录的/content/language/post中使用同样文件夹名，那么在生成的文章页中就会出现语言切换按钮了。

在我的仓库中：

- content/cn/post/blog_name_1/index.md
- content/en/post/blog_name_1/index.md

这两篇在不同目录下，但具有相同文章名文件夹的博客可以使用语言切换功能。


