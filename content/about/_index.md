---
title: "Advanced Customisation"
weight: 13
draft: false
description: "Learn how to build Blowfish manually."
slug: "advanced-customisation"
tags: ["advanced", "css", "docs"]
series: ["Documentation"]
series_order: 13
cascade:
  showReadingTime: false
layout: "simple"
---

There are many ways you can make advanced changes to Blowfish. Read below to learn more about what can be customised and the best way of achieving your desired result.

If you need further advice, post your questions on [GitHub Discussions](https://github.com/nunocoracao/blowfish/discussions).

## Hugo project structure

Before leaping into it, first a quick note about [Hugo project structure](https://gohugo.io/getting-started/directory-structure/) and best practices for managing your content and theme customisations.

{{< alert >}}
**In summary:** Never directly edit the theme files. Only make customisations in your Hugo project's sub-directories, not in the themes directory itself.
{{< /alert >}}
