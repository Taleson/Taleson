<div align="center">

<!-- TODO: Replace with actual logo -->
<!-- <img src="docs/screenshots/logo.png" alt="Taleson" width="120" /> -->

# Taleson

**A story editor that makes writing game-ready JSON easy**

No coding needed. Just write your story, connect the scenes, and export.

[![Download](https://img.shields.io/github/v/release/Taleson/Taleson?label=Download&style=for-the-badge)](https://github.com/Taleson/Taleson/releases)
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge)](#license)

[한국어](README.ko.md)

</div>

---

<!-- TODO: Add hero screenshot -->
<!-- ![Taleson Editor](docs/screenshots/editor-overview.png) -->

## What is Taleson?

Taleson is a desktop application for writing structured stories as JSON data. Whether you're crafting a visual novel, a branching RPG dialogue, or a complex interactive narrative, Taleson gives you the tools to organize, visualize, and export your story.

Every aspect of your project is **configuration-driven** -- column layouts, node types, and field behaviors are all defined by your project settings, not hardcoded.

### Demo Limitations

The demo version has the following resource limits:

| Resource | Demo | Full Version |
|----------|------|--------------|
| Chapters | 2 | Unlimited |
| Nodes per chapter | 10 | Unlimited |
| Lines per node | 15 | Unlimited |
| Variables | 3 | Unlimited |
| Resources (per type) | 3 each | Unlimited |

- Only **creation/addition** is restricted. Reading existing data has no limits.
- A message is shown when a limit is reached -- nothing is silently ignored.
- **Existing data is never deleted or corrupted** by the demo restrictions.

> **Warning -- JSON contamination risk**
>
> The demo works with the same JSON project files as the full version. If you plan to edit demo project files externally (scripts, tools, or manual edits), **back up the original JSON files first**. If you notice any data corruption or unexpected changes in your JSON files, **stop immediately and report it** via [Issues](https://github.com/Taleson/Taleson/issues/new?template=bug_report.md) before continuing.

## Features

### Story Structures

| Mode | Description | Best For |
|------|-------------|----------|
| **Array** | Linear, sequential nodes | Simple scripts, tutorials |
| **Graph** | Branching node tree with connections | RPG dialogues, choice-based narratives |
| **Graph-Inline** | Graph with inline child nodes | Visual novels, conversation-heavy stories |

### Editor

- Visual node editor with drag-and-drop
- Rich text editing for dialogue and narration
- Conditional branching (variables, operators, values)
- Node type system (dialogue, narration, branch, choice, and more)
- Customizable columns and fields per project

### Export

- HTML export for standalone reading
- JSON data for game engine integration

### AI Integration (MCP)

- Built-in MCP (Model Context Protocol) server
- AI agents can read, create, and modify story nodes
- Enables AI-assisted story writing workflows

## Download

Go to [**Releases**](https://github.com/Taleson/Taleson/releases) to download the latest version.

| Platform | Format |
|----------|--------|
| Windows | `.exe` installer |
| macOS | `.dmg` |
| Linux | `.AppImage` |

## Screenshots

<!-- TODO: Add screenshots when available -->
<!--
| Home Screen | Node Editor | Graph View |
|:-----------:|:-----------:|:----------:|
| ![Home](docs/screenshots/home.png) | ![Editor](docs/screenshots/editor.png) | ![Graph](docs/screenshots/graph.png) |
-->

*Screenshots coming soon.*

## Feedback & Community

We'd love to hear from you:

- **Bug Reports** -- [Open an issue](https://github.com/Taleson/Taleson/issues/new?template=bug_report.md)
- **Feature Requests** -- [Open an issue](https://github.com/Taleson/Taleson/issues/new?template=feature_request.md)
- **General Discussion** -- [Join Discussions](https://github.com/Taleson/Taleson/discussions)

## Planned Integrations

| Engine | Status |
|--------|--------|
| RPG Maker MV/MZ | Planned |
| Ren'Py | Planned |
| Ink (Unity) | Planned |
| Yarn Spinner (Unity) | Planned |

## License

Copyright (c) 2025 Taleson. All rights reserved.

This software is proprietary. Unauthorized copying, modification, distribution, or use of this software, via any medium, is strictly prohibited without prior written permission from the author.

See [LICENSE](LICENSE) for details.
