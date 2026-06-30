<h1 align="center">김지환 · Kim Jihwan</h1>

<p align="center">
  <strong>Frontend-focused Full-stack Developer</strong><br />
  React · TypeScript · Next.js · Electron 기반으로<br />
  업무용 SaaS와 웹 게임 제품을 설계하고 구현합니다.
</p>

<p align="center">
  <a href="https://pikan.dev/ko">
    <img src="https://img.shields.io/badge/Portfolio-pikan.dev-181717?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://game-park-yrss.vercel.app/">
    <img src="https://img.shields.io/badge/Play-Game%20Park-1A1A5E?style=flat-square&logo=googlechrome&logoColor=white" alt="Game Park" />
  </a>
  <a href="mailto:tykimdream@gmail.com">
    <img src="https://img.shields.io/badge/Email-tykimdream%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

## 👋 About Me

사용자와 운영자의 업무 흐름에서 반복되는 불편을 찾고,
**더 빠르고 안정적인 기능과 제품 경험으로 개선하는 개발자**입니다.

* React·TypeScript 중심의 웹 프론트엔드와 Electron 데스크톱 애플리케이션을 개발합니다.
* B2B SaaS 그룹웨어, 실시간 채팅, 전자결재, 해외 직구 플랫폼 등 복잡한 업무 도메인을 다뤄왔습니다.
* UI 구현을 넘어 API 계약, 상태 관리, 성능, 보안, 테스트, 배포 환경까지 함께 고려합니다.
* 요구사항의 빈틈을 빠르게 발견하고 기획·개발·QA가 같은 기준으로 협업할 수 있게 만드는 일을 중요하게 생각합니다.

<p>
  <a href="https://pikan.dev/ko"><strong>→ 상세 경력과 프로젝트는 포트폴리오에서 확인하기</strong></a>
</p>

---

## ✨ Highlights

| Area                | Contribution                                                            |
| ------------------- | ----------------------------------------------------------------------- |
| Product Performance | 채팅방 생성 흐름의 반복 요청 병목을 개선해 **6초 → 0.1초**로 단축                              |
| Desktop App         | Electron 기반 실시간 채팅 데스크톱 애플리케이션 기능·배포 환경 구현                              |
| Real-time           | Socket.IO 및 STOMP 기반 실시간 채팅 클라이언트 연동 및 상태 이벤트 처리                        |
| Frontend DX         | Storybook 빌더를 webpack에서 Vite로 전환해 cold build **28.9초 → 13.9초** 개선       |
| Web Performance     | 코드 스플리팅 최적화로 Lighthouse Performance **63 → 73**, FCP **3.1초 → 2.2초** 개선 |
| Security            | Refresh Token 저장 방식을 `localStorage`에서 **HttpOnly Cookie** 기반으로 전환       |
| Quality             | Playwright E2E 테스트, GitHub Actions CI/CD, AWS S3·CloudFront 자동 배포 환경 구축 |
| Team Productivity   | AI 개발 워크플로우와 팀 컨벤션을 정리해 개발 생산성 개선                                       |

---

## 🎮 Featured Project — Game Park

> 설치 없이 브라우저에서 바로 즐기는 무료 웹 게임 플랫폼

<p>
  <a href="https://game-park-yrss.vercel.app/">
    <img src="https://img.shields.io/badge/Live%20Demo-Game%20Park-1A1A5E?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Game Park Live Demo" />
  </a>
</p>

게임 플랫폼 구조, 개별 게임, UI/UX, 브랜드 자산, 개발 워크플로우까지 전반을 설계·개발한 개인 프로젝트입니다.

* `iframe + postMessage` 프로토콜 기반의 독립 게임 통합 아키텍처 설계
* React·Next.js 기반 플랫폼과 게임별 독립 실행 구조 구현
* Claude Code 기반 AI 개발 워크플로우 및 게임 보일러플레이트 설계
* 실시간 멀티플레이 퍼즐 게임 **Kaboom**
* 매일 새로운 퍼즐을 제공하는 한국어 워들 게임 **한들**
* Canvas 기반 로그라이크 타워 디펜스 게임 **신화 디펜스**
* 랭킹, 로그인, 게임 목록, 의견 수집 등 플랫폼 기능 구현
* 게임 제작을 위한 기획·에셋·구현·검증 과정을 AI와 결합해 반복 가능한 개발 프로세스로 정리

<p>
  <a href="https://game-park-yrss.vercel.app/">
    <strong>→ Game Park 플레이하기</strong>
  </a>
</p>

---

## 🛠 Tech Stack

### Frontend

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000000" alt="JavaScript" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=000000" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

### State · UI · Testing

<p>
  <img src="https://img.shields.io/badge/Zustand-443E38?style=flat-square&logo=react&logoColor=white" alt="Zustand" />
  <img src="https://img.shields.io/badge/React_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white" alt="React Query" />
  <img src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white" alt="React Hook Form" />
  <img src="https://img.shields.io/badge/Tiptap-000000?style=flat-square&logo=tiptap&logoColor=white" alt="Tiptap" />
  <img src="https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white" alt="Storybook" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
</p>

### Backend · Data · Infra

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS" />
  <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.IO" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

---

## 🧭 What I Care About

```text
01. 실제 사용자의 업무 흐름에서 문제를 발견하고 측정 가능한 개선을 만드는 것
02. 유지보수 가능한 컴포넌트 구조와 예측 가능한 상태 관리
03. 요구사항, API 계약, 예외 처리를 사전에 명확히 하는 협업
04. 성능, 보안, 테스트, 배포까지 책임지는 프론트엔드 개발
05. AI를 단순한 코드 생성 도구가 아닌 제품 개발 프로세스 개선 수단으로 활용하는 것
```

---

## 📚 Background

* **더블티** — Frontend Developer
  그룹웨어 SaaS, Electron 채팅 앱, 글로벌 B2B/B2C 해외 직구 플랫폼 프론트엔드 개발

* **태백넷** — Frontend Developer
  AI 이미지 처리 SaaS 프론트엔드 전반 설계·개발 및 운영

* **SSAFY 8기** — Web Development Track

* **42 Seoul** — Innovation Academy

---

## 📊 Algorithm

<p align="center">
  <a href="https://solved.ac/tykimdream">
    <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=tykimdream" width="280" alt="Solved.ac Profile" />
  </a>
</p>

---

<p align="center">
  <a href="https://pikan.dev/ko">Portfolio</a>
  ·
  <a href="https://game-park-yrss.vercel.app/">Game Park</a>
  ·
  <a href="mailto:tykimdream@gmail.com">Email</a>
</p>
