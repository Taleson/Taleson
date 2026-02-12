<div align="center">

<!-- TODO: Replace with actual logo -->
<!-- <img src="docs/screenshots/logo.png" alt="Taleson" width="120" /> -->

# Taleson

**轻松制作游戏用JSON的故事编辑器**

无需编码。只需编写故事、连接场景并导出。

[![Download](https://img.shields.io/github/v/release/Taleson/Taleson?label=Download&style=for-the-badge)](https://github.com/Taleson/Taleson/releases)
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge)](#license)

[English](README.md) | [한국어](README.ko.md) | [日本語](README.ja.md)

</div>

---

<!-- TODO: Add hero screenshot -->
<!-- ![Taleson Editor](docs/screenshots/editor-overview.png) -->

## Taleson是什么？

Taleson是一款用于将结构化故事编写为JSON数据的桌面应用程序。无论您是制作视觉小说、分支RPG对话还是复杂的互动叙事，Taleson都能为您提供整理、可视化和导出故事的工具。

项目的各个方面都是**配置驱动的** -- 列布局、节点类型和字段行为都由项目设置定义，而非硬编码。

**支持语言：** English, Korean (한국어), Japanese (日本語), Chinese (中文)

### 演示版限制

演示版具有以下资源限制：

| 资源 | 演示版 | 完整版 |
|----------|------|--------------|
| 章节 | 2个 | 无限制 |
| 每章节点 | 10个 | 无限制 |
| 每节点行数 | 15行 | 无限制 |
| 变量 | 3个 | 无限制 |
| 资源（每种类型） | 各3个 | 无限制 |

- 仅限制**创建/添加**。读取现有数据没有限制。
- 达到限制时会显示消息 -- 不会被忽略。
- **现有数据永远不会被删除或损坏**。

> **警告 -- JSON污染风险**
>
> 演示版使用与完整版相同的JSON项目文件。如果您计划在外部编辑演示项目文件（脚本、工具或手动编辑），**请先备份原始JSON文件**。如果您发现JSON文件中的数据损坏或意外更改，**请立即停止**并通过[Issues](https://github.com/Taleson/Taleson/issues/new?template=bug_report.md)报告后再继续。

### 定价

- **演示版：** 有资源限制的免费版本（永久免费）
- **完整版：** 即将在Steam Early Access上付费发布

演示版将永久保持免费。具有无限功能的完整版将在Steam上付费购买。

## 功能

### 故事结构

| 模式 | 描述 | 最适合 |
|------|-------------|----------|
| **Array** | 线性、顺序节点 | 简单脚本、教程 |
| **Graph** | 带连接的分支节点树 | RPG对话、基于选择的叙事 |
| **Graph-Inline** | 带内联子节点的图表 | 视觉小说、对话密集型故事 |

### 编辑器

- 拖放式可视节点编辑器
- 对话和旁白的富文本编辑
- 条件分支（变量、运算符、值）
- 节点类型系统（对话、旁白、分支、选择等）
- 每个项目可自定义的列和字段

### 导出

- 用于独立阅读的HTML导出
- 用于游戏引擎集成的JSON数据

### AI集成（MCP）

- 内置MCP（Model Context Protocol）服务器
- AI代理可以读取、创建和修改故事节点
- 实现AI辅助故事创作工作流程

## 下载

[**下载演示版 v1.0.0**](https://github.com/Taleson/Taleson/releases/tag/v1.0.0-demo)

| 类型 | 文件 | 备注 |
|------|------|------|
| **便携版（推荐）** | `Taleson Demo x.x.x.exe` | 无需安装。在应用程序仍处于早期开发阶段时推荐使用。 |
| 安装程序 | `Taleson Demo Setup x.x.x.exe` | Windows安装程序。MCP（AI集成）支持所需。 |

## 截图

<!-- TODO: Add screenshots when available -->
<!--
| 主屏幕 | 节点编辑器 | 图表视图 |
|:-----------:|:-----------:|:----------:|
| ![Home](docs/screenshots/home.png) | ![Editor](docs/screenshots/editor.png) | ![Graph](docs/screenshots/graph.png) |
-->

*截图即将推出。*

## 反馈与社区

我们很乐意听取您的意见：

- **错误报告** -- [提交Issue](https://github.com/Taleson/Taleson/issues/new?template=bug_report.md)
- **功能请求** -- [提交Issue](https://github.com/Taleson/Taleson/issues/new?template=feature_request.md)
- **一般讨论** -- [加入讨论](https://github.com/Taleson/Taleson/discussions)

## 计划集成

| 引擎 | 状态 |
|--------|--------|
| RPG Maker MV/MZ | 计划中 |
| Ren'Py | 计划中 |
| Ink (Unity) | 计划中 |
| Yarn Spinner (Unity) | 计划中 |

## 许可证

Copyright (c) 2025 Taleson. All rights reserved.

本软件为专有软件。未经作者事先书面许可，严禁通过任何媒介对本软件进行未经授权的复制、修改、分发或使用。

详情请参见[LICENSE](LICENSE)。
