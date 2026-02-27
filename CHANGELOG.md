# Changelog

All notable changes to Taleson will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/),
and this project adheres to [Semantic Versioning](https://semver.org/).

## [1.0.2] - 2026-02-28

### Added
- Inline system unification — all editors now support separateCollection with $type discriminator pattern
- Inline type group reorder buttons in Card and Compact editors
- Dynamic chapter creation modal with chapterTableColumns-based field inputs
- Export chapter selection UI for per-chapter document export
- Reader view separateCollection dialogue type filtering and inline reference resolver
- Field.InlineType namespace for role-based inline type accessors
- InlineInfoDisplay in all diagram node types (Variable, If, End, custom)
- ~93 missing i18n keys across 4 locales (project namespace)
- inputType change blocking when column has existing data
- Path B to Path A inline data migration (automatic on project load)
- MCP auto-detection: project path and language resolved dynamically from editor bridge (env vars no longer required)
- Custom field export support for game tool exporters (Ren'Py, Naninovel, Dialogic)
- Default image paths in all 12 visual game tool template configs
- HTML export option in Settings tab

### Changed
- Inline system: removed Path B, unified to single separateCollection path
- graph-inline templates rebuilt with $type discriminator-based polymorphic collection pattern
- All hardcoded field keys replaced with config-driven Field accessor lookups
- EdgeContextMenu uses config-based dynamic node types instead of hardcoded list
- CustomNode uses isNodeTypeRole for type checks instead of string comparison
- Behavior editors use explicit ColumnRole types for skipRoles
- Template role mappings unified to role 'text' for choice children
- MCP nodeTypeColumn resolution aligned with editor (role-based)
- MCP dead code cleanup: removed signature-mismatched wrappers and unused re-exports
- Export handlers unified into useExportHandlers hook (single source of truth for MenuBar and Settings)

### Fixed
- Data safety: atomic file writes, debounce flush before save, optimistic locking
- Undo corruption: deep clone nodes before mutation to prevent snapshot pollution
- Dangling references cleaned up on node deletion in graph mode
- Diagram edge connections now reflect immediately on drag-connect
- TOCTOU race condition and IPC error sanitization
- Duplicate ID guards for addResourceType and addChapter
- NodeType role duplicate check on import and validation
- Array column data corruption in custom node editors
- getNodeTypeMap crash guard for nodeTypes missing role field
- ChoiceFields role corrected from 'content' to 'text'
- columnOrder defensive filtering for missing separateCollection columns
- Custom node addition duplicate key and config errors in diagram
- PathGuard scope registration for recent project opens
- Field value coercion to dataType at input time
- Game tool exporters aligned with official engine format specifications (Ren'Py label start, Yarn Spinner inline conditionals, Dialogic .dtl format, Naninovel choice separation)
- Ren'Py entry node label collision resolved with "start" remapping
- Naninovel inline effects disabled for choice nodes
- Runtime errors in game tool export: digit-starting ID sanitization, Naninovel string quoting, Dialogic .dch Godot resource format

### Removed
- Dead code: validateProjectConfig.ts, InlineDialogueEditor.tsx, exportHelpers.ts, resourceCollector.ts, deprecated exports
- Outdated documentation: completed specs, duplicate reports

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
