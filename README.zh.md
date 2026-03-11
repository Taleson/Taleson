<div align="center">

# Taleson

**轻松创建游戏用JSON故事的编辑器**

无需编程。编写故事、连接场景、直接导出。

[![下载试玩版](https://img.shields.io/badge/%E4%B8%8B%E8%BD%BD-Demo%20v1.0.3-blue?style=for-the-badge)](https://github.com/Taleson/Taleson/releases/latest)
[![Steam](https://img.shields.io/badge/%E6%84%BF%E6%9C%9B%E5%8D%95-Steam-000000?style=for-the-badge&logo=steam)](https://store.steampowered.com/app/4507640/)
[![许可证](https://img.shields.io/badge/%E8%AE%B8%E5%8F%AF%E8%AF%81-All%20Rights%20Reserved-red?style=for-the-badge)](#许可证)

[English](README.md) | [한국어](README.ko.md) | [日本語](README.ja.md)

</div>

---

> **这是免费试玩版。** 部分功能有限制。在[Steam](https://store.steampowered.com/app/4507640/)上将正式版加入愿望单，获取发布通知。

## 什么是Taleson？

Taleson是一款用于将结构化故事编写为JSON数据的桌面应用程序。无论您是在创作视觉小说、分支RPG对话还是复杂的交互式叙事，Taleson都能为您提供工具来组织、可视化和导出故事。

项目的所有元素都是**配置驱动型**的。列布局、节点类型、字段行为都通过项目设置来定义。

## 截图

| 仪表盘 | 阅读视图 |
|:------:|:-------:|
| ![仪表盘](docs/screenshots/screenshot_01.png) | ![阅读](docs/screenshots/screenshot_02.png) |

| 紧凑编辑器 | 图表视图 |
|:---------:|:-------:|
| ![紧凑](docs/screenshots/screenshot_03.png) | ![图表](docs/screenshots/screenshot_04.png) |

| 卡片编辑器 |
|:---------:|
| ![卡片](docs/screenshots/screenshot_05.png) |

## 主要功能

### 故事结构

| 模式 | 说明 | 适用场景 |
|------|------|---------|
| **Array** | 线性、顺序节点 | 简单脚本、教程 |
| **Graph** | 分支节点树 | RPG对话、选择式叙事 |
| **Graph-Inline** | 带内联子节点的图 | 视觉小说、对话密集型故事 |

### 编辑器

- 7种编辑视图：卡片、紧凑、图表、脚本、阅读、JSON、草稿
- 拖放式可视化节点编辑器
- 条件分支（变量、运算符、值）
- 节点类型系统（对话、选择、条件、变量、结局、自定义类型）
- 按项目自定义列和字段
- 故事统计仪表盘

### 导出

- HTML导出（独立阅读）
- JSON数据（游戏引擎集成）

### AI集成（MCP）

- 内置MCP（Model Context Protocol）服务器
- AI代理可以读取、创建和修改故事节点
- 兼容22+种AI工具（Claude、Cursor、Windsurf、Copilot、JetBrains等）

### 多语言支持

- 完整UI支持4种语言：英语、韩语、日语、简体中文
- 每种语言8个项目模板

## 试玩版限制

| 功能 | 试玩版 | 正式版 |
|------|--------|--------|
| 章节 | 2个 | 无限制 |
| 每章节节点 | 10个 | 无限制 |
| 每节点对话 | 15条 | 无限制 |
| 变量 | 3个 | 无限制 |
| 每类型资源 | 3个 | 无限制 |

## 下载

前往[**Releases**](https://github.com/Taleson/Taleson/releases/latest)页面下载试玩版。

| 平台 | 格式 |
|------|------|
| Windows | `.exe` 安装程序 / 便携版 |

## 游戏引擎集成计划

| 引擎 | 状态 |
|------|------|
| RPG Maker MV/MZ | 计划中 |
| Ren'Py | 计划中 |
| Ink (Unity) | 计划中 |
| Yarn Spinner (Unity) | 计划中 |

## 反馈与社区

我们期待您的意见：

- **Bug报告** -- [提交Issue](https://github.com/Taleson/Taleson/issues/new?template=bug_report.md)
- **功能请求** -- [提交Issue](https://github.com/Taleson/Taleson/issues/new?template=feature_request.md)
- **自由讨论** -- [加入Discussions](https://github.com/Taleson/Taleson/discussions)

## 许可证

Copyright (c) 2025-2026 Taleson. All rights reserved.

本软件为专有软件。未经作者事先书面许可，严禁复制、修改、分发或使用本软件。

详情请参见[LICENSE](LICENSE)。
