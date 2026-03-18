# Hello, I'm SeongJin. 👋

> **팀워크를 중요시하는 개발자입니다.**  
> 함께 만들어가는 과정에서 더 좋은 결과가 나온다고 믿습니다.

<br/>

## 🏆 수상 & 자격증

> 🥇 **2026 블레이버스 MVP 개발 해커톤 — 팀워크상** 🏅

| 구분 | 내용 | 연도 |
|------|------|------|
| 🥇 수상 | 2026 블레이버스 MVP 개발 해커톤 — **팀워크상** | 2026 |
| 🥇 수상 | 2026 월간 해커톤: 바이브 코딩 개선 AI 아이디어 공모전 | 2026 |
| 📜 자격증 | 정보처리기사 필기 | - |

<br/>

## 💼 경험

- 🏥 **범일정보 현장실습** — 소리 기반 낙상 감지 및 보호자 알림 시스템 개발
- 🤝 **INNOV** — 경북 연합 공모전 동아리 활동

<br/>

## 🛠️ 프로젝트

### 🛡️ 낙상 지킴이 (AudioFallCare)
> 소리 기반 낙상 감지 및 보호자 알림 시스템 | 범일정보 현장실습

마이크 오디오를 실시간으로 수집·분석하여 낙상 사고를 자동 감지하고, 보호자에게 즉시 알림을 전송하는 시스템입니다.

**담당 역할 (백엔드 + AI 모델)**
- WebSocket 기반 실시간 오디오 스트리밍 서버 개발
- 낙상 감지 AI 모델 개발 — 오디오 데이터 전처리 및 분류 모델 구현
- 낙상 여부·신뢰도·소리 유형(Impact, Scream, Thud 등) 분류 API 설계
- 보호자 ↔ 피보호자 연결 코드 발급·검증 및 알림 전송 백엔드 구현
- 사고 이력 및 위험도 저장·조회 API 개발

[![배포](https://img.shields.io/badge/배포-Vercel-000000?style=flat-square&logo=vercel)](https://audio-fall-care-web.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-AudioFallCare-181717?style=flat-square&logo=github)](https://github.com/AudioFallCare/AudioFallcare_docs)

---

### 📋 통합 협업 + AI 작성 도우미 게시판 플랫폼
> React + TypeScript + Vite / Spring Boot | 풀스택

게시판, 칸반 보드, AI 작성 도우미를 하나의 플랫폼에 통합하여 팀 협업 효율을 극대화한 프로젝트입니다.

**담당 역할 (풀스택)**
- React 18 + TypeScript + Vite 기반 프론트엔드 전체 설계 및 구현
- 칸반 보드 시스템 — `@dnd-kit` 활용 드래그 앤 드롭, TODO / IN_PROGRESS / DONE 상태 관리
- TanStack Query 낙관적 업데이트로 실시간 동기화
- Quill.js Rich Text Editor, 캔버스 그림 그리기, 다중 파일 업로드
- Spring Boot 기반 백엔드 API 설계 및 구현
- JWT 인증 / 인가 시스템, AI 작성 도우미 (Ollama) 연동

[![Frontend](https://img.shields.io/badge/GitHub-Frontend-181717?style=flat-square&logo=github)](https://github.com/FAITRUEE/board_web)
[![Backend](https://img.shields.io/badge/GitHub-Backend-181717?style=flat-square&logo=github)](https://github.com/FAITRUEE/board_was)

---

### 🎓 설스터디 MVP — 멘토-멘티 학습 관리 플랫폼
> Spring Boot 4.0 + Java 21 | 2026 블레이버스 MVP 개발 해커톤 팀워크상

멘토가 멘티의 학습 플래너를 관리하고 피드백을 제공하는 플랫폼입니다.

**담당 역할 (백엔드)**
- Spring Boot 기반 백엔드 API 전체 설계 및 구현
- JWT 인증 / 인가 시스템 설계 (Stateless, Access Token)
- 과제·플래너·피드백·댓글·주간 리포트 등 전 도메인 RESTful API 개발
- Amazon S3 파일 업로드 통합 (프로필·과제·학습지·피드백 이미지)
- Firebase Cloud Messaging(FCM) 기반 푸시 알림 시스템 구현
- AWS EC2 + RDS + ECR + GitHub Actions CI/CD 파이프라인 구축
- 이미지 좌표 기반 피드백 시스템 설계 (비율 좌표로 해상도 무관 정확도 확보)

[![GitHub](https://img.shields.io/badge/GitHub-BlaybusBE-181717?style=flat-square&logo=github)](https://github.com/BlaybusHackathon/BlaybusBE)

---

### 💡 AI 생성 코드 계보 기반 신뢰 추적 시스템
> 2026 월간 해커톤: 바이브 코딩 개선 AI 아이디어 공모전

바이브 코딩 환경에서 AI 생성 코드의 출처·맥락·신뢰도를 추적하는 시스템을 설계·제안한 아이디어 공모전 프로젝트입니다.

**담당 역할**
- 핵심 아이디어 설계 — GCA(생성 맥락 서명), 세션 단위 계보 추적, 위험 전파 경로 분석
- 계보 그래프 시각화 데모 개발 (DAG 기반, 신뢰 등급 색상 표현)
- GCA 서명 시뮬레이터 구현 (SHA-256 / HMAC-SHA256 실시간 생성)
- 신뢰 점수 계산기 구현 (4개 요소 슬라이더 인터랙티브 계산기)
- 문서 5편 공동 작성 (문제 정의 → 원인 분석 → 개선 아이디어 → 시나리오 → 확장 가능성)

[![GitHub](https://img.shields.io/badge/GitHub-vibe--coding--improvement-181717?style=flat-square&logo=github)](https://github.com/vibe-coding-research/vibe-coding-improvement)

---

### 📚 Let's Study Now — 실시간 스터디 그룹 매칭 플랫폼
> 즉석으로 스터디 그룹을 매칭해주는 웹 서비스

언제든지 접속해 다른 사람들과 함께 공부할 수 있는 환경을 제공합니다.

**담당 역할 (프론트엔드)**
- 회원가입 / 로그인 / 프로필 관리 UI 개발
- 오픈 스터디·그룹 스터디·URL 공유 매칭 흐름 전체 구현
- 스터디룸 기능 개발 — 공부/휴식 상태 표시, 타이머(공부·휴식 시간 설정·자동 전환·알림), 상태메시지
- 체크리스트 CRUD 및 순서 변경, 디데이 설정, 스터디 기록·달성률 조회 기능 구현

[![GitHub](https://img.shields.io/badge/GitHub-Let's--Study--Now-181717?style=flat-square&logo=github)](https://github.com/Let-s-Study-Now/Let-s-Study-Now_web)

<br/>

## 🔧 기술 스택

**Language & Framework**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)

**Database & Infra**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

<br/>

## 🎓 학력

- 영남대학교 컴퓨터공학과 4학년 재학 중

<br/>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=FAITRUEE&show_icons=true&theme=default&hide_border=true" />
</p>
