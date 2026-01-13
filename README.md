# HTTP 완벽가이드 웹사이트

HTTP 프로토콜에 대한 완벽한 학습 자료를 MkDocs로 구축한 웹사이트

### 필수 요구사항

- Python 3.8+
- MkDocs 및 Material 테마 (자동 설치됨)

### 설치

```bash
pip install mkdocs mkdocs-material
```

### 로컬 서버 실행

```bash
mkdocs serve
```

브라우저에서 `http://localhost:8000` 접속

### 빌드

```bash
mkdocs build
```

정적 웹사이트는 `_site` 폴더에 생성

## 폴더 구조

```
.
├── mkdocs.yml           # MkDocs 설정 파일
├── docs/                # 문서 소스
│   ├── index.md
│   ├── ch01/
│   ├── ch02/
│   └── ...
└── _site/              # 빌드 결과 (배포 대상)
```

## 라이선스

이 자료는 학습용입니다.

**라이브 사이트:** https://http-definitive-guide.netlify.app
