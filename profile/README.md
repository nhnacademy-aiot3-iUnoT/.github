# 💊 iUnoT
> **IoT 기반 의약품 재고 및 보관 환경 관리 서비스**

의약품의 재고 관리와 보관 환경 모니터링을 제공하는 **기관 단위 관리 플랫폼**입니다.

IoT 센서 데이터를 활용하여 의약품 보관 환경을 관리하고,  
유통기한 및 재고 변동 이력을 기반으로 안정적인 의약품 관리 환경을 제공합니다.


---

## 📚 Documentation

| 문서 | 설명 |
|:---:|:---|
| 📄 [요구사항](https://github.com/nhnacademy-aiot3-iUnoT/docs) | 서비스 요구사항 정의 |


---

## 🧑‍💻 Team

<div align="center">

| 강병호 | 고나영 | 마지희 | 박준원 | 임성준 | 정다빈 | 정영우 | 홍보람 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| <img width="120" src="https://avatars.githubusercontent.com/u/94677012?v=4"/> | <img width="120" src="https://avatars.githubusercontent.com/u/133228490?v=4"/> | <img width="120" src="https://avatars.githubusercontent.com/u/251104855?v=4"/> | <img width="120" src="https://avatars.githubusercontent.com/u/145592263?v=4"/> | <img width="120" src="https://avatars.githubusercontent.com/u/52077256?v=4"/> | <img width="120" src="https://avatars.githubusercontent.com/u/182188997?v=4"/> | <img width="120" src="https://avatars.githubusercontent.com/u/176290691?v=4"/> | <img width="120" src="https://avatars.githubusercontent.com/u/176385754?v=4"/> |
| 인프라 | - | 재고 관리 | 룰 엔진 | 인증/인가 | 룰 엔진 | - | 재고 관리 |

</div>

<br>

---

## 🌐 System Architecture

<div align="center">

<img src="img/architecture.png" width="850"/>

</div>

<br>

---

## 🗄 ERD

<div align="center">

<img src="img/erd.png" width="850"/>

</div>

<br>

---

# 📋 주요 기능

## 🔐 회원 및 조직 관리

> 사용자 인증과 기관 단위 권한 관리를 제공합니다.

- 회원가입 및 계정 관리
- 조직 생성 및 가입
- 초대 기반 조직 관리
- 조직원 역할 및 업무 권한 관리
- 조직별 데이터 접근 제한


## 🏢 저장소 및 구역 관리

> 의약품이 보관되는 공간과 환경 기준을 관리합니다.

- 조직별 저장소 관리
- 저장소별 보관 구역 관리
- 구역별 환경 기준값 설정
- 보관 위치 관리


## 📦 의약품 재고 관리

> 의약품 입고부터 출고까지 전체 재고 흐름을 관리합니다.

- 의약품 기준정보 관리
- 제조번호·유통기한 기반 재고 관리
- 입고 및 출고 관리
- 재고 변동 이력 관리
- 재고 부족 및 유통기한 관리


## 🌡 환경 모니터링

> IoT 센서를 활용하여 의약품 보관 환경을 모니터링합니다.

- 센서 데이터 수집
- 환경 데이터 저장 및 조회
- 온도·습도·문 열림 상태 관리
- 임계값 기반 이상 감지
- 환경 이상 알림 제공


## 🔗 환경 기반 의약품 관리

> 환경 이상 발생 시 의약품 영향 여부를 분석합니다.

- 환경 이상과 의약품 정보 연계
- 영향 가능 의약품 식별
- 검토 대상 재고 관리
- 조치 결과 및 이력 관리


## 📊 Dashboard

> 서비스 운영 현황을 한눈에 확인할 수 있습니다.

- 조직별 재고 현황 조회
- 저장소·구역별 환경 상태 조회
- 재고 부족 및 유통기한 현황 조회
- 환경 이상 발생 기록 조회
- 최근 재고 변동 내역 조회

<br>

---

## 🛠️ Tech Stack
<div>
  <h3>Backend</h3>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/Eureka-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  
  <h3>Data</h3>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white">
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white">

  <h3>Infrastructure</h3>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white">
  <img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white">

  <h3>Frontend</h3>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white">

  <h3>AI</h3>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white">
</div>
<br>

<div align="right">
<a href="#top">▲</a>
</div>
