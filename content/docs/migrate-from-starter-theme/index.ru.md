---
authors:
- HB
- HugoMods
categories: null
date: "2023-12-01T11:47:31+08:00"
description: This guide shows how to migrate to the HB cards theme from the HB starter
  theme.
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
- Migration
title: Migrate from HB Starter Theme
---

You can migrate to cards theme from the [starter theme](https://github.com/hbstack/theme) effortlessly within two steps.

## Import the Cards Theme Module

{{< bs/alert danger >}}
{{< markdownify >}}
You'll ve to put the module `github.com/hbstack/theme-cards` on the ___top___, to make sure that the cards theme gets higher priority.
{{< /markdownify >}}
{{< /bs/alert >}}

{{< bs/config-toggle "hugo" >}}
module:
  imports:
    - path: github.com/hbstack/theme-cards
{{< /bs/config-toggle >}}

## Tweak Parameters

To make the carousel to take whole row on homepage, you'll need to tweak the position of pinned posts.

{{< bs/config-toggle "params" >}}
hb:
  blog:
    home:
      pinned_posts_position: list
{{< /bs/config-toggle >}}
