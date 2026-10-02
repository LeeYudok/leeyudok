# LeeYudok — 백엔드 · 자체 호스팅 인프라 · AI 개발 도구

백엔드 개발과 자체 호스팅 인프라 운영을 하며, AI 코딩 에이전트 도구와 개발 자동화를 만듭니다. TypeScript·Node.js·Go로 서비스를 개발하고, Linux·Podman 기반 서버에 배포해 모니터링까지 직접 운영합니다.

Claude Code·Codex용 에이전트 스킬, GitLab MR 보안 코드리뷰 봇, 문서 RAG 검색과 MCP 서버를 만들고 있습니다.

Backend development · Self-hosted infrastructure · AI coding agents · Developer tools

![profile views](https://count.doksam.com/badge/profile.svg)

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

### 공개 프로젝트

- [agents-scaffold](https://github.com/LeeYudok/agents-scaffold) — Claude Code 중심의 AI 코딩 에이전트 프로젝트 초기 설정 도구. Codex·Gemini용 AGENTS.md도 제공하며, 에이전트·스킬·훅과 P0/P1/P2 등급 규칙, 스택 프리셋을 pre-commit 품질 검사로 묶습니다.
- [finguard](https://github.com/LeeYudok/finguard) — Go로 만든 Semgrep·reviewdog 기반 정적 분석(SAST) 및 보안 코드리뷰 봇. 은행권 소스코드 취약점을 점검하고 GitLab Merge Request(MR)에 금융보안원 평가기준 근거를 붙인 인라인 코멘트를 답니다.
- [ai-sdlc-skills](https://github.com/LeeYudok/ai-sdlc-skills) — AI 에이전트 기반 소프트웨어 개발 생명주기(SDLC) 자동화 스킬 모음. 기존 저장소의 버그 수정·기능 요청을 분석 → BA 문서 → 영향도 분석 → 명세 → 구현 → QA → 배포 준비까지 추적합니다.
- [doksam-skills](https://github.com/LeeYudok/doksam-skills) — Claude Code·Codex·Antigravity용 모바일 웹·앱 UX/UI 기획 스킬. 정보 구조(IA)와 PPT 스타일의 HTML 화면설계서를 생성합니다.
- [doksam-ui](https://github.com/LeeYudok/doksam-ui) — 자체 호스팅 shadcn UI 컴포넌트 레지스트리와 디자인 토큰 카탈로그. [ui.doksam.com](https://ui.doksam.com)
- [oracle-us7ascii-jdbc](https://github.com/LeeYudok/oracle-us7ascii-jdbc) — Oracle US7ASCII 데이터베이스의 EUC-KR 한글 인코딩 처리를 위한 JDBC 드라이버 래퍼.

### 개발·운영 중인 작업

아래 작업은 자체 호스팅 GitLab의 비공개 저장소에서 개발·운영하고 있습니다.

- 자체 호스팅 인프라 운영 — rootless Podman + Quadlet, nginx 리버스 프록시, PostgreSQL 단일 클러스터
- 수집·분석 파이프라인 — 시세와 투자자 수급 데이터를 모아 Grafana로 관측
- AI 도구 연동 — 문서 검색 증강 생성(RAG) 서버, 개인 인프라용 Model Context Protocol(MCP) 서버, GitLab MR 코드리뷰 봇

위 조회수 뱃지도 직접 만들어 굴리고 있습니다. GitHub이 프로필 조회수를 알려주지 않아서, 뱃지 이미지 요청을 신호로 삼아 집계합니다.
