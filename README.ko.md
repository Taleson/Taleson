<div align="center">

<!-- TODO: Replace with actual logo -->
<!-- <img src="docs/screenshots/logo.png" alt="Taleson" width="120" /> -->

# Taleson

**게임용 JSON을 쉽게 만드는 스토리 에디터**

코딩 불필요. 스토리를 작성하고, 장면을 연결하고, 내보내기만 하세요.

[![Download](https://img.shields.io/github/v/release/Taleson/Taleson?label=Download&style=for-the-badge)](https://github.com/Taleson/Taleson/releases)
[![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge)](#license)

[English](README.md)

</div>

---

<!-- TODO: Add hero screenshot -->
<!-- ![Taleson Editor](docs/screenshots/editor-overview.png) -->

## Taleson이란?

Taleson은 구조화된 스토리를 JSON 데이터로 작성하는 데스크톱 애플리케이션입니다. 비주얼 노벨, 분기형 RPG 대화, 복잡한 인터랙티브 내러티브 등 어떤 것을 만들든 Taleson은 스토리를 정리하고, 시각화하고, 내보낼 수 있는 도구를 제공합니다.

프로젝트의 모든 측면은 **설정 기반**입니다 -- 컬럼 레이아웃, 노드 타입, 필드 동작이 모두 프로젝트 설정으로 정의되며 하드코딩되지 않습니다.

**지원 언어:** English, Korean (한국어), Japanese (日本語), Chinese (中文)

### 데모 버전 제한사항

데모 버전은 다음과 같은 리소스 제한이 있습니다:

| 리소스 | 데모 | 정식 버전 |
|----------|------|--------------|
| 챕터 | 2개 | 무제한 |
| 챕터당 노드 | 10개 | 무제한 |
| 노드당 라인 | 15개 | 무제한 |
| 변수 | 3개 | 무제한 |
| 리소스 (타입별) | 각 3개 | 무제한 |

- **생성/추가**만 제한됩니다. 기존 데이터 읽기는 제한이 없습니다.
- 제한에 도달하면 메시지가 표시됩니다 -- 무시되지 않습니다.
- **기존 데이터는 절대 삭제되거나 손상되지 않습니다**.

> **경고 -- JSON 오염 위험**
>
> 데모는 정식 버전과 동일한 JSON 프로젝트 파일을 사용합니다. 데모 프로젝트 파일을 외부에서 편집할 계획이라면 (스크립트, 도구, 수동 편집), **먼저 원본 JSON 파일을 백업하세요**. JSON 파일에서 데이터 손상이나 예상치 못한 변경사항을 발견하면 **즉시 중단하고** [Issues](https://github.com/Taleson/Taleson/issues/new?template=bug_report.md)를 통해 보고한 후 계속 진행하세요.

### 가격 정책

- **데모 버전:** 리소스 제한이 있는 무료 버전 (영구 무료)
- **정식 버전:** Steam Early Access 유료 출시 예정

데모는 영구적으로 무료로 제공됩니다. 무제한 기능을 갖춘 정식 버전은 Steam에서 유료로 구매 가능합니다.

## 기능

### 스토리 구조

| 모드 | 설명 | 적합한 용도 |
|------|-------------|----------|
| **Array** | 선형, 순차적 노드 | 간단한 스크립트, 튜토리얼 |
| **Graph** | 연결이 있는 분기형 노드 트리 | RPG 대화, 선택 기반 내러티브 |
| **Graph-Inline** | 인라인 자식 노드가 있는 그래프 | 비주얼 노벨, 대화 중심 스토리 |

### 에디터

- 드래그 앤 드롭 비주얼 노드 에디터
- 대화와 내레이션을 위한 리치 텍스트 편집
- 조건부 분기 (변수, 연산자, 값)
- 노드 타입 시스템 (대화, 내레이션, 분기, 선택 등)
- 프로젝트별 커스터마이징 가능한 컬럼 및 필드

### 내보내기

- 독립 실행형 읽기를 위한 HTML 내보내기
- 게임 엔진 통합을 위한 JSON 데이터

### AI 통합 (MCP)

- 내장 MCP (Model Context Protocol) 서버
- AI 에이전트가 스토리 노드를 읽고, 생성하고, 수정 가능
- AI 지원 스토리 작성 워크플로우 지원

## 다운로드

[**데모 v1.0.0 다운로드**](https://github.com/Taleson/Taleson/releases/tag/v1.0.0-demo)

| 타입 | 파일 | 비고 |
|------|------|------|
| **포터블 (권장)** | `Taleson Demo x.x.x.exe` | 설치 불필요. 초기 개발 단계에서 권장. |
| 설치 | `Taleson Demo Setup x.x.x.exe` | Windows 설치 프로그램. MCP (AI 통합) 지원에 필요. |

## 스크린샷

<!-- TODO: Add screenshots when available -->
<!--
| 홈 화면 | 노드 에디터 | 그래프 뷰 |
|:-----------:|:-----------:|:----------:|
| ![Home](docs/screenshots/home.png) | ![Editor](docs/screenshots/editor.png) | ![Graph](docs/screenshots/graph.png) |
-->

*스크린샷 준비 중.*

## 피드백 & 커뮤니티

여러분의 의견을 듣고 싶습니다:

- **버그 리포트** -- [이슈 열기](https://github.com/Taleson/Taleson/issues/new?template=bug_report.md)
- **기능 요청** -- [이슈 열기](https://github.com/Taleson/Taleson/issues/new?template=feature_request.md)
- **일반 토론** -- [토론 참여하기](https://github.com/Taleson/Taleson/discussions)

## 계획된 통합

| 엔진 | 상태 |
|--------|--------|
| RPG Maker MV/MZ | 계획됨 |
| Ren'Py | 계획됨 |
| Ink (Unity) | 계획됨 |
| Yarn Spinner (Unity) | 계획됨 |

## 라이선스

Copyright (c) 2025 Taleson. All rights reserved.

이 소프트웨어는 독점 소프트웨어입니다. 저자의 사전 서면 허가 없이 이 소프트웨어를 복사, 수정, 배포 또는 사용하는 것은 어떤 매체를 통해서든 엄격히 금지됩니다.

자세한 내용은 [LICENSE](LICENSE)를 참조하세요.
