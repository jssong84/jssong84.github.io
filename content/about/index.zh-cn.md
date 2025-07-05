---
title: 进阶自定义
weight: 13
draft: false
description: "了解如何手动构建 Blowfish。"
slug: "advanced-customisation"
tags: ["高级", "CSS", "文档"]
series: ["部署教程"]
series_order: 13
---

您可以通过多种方式对 Blowfish 进行高级自定义。请阅读下文，了解更多可自定义的内容以及实现想要效果的最佳方法。

如果您需要更多指导，请在 [GitHub Discussions](https://github.com/nunocoracao/blowfish/discussions) 上提问。

## Hugo 项目结构

在开始讨论之前，首先简要介绍一下 [Hugo 项目结构](https://gohugo.io/getting-started/directory-struct/) 以及管理内容和主题自定义的最佳方式。

{{< alert >}}
**总结：** 切勿直接编辑主题文件。一定要仅在 Hugo 项目的子目录中进行自定义，而不是在主题目录中进行自定义。
{{< /alert >}}
