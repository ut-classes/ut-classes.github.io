<p id="menu" align="center">
  <a href="https://ut-nodejs.github.io" title="Home">🏠</a> |
  <a href="about.html" title="About">개요</a> |
  <a href="/schedule.html" title="Schedule">일정</a> |
  <a href="/slides.html" title="Slides">스라이드</a> |
  <a href="/assignments.html" title="Assignments"><u>[과제]</u></a> |
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

## Instructions for working with assignments / 과제 작업 방법

![3rd-week-PPT](/img/gh-pages/3rd-week-PPT.png)

These instructions were presented in the 3rd week with the following PPT. For pictures to accompany the directions, [click here to download the PDF](https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/_3.%20%EA%B3%BC%EC%A0%9C%20%EB%AC%B8%EC%A0%9C%EC%99%80%20%ED%95%B4%EA%B2%B0.pdf). 이 방법은 3주차에 PPT로 설명되었습니다. 사진을 보려면 여기를 클릭하여 PDF를 다운로드하십시오.

![3rd-week-PPT-toc](/img/gh-pages/instructions/instructions_Page_02.jpg)

There are 3 major issues to address when completing assignments. 과제를 완료할 때 3가지 주요 문제가 있습니다.

1. [Accessing the assignment / 과제에 접근하기](#1-accessing-the-assignment)
2. [Submitting the assignment / 과제 제출하기](#2-submitting-the-assignment)
3. [Checking the assignment / 과제 확인하기](#3-checking-the-assignment)

However, before even accessing the assignment, please be sure the following programs are installed on your computer. (Installing the programs in this order will be beneficial as some of the software checks if other software has already been installed). 과제에 접근하기 전에 컴퓨터에 다음 프로그램이 설치되어 있는지 확인하십시오. (이 순서로 프로그램을 설치하면 일부 소프트웨어가 이미 설치되었는지 확인합니다).

- [VS Code](https://code.visualstudio.com/)
- [GitHub Classroom Extension for VS Code](https://marketplace.visualstudio.com/items?itemName=GitHub.classroom)
- [Git](https://git-scm.com/)
  - When the installation screen comes to the "default preferred text editor," you can select VS Code as the default if it's been previously installed.
  - 설치 화면에서 "기본 선호 텍스트 편집기"로 이동하면 이전에 설치했던 VS Code를 기본으로 선택할 수 있습니다.
- [Node.JS](https://nodejs.org/ko)
  - Be sure to also install the "optional" tools like [Chocolatey](https://chocolatey.org/) if you are using Windows.
  - Windows를 사용하는 경우 "선택 사항"으로 설치된 Chocolatey와 같은 도구도 설치해야 합니다.

After the software is installed, you will be able to access and complete the assignments. 소프트웨어가 설치되면 과제에 액세스하고 완료할 수 있습니다.

---

### 1. Accessing the Assignment / 과제에 접근하기

![3rd-week-PPT-access](/img/gh-pages/instructions/instructions_Page_03.jpg)

#### Preferred Method (EASY WAY) / 선호하는 방법 (쉬운 방법)

All assignments will be accessible from the [Assignments page](https://ut-nodejs.github.io/practice.html) from the start of each class. 모든 과제는 각 수업의 시작부터 [과제 페이지](https://ut-nodejs.github.io/practice.html)에서 액세스할 수 있습니다.

To access the assignment: 과제에 접근하려면 다음을 수행하십시오.

| ![3rd-week-PPT-access-1](/img/gh-pages/instructions/instructions_Page_06.jpg) | 1. Click the Assignment link for your class (**오전** or _오후_). 수업의 과제 링크를 클릭합니다 (**오전** 또는 _오후_). |
| ![3rd-week-PPT-access-2](/img/gh-pages/instructions/instructions_Page_07.jpg) | 2. On the GitHub Classroom page, "Accept assignment" to create your personal respository. GitHub Classroom 페이지에서 "과제 수락"을 클릭하여 개인 저장소를 만듭니다. |
| ![3rd-week-PPT-access-3](/img/gh-pages/instructions/instructions_Page_08.jpg) | 3. Refresh the page. The assignment should now be visible. 페이지를 새로 고칩니다. 이제 과제가 표시됩니다. |
| ![3rd-week-PPT-access-4](/img/gh-pages/instructions/instructions_Page_09.jpg) | 4. Click "Open in VS Code" to automatically clone the repository to your local computer and open it. "VS Code에서 열기"를 클릭하여 저장소를 로컬 컴퓨터에 자동으로 복제하고 엽니다. |

If VS Code does NOT properly clone and open your repository to your local computer, you may try the following solutions. VS Code가 저장소를 로컬 컴퓨터에 올바르게 복제하고 열지 않는 경우 다음 솔루션을 시도할 수 있습니다.

#### Alternative Method 1: `git clone` / 대체 방법 1: `git clone`

1. Make sure you have created a personal folder for YOUR assignments on your computer's Desktop with your <USERNAME>. 컴퓨터의 데스크톱에 <USERNAME>으로 개인 과제를 위한 개인 폴더를 만들었는지 확인하십시오.
2. Click the link to your personal respository (or go to [github.com/ut-nodejs](http://github.com/ut-nodejs) to find your assignment and open it). 개인 저장소에 대한 링크를 클릭하거나 github.com/ut-nodejs으로 이동하여 과제를 찾아 엽니다.
3. Copy your assignment repository's URL. 과제 저장소의 URL을 복사합니다.
4. Open Git Bash. Git Bash를 엽니다.
5. Type `cd ~/Desktop/<USERNAME>` to navigate to your personal folder on the Desktop. `cd ~/Desktop/<USERNAME>`를 입력하여 데스크톱의 개인 폴더로 이동합니다.
6. Type `git clone <URL>` to download your assignment to your personal directory (type SHIFT + INS to paste the URL you copied). `git clone <URL>`을 입력하여 과제를 개인 디렉토리에 다운로드합니다 (SHIFT + INS를 입력하여 복사한 URL을 붙여 넣으십시오).
7. Type `cd <ASSIGNMENT>` to move into the newly cloned git directory. `cd <ASSIGNMENT>`를 입력하여 새로 복제된 git 디렉토리로 이동합니다.
8. Type `code .` to open the assignment in VS Code. `code .`를 입력하여 VS Code에서 과제를 엽니다.

#### Alternative Method 2: Direct Download / 대체 방법 2: 직접 다운로드

1. Make sure you have created a personal folder for YOUR assignments on your computer's Desktop with your <USERNAME>. 컴퓨터의 데스크톱에 <USERNAME>으로 개인 과제를 위한 개인 폴더를 만들었는지 확인하십시오.
2. Click the link to your personal respository (or go to [github.com/ut-nodejs](http://github.com/ut-nodejs) to find your assignment and open it). 개인 저장소에 대한 링크를 클릭하거나 github.com/ut-nodejs으로 이동하여 과제를 찾아 엽니다.
3. Click the green "Code" button in the upper-right hand corner of the repository above the list of files. 파일 목록 위쪽 오른쪽에 있는 초록색 "Code" 버튼을 클릭합니다.
4. Click "Download ZIP" and save the files to your Desktop. "ZIP 다운로드"를 클릭하고 파일을 데스크톱에 저장합니다.
5. Unzip the assignment files. 과제 파일을 압축 해제합니다.
6. Open VS Code. VS Code를 엽니다.
7. Click and drag the assignment folder into VS Code. 과제 폴더를 VS Code로 끌어 놓습니다.

###### [↑ Top / 위로 가기](/schedule.html#web-programming-application-2023)

---

### 2. Submitting the Assignment / 과제 제출하기

#### Preferred Method (EASY WAY) / 선호하는 방법 (쉬운 방법)

The easiest way to submit assignments is by performing a `commit & push` directly from within VS Code. 과제를 제출하는 가장 쉬운 방법은 VS Code에서 직접 `commit & push`를 수행하는 것입니다.

1. Edit your files (1st tab). 파일을 편집합니다 (1번 탭).
2. Save (so the circle in your file's title disappears). 저장 (파일 제목의 원이 사라짐).
3. Click the Git tab (3rd tab). Git 탭을 클릭합니다 (3번 탭).
4. In the Message box, write an appropriate message describing WHAT you coded (how you changed the files). Without the message, you cannot `commit & push.` Some examples of good and bad commit messages are shown below. Good messages are short and descriptive. Bad messages not specific or meaningless. 메시지 상자에서 무엇을 코딩했는지를 설명하는 적절한 메시지를 작성합니다 (파일을 어떻게 변경했는지). 메시지가 없으면 `commit & push`를 수행할 수 없습니다. 아래에는 좋은 메시지와 나쁜 메시지의 예가 나와 있습니다. 좋은 메시지는 간결하고 설명이 잘되어 있습니다. 나쁜 메시지는 구체적이지 않거나 의미가 없습니다.
   - Good: `Added a new menu bar` / `새로운 메뉴 바 추가`
   - Good: `Removed contact form functionality` / `연락처 양식 기능 제거`
   - Bad: `Done` / `완료`
   - Bad: `asdfjkl;` / `asdfjkl;`
5. After writing a descriptive commit message, click the down arrow on the `commit` button and choose `commit & push`. 메시지를 작성한 후 `commit` 버튼의 아래 화살표를 클릭하고 `commit & push`를 선택합니다.
6. Click "Yes" on any additional popups. 추가 팝업에서 "예"를 클릭합니다.

The above is the **preferred** method to turn in assignments, but sometimes, you may not be able to for various reasons. 위 방법은 과제를 제출하는 **선호하는** 방법이지만, 다양한 이유로 수행할 수 없는 경우가 있습니다.

- A different student's git id is registered on that computer. 다른 학생의 git id가 해당 컴퓨터에 등록되어 있습니다.
- A different student's git id is linked to that VS Code. 다른 학생의 git id가 VS Code에 연결되어 있습니다.
- A different student's assignment repository is linked. 다른 학생의 과제 저장소가 연결되어 있습니다.
- You were unable to `git clone` the assignment and had to do a direct download instead. 과제를 `git clone`하지 못하고 직접 다운로드해야 했습니다.
- Your git `user.name` and `user.email` are not set (you will see a popup error message). In this case, simply set your git id on that computer and try your `commit & push` again. git `user.name`과 `user.email`이 설정되지 않았습니다 (팝업 오류 메시지가 표시됨). 이 경우, 해당 컴퓨터에서 git id를 설정하고 다시 `commit & push`를 수행하십시오.
  1. Open Git Bash / Git Bash를 엽니다.
  2. Type `git config --global user.name "Your name"` / `git config --global user.name "Your name"`을 입력합니다.
  3. Type `git config --global user.email yourgithub@email.com` / `git config --global user.email yourgithub@email.com`을 입력합니다.
  4. Try your `commit & push` in VS Code again / VS Code에서 다시 `commit & push`를 수행합니다.

In the above cases where you can't submit your assignment in the preferred method, you may try one of the alternatives listed below. 위에서 선호하는 방법으로 과제를 제출할 수 없는 경우, 아래에 나열된 대안 중 하나를 시도할 수 있습니다.

#### Alternative 1: Command Line (after `git clone`) / 대안 1: 명령 줄 (git clone 후)

If another student's account is linked through VS Code, you may try pushing your code directly from the Git Bash command line. (Note that this method will _only_ work if you have also used the command line to `git clone` your repository to your Desktop). 다른 학생의 계정이 VS Code를 통해 연결되어 있는 경우, Git Bash 명령 줄에서 직접 코드를 푸시할 수 있습니다. (이 방법은 _only_ 커맨드 라인을 사용하여 저장소를 데스크탑에 `git clone`했을 때 작동합니다).

1. Open Git Bash. Git Bash를 엽니다.
2. Type `~/Desktop/USERNAME/ASSIGNMENT` to navigate to your assignment repository. `~/Desktop/USERNAME/ASSIGNMENT`를 입력하여 과제 저장소로 이동합니다.
3. Type `git add *` to prepare all your modified files to save. `git add *`를 입력하여 수정된 모든 파일을 준비합니다.
4. Type `git commit -m "COMMIT MESSAGE"` to save all your modified files. `git commit -m "COMMIT MESSAGE"`를 입력하여 수정된 모든 파일을 저장합니다.
5. Type `git push origin main` to push your files back to GitHub Classroom online. `git push origin main`을 입력하여 파일을 GitHub Classroom 온라인으로 다시 푸시합니다.

#### Alternative 2: Direct Upload / 대안 2: 직접 업로드

If all of the above methods have failed, you may try a direct upload of your modified files. 만약 위의 모든 방법이 실패했다면, 수정된 파일을 직접 업로드할 수 있습니다.

1. Open your GitHub assignment respository at [github.com/ut-nodejs](https://github.com/ut-nodejs). 당신의 GitHub 과제 저장소를 github.com/ut-nodejs에서 엽니다.
2. Click "Add file" to the left of the green "Code" button above your list of files. 파일 목록의 위쪽에 있는 초록색 "Code" 버튼의 왼쪽에 "Add file"을 클릭합니다.
3. Click "Upload files" to open the upload page. 업로드 페이지를 열려면 "Upload files"을 클릭합니다.
4. Navigate to your assignment respository that is stored on your computer's Desktop. 컴퓨터의 데스크탑에 저장된 과제 저장소로 이동합니다.
5. Select all your modified files (with CTRL) that need to be uploaded. 업로드해야 하는 수정된 모든 파일을 선택합니다.
6. Click and drag your modified files into the GitHub upload page. 수정된 파일을 GitHub 업로드 페이지로 드래그합니다.
7. Click the green "Commit changes" button at the bottom of the page. 페이지 하단의 초록색 "Commit changes" 버튼을 클릭합니다.

###### [↑ Top / 위로 가기](/schedule.html#web-programming-application-2023)

---

### 3. Checking the Assignment / 과제 확인

#### Checking on your local computer / 로컬 컴퓨터에서 확인

The most basic method for checking whether your files run correctly is to simply run the file with `node`. 제일 기본적인 방법은 파일을 `node`로 실행하는 것입니다.

1. If you create a function, don't forget to _also_ call that function in the file. 함수를 만들면, 파일에서 _또한_ 해당 함수를 호출하지 않는 것을 잊지 마십시오.
2. Add `console.log()` messages where necessary to be sure the program reaches certain lines of code within the file. 필요한 경우 `console.log()` 메시지를 추가하여 프로그램이 파일 내의 특정 코드 라인에 도달하는지 확인하십시오.
3. Run `node FILENAME` to check that your file runs properly. `node FILENAME`을 실행하여 파일이 제대로 실행되는지 확인하십시오.

Most assignments will include a `/tests` folder that contains testing files for your JavaScript code. 대부분의 과제에는 JavaScript 코드를 테스트하는 테스팅 파일이 포함된 `/tests` 폴더가 있습니다.

To run the included tests: 포함된 테스트를 실행하려면:

1. Open a Terminal window with CTRL + \`. CTRL + \`를 눌러 터미널 창을 엽니다.
2. Be sure that your Terminal is in the correct folder (if not, `cd` to the assignment folder). 터미널이 올바른 폴더에 있는지 확인하십시오 (아니라면, 과제 폴더로 `cd`를 입력하십시오).
3. Run `npm install` to install the developer dependencies, including `jest` which is the testing program. `jest`는 테스트 프로그램이므로 `npm install`을 실행하여 개발자 의존성을 설치하십시오.
4. Run `npm test` to run the tests. `npm test`를 실행하여 테스트를 실행하십시오.

If your tests PASS, congratulations! Be sure to `commit & push` your work back to the assignment repository. 테스트가 통과하면 축하합니다! 작업을 과제 저장소로 다시 `commit & push`하십시오.

If your tests FAIL, carefully read the Error Messages and try to understand what you did wrong, and what results the tests are expecting. 테스트가 실패하면, 에러 메시지를 주의 깊게 읽고 무엇을 잘못했는지, 테스트가 기대하는 결과는 무엇인지 이해하려고 노력하십시오.

#### Checking online with GitHub Actions / GitHub Actions로 온라인에서 확인

You can also check whether your tests pass in the "Actions" tab in your assignment repository online. 또한, 과제 저장소의 "Actions" 탭에서 테스트가 통과하는지 확인할 수 있습니다.

1. First, `commit & push` your files back to the assignment repository. 먼저, 과제 저장소로 파일을 `commit & push`합니다.
2. The GitHub Classroom workflow will automatically run the assignment tests. GitHub Classroom 워크플로우는 자동으로 과제 테스트를 실행합니다.
3. Navigate in your browser to your assignment repository URL. 브라우저에서 과제 저장소 URL로 이동합니다.
4. Click the "Actions" tab (4th tab). "Actions" 탭 (4번째 탭)을 클릭합니다.
5. In the main window, under "Workflow Runs" click the most recently run Workflow to inspect it. 메인 창에서 "Workflow Runs" 아래에 가장 최근에 실행된 워크플로우를 클릭하여 검사합니다.
6. In the left sidebar, under "Summary" click "Autograding". 왼쪽 사이드바에서 "Summary" 아래에 "Autograding"을 클릭합니다.
7. In the main window (now black), click the third arrow down called `Run education/autograding@v1` to inspect the results of the GitHub Workflow tests. 메인 창 (이제 검은색)에서 `Run education/autograding@v1`이라고 불리는 세 번째 아래쪽 화살표를 클릭하여 GitHub 워크플로우 테스트 결과를 검사합니다.

If you want to add a "PASS/FAIL" badge to your README: 만약 "PASS/FAIL" 배지를 README에 추가하려면:

1. In the "Actions" tab, click the most recent Workflow Run. "Actions" 탭에서 가장 최근 워크플로우 실행을 클릭합니다.
2. In the upper right-hand corner, next to the "Re-run jobs" button, click the `...` button. 오른쪽 상단 모서리에서 "Re-run jobs" 버튼 옆에 `...` 버튼을 클릭합니다.
3. Click "Create status badge" to open a popup with the badge Markdown. "Create status badge"를 클릭하여 배지 마크다운이 포함된 팝업을 엽니다.
4. Copy the badge Markdown. 배지 마크다운을 복사합니다.
5. Return to your repository code and list of files (where the README is visible underneath). 저장소 코드와 파일 목록으로 돌아갑니다 (README가 아래에 표시됨).
6. Click the pencil icon to "EDIT" your README file. 펜 모양 아이콘을 클릭하여 README 파일을 "EDIT"합니다.
7. Paste the status badge Markdown code into the top of your README file. 상태 배지 마크다운 코드를 README 파일의 맨 위에 붙여넣습니다.
8. Click the green "Commit changes" button at the bottom of the screen to save. 화면 아래쪽에 있는 초록색 "Commit changes" 버튼을 클릭하여 저장합니다.

###### [↑ Top / 위로 가기](/schedule.html#web-programming-application-2023)
