<h1 align="center">김지환 · Jihwan Kim</h1>

<p align="center">
  <strong>Frontend-leaning Full-stack Engineer</strong><br />
  복잡한 업무 흐름을 제품으로 만들고, AI를 연결해 배포와 운영까지 다룹니다.
</p>

<p align="center">
  <a href="https://pikan.dev/ko">
    <img src="https://img.shields.io/badge/Portfolio-Full--stack-181717?style=flat-square&logo=vercel&logoColor=white" alt="Full-stack Portfolio" />
  </a>
  <a href="https://pikan.dev/ko/fde">
    <img src="https://img.shields.io/badge/Portfolio-FDE%20Focus-2563EB?style=flat-square&logo=vercel&logoColor=white" alt="FDE-focused Portfolio" />
  </a>
  <a href="https://github.com/tykimdream/JHWorks-AI-Groupware">
    <img src="https://img.shields.io/badge/Project-JHWorks%20AI-0F766E?style=flat-square&logo=github&logoColor=white" alt="JHWorks AI Groupware" />
  </a>
  <a href="https://game-park-yrss.vercel.app/">
    <img src="https://img.shields.io/badge/Live-Game%20Park-1A1A5E?style=flat-square&logo=googlechrome&logoColor=white" alt="Game Park" />
  </a>
  <a href="mailto:tykimdream@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

## About

React·Next.js를 중심으로 B2B SaaS, 글로벌 커머스, Electron 운영 도구를 개발해 왔습니다. 사용자 기능부터 API, 실시간 통신, 성능, 테스트, CI/CD와 데스크톱 배포까지 제품 전 주기를 연결합니다. 개인 프로젝트 JHWorks에서는 Python·FastAPI와 정책 RAG, 확인 기반 AI 워크플로우를 구현하고 Cloud Run·Supabase 비공개 배포와 백업·복원까지 검증하고 있습니다.

- 사용자가 기다리거나 운영자가 수작업하는 지점을 찾아 제품 구조로 개선합니다.
- 복잡한 권한·상태·거래 흐름을 예측 가능한 UI와 데이터 흐름으로 구현합니다.
- 웹뿐 아니라 Electron, Socket.IO·STOMP, NFC 하드웨어 연동과 배포 환경을 다룹니다.
- AI는 의도 구조화와 정책 검색에 활용하고, 권한·업무 계산·데이터 변경은 서버에서 검증합니다.
- 풀스택 제품 개발을 기반으로 고객 문제 정의와 현장 배포를 책임지는 FDE 역할까지 확장하고 있습니다.

> 상세 경력은 [기본 포트폴리오](https://pikan.dev/ko), 고객 워크플로우·현장 배포 관점은 [FDE 지원형 포트폴리오](https://pikan.dev/ko/fde)에서 확인할 수 있습니다.

---

## Selected Outcomes

| 영역 | 결과 |
| --- | --- |
| Product Performance | 반복 요청 구조를 재설계해 채팅방 생성 시간 **6초 → 0.1초** 단축 |
| Desktop Architecture | Electron 중복 IPC 리스너 **134회 → 15회**, 88.8% 축소 |
| Web Performance | 코드 스플리팅으로 FCP **3.1초 → 2.2초** 개선 |
| Frontend DX | Storybook webpack → Vite 전환으로 빌드 **28.9초 → 13.9초** 단축 |
| Global Product | i18n **800+ 사용처** 개편, **3개 언어·24개 페이지** 검색 노출 구조 정비 |
| Operations | 개발자가 DB를 수정하던 NFC·메뉴 업무를 운영 담당자 **셀프서비스 도구**로 전환 |
| Delivery | GitHub Actions, AWS S3·CloudFront 자동 업데이트, Windows 코드 서명·macOS 공증 적용 |

---

## Featured Project · JHWorks AI Groupware

> 자연어 휴가 요청을 일정 탐색, 정책 확인, 결재 초안과 제출로 연결하는 독립 개인 프로젝트

[**코드와 설계 근거 →**](https://github.com/tykimdream/JHWorks-AI-Groupware) · [**케이스 스터디 →**](https://pikan.dev/ko/projects/jhworks-ai-groupware)

- Next.js·FastAPI·PostgreSQL·pgvector 기반 전자결재와 근태·연차 도메인
- 정책 RAG와 인용 검증, Structured Output, 사용자 범위로 제한한 Tool Calling
- AI의 의도 구조화와 서버의 권한·일정·연차 계산 분리
- 저장과 제출 각각의 미리보기·사용자 확인, 서명 검증과 멱등 처리
- Cloud Run·Supabase 비공개 배포, 방문자 데이터 격리와 DB 공유 요청 제한
- 실제 PostgreSQL 경합·브라우저 CI, 합성 DB 백업과 격리 복원 대조 검증

모든 조직·정책·업무 데이터는 가상 데이터입니다. 앱은 비공개 검증 중이며 공개 도메인은 준비 화면입니다. 실제 조직 도입이나 사용자 생산성 개선을 주장하지 않습니다.

---

## Featured Project · Game Park

> 설치 없이 브라우저에서 즐기는 풀스택 웹 게임 플랫폼

[**Game Park 바로 플레이하기 →**](https://game-park-yrss.vercel.app/)

게임 플랫폼, 개별 게임, 실시간 기능, 데이터 모델과 반복 가능한 개발 워크플로우를 설계·개발한 개인 프로젝트입니다. 저장소는 비공개이며 라이브 서비스와 포트폴리오 케이스 스터디를 공개합니다.

- `iframe + postMessage` 기반 독립 게임 통합 프로토콜
- Next.js·NestJS·Prisma·PostgreSQL 기반 플랫폼과 API
- Socket.IO 기반 매칭 대기열·멀티플레이어·랭킹 시스템
- Canvas 게임 루프와 결정론적 상태 처리
- 프로젝트 규칙과 검증 절차를 포함한 게임 보일러플레이트
- 카붐·한들·신화 디펜스·네모네모 퍼즐 **4종 라이브 운영**

---

## Tech Stack

**Frontend**

<p>
  <img src="https://img.shields.io/badge/TypeScript-34495E?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-34495E?style=flat-square&logo=javascript&logoColor=white" alt="JavaScript" />
  <img src="https://img.shields.io/badge/React-34495E?style=flat-square&logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-34495E?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/TanStack%20Query-34495E?style=flat-square" alt="TanStack Query" />
  <img src="https://img.shields.io/badge/Zustand-34495E?style=flat-square" alt="Zustand" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-34495E?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

**Desktop & Real-time**

<p>
  <img src="https://img.shields.io/badge/Electron-34495E?style=flat-square&logo=electron&logoColor=white" alt="Electron" />
  <img src="https://img.shields.io/badge/Socket.IO-34495E?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.IO" />
  <img src="https://img.shields.io/badge/STOMP-34495E?style=flat-square" alt="STOMP" />
  <img src="https://img.shields.io/badge/IPC-34495E?style=flat-square" alt="IPC" />
  <img src="https://img.shields.io/badge/NFC-34495E?style=flat-square" alt="NFC" />
</p>

**Backend & Data**

<p>
  <img src="https://img.shields.io/badge/Node.js-34495E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/NestJS-34495E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS" />
  <img src="https://img.shields.io/badge/Python-34495E?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-34495E?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Prisma-34495E?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
  <img src="https://img.shields.io/badge/PostgreSQL-34495E?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/REST%20API-34495E?style=flat-square" alt="REST API" />
</p>

**AI**

<p>
  <img src="https://img.shields.io/badge/Policy%20RAG-34495E?style=flat-square" alt="Policy RAG" />
  <img src="https://img.shields.io/badge/pgvector-34495E?style=flat-square" alt="pgvector" />
  <img src="https://img.shields.io/badge/Structured%20Output-34495E?style=flat-square" alt="Structured Output" />
  <img src="https://img.shields.io/badge/Function%20Calling-34495E?style=flat-square" alt="Function Calling" />
</p>

**Quality & Delivery**

<p>
  <img src="https://img.shields.io/badge/Playwright-34495E?style=flat-square" alt="Playwright" />
  <img src="https://img.shields.io/badge/Storybook-34495E?style=flat-square&logo=storybook&logoColor=white" alt="Storybook" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-34495E?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Docker-34495E?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Cloud%20Run-34495E?style=flat-square&logo=googlecloud&logoColor=white" alt="Cloud Run" />
  <img src="https://img.shields.io/badge/Supabase-34495E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/AWS%20S3-34495E?style=flat-square" alt="AWS S3" />
  <img src="https://img.shields.io/badge/CloudFront-34495E?style=flat-square" alt="CloudFront" />
  <img src="https://img.shields.io/badge/Vercel-34495E?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
</p>

데스크톱 배포: macOS 공증 · Windows 코드 서명

---

## Experience

### 주식회사 더블티 · 풀스택 개발자, 프론트엔드 중심

`2025.04 - 2026.06`

B2B 그룹웨어 SaaS, Electron 채팅 앱, 글로벌 B2B/B2C 커머스와 사내 운영 도구를 개발했습니다.

### 태백넷 · 프론트엔드 개발자

`2024.04 - 2025.04`

AI 이미지 처리 SaaS tebekAI의 이미지 처리, 인증, 결제와 운영 화면을 개발했습니다.

---

## Training

- 삼성청년SW아카데미 8기 웹 개발 트랙
- 42 Seoul Innovation Academy

<p align="center">
  <a href="https://solved.ac/tykimdream">
    <img src="https://mazassumnida.wtf/api/v2/generate_badge?boj=tykimdream" width="280" alt="Solved.ac Profile" />
  </a>
</p>

---

<p align="center">
  <a href="https://pikan.dev/ko">Portfolio</a>
  ·
  <a href="https://pikan.dev/ko/fde">FDE Focus</a>
  ·
  <a href="https://github.com/tykimdream/JHWorks-AI-Groupware">JHWorks AI</a>
  ·
  <a href="https://game-park-yrss.vercel.app/">Game Park</a>
  ·
  <a href="mailto:tykimdream@gmail.com">Email</a>
</p>
