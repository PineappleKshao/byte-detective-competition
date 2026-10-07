# Byte Detective Competition

**Crack coded messages, practise Computer Science, and help improve the game.**

Byte Detective is a classroom learning project for Grade 7 students beginning IGCSE Computer Science. Students decode words, arrange them into a sentence, and solve a Unicode symbol clue. The competition has **5 groups and 3 rounds**, with a different message for every group in each round.

Students are welcome to contribute ideas, clearer explanations, bug reports, and small code improvements. Parents are welcome to explore what students are learning and try a round together.

[Project on GitHub](https://github.com/PineappleKshao/byte-detective-competition) · [Ideas and bug reports](https://github.com/PineappleKshao/byte-detective-competition/issues) · [Classroom instructions](START-HERE.md)

## Try the game

1. On the repository page, select **Code → Download ZIP**, then extract the downloaded folder.
2. Open **student-game/index.html** in a web browser.
3. Choose your group and round. In class, wait for your teacher's countdown before pressing **Start**.
4. Decode the five words, arrange the sentence, then solve the final Unicode clue.

There is no installation, terminal command, or Python requirement. The game works offline after downloading. A GitHub account is not needed to play.

The repository page shows the source files; it does not itself run the game. The separate [student-game.zip](student-game.zip) contains only the game: download it, extract it, and open `index.html`.

## What students learn

- Converting between **binary, denary, and hexadecimal**.
- Using **ASCII character codes** to represent letters.
- Recognising **Unicode code points** and symbols.
- Checking answers, showing working, and solving problems with a team.
- Explaining and testing improvements to a shared coding project.

The [printable Word reference sheet](print-for-students/ASCII-reference-sheet.docx) provides letters and their **binary ASCII codes only**. Students work out the denary and hexadecimal conversions themselves. The game's online letter table follows the same approach.

Each group gets five words and 23 letters per round, with the same mix of number systems. The messages and envelope order are prepared in advance and stay fixed for each group and round. Refreshing does not generate a new message. Full scoring and timing rules are in [START-HERE.md](START-HERE.md).

## For parents and carers

This activity helps students connect number systems with something they can read: a message. Ask your child to explain how one group of digits becomes a letter, or how they checked a conversion. The reasoning matters as much as finishing the puzzle.

The app does not ask for a student's name, email address, camera, or microphone. It saves group progress, points, and timing in the browser's local storage when available. It does not send game results to a central server, and there is no shared online leaderboard. The teacher records classroom results separately.

Playing the downloaded game is separate from contributing on GitHub. Students can suggest ideas through their teacher without an account. Any GitHub participation should follow the arrangements agreed by the school and family. Keep public contributions about the project; do not include students' personal details or classmates' work without permission.

## Students are welcome to contribute

You can make a useful contribution without writing code. For example:

- Explain which instruction you found confusing and suggest better wording.
- Report a problem with a button, a clue, or a narrow screen.
- Suggest an accessible colour, label, or keyboard-control improvement.
- Design a new balanced message and show its correct encodings.
- Improve the documentation or a small part of the game.

Before a larger change, discuss your idea in an [issue](https://github.com/PineappleKshao/byte-detective-competition/issues). Check existing issues first to avoid duplicating someone else's work.

### Report a problem

Include your browser, group and round, the steps you followed, what you expected, and what happened. Use a screenshot if it helps, without including personal information.

### Submit a change

1. **Fork** the repository to create your own copy on GitHub.
2. Create a branch with a clear name, such as `improve-puzzle-instructions`.
3. Make one small change. The app's HTML, CSS, and JavaScript are all in `student-game/index.html`.
4. Open your changed game locally and check the affected behaviour. For a README change, check the Markdown preview.
5. Commit your work and push it to your fork if you worked locally.
6. Open a **pull request** to this repository's `main` branch. Explain what you changed, why it helps, and how you tested it.

A pull request lets the project owner review a proposed change before adding it to the shared project. [GitHub's contribution guide](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project) explains the process with examples.

Keep feedback kind and specific. If you work in a group, explain each person's contribution. You should be able to explain the changes you submit.

### Check your changes

For a game change, check what is relevant:

- [ ] The page opens and group/round selection works.
- [ ] Correct answers are accepted, and incorrect answers give useful feedback.
- [ ] Hints, points, and the timer still behave as the instructions describe.
- [ ] Word placement and the Unicode clue still work.
- [ ] The page remains usable on a narrow screen and with a keyboard.
- [ ] Your pull request states what you tested and anything you could not test.

If you change messages, encodings, or rules, identify any corresponding answer-key or instruction changes in your pull request. Keep the reference table binary-only unless the teacher agrees otherwise. Treat `student-game/index.html` as the source to edit; the downloadable ZIP must be refreshed when an updated game is released.

## Folder guide

| File or folder | Purpose |
| --- | --- |
| [student-game/index.html](student-game/index.html) | The playable game and its source code. |
| [student-game.zip](student-game.zip) | A packaged copy for student computers. |
| [print-for-students](print-for-students/) | Printable ASCII reference materials. |
| [teacher](teacher/) | Answer key, teacher instructions, and score sheet. |
| [START-HERE.md](START-HERE.md) | Detailed setup, scoring, and lesson guidance. |

## A note about the answers

The teacher answer key is included in this repository, and the game source also contains the solutions. Anyone with access to the repository can inspect them. The `teacher` folder name does not make its contents private.

For a classroom competition, follow your teacher's instructions and solve the clues before reading the answers or source data. After the round, inspecting the code can be part of the learning. This is a teacher-supervised learning project, not a secure examination system.
