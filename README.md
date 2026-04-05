# KIM JISEOP | Java Backend Developer

실서비스 API 운영 경험을 바탕으로,  
외부 연동 · 상태 관리 · 정합성 · 배치/스케줄링 · 운영 안정성이 중요한  
백엔드 문제를 운영 관점에서 설계하고 개선해온 Java Backend Developer입니다.

단순 CRUD 구현보다  
예외 처리, 재시도, 장애 복구, 상태 전이, 최종 정합성이 중요한 문제를  
구조적으로 풀어내는 데 강점을 가지고 있습니다.

<br/>

## Summary

현재 사내 백엔드 전임 1인으로 근무하며,  
회사 앱서비스가 호출하는 통합 플랫폼 서버와 사내 공통 External API Gateway의  
설계, 개발, 리팩토링, 운영, 유지보수를 수행하고 있습니다.

충전, 가입자 조회, Mail, 국제 SMS, Push, Daemon, Scheduler, Callback API / Callback Daemon 등  
운영 민감도가 높은 영역을 다루며,  
기능 구현 자체보다 상태 전이, 예외 흐름, 복구 가능성, 최종 정합성이 중요한 문제를 더 중요하게 보고 있습니다.

또한 외부 연동 구조 설계, 레거시 PHP 및 Java 코드 분석 및 Spring Boot / Gradle 구조 리빌딩,  
장애 대응과 운영 안정성 개선을 함께 수행하며  
운영 민감도가 높은 백엔드 문제를 구조적으로 풀어내는 데 집중해왔습니다.

<br/>

## Core Strengths

- **Operational Stability**  
  장애 가능성을 낮추고, 실패 시에도 제어 가능한 흐름을 우선적으로 설계합니다.

- **State Management & Consistency**  
  상태 전이와 최종 정합성을 고려한 백엔드 로직 설계를 중요하게 생각합니다.

- **External Integration Design**  
  다수 외부 시스템 / Provider 연동에서 분기 처리, 예외 대응, 응답 표준화 구조를 설계해왔습니다.

- **Batch / Scheduler / Long-running Process**  
  운영형 배치, Scheduler, Daemon 구조에서 실행 제어, 재시도, 운영 가시성을 함께 고려합니다.

- **Legacy Analysis & Refactoring**  
  기존 구조를 빠르게 파악하고, 운영 리스크를 줄이는 방향으로 점진적으로 개선해왔습니다.

<br/>

## Experience

### Backend Developer | 2024.05 - Present

- 앱 서비스 API 서버에서 충전, 가입자 조회, Mail, 국제 SMS, Push, Daemon, Scheduler 영역을 전담하며 설계, 개발, 리팩토링, 운영, 유지보수를 수행했습니다.
- 외부 시스템 연동 과정에서 발생하는 상태 불일치, 예외 처리, 재시도 요구를 고려해 운영 가능한 구조로 로직과 처리 흐름을 정비했습니다.
- 레거시 PHP 및 Java 기반 코드를 분석한 뒤 Spring Boot · Gradle 구조로 리빌딩하며 유지보수성과 구조 이해도를 높였습니다.
- 외부 연동 업체와의 커뮤니케이션부터 테스트, 상용 반영까지 직접 수행하며 실서비스 적용 전 과정을 경험했습니다.
- 장애 대응과 운영 안정성을 우선하는 관점에서 구조를 개선하며, 장기적으로 관리 가능한 백엔드 시스템을 만드는 데 집중했습니다.

### Software Engineer | Automation Equipment Software | 2018.10 - 2023.10

- 산업기능요원으로 복무하며 자동화 설비 프로젝트에 참여했고, 입사 약 1년 이후부터는 단독으로 PM 역할을 맡아 소프트웨어 및 전장 설계 파트를 주도했습니다.
- 설비 제어 로직과 전장 구성을 설계하고, 현장 셋업·시운전·안정화 과정까지 직접 수행하며 프로젝트 완료까지 책임졌습니다.
- 국내 주요 산업 현장에서 짧게는 1개월, 길게는 약 1.5년의 장기 출장을 수행했고, 베트남(1개월), 중국(6개월), 인도(1개월), 미국(1개월) 등 해외 현장 대응 경험도 보유하고 있습니다.
- 설계, 일정 대응, 현장 이슈 해결, 안정화까지 직접 경험하며 복잡한 프로젝트를 끝까지 책임지는 역량을 길렀습니다.

<br/>

## Representative Projects

### 1. [provider-integration-gateway](https://github.com/Gseobi/provider-integration-gateway)
다수 Provider / PG 연동 환경에서 Provider 선택, 요청 구성, 응답 표준화를 Backend 게이트웨이로 분리해 설계한 프로젝트

- Provider별 분기 책임을 명확히 분리
- 공통 응답 구조를 표준화하여 호출부 복잡도 축소
- 확장 가능한 라우팅 구조를 통해 새로운 Provider 추가 비용을 낮추는 방향으로 설계

### 2. [ops-scheduler-batch-jobs](https://github.com/Gseobi/ops-scheduler-batch-jobs)
운영형 배치에서 중요한 중복 실행 제어, 재시도 흐름, 운영 가시성을 구조화한 Scheduler / Batch 프로젝트

- 시간 분산 실행과 실행 제어 구조를 명확히 분리
- 실패 시 재시도 흐름과 운영 로그 포인트를 고려
- 단순 스케줄 등록이 아니라 운영 환경 기준의 실행 안정성을 우선해 설계

### 3. [java-socket-daemon-springboot](https://github.com/Gseobi/java-socket-daemon-springboot)
DB 기반 작업 Polling, 암·복호화, Socket 송수신, 결과 반영 흐름을 분리해 장기 실행 Provider 연동 Daemon 구조를 설계한 프로젝트

- 장기 실행 프로세스에서 필요한 설정 분리, 타임아웃, 재시도, 예외 처리 구조 반영
- 암·복호화와 통신 책임을 분리해 문제 발생 지점을 추적 가능하게 설계
- 단순 Socket 연동이 아니라 운영 가능한 Daemon 구조를 목표로 정리

### 4. [realtime-caching-gateway](https://github.com/Gseobi/realtime-caching-gateway)
Redis를 실시간 처리 및 캐시 계층으로 활용하고, PostgreSQL fallback / synchronization 구조로 성능과 복구 가능성을 함께 고려한 프로젝트

- 캐시 적중뿐 아니라 full miss / partial miss 이후 recovery flow까지 고려
- 캐시 처리와 DB 동기화 책임을 분리
- 성능, 복구 가능성, 최종 정합성을 함께 보는 구조를 목표로 설계

### 5. [deferred-deeplink-backend](https://github.com/Gseobi/deferred-deeplink-backend)
광고 클릭 이후 앱 설치 전/후가 분리되는 흐름에서 서버 기준 추적, 검증, 상태 연결 구조를 설계한 프로젝트

- 설치 전/후가 분리된 흐름을 서버 기준으로 연결
- 위변조 방지와 유입 식별 검증을 고려
- 단순 URL 생성이 아니라 추적, 검증, 상태 연결 구조를 목표로 설계

<br/>

## Tech Stack

### Main
- Java
- Spring Boot
- MyBatis
- Oracle
- Gradle

### Production Experience
- REST API
- External Integration
- Scheduler
- Daemon
- Callback API
- Callback Daemon
- Linux
- Tomcat

### Working Knowledge
- Redis
- Docker
- PostgreSQL
- JPA
- QueryDSL

### Previous Engineering Background
- Ladder Logic
- Script-based Control Logic
- Equipment Setup / Maintenance / Field 대응

<br/>

## Links

- **GitHub**: [github.com/Gseobi](https://github.com/Gseobi)
- **LinkedIn**: [linkedin.com/in/jiseop-kim-3983813b9](https://www.linkedin.com/in/jiseop-kim-3983813b9/)
- **Email**: [wsx2386@naver.com](mailto:wsx2386@naver.com)

<br/>

## Notes

이 문서는 채용공고별 제출용 이력서가 아니라,  
GitHub 메인 프로필에 연결하기 위한 **공개용 Resume** 기준으로 작성했습니다.

지원 회사별로 강조 포인트를 조정한 제출용 이력서는 별도로 관리하고,  
이 문서는 공통적으로 보여주고 싶은 경력 방향과 대표 경험 중심으로 유지하는 것을 기준으로 합니다.
