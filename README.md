# INTERACTIVE-QUIZ-APPLICATION

COMPANY: CODTECH IT SOLUTIONS

NAME: Aasim Kader

INTERN ID: CT04DY864

DOMAIN: FRONT END DEVELOPMENT

DURATION: 4 WEEEKS

MENTOR: NEELA SANTOSH

Description of the Quiz Application Code:

This project is a Quiz Application built using HTML, CSS, and JavaScript. It allows users to answer multiple-choice questions, get instant feedback on their answers, and see their final score at the end. The app is fully interactive, user-friendly, and designed to look polished with a clean layout.

1. Structure (HTML)

The HTML part defines the layout of the quiz. It includes:

A container that holds all quiz elements.

A question area where the current question is displayed.

An answer button section where all answer choices are shown as buttons.

A Next button to move to the next question.

A score area to display the user’s final result.

This simple structure makes it easy to dynamically update content using JavaScript.

2. Styling (CSS)

The CSS provides a clean and professional design:

The page uses a centered container with a white background, rounded corners, and a light shadow for a card-like appearance.

Each answer option appears as a styled button with padding, rounded edges, and hover effects.

Correct answers are highlighted in green, and wrong answers in red, so the user gets instant feedback.

The Next button is styled in blue and only appears when needed.

This styling ensures the quiz is both functional and visually appealing.

3. Logic and Interactivity (JavaScript)

The JavaScript acts as the brain of the application. It controls question display, answer checking, and score calculation.

(a) Question Bank

All questions and answers are stored in a JavaScript array. Each question contains text and an array of possible answers, where one is marked correct.

(b) Starting the Quiz

The startQuiz() function resets the score and question index, then displays the first question.

(c) Showing Questions

The showQuestion() function:

Clears old answers.

Loads the current question.

Creates answer buttons dynamically.

Adds click events that allow users to select an answer.

(d) Selecting an Answer

When a user selects an answer:

Correct answers turn green, and the score increases.

Wrong answers turn red.

All buttons are disabled to prevent multiple selections.

The correct answer is highlighted for feedback.

The Next button appears.

(e) Moving to Next Question

The handleNextButton() function increases the question index:

If more questions exist, the next one loads.

If not, the final score is displayed.

(f) Showing the Score

The showScore() function shows the user’s final result.
The Next button is relabeled as Restart, allowing users to retake the quiz.

4. Features

Instant Feedback: Correct/incorrect answers are highlighted immediately.

Scoring System: Tracks and displays user performance.

Dynamic Buttons: Answer buttons are created on the fly, making the quiz flexible.

Restart Option: Users can retry without refreshing the page.

Clean UI: Simple, polished design ensures usability.

5. Flow of the Quiz

The quiz starts with the first question.

The user selects an answer → instant feedback is shown.

The Next button appears → moves to the next question.

After the last question, the score is displayed.

The user can restart the quiz.

Conclusion :

This Quiz Application is a complete front-end project that demonstrates the power of JavaScript for dynamic interactivity.

HTML provides the structure.

CSS adds styling.

JavaScript controls logic and real-time updates.

It can be extended by:

Adding more questions.

Loading questions from a JSON file or API.

Randomizing the order of questions and answers.

In just a small amount of code, this project delivers a fully functional quiz system that is interactive, polished, and educational.

