# HTTP 완벽가이드 웹사이트

HTTP 프로토콜에 대한 완벽한 학습 자료를 MkDocs로 구축한 웹사이트입니다.

## 기능

- 21개 챕터로 구성된 체계적인 학습 자료
- Material 테마를 사용한 깔끔한 UI
- 한국어 지원
- 빠른 검색 기능
- 모바일 반응형 디자인

## 로컬 개발

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

정적 웹사이트는 `_site` 폴더에 생성됩니다.

## Netlify 배포

이 레포지토리는 Netlify와 연동되어 있습니다. 다음 단계로 배포할 수 있습니다:

1. GitHub 레포지토리 생성 및 코드 푸시
2. [Netlify](https://netlify.com) 접속
3. "New site from Git" 선택
4. GitHub 레포지토리 선택
5. 빌드 설정:
   - Build command: `mkdocs build`
   - Publish directory: `_site`
6. 배포

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

---

**라이브 사이트:** https://http-definitive-guide.netlify.app
