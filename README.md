# 하루배움 (HaruBaeum) - 매일 성장하는 개발자를 위한 통합 학습 관리 플랫폼

멋쟁이사자처럼 백엔드 부트캠프 25기 3차 심화 프로젝트, 개발자 맞춤형 통합 학습 관리 플랫폼 하루배움(HaruBaeum) 저장소입니다.  
수강생의 체계적인 학습 진도 추적, 강사의 커리큘럼 및 과제 피드백, 관리자의 무인 배치 정산 및 AI 학사 행정 지원을 결합한 엔터프라이즈급 학습 관리 시스템(LMS)을 구현하고 AWS 및 Docker 기반 CI/CD 환경에 배포합니다.

## 1. 프로젝트 개요
- 서비스명: 하루배움 (HaruBaeum)
- 슬로건: "매일 한 걸음, 개발자의 성장을 증명하는 학습 루틴"
- 핵심 컨셉: 강좌 탐색부터 차시별 동영상 학습, 과제 평가, 수료증 발급, 정산 자동화 및 24시간 AI 학사 지원까지 학습의 전 과정을 하나로 통합한 엔터프라이즈 LMS
- 핵심 목표:
  - 수강생(STUDENT), 강사(INSTRUCTOR), 관리자(ADMIN) 다중 역할 기반 접근 제어(RBAC) 확립
  - 챕터-차시 계층형 커리큘럼 동영상 스트리밍, 실시간 진도율 추적 및 80% 차시 완료 판정
  - 포트원 PG 연동을 통한 결제 사전/사후 2단계 검증 및 망 취소 보상 트랜잭션 구현
  - Spring Batch 기반 자정 수강 만료 및 월간 강사 매출 정산 무인 자동화
  - 외부 LLM 연동 및 SSE 비동기 스트리밍 기반 AI 학사 행정 지원 챗봇 구축
  - Docker Compose 및 GitHub Actions 기반 무중단 CI/CD 배포 파이프라인 완성

## 2. 기술 스택
- 프론트엔드: React, TypeScript, Vite, Tailwind CSS, Zustand, Axios
- 백엔드 코어: Java, Spring Boot, Spring Security, JWT (Access/Refresh RTR)
- 영속성 및 데이터 접근: Spring Data JPA, OpenFeign QueryDSL, Hibernate
- 대용량 배치: Spring Batch
- 데이터베이스: MySQL, H2 (단위 테스트)
- AI 어시스턴트: OpenAI / Gemini API, Spring AI 및 WebClient (SSE 스트리밍)
- 인프라 및 CI/CD: AWS EC2, S3, CloudFront, Docker, Docker Compose, GitHub Actions
- 전자결제 연동: PortOne (단건 결제, 사전/사후 검증, 웹훅)

## 3. 상세 가이드 및 필수 산출물 안내
프로젝트 설정, 협업 규칙, 단계별 진행 가이드 및 필수 산출물 작성 가이드는 아래 문서를 참고하세요.

- [프로젝트 진행 가이드 바로가기](guide/README.md)
- [프로젝트 산출물 가이드 바로가기](docs/README.md)

