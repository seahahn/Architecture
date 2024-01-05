# ❇️ AI Play

## 1️⃣ 작품 소개

<!-- ![Architecture Overview](https://user-images.githubusercontent.com/73585246/152648288-f4d44660-86f2-4e24-8b6d-76ea7c31d76f.png) -->

🏠 [https://www.ai-play.app](https://www.ai-play.app)

### AI Play(인공지능 놀이)

- "AI가 뭔지 궁금해요? 일단 재밌게 놀아봐요!"
- 머신 러닝과 함께 딥 러닝을 경험할 수 있는 웹 어플리케이션
- 딥 러닝은 자연어 처리(NLP) 또는 컴퓨터 비전(CV)에 속하는 모델 몇 가지를 API 방식으로 연결하여 입력값만 넣으면 간단히 결과를 얻을 수 있는 기능 제공
  - 단순한 인풋-아웃풋보다는 모델을 체험하는 것에 흥미를 가질 수 있도록 하는 것이 목적
  - ex1. 얼굴 사진 업로드 - (Object Detection) - 닮은 과일 찾기
  - ex2. "나는 오늘 배가 고프다. 그래서" 문장 입력 - (Text Generation) - "나는 오늘 배가 고프다. 그래서 엘레강트하게 치킨을 먹어요"

### 주요 서비스 : MalLang MalLang(말랑말랑)

- 딱딱하게만 느껴진 머신 러닝을 **말랑말랑**하게 할 수 있다!
- 머신 러닝을 잘 알지 못해도 머신 러닝 모델을 만들 수 있게 해주는 웹 어플리케이션 서비스
- GUI 방식(마우스 클릭 + 간단한 값 입력)만으로 머신 러닝 과정(EDA, Feature Engineering, Training, ...) 수행 가능

### 프로젝트 기능별 결과물 저장소

| 기능                                    | 저장소 주소                                                                               |
| --------------------------------------- | ----------------------------------------------------------------------------------------- |
| 웹 앱 UI                                | [ai-play_frontend](https://github.com/seahahn/ai-play_frontend)                           |
| EDA 및 데이터 전처리 기능 API           | [ai-play_ml-functions](https://github.com/seahahn/ai-play_ml-functions)                   |
| 머신 러닝 모델 훈련 기능 API            | [ai-play_ml-training](https://github.com/seahahn/ai-play_ml-training)                     |
| 사용자 계정 관리 기능 API               | [ai-play_user-auth](https://github.com/seahahn/ai-play_user-auth)                         |
| 사용자 머신 러닝 프로젝트 관리 기능 API | [ai-play_user-project-managing](https://github.com/seahahn/ai-play_user-project-managing) |
| 딥 러닝 체험 기능 API                   | [ai-play_deep-learning-api](https://github.com/seahahn/ai-play_deep-learning-api)         |
| 채팅 서버                               | [ai-play_chatting](https://github.com/seahahn/ai-play_chatting)                           |

<br/>

## 2️⃣ 제작 기간 & 참여 인원

- 2022.02.14 - 2022.03.28
- 팀 프로젝트 : 3명
- 팀 구성원
  <details>
    <summary><a href="https://github.com/seahahn">안경호</a></summary>

  - 팀장, 기획 & 개발 총괄
    - 프로젝트 아이디어 제안 및 기획, 설계
    - 프로젝트에 사용할 기술 선택
    - Github Issues와 Project Kanban Board를 이용한 팀의 일정 및 할 일 관리 주도
    - 팀 구성원이 올린 Github Pull Request의 Code Review 수행
    - 프로젝트 내용 문서화
  - 프론트앤드(웹 앱 UI 및 기능) 전체 개발
  - 백앤드 개발 - 사용자 계정 관련 API(회원가입, 로그인 등) 서버 구현 및 리팩토링 - 사용자의 머신 러닝 프로젝트 관리 API 서버 구현 및 배포 - 딥 러닝 체험용 모델 API 서버 구현 및 배포
  </details>
  <details>
    <summary><a href="https://github.com/KayyoungHL">이경희</a></summary>

  - 머신 러닝 기능 관련 API 개발 담당
  - 머신 러닝 API 서버(ML-Funcs, ML-Train) 전체 구현
  - 채팅 서버 구현
  </details>
  <details>
    <summary><a href="https://github.com/Library-of-jade">김민석</a></summary>

  - 데이터 시각화 기능 구현
  - 사용자 계정 관련 API(회원가입, 로그인 등) 서버 구현
  - 머신 러닝 및 사용자 계정 관련 API 서버 배포
  - 데이터베이스 모델 설계 및 구현
  </details>

<br/>

## 3️⃣ 사용 기술

- 기술 선택 이유 : https://github.com/AI-Play/Architecture/blob/main/tech_stacks.md

| 분류         | 기술 목록                                                            |
| ------------ | -------------------------------------------------------------------- |
| Frontend     | React.js 17.0.2, TailwindCSS 3.0.22                                  |
| Backend      | FastAPI 0.75.0, Django 4.0.3, Fastify 3.27.2, Python 3.8.10, Go 1.17 |
| Database     | PostgreSQL(ElephantSQL), MongoDB(MongoDB Atlas) 5.0.6                |
| DevOps       | AWS (S3, Lambda), GCP (App Engine, Cloud Build), Heroku, Vercel      |
| Data Science | Pandas 1.4.1, Scikit-Learn 1.0.2, Bokeh 2.4.2                        |
| etc.         | Git · Github, JWT                                                    |

<br/>

## 4️⃣ 프로젝트 전체 구조도

![Project Structure](https://user-images.githubusercontent.com/73585246/162391560-59af981e-2634-40ad-aab8-fd4141c46401.png)

<br/>

## 5️⃣ ERD

![ERD](https://user-images.githubusercontent.com/73585246/162384496-4ea3963b-e87d-4fed-9468-33c2afca07ad.png)

<br/>

## 6️⃣ 프로젝트 시연 영상 (클릭 시 이동)

[![Project AI-Play Presentation](https://user-images.githubusercontent.com/73585246/162387097-fadcab28-3555-4a27-9dc1-3964d140105c.png)](https://youtu.be/eAUlGmGqqqc)
