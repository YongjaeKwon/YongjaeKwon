# 권용재 · Yongjae Kwon

**Java/Spring 기반 업무 시스템을 개발하는 웹 개발자입니다.**

요구사항을 화면·API·SQL로 구현하고, 사용자 검수와 배포까지 담당합니다.
개인 프로젝트에서는 동시 요청과 데이터 오류를 다루는 방법을 구현하고 테스트로 확인합니다.

[포트폴리오](https://www.yongjaekwon.com/) · [백엔드 이력서](https://www.yongjaekwon.com/resume-backend.pdf) · [프론트엔드 이력서](https://www.yongjaekwon.com/resume.pdf) · [Email](mailto:yongjae116@gmail.com)

## 실무에서 개선한 문제

- **대량 파일 처리 — B2B 협력사 포털(PPS)**<br>
  첨부파일 300~400건의 압축 요청을 비동기 작업으로 분리했습니다. 작업 ID로 진행·실패·완료 상태를 조회하고, 새로고침 뒤에도 같은 작업을 확인할 수 있도록 화면과 서버를 연결했습니다.
- **외부 API 연동 — 교육용 단말 운영 시스템(TSMS)**<br>
  25개 화면의 외부 API 호출을 공통 서버 경로로 옮겼습니다. 브라우저에 있던 API 키를 서버 설정으로 옮기고, 기존 화면의 입력·응답 형식을 유지했습니다.

실무에서는 **Java · Spring · MyBatis · SQL · Vue/WebSquare · Jenkins**를 사용합니다.
담당 범위와 설계 이유는 [상세 사례](https://www.yongjaekwon.com/#projects)에 정리했습니다. 사내 코드는 비공개입니다.

## 공개 코드로 살펴볼 프로젝트

| 프로젝트 | 구현한 내용 | 확인할 부분 |
| --- | --- | --- |
| **[티켓러시](https://github.com/YongjaeKwon/ticket-rush)** · 개인 | Java/Spring 기반 대기열·좌석 선점·예매 처리 | 같은 좌석의 동시 요청, 홀드 만료, 중복 확정을 다루는 코드와 통합 테스트 |
| **[데이터 데모](https://github.com/YongjaeKwon/quant-lab)** · 개인 | Python/FastAPI · React로 연결한 합성 데이터 파이프라인과 대시보드 | 재실행 시 중복 방지, 잘못된 시계열 입력 거부, API와 화면 상태 테스트 |
| **[포트폴리오](https://github.com/YongjaeKwon/portfolio)** · 개인 | Vue 3 · TypeScript로 구현한 경력·프로젝트 사이트 | 상세 콘텐츠 지연 로딩, 공통 UI, 프로젝트별 브라우저 데모 |

각 저장소의 README에서 구현 코드, 테스트와 실행 방법으로 이동할 수 있습니다.
티켓러시는 개발 중이며, 데이터 데모는 합성 데이터로 동작합니다.

<details>
<summary>팀 프로젝트와 담당 기능</summary>

| 프로젝트 | 제가 맡은 부분 |
| --- | --- |
| [SSAFAST](https://github.com/SSAFAST/ssafast) · Next.js/React | 동적 API 명세 입력 폼과 성능 테스트 화면 |
| [또잉](https://github.com/GomGom-Team/ddoing) · React/Canvas | 그림 입력, AI 판별 API 연계, 점수·게임 상태 흐름 |
| [MODAC](https://github.com/YongjaeKwon/MODAC) · Vue | 스터디룸, 게시글·마이페이지 화면과 실시간 참여 상태 연동 |

</details>
