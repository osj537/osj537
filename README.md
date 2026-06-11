# 오상진 (Sangjin Oh)

풀스택 개발자입니다. 시각디자인을 전공하다가 화면 너머에서 일어나는 일이 궁금해서 개발로 넘어왔습니다.
화면의 흐름과 데이터의 흐름이 어긋나지 않는 서비스를 만드는 데 관심이 많습니다.

주로 Java/Spring Boot와 Python/FastAPI로 백엔드를, React와 Vue.js로 프론트엔드를 작업합니다.

[Portfolio](https://portfolio-one-kappa-n7q736afg1.vercel.app/) · [Notion](https://granite-engineer-6d1.notion.site/Portfolio-2706f9ef939f810ea3c3faec8ab5a357?pvs=74) · osj203040@gmail.com

<br>

## Tech Stack

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

그 외 MyBatis, JPA, JSP/Servlet, Bootstrap, Figma를 다룹니다.

<br>

## Projects

### Daol Project — AI 문서 인식·분류 자동화 플랫폼
LLM(Gemma)과 OCR로 문서 텍스트 추출부터 요약까지 자동화하는 시스템. 인턴십에서 프론트와 백엔드 전반을 맡았습니다.

AI 요약 결과를 한 번에 띄우면 사용자가 기다리는 동안 아무것도 알 수 없어서, SSE 스트리밍으로 바꿔 토큰 단위로 출력되게 만들었습니다. 한국어 법률문서 OCR 인식률이 낮은 문제는 모델이 아니라 데이터 문제로 보고, Pillow로 합성 이미지 15만 장을 만들어 파인튜닝했습니다. 에러가 나면 Discord로 바로 알림이 오는 모니터링도 직접 붙였습니다.

React, Python, FastAPI, SQLAlchemy, EasyOCR, LMDB, MariaDB, Docker

[GitHub](https://github.com/osj537/daol-project) / [Notion](https://granite-engineer-6d1.notion.site/AI-Ollama-Gemma-2ae6f9ef939f80bc9cfcdd212058bb8e)

### Pullit — 학업성취도 평가 및 OCR 기반 자동 출제 플랫폼
500개 이상의 문항 데이터로 교사와 관리자가 평가 결과를 분석할 수 있는 플랫폼.

Vue.js와 Chart.js로 성취도 통계 대시보드를 만들고, PDFKit으로 리포트 PDF 다운로드를 구현했습니다. 다운로드를 비동기로 전환해 속도를 약 30% 줄였고, API 호출에 캐싱을 적용해 서버 요청을 20% 줄였습니다. 복잡하게 묶여 있던 상세 페이지를 교사용/학생용으로 분리하자고 제안해서 직접 재구성하기도 했습니다.

Vue.js, Java, Spring Boot, MySQL, AWS EC2, Docker, GitHub Actions

[Backend](https://github.com/osj537/pullit-backend) / [Frontend](https://github.com/osj537/pullit-frontend) / [Notion](https://granite-engineer-6d1.notion.site/T-Fullit-2706f9ef939f8113bd5ff6a081bb3ea3)

### Team-Stack — 강의 운영 관리 플랫폼
오프라인 강의 등록부터 학생 승인까지 전산화한 플랫폼.

Figma로 화면을 먼저 설계하고 Spring + MyBatis로 백엔드를 연동했습니다. 강사 마이페이지에서 새로고침 없이 강의를 관리할 수 있게 AJAX로 구현했고, 진행 중/만료 강의 필터링과 승인 워크플로우를 만들었습니다.

Java, Spring, MyBatis, JSP, jQuery, Oracle

[GitHub](https://github.com/PARK-se-ung/Team-Stack) / [Notion](https://granite-engineer-6d1.notion.site/teamstack-2706f9ef939f818d9c2fc296e25d97aa)

### GoBookEE — 커뮤니티 플랫폼
Java/JSP로 기획부터 구현까지 처음 끝까지 만들어본 커뮤니티 프로젝트.

fetch API로 로그인/회원가입 실시간 유효성 검사를 구현하고, 세션·쿠키 기반 로그인 상태 관리를 맡았습니다. 공지사항과 마이페이지의 백엔드 로직, Oracle DB 연동을 전담했습니다.

Java, JSP, Tomcat, Oracle, Google Maps API

[GitHub](https://github.com/GoBookEE/GoBookEE) / [Notion](https://granite-engineer-6d1.notion.site/GoBookE-2706f9ef939f8130a7c2fbcfa2878ef9)

<br>

## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=osj537&show_icons=true&theme=default&hide_border=true)
