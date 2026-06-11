<div align="center">

# 👋 Hi, I'm Sangjin Oh

### Fullstack Developer

**Frontend부터 Backend까지** 아우르는 풀스택 개발자입니다.  
시각디자인 전공을 바탕으로 사용자 흐름을 고려한 기능 구현과 확장 가능한 서비스 설계에 관심이 많습니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-one-kappa-n7q736afg1.vercel.app/)
[![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)](https://granite-engineer-6d1.notion.site/Portfolio-2706f9ef939f810ea3c3faec8ab5a357?pvs=74)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:osj203040@gmail.com)

</div>

---

## 🛠 Tech Stack

**Frontend**  
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

**Backend**  
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square&logo=data:image/png;base64,&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)

**Database**  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)

**Tools & Infra**  
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

## 🚀 Projects

### 🤖 Daol Project — AI 문서 인식·분류 자동화 플랫폼
> LLM(Gemma)과 OCR을 결합해 문서 분류부터 요약까지 전 과정을 자동화한 AI 플랫폼

- **주요 기능**: AI 기반 문서 자동 분류·요약, SSE 실시간 상태 피드백, Discord 모니터링, HWPX·PDF 파싱
- **기술 스택**: `React` `Python` `FastAPI` `SQLAlchemy` `EasyOCR` `MariaDB` `Docker`
- **기여 내용**:
  - SSE 기반 비차단(Non-blocking) 실시간 알림 아키텍처 설계
  - Pillow로 **15만 장** 합성 학습 이미지 생성 파이프라인 구축 → OCR 인식률 개선
  - ThreadPoolExecutor + LMDB 도입으로 대규모 데이터 I/O 최적화
  - Discord Webhooks 전역 에러 핸들러 구축으로 장애 대응 속도 개선
  - SQLAlchemy ORM 기반 CRUD 및 ACL(접근 제어) 구현
- [🔗 GitHub](https://github.com/osj537/daol-project) | [📋 Notion](https://granite-engineer-6d1.notion.site/AI-Ollama-Gemma-2ae6f9ef939f80bc9cfcdd212058bb8e)

---

### 📚 Pullit — 학업성취도 평가 및 OCR 기반 자동 출제 플랫폼
> 500개 이상 문항 데이터를 기반으로 성취도를 시각화하고 PDF 리포트를 자동 생성하는 교육 플랫폼

- **주요 기능**: 학년별 성취도 통계 대시보드, PDF 리포트 다운로드, 수식 렌더링(KaTeX/MathJax), 교사·학생 페이지 분리
- **기술 스택**: `Vue.js` `Chart.js` `Java` `Spring Boot` `MySQL` `AWS EC2` `Docker` `GitHub Actions`
- **기여 내용**:
  - Vue.js + Chart.js 인터랙티브 성취도 대시보드 구현
  - PDFKit 기반 동적 리포트 생성 → 비동기 처리 전환으로 **다운로드 속도 약 30% 개선**
  - API 캐싱 전략 적용으로 **불필요한 서버 요청 20% 감소**
  - Vue Router로 교사용·학생용 페이지 세분화 및 UX 재설계
  - RESTful API 설계 및 핵심 백엔드 기능 Java/Spring Boot로 구현
- [🔗 GitHub (Backend)](https://github.com/osj537/pullit-backend) | [🔗 GitHub (Frontend)](https://github.com/osj537/pullit-frontend) | [📋 Notion](https://granite-engineer-6d1.notion.site/T-Fullit-2706f9ef939f8113bd5ff6a081bb3ea3)

---

### 🎓 Team-Stack — 디지털 교육 운영 및 강의 관리 플랫폼
> 오프라인 강의 운영을 전산화한 강의 등록·학생 승인 통합 관리 플랫폼

- **주요 기능**: 강사 마이페이지, 강의 생애주기 관리, 학생 승인 워크플로우, 멀티미디어 파일 업로드
- **기술 스택**: `JavaScript` `jQuery` `Java` `Spring Framework` `MyBatis` `JSP` `Oracle` `Figma`
- **기여 내용**:
  - AJAX 기반 실시간 강의 데이터 관리 UI 구현
  - Figma로 화면 설계 후 Spring + MyBatis 백엔드 로직 연동
  - 20건 이상의 테스트 데이터로 대량 데이터 환경 안정성 검증
- [🔗 GitHub](https://github.com/PARK-se-ung/Team-Stack) | [📋 Notion](https://granite-engineer-6d1.notion.site/teamstack-2706f9ef939f818d9c2fc296e25d97aa)

---

### 📖 GoBookEE — 사용자 중심 커뮤니티 및 정보 공유 플랫폼
> Java/JSP 기반 커뮤니티 플랫폼으로 웹 서비스 기초 라이프사이클 전 과정 경험

- **주요 기능**: 비동기 회원 인증, 공지사항·마이페이지 대시보드, Google Maps API 연동
- **기술 스택**: `JavaScript` `jQuery` `Java` `JSP` `Oracle` `Google Maps API` `Figma`
- **기여 내용**:
  - fetch API 기반 AJAX 통신으로 페이지 전환 없는 실시간 유효성 검사 구현
  - 세션·쿠키 기반 로그인 상태 관리 및 프론트-백엔드 교차 검증으로 데이터 무결성 확보
  - 공지사항·마이페이지 Java/JSP 백엔드 로직 및 Oracle DB 연동 전담
- [🔗 GitHub](https://github.com/GoBookEE/GoBookEE) | [📋 Notion](https://granite-engineer-6d1.notion.site/GoBookE-2706f9ef939f8130a7c2fbcfa2878ef9)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=osj537&show_icons=true&theme=tokyonight&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=osj537&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

📬 **Contact**: osj203040@gmail.com

</div>
