<div align="center">

<!-- TODO: 실제 로고로 교체 -->
<!-- <img src="docs/screenshots/logo.png" alt="Taleson" width="120" /> -->

# Taleson

**스토리용 JSON을 쉽게 만드는 에디터**

코딩 없이 스토리를 쓰고, 장면을 연결하고, 바로 내보내세요.

[![다운로드](https://img.shields.io/github/v/release/Taleson/Taleson?label=%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C&style=for-the-badge)](https://github.com/Taleson/Taleson/releases)
[![라이선스](https://img.shields.io/badge/%EB%9D%BC%EC%9D%B4%EC%84%A0%EC%8A%A4-All%20Rights%20Reserved-red?style=for-the-badge)](#라이선스)

[English](README.md)

</div>

---

<!-- TODO: 메인 스크린샷 추가 -->
<!-- ![Taleson 에디터](docs/screenshots/editor-overview.png) -->

## Taleson이란?

Taleson은 JSON 데이터로 구조화된 스토리를 작성하기 위한 데스크톱 애플리케이션입니다. 비주얼 노벨, 분기형 RPG 대화, 복잡한 인터랙티브 내러티브 등 어떤 스토리든 체계적으로 구성하고, 시각화하고, 내보낼 수 있습니다.

프로젝트의 모든 요소는 **설정 기반**으로 동작합니다. 컬럼 레이아웃, 노드 타입, 필드 동작 모두 프로젝트 설정으로 정의됩니다.

### 데모 제한 사항

데모 버전에는 다음과 같은 리소스 제한이 있습니다:

| 항목 | 데모 | 풀 버전 |
|------|------|---------|
| 챕터 수 | 2개 | 무제한 |
| 챕터당 노드 수 | 10개 | 무제한 |
| 노드당 대사 수 | 15개 | 무제한 |
| 변수 | 3개 | 무제한 |
| 리소스 (종류별) | 각 3개 | 무제한 |

- **추가/생성만** 제한됩니다. 기존 데이터 읽기는 제한 없이 가능합니다.
- 제한 초과 시 안내 메시지가 표시됩니다 -- 조용히 무시되지 않습니다.
- 데모 제한으로 인해 **기존 데이터가 삭제되거나 손상되는 일은 없습니다**.

> **주의 -- 원본 JSON 오염 위험**
>
> 데모는 풀 버전과 동일한 JSON 프로젝트 파일을 사용합니다. 데모 프로젝트 파일을 외부에서 편집(스크립트, 도구, 수동 편집 등)할 경우 **반드시 원본 JSON 파일을 백업한 후 작업하세요**. JSON 파일에서 데이터 오염이나 예기치 않은 변경이 발견되면 **즉시 작업을 중단하고** [이슈](https://github.com/Taleson/Taleson/issues/new?template=bug_report.md)를 통해 피드백을 남겨 주세요.

## 주요 기능

### 스토리 구조

| 모드 | 설명 | 적합한 용도 |
|------|------|------------|
| **Array** | 선형, 순차적 노드 | 단순 스크립트, 튜토리얼 |
| **Graph** | 분기형 노드 트리 | RPG 대화, 선택지 기반 내러티브 |
| **Graph-Inline** | 인라인 자식 노드가 있는 그래프 | 비주얼 노벨, 대화 중심 스토리 |

### 에디터

- 드래그 앤 드롭 비주얼 노드 에디터
- 대화 및 나레이션용 리치 텍스트 편집
- 조건 분기 (변수, 연산자, 값)
- 노드 타입 시스템 (대화, 나레이션, 분기, 선택지 등)
- 프로젝트별 커스터마이즈 가능한 컬럼과 필드

### 내보내기

- HTML 내보내기 (독립 실행형 리딩)
- JSON 데이터 (게임 엔진 연동)

### AI 연동 (MCP)

- 내장 MCP (Model Context Protocol) 서버
- AI 에이전트가 스토리 노드를 읽고, 생성하고, 수정 가능
- AI 지원 스토리 작성 워크플로우

## 다운로드

[**Demo v1.0.0 다운로드**](https://github.com/Taleson/Taleson/releases/tag/v1.0.0-demo)

| 종류 | 파일 | 비고 |
|------|------|------|
| **포터블 (추천)** | `Taleson Demo x.x.x.exe` | 설치 불필요. 아직 개발 초기 단계이므로 포터블 사용을 권장합니다. |
| 설치형 | `Taleson Demo Setup x.x.x.exe` | Windows 설치파일. MCP (AI 연동) 기능을 사용하려면 설치형이 필요합니다. |

## 스크린샷

<!-- TODO: 스크린샷 추가 예정 -->
<!--
| 홈 화면 | 노드 에디터 | 그래프 뷰 |
|:-------:|:----------:|:--------:|
| ![홈](docs/screenshots/home.png) | ![에디터](docs/screenshots/editor.png) | ![그래프](docs/screenshots/graph.png) |
-->

*스크린샷 준비 중입니다.*

## 피드백 & 커뮤니티

여러분의 의견을 기다립니다:

- **버그 제보** -- [이슈 등록](https://github.com/Taleson/Taleson/issues/new?template=bug_report.md)
- **기능 요청** -- [이슈 등록](https://github.com/Taleson/Taleson/issues/new?template=feature_request.md)
- **자유 토론** -- [Discussions 참여](https://github.com/Taleson/Taleson/discussions)

## 게임 엔진 연동 계획

| 엔진 | 상태 |
|------|------|
| RPG Maker MV/MZ | 예정 |
| Ren'Py | 예정 |
| Ink (Unity) | 예정 |
| Yarn Spinner (Unity) | 예정 |

## 라이선스

Copyright (c) 2025 Taleson. All rights reserved.

이 소프트웨어는 독점 소프트웨어입니다. 저자의 사전 서면 허가 없이 이 소프트웨어를 복사, 수정, 배포 또는 사용하는 것은 엄격히 금지됩니다.

자세한 내용은 [LICENSE](LICENSE)를 참조하세요.
