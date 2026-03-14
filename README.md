# giantforest.lab

> 태림 스튜디오의 기술 노트와 오픈소스 실험실

[![MIT License (code)](https://img.shields.io/badge/code-MIT-green)](LICENSE)
[![CC BY-NC 4.0 (content)](https://img.shields.io/badge/content-CC_BY--NC_4.0-lightgrey)](LICENSE-CONTENT.md)

전시, 팝업, 포토부스, 인터랙티브 웹 — 현장에서 경험이 돌아가게 만들면서 배운 것들을 기록하고, 재사용할 수 있는 코드를 공개합니다.

🔗 **[giant-forest-studio.web.app](https://giant-forest-studio.web.app)** — 태림 스튜디오 홈페이지

> 여기 올라온 글은 [홈페이지](https://giant-forest-studio.web.app)에서도 읽을 수 있습니다.
> 이 레포가 원본이고, 홈페이지는 빌드 시 여기서 가져가 렌더링합니다.

## 무엇이 있나요

### 📝 현장 노트 (`docs/articles/`)

기술 블로그보다는 **현장 노트**에 가깝습니다. 코드 자랑이 아니라, 이 현장에서 왜 이 선택을 했는지를 기록합니다.

- [2주 약 5,400회를 버틴 포토부스는 무엇이 달랐을까](docs/articles/how-we-ran-5400-sessions.md)
- [우리는 왜 '기술 블로그' 대신 '현장 노트'를 쓰기로 했나](docs/articles/why-we-write-field-notes.md)

### 📦 패키지 (`packages/`)

재사용 가능한 작은 코드를 공개합니다. _(준비 중)_

### 🧪 예제 (`examples/`)

글이나 패키지를 바로 돌려볼 수 있는 최소 재현 예제. _(준비 중)_

## 구조

```text
giantforest.lab/
├── docs/
│   ├── articles/    # 현장 노트 (Markdown)
│   └── assets/      # 글에 쓰이는 이미지
├── packages/        # 재사용 가능한 코드
├── examples/        # 최소 재현 예제
└── catalog/
    └── entries.json # 홈페이지 연동용 manifest
```

## 만든 사람들

**태림 스튜디오 (Giant Forest Studio)**
- 이상규 — 개발
- 하지영 — 디자인
- AI — 팀원 (Claude Code, Codex)

## 라이선스

- **소스 코드** (`packages/`, `examples/`): [MIT License](LICENSE)
- **글과 미디어** (`docs/`): [CC BY-NC 4.0](LICENSE-CONTENT.md)
- **브랜드 자산** (로고, 스크린샷): All Rights Reserved
