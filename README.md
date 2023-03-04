<p id="menu" align="center">
  <a href="https://ut-nodejs.github.io" title="Home">🏠</a> |
  <a href="about.html" title="About">소개</a> |
  <a href="/schedule.html" title="Schedule">일정</a> |
  <a href="/slides" title="Slides">스라이드</a> |
  <a href="/practice" title="Practice">과제</a> |
  <a href="/project.html" title="Project">프로젝트</a> |
  <a href="/tests.html" title="Tests">고사</a> |
  <a href="/grading.html" title="Grading">성적</a>
</p>

---

# Web Programming Application 2023

<p>한국교통대학교, 충주<small> | KNUT (Korea National University of Transportation)</small></p>

---

This repository contains the course materials for the [Computer Science](https://www.ut.ac.kr/ceit/sub02_00.do) course [Web Programming Application](https://ut-nodejs.github.io) taught in Spring 2023 by Aaron Snowberger. 이 저장소는 [컴퓨터과학](https://www.ut.ac.kr/ceit/sub02_00.do) 과정 [웹프로그래밍응용](https://ut-nodejs.github.io)은 에런 스노버거가 2023년 봄에 가르쳤다.

![Aaron pic](https://avatars.githubusercontent.com/u/6644259?s=200&v=4)

### Instructor / 강사

- Aaron Snowberger ([aaron@g.ut.ac.kr](aaron@g.ut.ac.kr)), Graduate School of Information & Communications Engineering, Hanbat University
- 에런 스노버거, 정보통신공학과, 한밭대학교

---

### Online Classroom / 온라인 클래스룸

| Google Classroom (PPTs) | [오전](https://classroom.google.com/c/NTEyMjUxMTM4MjQz?cjc=m5cbuja) | [오후](https://classroom.google.com/c/NTE2NTcyNjcwNjMz?cjc=sr6x7hg)
| GitHub Classroom (과제) | [오전](https://classroom.github.com/classrooms/126310482-2023sp-259122-1-am) | [오후](https://classroom.github.com/classrooms/126310482-2023sp-259122-2-pm)

##### Google Classroom / 구글 클래스룸

- Which system? 에떤 시스템? [@gmail.com](https://classroom.google.com) | [@a.ut.ac.kr](https://classroom.google.com)

##### GitHub Classroom / 깃허브 클래스룸

1. (학생) 구글 클래스룸 신청 / Join Google Classroom
2. (교사) 링크 구글 클래스룸 출석부 / Link Google Classroom roster
3. (교사) 과제1 보내 / Distribute Assignment #1 with link
4. (교사) 과제1 받은 학생의 계정이 깃허브 클래스룸과 링크 / Link accepted assignments with GitHub accounts possessing that assignment
5. (같이) 코딩 합습 / Code in VS Code
6. (학생) 제출하면 깃 커밋과 푸시 / Commit & Push to Turn in

---

### Important Specifics / 중요한 세부 사항

##### Computer Software / 소프트웨어

The software we will be using is listed below. 수업에서 사용할 소프트웨어가 다음과 같다.

- [Node.JS](https://nodejs.org/en/download/)
- [Visual Studio Code](https://code.visualstudio.com/download)
- [git](https://git-scm.com/downloads)

##### Main Texts / 주제책

| Textbook                                                                                                                                                                   | Supplementary book                                                                                                     |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| ![book-main](/img/gh-pages/book-main.jpg)                                                                                                                                  | ![book-extra](/img/gh-pages/book-extra.jpg)                                                                            |
| Wexler, Jonathan. (2019, 2020 번역) [_Get Programming with Node.js_ (Yes24)](http://www.yes24.com/Product/Goods/86429845), Manning Publishing Company (에이콘출판사 번역). | Jo, Hyunyoung. (2022). [_Node.js 교과서, 3rd edition_ (Yes24)](http://www.yes24.com/Product/Goods/116192535). Gilbert. |

<!-- The primary text is (주제책은):

![book-main](/img/gh-pages/book-main.jpg)

- Wexler, Jonathan. (2019, 2020 번역) [_Get Programming with Node.js_ (Yes24)](http://www.yes24.com/Product/Goods/86429845), Manning Publishing Company (에이콘출판사 번역).

The following is a supplemental text which you may also find useful (첨고책은):

![book-extra](/img/gh-pages/book-extra.jpg)

- Jo, Hyunyoung. (2022). [_Node.js 교과서, 3rd edition_ (Yes24)](http://www.yes24.com/Product/Goods/116192535). Gilbert. -->

---

### Course Topics / 과정 화제

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

### About Aaron / 교사 소개

**Aaron Snowberger** is a PhD candidate in the Graduate School of Information and Communications Engineering, majoring in Information and Communications Engineering, at Hanbat National University, Korea. He received his B.S degree in Computer Science from the College of Engineering, University of Wyoming, USA in 2006 and his M.FA degree in Media Design from Full Sail University, USA in 2011. From 2010 to present, he is a professor of English Conversation at Jeonju University, Korea. His research interests include computer vision, natural language processing, image processing, signal processing, and machine learning.
