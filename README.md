# 권용재 · Yongjae Kwon

**Java/Spring으로 업무 시스템을 개발하는 웹 개발자입니다.**

B2B 협력사 포털과 교육용 단말 운영 시스템에서 요구사항 협의부터 화면·API·SQL 개발, 검수와 배포까지 담당하고 있습니다.

작업이 오래 걸릴 때 무엇을 보여줄지, 같은 요청이 다시 들어오면 어떻게 처리할지에 관심이 있습니다. 사용자가 현재 상황을 이해할 수 있는 화면과, 재시도해도 데이터가 어긋나지 않는 처리 흐름을 함께 고민합니다.

[포트폴리오](https://www.yongjaekwon.com/) · [백엔드 이력서](https://www.yongjaekwon.com/resume-backend.pdf) · [프론트엔드 이력서](https://www.yongjaekwon.com/resume.pdf) · [이메일](mailto:yongjae116@gmail.com)

## 개발할 때 중요하게 생각하는 것

### 사용자가 겪는 문제에서 시작합니다

협력사 포털에서는 첨부파일 300~400건을 압축하는 동안 요청이 오래 유지되고, 사용자가 진행 상황을 알기 어려웠습니다. 압축을 비동기 작업으로 분리하고 진행·실패·완료 상태를 화면에 연결했습니다. 새로고침 뒤에도 같은 작업을 다시 확인할 수 있도록 작업 ID를 기준으로 처리했습니다.

### 실패와 재시도도 기능의 일부로 다룹니다

티켓러시에서는 좌석 선점 시간이 지난 뒤 결제를 요청하거나, 결제 결과를 받지 못한 상황을 구분해 처리했습니다. 상태 변경과 재시도 판단을 테스트로 확인하고, 검증한 범위와 남은 과제도 문서에 함께 정리했습니다.

### 변경할 곳을 줄이고, 판단 근거를 남깁니다

교육용 단말 운영 시스템에서는 25개 화면의 외부 API 호출을 공통 서버 경로로 옮겼습니다. API 키를 서버 설정으로 옮기면서 기존 화면의 입력과 응답 형식을 유지했습니다. 개인 프로젝트에서는 선택지와 제약을 [설계 결정 기록](https://github.com/YongjaeKwon/ticket-rush/tree/main/docs/adr)에 정리하고 있습니다.

실무에서 맡은 범위와 구현 배경은 [상세 사례](https://www.yongjaekwon.com/#projects)에서 확인할 수 있습니다. 사내 코드는 공개하지 않습니다.

## 공개 프로젝트

### [티켓러시](https://github.com/YongjaeKwon/ticket-rush) · 동시 요청과 예매 상태

Java/Spring 기반의 개인 예매 시스템입니다. Redis의 좌석 선점과 DB의 최종 확정 제약을 나누고, 실제 MySQL·Redis를 사용하는 테스트로 경쟁 요청과 만료 상황을 확인합니다. 웹 예매 흐름을 함께 구현하고 있으며 결제는 모의 결제로 동작합니다.

### [데이터 검증·조회 데모](https://github.com/YongjaeKwon/quant-lab) · 반복 실행과 데이터 일관성

합성 데이터를 저장·검증하고 FastAPI와 React로 조회하는 개인 프로젝트입니다. 같은 날짜의 데이터를 중복 없이 갱신하고, 잘못된 시계열 입력은 저장 전에 걸러냅니다. 화면에서는 조회 실패와 빈 결과를 구분합니다.

### [포트폴리오](https://github.com/YongjaeKwon/portfolio) · 정보와 화면의 구성

Vue 3와 TypeScript로 만든 사이트입니다. 소개 데이터를 화면 코드에서 분리하고 상세 내용과 데모를 필요할 때 불러옵니다. 모달의 키보드 이동과 데모 종료 시 상태 정리도 다룹니다.

<details>
<summary><strong>팀 프로젝트와 담당한 기능</strong></summary>

| 프로젝트 | 제가 맡은 부분 |
| --- | --- |
| [SSAFAST](https://github.com/SSAFAST/ssafast) · Next.js/React | 동적 API 명세 입력 폼과 성능 테스트 화면 |
| [또잉](https://github.com/GomGom-Team/ddoing) · React/Canvas | 그림 입력, AI 판별 API 연계, 점수와 게임 진행 상태 관리 |
| [MODAC](https://github.com/YongjaeKwon/MODAC) · Vue | 스터디룸, 게시글·마이페이지 화면, 실시간 참여 상태 연동 |

</details>
