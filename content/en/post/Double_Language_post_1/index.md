---
title: 【Double Language】Setting a post with multiple language
description: Content mutiple language setting
slug: DL_post1
date: 2023-09-07 00:00:00+0000
categories:
    - Double Language
tags:
    - Hugo
---

In this article, you can learn how to set your post with more than one language. A reader can choose the disire language with Language button.

Language switch is a function of the deployed theme：[**stack**](https://github.com/CaiJimmy/hugo-theme-stack). If you apply other themes, you should test if the function works same with theme Stack. I'm not sure if this function will always be deployed by Hugo automatically.

To apply the language switch fuction, you should set you language configeration into multiple model. At the root of different language /content/language/post, you should use the same dir_name in the different languages which you designed can be switched with each other, then you activate language switch function.

In my repository：

- content/cn/post/blog_name_1/index.md
- content/en/post/blog_name_1/index.md

This two articles are in Chinese and English respectively. They can switch to each other as they share the blog directory name with blog_name_1. 
