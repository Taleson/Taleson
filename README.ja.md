<div align="center">

# Taleson

**ゲーム用JSONストーリーを簡単に作成するエディタ**

コーディング不要。ストーリーを書いて、シーンをつなげて、エクスポート。

[![デモダウンロード](https://img.shields.io/badge/%E3%83%80%E3%82%A6%E3%83%B3%E3%83%AD%E3%83%BC%E3%83%89-Demo%20v1.0.4-blue?style=for-the-badge)](https://github.com/Taleson/Taleson/releases/latest)
[![Steam](https://img.shields.io/badge/%E3%82%A6%E3%82%A3%E3%83%83%E3%82%B7%E3%83%A5%E3%83%AA%E3%82%B9%E3%83%88-Steam-000000?style=for-the-badge&logo=steam)](https://store.steampowered.com/app/4507640/)
[![ライセンス](https://img.shields.io/badge/%E3%83%A9%E3%82%A4%E3%82%BB%E3%83%B3%E3%82%B9-All%20Rights%20Reserved-red?style=for-the-badge)](#ライセンス)

[English](README.md) | [한국어](README.ko.md) | [中文](README.zh.md)

</div>

---

> **これは無料デモ版です。** 一部の機能に制限があります。[Steam](https://store.steampowered.com/app/4507640/)で製品版をウィッシュリストに追加して、リリース通知を受け取りましょう。

## Talesonとは？

Talesonは、JSONデータとして構造化されたストーリーを作成するためのデスクトップアプリケーションです。ビジュアルノベル、分岐型RPGダイアログ、複雑なインタラクティブナラティブなど、あらゆるストーリーを体系的に構成、可視化、エクスポートできます。

プロジェクトのすべての要素は**設定駆動型**です。カラムレイアウト、ノードタイプ、フィールドの動作はすべてプロジェクト設定で定義されます。

## スクリーンショット

| ダッシュボード | リーダービュー |
|:------------:|:----------:|
| ![ダッシュボード](docs/screenshots/screenshot_01.png) | ![リーダー](docs/screenshots/screenshot_02.png) |

| コンパクトエディタ | ダイアグラムビュー |
|:---------------:|:-------------:|
| ![コンパクト](docs/screenshots/screenshot_03.png) | ![ダイアグラム](docs/screenshots/screenshot_04.png) |

| カードエディタ |
|:----------:|
| ![カード](docs/screenshots/screenshot_05.png) |

## 主な機能

### ストーリー構造

| モード | 説明 | 最適な用途 |
|--------|------|-----------|
| **Array** | 線形・順次ノード | シンプルなスクリプト、チュートリアル |
| **Graph** | 分岐ノードツリー | RPGダイアログ、選択肢ベースのナラティブ |
| **Graph-Inline** | ノードの台詞を軸に、選択肢へインライン反応を重ねる構造 | ビジュアルノベル、会話中心のストーリー |

### エディタ

- 7つの編集ビュー: カード、コンパクト、ダイアグラム、スクリプト、リーダー、JSON、ドラフト
- ドラッグ＆ドロップ対応ビジュアルノードエディタ
- 条件分岐（変数、演算子、値）
- ノードタイプシステム（ダイアログ、選択肢、条件、変数、エンディング、カスタムタイプ）
- プロジェクト別にカスタマイズ可能なカラムとフィールド
- ストーリー統計ダッシュボード

### エクスポート

- ゲームスクリプト書き出し: Ren'Py (`.rpy`)、Ink (`.ink`)、Yarn Spinner (`.yarn`)、Dialogic 2 (`.dtl`)、Naninovel (`.nani`)
- ドキュメント書き出し: HTML、Markdown、Word (`.docx`)、Excel (`.xlsx`)
- JSONデータ（ゲームエンジン連携やカスタムパイプライン向け）

### AI連携（MCP）

- 内蔵MCP（Model Context Protocol）サーバー
- AIエージェントがストーリーノードの読み取り、作成、編集に対応
- パッケージ版TalesonだけでローカルMCPサーバーを実行でき、別途Node.jsをインストールする必要はありません
- 設定タブでクライアント別のMCP設定スニペットを生成でき、ポータブル実行ファイルのパス上書きにも対応
- Claude Desktop、Cursor、VS Code (Copilot)、Windsurf、Google Antigravity、Claude Code、OpenAI Codex CLI、OpenAI Codex App、Gemini CLI 向けの設定ガイドを同梱

### 多言語対応

- 4言語完全UI対応: 英語、韓国語、日本語、中国語（簡体字）
- 言語ごとに8つのプロジェクトテンプレート

## デモ版の制限

| 機能 | デモ版 | 製品版 |
|------|--------|--------|
| チャプター | 2 | 無制限 |
| チャプターあたりのノード | 10 | 無制限 |
| ノードあたりのダイアログ | 15 | 無制限 |
| 変数 | 3 | 無制限 |
| タイプあたりのリソース | 3 | 無制限 |

## ダウンロード

[**Releases**](https://github.com/Taleson/Taleson/releases/latest)ページからデモ版をダウンロードしてください。

| プラットフォーム | 形式 |
|-----------------|------|
| Windows | `.exe` インストーラー / ポータブル |

## 同梱テンプレートと書き出し先

| ツール | テンプレート | 書き出し |
|--------|-----------|-----------|
| Ren'Py | 同梱 | `.rpy` |
| Ink | 同梱 | `.ink` |
| Yarn Spinner | 同梱 | `.yarn` |
| Dialogic 2 | 同梱 | `.dtl` |
| Naninovel | 同梱 | `.nani` |

## フィードバック & コミュニティ

皆さまのご意見をお待ちしています:

- **バグ報告** -- [Issueを作成](https://github.com/Taleson/Taleson/issues/new?template=bug_report.md)
- **機能リクエスト** -- [Issueを作成](https://github.com/Taleson/Taleson/issues/new?template=feature_request.md)
- **自由な議論** -- [Discussionsに参加](https://github.com/Taleson/Taleson/discussions)

## ライセンス

Copyright (c) 2025-2026 Taleson. All rights reserved.

このソフトウェアは独占的ソフトウェアです。著者の事前の書面による許可なく、このソフトウェアを複製、修正、配布、または使用することは厳しく禁止されています。

詳細は[LICENSE](LICENSE)をご参照ください。
