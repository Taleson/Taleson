<div align="center">

<!-- TODO: Replace with actual logo -->
<!-- <img src="docs/screenshots/logo.png" alt="Taleson" width="120" /> -->

# Taleson

**ゲーム用JSONを簡単に作成できるストーリーエディター**

コーディング不要。ストーリーを書き、シーンをつなげて、エクスポートするだけ。

[![Download](https://img.shields.io/github/v/release/Taleson/Taleson?label=Download&style=for-the-badge)](https://github.com/Taleson/Taleson/releases)
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge)](#license)

[English](README.md) | [한국어](README.ko.md)

</div>

---

<!-- TODO: Add hero screenshot -->
<!-- ![Taleson Editor](docs/screenshots/editor-overview.png) -->

## Talesonとは？

Talesonは、構造化されたストーリーをJSONデータとして作成するデスクトップアプリケーションです。ビジュアルノベル、分岐型RPGダイアログ、複雑なインタラクティブナラティブなど、何を作る場合でも、Talesonはストーリーを整理し、視覚化し、エクスポートするツールを提供します。

プロジェクトのあらゆる側面は**設定駆動型**です -- カラムレイアウト、ノードタイプ、フィールドの動作はすべてプロジェクト設定で定義され、ハードコーディングされていません。

**対応言語:** English, Korean (한국어), Japanese (日本語), Chinese (中文)

### デモ版の制限

デモ版には以下のリソース制限があります：

| リソース | デモ | フルバージョン |
|----------|------|--------------|
| チャプター | 2個 | 無制限 |
| チャプターあたりのノード | 10個 | 無制限 |
| ノードあたりの行 | 15個 | 無制限 |
| 変数 | 3個 | 無制限 |
| リソース（タイプごと） | 各3個 | 無制限 |

- **作成/追加**のみが制限されます。既存データの読み取りに制限はありません。
- 制限に達するとメッセージが表示されます -- 何も無視されません。
- **既存データは決して削除または破損されません**。

> **警告 -- JSON汚染リスク**
>
> デモ版はフルバージョンと同じJSONプロジェクトファイルを使用します。デモプロジェクトファイルを外部で編集する予定がある場合（スクリプト、ツール、手動編集）、**まず元のJSONファイルをバックアップしてください**。JSONファイルでデータの破損や予期しない変更に気づいた場合は、**すぐに中止し**、[Issues](https://github.com/Taleson/Taleson/issues/new?template=bug_report.md)で報告してから続行してください。

### 価格

- **デモ版：** リソース制限付きの無料版（永久無料）
- **フルバージョン：** Steam Early Accessで有料リリース予定

デモ版は永久に無料で提供されます。無制限の機能を備えたフルバージョンは、Steamで購入可能になります。

## 機能

### ストーリー構造

| モード | 説明 | 最適な用途 |
|------|-------------|----------|
| **Array** | 線形、順次的なノード | シンプルなスクリプト、チュートリアル |
| **Graph** | 接続のある分岐型ノードツリー | RPGダイアログ、選択ベースのナラティブ |
| **Graph-Inline** | インライン子ノードを持つグラフ | ビジュアルノベル、会話中心のストーリー |

### エディター

- ドラッグ&ドロップビジュアルノードエディター
- ダイアログとナレーションのためのリッチテキスト編集
- 条件分岐（変数、演算子、値）
- ノードタイプシステム（ダイアログ、ナレーション、分岐、選択など）
- プロジェクトごとにカスタマイズ可能なカラムとフィールド

### エクスポート

- スタンドアロン読み取り用のHTMLエクスポート
- ゲームエンジン統合用のJSONデータ

### AI統合（MCP）

- 組み込みMCP（Model Context Protocol）サーバー
- AIエージェントがストーリーノードを読み取り、作成、変更可能
- AI支援ストーリー作成ワークフローを実現

## ダウンロード

[**デモ v1.0.0 ダウンロード**](https://github.com/Taleson/Taleson/releases/tag/v1.0.0-demo)

| タイプ | ファイル | 注記 |
|------|------|------|
| **ポータブル（推奨）** | `Taleson Demo x.x.x.exe` | インストール不要。初期開発段階で推奨。 |
| セットアップ | `Taleson Demo Setup x.x.x.exe` | Windowsインストーラー。MCP（AI統合）サポートに必要。 |

## スクリーンショット

<!-- TODO: Add screenshots when available -->
<!--
| ホーム画面 | ノードエディター | グラフビュー |
|:-----------:|:-----------:|:----------:|
| ![Home](docs/screenshots/home.png) | ![Editor](docs/screenshots/editor.png) | ![Graph](docs/screenshots/graph.png) |
-->

*スクリーンショット準備中。*

## フィードバック＆コミュニティ

皆様のご意見をお聞かせください：

- **バグ報告** -- [Issueを開く](https://github.com/Taleson/Taleson/issues/new?template=bug_report.md)
- **機能リクエスト** -- [Issueを開く](https://github.com/Taleson/Taleson/issues/new?template=feature_request.md)
- **一般的な議論** -- [ディスカッションに参加](https://github.com/Taleson/Taleson/discussions)

## 計画中の統合

| エンジン | ステータス |
|--------|--------|
| RPG Maker MV/MZ | 計画中 |
| Ren'Py | 計画中 |
| Ink (Unity) | 計画中 |
| Yarn Spinner (Unity) | 計画中 |

## ライセンス

Copyright (c) 2025 Taleson. All rights reserved.

本ソフトウェアは独占的なソフトウェアです。著者の事前の書面による許可なく、いかなる媒体を通じても、本ソフトウェアの無断複製、変更、配布、使用は厳しく禁止されています。

詳細は[LICENSE](LICENSE)を参照してください。
