<div align="center">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=180&text=RASIT&fontColor=ffffff&fontSize=60"/>
</div>

<div align="center">
    <h3>배포와 운영까지 맡아 온 백엔드 개발자</h3>
    <p>프레임워크 아래 계층도 직접 구현해 보았습니다</p>
    <a href="mailto:shjh0815@naver.com"><img src="https://img.shields.io/badge/shjh0815@naver.com-03C75A?style=flat-square&logo=naver&logoColor=white"/></a>
</div>

<br>

## 💻 Projects

### Building HTTP Server | epoll 기반 HTTP/1.1 서버

> 개인 프로젝트 · [GitHub](https://github.com/Rasit-NP/building-http-server)

프레임워크가 가려주던 소켓·이벤트 루프·프로토콜 파싱 계층을 표준 라이브러리만으로 직접 쌓아 올린 프로젝트입니다.
동시성을 처음부터 얹지 않고 **single-threaded reactor에서 I/O 다중화와 프로토콜 파싱을 먼저 완결**한 것은 의도적인 선택으로, 파서 버그와 스레드 경계의 소유권 문제가 뒤섞이지 않도록 축을 분리했습니다.

- **역할** : 전체 설계 및 구현
- **기술** : C++(표준 라이브러리만 사용, 외부 HTTP 라이브러리 없음), Linux epoll, CMake, GoogleTest/CTest, Docker(Ubuntu), GitHub Actions
- **구현** : epoll reactor 이벤트 루프, HTTP/1.1 요청 점진적 파싱(TCP 메시지 경계 비보장 전제), 정적 파일 서빙(path traversal 차단), `EPOLLOUT` 기반 write backpressure 처리
- **검증** : 단위 테스트(GoogleTest) + 블랙박스 통합 harness, CI에서 Release 빌드와 `ctest` 통과

### Hater | 타워 디펜스 웹 게임 서비스

> SSAFY 2학기 자율프로젝트

- **역할** : 백엔드 개발
- **기술** : Java 21, Spring Boot, PostgreSQL, Redis, JWT, RSA-AES 하이브리드 암호화
- **서비스** : React 웹 포털 + Unity WebGL 게임 클라이언트 + Spring Boot REST API 구성, 클라이언트-서버 간 AES-256-GCM 암호화 통신 적용

### Jupasu | 와인 추천 서비스

> SSAFY 2학기 특화프로젝트 · 우수상

- **역할** : 인프라, 백엔드(추천 점수 로직 구현)
- **기술** : Spring Boot, Docker Compose, Jenkins, Prometheus, Grafana

### 이웃집 웰리 | 올인원 복지 매니지먼트 서비스

> SSAFY 2학기 공통프로젝트

- **역할** : 백엔드 개발, 인프라(CI/CD, HTTPS 배포)
- **기술** : Spring Boot, MySQL, Docker Compose, Jenkins

### Nestudy | 그룹 스터디 관리 플랫폼

> SSAFY 1학기 관통프로젝트 · [GitHub](https://github.com/Juseong-Yu/SSAFY_GroupStudyPlanner)

- **역할** : 백엔드 개발, Discord 봇 및 서버 개발, 배포
- **기술** : Django, FastAPI, Celery, Redis(Message Broker), Docker Compose

<br>

## 🛠️ Tech Stacks

**Language**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)

**Infra & CI/CD**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

<br>

## ⏳ Timeline

| 기간 | 내용 |
| --- | --- |
| 2025.07 ~ 2026.06 | 삼성 청년 SW 아카데미 14기 |
| 2016.03 ~ 2025.02 | 연세대학교 이과대학 물리학과 학사 졸업 |

<br>

## 🧩 Daily Problem Solving

- **백준** Platinum II · 1,000 solved
- **플랫폼** 백준, LeetCode, Codeforces, 프로그래머스
- **풀이 저장소** [Algorithm-Solutions](https://github.com/Rasit-NP/Algorithm-Solutions)

<div align="left">
    <a href="https://solved.ac/profile/shjh0815"><img src="https://mazassumnida.wtf/api/v2/generate_badge?boj=shjh0815"/></a>
</div>

<!--
================================================================
🏅 GitHub Stats — 일시 비활성화

github-readme-stats 공개 인스턴스가 503 DEPLOYMENT_PAUSED 상태라
카드가 깨진 이미지로 표시되어 잠시 숨겨 둡니다.
서비스가 정상화되면 이 주석의 여는/닫는 기호만 지우면 복구됩니다.

확인: curl -s -o /dev/null -w "%{http_code}\n" \
      "https://github-readme-stats.vercel.app/api?username=Rasit-NP"

top-langs에는 exclude_repo로 PS 저장소를 제외해 두었습니다.
(바이트 수 기준 집계라 제외하지 않으면 C++/Python이 상위를 차지합니다.)
================================================================

## 🏅 GitHub Stats

<div align="center">
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Rasit-NP&show_icons=true&hide_border=true&theme=github_dark"/>
        <img src="https://github-readme-stats.vercel.app/api?username=Rasit-NP&show_icons=true&hide_border=true&theme=default"/>
    </picture>
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Rasit-NP&layout=compact&hide_border=true&exclude_repo=Algorithm-Solutions&theme=github_dark"/>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rasit-NP&layout=compact&hide_border=true&exclude_repo=Algorithm-Solutions&theme=default"/>
    </picture>
</div>

-->

