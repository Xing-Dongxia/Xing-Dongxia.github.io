---
title: Hugo Module 使用方法学习
description: 这个静态网页生成使用的Hugo Module
slug: Hugo Module
date: 2023-09-03 21:03:00+0000
image: cover.jpg
categories:
    - Hugo
tags:
    - Hugo
weight: 1
---

参考 [Hugo Modules: everything you need to know](https://www.thenewdynamic.com/article/hugo-modules-everything-from-imports-to-create/) ,学习Module的使用。

[hugo-theme-stack-stater](https://github.com/CaiJimmy/hugo-theme-stack-starter) 是一个已经被初始化为Hugo Module的仓库，因此会生成两个文件go.mod和go.sum。在config中module.imports.path定义的链接mount了一个包含Hugo主题和布局的GitHub仓库。可以尝试同时mount多个仓库的指定文件到自己仓库的指定目录下。

Hugo Module 是一种从其他公共仓库引入文件到自己的Hugo工程的方法，他同时可以管理各种引入文件的版本，当然这是基于引入仓库的良好维护的。在开源环境中，一些静态网页被使用的模块可以被反复使用，而不用在本地工程中存放，又或者你可以通过这种方式方便的根据引用仓库的迭代，更新优化自己的网站页面。

如果担心引入的仓库无法连接，把需要使用的layout放在自己的工程下也是一个好的选择。

> Photo by [Pawel Czerwinski](https://unsplash.com/@pawel_czerwinski) on [Unsplash](https://unsplash.com/)
