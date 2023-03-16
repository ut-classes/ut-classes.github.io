<p id="menu" align="center">
  <a href="https://ut-nodejs.github.io" title="Home">🏠</a> |
  <a href="about.html" title="About">개요</a> |
  <a href="/schedule.html" title="Schedule"><u>[일정]</u></a> |
  <a href="/slides.html" title="Slides">스라이드</a> |
  <a href="/practice.html" title="Practice">과제</a> |
  <a href="/project.html" title="Project">프로젝트</a> |
  <a href="/tests.html" title="Tests">시험</a> |
  <a href="/grading.html" title="Grading">성적</a> |
  <a href="https://pollev.com/aarons007" title="PollEverywhere">설문↗️</a>
</p>

---

# Web Programming Application 2023

<p>한국교통대학교, 충주<small> | KNUT (Korea National University of Transportation)</small></p>

---

## This Week / 3주차 3월17일

#### 3. Node Webserver First Steps / 노드 웹서버 첫 걸음

This week we take a look at some of the major problems and mistakes from last week and how to fix them. We will have a brief introduction to what Node is, how it works, and why it's important. Finally, we'll get to work on creating a web server and simple website in Node.js.

이번 주에는 지난주의 주요 문제와 실수를 살펴보고 이를 수정하는 방법을 알아봅시다. Node.js가 무엇인지, 어떻게 작동하는지, 왜 중요한지에 대해 간략하게 소개하겠습니다. 마지막으로 Node.js에서 웹 서버와 간단한 웹 사이트를 만드는 작업을 시작합니다.

##### Resources / 리소스

- PPT <a href="slides/https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/_3.%20%EA%B3%BC%EC%A0%9C%20%EB%AC%B8%EC%A0%9C%EC%99%80%20%ED%95%B4%EA%B2%B0.pdf">\*3. Assignment Problems & Solutions / 과제 문제와 해결</a>
- PPT <a href="https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/_4.%20Node.JS%EC%9D%98%20%EC%9D%B4%ED%95%B4.pdf">\*4. Understanding Node.js / Node.js의 이해</a>
- PPT <a href="https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/1.%20Node.js%EC%9D%98%20%EC%8B%9C%EC%9E%91.pdf">Unit 1. Starting Node.js / Node.js의 시작</a>

##### Required Reading / 필수 독서

- [_Get Programming with Node.js_](http://www.yes24.com/Product/Goods/86429845)
  - pp. 37-46 (Lesson 0: Node.js 설정과 JavaScript 엔진 설치)
  - pp. 67-78 (Lesson 3: Node.js 모듈 생성)
  - pp. 79-88 (Lesson 4: Node.js에서 웹 서버 만들기)
  - pp. 89-100 (Lesson 5: 수신 데이터 다루기)
  - pp. 101-116 (Lesson 6: 라우트와 외부 파일)

##### Recommended reading / 추천 독서

- [_Node.js 교과서_](http://www.yes24.com/Product/Goods/116192535)
  - pp. 179-216 (4장: http 모듈로 서버 만들기)
  - pp. 217-240 (5장: 패키지 매니저)
- [Node.js란 무엇인가?](https://velog.io/@sms8377/Javascript-Node.js%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80)
- [Node.js란...?](https://perfectacle.github.io/2017/06/18/what-is-node-js/)

---

## Course Topics / 과정 화제

| Week | Date    | Unit | Topic                                                                             | 화제                                                                        |
| :--: | :------ | :--: | :-------------------------------------------------------------------------------- | :-------------------------------------------------------------------------- |
|  1   | 3월3일  |  --  | [Overview and introduction to class](/schedule.html#week-1--1주차-3월3일)         | [수업 소개](/schedule.html#week-1--1주차-3월3일)                            |
|  2   | 3월10일 |  0   | [GitHub Classroom & Web Programming Review](/schedule.html#week-2--2주차-3월10일) | [깃허브 클래스룸과 웹프로그래밍 복습](/schedule.html#week-2--2주차-3월10일) |
|  3   | 3월17일 |  1   | [Node Webserver First Steps](/schedule.html#week-3--3주차-3월17일)                | [노드 웹서버 첫 걸음](/schedule.html#week-3--3주차-3월17일)                 |
|  4   | 3월24일 |  2   | Routing in Express.js                                                             | Express.js 라우팅                                                           |
|  5   | 3월31일 |  2   | Project Start                                                                     | 프로젝트 시작                                                               |
|  6   | 4월7일  |  3   | Connecting to MongoDB                                                             | MongoDB 연결                                                                |
|  7   | 4월14일 |  4   | User Data Models                                                                  | 사용자 데이터 모델                                                          |
|  8   | 4월21일 |  --  | Midterm Exam / Project                                                            | 중간고사                                                                    |
|  9   | 4월28일 |  4   | CRUD (Create, Read, Update, Delete)                                               | CRUD (생성, 조회, 수정, 삭제)                                               |
|  --  | 5월5일  |  --  | _HOLIDAY: Children's Day_                                                         | _공휴일: 어린이날_                                                          |
|  10  | 5월12일 |  5   | User Authentication                                                               | 사용자 인증                                                                 |
|  11  | 5월19일 |  6   | Adding an API                                                                     | API 추가                                                                    |
|  12  | 5월26일 |  7   | Adding Chat Functionality                                                         | 채팅 추가                                                                   |
|  13  | 6월2일  |  8   | Deploying to Production                                                           | 프로덕션                                                                    |
|  14  | 6월9일  | A,B  | Supplementary Topics / Personal Projects                                          | 개인 프로젝트                                                               |
|  15  | 6월16일 |  --  | Final Exam                                                                        | 기말고사                                                                    |

<!----
| 16  | 6월16일 | --   | [Personal Projects](/en/#14-personal-projects)                                  | [개인 프로젝트]()             |
| 17  | 6월23일 | --   | [Final Exam](/en/#final-exam)                                                   | [기말고사]()                  |
| 18  | 6월30일 | --   | [Grading Period](/en/#grading)                                                  | [성적 처리 기간]()            |
---->

---

## Previous Weeks / 이전 주차

### Week 1 / 1주차 3월3일

#### 1. Orientation and introduction to class / 오리엔테이션 및 수업 소개

We will use this session to get to know the range of interests and experience students bring to the class, as well as to survey the topics to be covered. We will discuss class goals, grading, the textbook, and get to know the instructor.

우리는 이 세션을 통해 학생들이 수업에 가져오는 관심사와 경험의 범위를 파악하고 다룰 주제를 조사할 것입니다. 우리는 수업 목표, 채점, 교과서에 대해 논의하고 강사를 알게 될 것입니다.

##### Resources / 리소스

- PPT <a href="https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/_0-NodeJS-수업-소개.pdf">\*0. Class, Book, Teacher Introduction / 수업 소개</a>

<!-- - Google Classroom (PPTs) ([오전](https://classroom.google.com/c/NTEyMjUxMTM4MjQz?cjc=m5cbuja) / [오후](https://classroom.google.com/c/NTE2NTcyNjcwNjMz?cjc=sr6x7hg)) -->
<!-- - GitHub Classroom (과제) ([오전](https://classroom.github.com/classrooms/126310482-2023sp-259122-1-am) / [오후](https://classroom.github.com/classrooms/126310482-2023sp-259122-2-pm))
- [PPT \*0. Class, Book, Teacher Introduction](lecturenotes/)
- [PPT \*1. Web Programming Review](lecturenotes/)
- [PPT \*2. Git and GitHub Classroom Introduction](lecturenotes/)
- [Lab 0 materials](https://lse-me314.github.io/assignment01/) -->

##### Recommended reading / 추천 독서

- [git - 간편 안내서](https://up1.github.io/git-guide/index.ko.html)
- [누구나 쉽게 이해할 수 있는 git 입문](https://backlog.com/git-tutorial/kr/)

###### [↑ Schedule / 일정 다시 가기](/schedule.html#course-topics--과정-화제)

---

### Week 2 / 2주차 3월10일

#### 2. GitHub Classroom & Web Programming Review / 깃허브 클래스룸과 웹프로그래밍 복습

This week will introduce GitHub Classroom and how to submit assignments. We will then install the programs we will need to use in this class. We will also do a web programming review, including building a simple, responsive, website menu with HTML, CSS, and JavaScript. Finally, we'll write a few simple scripts and run them in Node.

이번 주에는 GitHub 클래스룸과 과제 제출 방법을 소개합니다. 그런 다음 이 수업에서 사용할 프로그램을 설치합니다. 또한 웹프로그래밍 복습을 수행하고 HTML, CSS, 및 JavaScript를 사용하여 간단하고 반응 가능 웹사이트 메뉴를 만들 것입니다. 마지막으로 몇 가지 간단한 스크립트를 작성하고 Node.js에서 실행할 것입니다.

##### Resources / 리소스

- [PollEv 설문](https://pollev.com/aarons007)
- [Google 설문](https://forms.gle/S16WqFdeax5fTMuv6)
- PPT <a href="https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/_1.%20깃과%20깃허브%20클래스룸.pdf">\*1. Git & GitHub Classroom / 깃과 깃허브 클래스룸</a>
- PPT <a href="https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/_2.%20웹%20프로그래밍%20복습.pdf">\*2. Web Programming Review / 웹프로그래밍 복습</a>

##### Required Reading / 필수 독서

- [_Get Programming with Node.js_](http://www.yes24.com/Product/Goods/86429845)
  - pp. 25-33 (들어가며)
  - pp. 47-57 (Lesson 1: 환경설정)
  - pp. 59-68 (Lesson 2: Node.js 애플리케이션 실행)

##### Recommended reading / 추천 독서

- [_Node.js 교과서_](http://www.yes24.com/Product/Goods/116192535)
  - pp. 23-64 (1장: 노드 시작하기)
  - pp. 66-92 (2장: 알아둬야 할 자바스크립트)
  - pp. 94-178 (3장: 노드 기능 알아보기)
- [Heropy HTML + CSS 튜토리럴](https://heropy.blog/2019/04/24/html-css-starter/)
- [Dev.to JavaScript 메뉴 튜토리럴](https://dev.to/ljcdev/easy-hamburger-menu-with-js-2do0)

###### [↑ Schedule / 일정 다시 가기](/schedule.html#course-topics--과정-화제)

---

### Week 3 / 3주차 3월17일

#### 3. Node Webserver First Steps / 노드 웹서버 첫 걸음

This week we take a look at some of the major problems and mistakes from last week and how to fix them. We will have a brief introduction to what Node is, how it works, and why it's important. Finally, we'll get to work on creating a web server and simple website in Node.js.

이번 주에는 지난주의 주요 문제와 실수를 살펴보고 이를 수정하는 방법을 알아봅시다. Node.js가 무엇인지, 어떻게 작동하는지, 왜 중요한지에 대해 간략하게 소개하겠습니다. 마지막으로 Node.js에서 웹 서버와 간단한 웹 사이트를 만드는 작업을 시작합니다.

##### Resources / 리소스

- PPT <a href="slides/https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/_3.%20%EA%B3%BC%EC%A0%9C%20%EB%AC%B8%EC%A0%9C%EC%99%80%20%ED%95%B4%EA%B2%B0.pdf">\*3. Assignment Problems & Solutions / 과제 문제와 해결</a>
- PPT <a href="https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/_4.%20Node.JS%EC%9D%98%20%EC%9D%B4%ED%95%B4.pdf">\*4. Understanding Node.js / Node.js의 이해</a>
- PPT <a href="https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/1.%20Node.js%EC%9D%98%20%EC%8B%9C%EC%9E%91.pdf">Unit 1. Starting Node.js / Node.js의 시작</a>

##### Required Reading / 필수 독서

- [_Get Programming with Node.js_](http://www.yes24.com/Product/Goods/86429845)
  - pp. 37-46 (Lesson 0: Node.js 설정과 JavaScript 엔진 설치)
  - pp. 67-78 (Lesson 3: Node.js 모듈 생성)
  - pp. 79-88 (Lesson 4: Node.js에서 웹 서버 만들기)
  - pp. 89-100 (Lesson 5: 수신 데이터 다루기)
  - pp. 101-116 (Lesson 6: 라우트와 외부 파일)

##### Recommended reading / 추천 독서

- [_Node.js 교과서_](http://www.yes24.com/Product/Goods/116192535)
  - pp. 179-216 (4장: http 모듈로 서버 만들기)
  - pp. 217-240 (5장: 패키지 매니저)
- [Node.js란 무엇인가?](https://velog.io/@sms8377/Javascript-Node.js%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80)
- [Node.js란...?](https://perfectacle.github.io/2017/06/18/what-is-node-js/)

###### [↑ Schedule / 일정 다시 가기](/schedule.html#course-topics--과정-화제)
