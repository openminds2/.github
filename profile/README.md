# 오픈마인즈

이곳에서는 오픈마인즈에서 개발·운영하는 서비스와 기술 프로젝트를 관리합니다.

## About Us

사용자의 문제를 해결하고 더 나은 경험을 제공하기 위한 웹·앱 서비스를 개발합니다.

기획부터 설계, 개발, 테스트, 배포 및 운영까지 제품 개발 전반의 품질과 지속적인 개선을 중요하게 생각합니다.

## What We Build

* Web Applications
* Mobile Applications
* Backend APIs
* Internal Services
* Product & Service Prototypes

## Projects

### 1️⃣ [Tone Me](https://play.google.com/store/apps/details?id=com.toneme.app) 🎨

퍼스널컬러를 기반으로 사용자에게 어울리는 사진 필터를 제공하는 Android 모바일 애플리케이션입니다.

**Key Features**

* 퍼스널컬러 기반 맞춤 사진 필터
* 카메라 및 사진 편집
* 필터 강도·밝기 조절
* 인앱 결제
* 광고 기반 콘텐츠 이용
* Push Notification

**Tech**

- `React Native 0.86.2` `React 19.2.3` `TypeScript 6.0.3` `Expo SDK 57.0.9`
- `Expo Router 57.0.9` `Zustand 5.0.14`
- `Supabase JS 2.110.3` `Supabase PostgreSQL` `Supabase Edge Functions (Deno)`
- `Firebase App 25.1.0` `Firebase Analytics 25.1.0`
- `RevenueCat 10.6.0` `Google Mobile Ads 16.3.4`
- `React Native Vision Camera 5.1.0` `React Native Skia 2.6.2`
- `Android minSdk 26` `Gradle 9.3.1` `Hermes JavaScript Engine`

### 2️⃣ Groupware 🏙️

조직의 업무와 협업을 지원하는 웹 기반 그룹웨어 시스템입니다.

**Key Features**

* 근태 관리
* 전자결재
* 조직도
* 게시판
* 역할 및 권한 기반 메뉴 관리
* 반응형 UI

**Tech**

- BE
  - `Java (JDK 17)` `Spring Boot 2.7.18` `Spring Framework 5.3.37`
  - `MyBatis 3.5.16` `MyBatis-Spring 2.1.2`
  - `PostgreSQL` `PostgreSQL JDBC Driver 42.7.3` `Apache Commons DBCP 2.12.0`
  - `Springdoc OpenAPI 1.7.0` `Swagger UI`
  - `Spring Mail Gmail SMTP`
  - `JJWT 0.9.1` `Jasypt Spring Boot 3.0.3`
  - `Lombok 1.18.44 Maven`
- FE
  - `React 18.3.1` `JavaScript (JSX)` `React Router DOM 6.30.1`
  - `Zustand 5.0.11`
  - `AG Grid 35.1.0` `AG Charts 13.1.0` `Recharts 3.7.0`
  - `Lexical 0.45.0` `React Datepicker 4.25.0`
  - `Vite 5.4.19`

### 3️⃣ Commerce Platform 🛒

상품 관리와 사용자 서비스를 제공하는 웹 기반 커머스 프로젝트입니다.

**Key Features**

* AI 기반 상품 추천
* 상품 및 카테고리 관리
* 사용자·관리자 화면 분리
* 역할 및 권한 관리
* 반응형 UI

**Tech**

- BE
  - `Spring AI 1.1.4` `Google GenAI (Gemini) Chat API`
  - `PortOne Server SDK 0.23.0` `PortOne 결제·웹훅 API`
  - `택배조회 API (tracker.delivery)` `Spring Scheduling`
  - `Java (JDK 17)` `Spring Boot 2.7.18` `Spring Framework 5.3.37`
  - `MyBatis 3.5.16` `MyBatis-Spring 2.1.2`
  - `PostgreSQL` `PostgreSQL JDBC Driver 42.7.3` `Apache Commons DBCP 2.12.0`
  - `Springdoc OpenAPI 1.7.0` `Swagger UI`
  - `JJWT 0.9.1` `Jasypt Spring Boot 3.0.3`
  - `Lombok 1.18.44` `Maven`
- FE
  - `React 18.3.1` `JavaScript (JSX)` `React Router DOM 6.30.1`
  - `Zustand 5.0.11`
  - `AG Grid 35.1.0` `AG Charts 13.1.0`
  - `Swiper 12.1.3`
  - `Vite 5.4.19`

### 4️⃣ [Care Service Platform](https://omcst.duckdns.org:9999/nursing/) 🧓

공공데이터를 활용하여 요양 관련 시설 정보를 검색하고 비교할 수 있도록 구성한 웹 서비스입니다.

**Key Features**

* AI 기반 시설 추천
* 위치 기반 요양시설 검색
* 시설 정보 비교
* 공공데이터 연동
* 사용자 편의 중심 요양 정보 제공
* 커뮤니티
* 반응형 UI

**Tech**

- BE
  - `Spring AI 1.1.4` `Google GenAI (Gemini) Chat API`
  - `공공데이터포털 장기요양기관·병원정보 API` `RestTemplate`
  - `Java (JDK 17)` `Spring Boot 2.7.18` `Spring Framework 5.3.37`
  - `MyBatis 3.5.16` `MyBatis-Spring 2.1.2`
  - `PostgreSQL` `PostgreSQL JDBC Driver 42.7.3` `Apache Commons DBCP 2.12.0`
  - `Springdoc OpenAPI 1.7.0` `Swagger UI`
  - `Spring Scheduling`
  - `JJWT 0.9.1` `Jasypt Spring Boot 3.0.3`
  - `Lombok 1.18.44` `Maven`
- FE
  - `React 18.3.1` `JavaScript (JSX)` `React Router DOM 6.30.1`
  - `Zustand 5.0.11`
  - `AG Grid 35.1.0` `AG Charts 13.1.0`
  - `MUI Icons 7.3.9`
  - `Vite 5.4.19`

### 5️⃣ Attenda 💬

웹, AI Agent 기반 근태·휴가 업무 자동화 시스템입니다.

**Key Features**

* AI Assistant를 통한 근태·연차·휴가·결재 질의
* 근태 관리
* 전자결재
* 조직도
* 반응형 UI

**Tech**

- `OpenAI Chat Completions API`, `Springdoc OpenAPI	3.0.0`
- `Java (JDK-21)` `Spring Boot 4.0.8` `Spring Security + JWT` `MariaDB` `Persistence	MyBatis Spring Boot Starter 4.0.1`
- `React 19.2.8` `TypeScript 6.0.2` `Vite 8.2.2` `Routing	React Router DOM	7.18.2`
- `Zustand` `Chart.js` `AG Grid Community 36.1.0`

---

© 주식회사 오픈마인즈
