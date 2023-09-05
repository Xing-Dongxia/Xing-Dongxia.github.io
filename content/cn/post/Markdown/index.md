---
title: Markdown使用 (1)
description: Markdown分段，字体和超链接
date: 2023-09-04 00:00:00+0000
categories:
    - Code
tags:
    - Markdown
---

Markdown不应该成为限制你写作或者创作因素，应该做到使用它，再熟悉它。Markdown的一个优点是，格式的规整和一致，让读者和作者都能够清晰的看到文章的结构和重点，目录和超链接能够方便的做到检索和跳转。能做到这一点，Markdown已经很好的完了它的使命。

## 结构

最常用的结构是标题和列表：

- 标题：你可以在右边的目录里通过标题快速定位到目标内容的位置，这也是使用Markdown配合Hugo结构的好处。

```markdown
## 这是一个二号标题
### 这是一个三号标题
```

- 列表：

```markdown
- 列表项1
- 列表项2
```

---
## 字体

我最常用的字体形式是**加粗**和*斜体*

```markdown
我最常用的字体形式是**加粗**和*斜体*
```

---
## 超链接

超链接可以让你快速跳转到需要的地址，需要配合 `[]`和`()` 使用。 

查看更详细的指导，[**点点我**](https://www.markdownguide.org/basic-syntax/#links)。

```markdown
查看更详细的指导，[**点点我**](https://www.markdownguide.org/basic-syntax/#links)。
```

如果你想直接显示出链接，可以使用`<>`: <https://www.markdownguide.org/>
