<p align="center">
  <img
    width="100%"
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,45:1d4ed8,100:06b6d4&height=220&section=header&text=Yongjae%20Kwon&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Web%20Developer%20%7C%20Operation%20UI%20%7C%20API%20%26%20Data%20Flow&descAlignY=56&descSize=17"
    alt="Yongjae Kwon header"
  />
</p>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img
      src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2800&pause=700&color=38BDF8&center=true&vCenter=true&width=900&lines=I+build+operation-grade+web+systems.;UI+%2B+API+%2B+SQL+%2B+external+integrations.;Vue+%7C+React+%7C+Spring+%7C+FastAPI"
      alt="Typing SVG"
    />
  </a>
</p>

<p align="center">
  <a href="mailto:koj185364@naver.com">
    <img src="https://img.shields.io/badge/Email-koj185364%40naver.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/YongjaeKwon/portfolio">
    <img src="https://img.shields.io/badge/Portfolio-Repository-111827?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio Repository" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=YongjaeKwon&style=for-the-badge&color=38bdf8&label=PROFILE+VIEWS" alt="Profile views" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Production%20Systems-4-38BDF8?style=for-the-badge&labelColor=0f172a" alt="Production systems" />
  <img src="https://img.shields.io/badge/Since-2024.06-22C55E?style=for-the-badge&labelColor=0f172a" alt="Since 2024.06" />
  <img src="https://img.shields.io/badge/PPS%20Personal%20Commits-268-F97316?style=for-the-badge&labelColor=0f172a" alt="PPS personal commits" />
</p>

## About

운영 시스템과 관리자 도구를 개발하며 화면, API, SQL, 외부 연동 흐름을 함께 봅니다.

사용자가 실제로 처리하는 등록, 업로드, 발송, 조회, 이력 확인 흐름이 끊기지 않도록 구현하는 데 관심이 많습니다. 단순히 화면을 만드는 것보다, 권한 조건과 데이터 기준, 외부 연동 결과가 실제 업무 순서와 맞물리는지 확인하며 개발합니다.

```text
I turn messy business workflows into calm, traceable web systems.
```

## Engineering Focus

| Area | What I Care About |
| --- | --- |
| Operation UI | 운영자가 반복해서 쓰는 목록, 상세, 검색, 발송, 이력 확인 화면을 안정적으로 구현합니다. |
| API & State | 성공, 실패, 대기, 예외 응답을 화면 메시지와 버튼 상태로 연결합니다. |
| Data Conditions | 권한, 조직, 기간, 상태값이 SQL과 화면 필터에서 같은 기준으로 동작하는지 확인합니다. |
| Integration | 메일, 파일, 엑셀, 인증, 알림 발송처럼 실패 케이스가 있는 연동 흐름을 다룹니다. |
| Product Thinking | 사용자가 어떤 업무를 끝내야 하는지부터 보고, 기능 단위보다 흐름 단위로 구현합니다. |

## System Map

```mermaid
flowchart LR
  A["Field / Admin User"] --> B["Vue · React · WebSquare · Nexacro UI"]
  B --> C["REST API · Spring Boot · Spring MVC"]
  C --> D["Service Logic · Permission Rules"]
  D --> E["MyBatis · SQL · MariaDB · Oracle"]
  C --> F["Mail · File · Excel · OTP · BizTalk"]
  E --> G["Dashboards · Reports · Histories"]
  F --> G
```

## Stack

<p align="center">
  <img
    src="https://skillicons.dev/icons?i=ts,vue,react,nextjs,js,html,css,tailwind,java,spring,py,fastapi,mysql,postgres,redis,docker,git,nginx,vite&perline=10"
    alt="Tech stack icons"
  />
</p>

**Frontend**

Vue, React, Next.js, TypeScript, JavaScript, HTML, CSS, TailwindCSS, WebSquare, Nexacro, JSP, jQuery

**Backend & Data**

Java, Spring Boot, Spring MVC, Spring Security, MyBatis, FastAPI, Python, MariaDB, Oracle, PostgreSQL, Redis

**Tools & Workflow**

Git, SVN, Docker, Docker Compose, Nginx, Vite, Maven, Gradle, Tabulator, Chart.js

## Featured Work

| Project | Role | Impact |
| --- | --- | --- |
| TGS 협력사 포탈 시스템 | Backend + Vue UI | 교육 등록, 대상자 업로드, 메일 발송, 제출 현황 조회, 댓글 공통화, OTP 예외 처리를 구현했습니다. |
| TSMS / IDCMS AS 업무 시스템 | Frontend Lead | 모바일 AS 접수, 개인정보 동의, QR 확인, 태블릿 전자서명, 알림톡 결과 처리 흐름을 개발했습니다. |
| 교육청 IT 자산관리 솔루션 | Backend + UI | 권한별 조회 범위, 자산 현황, 대시보드 집계, 상태 변경, 이력 조회 흐름을 개선했습니다. |
| SR30 물류관리시스템 | Operation Feature Development | 일정, 설문, 물류·재고, 리포트, KPI, 엑셀 다운로드, 관리자 이력 조회 기능을 개선했습니다. |

## Open Projects

| Project | What It Shows | Link |
| --- | --- | --- |
| Portfolio | 역할 관점별로 실무 경험을 보여주는 Vue 기반 포트폴리오 | [Repository](https://github.com/YongjaeKwon/portfolio) |
| agent-bridge | AI를 활용한 블로그 포스팅 지원 프로그램 | [Repository](https://github.com/YongjaeKwon/agent-bridge) |
| SSAFAST | API 명세, 요청 테스트, 유스케이스 테스트, 성능 테스트를 연결한 SSAFY 팀 프로젝트 | [Repository](https://github.com/SSAFAST/ssafast) |
| MODAC | 개발자가 학습 내용을 기록하고 공유할 수 있는 Vue 기반 학습 기록 플랫폼 | [Repository](https://github.com/YongjaeKwon/MODAC) |
| ddoing | 그림 그리기와 AI 추론을 연결한 React 기반 영어 학습 서비스 | [Repository](https://github.com/GomGom-Team/ddoing) |
| quant-core | React/FastAPI 기반 퀀트 트레이딩 시스템 학습 프로젝트 | Private Lab |

## GitHub Metrics

<p align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=YongjaeKwon&theme=github_dark" alt="GitHub profile details" />
</p>

<p align="center">
  <img width="32.5%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=YongjaeKwon&theme=github_dark" alt="Repos per language" />
  <img width="32.5%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=YongjaeKwon&theme=github_dark" alt="Most commit language" />
  <img width="32.5%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=YongjaeKwon&theme=github_dark&utcOffset=9" alt="Productive time" />
</p>

<p align="center">
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=YongjaeKwon&theme=github_dark" alt="GitHub stats" />
  <img width="49%" src="https://streak-stats.demolab.com?user=YongjaeKwon&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=YongjaeKwon&theme=react-dark&hide_border=true&area=true&custom_title=Contribution%20Graph" alt="Contribution graph" />
</p>

<p align="center">
  <img
    width="100%"
    src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,45:1d4ed8,100:0f172a&height=120&section=footer"
    alt="Footer wave"
  />
</p>
