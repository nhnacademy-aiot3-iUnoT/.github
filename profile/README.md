# 💊 iUnoT

> ####  IoT 기반 의약품 재고 및 보관 환경 관리 서비스
|                                     강병호                                      |                                      고나영                                      |                                      마지희                                       | 박준원 | 임성준 | 정다빈 |                                      정영우                                       |                                      홍보람                                       |
|:----------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|:------------------------------------------------------------------------------:|:---:|:---:|:---:|:------------------------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| <img width="90" src="https://avatars.githubusercontent.com/u/94677012?v=4"/> | <img width="90" src="https://avatars.githubusercontent.com/u/133228490?v=4"/> | <img width="90" src="https://avatars.githubusercontent.com/u/251104855?v=4"/> | <img width="90" src="https://avatars.githubusercontent.com/u/145592263?v=4"/> | <img width="90" src="https://avatars.githubusercontent.com/u/52077256?v=4"/> | <img width="90" src="https://avatars.githubusercontent.com/u/182188997?v=4"/> | <img width="90" src="https://avatars.githubusercontent.com/u/176290691?v=4"/> | <img width="90" src="https://avatars.githubusercontent.com/u/176385754?v=4"/> |
|                                     인프라                                      |                                     조직관리                                      |                                      재고관리                                      | 룰 엔진 | 인증/인가 | 룰 엔진 |                                      재고관리                                      |                                      재고관리                                      |

---

## 🧑‍💻 프로젝트 소개

#### 기간 : 2026.07.06 ~ 2026.09.xx

- iUnoT는 IoT 센서를 활용하여 의약품의 보관 환경과 재고를 통합 관리하는 기관 단위 플랫폼입니다.

- 실시간 환경 데이터를 기반으로 안전한 보관 환경을 유지하고, 
- 제조번호(Lot) 및 유통기한 기반의 재고 관리와 환경 이상 발생 시 영향 의약품 식별 기능을 제공하여 효율적인 의약품 운영을 지원합니다.

### 핵심 목표
- IoT 기반 환경 데이터와 재고 정보를 통합 관리
- 제조번호(Lot) 및 유통기한 기반 재고 추적
- 환경 이상 발생 시 영향 의약품 식별
- 기관 단위 권한 기반 데이터 관리 체계 구축

### Tech Stack

| Category | Stack |
|----------|-------|
| **Backend** | <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white"> <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"> <img src="https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/Eureka-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> |
| **Database** | <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"> <img src="https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"> <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white"> |
| **Messaging** | <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white"> |
| **Infrastructure** | <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"> <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white"> <img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white"> |
| **Frontend** | <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white"> |
| **AI** | <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"> |
---

## 📋 주요 기능

### 회원 및 조직 관리

- 회원가입 및 계정 관리
- 조직 생성 및 초대 기반 가입
- 조직원 역할 및 권한 관리
- 조직별 데이터 접근 제어

---

### 저장소 및 구역 관리

- 조직별 저장소 및 보관 구역 관리
- 구역별 환경 기준값 설정
- 의약품 보관 위치 관리

---

### 의약품 재고 관리

- 의약품 기준정보 관리
- 제조번호(Lot) 및 유통기한 기반 재고 관리
- 입고·출고 및 재고 변동 이력 관리
- 재고 부족 및 유통기한 임박 알림

---

### 환경 모니터링

- 센서 데이터 수집 및 조회
- 온도·습도·조도·문 열림 상태 모니터링
- 임계값 기반 이상 감지 및 알림

---

### 환경 기반 의약품 관리

- 환경 이상과 의약품 정보 연계
- 영향 가능 의약품 식별
- 검토 및 조치 이력 관리

---

### 대시보드

- 재고 및 유통기한 현황
- 저장소·구역별 환경 상태
- 환경 이상 및 재고 변동 이력 조회

---


## 🌐 시스템 구조
> MSA 기반 구조로 구성되며, Gateway를 통해 인증, 조직, 재고, 룰 엔진 등의 서비스를 분리하여 제공합니다.

<div align="center">

<img src="img/architecture.png" width="750"/>

</div>

<br>

---

## 🗄 ERD
> 🚧 현재 설계 보완 중이며 지속적으로 업데이트됩니다.
<div align="center">

<img src="img/[erd]v1.png" width="750"/>

</div>

<br>

---

## 📚 Documentation

| 문서 | 설명 |
|:---:|:---|
| [요구사항](https://github.com/nhnacademy-aiot3-iUnoT/docs) | 서비스 요구사항 정의 |
| [기능명세](https://github.com/nhnacademy-aiot3-iUnoT/docs/tree/docs/%EA%B8%B0%EB%8A%A5%20%EB%AA%85%EC%84%B8) | 기능 명세서 |
| [목업](https://github.com/nhnacademy-aiot3-iUnoT/docs/tree/docs/%EB%AA%A9%EC%97%85) | 목업 문서화 |
| API Docs | REST Docs (예정) |
---
