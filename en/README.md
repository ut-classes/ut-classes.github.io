<p align="center">
  <a href="https://ut-nodejs.github.io">🏠</a> | <a href="/en"><u>[English]</u></a> | <a href="/ko">한국어</a>
</p>

---

# Applied Web Programming 2023

Korea National University of Transportation

![Aaron pic](https://avatars.githubusercontent.com/u/6644259?s=200&v=4)

##### Instructor

- Aaron Snowberger ([aaron@ut.ac.kr](aaron@ut.ac.kr)), Graduate School of Information & Communications Engineering, Hanbat University

##### Online Classroom

| Google Classroom (PPTs) | [오전](https://classroom.google.com/c/NTEyMjUxMTM4MjQz?cjc=m5cbuja) | [오후](https://classroom.google.com/c/NTE2NTcyNjcwNjMz?cjc=sr6x7hg)
| GitHub Classroom (과제) | [오전](https://classroom.github.com/classrooms/126310482-2023sp-259122-1-am) | [오후](https://classroom.github.com/classrooms/126310482-2023sp-259122-2-pm)

This repository contains the course materials for the [Computer Science](https://www.ut.ac.kr/ceit/sub02_00.do) course [Applied Web Programming](https://ut-nodejs.github.io) taught in Spring 2023 by Aaron Snowberger.

### Course Topics

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

Node.js is used to build web servers in Javascript, and there are numerous pre-built packages available through npm. This class follows 8 programming projects listed in the book and requires students to work on a 9th personal project at the end of the class. Topics such as development process, security, database management (Mongoose), user account authentication, and production deployment are covered. You will also learn about debugging asynchronous code, data models, and Javascript modules.

### Objectives

Understand CRUD functions in web servers and websites with Node.js and Express, learn to implement chatting and other interactive functions, and learn English expressions suitable for the international era.

The course will be delivered as a series of 2-hour lectures (with a break in the middle), followed by practice lab sessions where students will apply the lessons in a series of instructor-guided exercises using the provided starter code as part of the exercises. The course will cover the following topics:

- running Node.js applications and creating Node.js modules
- building web servers in Node.js and Express.js and handling routing
- connecting to MongoDB to serve data and the Controller, Model, View paradigm
- handling CRUD (Create, Read, Update, Delete) functions in Node.js
- creating user accounts and authenticating users
- building an API and adding API security
- adding chat functionality with Socket.io
- deploying and managing code in production

## Lectures, practice, and assignments

- Lectures: Lectures will be held for 2 hours every Friday.
- Practice time: Students will be given the final hour of each lecture period to practice what was covered in the lecture.
- Assignments: Students will be required to turn in assignments in GitHub Classroom ([am](https://classroom.github.com/classrooms/126310482-2023sp-259122-1-am) / [pm](https://classroom.github.com/classrooms/126310482-2023sp-259122-2-pm)).

See the Google Classroom [am](https://classroom.google.com/c/NTEyMjUxMTM4MjQz?cjc=m5cbuja) / [pm](https://classroom.google.com/c/NTE2NTcyNjcwNjMz?cjc=sr6x7hg) for class PPTs, lists, and announcements.

### Prerequisites

Students should already be familiar with basic web programming and basic JavaScript. A list of expected knowledge will be made available for review...

### Preparing for the course

You will need NodeJS and a basic code editor or IDE for this course. You will need to download and install [Node.JS](https://nodejs.org/en/download/) and a code editor such as [Visual Studio Code](https://code.visualstudio.com/download) on your computer.

**Detailed instructions can also be found [here](https://ut-nodejs.github.io/instructions) for installing the tools you need and working with the lab materials.**

If you are not already familiar with JavaScript, HTML, or CSS, you are strongly encouraged to attempt to become familiar before the start of the course. That way, you will spend much less time becoming familiar with the tools, and will be able to focus more on the methods. The following links provide basic introductions to web programming, which you can study at your own pace before the course begins.

- [HTML]()
- [CSS]()
- [JavaScript]()
- [How much JavaScript do you need to know to use NodeJS?](https://nodejs.dev/en/learn/how-much-javascript-do-you-need-to-know-to-use-nodejs/)

You are also strongly recommended to spend some time before the course working through the following materials related to working with git and GitHub and turning in homework:

- [git]()
- [GitHub]()
- [GitHub Classroom]()

### Important Specifics

#### Computer Software

The software we will be using is listed below.

- [Node.JS](https://nodejs.org/en/download/)
- [Visual Studio Code](https://code.visualstudio.com/download)
- [git](https://git-scm.com/downloads)

#### Main Texts

The primary text is:

![book-main](/img/gh-pages/book-main.jpg)

- Wexler, Jonathan. (2019, 2020 번역) _Get Programming with Node.js_, Manning Publishing Company (에이콘출판사 번역). [Yes24 link](http://www.yes24.com/Product/Goods/86429845).

The following is a supplemental text which you may also find useful:

![book-extra](/img/gh-pages/book-main.jpg)

- Jo, Hyunyoung. (2022). _Node.js 교과서, 3rd edition_. Gilbert. [Yes24 link](http://www.yes24.com/Product/Goods/116192535)

### Instructor

**Aaron Snowberger** is a PhD candidate in the Graduate School of Information and Communications Engineering, majoring in Information and Communications Engineering, at Hanbat National University, Korea. He received his B.S degree in Computer Science from the College of Engineering, University of Wyoming, USA in 2006 and his M.FA degree in Media Design from Full Sail University, USA in 2011. From 2010 to present, he is a professor of English Conversation at Jeonju University, Korea. His research interests include computer vision, natural language processing, image processing, signal processing, and machine learning.

### Grading

Grading will be broken down into 5 main components:

1. Attendance : 10%
2. Participation : 10%
3. Lab Assignments : 20%
4. Final Project : 40%
5. Tests (Midterm / Final) : 20%

The university grades on a curve. The following is a simple guideline for understanding how the final project will be graded.

- 상대평가
  - _A: Customize (Content + Design)_
  - **B: Complete (just what's in the book)**
  - C: Incomplete or broken
  - D: Very minimal effort
  - F: Absences

#### 1. Attendance (10%)

The university's guidelines on attendance are as follows:

- 3 Late = 1 Absence
- More than 20% Absences = F

If a student has a valid excuse to be absent, such as quarantining for COVID-19, a school event, etc, they may be given self-study work to complete.

#### 2. Participation (10%)

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

#### 3. Daily Lab Exercises (20%)

These are graded on a {Complete, Half-complete, Incomplete} scale and will form the practical materials for each day's labs. See these instructions for how to access and work with each day's exercise.

See [https://ut-nodejs.github.io/instructions](https://ut-nodejs.github.io/instructions) for detailed instructions on obtaining and working with each day's lab materials.

#### 4. Final Project (40%)

The Final Project should be an updated customization of the project we work on in class. It should do at least TWO things differently from the project described in the book:

1. Solve a different problem (i.e. not a Cooking / Recipe site)
2. Have a different design / style

Ways to make your project stand out:

- Use a CSS framework
- Include multiple page templates
- Implement your own, self-selected JavaScript functionality, widget, feature, etc.

#### Midterm Exam (10%)

It is possible that the CRUD or User Data Model assignments will be used for the Midterm. The midterm will be released after the lecture on Day 7 (4월14일) and will be due at 11:59pm on Day 9 (4월28일). <!--- The [midterm is available here](https://ut-nodejs.github.io/midterm-2023/).--->

#### Final Exam (10%)

It is possible that your Final project may be used for the Final Exam. But, there may be a quiz or test of some kind included. The final will be released after the lecture on Day 15 (6월9일) and will be due at 11:59pm on the Monday after Day 16 (6월19일). <!--- The [final is available here](https://ut-nodejs.github.io/final-2023/).--->

#### Exam Schedule

- Midterm exam: April 21 (Week 8) or April 28 (Week 9).
- Final exam: June 16 (Week 16).
- Final project due: June 19 (Monday).

<!---[Instructions for the final project are here](https://ut-nodejs.github.io/final-project/).--->

#### Contact

If you have questions, please contact Aaron at [aaron@ut.ac.kr](aaron@ut.ac.kr).

### Detailed Course Schedule

---

#### 1. Overview and introduction to class

- \*0. Class, Book, Teacher Introduction
- \*1. Web Programming Review
- \*2. Git and GitHub Classroom Introduction

We will use this session to get to know the range of interests and experience students bring to the class, as well as to survey the topics to be covered. We will discuss class goals, grading, the textbook, and get to know the instructor. We will also review basic web programming skills, git, GitHub, and GitHub classroom that will be used in the class.

##### Resources

- [Google Classroom](https://classroom.google.com)
- [GitHub Classroom](https://classroom.github.com)
- [PPT \*0. Class, Book, Teacher Introduction](lecturenotes/)
- [PPT \*1. Web Programming Review](lecturenotes/)
- [PPT \*2. Git and GitHub Classroom Introduction](lecturenotes/)
- [Lab 0 materials](https://lse-me314.github.io/assignment01/)

##### Practice & Assignment

<!---- - Lab 1 [start](/1-start) | [finish](/1-finish). ---->

##### Required reading

- [GitHub Tutorial (KO)](https://backlog.com/git-tutorial/kr/)

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

<!---- - Lab 2 [start](/2-start) | [finish](/2-finish). ---->

##### Required reading

-

##### Recommended reading

-

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

<!---- - Lab 3 [start](/3-start) | [finish](/3-finish). ---->

##### Required reading

-

##### Recommended Reading

-

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

<!---- - Lab 4 [start](/4-start) | [finish](/4-finish). ---->

##### Required Reading

-

##### Recommended Reading

-

#### 5. Project Start

- Lesson 10 뷰와 템플릿의 연결 / Connecting views with templates
- Lesson 11. 설정과 에러 처리 / Configurations and error handling
- Lesson 12. 캡스톤 프로젝트: Express.js를 통한 Confetti Cuisine 사이트 개선 / Capstone: Enhancing the Confetti Cuisine site with Express.js

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day5.pdf)
- [Lab 5 materials](https://lse-me314.github.io/assignment05/)

##### Practice & Assignment

<!---- - Lab 5 [start](/5-start) | [finish](/5-finish). ---->

##### Required Reading

-

##### Recommended Reading

-

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

<!---- - Lab 6 [start](/6-start) | [finish](/6-finish). ---->

##### Required Reading

-

##### Recommended Reading

-

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

<!---- - Lab 7 [start](/7-start) | [finish](/7-finish). ---->

##### Required Reading

-

##### Recommended Reading

-

#### Midterm Exam

- 중간고사 / 프로젝트

For review...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day9.pdf)
- [Midterm](https://lse-me314.github.io/assignment09/)

##### Practice & Assignment

<!---- - Midterm [start](/midterm-2023). ---->

##### Required reading

-

##### Recommended Reading

-

#### 8. CRUD (Create, Read, Update, Delete)

- Lesson 20. 모델의 업데이트와 삭제 / Updating and deleting your models
- Lesson 21. 캡스톤 프로젝트: Confetti Cusine에 CRUD 모델 추가 / Capstone: Adding CRUD models to Confetti Cuisine

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day8.pdf)
- [Lab 8 materials](https://lse-me314.github.io/assignment08/)

##### Practice & Assignment

<!---- - Lab 8 [start](/8-start) | [finish](/8-finish). ---->

##### Required reading

-

##### Recommended Reading

-

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

<!---- - Lab 9 [start](/9-start) | [finish](/9-finish). ---->

##### Required reading

-

##### Recommended Reading

-

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

<!---- - Lab 10 [start](/10-start) | [finish](/10-finish). ---->

##### Required reading

-

##### Recommended Reading

-

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

<!---- - Lab 11 [start](/11-start) | [finish](/11-finish). ---->

##### Required reading:

-

##### Recommended reading:

-

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

<!---- - Lab 12 [start](/12-start) | [finish](/12-finish). ---->

##### Required Reading:

-

##### Recommended Reading:

-

#### 13. Supplementary Topics

- Appendix A. ES6에서 소개하는 JavaScript 문법 / JavaScript syntax introduced in ES6
- Appendix B. 로깅과 Node.js의 전역 객체의 사용 / Logging and using Node.js global objects
- 개인 프로젝트 안내와 선택 / Personal projects information and selection

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day13.pdf)
- [Lab 13 materials](https://lse-me314.github.io/assignment13/)

##### Practice & Assignment

<!---- - Lab 13 [start](/13-start) | [finish](/13-finish). ---->

##### Required Reading:

-

##### Recommended Reading:

-

#### 14. Personal Projects

- 개인 프로젝트 / Personal projects

This week...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day14.pdf)
- [Lab 14 materials](https://lse-me314.github.io/assignment14/)

##### Practice & Assignment

<!---- - Lab 14 [start](/14-start) | [finish](/14-finish). ---->

##### Required Reading:

-

##### Recommended Reading:

-

#### Final Exam

- 기말고사 / 프로젝트

For review...

##### Resources

- [Lecture Notes](lecturenotes/ME314_day16.pdf)
- [Lab 16 materials](https://lse-me314.github.io/assignment16/)

##### Practice & Assignment

<!---- - [Final exam](/final-2023). ---->

##### Required Reading:

-

##### Recommended Reading:

-
