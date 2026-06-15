# 최상인 | AI Backend Developer 👋

> **의료 현장의 문제를 이해하고, AI가 실제로 작동하는 서비스로 구현합니다.**

---

## 🎯 What I Do

* **AI 모델 활용 및 최적화**
  LLM·STT 파인튜닝, LoRA, GGUF 양자화, 구조화 출력 구현

* **AI Backend 개발**
  FastAPI 기반 추론 API와 Redis를 활용한 비동기 처리 구조 설계

* **도메인 문제 해결**
  의료·교육·공연 데이터를 분석하고 서비스에 필요한 문제로 재정의

---

## 💼 Experience

### 삼성청년SW·AI아카데미 AI 실습코치

`2025.12 – Present`

* 교육생 프로젝트의 AI 기술 및 모델 적용 방향 코칭
* 25개 팀의 프로젝트 아키텍처와 기술 스택 선정 지원
* AI 실습 교안 검수 및 프롬프트 엔지니어링 콘텐츠 제작

### 삼성청년SW·AI아카데미 13기

`2025.01 – 2025.12`

* Python 트랙 수료
* 프로젝트 4회 중 3회 최우수상 수상

### 을지대학교 응급구조학과

`2019.03 – 2025.02`

* 병원 응급실 및 119구급대 현장 실습
* 1급 응급구조사

---

## 🛠️ Tech Stack

### Language

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=openjdk\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge\&logo=typescript\&logoColor=white)

### AI / ML

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge\&logo=pytorch\&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge\&logo=huggingface\&logoColor=black)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge\&logo=huggingface\&logoColor=black)
![LoRA](https://img.shields.io/badge/LoRA_/_QLoRA-8A2BE2?style=for-the-badge)
![Faster Whisper](https://img.shields.io/badge/Faster_Whisper-2D3748?style=for-the-badge)
![Scikit Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge\&logo=scikitlearn\&logoColor=white)

### Backend

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge\&logo=fastapi\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge\&logo=springboot\&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge\&logo=django\&logoColor=white)

### Frontend

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge\&logo=vuedotjs\&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)

### Database / Infra

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge\&logo=postgresql\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge\&logo=redis\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge\&logo=amazonec2\&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge\&logo=nginx\&logoColor=white)

### Tools / Collaboration

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge\&logo=gitlab\&logoColor=white)
![JIRA](https://img.shields.io/badge/JIRA-0052CC?style=for-the-badge\&logo=jira\&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge\&logo=notion\&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge\&logo=postman\&logoColor=white)


---

## 🚀 Featured Projects

### 🚑 SSAIREN

**AI 기반 구급활동 어시스턴트**

`SSAFY 자율 프로젝트 최우수상`

구급 현장의 대화를 분석해 구급활동일지를 자동 작성하고,
환자 상태에 적합한 병원 선정을 지원하는 서비스입니다.

**주요 기여**

* 팀장 및 AI 개발 담당
* 약 24,000건의 구급활동일지를 분석해 데이터 구조와 출력 스키마 설계
* Faster-Whisper 기반 로컬 STT와 Qwen2.5-3B-Instruct 추론 파이프라인 구현
* LoRA 파인튜닝과 GBNF 기반 구조화 출력 적용
* GGUF·Q5_K_M 양자화로 모델 크기 `6GB → 2.5GB` 축소
* 외부 서버로 환자정보를 전송하지 않는 온프레미스 추론 구조 구현
* 구급활동일지 JSON 스키마 준수율 `95%` 달성

`Python` `FastAPI` `Qwen2.5` `LoRA` `GGUF` `Faster-Whisper`

---

### 🎭 KOPIS 빅데이터 분석 공모전

**복합 장르 공연의 성과를 분석하는 데이터 기반 의사결정 도구**

`제5회 KOPIS 빅데이터 공모전 혁신상`

KOPIS에서 하나의 ‘복합’ 범주로 관리되던 공연을
구체적인 장르 조합으로 분류하고 성과를 정량적으로 분석했습니다.

**주요 기여**

* 팀장, 데이터 분석 및 AI 모델링 담당
* 공연·인물·제작사·장르 관계를 그래프로 구성
* GCN 기반 다중 라벨 분류로 복합 공연 1,099건의 장르 조합 추론
* 참여도·규모·가격 접근성을 반영한 자체 성과지표 `D-PI` 설계
* 복합 공연의 평균 D-PI가 비복합 공연보다 `6.92점` 높음을 분석
* 랜덤포레스트 회귀로 실패 공연의 성공 전환에 필요한 최소 개선량 도출

`Python` `PyTorch Geometric` `Pandas` `scikit-learn` `SciPy`

---

### 💸 우리들의 비밀장터

**청소년 경제 학습을 위한 AI 콘텐츠 생성 플랫폼**

`SSAFY 특화 프로젝트 최우수상`

경제 뉴스를 수집·요약하고, 청소년 수준에 맞는 퀴즈를
자동으로 생성하는 AI 파이프라인을 구축했습니다.

**주요 기여**

* 팀장, AI 및 백엔드 개발 담당
* RSS 수집부터 뉴스 요약·퀴즈 생성까지 자동화
* AI 호출 실패 시 TextRank로 전환되는 폴백 구조 구현
* 장애 원인별 재시도와 타임아웃 처리로 요약 실패율 `30~40% → 0.5% 미만` 개선
* 품질 필터링 기반 학습으로 퀴즈 생성 성공률 `14%` 향상
* 콘텐츠 품질 점수 `35%` 개선

`Python` `FastAPI` `SQLAlchemy` `Sentence Transformers` `TextRank`

---

## 📂 Other Projects

| 프로젝트         | 주요 기여                                                                |
| ------------ | -------------------------------------------------------------------- |
| **EatDa**    | Redis Streams·Consumer Group·DLQ 기반 비동기 AI 워커와 멀티 AI 콘텐츠 생성 파이프라인 구축 |
| **SeedBank** | Django·Vue 기반 금융상품 추천 서비스 개발, JWT 인증과 유사도 기반 추천 로직 구현                |

---

## 📬 Contact

* GitHub: [github.com/sangin302](https://github.com/sangin302)
* Portfolio: [bit.ly/sanginotion](https://bit.ly/sanginotion)
* Email: [tkddls0127@naver.com](mailto:tkddls0127@naver.com)
