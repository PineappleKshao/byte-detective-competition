# Byte Detective classroom competition

For 20 students working in 5 groups. This is a new competition edition; the original secret-announcement game is still available in its original folder.

## What to open

- **student-game/index.html** — the complete offline game and its source code. Double-click to open in a browser.
- **teacher/Competition-answer-key.docx** — teacher instructions, score sheet, and answers for every group in all three rounds. Keep this document with the teacher.
- **print-for-students/ASCII-reference-sheet.docx** — one-page A4 reference with uppercase letters, binary ASCII codes and the Unicode seal lookup. Print 10 copies for one per pair, or 5 for one per group.
- **student-game.zip** — only the student game, ready to copy to student laptops. Extract and open index.html.

## Run a round

1. Copy the student game to each group's laptop. The same file contains all group assignments. A localhost preview link works only on the computer running that preview; give students the file itself.
2. Assign groups 1–5 and announce round 1, 2 or 3. Use one browser tab per group.
3. Students select their assigned group and round. Start together on your countdown.
4. Students convert denary and hexadecimal character codes to binary, use the binary-only reference to decode five words, assemble a sentence, and choose the correct Unicode seal. They can use the printed reference or online handbook for free.
5. Record each group's final points and elapsed time on the teacher score sheet. There is no live scoreboard shared between laptops.
6. Rotate roles and announce the next round. Scores rank first; lower elapsed time breaks a tie. For an overall winner, total the points and elapsed times over the same completed rounds.

## How messages change

There are **15 different messages: 5 groups × 3 rounds**. Words, message assignments and envelope order were shuffled when the set was generated. Selecting another group or round gives another case. Refreshing does not reroll a case. The prepared cases stay fixed so every answer matches the printed Word key.

Every message has five words and 23 letters. Each case has 11 binary-coded letters, 9 hex-coded letters and 3 denary-coded letters. This balances the decoding workload, although familiarity with particular words can still differ. The final Unicode seal changes with each round.

## Points and time

- Five words: 100 points each.
- Correct sentence: 50 points.
- Correct Unicode seal: 50 points.
- First-letter hint: minus 10, charged once per envelope.
- Wrong word, sentence or symbol check: minus 5 each.
- Blank word input: no penalty.
- Maximum: 600 per round; minimum: 0.

The timer starts when Start is pressed and stops on the correct final seal. It keeps running if students refresh, switch tabs, or leave a started round. A completed score and time remain fixed. Local storage keeps separate progress for each group and round when the browser permits it. Use the same browser and address to resume. For a new class, choose a group and round and press Clear saved round before starting.

## Lesson pacing

Try 10 minutes of modelling, 3 rounds of roughly 10–15 minutes with brief role changes, then student-created codes and a short debrief. Adjust after the first round. Students who already know ASCII lookups may finish considerably faster.

This is a teacher-supervised classroom activity, not a secure exam platform. The game runs entirely locally and contains its solutions in the JavaScript. Do not distribute the teacher folder with student copies.
