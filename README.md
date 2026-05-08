# 길을 묻다 — 선배가 들려주는 진로 이야기

서울대학교 농업생명과학대학 응용생명화학전공 선배 초청 세미나 발표 자료입니다.

- **연사**: 정승규 (농화학 89학번, NHN PAYCO 대표이사 · NHN KCP COO)
- **일시**: 2026. 05. 07 (목)
- **주제**: 30년 직장생활을 거치며 보고 듣고 느낀 진로 이야기

## 페이지 구성

- [`index.html`](./index.html) — 슬라이드만 보기 모드
- [`with-script.html`](./with-script.html) — 슬라이드 + 발표 스크립트 같이 보기 모드
- [`slides/`](./slides/) — 발표 슬라이드 이미지 (20장)
- [`downloads/`](./downloads/) — 발표자료(PPTX) 및 발표 원고(PDF)

## 기술 스택

- **정적 HTML** — 빌드 도구 없이 단일 파일로 동작 (CSS/JS 인라인)
- **Google Fonts** — Noto Sans KR, Noto Serif KR
- **Google Analytics 4** — 방문자 및 다운로드 이벤트 추적 (`G-KQECGH8X3M`)

## 배포

동일한 정적 사이트를 두 호스팅에 동시 배포하여 가용성을 확보합니다.

- **Netlify**
- **Vercel**

루트의 HTML 파일을 그대로 서빙하면 되며, 별도의 빌드 설정이 필요하지 않습니다.

## 로컬에서 보기

별도의 서버 없이 `index.html` 파일을 브라우저로 직접 열어도 동작합니다.
