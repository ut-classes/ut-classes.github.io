<p id="menu" align="center">
  <a href="https://ut-nodejs.github.io" title="Home">🏠</a> |
  <a href="about.html" title="About">개요</a> |
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

## Instructions for working with assignments

![3rd-week-PPT](/img/gh-pages/3rd-week-PPT.png)

These instructions were presented in the 3rd week with the following PPT. For pictures to accompany the directions, [click here to download the PDF](https://github.com/ut-nodejs/ut-nodejs.github.io/raw/master/slides/_3.%20%EA%B3%BC%EC%A0%9C%20%EB%AC%B8%EC%A0%9C%EC%99%80%20%ED%95%B4%EA%B2%B0.pdf).

(Korean translation forthcoming...)

There are 3 major issues to address when completing assignments.

1. [Accessing the assignment](#1-accessing-the-assignment)
2. [Turning in the assignment](#2-turning-in-the-assignment)
3. [Checking the assignment](#3-checking-the-assignment)

However, before even accessing the assignment, please be sure the following programs are installed on your computer. (Installing the programs in this order will be beneficial as some of the software checks if other software has already been installed)

1. [VS Code](https://code.visualstudio.com/) (Also, you can install the [GitHub Classroom Extension]() in VS Code after its installed)
2. [Git](https://git-scm.com/) (When the installation screen comes to the "default preferred text editor," you can select VS Code as the default if it's been previously installed)
3. [Node.JS](https://nodejs.org/ko) (Be sure to also install the "optional" tools like Chocolatey if you are using Windows)

After the software is installed, you will be able to access and complete the assignments.

### 1. Accessing the Assignment

#### Preferred Method (EASY WAY)

All assignments will be accessible from the [homepage](https://ut-nodejs.github.io/practice.html) from the start of each class. To access the assignment:

1. Click the Assignment link for your class (**오전** or _오후_)
2. On the GitHub Classroom page, "Accept assignment" to create your personal respository
3. Refresh the page
4. Click "Open in VS Code" to automatically clone the repository to your local computer and open it

If VS Code does NOT properly clone and open your repository to your local computer, you may try the following solutions.

#### Alternative Method 1: `git clone`

1. Make sure you have created a personal folder for YOUR assignments on your computer's Desktop with your <USERNAME>
2. Click the link to your personal respository (or go to [github.com/ut-nodejs](http://github.com/ut-nodejs) to find your assignment and open it)
3. Copy your assignment repository's URL
4. Open Git Bash
5. Type `cd ~/Desktop/<USERNAME>` to navigate to your personal folder on the Desktop
6. Type `git clone <URL>` to download your assignment to your personal directory (type SHIFT + INS to paste the URL you copied)
7. Type `cd <ASSIGNMENT>` to move into the newly cloned git directory
8. Type `code .` to open the assignment in VS Code

#### Alternative Method 2: Direct Download

1. Make sure you have created a personal folder for YOUR assignments on your computer's Desktop with your <USERNAME>
2. Click the link to your personal respository (or go to [github.com/ut-nodejs](http://github.com/ut-nodejs) to find your assignment and open it)
3. Click the green "Code" button in the upper-right hand corner of the repository above the list of files
4. Click "Download ZIP" and save the files to your Desktop
5. Unzip the assignment files
6. Open VS Code
7. Click and drag the assignment folder into VS Code

###### [↑ Top / 위로 가기](/schedule.html#web-programming-application-2023)

---

### 2. Turning in the Assignment

#### Preferred Method (EASY WAY)

The easiest way to submit assignments is by performing a `commit & push` directly from within VS Code.

1. Edit your files (1st tab)
2. Save (so the circle in your file's title disappears)
3. Click the Git tab (3rd tab)
4. In the Message box, write an appropriate message describing WHAT you coded (how you changed the files). Without the message, you cannot `commit & push.` Some examples of good and bad commit messages are shown below. Good messages are short and descriptive. Bad messages not specific or meaningless.
   - Good: `Added a new menu bar`
   - Good: `Removed contact form functionality`
   - Bad: `Done`
   - Bad: `asdfjkl;`
5. After writing a descriptive commit message, click the down arrow on the `commit` button and choose `commit & push`
6. Click "Yes" on any additional popups

The above is the **preferred** method to turn in assignments, but sometimes, you may not be able to for various reasons:

- A different student's git id is registered on that computer
- A different student's git id is linked to that VS Code
- A different student's assignment repository is linked
- You were unable to `git clone` the assignment and had to do a direct download instead
- Your git `user.name` and `user.email` are not set (you will see a popup error message). In this case, simply set your git id on that computer and try your `commit & push` again.
  1. Open Git Bash
  2. Type `git config --global user.name "Your name"`
  3. Type `git config --global user.email yourgithub@email.com`
  4. Try your `commit & push` in VS Code again

In the above cases where you can't submit your assignment in the preferred method, you may try one of the alternatives listed below:

#### Alternative 1: Command Line (after `git clone`)

If another student's account is linked through VS Code, you may try pushing your code directly from the Git Bash command line. (Note that this method will _only_ work if you have also used the command line to `git clone` your repository to your Desktop).

1. Open Git Bash
2. Type `~/Desktop/USERNAME/ASSIGNMENT` to navigate to your assignment repository
3. Type `git add *` to prepare all your modified files to save
4. Type `git commit -m "COMMIT MESSAGE"` to save all your modified files
5. Type `git push origin main` to push your files back to GitHub Classroom online

#### Alternative 2: Direct Upload

If all of the above methods have failed, you may try a direct upload of your modified files.

1. Open your GitHub assignment respository at [github.com/ut-nodejs](https://github.com/ut-nodejs)
2. Click "Add file" to the left of the green "Code" button above your list of files
3. Click "Upload files" to open the upload page
4. Navigate to your assignment respository that is stored on your computer's Desktop
5. Select all your modified files (with CTRL) that need to be uploaded
6. Click and drag your modified files into the GitHub upload page
7. Click the green "Commit changes" button at the bottom of the page

###### [↑ Top / 위로 가기](/schedule.html#web-programming-application-2023)

---

### 3. Checking the Assignment

#### Checking on your local computer

The most basic method for checking whether your files run correctly is to simply run the file with `node`.

1. If you create a function, don't forget to _also_ call that function in the file
2. Add `console.log()` messages where necessary to be sure the program reaches certain lines of code within the file
3. Run `node FILENAME` to check that your file runs properly

Most assignments will include a `/tests` folder that contains testing files for your JavaScript code. To run the included tests:

1. Open a Terminal window with CTRL + \`
2. Be sure that your Terminal is in the correct folder (if not, `cd` to the assignment folder)
3. Run `npm install` to install the developer dependencies, including `jest` which is the testing program
4. Run `npm test` to run the tests

If your tests PASS, congratulations! Be sure to `commit & push` your work back to the assignment repository.<br>
If your tests FAIL, carefully read the Error Messages and try to understand what you did wrong, and what results the tests are expecting.

#### Checking online

You can also check whether your tests pass in the "Actions" tab in your assignment repository online.

1. First, `commit & push` your files back to the assignment repository
2. The GitHub Classroom workflow will automatically run the assignment tests
3. Navigate in your browser to your assignment repository URL
4. Click the "Actions" tab (4th tab)
5. In the main window, under "Workflow Runs" click the most recently run Workflow to inspect it
6. In the left sidebar, under "Summary" click "Autograding"
7. In the main window (now black), click the third arrow down called `Run education/autograding@v1` to inspect the results of the GitHub Workflow tests

If you want to add a "PASS/FAIL" badge to your README:

1. In the "Actions" tab, click the most recent Workflow Run
2. In the upper right-hand corner, next to the "Re-run jobs" button, click the `...` button
3. Click "Create status badge" to open a popup with the badge Markdown
4. Copy the badge Markdown
5. Return to your repository code and list of files (where the README is visible underneath)
6. Click the pencil icon to "EDIT" your README file
7. Paste the status badge Markdown code into the top of your README file
8. Click the green "Commit changes" button at the bottom of the screen to save

###### [↑ Top / 위로 가기](/schedule.html#web-programming-application-2023)
