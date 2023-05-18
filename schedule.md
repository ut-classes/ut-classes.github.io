<p id="menu" align="center">
  <a href="https://ut-nodejs.github.io" title="Home">🏠</a> |
  <a href="about.html" title="About">개요</a> |
  <a href="/schedule.html" title="Schedule"><u>[일정]</u></a> |
  <a href="/slides.html" title="Slides">스라이드</a> |
  <a href="/assignments.html" title="Assignments">과제</a> |
  <a href="/project.html" title="Project">프로젝트</a> |
  <a href="/tests.html" title="Tests">시험</a> |
  <a href="/grading.html" title="Grading">성적</a> |
  <a href="/resources.html" title="Resources">자료</a>
  <!-- <a href="https://pollev.com/aarons007" title="PollEverywhere">설문↗️</a> -->
</p>

---

# Web Programming Application 2023

<p>한국교통대학교, 충주<small> | KNUT (Korea National University of Transportation)</small></p>

---

<!--
## Notes AFTER Class **(5주차)**

| Activity | Morning | Afternoon |
| -------- | ------- | --------- |
| 실습     | 2주차 Web Programming Practice (less look at Bootstrap) | Lesson 6 code (listing6.5, listing6.6) + Basic Web Programming (more Bootstrap) |
| 과제     | No time - will give _MORE_ time next week | 30 min, most _started_ Lesson 7 - give more time next week |
| 다음 주  | Lesson 7 CODING time (_MORE_) + Unit 2 PPT         | Lesson 7 CODING time + Unit 2 PPT         |
| Notes    | MORE students gone (again) - 9 this week           | Only 2 missing today                      |
-->

## This Week / 11주차 5월19일

![this-week](/img/gh-pages/slides-covers/4.17-building-user-model.jpg)

#### 11. Unit 4: CRUD Operations / CRUD 작업

This week we will build out the rest of our CRUD operations for our User model. We will also add some additional validation to our model and add some additional routes to our application. Then we will talk about our Final Project and you will have time to work on it.

이번 주에는 사용자 모델의 CRUD 작업을 완성합니다. 또한 모델에 추가적인 유효성 검사를 추가하고 애플리케이션에 추가적인 라우트를 추가합니다. 그런 다음 최종 프로젝트에 대해 이야기하고 작업할 시간을 드립니다.

##### Assignment / 과제

This week's assignment is continuing Week 10's assignment. 이번 주의 과제는 10주차 과제를 계속하는 것입니다.

- [10주차 **오전** 과제 받기](https://classroom.github.com/a/is-vbBM_)
- [10주차 _오후_ 과제 받기](https://classroom.github.com/a/Q0S0uHH3)
- [10주차 과제 **HELP**](https://github.com/orgs/ut-nodejs/discussions/7)

See the [List of Assignments](https://ut-nodejs.github.io/assignments.html#list-of-assignments--과제-목록) for specifics about grading. 과제의 세부 사항은 과제 목록을 참조하십시오.

##### Resources / 리소스

- PPT <a href="/slides/4.17-building-user-model.pdf">Unit 4: 17-20. Building a User Model / 사용자 모델 제작</a>

##### Required Reading / 필수 독서

- [_Get Programming with Node.js_](http://www.yes24.com/Product/Goods/86429845)
  - pp. 275-287 (Lesson 19: 모델의 생성과 읽기)
  - pp. 289-300 (Lesson 20: 모델의 업데이트와 삭제)

##### Recommended reading / 추천 독서

- [_Node.js 교과서_](http://www.yes24.com/Product/Goods/116192535)
  - pp. 387-396 (8.5: CRUD 작업하기)
  - pp. 397-415 (8.6: 몽구스 사용하기)
  - pp. 415-416 (8.7: 함께 보면 좋은 자료)

---

## Course Topics / 과정 화제

| Week | Date | Unit | 화제                                                                         | Topic                                           |
| :--: | :--- | :--: | :--------------------------------------------------------------------------- | :---------------------------------------------- |
|  1   | 3/3  |  --  | [수업 소개](/schedule.html#week-1--1주차-3월3일)                             | Overview and introduction to class              |
|  2   | 3/10 |  0   | [깃허브 클래스룸과 웹프로그래밍 복습](/schedule.html#week-2--2주차-3월10일)  | GitHub Classroom & Web Programming Review       |
|  3   | 3/17 |  1   | [노드 웹서버 첫 걸음](/schedule.html#week-3--3주차-3월17일)                  | Node Webserver First Steps                      |
|  4   | 3/24 |  1   | [캡스톤1: 첫 웹 앱](/schedule.html#week-4--4주차-3월24일)                    | Capstone 1: First Web App                       |
|  5   | 3/31 |  1   | [캡스톤1: 연속 (부트스트랩 사용)](/schedule.html#week-5--5주차-3월31일)      | Capstone 1: Continued (with Bootstrap)          |
|  6   | 4/7  |  2   | [Express를 통한 웹 개발](/schedule.html#week-6--6주차-4월7일)                | Express Webserver                               |
|  7   | 4/14 |  3   | [MongoDB 연결](/schedule.html#week-7--7주차-4월14일)                         | Connecting MongoDB                              |
|  8   | 4/21 |  --  | [**중간고사:** 캡스톤2](/schedule.html#week-8--8주차-4월21일)                | **Midterm Exam:** Capstone 2                    |
|  9   | 4/28 |  3   | [MongoDB 연결 + 캡스톤3: MongoDB 추가](/schedule.html#week-9--9주차-4월28일) | Connecting MongoDB + Capstone 3                 |
|  --  | 5/5  |  --  | _공휴일: 어린이날_                                                           | _HOLIDAY: Children's Day_                       |
|  10  | 5/12 |  4   | [사용자 데이터 모델](/schedule.html#week-10--10주차-5월12일)                 | User Data Models                                |
|  11  | 5/19 |  4   | 캡스톤4: CRUD (생성, 조회, 수정, 삭제)                                       | Capstone 4: CRUD (Create, Read, Update, Delete) |
|  12  | 5/26 |  5   | 사용자 인증                                                                  | User Authentication                             |
|  13  | 6/2  |  5   | 캡스톤5: 사용자 인증 추가                                                    | Capstone 5: Adding User Authentication          |
|  14  | 6/9  |  6   | API 추가 (+ 캡스톤6?)                                                        | Adding an API (+ Capstone 6?)                   |
|  15  | 6/16 |  --  | 최종 프로젝트 + 기말고사                                                     | Final Projects + Final Exam                     |

<!----
| 16  | 6월16일 | --   | [Personal Projects](/en/#14-personal-projects)                                  | [개인 프로젝트]()             |
| 17  | 6월23일 | --   | [Final Exam](/en/#final-exam)                                                   | [기말고사]()                  |
| 18  | 6월30일 | --   | [Grading Period](/en/#grading)                                                  | [성적 처리 기간]()            |
---->

<!-- | 6 | 4월7일 | 3 | Connecting to MongoDB | MongoDB 연결 |
| 7 | 4월14일 | 4 | User Data Models | 사용자 데이터 모델 |
| 8 | 4월21일 | -- | Midterm Exam / Project | 중간고사 |
| 9 | 4월28일 | 4 | CRUD (Create, Read, Update, Delete) | CRUD (생성, 조회, 수정, 삭제) |
| -- | 5월5일 | -- | _HOLIDAY: Children's Day_ | _공휴일: 어린이날_ |
| 10 | 5월12일 | 5 | User Authentication | 사용자 인증 |
| 11 | 5월19일 | 6 | Adding an API | API 추가 |
| 12 | 5월26일 | 7 | Adding Chat Functionality | 채팅 추가 |
| 13 | 6월2일 | 8 | Deploying to Production | 프로덕션 |
| 14 | 6월9일 | A,B | Supplementary Topics / Personal Projects | 개인 프로젝트 |
| 15 | 6월16일 | -- | Final Exam | 기말고사 | -->

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

##### Assignment / 과제

- [2주차 **오전** 과제 받기](https://classroom.github.com/a/ufXcgZ68)
- [2주차 _오후_ 과제 받기](https://classroom.github.com/a/YeQuxwK6)
- [2주차 과제 **HELP**](https://github.com/orgs/ut-nodejs/discussions/1)

책에서 다음 코드 연습을 완료하십시오. 그런 다음 다시 GitHub 클래스룸으로 "커밋 및 푸시" 하십시오.

- `messages.js`
- `numbers.js`
- `print.js`

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

##### Assignment / 과제

- [3주차 **오전** 과제 받기](https://classroom.github.com/a/poWHzDMH)
- [3주차 _오후_ 과제 받기](https://classroom.github.com/a/Fyol0_-I)
- [3주차 과제 **HELP**](https://github.com/orgs/ut-nodejs/discussions/2)

책에서 다음 코드 연습을 완료하십시오. 그런 다음 다시 GitHub 클래스룸으로 "커밋 및 푸시" 하십시오.

- `/practice/lesson-5/listing.5.4.EX.js`
- `/practice/lesson-5/listing.5.6.TODO.js`

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

---

### Week 4 / 4주차 3월24일

#### 4. Capstone 1: First Web Application / 캡스톤 1: 첫 번째 웹 애플리케이션

This week we will finish Lesson 6 in dealing with routes and external files. Then we will build our first full web application in Lesson 7 with our first Capstone Project.

이번 주에 우리는 라우트와 외부 파일을 다루는 6과를 끝낼 것입니다. 그런 다음에 첫 번째 캡스톤 프로젝트를 사용하여 7과에서 첫 번째 웹 애플리케이션을 만듭니다.

##### Assignment / 과제

- [4주차 **오전** 과제 받기](https://classroom.github.com/a/TJpdR0C3)
- [4주차 _오후_ 과제 받기](https://classroom.github.com/a/F4nLnLQw)
- [4주차 과제 **HELP**](https://github.com/orgs/ut-nodejs/discussions/3)

책에서 다음 코드 연습을 완료하십시오. 그런 다음 다시 GitHub 클래스룸으로 "커밋 및 푸시" 하십시오.

- 지난주의 저장소 (학습)
  - `/practice/lesson-6/listing.6.4.EX.js`
  - `/practice/lesson-6/listing.6.6.TODO.js`
  - `/practice/lesson-6/listing.6.6.TODO.js`
- 이 번주의 저장소 (과제)
  - [프로젝트 readme.md](https://github.com/ut-nodejs/2-webserver-capstone)의 지침을 따르고 완성된 웹 애플리케이션을 GitHub 클래스룸으로 "커밋 및 푸시" 하십시오.

##### Resources / 리소스

- PPT <a href="https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/1.%20Node.js%EC%9D%98%20%EC%8B%9C%EC%9E%91.pdf">Unit 1. Starting Node.js / Node.js의 시작</a>
- PPT <a href="https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/1-7.%20%EC%BA%A1%EC%8A%A4%ED%86%A41%20-%20%EC%B2%AB%20%EC%9B%B9%20%EC%95%A0%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98.pdf">Unit 1-7. Capstone 1: First Web Application / 캡스톤1: 첫 웹 애플리케이션</a>
- [Bootstrap CSS](https://getbootstrap.kr/)
- [Tailwind CSS](https://tailwindcss.com/) (다른 CSS 프레임워크) &bull; [Tailwind Elements](https://tailwind-elements.com/) (컴포넌트 예시)
- [Pixabay.com](https://pixabay.com) (저작권 없는 이미지)

##### Required Reading / 필수 독서

- [_Get Programming with Node.js_](http://www.yes24.com/Product/Goods/86429845)
  - pp. 101-116 (Lesson 6: 라우트와 외부 파일)
  - pp. 117-129 (Lesson 7: 캡스톤 프로젝트: 첫 번째 웹 애플리케이션)

##### Recommended reading / 추천 독서

- [_Node.js 교과서_](http://www.yes24.com/Product/Goods/116192535)
  - pp. 179-216 (4장: http 모듈로 서버 만들기)
  - pp. 217-240 (5장: 패키지 매니저)

###### [↑ Schedule / 일정 다시 가기](/schedule.html#course-topics--과정-화제)

---

### Week 5 / 5주차 3월31일

#### 5. Capstone 1: Continued (with Bootstrap) / 캡스톤 1: 연속 (부트스트랩 사용)

This week will include **more in-class coding time**. We will continue working on our first Capstone Project, adding Bootstrap to our web application. We will build a simple `index.html` page together with [Bootstrap](https://getbootstrap.kr) and students will add their own pages to the project.

이번 주에는 **수업 중 더 많은 코딩 시간**이 포함될 것입니다. 우리는 웹 응용 프로그램에 [부트스트랩](https://getbootstrap.kr)을 추가하여 첫 번째 캡스톤 프로젝트를 계속 작업할 것입니다. 우리는 간단한 `index.html` 페이지를 부트스트랩과 함께 만들고 학생들은 자신의 페이지를 프로젝트에 추가할 것입니다.

##### Assignment / 과제

- 이 번주의 저장소 (과제)
  - [프로젝트 readme.md](https://github.com/ut-nodejs/2-webserver-capstone)의 지침을 따르고 완성된 웹 애플리케이션을 GitHub 클래스룸으로 "커밋 및 푸시" 하십시오.

##### Resources / 리소스

- PPT <a href="https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/1-7.%20%EC%BA%A1%EC%8A%A4%ED%86%A41%20-%20%EC%B2%AB%20%EC%9B%B9%20%EC%95%A0%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98.pdf">Unit 1-7. Capstone 1: First Web Application / 캡스톤1: 첫 웹 애플리케이션</a>
- PPT <a href="https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/1-7b.%20%EC%BA%A1%EC%8A%A4%ED%86%A41%20-%20%EB%B6%80%ED%8A%B8%EC%8A%A4%ED%8A%B8%EB%9E%A9%20%EB%B3%B4%EC%B6%A9.pdf">Unit 1-7b. Capstone 1 (with Bootstrap) / 캡스톤 1 하고 부트스트랩 포함</a>
- [Heropy 튜토리얼](https://heropy.blog/2019/04/24/html-css-starter/)
- [Bootstrap CSS](https://getbootstrap.kr/) (한국어)
- [Pixabay.com](https://pixabay.com) (저작권 없는 이미지)
- [2주차 과제의 readme.md](https://github.com/ut-nodejs/0-starting-nodejs)
- [4주차 과제의 readme.md](https://github.com/ut-nodejs/2-webserver-capstone)

##### Required Reading / 필수 독서

- [_Get Programming with Node.js_](http://www.yes24.com/Product/Goods/86429845)
  - pp. 117-129 (Lesson 7: 캡스톤 프로젝트: 첫 번째 웹 애플리케이션)

##### Recommended reading / 추천 독서

- [Bootstrap 문서](https://getbootstrap.kr/docs/5.2/getting-started/introduction/)

###### [↑ Schedule / 일정 다시 가기](/schedule.html#course-topics--과정-화제)

---

### Week 6 / 6주차 4월7일

#### 6. Unit 2: Web Development with Express.js / Express.js를 통한 웹 개발

Let's change things up a little bit this week. We will be learning about [Express.js](https://expressjs.com/ko/), a popular web framework for Node.js. It makes it easier to build web applications and APIs. We will also learn about the [EJS](https://ejs.co/) template engine, which is used to generate HTML, and [middleware](https://expressjs.com/ko/guide/using-middleware.html), which is code that runs between the request and the response.

이번 주에는 조금 다른 것을 배워보겠습니다. 우리는 [Express.js](https://expressjs.com/ko/)를 배울 것입니다. 이것은 Node.js의 인기있는 웹 프레임워크입니다. 웹 응용 프로그램과 API를 더 쉽게 만들 수 있습니다. 우리는 또한 HTML을 생성하기 위해 사용되는 [EJS](https://ejs.co/) 템플릿 엔진과 요청과 응답 사이에 실행되는 코드인 [미들웨어](https://expressjs.com/ko/guide/using-middleware.html)에 대해 배울 것입니다.

##### Assignment / 과제

- [6주차 **오전** 과제 받기](https://classroom.github.com/a/rmcCIOLs)
- [6주차 _오후_ 과제 받기](https://classroom.github.com/a/PS97F3y2)
- [6주차 과제 **HELP**](https://github.com/orgs/ut-nodejs/discussions/4)

See the [List of Assignments](https://ut-nodejs.github.io/assignments.html#list-of-assignments--과제-목록) for specifics about grading. 과제의 세부 사항은 과제 목록을 참조하십시오.

##### Resources / 리소스

- PPT <a href="/slides/2.8-11-express-web-development.pdf">Unit 2: 8-11. Web Development with Express.js / Express.js를 통한 웹 개발</a>
- [Express.js](https://expressjs.com/ko/)
- [Express 미들웨어](https://expressjs.com/ko/guide/using-middleware.html)
- [EJS 템플릿 엔진](https://ejs.co/)

##### Required Reading / 필수 독서

- [_Get Programming with Node.js_](http://www.yes24.com/Product/Goods/86429845)
  - pp. 133-141 (Lesson 8: Express.js 설정)
  - pp. 143-154 (Lesson 9: Express.js에서의 라우트)
  - pp. 155-164 (Lesson 10: 뷰와 템플릿의 연결)
  - pp. 165-171 (Lesson 11: 설정과 에러 처리)

##### Recommended reading / 추천 독서

- [_Node.js 교과서_](http://www.yes24.com/Product/Goods/116192535)
  - pp. 241-290 (6장: 익스프레스 웹 서버 만들기)

###### [↑ Schedule / 일정 다시 가기](/schedule.html#course-topics--과정-화제)

---

### Week 7 / 7주차 4월14일

#### 7. Unit 3: Connecting to MongoDB / MongoDB에 연결

It's time to start working with a database where we can store our data. We will be using [MongoDB](https://www.mongodb.com/), a popular NoSQL database. We will also be using [Mongoose](https://mongoosejs.com/), an Object Data Modeling (ODM) library for MongoDB and Node.js. **This week we will also be going over the [Midterm Study Guide.](/midterm.html)**

데이터를 저장할 수 있는 데이터베이스를 사용하여 작업을 시작할 시간입니다. 우리는 인기있는 NoSQL 데이터베이스인 [MongoDB](https://www.mongodb.com/)를 사용할 것입니다. 우리는 또한 MongoDB와 Node.js를 위한 객체 데이터 모델링 (ODM) 라이브러리인 [Mongoose](https://mongoosejs.com/)를 사용할 것입니다. **이번 주에는 [중간고사 스터디 가이드](/midterm.html)도 다룰 것입니다.**

##### Assignment / 과제

- [7주차 **오전** 과제 받기](https://classroom.github.com/a/WlIOQuYe)
- [7주차 _오후_ 과제 받기](https://classroom.github.com/a/HW6fxILP)
- [7주차 과제 **HELP**](https://github.com/orgs/ut-nodejs/discussions/5)

See the [List of Assignments](https://ut-nodejs.github.io/assignments.html#list-of-assignments--과제-목록) for specifics about grading. 과제의 세부 사항은 과제 목록을 참조하십시오.

##### Resources / 리소스

- PPT <a href="/slides/3.13-15-connecting-mongodb.pdf">Unit 3: 13-16. Connecting to MongdoDB / MongoDB에 연결</a>
- [Midterm Study Guide / 중간고사 스터디 가이드](/midterm.html)
- [MongoDB](https://www.mongodb.com/ko-kr/)
- [MongoDB Shell](https://www.mongodb.com/try/download/shell)
- [Mongoose](https://mongoosejs.com/)
- [Mongoose Schema](https://mongoosejs.com/docs/guide.html#definition)
- [How to Install MongoDB on Windows (사진)](https://www.knowledgehut.com/blog/web-development/install-mongodb-on-windows)
- [Windows에서 Chocolatey를 사용하여 MongoDB 설치](https://whatilearned.tistory.com/139)

##### Required Reading / 필수 독서

- [_Get Programming with Node.js_](http://www.yes24.com/Product/Goods/86429845)
  - pp. 189-202 (Lesson 13: MongoDB 셋업)
  - pp. 203-211 (Lesson 14: Mongoose를 사용한 모델 제작)
  - pp. 213-226 (Lesson 15: 컨트롤러와 모델과의 연결)

##### Recommended reading / 추천 독서

- [_Node.js 교과서_](http://www.yes24.com/Product/Goods/116192535)
  - pp. 241-415 (8장: 몽고디비)

###### [↑ Schedule / 일정 다시 가기](/schedule.html#course-topics--과정-화제)

---

### Week 8 / 8주차 4월21일

#### 8. Midterm Test / 중간고사

The midterm test consists of 2 parts. / 중간고사는 2가지 부분으로 이루어집니다.

1. Online Quiz / 온라인 퀴즈 ([Study Guide / 스터디 가이드](https://ut-nodejs.github.io/midterm.html))
2. Capstone Project / 캡스톤 실기 시험

This test is **OPEN BOOK**. You may use any resources you want, including the Internet, books, notes, etc. You may not communicate with other students or use any other resources during the test.<br>
이 시험은 **OPEN BOOK**입니다. 인터넷, 책, 노트 등을 포함한 모든 자료를 사용할 수 있습니다. 시험 중에 다른 학생과 통신하거나 다른 자료를 사용할 수 없습니다.

This midterm project, together with the online quiz, will be worth **15% of your final grade**.<br>
이 중간 프로젝트는 온라인 퀴즈와 함께 **최종 성적의 15%** 를 차지합니다.

##### Test / 시험

- Quiz: Node.js Google Forms / Node.js 구글 폼 퀴즈: **5%**
- Capstone: Lesson 12 / 12과 캡스톤 실기 시험: **10%**
- TOTAL / 총점: **15%**

##### Resources / 리소스

- PPT <a href="/slides/2.12-express-capstone.pdf">Unit 2: Capstone: Enhance your site with Express / 캡스톤: 익스프레스로 사이트 개선하기</a>
- [Midterm Study Guide / 중간고사 스터디 가이드](/midterm.html)

##### Required Reading / 필수 독서

- [_Get Programming with Node.js_](http://www.yes24.com/Product/Goods/86429845)
  - pp. 189-202 (Lesson 12: 캡스톤 프로젝트: Express.js를 통한 사이트 개선)

##### Recommended reading / 추천 독서

- [_Node.js 교과서_](http://www.yes24.com/Product/Goods/116192535)
  - pp. 241-290 (6장: 익스프레스 웹 서버 만들기)

###### [↑ Schedule / 일정 다시 가기](/schedule.html#course-topics--과정-화제)

---

### Week 9 / 9주차 4월28일

#### 9. Unit 3: Continuing MongoDB + Capstone / MongoDB 계속하기 + 캡스톤

**First, we will be going over the [Midterm Test solution.](https://github.com/ut-nodejs/assignment-solutions/tree/main/midterm-test-soln-PUBLIC)** After that, we will continue with MongoDB and Mongoose. We will also be starting the Capstone project, which will be due in 2 weeks (on May 12, 2023).

**먼저 [중간고사 해설](https://github.com/ut-nodejs/assignment-solutions/tree/main/midterm-test-soln-PUBLIC)을 진행합니다.** 그 후에는 MongoDB와 Mongoose를 계속 진행합니다. 또한 2주 후에 (2023년 5월 12일) 제출할 캡스톤 프로젝트를 시작합니다.

##### Assignment / 과제

- [9주차 **오전** 과제 받기](https://classroom.github.com/a/v0fVqeZI)
- [9주차 _오후_ 과제 받기](https://classroom.github.com/a/wX75l5Lj)
- [9주차 과제 **HELP**](https://github.com/orgs/ut-nodejs/discussions/6)

See the [List of Assignments](https://ut-nodejs.github.io/assignments.html#list-of-assignments--과제-목록) for specifics about grading. 과제의 세부 사항은 과제 목록을 참조하십시오.

##### Resources / 리소스

- PPT <a href="/slides/M-midterm-test-solution.pdf">M. Midterm Test Solution / 중간고사 해설</a>
- PPT <a href="/slides/3.13-15-connecting-mongodb.pdf">Unit 3: 13-15. Connecting to MongdoDB / MongoDB에 연결</a>
- PPT <a href="/slides/3.16-mongo-capstone.pdf">Unit 3: 16. MongdoDB Capstone / MongoDB 캡스톤</a>

##### Required Reading / 필수 독서

- [_Get Programming with Node.js_](http://www.yes24.com/Product/Goods/86429845)
  - pp. 189-202 (Lesson 13: MongoDB 셋업)
  - pp. 203-211 (Lesson 14: Mongoose를 사용한 모델 제작)
  - pp. 213-226 (Lesson 15: 컨트롤러와 모델과의 연결)
  - pp. 227-235 (Lesson 16: 캡스톤: 사용자 구독 저장)

##### Recommended reading / 추천 독서

- [_Node.js 교과서_](http://www.yes24.com/Product/Goods/116192535)
  - pp. 241-415 (8장: 몽고디비)

###### [↑ Schedule / 일정 다시 가기](/schedule.html#course-topics--과정-화제)

---

### Week 10 / 10주차 5월12일

#### 10. Unit 4: Building a User Model / 사용자 모델 제작

This week we will begin building our User and Course model-view-controllers. First we add some validation to our models, then we add CRUD methods to our controllers. Finally, we will add our new routes to our application.

이번 주에는 사용자와 코스 모델-뷰-컨트롤러를 제작하기 시작합니다. 먼저 모델에 일부 유효성 검사를 추가한 다음 컨트롤러에 CRUD 메서드를 추가합니다. 마지막으로 새로운 라우트를 애플리케이션에 추가합니다.

##### Assignment / 과제

- [10주차 **오전** 과제 받기](https://classroom.github.com/a/is-vbBM_)
- [10주차 _오후_ 과제 받기](https://classroom.github.com/a/Q0S0uHH3)
- [10주차 과제 **HELP**](https://github.com/orgs/ut-nodejs/discussions/7)

See the [List of Assignments](https://ut-nodejs.github.io/assignments.html#list-of-assignments--과제-목록) for specifics about grading. 과제의 세부 사항은 과제 목록을 참조하십시오.

##### Resources / 리소스

- PPT <a href="/slides/4.17-building-user-model.pdf">Unit 4: 17-20. Building a User Model / 사용자 모델 제작</a>

##### Required Reading / 필수 독서

- [_Get Programming with Node.js_](http://www.yes24.com/Product/Goods/86429845)
  - pp. 239-256 (Lesson 17: 데이터 모델의 개선)
  - pp. 257-273 (Lesson 18: 사용자 모델의 구현)

##### Recommended reading / 추천 독서

- [_Node.js 교과서_](http://www.yes24.com/Product/Goods/116192535)
  - pp. 387-396 (8.5: CRUD 작업하기)
  - pp. 397-415 (8.6: 몽구스 사용하기)
  - pp. 415-416 (8.7: 함께 보면 좋은 자료)

###### [↑ Schedule / 일정 다시 가기](/schedule.html#course-topics--과정-화제)

---

### Week 11 / 11주차 5월19일

#### 11. Unit 4: CRUD Operations / CRUD 작업

This week we will build out the rest of our CRUD operations for our User model. We will also add some additional validation to our model and add some additional routes to our application. Then we will talk about our Final Project and you will have time to work on it.

이번 주에는 사용자 모델의 CRUD 작업을 완성합니다. 또한 모델에 추가적인 유효성 검사를 추가하고 애플리케이션에 추가적인 라우트를 추가합니다. 그런 다음 최종 프로젝트에 대해 이야기하고 작업할 시간을 드립니다.

##### Assignment / 과제

This week's assignment is continuing Week 10's assignment. 이번 주의 과제는 10주차 과제를 계속하는 것입니다.

- [10주차 **오전** 과제 받기](https://classroom.github.com/a/is-vbBM_)
- [10주차 _오후_ 과제 받기](https://classroom.github.com/a/Q0S0uHH3)
- [10주차 과제 **HELP**](https://github.com/orgs/ut-nodejs/discussions/7)

See the [List of Assignments](https://ut-nodejs.github.io/assignments.html#list-of-assignments--과제-목록) for specifics about grading. 과제의 세부 사항은 과제 목록을 참조하십시오.

##### Resources / 리소스

- PPT <a href="/slides/4.17-building-user-model.pdf">Unit 4: 17-20. Building a User Model / 사용자 모델 제작</a>

##### Required Reading / 필수 독서

- [_Get Programming with Node.js_](http://www.yes24.com/Product/Goods/86429845)
  - pp. 275-287 (Lesson 19: 모델의 생성과 읽기)
  - pp. 289-300 (Lesson 20: 모델의 업데이트와 삭제)

##### Recommended reading / 추천 독서

- [_Node.js 교과서_](http://www.yes24.com/Product/Goods/116192535)
  - pp. 387-396 (8.5: CRUD 작업하기)
  - pp. 397-415 (8.6: 몽구스 사용하기)
  - pp. 415-416 (8.7: 함께 보면 좋은 자료)

###### [↑ Schedule / 일정 다시 가기](/schedule.html#course-topics--과정-화제)
