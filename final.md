<p id="menu" align="center">
  <a href="https://ut-nodejs.github.io" title="Home">🏠</a> |
  <a href="about.html" title="About">개요</a> |
  <a href="/schedule.html" title="Schedule">일정</a> |
  <a href="/slides.html" title="Slides">스라이드</a> |
  <a href="/assignments.html" title="Assignments">과제</a> |
  <a href="/project.html" title="Project">프로젝트</a> |
  <a href="/tests.html" title="Tests"><u>[시험]</u></a> |
  <a href="/grading.html" title="Grading">성적</a> |
  <a href="/resources.html" title="Resources">자료</a>
  <!-- <a href="https://pollev.com/aarons007" title="PollEverywhere">설문↗️</a> -->
</p>

---

# Web Programming Application 2023

<p>한국교통대학교, 충주<small> | KNUT (Korea National University of Transportation)</small></p>

---

## Final Test / 기말고사

Schedule: **6월 16일 일정**

### Study Guide / 공부 가이드

- **MongoDB**로 데이터베이스 만들기
- **Mongoose**로 데이터베이스 모델 만들기
- **Passport**로 사용자 인증 구현하기

- [3. MongoDB & Mongoose Introduction](#unit-3-mongodb--mongoose-introduction)
  - [Basic MongoDB Shell Commands](#basic-mongodb-shell-commands)
  - [Mongoose](#mongoose)
    - [Basic Mongoose Commands](#basic-mongoose-commands)
    - [Mongoose Schema](#mongoose-schema)
    - [Mongoose Schema Types](#mongoose-schema-types)
    - [Mongoose Schema Options](#mongoose-schema-options)
    - [Data Relationships](#data-relationships)
    - [JavaScript Promises](#javascript-promises)
- [4. CRUD Operations with Mongoose](#unit-4-crud-operations-with-mongoose)
  - [Create](#create)
    - [Create Controller Actions](#create-controller-actions)
  - [Read](#read)
    - [Read Controller Actions](#read-controller-actions)
  - [Update](#update)
    - [Update Controller Actions](#update-controller-actions)
  - [Delete](#delete)
    - [Delete Controller Actions](#delete-controller-actions)
- [5. User Authentication with Passport](#unit-5-user-authentication-with-passport)
  - [Flash Messages with Connect-Flash](#flash-messages-with-connect-flash)
  - [Password Hashing with Bcrypt](#password-hashing-with-bcrypt)
  - [Passport](#passport)
    - [Passport Configuration](#passport-configuration)
    - [Passport Local Strategy](#passport-local-strategy)
    - [Local Variables](#local-variables)
    - [Passport Local Authentication](#passport-local-authentication)
- [Important Packages](#important-packages)

# Unit 3: MongoDB & Mongoose Introduction

MongoDB is a NoSQL, non-relational, database that stores data in BSON (binary JSON) documents.<br>
몽고디비는 NoSQL, 비관계형 데이터베이스로 데이터를 BSON (바이너리 JSON) 문서에 저장합니다.

## Basic MongoDB Shell commands

- `show dbs` = show databases / 데이터베이스 목록 보기
- `use <db>` = use database / 데이터베이스 선택하기
- `show collections` = show collections / 컬렉션 목록 보기
- `db.<collection>.findOne()` = find one document / 한 개의 문서 찾기
- `db.<collection>.find()` = find all documents / 모든 문서 찾기
- `db.<collection>.insertOne()` = insert one document / 한 개의 문서 삽입하기
- `db.<collection>.insertMany()` = insert many documents / 여러 개의 문서 삽입하기
- `db.<collection>.updateOne()` = update one document / 한 개의 문서 수정하기
- `db.<collection>.updateMany()` = update many documents / 여러 개의 문서 수정하기
- `db.<collection>.deleteOne()` = delete one document / 한 개의 문서 삭제하기
- `db.<collection>.deleteMany()` = delete many documents / 여러 개의 문서 삭제하기
- `db.<collection>.drop()` = drop collection / 컬렉션 삭제하기

## Mongoose

Mongoose is an object-document modeling, or object-document mapper, (ODM) library for MongoDB that allows you to run MongoDB commands in a way that preserves the object-oriented structure of your application.<br>
몽구스는 몽고디비의 객체-문서 모델링, 또는 객체-문서 매퍼 (ODM) 라이브러리로, 애플리케이션의 객체 지향 구조를 보존하는 방식으로 몽고디비 명령을 실행할 수 있습니다.

### Basic Mongoose commands

- `mongoose.connect()` = connect to MongoDB / 몽고디비에 연결하기
- `mongoose.connection` = connection object / 연결 객체
- `mongoose.connection.on()` = listen for events / 이벤트 수신하기
- `mongoose.connection.once()` = listen for one event / 한 번의 이벤트 수신하기
- `mongoose.connection.close()` = close connection / 연결 종료하기
- `mongoose.model()` = create model / 모델 생성하기
- `mongoose.model().find()` = find documents / 문서 찾기
- `mongoose.model().findOne()` = find one document / 한 개의 문서 찾기
- `mongoose.model().findById()` = find document by ID / ID로 문서 찾기
- `mongoose.model().create()` = create document / 문서 생성하기
- `mongoose.model().insertMany()` = create many documents / 여러 개의 문서 생성하기
- `mongoose.model().updateOne()` = update one document / 한 개의 문서 수정하기
- `mongoose.model().updateMany()` = update many documents / 여러 개의 문서 수정하기
- `mongoose.model().findByIdAndUpdate()` = find document by ID and update / ID로 문서 찾아서 수정하기
- `mongoose.model().deleteOne()` = delete one document / 한 개의 문서 삭제하기
- `mongoose.model().deleteMany()` = delete many documents / 여러 개의 문서 삭제하기
- `mongoose.model().findByIdAndDelete()` = find document by ID and delete / ID로 문서 찾아서 삭제하기
- `mongoose.model().findOneAndDelete()` = find one document and delete / 한 개의 문서 찾아서 삭제하기
- `mongoose.model().findByIdAndRemove()` = find document by ID and remove / ID로 문서 찾아서 삭제하기

### Mongoose Schema

A Mongoose schema defines the structure of the document, default values, validators, etc., whereas a Mongoose model provides an interface to the database for creating, querying, updating, deleting records, etc.<br>
몽구스 스키마는 문서의 구조, 기본값, 유효성 검사기 등을 정의하는 반면, 몽구스 모델은 레코드 생성, 조회, 수정, 삭제 등을 위한 데이터베이스 인터페이스를 제공합니다.

```js
const mongoose = require("mongoose"),
  Schema = mongoose.Schema;

const userSchema = new Schema({
  username: { type: String, required: true, unique: true },
  password: { type: String, required: true },
});

module.exports = mongoose.model("User", userSchema);
```

### Mongoose Schema Types

- String = 문자열
- Number = 숫자
- Date = JS날짜
- Buffer = 바이너리 데이터
- Boolean = 불리언
- Mixed = 혼합 - `mongoose.Schema.Types.Mixed`
- ObjectId = 몽고디비 ID - `mongoose.Schema.Types.ObjectId` - Ex: '5f0bfbf4e8b7a5e9a4b7e8b7'
- Array = 배열

### Mongoose Schema Options

- **type = 데이터 타입**
- **required = 필수 여부**
- **default = 기본값**
- **unique = 고유 여부**
- enum = 열거형
- min = 최소값
- max = 최대값
- minlength = 최소 길이
- maxlength = 최대 길이
- match = 정규식
- validate = 유효성 검사기
- timestamps = 타임스탬프

### Data Relationships

- One-to-One = 1:1
  - For example, a user has one profile.
  - 예를 들어, 사용자는 하나의 프로필을 가지고 있습니다.
- One-to-Many = 1:N
  - For example, a user has many posts.
  - 예를 들어, 사용자는 많은 게시물을 가지고 있습니다.
- Many-to-Many = N:M
  - For example, a user has many followers and a follower has many users.
  - 예를 들어, 사용자는 많은 팔로워를 가지고 있고, 팔로워는 많은 사용자를 가지고 있습니다.

### JavaScript Promises

A JavaScript Promise is an object that represents the eventual completion (or failure) of an asynchronous operation, and its resulting value.<br>
자바스크립트 프로미스는 비동기 작업의 최종 완료 (또는 실패) 및 그 결과 값을 나타내는 객체입니다.

```js
const promise = new Promise((resolve, reject) => {
  // do something
  if (/* success */) {
    resolve(/* value */);
  } else {
    reject(/* reason */);
  }
});

promise
  .then((value) => {
    // success
  })
  .catch((reason) => {
    // failure
  });
```

# Unit 4: CRUD Operations with Mongoose

The four basic operations of persistent storage are Create, Read, Update, and Delete (CRUD).<br>
지속적인 저장의 네 가지 기본 작업은 생성, 읽기, 수정 및 삭제 (CRUD)입니다.

| Operation | HTTP Method | Mongoose Method | Controller action |
| --------- | ----------- | --------------- | ----------------- |
| Create    | POST        | create()        | create()          |
| Read      | GET         | find()          | index()           |
| Update    | PUT         | update()        | update()          |
| Delete    | DELETE      | delete()        | delete()          |

In order to use PUT and DELETE HTTP methods, we need to install and configure the [method-override](https://www.npmjs.com/package/method-override) middleware.<br>
PUT 및 DELETE HTTP 메서드를 사용하려면 [method-override](https://www.npmjs.com/package/method-override) 미들웨어를 설치하고 구성해야 합니다.

```js
const methodOverride = require("method-override");
app.use(
  methodOverride("_method", {
    methods: ["POST", "GET"],
  })
);
```

Then, we can use the `_method` query parameter to override the HTTP method.<br>
그런 다음 `_method` 쿼리 매개변수를 사용하여 HTTP 메서드를 재정의할 수 있습니다.

```html
<form method="POST" action="/users/<%= user.id %>/update?_method=PUT">
  <!-- ... -->
</form>
```

## Create

Three important things to remember when creating a new document using a Submit form are:<br>
제출 양식을 사용하여 새 문서를 생성할 때 기억해야 할 세 가지 중요한 사항은 다음과 같습니다.

1. The form's `action` attribute must be set to the route that will handle the form submission.
   - 양식의 `action` 속성은 양식 제출을 처리할 경로로 설정해야 합니다.
2. The form's `method` attribute must be set to `POST`.
   - 양식의 `method` 속성은 `POST`로 설정해야 합니다.
3. The form's `input` elements must have `name` attributes that match the names of the document's properties.
   - 양식의 `input` 요소는 문서의 속성 이름과 일치하는 `name` 속성을 가져야 합니다.

```html
<form action="/users" method="POST">
  <input type="text" name="username" />
  <input type="password" name="password" />
  <button type="submit">Submit</button>
</form>
```

### Create Controller Actions

- new: render the form for creating a new document / 새 문서를 생성하는 양식을 렌더링합니다.
- create: create a new document / 새 문서를 생성합니다.

```js
const User = require("../models/user");

module.exports = {
  new: (req, res) => {
    res.render("users/new");
  },

  create: (req, res, next) => {
    User.create(req.body)
      .then((user) => {
        res.redirect("/users"); // redirect to the '/users' route
      })
      .catch((err) => {
        next(err);
      });
  },
};
```

## Read

### Read Controller Actions

- index: render a list of documents / 문서 목록을 렌더링합니다.
- show: render a single document / 단일 문서를 렌더링합니다.

```js
const User = require("../models/user");

module.exports = {
  index: (req, res, next) => {
    User.find()
      .then((users) => {
        res.render("users/index", { users }); // render the 'users/index' template with the 'users' array
      })
      .catch((err) => {
        next(err);
      });
  },

  show: (req, res, next) => {
    User.findById(req.params.id)
      .then((user) => {
        res.render("users/show", { user }); // render the 'users/show' template with the 'user' object
      })
      .catch((err) => {
        next(err);
      });
  },
};
```

## Update

### Update Controller Actions

- edit: render the form for editing a document / 문서를 편집하는 양식을 렌더링합니다.
- update: update a document / 문서를 수정합니다.

```js
const User = require("../models/user");

module.exports = {
  edit: (req, res, next) => {
    User.findById(req.params.id)
      .then((user) => {
        res.render("users/edit", { user }); // render the 'users/edit' template with the 'user' object
      })
      .catch((err) => {
        next(err);
      });
  },

  update: (req, res, next) => {
    User.findByIdAndUpdate(req.params.id, req.body)
      .then((user) => {
        res.redirect(`/users/${user.id}`); // redirect to the '/users/:id' route
      })
      .catch((err) => {
        next(err);
      });
  },
};
```

## Delete

### Delete Controller Actions

- delete: delete a document / 문서를 삭제합니다.

```js
const User = require("../models/user");

module.exports = {
  delete: (req, res, next) => {
    User.findByIdAndDelete(req.params.id)
      .then(() => {
        res.redirect("/users"); // redirect to the '/users' route
      })
      .catch((err) => {
        next(err);
      });
  },
};
```

# Unit 5: User Authentication with Passport

## Flash Messages with Connect-Flash

Flash messages are messages that are stored in the session and then rendered to the user. They are typically used to display `success` or `error` messages.<br>
플래시 메시지는 세션에 저장한 다음 사용자에게 렌더링되는 메시지입니다. 일반적으로 `success` 또는 `error` 메시지를 표시하는 데 사용됩니다.

```js
const session = require("express-session"),
  flash = require("connect-flash");

router.use((req, res, next) => {
  res.locals.flashMessages = req.flash();
  next();
});

// Controller action
module.exports = {
  create: (req, res, next) => {
    User.create(req.body)
      .then((user) => {
        req.flash("success", "User created successfully!"); // set the flash message
        res.redirect("/users");
      })
      .catch((err) => {
        req.flash("error", err.message); // set the flash message
        next(err);
      });
  },
};
```

## Password Hashing with Bcrypt

`bcrypt` is a password hashing function that is used to hash passwords before storing them in the database.<br>
`bcrypt`는 데이터베이스에 저장하기 전에 비밀번호를 해시하는 데 사용되는 비밀번호 해시 함수입니다.

We usually use the `bcrypt.hash()` function to hash passwords before saving them in the database with a pre-save hook.We use the `bcrypt.compare()` function to compare passwords when logging in users.<br>
일반적으로 사전 저장 후크로 데이터베이스에 저장하기 전에 비밀번호를 해시하는 데 `bcrypt.hash()` 함수를 사용합니다. 사용자 로그인 시 비밀번호를 비교하는 데 `bcrypt.compare()` 함수를 사용합니다.

```js
const bcrypt = require("bcrypt");

userSchema.pre("save", function (next) {
  const user = this;
  bcrypt
    .hash(user.password, 10)
    .then((hash) => {
      user.password = hash;
      next();
    })
    .catch((err) => {
      console.log(err); // handle error
      next(err);
    });
});

// Controller action
module.exports = {
  authenticate: (req, res, next) => {
    User.findOne(email: req.body.email)
      .then((user) => {
        if (!user) {
          req.flash("error", "User not found!");
          res.redirect("/login");
        } else {
          bcrypt
            .compare(req.body.password, user.password)
            .then((result) => {
              if (result) {
                req.session.userId = user.id;
                res.redirect("/users");
              } else {
                req.flash("error", "Password is incorrect!");
                res.redirect("/login");
              }
            })
            .catch((err) => {
              console.log(err); // handle error
              next(err);
            });
        }
      })
      .catch((err) => {
        console.log(err); // handle error
        next(err);
      });
  },
}
```

## Passport

Passport is an authentication middleware for Node.js that supports authentication using a username and password, Facebook, Twitter, and more.<br>
Passport는 Node.js용 인증 미들웨어로, 사용자 이름과 비밀번호, Facebook, Twitter 등을 사용한 인증을 지원합니다.

### Passport Configuration

```js
const passport = require("passport");
router.use(passport.initialize());
router.use(passport.session());

// serialize user = save user ID to session / 사용자 ID를 세션에 저장
const User = require("../models/user");
passport.serializeUser(User.serializeUser());
passport.deserializeUser(User.deserializeUser());
```

### Passport Local Strategy

We use `passport-local-mongoose` to add a local strategy to our User model.<br>
`passport-local-mongoose`를 사용하여 User 모델에 로컬 전략을 추가합니다.

```js
const passportLocalMongoose = require("passport-local-mongoose");
userSchema.plugin(passportLocalMongoose, {
  usernameField: "email",
});
```

### Local Variables

We also need to add the `loggedIn` and `currentUser` variables to the `res.locals` object so that they are available in all templates.<br>
모든 템플릿에서 사용할 수 있도록 `res.locals` 객체에 `loggedIn` 및 `currentUser` 변수를 추가해야 합니다.

```js
router.use((req, res, next) => {
  res.locals.loggedIn = req.isAuthenticated();
  res.locals.currentUser = req.user;
  next();
});
```

### Passport Local Authentication

Finally, we rewrite `create` and `authenticate` controller actions to use Passport local authentication. We also add a `logout` controller action to log out users.<br>
마지막으로, Passport 로컬 인증을 사용하도록 `create` 및 `authenticate` 컨트롤러 액션을 다시 작성합니다. 또한 사용자 로그아웃을 위해 `logout` 컨트롤러 액션을 추가합니다.

```js
const passport = require("passport");

module.exports = {
  create: (req, res, next) => {
    User.register(new User({ email: req.body.email }), req.body.password)
      .then((user) => {
        passport.authenticate("local")(req, res, () => {
          req.flash("success", "User created successfully!");
          res.redirect("/users");
        });
      })
      .catch((err) => {
        req.flash("error", err.message);
        next(err);
      });
  },

  login: (req, res) => {
    res.render("users/login");
  },

  authenticate: (req, res, next) => {
    passport.authenticate("local", {
      successRedirect: "/users",
      failureRedirect: "/login",
      failureFlash: true,
    })(req, res, next);
  },

  logout: (req, res, next) => {
    req.logout();
    res.redirect("/login");
  },
};
```

# Important Packages

We are using the following Node.js packages in our project. Be sure you understand what they do and how to use them.<br>
프로젝트에서 다음 Node.js 패키지를 사용합니다. 이들이 무엇을 하는지와 사용 방법을 반드시 이해하십시오.

- [bcrypt](https://www.npmjs.com/package/bcrypt) = Password hashing / 비밀번호 해시
- [connect-flash](https://www.npmjs.com/package/connect-flash) = Flash messages / 플래시 메시지
- [cookie-parser](https://www.npmjs.com/package/cookie-parser) = Cookie parsing / 쿠키 파싱
- [ejs](https://www.npmjs.com/package/ejs) = Embedded JavaScript templates / 내장된 JavaScript 템플릿
- [express](https://www.npmjs.com/package/express) = Web framework / 웹 프레임워크
- [express-ejs-layouts](https://www.npmjs.com/package/express-ejs-layouts) = Layout support for EJS / EJS 레이아웃 지원
- [express-session](https://www.npmjs.com/package/express-session) = Session middleware / 세션 미들웨어
- [express-validator](https://www.npmjs.com/package/express-validator) = Form validation / 양식 유효성 검사
- [http-status-codes](https://www.npmjs.com/package/http-status-codes) = HTTP status codes / HTTP 상태 코드
- [method-override](https://www.npmjs.com/package/method-override) = HTTP method override / HTTP 메서드 재정의
- [mongodb](https://www.npmjs.com/package/mongodb) = MongoDB driver / MongoDB 드라이버
- [mongoose](https://www.npmjs.com/package/mongoose) = MongoDB ODM (Object-document mapper) / MongoDB ODM (객체-문서 매퍼)
- [passport](https://www.npmjs.com/package/passport) = Authentication middleware / 인증 미들웨어
- [passport-local-mongoose](https://www.npmjs.com/package/passport-local-mongoose) = Passport local strategy / Passport 로컬 전략
