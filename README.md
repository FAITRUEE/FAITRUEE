<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:30363d&height=200&section=header&text=FAITRUEE&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Frontend%20%7C%20Backend&descAlignY=58&descSize=18&descColor=8b949e)

</div>

<p align="center">
  <img src="https://render.gitanimals.org/farms/FAITRUEE?loading" />
</p>

<br/>

<div align="center">

*팀워크를 중요시하는 개발자입니다.*  
*함께 만들어가는 과정에서 더 좋은 결과가 나온다고 믿습니다.*

</div>

---

<br/>

## 🏆 &nbsp;Awards & Certifications

| | |
|---|---|
| 🥇 | 2026 블레이버스 MVP 개발 해커톤 — **팀워크상** |
| 📜 | 정보처리기사 필기 |

<br/>

---

## 💼 &nbsp;Experience

```
🏥  (주)범일정보 현장실습
🤝  경북 연합 공모전 동아리 INNOV
🎓  영남대학교 컴퓨터공학과 4학년 재학 중
```

<br/>

---

## 🛠 &nbsp;Projects

<details>
<summary><b>🛡️ &nbsp;낙상 지킴이 (AudioFallCare)</b> &nbsp;·&nbsp; Backend · AI Model &nbsp;·&nbsp; 범일정보 현장실습</summary>

<br/>

> 마이크 오디오를 실시간으로 수집·분석하여 낙상 사고를 자동 감지하고, 보호자에게 즉시 알림을 전송하는 시스템

- WebSocket 기반 실시간 오디오 스트리밍 서버 개발
- 낙상 감지 AI 모델 개발 — 오디오 데이터 전처리 및 분류 모델 구현
- 낙상 여부·신뢰도·소리 유형(Impact, Scream, Thud 등) 분류 API 설계
- 보호자 ↔ 피보호자 연결 코드 발급·검증 및 알림 전송 백엔드 구현
- 사고 이력 및 위험도 저장·조회 API 개발

[![Demo](https://img.shields.io/badge/DEMO-live-4CAF50?style=flat-square&logo=vercel&logoColor=white)](https://audio-fall-care-web.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-repo-30363d?style=flat-square&logo=github)](https://github.com/orgs/AudioFallCare/repositories)

</details>

<details>
<summary><b>📋 &nbsp;통합 협업 + AI 작성 도우미 게시판</b> &nbsp;·&nbsp; Fullstack</summary>

<br/>

> 게시판·칸반 보드·AI 작성 도우미를 하나의 플랫폼에 통합한 협업 툴

- React 18 + TypeScript + Vite 기반 프론트엔드 전체 설계 및 구현
- 칸반 보드 — `@dnd-kit` 드래그 앤 드롭, TODO / IN_PROGRESS / DONE 상태 관리
- TanStack Query 낙관적 업데이트, Quill.js Rich Text Editor, 다중 파일 업로드
- Spring Boot 백엔드 API 설계 및 구현, JWT 인증 / 인가 시스템
- AI 작성 도우미 (Ollama) 연동

[![Frontend](https://img.shields.io/badge/GitHub-frontend-30363d?style=flat-square&logo=github)](https://github.com/FAITRUEE/board_web)
[![Backend](https://img.shields.io/badge/GitHub-backend-30363d?style=flat-square&logo=github)](https://github.com/FAITRUEE/board_was)

</details>

<details>
<summary><b>🎓 &nbsp;설스터디 MVP</b> &nbsp;·&nbsp; Backend &nbsp;·&nbsp; 2026 블레이버스 해커톤 팀워크상</summary>

<br/>

> 멘토가 멘티의 학습 플래너를 관리하고 피드백을 제공하는 플랫폼

- Spring Boot 기반 백엔드 API 전체 설계 및 구현
- JWT 인증 / 인가 시스템 설계 (Stateless, Access Token)
- 과제·플래너·피드백·댓글·주간 리포트 전 도메인 RESTful API 개발
- Amazon S3 파일 업로드 통합, FCM 기반 푸시 알림 시스템 구현
- AWS EC2 + RDS + ECR + GitHub Actions CI/CD 파이프라인 구축
- 이미지 좌표 기반 피드백 시스템 설계 (비율 좌표, 해상도 무관)

[![GitHub](https://img.shields.io/badge/GitHub-repo-30363d?style=flat-square&logo=github)](https://github.com/BlaybusHackathon)

</details>

<details>
<summary><b>💡 &nbsp;AI 코드 계보 기반 신뢰 추적 시스템</b> &nbsp;·&nbsp; 2026 바이브 코딩 개선 AI 아이디어 공모전</summary>

<br/>

> 바이브 코딩 환경에서 AI 생성 코드의 출처·맥락·신뢰도를 추적하는 시스템 설계·제안

- GCA(생성 맥락 서명), 세션 단위 계보 추적, 위험 전파 경로 분석 설계
- 계보 그래프 시각화 데모 (DAG 기반, 신뢰 등급 색상 표현)
- GCA 서명 시뮬레이터 (SHA-256 / HMAC-SHA256 실시간 생성)
- 신뢰 점수 계산기 (4개 요소 슬라이더 인터랙티브 계산기)
- 문서 5편 공동 작성 (문제 정의 → 원인 분석 → 개선 아이디어 → 시나리오 → 확장)

[![GitHub](https://img.shields.io/badge/GitHub-repo-30363d?style=flat-square&logo=github)](https://github.com/vibe-coding-research/vibe-coding-improvement)

</details>

<details>
<summary><b>📚 &nbsp;Let's Study Now</b> &nbsp;·&nbsp; Frontend &nbsp;·&nbsp; 실시간 스터디 그룹 매칭</summary>

<br/>

> 즉석으로 스터디 그룹을 매칭해주는 웹 서비스

- 회원가입 / 로그인 / 프로필 관리 UI 개발
- 오픈 스터디·그룹 스터디·URL 공유 매칭 흐름 전체 구현
- 스터디룸 — 공부/휴식 상태 표시, 타이머(자동 전환·알림), 상태메시지
- 체크리스트 CRUD·순서 변경, 디데이 설정, 스터디 기록·달성률 조회

[![GitHub](https://img.shields.io/badge/GitHub-repo-30363d?style=flat-square&logo=github)](https://github.com/orgs/Let-s-Study-Now/repositories)

</details>

<br/>

---

## ⚙️ &nbsp;Tech Stack

![Java](https://img.shields.io/badge/Java-0d1117?style=flat-square&logo=openjdk&logoColor=f89820)
![Spring](https://img.shields.io/badge/Spring-0d1117?style=flat-square&logo=spring&logoColor=6DB33F)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=3178C6)
![React](https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=next.js&logoColor=ffffff)
![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB)
![MySQL](https://img.shields.io/badge/MySQL-0d1117?style=flat-square&logo=mysql&logoColor=4479A1)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ED)
![AWS](https://img.shields.io/badge/AWS-0d1117?style=flat-square&logo=amazonwebservices&logoColor=FF9900)

<br/>

---

## 📊 &nbsp;Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=FAITRUEE&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=ffffff&text_color=8b949e&icon_color=58a6ff" />
&nbsp;&nbsp;
<img height="160" src="https://streak-stats.demolab.com?user=FAITRUEE&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=30363d&ring=58a6ff&fire=ff6b6b&currStreakLabel=ffffff&sideLabels=8b949e&dates=8b949e" />

</div>

<br/>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:30363d,100:0d1117&height=100&section=footer)
