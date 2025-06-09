# INTERACTIVE-QUIZ-APPLICATION
COMPANY: CODTECH IT SOLUTIONS
NAME : DUMPALA VENKATA SAI JYOTHSNA
Intern ID :CT04DF335
DOMAIN : Frontend Web Development
DURATION : 4 WEEKS
MENTOR : NEELA SANTOSH
The HTML, CSS, and JavaScript you’ve written combine elegantly to create a polished, interactive quiz application packed with functionality and thoughtful design. Visually, the entire app is centered on the screen, with a dark, modern aesthetic—featuring a deep background and contrasting white text, accented with lively teal buttons. The layout divides the experience into three clear states: a “Start Quiz” button at launch, the quiz interface itself where each question appears, and a final “Result” screen that displays the user's score along with a “Restart” button for replayability.
At its heart is the `quizData` array, storing ten quiz question objects—each with a prompt, a set of four possible answers, and an explicitly correct answer. This structure makes it simple to manage and expand the question set if desired. Once the quiz starts, JavaScript dynamically populates the question and options into the DOM, creating `<li>` elements for each choice and attaching click event listeners to handle user interaction.
Selecting an answer triggers the `selectAnswer` function, which immediately disables further selection to prevent double-clicks and validates the chosen option. A green highlight shows correct selections while incorrect choices are marked in red, and the correct answer is revealed if the user errs. This immediate feedback enhances engagement and learning. After a choice is made (or time runs out), the “Next” button appears, guiding the user through the quiz in a clean, step-by-step progression.
A standout feature of your app is the countdown timer tied to a visual progress bar. Each question resets a 20-second timer that gradually shrinks the green bar from full width to zero. If the timer hits zero before an answer is selected, `autoFail` activates automatically, greying out further interaction and revealing the correct answer in green—ensuring no unanswered questions disrupt the flow. The dynamic progress bar is both informative and visually satisfying, with smooth CSS transitions enhancing user experience.
Once all questions have been attempted, the UI hides the quiz section and displays a “You scored X out of Y” message. This is accompanied by a “Restart” button that resets internal state variables (`currentQuestionIndex`, `score`, progress bar width, and result display), making it straightforward for users to replay the quiz from scratch.
Stylistically, your CSS is clean and purposeful: consistent paddings, rounded corners, responsive width limiting to 600px, shadow effects for depth, and hover states that subtly darken options, signaling interactivity. Buttons share a unified style—teal backgrounds, white text, rounded shapes—that stand out clearly against the darker base palette.
In sum, this “Advanced Quiz App” is a thoughtfully architected, single-page quiz experience that balances visual appeal with functional robustness. It modularizes data, dynamically drives DOM output, manages state cleanly, and incorporates timed interactions with instant feedback—all contributing to a smooth, engaging user experience of well over 500 words worth of design and planning behind the scenes.

OUTPUT:
![Image](https://github.com/user-attachments/assets/06de0632-8515-4e6e-9038-175b57a61fe9)


