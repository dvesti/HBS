---
authors:
- HB
- HugoMods
categories: null
date: "2023-11-02T11:47:31+08:00"
description: 在其他板块使用文档布局的指南。
draft: false
featured: true
images:
- https://images.pexels.com/photos/1629212/pexels-photo-1629212.jpeg?auto=compress&cs=tinysrgb&w=1600
nav_icon:
  color: green
  name: columns
  vendor: bootstrap
nav_weight: 1000
noindex: false
pinned: false
series:
- 笔记
tags:
- 布局
title: 于其他板块使用文档布局
type: docs
---

## 背景

默认情况下，文档布局应用于 `docs` 板块，在大多数情况下，将多个数字花园分割成不同的板块是合理的，例如多个项目的文档、指南和笔记。

## 如何在其他部分使用文档布局？

要在 `docs` 以外的板块使用文档布局，你需要做的是在前言中将 `type` 设置为 `docs`。

{{< bs/config-toggle >}}
type: docs
{{< /bs/config-toggle >}}
