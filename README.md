# LeeYudok — 백엔드 · 자체 호스팅 인프라 · AI 개발 도구

백엔드 개발과 자체 호스팅 인프라 운영을 하며, AI 코딩 에이전트 도구와 개발 자동화를 만듭니다. TypeScript·Node.js·Go로 서비스를 개발하고, Linux·Podman 기반 서버에 배포해 모니터링까지 직접 운영합니다.

Claude Code·Codex용 에이전트 스킬, GitLab MR 보안 코드리뷰 봇, 문서 RAG 검색과 MCP 서버를 만들고 있습니다.

Backend development · Self-hosted infrastructure · AI coding agents · Developer tools

![profile views](https://count.doksam.com/badge/profile.svg)

### 대표 프로젝트

AI 개발 환경 설정부터 화면 기획과 UI 구현까지, 직접 만들고 사용하는 도구입니다.

| 프로젝트 | Stars | 하는 일 |
| --- | --- | --- |
| [agents-scaffold](https://github.com/LeeYudok/agents-scaffold) | ![GitHub stars](https://img.shields.io/github/stars/LeeYudok/agents-scaffold?style=flat-square) | **AI 코딩 에이전트 프로젝트 초기 설정.** Claude Code 중심으로 에이전트·스킬·스택 프리셋과 pre-commit 검사를 구성합니다. Codex·Gemini용 AGENTS.md, 설치 안내와 회귀 테스트를 제공합니다. |
| [doksam-skills](https://github.com/LeeYudok/doksam-skills) | ![GitHub stars](https://img.shields.io/github/stars/LeeYudok/doksam-skills?style=flat-square) | **화면 기획부터 구현까지 연결하는 에이전트 스킬.** Claude Code·Codex·Antigravity에서 UX/UI 화면설계서와 Business Rules를 만들고 후속 구현으로 연결합니다. 산출물 미리보기와 설치 안내를 제공합니다. |
| [doksam-ui](https://github.com/LeeYudok/doksam-ui) | ![GitHub stars](https://img.shields.io/github/stars/LeeYudok/doksam-ui?style=flat-square) | **shadcn/ui 기반 UI 컴포넌트·패턴·템플릿 카탈로그.** 데모와 코드, 디자인 토큰을 확인하고 shadcn 레지스트리로 설치할 수 있습니다. [라이브 카탈로그](https://ui.doksam.com) |

### 함께 만드는 개발·운영 도구

| 프로젝트 | Stars | 하는 일 |
| --- | --- | --- |
| [ai-sdlc-skills](https://github.com/LeeYudok/ai-sdlc-skills) | ![GitHub stars](https://img.shields.io/github/stars/LeeYudok/ai-sdlc-skills?style=flat-square) | 기존 저장소의 변경 요청을 분석·명세·구현·QA·배포 준비까지 추적하는 **Codex 개발 자동화 스킬**. 도입 안내와 단계별 산출물 문서를 제공합니다. |
| [finguard](https://github.com/LeeYudok/finguard) | ![GitHub stars](https://img.shields.io/github/stars/LeeYudok/finguard?style=flat-square) | Go·Semgrep·reviewdog 기반 **GitLab MR 보안 코드리뷰 봇**. 취약점 점검 결과에 금융보안원 평가기준 근거와 수정 가이드를 붙입니다. 빌드·실행 방법과 탐지 범위를 문서화했습니다. |
| [dotfiles](https://github.com/LeeYudok/dotfiles) | ![GitHub stars](https://img.shields.io/github/stars/LeeYudok/dotfiles?style=flat-square) | **zsh·Starship 셸 환경과 AI 코딩 도구 상태 표시줄 설정**. macOS·Linux 설치와 복원, Windows Git Bash 환경 구성을 안내합니다. |
| [oracle-us7ascii-jdbc](https://github.com/LeeYudok/oracle-us7ascii-jdbc) | ![GitHub stars](https://img.shields.io/github/stars/LeeYudok/oracle-us7ascii-jdbc?style=flat-square) | Oracle US7ASCII 환경에서 **EUC-KR 한글 깨짐을 처리하는 Java JDBC 드라이버 래퍼**. 빠른 시작, 호환성, 테스트와 DBeaver 설정을 안내합니다. |

### 기술 스택

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-FBF0DF?style=flat-square&logo=bun&logoColor=000000)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-374151?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-892CA0?style=flat-square&logo=podman&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Rocky Linux](https://img.shields.io/badge/Rocky%20Linux-10B981?style=flat-square&logo=rockylinux&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F5A800?style=flat-square)

### 개발·운영 중인 작업

아래 작업은 자체 호스팅 GitLab의 비공개 저장소에서 개발·운영하고 있습니다.

- 자체 호스팅 인프라 운영 — rootless Podman + Quadlet, nginx 리버스 프록시, PostgreSQL 단일 클러스터
- 수집·분석 파이프라인 — 시세와 투자자 수급 데이터를 모아 Grafana로 관측
- AI 도구 연동 — 문서 검색 증강 생성(RAG) 서버, 개인 인프라용 Model Context Protocol(MCP) 서버, GitLab MR 코드리뷰 봇

위 조회수 뱃지도 직접 만들어 굴리고 있습니다. GitHub이 프로필 조회수를 알려주지 않아서, 뱃지 이미지 요청을 신호로 삼아 집계합니다.

### In English

I work on backend development and self-hosted infrastructure, and I build tools for AI coding agents and developer automation. I develop services in TypeScript, Node.js, and Go, then deploy and monitor them on my own Linux servers with rootless Podman, nginx, PostgreSQL, Prometheus, Grafana, and Loki.

- [agents-scaffold](https://github.com/LeeYudok/agents-scaffold) — Project setup for AI coding agents, centered on Claude Code: agents, skills, stack presets, and pre-commit checks, plus AGENTS.md for Codex and Gemini.
- [doksam-skills](https://github.com/LeeYudok/doksam-skills) — Agent skills for Claude Code, Codex, and Antigravity that turn UX/UI screen specs and business rules into implementation.
- [doksam-ui](https://github.com/LeeYudok/doksam-ui) — A catalog of shadcn/ui-based components, patterns, and templates, installable from a shadcn registry. [Live catalog](https://ui.doksam.com)
- [finguard](https://github.com/LeeYudok/finguard) — A GitLab merge request security code review bot built with Go, Semgrep, and reviewdog.
- [oracle-us7ascii-jdbc](https://github.com/LeeYudok/oracle-us7ascii-jdbc) — A Java JDBC driver wrapper that fixes broken EUC-KR Korean text in Oracle US7ASCII databases.
