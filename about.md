<p id="menu" align="center">
  <a href="https://ut-nodejs.github.io" title="Home">🏠</a> |
  <a href="about.html" title="About"><u>[개요]</u></a> |
  <a href="/schedule.html" title="Schedule">일정</a> |
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

## Overview / 수업 개요

Node.js is used to build web servers in Javascript, and there are numerous pre-built packages available through [npm](https://www.npmjs.com/). Node.js는 Javascript로 웹 서버를 만들 수 있으며, [npm](https://www.npmjs.com/)을 통해 다양한 미리 만들어진 패키지를 사용할 수 있습니다.

This class follows <del>8</del> **5** programming projects listed in the book and requires students to work on a _[final project](/project.html)_ at the end of the class. 이 수업은 책에 나열된 <del>8</del> **5**개의 프로그래밍 프로젝트를 따르며, 수업이 끝난 후 *[최종 프로젝트](/project.html)*를 수행하도록 합니다.

Topics such as the web development process, security, database management (Mongoose), and user account authentication are covered. You will also learn about debugging asynchronous code, data models, and Javascript modules. 주제로는 웹 개발 프로세스, 보안, 데이터베이스 관리 (Mongoose), 사용자 계정 인증 등이 포함됩니다. 비동기 코드 디버깅, 데이터 모델 및 Javascript 모듈에 대해서도 배우게 됩니다.

## Objectives / 수업 목표

Students will learn about CRUD functions in web servers and websites with Node.js and Express, learn to implement <delchatting</del> and other interactive functions, and learn English expressions suitable for the international era. 학생들은 Node.js 및 Express를 사용하여 웹 서버 및 웹 사이트에서 CRUD 기능을 배우고, <del>채팅</del> 및 기타 상호 작용 기능을 구현하는 방법을 배우고, 국제 시대에 적합한 영어 표현을 배우게 됩니다.

The course will be delivered as a series of 2-hour lectures (with a break in the middle), followed by [Practice Lab](/assignments.html) sessions where students will apply the lessons in a series of instructor-guided exercises using the provided starter code as part of the exercises. 이 수업은 2시간 간격의 강의 (중간에 휴식)로 제공되며, 제공된 스타터 코드를 사용하여 강사가 지도하는 연습 문제를 통해 학생들이 수업을 적용할 수 있도록 [실습실](/assignments.html) 세션을 제공합니다.

The course will cover the following topics. 이 수업은 다음과 같은 주제를 다룹니다.

- Running [Node.js](https://nodejs.org/ko) applications and creating Node.js modules
  - Node.js 애플리케이션 실행 및 Node.js 모듈 생성
- Building web servers in Node.js and [Express.js](https://expressjs.com/ko/) and handling routing
  - Node.js 및 Express.js에서 웹 서버 구축 및 라우팅 처리
- Connecting to [MongoDB](https://www.mongodb.com/) to serve data and the Model, View, Controller paradigm
  - 데이터를 제공하고 MVC 패러다임에 연결하는 MongoDB
- Handling CRUD (Create, Read, Update, Delete) functions with [Mongoose](https://mongoosejs.com/) schemas
  - Mongoose 스키마를 사용하여 CRUD (생성, 읽기, 수정, 삭제) 기능 처리
- Creating user accounts and authenticating users with [Passport.js](https://www.passportjs.org/)
  - 사용자 계정 생성 및 사용자 인증
- <del>Building an API and adding API security</del>
- <del>Adding chat functionality with Socket.io</del>
- <del>Deploying and managing code in production</del>

## Course Structure / 수업 구조

- **Lectures:** Lectures will be held for 2 hours every Friday. 강의는 매주 금요일에 2시간 동안 진행됩니다.
- **Practice Time:** Students will be given the final hour of each lecture period to practice what was covered in the lecture. 강의 시간의 마지막 1시간 동안 학생들은 강의에서 다룬 내용을 실습할 수 있습니다.
- **Assignments:** Students will be required to turn in assignments in [GitHub Classroom](https://github.com/ut-nodejs) 학생들은 GitHub Classroom에서 과제를 제출해야 합니다.
- **Homework:** Whatever is not finished in the Practice Time will be assigned as homework. _The [assignments](/assignments.html) will be due the following Friday._ 실습 시간에 완료되지 않은 것은 숙제로 지정됩니다. _과제는 다음 금요일까지 제출되어야 합니다._

### Preparing for the course / 수업 준비

You will need [Node.JS](https://nodejs.org/en/download/) and a basic code editor or IDE such as [Visual Studio Code](https://code.visualstudio.com/download) for this course. You will also need to install [git](https://git-scm.com/downloads) in order to access the Assignments on GitHub Classroom. 이 수업에는 [Node.JS](https://nodejs.org/en/download/)와 [Visual Studio Code](https://code.visualstudio.com/download)와 같은 기본 코드 편집기 또는 IDE가 필요합니다. 또한 GitHub Classroom에서 과제에 액세스하려면 [git](https://git-scm.com/downloads)을 설치해야 합니다.

**Detailed instructions can be found [here](https://ut-nodejs.github.io/instructions) for accessing and submitting Assignments in GitHub Classroom.** **GitHub Classroom에서 과제에 액세스하고 제출하는 방법에 대한 자세한 지침은 [여기](https://ut-nodejs.github.io/instructions)에서 확인할 수 있습니다.**

If you are not already familiar with JavaScript, HTML, or CSS, you are **STRONGLY ENCOURAGED** to attempt to become familiar before the start of the course. That way, you will spend much less time becoming familiar with the tools, and will be able to focus more on the methods. 만약 JavaScript, HTML 또는 CSS에 이미 익숙하지 않다면, 수업 시작 전에 익숙해지려고 노력하는 것이 좋습니다. 그러면 툴에 익숙해지는 데 시간을 훨씬 적게 소비하고, 더 많은 시간을 메서드에 집중할 수 있습니다.

The following links provide basic introductions to web programming, which you can study at your own pace before the course begins. 다음 링크는 웹 프로그래밍에 대한 기본 소개를 제공하며, 수업이 시작되기 전에 스스로의 속도에 맞게 공부할 수 있습니다.

- [HTML, CSS, JavaScript 튜토리얼](https://heropy.blog/2019/04/24/html-css-starter/)
- [HTML 모질라](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [CSS 모질라](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
- [JavaScript 모질라](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [How much JavaScript do you need to know to use NodeJS?](https://nodejs.dev/en/learn/how-much-javascript-do-you-need-to-know-to-use-nodejs/)

You are also strongly recommended to spend some time before the course working through the following materials related to working with git and GitHub and turning in homework. If you do not already have a [GitHub](https://github.com) account, you will be asked to create one. 수업 시작 전에 git 및 GitHub과 관련된 다음 자료를 통해 작업하는 데 시간을 할애하는 것이 좋습니다. 이미 GitHub 계정이 없는 경우 새로 만들도록 요청됩니다.

- [git - 간편 안내서](https://up1.github.io/git-guide/index.ko.html)
- [누구나 쉽게 이해할 수 있는 git 입문](https://backlog.com/git-tutorial/kr/)

### Important Specifics / 중요한 사항

#### Computer Software / 컴퓨터 소프트웨어

The software we will be using is listed below. 필요한 소프트웨어는 아래와 같습니다.

- [Node.JS](https://nodejs.org/en/download/)
- [Visual Studio Code](https://code.visualstudio.com/download)
- [git](https://git-scm.com/downloads)

### Main Texts / 주제책

| Textbook                                                                              | Supplementary book                                                                    |
| :------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------ |
| ![book-main](/img/gh-pages/book-main.jpg)                                             | ![book-extra](/img/gh-pages/book-extra.jpg)                                           |
| Wexler, Jonathan. (2019, 2020 번역)                                                   | Jo, Hyunyoung. (2022)                                                                 |
| [_Get Programming with Node.js_ (Yes24)](http://www.yes24.com/Product/Goods/86429845) | [_Node.js 교과서, 3rd edition_ (Yes24)](http://www.yes24.com/Product/Goods/116192535) |
| Manning Publishing Company (에이콘출판사 번역).                                       | Gilbert                                                                               |

### Instructor / 교수

**Aaron Snowberger** is a PhD candidate majoring in Information and Communications Engineering at Hanbat National University in Korea. He also holds degrees in Computer Science and Media Design. He has taught high school technology courses for over 6 years, and has built dozens of web applications with Node and Express. His current research interests include computer vision, natural language processing, image processing, signal processing, and machine learning.

Aaron Snowberger는 한밭대학교 정보통신공학과 박사과정 수료했으며, 컴퓨터 공학 및 미디어 디자인 학위를 보유하고 있습니다. 그는 6년 이상의 고등학교 기술 교육 과정을 가르치고 있으며, Node 및 Express를 사용하여 수십 개의 웹 애플리케이션을 구축했습니다. 현재 연구 관심사는 컴퓨터 비전, 자연어 처리, 영상 처리, 신호 처리 및 기계 학습입니다.

#### Contact / 연락처

If you have questions, please contact Aaron at [aaron@ut.ac.kr](aaron@ut.ac.kr) (Webmail) or [aaron@g.ut.ac.kr](aaron@g.ut.ac.kr) (Google Mail). 질문이 있으면 Aaron 교수에게 이메일을 보내주세요.
