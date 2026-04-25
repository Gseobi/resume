# KIM JISEOP | Resume

> 단순 기능 구현보다,  
> 서비스 사용자 경험과 운영자의 관리 편의를 함께 고려하며  
> 상태 변화, 실패 분기, 복구 가능성을 구조적으로 정리해 문제를 풀어내는 Backend Developer입니다.

## Summary

Java / Spring 기반 실서비스 운영 경험을 바탕으로,
외부 연동 · 상태 관리 · 정합성 · 운영 자동화처럼
운영 민감도가 높은 백엔드 문제를 구조적으로 설계하고 개선해왔습니다.

현재는 통합 플랫폼 서버와 공통 External API Gateway 영역을 담당하며,  
조회, 충전, 메시징, Callback, 비동기 후속 처리처럼  
한 번의 요청으로 끝나지 않는 흐름을 주로 다루고 있습니다.

## Core Strengths

- **Problem Structuring**  
  기능 구현보다 먼저 상태 변화, 실패 지점, 운영 기준을 정리합니다.

- **Operational Stability**  
  장애를 줄이는 것뿐 아니라, 장애 시에도 복구 가능한 흐름을 우선 설계합니다.

- **State & Consistency**  
  상태 전이와 최종 정합성이 중요한 흐름을 구조적으로 설계합니다.

- **Integration Boundary**  
  외부 시스템 차이를 내부 경계에서 흡수하고 표준화하는 구조에 익숙합니다.

- **Language Adaptability**  
  새로운 언어와 코드베이스도 문법보다 구조와 구현 의도를 먼저 이해하며 적응합니다.
  
## Experience

### Backend Developer | 2024.05 - Present
- 앱 서비스 API 서버와 공통 External API Gateway를 중심으로 충전, 가입자 조회, Mail, 국제 SMS, Push, Daemon, Scheduler 영역의 설계·개발·운영을 담당
- 외부 Provider 연동 과정에서 발생하는 요청/응답 차이, 인증 방식, timeout, 실패 분기, 후속 처리 문제를 운영 가능한 구조로 정리
- 분산되어 있던 외부 API 호출 로직을 공통 설정과 호출 흐름 중심으로 리팩토링해, 연동사 변경 대응과 장애 원인 추적이 쉬운 구조로 개선
- PHP / Java 기반 레거시 Callback API 및 Daemon 구조를 Spring Boot · Gradle 기반으로 리빌딩하며 유지보수성과 구조 이해도를 개선
- 외부 연동 업체와의 커뮤니케이션, 테스트, 상용 반영, 운영 대응까지 직접 수행하며 실서비스 적용 전 과정을 경험

### Software Engineer | Automation Equipment Software | 2018.10 - 2023.10
- 현장 운영 안정성과 예외 대응이 중요한 환경에서 프로젝트 수행
- 시스템 흐름과 운영 관점에서 문제를 구조적으로 해석하는 기반을 쌓음

## Selected Projects

### [commerce-orchestration-backend](https://github.com/Gseobi/commerce-orchestration-backend)
주문 이후 payment · settlement · notification · outbox 흐름을  
Orchestration, explicit state transition, compensation, retry/dead-letter, admin recovery 관점으로 설계한 프로젝트

`Transaction Flow` · `Explicit State` · `Compensation / Recovery`

### [provider-integration-gateway](https://github.com/Gseobi/provider-integration-gateway)
다수 Provider / PG 연동에서 Provider 선택, 요청 구성, 응답 표준화 책임을 
Gateway 계층으로 분리한 프로젝트

`External Integration` · `Strategy Pattern` · `Response Standardization`

### [realtime-caching-gateway](https://github.com/Gseobi/realtime-caching-gateway)
Scheduler 기반 배치 작업을 중복 실행 제어, retry, 운영 가시성 관점으로 구조화한 프로젝트

`Scheduler` · `Retry Flow` · `Execution Control`

## Tech Stack

**Language**  
Java (main), JavaScript  
Kotlin / Python 등 문서·코드 이해 기반의 구조 중심 적응 가능

**Framework**  
Spring, Spring Boot, WebClient, MyBatis, JPA, QueryDSL

**Database**  
Oracle, MySQL, PostgreSQL, Redis
