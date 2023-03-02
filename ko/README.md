<p align="center">
  <a href="https://ut-nodejs.github.io">🏠</a> | <a href="/en">English</a> | <a href="/ko"><u>[한국어]</u></a>
</p>

---

# 웹프로그래밍응용 2023

한국교통대학교, 충주

![Aaron pic](https://avatars.githubusercontent.com/u/6644259?s=200&v=4)

##### 강사

- 에런 스노버거 ([aaron@ut.ac.kr](aaron@ut.ac.kr)), 정보통신공학과, 한밭대학교

##### 온라인 클래스룸

| Google Classroom (PPTs) | [오전](https://classroom.google.com/c/NTEyMjUxMTM4MjQz?cjc=m5cbuja) | [오후](https://classroom.google.com/c/NTE2NTcyNjcwNjMz?cjc=sr6x7hg) |
| GitHub Classroom (과제) | [오전](https://classroom.github.com/classrooms/126310482-2023sp-259122-1-am) | [오후](https://classroom.github.com/classrooms/126310482-2023sp-259122-2-pm) |

이 저장소는 [컴퓨터과학](https://www.ut.ac.kr/ceit/sub02_00.do) 과정 [웹프로그래밍응용](https://ut-nodejs.github.io)은 에런 스노버거가 2023년 봄에 가르쳤다.

### 과정 화제

| Day | Date    | Unit | Topic                                                                           | 화제                                                                     |
| :-: | :------ | :--: | :------------------------------------------------------------------------------ | :----------------------------------------------------------------------- |
|  1  | 3월3일  |  --  | [Overview and introduction to class](/en/#1-overview-and-introduction-to-class) | [수업 소개](/ko/#1-overview-and-introduction-to-class)                   |
|  2  | 3월10일 |  0   | [Starting Node and GitHub Classroom](/en/#2-starting-node-and-github-classroom) | [노드 시작과 깃허브 클래스룸](/ko/#2-starting-node-and-github-classroom) |
|  3  | 3월17일 |  1   | [Node Webservers and Routes](/en/#3-node-webservers-and-routes)                 | [노드 웹서버와 라우팅](/ko/#3-node-webservers-and-routes)                |
|  4  | 3월24일 |  2   | [Routing in Express.js](/en/#4-routing-in-expressjs)                            | [Express.js 라우팅](/ko/#4-routing-in-expressjs)                         |
|  5  | 3월31일 |  2   | [Project Start](/en/#5-project-start)                                           | [프로젝트 시작](/ko/#5-project-start)                                    |
|  6  | 4월7일  |  3   | [Connecting to MongoDB](/en/#6-connecting-to-mongodb)                           | [MongoDB 연결](/ko/#6-connecting-to-mongodb)                             |
|  7  | 4월14일 |  4   | [User Data Models](/en/#7-user-data-models)                                     | [사용자 데이터 모델](/ko/#7-user-data-models)                            |
|  8  | 4월21일 |  --  | [Midterm Exam / Project](/en/#midterm-exam)                                     | [중간고사](/ko/#midterm-exam)                                            |
|  9  | 4월28일 |  4   | [CRUD (Create, Read, Update, Delete)](/en/#8-crud-create-read-update-delete)    | [CRUD](/ko/#8-crud-create-read-update-delete)                            |
| 10  | 5월5일  |  --  | HOLIDAY: Children's Day                                                         | 공휴일: 어린이날                                                         |
| 11  | 5월12일 |  5   | [User Authentication](/en/#9-user-authentication)                               | [사용자 인증](/ko/#9-user-authentication)                                |
| 12  | 5월19일 |  6   | [Adding an API](/en/#10-adding-an-api)                                          | [API 추가](/ko/#10-adding-an-api)                                        |
| 13  | 5월26일 |  7   | [Adding Chat Functionality](/en/#11-adding-chat-functionality)                  | [채팅 추가](/ko/#11-adding-chat-functionality)                           |
| 14  | 6월2일  |  8   | [Deploying to Production](/en/#12-deploying-to-production)                      | [프로덕션](/ko/#12-deploying-to-production)                              |
| 15  | 6월9일  | A,B  | [Supplementary Topics / Personal Projects](/en/#13-supplementary-topics)        | [개인 프로젝트](/ko/#13-supplementary-topics)                            |
| 16  | 6월16일 |  --  | [Final Exam](/en/#final-exam)                                                   | [기말고사](/ko/#final-exam)                                              |

<!----
| 16  | 6월16일 | --   | [Personal Projects](/en/#14-personal-projects)                                  | [개인 프로젝트]()             |
| 17  | 6월23일 | --   | [Final Exam](/en/#final-exam)                                                   | [기말고사]()                  |
| 18  | 6월30일 | --   | [Grading Period](/en/#grading)                                                  | [성적 처리 기간]()            |
---->

---

### Overview

Node.js는 Javascript로 웹 서버를 구축하는 데 사용되며 npm을 통해 사용할 수 있는 수많은 사전 구축 패키지가 있습니다. 이 수업은 책에 나열된 8개의 프로그래밍 프로젝트를 따르며 수업이 끝날 때 학생들이 9번째 개인 프로젝트를 수행해야 합니다. 개발 프로세스, 보안, 데이터베이스 관리(Mongoose), 사용자 계정 인증 및 프로덕션 배포와 같은 주제를 다룹니다. 또한 비동기 코드, 데이터 모델 및 Javascript 모듈 디버깅에 대해서도 배웁니다.

### Objectives / 교과목교육목표

Node.js와 Express로 웹서버, 웹사이트에서 CRUD 기능 이해하고 채팅 및 기타 대화형 기능 구현 을 배우고, 국제한 시대에 맞게 영어 표현도 배운다.

이 과정은 일련의 2시간 강의(중간에 휴식 포함)로 제공되며 학생들이 강의의 일부로 제공된 스타터 코드를 사용하여 일련의 강사 안내 연습에서 수업을 적용하는 실습 랩 세션이 이어집니다. 이 과정은 다음 주제를 다룹니다:

- Node.js 애플리케이션 실행 및 Node.js 모듈 생성
- Node.js 및 Express.js로 웹 서버 구축 및 라우팅 처리
- MongoDB에 연결하여 데이터 및 Controller, Model, View 패러다임 제공
- Node.js에서 CRUD(만들기, 읽기, 업데이트, 삭제) 기능 처리
- 사용자 계정 생성 및 사용자 인증
- API 구축 및 API 보안 추가
- Socket.io로 채팅 기능 추가
- 프로덕션에서 코드 배포 및 관리

## Lectures, practice, and assignments / 강의, 실습 및 과제

- 강의 : 매주 금요일 2시간 강의가 진행됩니다.
- 연습시간 : 각 강의의 마지막 시간은 강의에서 다룬 내용을 연습하는 시간입니다.
- 과제: 학생들은 GitHub Classroom에서 과제를 제출해야 합니다. ([오전](https://classroom.github.com/classrooms/126310482-2023sp-259122-1-am) | [오후](https://classroom.github.com/classrooms/126310482-2023sp-259122-2-pm)).

See the [Google Classroom](https://classroom.google.com) for class PPTs, lists, and announcements.

### Prerequisites / 전제 조건

Students should already be familiar with basic web programming an basic JavaScript. A list of expected knowledge will be made available for review...

### Preparing for the course / 수업 준비

이 과정에는 NodeJS와 기본 코드 편집기 또는 IDE가 필요합니다. [Node.JS](https://nodejs.org/en/download/) 및 [Visual Studio Code](https://code.visualstudio.com/download)와 같은 코드 편집기를 다운로드하여 설치해야 합니다.

<!---- **Detailed instructions can also be found [here](https://ut-nodejs.github.io/instructions) for installing the tools you need and working with the lab materials.** ---->

JavaScript, HTML 또는 CSS에 익숙하지 않은 경우 과정을 시작하기 전에 익숙해지기를 강력히 권장합니다. 그렇게 하면 도구에 익숙해지는 데 훨씬 적은 시간을 할애하고 방법에 더 집중할 수 있습니다. 다음 링크는 과정이 시작되기 전에 자신의 진도에 맞춰 학습할 수 있는 웹 프로그래밍에 대한 기본 소개를 제공합니다.

- [HTML](https://developer.mozilla.org/ko/docs/Web/HTML/Element).
- [CSS](https://developer.mozilla.org/ko/docs/Web/CSS/Reference).
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide).
- [How much JavaScript do you need to know to use NodeJS?](https://nodejs.dev/en/learn/how-much-javascript-do-you-need-to-know-to-use-nodejs/).

또한 git 및 GitHub로 작업하고 숙제를 제출하는 것과 관련된 다음 자료를 통해 작업하는 과정 전에 시간을 할애하는 것이 좋습니다.

- [git - 간편 안내서](https://up1.github.io/git-guide/index.ko.html)
- [누구나 쉽게 이해할 수 있는 git 입문](https://backlog.com/git-tutorial/kr/)

### Important Specifics / 중요한 세부 사항

#### Computer Software / 소프트웨어

우리가 사용할 소프트웨어는 다음과 같습니다.

- [Node.JS](https://nodejs.org/en/download/)
- [Visual Studio Code](https://code.visualstudio.com/download)
- [git](https://git-scm.com/downloads)

#### Main Texts / 과재

The primary text is:

![book-main](/img/gh-pages/book-main.jpg)

- Wexler, Jonathan. (2019, 2020 번역) _Get Programming with Node.js_, Manning Publishing Company (에이콘출판사 번역). [Yes24 link](http://www.yes24.com/Product/Goods/86429845).

다음은 유용할 수 있는 추가 텍스트입니다.

![book-extra](/img/gh-pages/book-extra.jpg)

- Jo, Hyunyoung. (2022). _Node.js 교과서, 3rd edition_. Gilbert. [Yes24 link](http://www.yes24.com/Product/Goods/116192535)

### Instructor / 강사

**Aaron Snowberger** is a PhD candidate in the Graduate School of Information and Communications Engineering, majoring in Information and Communications Engineering, at Hanbat National University, Korea. He received his B.S degree in Computer Science from the College of Engineering, University of Wyoming, USA in 2006 and his M.FA degree in Media Design from Full Sail University, USA in 2011. From 2010 to present, he is a professor of English Conversation at Jeonju University, Korea. His research interests include computer vision, natural language processing, image processing, signal processing, and machine learning.

### Grading / 성적 {#grading}

성적은 5가지 주요 구성 요소로 나뉩니다:

| %   | 부분          | 명세                                           |
| --- | ------------- | ---------------------------------------------- |
| 10% | 출석          |                                                |
| 30% | 과제          | 수업시간에 학습한 것을 GitHub Classroom에 저장 |
| 15% | 중간고사      | 쪽지시험 + 실기 프로젝트                       |
| 20% | 기말고사      | 쪽지시험 + 실기 프로젝트                       |
| 25% | 개인 프로젝트 | 책의 프로젝트와 추가 기능                      |

성적은 상대평가다. 다음은 최종 프로젝트에 대한 당신의 노력이 당신의 성적에 어떻게 반영될 것인지를 이해하기 위한 간단한 지침이다.

- 상대평가
  - _A: Customize (Content + Design)_
  - **B: Complete (including Practice Lab updates)**
  - C: Complete (_only_ code form the book / GitHub repo)
  - D: Incomplete or broken
  - F: Very minimal effort and/or Absences

#### 1. Attendance (including Participation) (10%) {#grading-attendance}

The university's guidelines on attendance are as follows:

- 3 Late = 1 Absence
- More than 20% Absences = F

If a student has a valid excuse to be absent, such as quarantining for COVID-19, a school event, etc, they may be given self-study work to complete.

Participation follows along with attendance in many ways. While individual participation points will not be recorded every day (there are too many students), a student's individual behavior and habits over the course of the semester will be taken into account. For example, a student who is always Late, or always sleeps, or always talks in class, or always turns in homework on time, will be awarded points corresponding to their behavior.

The following are ways to earn or lose participation points:

- Gain points
  - On time, participate in the class exercises
  - Complete all homework
  - Help other students
- Lose points
  - Be late or absent often
  - Use the phone, or be off task on the computer often
  - Do not turn in homework or participate in lab exercises
  - Be disorderly or disrespectful to the teacher or other students

#### 2. Daily Lab Exercises (30%) {#grading-practice}

These are graded on a {Complete, Half-complete, Incomplete} scale and will form the practical materials for each day's labs. See these instructions for how to access and work with each day's exercise.

See [https://ut-nodejs.github.io/instructions](https://ut-nodejs.github.io/instructions) for detailed instructions on obtaining and working with each day's lab materials.

#### Midterm Exam (15%) {#grading-midterm-exam}

It is possible that the CRUD or User Data Model assignments will be used for the Midterm. The midterm will be released after the lecture on Day 7 (4월14일) and will be due at 11:59pm on Day 9 (4월28일). <!--- The [midterm is available here](https://ut-nodejs.github.io/midterm-2023/).--->

#### Final Exam (20%) {#grading-final-exam}

It is possible that your Final project may be used for the Final Exam. But, there may be a quiz or test of some kind included. The final will be released after the lecture on Day 15 (6월9일) and will be due at 11:59pm on the Monday after Day 16 (6월19일). <!--- The [final is available here](https://ut-nodejs.github.io/final-2023/).--->

##### Exam Schedule {#grading-exam-schedule}

- Midterm exam: April 21 (Week 8) or April 28 (Week 9).
- Final exam: June 16 (Week 16).
- Final project due: June 19 (Monday).

#### 5. Final Project (25%) {#grading-final-project}

The Final Project should be an updated customization of the project we work on in class. It should do at least TWO things differently from the project described in the book:

1. Solve a different problem (i.e. not a Cooking / Recipe site)
2. Have a different design / style

Ways to make your project stand out:

- Use a CSS framework
- Include multiple page templates
- Implement your own, self-selected JavaScript functionality, widget, feature, etc.

<!---[Instructions for the final project are here](https://ut-nodejs.github.io/final-project/).--->

#### Contact

If you have questions, please contact Aaron at [aaron@ut.ac.kr](aaron@ut.ac.kr) or in Google Classroom .

### Detailed Course Schedule

---

#### 1. Overview and introduction to class

- \*0. 수업, 책, 강사 소개
- \*1. 웹 프로그래밍 복습
- \*2. 깃과 깃허브 클래스룸 소개

우리는 이 세션을 통해 학생들이 수업에 가져오는 관심사와 경험의 범위를 파악하고 다룰 주제를 조사할 것입니다. 우리는 수업 목표, 채점, 교과서에 대해 논의하고 강사를 알게 될 것입니다. 또한 수업에서 사용할 기본 웹 프로그래밍 기술, git, GitHub 및 GitHub 강의실을 검토합니다.

##### Resources

- [Google Classroom](https://classroom.google.com)
- [GitHub Classroom](https://classroom.github.com)
- [스라이드 \*0: 수업 소개](lecturenotes/)
- [스라이드 \*1: 웹 프로그래밍 복습](lecturenotes/)
- [스라이드 \*2: 깃과 깃허브](lecturenotes/)
- [Lab 0 materials](https://lse-me314.github.io/assignment01/)

##### Practice & Assignment

<!---- * Lab 1 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment1_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment1_solution.html). ---->

##### Required reading

- [누구나 쉽게 이해할 수 있는 git 입분](https://backlog.com/git-tutorial/kr/)

##### Recommended reading

- [How much JavaScript do you need to know to use NodeJS?](https://nodejs.dev/en/learn/how-much-javascript-do-you-need-to-know-to-use-nodejs/)
- [git - 간편 안내서](https://up1.github.io/git-guide/index.ko.html)
- [누구나 쉽게 이해할 수 있는 git 입문](https://backlog.com/git-tutorial/kr/)
- [깃 브랜칭을 배워봅시다](https://learngitbranching.js.org/?locale=ko)

---

#### 2. Starting Node and GitHub Classroom

- Unit 0. 시작하기 / Getting Set up
  - Lesson 0. Node.js의 설정과 JavaScript 엔진 설치 / Setting up Node.js and the JavaScript engine
  - Lesson 1. 환경설정 / Configuring your environment
  - Lesson 2. Node.js 애플리케이션 실행 / Running a Node.js application

This week ...

##### Resources

- [Lecture Notes Part 1](lecturenotes/ME314_day2.pdf)
- [Lab 2 materials](https://lse-me314.github.io/assignment02/)

##### Practice & Assignment

<!---- * Lab 2 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment2_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment2_solution.html). ---->

##### Required reading

-

##### Recommended reading

- ***

#### 3. Node Webservers and Routes

- Unit 1. Node.js의 시작 / Getting started with Node.js
  - Lesson 3. Node.js 모듈의 생성 / Creating a Node.js module
  - Lesson 4. Node.js에서 웹 서버 만들기 / Building a simple web server in Node.js
  - Lesson 5. 수신 데이터 다루기 / Handling incoming data
  - Lesson 6. 라우트와 외부 파일 / Writing better routes and serving external files

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day3.pdf)
- [Lab 3 materials](https://lse-me314.github.io/assignment03/)

##### Practice & Assignment

<!--- * Lab 3 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment3_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment3_solution.html). ---->

##### Required reading

-

##### Recommended Reading

- ***

#### 4. Routing in Express.js

- Lesson 7. 캡스톤 프로젝트: 첫 번째 웹 애플리케이션 만들기 / Capstone: Creating your first web application
- Unit 2. Express.js를 통한 웹 개발 / Easier web development with Express.js
  - Lesson 8. Express.js의 설정 / Setting up an app with Express.js
  - Lesson 9. Express.js에서의 라우트 / Routing in Express.js

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day4.pdf)
- [Lab 4 materials](https://lse-me314.github.io/assignment04/)

##### Practice & Assignment

<!---- * Lab 4 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment4_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment4_solution.html). ---->

##### Required Reading

-

##### Recommended Reading

- ***

#### 5. Project Start

- Lesson 10 뷰와 템플릿의 연결 / Connecting views with templates
- Lesson 11. 설정과 에러 처리 / Configurations and error handling
- Lesson 12. 캡스톤 프로젝트: Express.js를 통한 Confetti Cuisine 사이트 개선 / Capstone: Enhancing the Confetti Cuisine site with Express.js

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day5.pdf)
- [Lab 5 materials](https://lse-me314.github.io/assignment05/)

##### Practice & Assignment

<!---- The **mid-term exam** will be posted on [Moodle](https://shortcourses.lse.ac.uk/course/view.php?id=158). ---->

##### Required Reading

-

##### Recommended Reading

- ***

#### 6. Connecting to MongoDB

- Unit 3. 데이터베이스 연결 / Connecting to a database
  - Lesson 13. 몽고DB 데이터베이스 셋업 / Setting up a MongoDB database
  - Lesson 14. Mongoose를 사용한 모델 제작 / Building models with Mongoose
  - Lesson 15. 컨트롤러와 모델과의 연결 / Connecting controllers and models
  - Lesson 16. 캡스톤: 사용자 구독 저장 / Capstone: Saving user subscriptions

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day6.pdf)
- [Lab 6 materials](https://lse-me314.github.io/assignment06/)

##### Practice & Assignment

<!---- * Lab 6 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment6_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment6_solution.html). ---->

##### Required Reading

-

##### Recommended Reading

- ***

#### 7. User Data Models

- Unit 4. 사용자 모델 제작 / Building a User model
  - Lesson 17. 데이터 모델의 개선 / Improving your data models
  - Lesson 18. 사용자 모델의 구현 / Building the user model
  - Lesson 19. 모델의 생성과 읽기 / Creating and reading your models

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day7.pdf)
- [Lab 7 materials](https://lse-me314.github.io/assignment07/)

##### Practice & Assignment

<!---- * Lab 7 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment7_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment7_solution.html).---->

<!---

* [Lecture Notes](lecturenotes/ME314_day7.pdf)
* [Lab 7 materials](https://lse-me314.github.io/assignment07/)
* Lab 7 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment7_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment7_solution.html).

--->

##### Required Reading

-

##### Recommended Reading

- ***

#### 8. CRUD (Create, Read, Update, Delete)

- Lesson 20. 모델의 업데이트와 삭제 / Updating and deleting your models
- Lesson 21. 캡스톤 프로젝트: Confetti Cusine에 CRUD 모델 추가 / Capstone: Adding CRUD models to Confetti Cuisine

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day8.pdf)
- [Lab 8 materials](https://lse-me314.github.io/assignment08/)

##### Practice & Assignment

<!---- * Lab 8 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment8_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment8_solution.html). ---->

##### Required reading

-

##### Recommended Reading

- ***

#### Midterm Exam

- 중간고사 / 프로젝트

For review...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day9.pdf)
- [Lab 9 materials](https://lse-me314.github.io/assignment09/)

##### Practice & Assignment

<!---- * Lab 9 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment9_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment9_solution.html). ---->

##### Required reading

-

##### Recommended Reading

- ***

#### 9. User Authentication

- Unit 5. 사용자 계정 인증 / Authenticating User accounts
  - Lesson 22. 세션과 플래시 메시지의 추가 / Adding sessions and flash messages
  - Lesson 23. 사용자 로그인 폼 생성과 패스워드 해시 / Building a user login and hashing passwords
  - Lesson 24. 사용자 인증 추가 / Adding user authentication
  - Lesson 25. 캡스톤 프로젝트: Confetti Cuisine에 사용자 인증 추가 / Capstone: Adding user authentication to Confetti Cuisine

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day9.pdf)
- [Lab 9 materials](https://lse-me314.github.io/assignment9/)

##### Practice & Assignment

<!--- * Lab 9 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment9_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment9_solution.html). --->

##### Required reading

-

##### Recommended Reading

- ***

#### 10. Adding an API

- Unit 6. API 빌드 / Building an API
  - Lesson 26. 애플리케이션에 API 추가 / Adding an API to your application
  - Lesson 27. 애플리케이션에서 API 액세스 / Accessing your API from your application
  - Lesson 28. API 보안 / Adding API security
  - Lesson 29. 캡스톤 프로젝트: API 구현 / Capstone: Implementing an API

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day10.pdf)
- [Lab 10 materials](https://lse-me314.github.io/assignment10/)

##### Practice & Assignment

<!---- * Lab 10 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment10_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment10_solution.html). ---->

##### Required reading

-

##### Recommended Reading

- ***

#### 11. Adding Chat Functionality

- Unit 7. 채팅 기능 추가 / Adding Chat functionality
  - Lesson 30. socket.io로의 작업 / Working with Socket.io
  - Lesson 31. 채팅 메시지의 저장 / Saving chat messages
  - Lesson 32. 채팅 알림 표시 추가 / Adding a chat notification indicator
  - Lesson 33. 캡스톤 프로젝트: Confetti Cuisine에 채팅 기능 추가 / Capstone: adding a chat feature to Confetti Cuisine

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day11.pdf)
- [Lab 11 materials](https://lse-me314.github.io/assignment11/)

##### Practice & Assignment

<!---- * Lab 11 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment11_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment11_solution.html). ---->

##### Required reading:

-

##### Recommended reading:

-

<!---
##### To use the `rtweet` package in R:
* [`rtweet` vignette](https://github.com/mkearney/rtweet)
* Twitter Authentication setup:
    + [Official](https://dev.twitter.com/oauth/overview/application-owner-access-tokens)
    + [Walkthrough](https://rtweet.info/articles/auth.html)
* Twitter API documentation:
    + [Overview of REST API](https://dev.twitter.com/rest/public)
    + [Overview of streaming API](https://dev.twitter.com/streaming/overview)

--->

[](./data/covid_country_data.csv)
[](./data/ess.csv)
[](./data/const-econ-vars.csv)

---

#### 12. Deploying to Production

- Unit 8. 프로덕션에서의 코드 배포와 관리 / Deploying and managing code in production
  - Lesson 34. 애플리케이션 배포 / Deploying your application
  - Lesson 35. 프로덕션에서의 관리 / Managing in production
  - Lesson 36 애플리케이션의 테스팅 / Testing your application
  - Lesson 37. 캡스톤 프로젝트: Confetti Cuisine의 배포 / Capstone: Deploying Confetti Cuisine

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day12.pdf)
- [Lab 12 materials](https://lse-me314.github.io/assignment12/)

##### Practice & Assignment

<!---- * Lab 12 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment12_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment12_solution.html). ---->

##### Required Reading:

-

##### Recommended Reading:

- ***

#### 13. Supplementary Topics

- Appendix A. ES6에서 소개하는 JavaScript 문법 / JavaScript syntax introduced in ES6
- Appendix B. 로깅과 Node.js의 전역 객체의 사용 / Logging and using Node.js global objects
- 개인 프로젝트 안내와 선택 / Personal projects information and selection

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day13.pdf)
- [Lab 13 materials](https://lse-me314.github.io/assignment13/)

##### Practice & Assignment

<!---- * Lab 13 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment13_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment13_solution.html). ---->

##### Required Reading:

-

##### Recommended Reading:

- ***

#### 14. Personal Projects

- 개인 프로젝트 / Personal projects

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day14.pdf)
- [Lab 14 materials](https://lse-me314.github.io/assignment14/)

##### Practice & Assignment

<!---- * Lab 15 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment15_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment15_solution.html). ---->

##### Required Reading:

-

##### Recommended Reading:

- ***

#### Final Exam

- 기말고사 / 프로젝트

For review...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day16.pdf)
- [Lab 16 materials](https://lse-me314.github.io/assignment16/)

##### Practice & Assignment

<!---- * Lab 12 solution [as RMarkdown](https://lse-me314.github.io/solutions/ME314_assignment12_solution.Rmd) or [as HTML](https://lse-me314.github.io/solutions/ME314_assignment12_solution.html). ---->

##### Required Reading:

-

##### Recommended Reading:

- ***

#### Grading

- 상대평가
  - _A: Customize (Content + Design)_
  - **B: Complete (just what's in the book)**
  - C: Incomplete or broken
  - D: Very minimal effort
  - F: Absences

##### Resources

##### Recommended Reading:
