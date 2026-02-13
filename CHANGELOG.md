# Changelog

All notable changes to Taleson will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/),
and this project adheres to [Semantic Versioning](https://semver.org/).

## [1.0.1] - 2026-02-13

### Added
- Rough draft editor with tab and floating panel modes
- Demo mode limits and portable build support
- Demo release workflow and dynamic author footer
- i18n support for MCP server language-aware output
- Japanese/Chinese locale templates for all 8 templates
- Game tool exporters and demo build infrastructure
- Internationalization infrastructure (4 languages × 8 namespaces)

### Changed
- MCP integration: expanded supported tools from 14 to 22 (added JetBrains, OpenAI Codex, Gemini CLI, Amazon Q, Roo Code, Kilo Code, Augment Code, Warp)
- MCP config generator now outputs tool-specific formats (JSON/TOML/YAML) with correct config keys per tool
- Removed ChatGPT Desktop from MCP list (does not support local stdio)
- Migrated all hardcoded Korean strings to i18n
- Restructured project creation flow with template dialog

### Fixed
- Inline dialogue add silently failing on choice nodes
- Missing dataType/uiComponent in templates and broken references
- All 51 E2E test failures after i18n migration
- JSON data contamination from unrelated columns
- Read-only scope for template file access in PathGuard

## [1.0.0] - 2025-12-01
### Added
- Initial public release
