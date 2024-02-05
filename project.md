<p id="menu" align="center">
  <a href="https://ut-nodejs.github.io" title="Home">🏠</a> |
  <a href="about.html" title="About">개요</a> |
  <a href="/schedule.html" title="Schedule">일정</a> |
  <a href="/slides.html" title="Slides">스라이드</a> |
  <a href="/assignments.html" title="Assignments">과제</a> |
  <a href="/project.html" title="Project"><u>[프로젝트]</u></a> |
  <a href="/tests.html" title="Tests">시험</a> |
  <a href="/grading.html" title="Grading">성적</a> |
  <a href="/resources.html" title="Resources">자료</a>
  <!-- <a href="https://pollev.com/aarons007" title="PollEverywhere">설문↗️</a> -->
</p>

---

# Web Programming Application 2023

<p>한국교통대학교, 충주<small> | KNUT (Korea National University of Transportation)</small></p>

---

## Final Project / 최종 프로젝트

`마감일: 6월19일: 9:00am`

Your final project will be to create a full web application with the following features. 당신의 최종 프로젝트는 다음과 같은 기능을 가진 전체 웹 애플리케이션을 만드는 것이다.

Starter code will be provided from [Lesson 21 (Capstone 4: CRUD Operations)](/slides/4.21-crud-capstone.pdf). Your final project should be based on this code. Lesson 21 (캡스톤 4: CRUD 운영)에서 스타터 코드가 제공될 것이다. 당신의 최종 프로젝트는 이 코드를 기반으로 해야 한다.

You should also implement User Authentication from [Lesson 25 (Capstone 5: User Authentication)](/slides/5.25-user-auth-capstone.pdf). Lesson 25 (캡스톤 5: 사용자 인증)에서 사용자 인증을 구현해야 한다.

- [☕ am 파일 받기](https://classroom.github.com/a/6WBLNv7l)
- [🍔 pm 파일 받기](https://classroom.github.com/a/tRhkgu_r)

### Helpful Files / 도움이 되는 파일

- [Final Project Starter Code](https://github.com/ut-nodejs/final-project-starter-files)
- PPT: [Capstone 4. CRUD Operations / CRUD 운영](/slides/4.21-crud-capstone.pdf)
- PPT: [Capstone 5. User Authentication / 사용자 인증](/slides/5.25-user-auth-capstone.pdf)

---

## 1. Required Features / 필수 기능

1. **NEW MVC Model / 새로운 MVC 모델** (Unit 4)
   1. `User` / 사용자 (already provided / 이미 제공됨)
   2. `Subscriber` / 구독자 (already provided / 이미 제공됨)
   3. `Course` / 강좌 (already provided / 이미 제공됨)
   4. **`(Your Choice)` / (당신의 선택)**
      - `Book` / 책
      - `Movie` / 영화
      - `Music` / 음악
      - `Restaurant` / 식당
      - `Product` / 제품
      - `Recipe` / 레시피
      - `Game` / 게임
      - `Sports Team` / 스포츠 팀
      - `TV Show` / TV 프로그램
      - `Other` / 기타
1. **User Authentication / 사용자 인증** (Unit 5)
   1. Users should be able to register and login to your site
   2. 사용자는 사이트에 등록하고 로그인할 수 있어야 한다

---

## 2. Required Files / 필수 파일

For your _new MVC model_, you should include the following files. *새로운 MVC 모델*에 대해 다음과 같은 파일이 있어야 한다.

1. **Model / 모델**
   1. `models/Model.js`
2. **Controller / 컨트롤러**
   1. `controllers/Controller.js`
3. **Views / 뷰**
   1. `views/Model/`
      1. `index.ejs`
      2. `new.ejs`
      3. `show.ejs`
      4. `edit.ejs`
4. <del>**Data / 데이터**
   1. `data/seedModel.js`</del> (optional / 선택 기능)

For each of these files, you may **copy and edit** the existing files from the starter code. 이러한 파일 각각에 대해, 당신은 스타터 코드에서 기존 파일을 **복사하고 편집할 수 있다**.

For example: 예를 들어:

- `models/Course.js` -> **`models/Book.js`**
- `views/Course/` -> **`views/Book/`**
  - `views/Course/index.ejs` -> **`views/Book/index.ejs`**
  - `views/Course/new.ejs` -> **`views/Book/new.ejs`**
  - `views/Course/show.ejs` -> **`views/Book/show.ejs`**
  - `views/Course/edit.ejs` -> **`views/Book/edit.ejs`**
- `controllers/coursesController.js` -> **`controllers/bookController.js`**

Also, feel free to **redesign** the pages as you wish with additional CSS or Bootstrap code. 또한, 추가 CSS 또는 Bootstrap 코드로 원하는 대로 페이지를 **재설계할 수 있다**.

Finally, **be sure to change the text and images** to match your site. 마지막으로, **당신의 사이트와 일치하도록 텍스트와 이미지를 변경**하라.

---

## 3. Optional Features / 선택 기능

1. **RESTful API** (Unit 6)
   1. Create a RESTful API for your site
   2. 사이트에 RESTful API를 만든다
2. **Socket.io** (Unit 7)
   1. Use [Socket.io](https://socket.io/) to implement real-time communication
   2. [Socket.io](https://socket.io/)를 사용하여 실시간 통신을 구현한다
3. **Bootstrap** (Unit 1-2)
   1. Use [Bootstrap](https://getbootstrap.kr) to build your web client
   2. [Bootstrap](https://getbootstrap.kr)을 사용하여 웹 클라이언트를 구축한다

---

## 4. Checklist / 체크리스트

- [ ] **1. NEW MVC Model / 새로운 MVC 모델** (Unit 4)
  - [ ] Model / 모델
    - [ ] `models/Model.js`
  - [ ] Controller / 컨트롤러
    - [ ] `controllers/Controller.js`
  - [ ] Views / 뷰
    - [ ] `views/Model/`
      - [ ] `index.ejs`
      - [ ] `new.ejs`
      - [ ] `show.ejs`
      - [ ] `edit.ejs`
- [ ] **2. User Authentication / 사용자 인증** (Unit 5)
  - [ ] Flash Messaging / 플래시 메시지
    - [ ] `views/partials/flash.ejs`
  - [ ] Login / 로그인
    - [ ] `views/users/login.ejs`
  - [ ] Login links
    - [ ] `views/partials/header.ejs`
- [ ] **3. Images and/or Design update / 이미지 및/또는 디자인 업데이트**
  - [ ] `public/css/style.css` (Homepage image / 홈페이지 이미지)
  - [ ] `views/_pages/about.ejs` (Update content / 내용 업데이트)
  - [ ] `views/_partials/navigation.ejs` (Update nav links / 네비게이션 링크 업데이트)
  - [ ] `views/_partials/footer.ejs` (Update footer / 푸터 업데이트)
  - [ ] Other necessary updates / 기타 필요한 업데이트
  - [ ] Seed data / 시드 데이터
    - [ ] `data/seedModel.js` (optional / 선택 기능)

---

## 5. Grading / 성적

The total points will be out of **100**. The final project counts for **30%** of your final grade. / 총 점수는 **100점** 만점이다. 최종 프로젝트는 최종 성적의 **30%** 를 차지한다.

| Description                                  | 설명                                      | Points / 점수                             |
| -------------------------------------------- | ----------------------------------------- | ----------------------------------------- |
| Starter files not modified                   | 스타터 파일이 수정되지 않음               | `50`                                      |
| Doesn't run (big fixes required)             | 실행되지 않음 (큰 수정이 필요함)          | `-10`                                     |
| Doesn't run (small fixes required)           | 실행되지 않음 (작은 수정이 필요함)        | `-5`                                      |
| No `create` action (or broken)               | 생성 작업이 없음 (또는 작동하지 않음)     | `-5`                                      |
| No `read` action (or broken)                 | 읽기 작업이 없음 (또는 작동하지 않음)     | `-5`                                      |
| No `update` action (or broken)               | 업데이트 작업이 없음 (또는 작동하지 않음) | `-5`                                      |
| No `delete` action (or broken)               | 삭제 작업이 없음 (또는 작동하지 않음)     | `-5`                                      |
| No User Authentication                       | 사용자 인증이 없음                        | `-5`                                      |
| Redirect or DB error (404, 500)              | 리디렉션 또는 DB 오류 (404, 500)          | `-5`                                      |
| No images changed                            | 이미지가 변경되지 않음                    | `-5`                                      |
| Navigation links not changed or error        | 네비게이션 링크가 변경되지 않음 또는 오류 | `-5`                                      |
| Footer not changed                           | 푸터가 변경되지 않음                      | `-2`                                      |
| No new Controller file                       | 새로운 컨트롤러 파일이 없음               | `-5`                                      |
| No new Model file                            | 새로운 모델 파일이 없음                   | `-5`                                      |
| No new View files                            | 새로운 뷰 파일이 없음                     | `-5`                                      |
| User creation or Login error                 | 사용자 생성 또는 로그인 오류              | `-5`                                      |
| Login links missing                          | 로그인 링크가 없음                        | `-5`                                      |
| Incorrect packages installed (not installed) | 잘못된 패키지가 설치됨 (설치되지 않음)    | `-10`                                     |
| Design problems or other errors              | 디자인 문제 또는 다른 오류                | `-1` (point-by-point basis / 점수별 기준) |
| Late submission                              | 지각 제출                                 | `-5`                                      |

---

## Resource Links / 자료 링크

The following topics were covered in class and you will be required to implement them in your project. 다음은 수업에서 다루어지며 당신은 당신의 프로젝트에서 구현해야 한다.

- **웹 서버와 크라이언트 (Unit 1-2)**
  1. [Node.js](https://nodejs.org/ko)와 [Express](https://expressjs.com/ko/)를 사용하여 웹 서버를 구축하고
  2. [HTML, CSS, JavaScript](https://heropy.blog/2019/04/24/html-css-starter/)를 사용하여 웹 클라이언트를 구축한다
- **데이터베이스와 데이터베이스 모델 (Unit 3-4)**
  1. [MongoDB](https://www.mongodb.com/)를 사용하여 데이터베이스를 구축하고
  2. 데이터베이스 모델은 [Mongoose](https://mongoosejs.com/)를 사용하여 구축한다
- **사용자 인증 (Unit 5)**
  1. [Passport](https://www.passportjs.org/)를 사용하여 사용자 인증을 구현한다

### 선택 과목

If you want to _make your project stand out_, you can self-study and implement one or more of the following features. 당신이 _당신의 프로젝트를 더 두드러지게 하고 싶다면_, 당신은 자체 학습을 하고 하나 이상의 다음 기능을 구현할 수 있다.

- **RESTful API (Unit 6)**
  1. RESTful API를 구현한다
- **Socket.io (Unit 7)**
  1. [Socket.io](https://socket.io/)를 사용하여 실시간 통신을 구현한다
- [Bootstrap](https://getbootstrap.kr)을 사용하여 웹 클라이언트를 구축한다
