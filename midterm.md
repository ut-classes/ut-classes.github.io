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

## Midterm Test Study Guide / 중간고사 스터디 가이드

Schedule: **4월21일 일정**

<!-- Download: [PDF](https://ut-nodejs.github.io/midterm.pdf) | [PPTX](https://ut-nodejs.github.io/midterm.pptx) -->

- [1. Git and GitHub Classroom](#1-git-and-github-classroom)
  - [Basic Git commands](#basic-git-commands)
  - [GitHub Classroom](#github-classroom)
- [2. Node.js](#2-nodejs)
  - [What is Node.js?](#what-is-nodejs)
  - [Node.js REPL](#nodejs-repl)
  - [Modules, Packages, and Dependencies](#modules-packages-and-dependencies)
  - [`exports` Module / `require` keyword](#exports-module--require-keyword)
  - [Callback Functions](#callback-functions)
- [3. NPM](#3-npm)
  - [What is NPM?](#what-is-npm)
  - [Some important NPM commands](#some-important-npm-commands)
  - [The `package.json` file](#the-packagejson-file)
  - [The `node_modules` folder](#the-node_modules-folder)
  - [NPM modules in this course](#npm-modules-in-this-course)
  - [NPM scripts](#npm-scripts)
  - [About `nodemon`](#about-nodemon)
- [4. Basic Web Servers](#4-basic-web-servers)
  - [HTTP Module](#http-module)
  - [`request` and `response` objects](#request-and-response-objects)
  - [`http-status-codes` (200, 404, 500)](#http-status-codes-200-404-500)
  - [HTTP Headers](#http-headers)
  - [HTTP Methods](#http-methods)
- [5. Request-Response Cycle](#5-request-response-cycle)
  - [Listening for Requests](#listening-for-requests)
  - [Analyzing the Request](#analyzing-the-request)
  - [Reading the Request Body](#reading-the-request-body)
    - [JSON.stringify()](#jsonstringify)
    - [JSON.parse()](#jsonparse)
- [6. Routing and External Files](#6-routing-and-external-files)
  - [Simple Routing](#simple-routing)
  - [Working with Static Files](#working-with-static-files)
  - [Simple Route Handling in External Files](#simple-route-handling-in-external-files)
- [7. Express Framework](#5-express-framework)
- [8. Middleware](#6-middleware)
- [9. Template Engine](#8-template-engine)
- [10. MVC Pattern](#9-mvc-pattern)

---

# Unit 0

## 1. `git` and GitHub Classroom

### Basic `git` commands

- `git init` - initialize a local repository / 로컬 저장소 초기화
- `git add` - add files to the staging area / 스테이징 영역에 파일 추가
- `git commit` - commit changes to the local repository / 로컬 저장소에 변경사항 커밋
- `git push` - push changes to the remote repository / 원격 저장소에 변경사항 푸시
- `git pull` - pull changes from the remote repository / 원격 저장소에서 변경사항 풀
- `git clone` - clone a remote repository / 원격 저장소 복제

### [GitHub Classroom](https://ut-nodejs.github.io/instructions.html)

- [Accepting an assignment / 과제 수락](https://ut-nodejs.github.io/instructions.html#1-accessing-the-assignment)
- [Submitting an assignment / 과제 제출](https://ut-nodejs.github.io/instructions.html#2-submitting-the-assignment)
- [Checking the status of an assignment / 과제 상태 확인](https://ut-nodejs.github.io/instructions.html#3-checking-the-assignment)

---

## 2. Node.js

### What is Node.js?

An **asynchronous runtime environment**, used for building JavaScript web applications. It handles the backend web server and can run JavaScript outside the browser. It is built on **Google Chrome's V8 JavaScript engine**.<br>
자바스크립트를 사용하여 웹 애플리케이션을 만들기 위한 **비동기 런타임 환경**입니다. 백엔드 웹 서버를 다루고 브라우저 밖에서 자바스크립트를 실행할 수 있습니다. **구글 크롬의 V8 자바스크립트 엔진**을 기반으로 만들어졌습니다.

- [Node.js](https://nodejs.org/ko/)
- [Node.js 설치](https://nodejs.org/ko/download/)

### Node.js REPL

REPL is the Read-Eval-Print-Loop. It is a simple interactive shell that evaluates expressions and returns the result to the user. It is used for debugging and testing.<br>
REPL은 Read-Eval-Print-Loop의 약자입니다. 표현식을 평가하고 결과를 사용자에게 반환하는 간단한 대화형 셸입니다. 디버깅과 테스트에 사용됩니다.

- [REPL](https://nodejs.org/ko/docs/guides/getting-started-guide/#repl)

### Modules, Packages, and Dependencies

1. Modules are the basic building blocks of Node.js applications. They are **self-contained pieces of code** that can be reused throughout an application.<br>
   모듈은 Node.js 애플리케이션의 기본 구성 요소입니다. 애플리케이션 전체에서 재사용할 수 있는 **독립적인 코드 조각**입니다.
2. Packages are a **collection of modules** that can be used in an application.<br>
   패키지는 애플리케이션에서 사용할 수 있는 **모듈의 모음**입니다.
3. Dependencies are the packages that an application **needs** to run.<br>
   의존성은 애플리케이션을 실행하는 데 **필요한 패키지**입니다.

- [Modules](https://nodejs.org/ko/docs/guides/getting-started-guide/#modules)
- [Packages](https://nodejs.org/ko/docs/guides/getting-started-guide/#packages)
- [Dependencies](https://nodejs.org/ko/docs/guides/getting-started-guide/#dependencies)

### `exports` Module / `require` keyword

Modules can be exported from one file with the `exports` object and imported in another file with the `require` keyword.<br>
모듈은 `exports` 객체로 하나의 파일에서 내보내고 `require` 키워드로 다른 파일에서 가져올 수 있습니다.

- [export](https://nodejs.org/ko/docs/guides/getting-started-guide/#export)
- [require](https://nodejs.org/ko/docs/guides/getting-started-guide/#require)

### Callback functions

A callback function is a function that is passed as an argument to another function and is executed after some operation has been completed.<br>
콜백 함수는 다른 함수에 인수로 전달되고 일부 작업이 완료된 후 실행되는 함수입니다.

- [Callback functions](https://nodejs.org/ko/docs/guides/getting-started-guide/#callback-functions)

---

## 3. NPM

### What is NPM?

NPM is the **Node Package Manager**. It is used to install and manage Node.js packages.<br>
NPM은 **Node 패키지 관리자**입니다. Node.js 패키지를 설치하고 관리하는 데 사용됩니다.

### Some important NPM commands

- `npm init` - initialize a Node.js project / Node.js 프로젝트 초기화
- `npm install` - install a package / 패키지 설치
- `npm install -g` - install a package globally / 패키지를 전역으로 설치
- `npm install --save` - install a package and add it to the `package.json` file / 패키지를 설치하고 `package.json` 파일에 추가
- `npm install --save-dev` - install a package and add it to the `package.json` file as a development dependency / 패키지를 설치하고 `package.json` 파일에 개발 의존성으로 추가
- `npm uninstall` - uninstall a package / 패키지 삭제
- `npm update` - update a package / 패키지 업데이트
- `npm start` - run the `start` script in the `package.json` file / `package.json` 파일의 `start` 스크립트 실행

Of the commands listed above, you should at least be familiar with `npm init`, `npm install`, and `npm start`.<br>
위 목록에 나열된 명령 중에서 적어도 `npm init`, `npm install`, `npm start`를 알고 있어야 합니다.

- [NPM](https://www.npmjs.com/)

### The `package.json` file

The `package.json` file is used to manage the dependencies of a Node.js project. It is created with the `npm init` command.<br>
`package.json` 파일은 Node.js 프로젝트의 의존성을 관리하는 데 사용됩니다. `npm init` 명령으로 생성됩니다.

- [package.json](https://nodejs.org/ko/docs/guides/getting-started-guide/#packagejson)

### The `node_modules` folder

The `node_modules` folder is created when you install a package with the `npm install` command. It contains all the packages that are installed in the project. As a best practice, the `node_modules` folder should not be added to the repository. Ignore it with a `.gitignore` file.<br>
`node_modules` 폴더는 `npm install` 명령으로 패키지를 설치할 때 생성됩니다. 이 폴더에는 프로젝트에 설치된 모든 패키지가 포함됩니다. 가장 좋은 방법은 `node_modules` 폴더를 저장소에 추가하지 않는 것입니다. `.gitignore` 파일로 무시하세요.

### NPM Modules in this course

- [http-status-codes](https://www.npmjs.com/package/http-status-codes)
- [nodemon](https://www.npmjs.com/package/nodemon)
- [express](https://www.npmjs.com/package/express)
- [ejs](https://www.npmjs.com/package/ejs)
- [express-ejs-layouts](https://www.npmjs.com/package/express-ejs-layouts)
- [body-parser](https://www.npmjs.com/package/body-parser)
- [mongodb](https://www.npmjs.com/package/mongodb)
- [mongoose](https://www.npmjs.com/package/mongoose)

### NPM Scripts

NPM scripts are used to run predefined scripts via the `npm` command. They are defined in the `scripts` object in the `package.json` file. For example, we use the `npm start` script to run our web applications, and some assignments use the `npm test` script for auto-grading.<br>
NPM 스크립트는 `npm` 명령을 통해 미리 정의된 스크립트를 실행하는 데 사용됩니다. 이들은 `package.json` 파일의 `scripts` 객체에 정의됩니다. 예를 들어, 웹 애플리케이션을 실행하기 위해 `npm start` 스크립트를 사용하고 일부 과제는 `npm test` 스크립트를 사용하여 자동 채점합니다.

### About `nodemon`

`nodemon` is a tool that helps develop Node.js based applications by automatically restarting the node application when file changes in the directory are detected. We use this module during development so we don't need to always press CTRL+C when we make changes to our files. It is easiest to include this in the `npm start` script as shown below.<br>
`nodemon`은 디렉토리의 파일 변경을 감지할 때 노드 애플리케이션을 자동으로 다시 시작하여 Node.js 기반 애플리케이션을 개발하는 데 도움을 주는 도구입니다. 이 모듈을 개발 중에 사용하여 파일을 변경할 때마다 항상 CTRL + C를 누르지 않아도 됩니다. 아래와 같이 `npm start` 스크립트에 포함하는 것이 가장 쉽습니다.

```json
"scripts": {
  "start": "nodemon main.js"
}
```

```bash
npm start
```

---

# Unit 1

## 4. Basic Web Servers

For a more in-depth explanation of an **HTTP transaction**, see [this article](https://nodejs.org/ko/docs/guides/anatomy-of-an-http-transaction) from the Node.js documentation.<br>
**HTTP 트랜잭션**에 대한 자세한 설명은 Node.js 문서의 [이 글](https://nodejs.org/ko/docs/guides/anatomy-of-an-http-transaction)을 참고하세요.

### `http` Module

The HTTP module is used to create Node.js web servers. A server can be created with the `createServer` method. The `createServer` method takes a callback function as a parameter. The callback function takes two parameters: `request` and `response`.<br>
HTTP 모듈은 Node.js 웹 서버를 만들 때 사용됩니다. `createServer` 메서드를 사용하여 서버를 만들 수 있습니다. `createServer` 메서드는 콜백 함수를 매개변수로 사용합니다. 콜백 함수는 `request`와 `response`를 매개변수로 사용합니다.

```js
const http = require("http");

const server = http.createServer((request, response) => {
  // ...
});
```

#### `request` & `response` Objects

The `request` object represents the request from the client. It contains information about the request such as the URL, request method, request headers, and data. The `response` object represents the response that the server sends back to the client. It contains information about the response such as the status code, response headers, and data.<br>
`request` 객체는 클라이언트의 요청을 나타냅니다. URL, 요청 방법, 요청 헤더 및 데이터와 같은 요청에 대한 정보가 포함됩니다. `response` 객체는 서버가 클라이언트에게 보내는 응답을 나타냅니다. 상태 코드, 응답 헤더 및 데이터와 같은 응답에 대한 정보가 포함됩니다.

- [request](https://nodejs.org/ko/docs/guides/anatomy-of-an-http-transaction/#request)
- [response](https://nodejs.org/ko/docs/guides/anatomy-of-an-http-transaction/#response)

### `http-status-codes` (200, 404, 500)

The HTTP status codes are used to indicate the status of a server response. The most common status codes are 200, 404, and 500.<br>
HTTP 상태 코드는 서버 응답의 상태를 나타내는 데 사용됩니다. 가장 일반적인 상태 코드는 200, 404, 500입니다.

- `200` - OK
- `404` - Not Found
- `500` - Internal Server Error

We use the `writeHead` method to check the status code of the response. Then we use the `write` method to write the response message. Finally, we use the `end` method to end the response.<br>
`writeHead` 메서드를 사용하여 응답의 상태 코드를 확인합니다. 그런 다음 `write` 메서드를 사용하여 응답 메시지를 작성합니다. 마지막으로 `end` 메서드를 사용하여 응답을 종료합니다.

```js
const http = require("http");
const httpStatusCode = require("http-status-codes");
const port = 3000;

const server = http.createServer((request, response) => {
  response.writeHead(httpStatusCode.OK, {
    // status code: 200
    "Content-Type": "text/html", // response header
  });

  let responseMessage = "<h1>Hello, Universe!</h1>";
  response.write(responseMessage);
  response.end();
});
```

- [http-status-codes](https://www.npmjs.com/package/http-status-codes)

### HTTP Headers

HTTP headers are used to send additional information with the request or the response. One of the most common HTTP headers is `Content-Type`, shown above in the `writeHead` function. This header is used to indicate the type of data that is being sent (HTML, CSS, JavaScript, JSON, etc.).<br>
HTTP 헤더는 요청 또는 응답에 추가 정보를 보내는 데 사용됩니다. 가장 일반적인 HTTP 헤더 중 하나는 `writeHead` 함수에서 보여진 `Content-Type`입니다. 이 헤더는 보내는 데이터의 유형을 나타내는 데 사용됩니다 (HTML, CSS, JavaScript, JSON 등).

### HTTP Methods

HTTP methods are used to indicate the type of action that the client wants to perform on a resource. **In the class, we have studied `GET` and `POST`.** Later, we will also study `PUT` and `DELETE`.<br>
HTTP 메서드는 클라이언트가 리소스에 대해 수행하려는 작업 유형을 나타내는 데 사용됩니다. **클래스에서는 `GET`과 `POST`를 공부했습니다.** 나중에 `PUT`과 `DELETE`도 공부할 것입니다.

- `GET` - retrieve a resource / 리소스 검색
- `POST` - create a resource / 리소스 생성
- <del>`PUT` - update a resource / 리소스 업데이트</del>
- <del>`DELETE` - delete a resource / 리소스 삭제</del>

```js
const http = require("http");
const httpStatusCode = require("http-status-codes");
const port = 3000;

const server = http.createServer((request, response) => {
  console.log(`Method: ${request.method}`); // GET, POST, PUT, DELETE
  console.log(`URL: ${request.url}`);
  // ...
});
```

---

## 5. Request-Response Cycle

### Listening for Requests

The `listen` method is used to start the server. It takes two parameters: the port number and the callback function. The callback function is executed when the server starts listening for requests.<br>
`listen` 메서드는 서버를 시작하는 데 사용됩니다. 두 개의 매개변수를 사용합니다: 포트 번호와 콜백 함수. 콜백 함수는 서버가 요청을 수신하기 시작할 때 실행됩니다.

```js
const http = require("http");
const httpStatusCode = require("http-status-codes");
const port = 3000;

const server = http.createServer((request, response) => {
  // ...
});

server.listen(port, () => {
  console.log(
    `The server has started and is listening on port number: ${port}`
  );
});
```

### Analyzing the Request

The `request` object contains information about the request. We can use the `url` property to get the URL of the request. We can use the `method` property to get the HTTP method of the request.<br>
`request` 객체에는 요청에 대한 정보가 포함됩니다. `url` 속성을 사용하여 요청의 URL을 가져올 수 있습니다. `method` 속성을 사용하여 요청의 HTTP 메서드를 가져올 수 있습니다.

```js
const http = require("http");
const httpStatusCode = require("http-status-codes");
const port = 3000;

const server = http.createServer((request, response) => {
  console.log(`Method: ${request.method}`); // GET, POST, PUT, DELETE
  console.log(`URL: ${request.url}`);
  // ...
});
```

### Reading the Request Body

The `body` property of the `request` object (shown above) is not available immediately. It is only available after the `end` event is emitted.<br>
`request` 객체의 `body` 속성 (위에서 표시됨)은 즉시 사용할 수 없습니다. `end` 이벤트가 발생한 후에만 사용할 수 있습니다.

```js
const http = require("http");
const httpStatusCode = require("http-status-codes");
const port = 3000;

const server = http.createServer((request, response) => {
  let body = [];

  request
    .on("data", (chunk) => {
      body.push(chunk);
    })
    .on("end", () => {
      body = Buffer.concat(body).toString();
      console.log("body:", body);
    });
});

server.listen(port, () => {
  console.log(
    `The server has started and is listening on port number: ${port}`
  );
});
```

#### JSON.stringify()

The `JSON.stringify` method is used to convert a JavaScript object (such as the URL request parameters, or URL request body) into a JSON string.<br>
`JSON.stringify` 메서드는 JavaScript 객체 (URL 요청 매개변수 또는 URL 요청 본문과 같은)를 JSON 문자열로 변환하는 데 사용됩니다.

```js
const http = require("http");
const httpStatusCode = require("http-status-codes");
const port = 3000;

const server = http.createServer((request, response) => {
  console.log("url:", request.url); // request url
  console.log("method:", request.method); // request method
  console.log("request parameters:", JSON.stringify(request.params)); // request parameters
  console.log("request body:", JSON.stringify(request.body)); // request body
  // ...
});

server.listen(port, () => {
  console.log(
    `The server has started and is listening on port number: ${port}`
  );
});
```

#### JSON.parse()

On the other hand, the `JSON.parse` method is used to convert a JSON string back into a JavaScript object. The `JSON.parse` method takes two parameters: the string to convert and the function used to replace values.<br>
반면에 `JSON.parse` 메서드는 JSON 문자열을 다시 JavaScript 객체로 변환하는 데 사용됩니다. `JSON.parse` 메서드는 두 개의 매개변수를 사용합니다: 변환할 문자열과 값을 대체하는 데 사용되는 함수.

---

## 6. Routing and External Files

### Simple Routing

Because the `request` object contains a `url` property which contains the URL of the request, we can use this property to implement simple routing.<br>
`request` 객체에는 요청의 URL을 포함하는 `url` 속성이 포함되어 있으므로 이 속성을 사용하여 간단한 라우팅을 구현할 수 있습니다.

```js
const http = require("http");
const httpStatusCode = require("http-status-codes");
const port = 3000;

const server = http.createServer((request, response) => {
  if (request.url === "/") {
    // home route
    response.writeHead(httpStatusCode.OK, {
      "Content-Type": "text/html",
    });
    response.write("<h1>Hello World!</h1>");
    response.end();
  } else if (request.url === "/users") {
    // users route
    response.writeHead(httpStatusCode.OK, {
      "Content-Type": "text/html",
    });
    response.write("<h1>Users</h1>");
    response.end();
  } else {
    // 404 Not Found route
    response.writeHead(httpStatusCode.NOT_FOUND, {
      "Content-Type": "text/html",
    });
    response.write("<h1>Not Found</h1>");
    response.end();
  }
});

server.listen(port, () => {
  console.log(
    `The server has started and is listening on port number: ${port}`
  );
});
```

### Working with Static Files

The `fs` module uses the `readFile` method to read the contents of a file. The `readFile` method takes three parameters: the file path, the encoding, and the callback function. Remember that the first parameter in the callback function is _always_ the error object, and the second parameter is the data.<br>
`fs` 모듈은 `readFile` 메서드를 사용하여 파일의 내용을 읽습니다. `readFile` 메서드는 세 개의 매개변수를 사용합니다: 파일 경로, 인코딩 및 콜백 함수. 콜백 함수의 첫 번째 매개변수는 _항상_ 오류 객체이고 두 번째 매개변수는 데이터입니다.

```js
const http = require("http");
const httpStatusCode = require("http-status-codes");
const fs = require("fs");
const port = 3000;

const server = http.createServer((request, response) => {
  if (request.url === "/") {
    // home route
    response.writeHead(httpStatusCode.OK, {
      "Content-Type": "text/html",
    });
    fs.readFile("./views/index.html", (error, data) => {
      if (error) {
        console.log(error);
        response.end();
      } else {
        response.write(data);
        response.end();
      }
    });
  } else {
    // 404 Not Found route
    response.writeHead(httpStatusCode.NOT_FOUND, {
      "Content-Type": "text/html",
    });
    fs.readFile("./views/404.html", (error, data) => {
      if (error) {
        console.log(error);
        response.end();
      } else {
        response.write(data);
        response.end();
      }
    });
  }
});

server.listen(port, () => {
  console.log(
    `The server has started and is listening on port number: ${port}`
  );
});
```

### Simple Route Handling in External Files

We can break the routing logic into separate files and use the `require` function to import them into our main file.<br>
라우팅 로직을 별도의 파일로 나누고 `require` 함수를 사용하여 메인 파일에 가져올 수 있습니다.

```js
// main.js
const http = require("http");
const httpStatusCode = require("http-status-codes");
const fs = require("fs");
const port = 3000;

const router = require("./router");

const server = http.createServer(router.handle);

server.listen(port, () => {
  console.log(
    `The server has started and is listening on port number: ${port}`
  );
});
```

```js
// router.js
const routes = {
  GET: {},
  POST: {},
};

exports.handle = (request, response) => {
  try {
    routes[request.method][request.url](request, response);
  } catch (error) {
    response.writeHead(404);
    response.end();
  }
};

exports.get = (url, action) => {
  routes["GET"][url] = action;
};

exports.post = (url, action) => {
  routes["POST"][url] = action;
};
```

---

# Unit 2

## 7. Express Framework

Express is the most popular Node.js framework. One of the main reasons for its popularity is that it is very easy to use and it provides a lot of useful features out of the box.<br>
Express는 가장 인기있는 Node.js 프레임워크입니다. 인기의 주요 이유 중 하나는 사용하기 매우 쉽고 많은 유용한 기능을 제공하기 때문입니다.

- [Express](https://expressjs.com/ko/)
- [Express Generator](https://expressjs.com/ko/starter/generator.html)

### Setting up a New Express Project

Setting up a new Express project is easy.<br>
새로운 Express 프로젝트를 설정하는 것은 쉽습니다.

```js
const port = 3000;
const express = require("express");
const app = express();

app.get("/", (request, response) => {
  response.send("Hello World!");
});

app.listen(port, () => {
  console.log(`Example app listening at http://localhost:${port}`);
});
```

### Request and Response Object Methods

The `request` object contains information about the request that was made to the server. The `response` object contains methods that we can use to send a response back to the client.<br>
`request` 객체에는 서버에 대한 요청에 대한 정보가 포함되어 있습니다. `response` 객체에는 클라이언트에게 응답을 보내는 데 사용할 수 있는 메서드가 포함되어 있습니다.

- `request.url` - 요청의 URL
- `request.method` - 요청의 HTTP 메서드
- `response.send()` - 클라이언트에게 응답을 보냅니다.
- `response.status()` - 응답의 HTTP 상태 코드를 설정합니다.
- `response.json()` - 클라이언트에게 JSON 응답을 보냅니다.

### Routing in Express

Routing in Express is very similar to routing in Node.js. The main difference is that we use the `app` object instead of the `http` object.<br>
Express에서 라우팅은 Node.js에서 라우팅과 매우 유사합니다. 주요 차이점은 `http` 객체 대신 `app` 객체를 사용한다는 것입니다.

```js
const port = 3000;
const express = require("express");
const app = express();

app.get("/", (request, response) => {
  response.send("Hello World!");
});

app.get("/users", (request, response) => {
  response.send("Users");
});

app.post("/users", (request, response) => {
  response.send("Users");
});

app.listen(port, () => {
  console.log(`Example app listening at http://localhost:${port}`);
});
```

### Using Route Parameters

Route parameters are used to capture values from the URL such as the user ID.<br>
라우트 매개 변수는 사용자 ID와 같은 URL에서 값을 캡처하는 데 사용됩니다.

```js
const port = 3000;
const express = require("express");
const app = express();

app.get("/", (request, response) => {
  response.send("Hello World!");
});

app.get("/users/:id", (request, response) => {
  response.send(`User ID: ${request.params.id}`);
});

app.listen(port, () => {
  console.log(`Example app listening at http://localhost:${port}`);
});
```

### Working with Query Parameters

Express provides a built-in middleware function called `express.urlencoded` to parse the query string in the URL. An example of a query string is `?name=John&age=30`.<br>
Express는 URL의 쿼리 문자열을 구문 분석하는 빌트인 미들웨어 함수인 `express.urlencoded`를 제공합니다. 쿼리 문자열의 예는 `?name=John&age=30`입니다.

```js
const port = 3000;
const express = require("express");
const app = express();

app.use(express.urlencoded({ extended: true }));

// ...
```

### Working with Request Body

Express provides a built-in middleware function called `express.json` to parse the request body.<br>
Express는 요청 본문을 구문 분석하는 빌트인 미들웨어 함수인 `express.json`을 제공합니다.

```js
const port = 3000;
const express = require("express");
const app = express();

app.use(express.json());

// ...
```

### Working with Static Files

Express provides a built-in middleware function called `express.static` to serve static files.<br>
Express는 정적 파일을 제공하는 빌트인 미들웨어 함수인 `express.static`을 제공합니다.

```js
const port = 3000;
const express = require("express");
const app = express();

app.use(express.static("public"));

// ...
```

## 8. Middleware

Middleware is a function that has access to the `request` and `response` objects. The term _middleware_ is applied to code that assists in (1) listening for, (2) analyzing, (3) filtering, and (4) handling HTTP communication before data interacts with application logic.<br>
미들웨어는 `request` 및 `response` 객체에 액세스 할 수있는 함수입니다. *미들웨어*라는 용어는 데이터가 응용 프로그램 로직과 상호 작용하기 전에 HTTP 통신을 (1)수신, (2)분석, (3)필터링 및 (4)처리하는 데 도움이되는 코드에 적용됩니다.

### Creating Custom Middleware

We can create custom middleware functions that can be used in our Express application. The important thing to remember is that the middleware function must call the `next` function to pass control to the next middleware function. This is called _middleware chaining_ and allows us to create a pipeline of functions that can be executed in sequence.<br>
Express 애플리케이션에서 사용할 수있는 사용자 정의 미들웨어 함수를 만들 수 있습니다. 기억해야 할 중요한 점은 미들웨어 함수가 `next` 함수를 호출하여 제어를 다음 미들웨어 함수로 전달해야한다는 것입니다. 이것은 *미들웨어 체이닝*이라고하며 순차적으로 실행할 수있는 함수의 파이프 라인을 만들 수 있습니다.

```js
const port = 3000;
const express = require("express");
const app = express();

app.use(express.json());

app.use((request, response, next) => {
  console.log("Hello World!");
  next();
});

app.use((request, response, next) => {
  console.log("Hello World Again!");
  next();
});

// ...
```

## 9. Template Engine

The template engine is responsible for generating the HTML that is sent to the client. In this tutorial, we will use the EJS template engine. EJS makes it possible to use plain JavaScript in HTML files as well as to create reusable partial components.<br>
템플릿 엔진은 클라이언트에게 전송되는 HTML을 생성하는 책임이 있습니다. 이 튜토리얼에서는 EJS 템플릿 엔진을 사용합니다. EJS를 사용하면 HTML 파일에서 일반 JavaScript를 사용하고 재사용 가능한 부분 컴포넌트를 만들 수 있습니다.

```html
<h1><%= title %></h1>
<ul>
  <% for (let i = 0; i < users.length; i++) { %>
  <li><%= users[i].name %></li>
  <% } %>
</ul>
```

## 10. MVC Pattern

The MVC pattern stands for Model-View-Controller. It is a software design pattern that separates the application into three main components: the model, the view, and the controller.<br>
MVC 패턴은 Model-View-Controller의 약자입니다. 이것은 응용 프로그램을 모델, 뷰 및 컨트롤러라는 세 가지 주요 구성 요소로 분리하는 소프트웨어 디자인 패턴입니다.

- **Model**
  - data layer (handled by MongoDB and Mongoose)
  - 데이터 계층 (MongoDB 및 Mongoose에 의해 처리됨)
- **View**
  - presentation layer (handled by EJS)
  - 표현 계층 (EJS에 의해 처리됨)
- **Controller**
  - application logic layer (handled by Express)
  - 응용 프로그램 로직 계층 (Express에 의해 처리됨)
