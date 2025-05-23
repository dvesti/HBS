---
authors:
- HB
- HugoMods
categories: null
date: "2023-12-01T11:47:31+08:00"
description: 本指南介绍如何从 HB 初始主题迁移到 HB 卡主题。
draft: false
featured: true
images:
- https://example-images.razonyang.com/speed.webp?width=1920&height=1280
nav_icon:
  className: text-primary
  name: arrow-clockwise
  vendor: bootstrap
nav_weight: 2
noindex: false
pinned: false
series:
- Docs
tags:
- 迁移
title: 从 HB 新手模板迁移
---

你可以毫不费力地从[新手主题](https://github.com/hbstack/theme)迁移至卡片主题。

## 导入卡片主题模块

{{< bs/alert danger >}}
{{< markdownify >}}
你需要将 `github.com/hbstack/theme-cards` 模块置于顶部，以确保卡片主题获得更高的优先权。
{{< /markdownify >}}
{{< /bs/alert >}}

{{< bs/config-toggle "hugo" >}}
module:
  imports:
    - path: github.com/hbstack/theme-cards
{{< /bs/config-toggle >}}

## 调整参数

若要使首页幻灯片占据整行，可以通过调整置顶文章的位置为 `list`。

{{< bs/config-toggle "params" >}}
hb:
  blog:
    home:
      pinned_posts_position: list
{{< /bs/config-toggle >}}
