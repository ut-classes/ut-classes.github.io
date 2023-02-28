# UT NodeJS 2023

Korea National University of Transportation / 교통대학교, 충주

![Aaron pic](https://avatars.githubusercontent.com/u/6644259?s=200&v=4)

Instructor / 강사

- Aaron Snowberger ([aaron@ut.ac.kr](aaron@ut.ac.kr)), Graduate School of Information & Communications Engineering, Hanbat University
- 에런 스노버거, 정보통신공학과, 한밭대학교

Online Classroom / 온라인 클래스룸

- Google Classroom (PPTs) | [XXXXXXXX](https://classroom.google.com)
- GitHub Classroom (과제) | [오전](https://classroom.github.com/classrooms/126310482-2023sp-259122-1-am) | [오후](https://classroom.github.com/classrooms/126310482-2023sp-259122-2-pm)

This repository contains the course materials for the [Computer Science](https://www.lse.ac.uk/study-at-lse/Summer-Schools/Summer-School/Courses/Secure/Research-Methods-Data-Science-and-Mathematics) course [Web Programming Applications](https://www.lse.ac.uk/study-at-lse/Summer-Schools/Summer-School/Courses/Secure/Research-Methods-Data-Science-and-Mathematics/ME314) taught in Spring 2023 by Aaron Snowberger.

### Quick links to topics

| Day | Date    | Unit | Topic                                                                       |
| :-: | :------ | :--- | :-------------------------------------------------------------------------- |
|  1  | 3월3일  | --   | [Overview and introduction to class](#1-overview-and-introduction-to-class) |
|  2  | 3월10일 | 0    | [Starting Node and GitHub Classroom](#2-starting-node-and-github-classroom) |
|  3  | 3월17일 | 1    | [Node Webservers and Routes](#3-node-webservers-and-routes)                 |
|  4  | 3월24일 | 2    | [Routing in Express.js](#4-routing-in-expressjs)                            |
|  5  | 3월31일 | 2    | [Project Start](#5-project-start)                                           |
|  6  | 4월7일  | 3    | [Connecting to MongoDB](#6-connecting-to-mongodb)                           |
|  7  | 4월14일 | 4    | [User Data Models](#7-user-data-models)                                     |
|  8  | 4월21일 | --   | [Midterm Exam / Project](#midterm-exam)                                     |
|  9  | 4월28일 | 4    | [CRUD (Create, Read, Update, Delete)](#8-crud-create-read-update-delete)    |
| 10  | 5월5일  | --   | HOLIDAY: Children's Day                                                     |
| 11  | 5월12일 | 5    | [User Authentication](#9-user-authentication)                               |
| 12  | 5월19일 | 6    | [Adding an API](#10-adding-an-api)                                          |
| 13  | 5월26일 | 7    | [Adding Chat Functionality](#11-adding-chat-functionality)                  |
| 14  | 6월2일  | 8    | [Deploying to Production](#12-deploying-to-production)                      |
| 15  | 6월9일  | A,B  | [Supplementary Topics / Personal Projects](#13-supplementary-topics)        |
| 16  | 6월16일 | --   | [Final Exam](#final-exam)                                                   |

<!----
| 16  | 6월16일 | --   | [Personal Projects](#14-personal-projects)                                  |
| 17  | 6월23일 | --   | [Final Exam](#final-exam)                                                   |
| 18  | 6월30일 | --   | [Grading Period](#grading)                                                  |
---->

### Overview

Node.js is used to build web servers in Javascript, and there are numerous pre-built packages available through npm. This class follows 8 programming projects listed in the book and requires students to work on a 9th personal project at the end of the class. Topics such as development process, security, database management (Mongoose), user account authentication, and production deployment are covered. You will also learn about debugging asynchronous code, data models, and Javascript modules.

Node.js는 Javascript로 웹 서버를 구축하는 데 사용되며 npm을 통해 사용할 수 있는 수많은 사전 구축 패키지가 있습니다. 이 수업은 책에 나열된 8개의 프로그래밍 프로젝트를 따르며 수업이 끝날 때 학생들이 9번째 개인 프로젝트를 수행해야 합니다. 개발 프로세스, 보안, 데이터베이스 관리(Mongoose), 사용자 계정 인증 및 프로덕션 배포와 같은 주제를 다룹니다. 또한 비동기 코드, 데이터 모델 및 Javascript 모듈 디버깅에 대해서도 배웁니다.

### Objectives / 교과목교육목표

Understand CRUD functions in web servers and websites with Node.js and Express, learn to implement chatting and other interactive functions, and learn English expressions suitable for the international era.

Node.js와 Express로 웹서버, 웹사이트에서 CRUD 기능 이해하고 채팅 및 기타 대화형 기능 구현 을 배우고, 국제한 시대에 맞게 영어 표현도 배운다.

The course will be delivered as a series of 2-hour lectures (with a break in the middle), followed by practice lab sessions where students will apply the lessons in a series of instructor-guided exercises using the provided starter code as part of the exercises. The course will cover the following topics:

이 과정은 일련의 2시간 강의(중간에 휴식 포함)로 제공되며 학생들이 강의의 일부로 제공된 스타터 코드를 사용하여 일련의 강사 안내 연습에서 수업을 적용하는 실습 랩 세션이 이어집니다. 이 과정은 다음 주제를 다룹니다:

- running Node.js applications and creating Node.js modules
  - Node.js 애플리케이션 실행 및 Node.js 모듈 생성
- building web servers in Node.js and Express.js and handling routing
  - Node.js 및 Express.js로 웹 서버 구축 및 라우팅 처리
- connecting to MongoDB to serve data and the Controller, Model, View paradigm
  - MongoDB에 연결하여 데이터 및 Controller, Model, View 패러다임 제공
- handling CRUD (Create, Read, Update, Delete) functions in Node.js
  - Node.js에서 CRUD(만들기, 읽기, 업데이트, 삭제) 기능 처리
- creating user accounts and authenticating users
  - 사용자 계정 생성 및 사용자 인증
- building an API and adding API security
  - API 구축 및 API 보안 추가
- adding chat functionality with Socket.io
  - Socket.io로 채팅 기능 추가
- deploying and managing code in production
  - 프로덕션에서 코드 배포 및 관리

## Lectures, practice, and assignments

- Lectures: Lectures will be held for 2 hours every Friday.
- Practice time: Students will be given the final hour of each lecture period to practice what was covered in the lecture.
- Assignments: Students will be required to turn in assignments in GitHub Classroom ([오전](https://classroom.github.com/classrooms/126310482-2023sp-259122-1-am) | [오후](https://classroom.github.com/classrooms/126310482-2023sp-259122-2-pm)).

See the [Google Classroom](https://classroom.google.com) for class PPTs, lists, and announcements.

### Prerequisites

Students should already be familiar with basic web programming an basic JavaScript. A list of expected knowledge will be made available for review...

### Preparing for the course

You will need NodeJS and a basic code editor or IDE for this course. You will need to download and install [Node.JS](https://nodejs.org/en/download/) and a code editor such as [Visual Studio Code](https://code.visualstudio.com/download) on your computer.

**Detailed instructions can also be found [here](https://ut-nodejs.github.io/instructions) for installing the tools you need and working with the lab materials.**

If you are not already familiar with JavaScript, HTML, or CSS, we strongly encourage you to attempt to become familiar before the start of the course. That way, you will spend much less time become familiar with the tools, and be able to focus more on the methods. The following links provide basic introductions to web programming, which you can study at your own pace before the course begins.

- [_HTML_](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf).
- [CSS](https://www.datacamp.com/courses/free-introduction-to-r).
- [JavaScript](https://www.datacamp.com/courses/reporting-with-r-markdown).
- [How much JavaScript do you need to know to use NodeJS?](https://nodejs.dev/en/learn/how-much-javascript-do-you-need-to-know-to-use-nodejs/).

We also strongly recommend you spend some time before the course working through the following materials related to working with git and GitHub and turning in homework:

- [git]()
- [GitHub]()
- [GitHub Classroom]()

### Important Specifics

#### Computer Software

The software we will be using is listed below.

#### Main Texts

The primary text is:

- James et al. (2021) _An Introduction to Statistical Learning: With applications in R_, Springer. Note: The book is available free online [here](https://www.statlearning.com).

The following is a supplemental text which you may also find useful:

- Lantz, B. (2013). _Machine Learning with R_. Packt Publishing.

### Instructors

**Aaron Snowberger** is a PhD candidate in the Graduate School of Information and Communications Engineering, majoring in Information and Communications Engineering, at Hanbat National University, Korea. He received his B.S degree in Computer Science from the College of Engineering, University of Wyoming, USA in 2006 and his M.FA degree in Media Design from Full Sail University, USA in 2011. From 2010 to present, he is a professor of English Conversation at Jeonju University, Korea. His research interests include computer vision, natural language processing, image processing, signal processing, and machine learning.

### Assessment

#### Daily lab exercises

These are not assessed, but will form the practical materials for each day's labs. See these instructions for how to access and work with each day's exercise.

See [https://lse-me314.github.io/instructions](https://lse-me314.github.io/instructions) for detailed instructions on obtaining and working with each day's lab materials.

#### Mid-term

The class assignment for Day 5 will count as the mid-term assignment, which will count for 25% of the grade. The midterm will be released after the lecture on Day 5 (Monday 18th July) and will be due at 7pm on Day 7 (Wednesday 20th July). <!--- The [mid-term is available here](https://lse-me314.github.io/midterm-2019/).--->

#### Exams

- Midterm exam: April 21 (Week 8) or April 28 (Week 9).
- Final exam: June 16 (Week 16).

<!---[The exam is here](https://lse-me314.github.io/finalexam/).--->

#### Contact

If you have questions, please contact Aaron via Google Classroom.

### Detailed Course Schedule

---

#### 1. Overview and introduction to class

- \*0. Class, Book, Teacher Introduction / 수업, 책, 강사 소개
- \*1. Web Programming Review / 웹 프로그래밍 복습
- \*2. Git and GitHub Classroom Introduction / 깃과 깃허브 클래스룸 소개

We will use this session to get to know the range of interests and experience students bring to the class, as well as to survey the topics to be covered. We will discuss class goals, grading, the textbook, and get to know the instructor. We will also review basic web programming skills, git, GitHub, and GitHub classroom that will be used in the class.

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

- [GitHub Tutorial / 누구나 쉽게 이해할 수 있는 git 입분](https://backlog.com/git-tutorial/kr/)

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
