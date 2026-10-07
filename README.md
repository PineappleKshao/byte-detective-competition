# Byte Detective Competition · 字节侦探解码挑战赛

**Crack the code. Explain your thinking. Build something together.**

**破解编码，讲清思路，一起完善作品。**

[English](#english) · [简体中文](#simplified-chinese)

[🎮 Download the game · 下载游戏](student-game.zip) · [📖 Classroom guide · 课堂指南](START-HERE.md) · [💡 Ideas and bug reports · 建议与问题反馈](https://github.com/PineappleKshao/byte-detective-competition/issues)

| Audience · 适合对象 | Format · 活动形式 | Access · 使用方式 |
| --- | --- | --- |
| Grade 7/8 · 七八年级 | 5 groups × 3 rounds · 5 组 × 3 轮 | Offline after download · 下载后离线使用 |

<a id="english"></a>

## English

### Welcome to Byte Detective

Byte Detective is a classroom learning project for Grade 7 students beginning IGCSE Computer Science. Students decode words, arrange them into a sentence, and solve a Unicode symbol clue. Each group receives a different message in each round.

Students are welcome to contribute ideas, clearer explanations, bug reports, and small code improvements. Parents and carers are welcome to explore what students are learning and try a round together.

### Get started

1. On the [repository page](https://github.com/PineappleKshao/byte-detective-competition), select **Code → Download ZIP**, then extract the downloaded folder.
2. Open **student-game/index.html** in a web browser.
3. Choose your group and round. In class, wait for your teacher's countdown before pressing **Start**.
4. Decode the five words, arrange the sentence, then solve the final Unicode clue.

No installation, terminal commands, Python, or GitHub account are needed to play. The game works offline after downloading.

The repository page shows the project files; it does not itself run the game. If you only want the game, download [student-game.zip](student-game.zip), extract it, and open `index.html`.

### What students learn

- Converting between **binary, denary, and hexadecimal**.
- Using **ASCII character codes** to represent letters.
- Recognising **Unicode code points** and symbols.
- Checking answers, showing working, and solving problems as a team.
- Explaining and testing improvements to a shared coding project.

The [printable Word reference sheet](print-for-students/ASCII-reference-sheet.docx) provides letters and their **binary ASCII codes only**. Students work out the denary and hexadecimal conversions themselves. The game's online letter table follows the same approach.

Each group gets five words and 23 letters per round, with the same mix of number systems. Messages and envelope order are prepared in advance and stay fixed for each group and round. Refreshing does not generate a new message. Full scoring and timing rules are in [START-HERE.md](START-HERE.md).

### For parents and carers

This activity connects number systems with something students can read: a message. Ask your child to explain how a group of digits becomes a letter, or how they checked a conversion. Understanding the process matters as much as finishing the puzzle.

**Privacy and progress.** The app does not ask for a student's name, email address, camera, or microphone. It saves group progress, points, and timing in the browser's local storage when available. It does not send game results to a central server, and there is no shared online leaderboard. The teacher records classroom results separately.

**Taking part on GitHub.** Playing the downloaded game is separate from contributing on GitHub. Students can suggest ideas through their teacher without an account. GitHub participation should follow the arrangements agreed by the school and family. Keep public contributions about the project; do not include students' personal details or classmates' work without permission.

### Contribute to the project

You can help without writing code. For example:

- Suggest clearer wording for an instruction you found confusing.
- Report a problem with a button, a clue, or a narrow screen.
- Improve accessible colours, labels, or keyboard controls.
- Design a new balanced message and show its correct encodings.
- Improve the documentation or a small part of the game.

Before a larger change, discuss your idea in an [issue](https://github.com/PineappleKshao/byte-detective-competition/issues). Check existing issues first to avoid duplicating someone else's work.

#### Report a problem

Include your browser, group and round, the steps you followed, what you expected, and what happened. A screenshot can help, but leave out personal information.

#### Submit a change

1. **Fork** the repository to create your own copy on GitHub.
2. Create a branch with a clear name, such as `improve-puzzle-instructions`.
3. Make one small change. The app's HTML, CSS, and JavaScript are all in `student-game/index.html`.
4. Open your changed game locally and check the affected behaviour. For a README change, check the Markdown preview.
5. Commit your work and push it to your fork if you worked locally.
6. Open a **pull request** to this repository's `main` branch. Explain what you changed, why it helps, and how you tested it.

A pull request lets the project owner review a proposed change before adding it to the shared project. [GitHub's contribution guide](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project) explains the process with examples.

Keep feedback kind and specific. If you work in a group, explain each person's contribution. You should be able to explain the changes you submit.

#### Before submitting

For a game change, check what is relevant:

- [ ] The page opens and group/round selection works.
- [ ] Correct answers are accepted, and incorrect answers give useful feedback.
- [ ] Hints, points, and the timer behave as the instructions describe.
- [ ] Word placement and the Unicode clue work.
- [ ] The page remains usable on a narrow screen and with a keyboard.
- [ ] Your pull request states what you tested and anything you could not test.

If you change messages, encodings, or rules, identify any corresponding answer-key or instruction changes in your pull request. Keep the reference table binary-only unless the teacher agrees otherwise. Edit `student-game/index.html` as the source; the downloadable ZIP must be refreshed when an updated game is released.

### Files and folders

| File or folder | Purpose |
| --- | --- |
| [student-game/index.html](student-game/index.html) | The playable game and its source code. |
| [student-game.zip](student-game.zip) | A packaged copy for student computers. |
| [print-for-students](print-for-students/) | Printable ASCII reference materials. |
| [teacher](teacher/) | Answer key, teacher instructions, and score sheet. |
| [START-HERE.md](START-HERE.md) | Detailed setup, scoring, and lesson guidance. |

### Learning fairly

The teacher answer key is included in this repository, and the game source also contains the solutions. Anyone with repository access can inspect them. The `teacher` folder name does not make its contents private.

During a classroom competition, follow your teacher's instructions and solve the clues before reading the answers or source data. After the round, inspecting the code can be part of the learning. This is a teacher-supervised learning project, not a secure examination system.

[Read in Chinese · 阅读中文版 ↓](#simplified-chinese)

---

<a id="simplified-chinese"></a>

## 简体中文

### 欢迎来到字节侦探

字节侦探是一项面向七年级学生的课堂学习项目，帮助学生入门 IGCSE 计算机科学。学生需要解码单词、把单词排列成句子，再破解一道 Unicode 符号线索。比赛共有 **5 个小组、3 轮挑战**，每组在每一轮都会收到不同的信息。

欢迎学生提出建议、改进说明、反馈问题，或尝试小幅修改代码。也欢迎家长了解孩子正在学习的内容，与孩子一起体验一轮挑战。

### 如何开始

1. 打开 [GitHub 项目页面](https://github.com/PineappleKshao/byte-detective-competition)，点击 **Code → Download ZIP**，然后解压下载的文件。
2. 使用浏览器打开 **student-game/index.html**。
3. 选择自己的小组和轮次。课堂比赛时，请等待老师倒数后，再点击 **Start**。
4. 解码五个单词，排列出正确的句子，最后完成 Unicode 符号挑战。

使用游戏**不需要安装软件、输入终端命令、安装 Python，也不需要 GitHub 账号**。下载后可以离线使用。

GitHub 项目页面用于展示文件，不会直接运行游戏。如果只需要游戏，可以下载 [student-game.zip](student-game.zip)，解压后打开其中的 `index.html`。

### 学生将学到什么

- **二进制、十进制和十六进制**之间的转换。
- 使用 **ASCII 字符编码**表示字母。
- 认识 **Unicode 码点**及其对应的符号。
- 检查答案、展示计算过程，并与组员合作解决问题。
- 说明自己对项目的改进，并测试修改是否有效。

[可打印的 Word 参考表](print-for-students/ASCII-reference-sheet.docx)仅提供**字母及其二进制 ASCII 编码**。十进制和十六进制的转换需要学生自己完成。游戏内的字母参考表也采用相同设计。

每组每轮都有五个单词，共 23 个字母，各种进制的题量分配一致。信息和信封顺序已预先安排；同一小组、同一轮次的题目保持不变，刷新页面不会生成新题。完整的计分和计时规则见 [START-HERE.md 英文课堂指南](START-HERE.md)。

### 给家长和监护人的说明

这项活动将抽象的进制知识与学生能够读懂的信息联系起来。您可以请孩子解释：一组数字怎样变成一个字母？他们是怎样检查转换结果的？理解过程与完成挑战同样重要。

**隐私与学习进度。** 游戏不要求填写学生姓名或邮箱，也不需要使用摄像头或麦克风。浏览器允许时，游戏会在本地保存小组进度、分数和用时。游戏结果不会发送到中央服务器，也没有跨设备共享的在线排行榜。课堂成绩由老师另行记录。

**参与 GitHub 项目。** 使用下载后的游戏与在 GitHub 上贡献代码是两件事。没有 GitHub 账号的学生，也可以通过老师提交建议。学生参与 GitHub 应遵循学校与家庭商定的安排。公开提交的内容应围绕项目本身；请勿擅自上传学生个人信息或同学的作品。

### 如何参与改进

即使暂时不会编程，也可以作出有价值的贡献，例如：

- 指出不易理解的说明，并提出更清楚的表达方式。
- 反馈按钮、线索或小屏幕显示方面的问题。
- 改进配色、标签或键盘操作，让更多人方便使用。
- 设计难度均衡的新信息，并给出正确的编码。
- 完善项目文档，或修改游戏中的一个小功能。

较大的修改建议先通过 [Issue 问题与建议区](https://github.com/PineappleKshao/byte-detective-competition/issues)讨论。提交前先查看已有内容，避免重复工作。

#### 反馈问题

请写明使用的浏览器、小组和轮次、操作步骤、预期结果，以及实际发生的情况。可以附上截图，但请不要包含个人信息。

#### 提交修改

1. 点击 **Fork**，在自己的 GitHub 账号下创建项目副本。
2. 新建一个名称清楚的分支，例如 `improve-puzzle-instructions`。
3. 先完成一项小修改。游戏的 HTML、CSS 和 JavaScript 都在 `student-game/index.html` 中。
4. 在自己的电脑上打开修改后的游戏，检查相关功能。如果只修改 README，请检查 Markdown 预览。
5. 提交修改（Commit）；如果在本地编辑，再将分支推送（Push）到自己的 Fork。
6. 向本项目的 `main` 分支发起 **Pull Request（合并请求）**，说明修改了什么、有什么帮助，以及如何测试。

Pull Request 让项目维护者能够先检查修改，再决定是否合并。[GitHub 官方贡献指南](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project)提供了具体示例。

交流时请友善、具体。如果以小组形式完成，请说明每位成员的贡献。提交者应能够解释自己所做的修改。

#### 提交前检查

修改游戏后，请根据涉及的功能进行检查：

- [ ] 页面能够打开，小组和轮次选择正常。
- [ ] 正确答案能够通过，错误答案会得到清楚的反馈。
- [ ] 提示、分数和计时器符合说明中的规则。
- [ ] 单词排列和 Unicode 符号挑战正常。
- [ ] 小屏幕和键盘操作仍然可用。
- [ ] Pull Request 中写明了测试内容，以及尚未测试的部分。

如果修改了信息、编码或规则，请在 Pull Request 中说明答案文件或说明文档需要怎样同步更新。除非老师同意，请保留仅含二进制的字母参考表。修改游戏时以 `student-game/index.html` 为源文件；发布更新版本时，也需要重新打包供下载的 ZIP 文件。

### 文件与文件夹

| 文件或文件夹 | 用途 |
| --- | --- |
| [student-game/index.html](student-game/index.html) | 可以运行的游戏及其源代码。 |
| [student-game.zip](student-game.zip) | 便于分发到学生电脑的游戏压缩包。 |
| [print-for-students](print-for-students/) | 可打印的 ASCII 参考资料。 |
| [teacher](teacher/) | 教师答案、教学说明和计分表。 |
| [START-HERE.md](START-HERE.md) | 英文版详细设置、计分规则与课堂活动建议。 |

### 公平参与与课后探索

本仓库包含教师答案，游戏源代码中也包含题目解答。任何能够访问仓库的人都可以查看；文件夹命名为 `teacher` 并不代表其中内容受到访问限制。

课堂比赛时，请按照老师的要求先独立或合作解题，再查看答案或源数据。比赛结束后，阅读代码也可以成为学习的一部分。本项目用于教师指导下的课堂学习，不是用于保密考试的系统。

[Back to English · 返回英文版 ↑](#english)
