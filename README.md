<div align="center">

# Taleson

**A story editor that makes writing game-ready JSON easy**

No coding needed. Just write your story, connect the scenes, and export.

[![Download Demo](https://img.shields.io/badge/Download-Demo%20v1.0.4-blue?style=for-the-badge)](https://github.com/Taleson/Taleson/releases/latest)
[![Steam](https://img.shields.io/badge/Wishlist-Steam-000000?style=for-the-badge&logo=steam)](https://store.steampowered.com/app/4507640/)
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge)](#license)

[한국어](README.ko.md) | [日本語](README.ja.md) | [中文](README.zh.md)

</div>

---

> **This is a free demo.** Some features have limits. Wishlist the full version on [Steam](https://store.steampowered.com/app/4507640/) to get notified on release.

## What is Taleson?

Taleson is a desktop application for writing structured stories as JSON data. Whether you're crafting a visual novel, a branching RPG dialogue, or a complex interactive narrative, Taleson gives you the tools to organize, visualize, and export your story.

Every aspect of your project is **configuration-driven** -- column layouts, node types, and field behaviors are all defined by your project settings, not hardcoded.

## Screenshots

| Dashboard | Reader View |
|:---------:|:-----------:|
| ![Dashboard](docs/screenshots/screenshot_01.png) | ![Reader](docs/screenshots/screenshot_02.png) |

| Compact Editor | Diagram View |
|:--------------:|:------------:|
| ![Compact](docs/screenshots/screenshot_03.png) | ![Diagram](docs/screenshots/screenshot_04.png) |

| Card Editor |
|:-----------:|
| ![Card](docs/screenshots/screenshot_05.png) |

## Features

### Story Structures

| Mode | Description | Best For |
|------|-------------|----------|
| **Array** | Linear, sequential nodes | Simple scripts, tutorials |
| **Graph** | Branching node tree with connections | RPG dialogues, choice-based narratives |
| **Graph-Inline** | Node-first dialogue with inline reactions on choices | Visual novels, conversation-heavy stories |

### Editor

- 7 editing views: Card, Compact, Diagram, Script, Reader, JSON, Draft
- Visual node editor with drag-and-drop
- Conditional branching (variables, operators, values)
- Node type system (dialogue, choice, condition, variable, end, and custom types)
- Customizable columns and fields per project
- Story statistics dashboard

### Export

- Game script export: Ren'Py (`.rpy`), Ink (`.ink`), Yarn Spinner (`.yarn`), Dialogic 2 (`.dtl`), Naninovel (`.nani`)
- Document export: HTML, Markdown, Word (`.docx`), Excel (`.xlsx`)
- JSON data for engine integration and custom pipelines

### AI Integration (MCP)

- Built-in MCP (Model Context Protocol) server
- AI agents can read, create, and modify story nodes
- Packaged Taleson can be used as a local MCP server without requiring a separate Node.js install
- Settings can generate client-specific MCP snippets and support portable executable path overrides
- Curated setup guides are included for Claude Desktop, Cursor, VS Code (Copilot), Windsurf, Google Antigravity, Claude Code, OpenAI Codex CLI, OpenAI Codex App, and Gemini CLI

### Internationalization

- Full UI support for 4 languages: English, Korean, Japanese, Chinese (Simplified)
- 8 project templates per language

## Demo Limitations

| Feature | Demo | Full Version |
|---------|------|--------------|
| Chapters | 2 | Unlimited |
| Nodes per chapter | 10 | Unlimited |
| Dialogues per node | 15 | Unlimited |
| Variables | 3 | Unlimited |
| Resources per type | 3 | Unlimited |

## Download

Go to [**Releases**](https://github.com/Taleson/Taleson/releases/latest) to download the demo.

| Platform | Format |
|----------|--------|
| Windows | `.exe` installer / portable |

## Included Tool Templates & Export Targets

| Tool | Template | Export |
|------|----------|--------|
| Ren'Py | Included | `.rpy` |
| Ink | Included | `.ink` |
| Yarn Spinner | Included | `.yarn` |
| Dialogic 2 | Included | `.dtl` |
| Naninovel | Included | `.nani` |

## Feedback & Community

We'd love to hear from you:

- **Bug Reports** -- [Open an issue](https://github.com/Taleson/Taleson/issues/new?template=bug_report.md)
- **Feature Requests** -- [Open an issue](https://github.com/Taleson/Taleson/issues/new?template=feature_request.md)
- **General Discussion** -- [Join Discussions](https://github.com/Taleson/Taleson/discussions)

## License

Copyright (c) 2025-2026 Taleson. All rights reserved.

This software is proprietary. Unauthorized copying, modification, distribution, or use of this software, via any medium, is strictly prohibited without prior written permission from the author.

See [LICENSE](LICENSE) for details.
