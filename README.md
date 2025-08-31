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


OUTPUT :

<img width="1366" height="724" alt="Image" src="https://github.com/user-attachments/assets/9a57554a-306e-4cd8-a7c8-3562d3f8a720" />
<img width="1366" height="730" alt="Image" src="https://github.com/user-attachments/assets/55aeeefe-e0c6-412c-85f4-815d3e9ad1b3" />
<img width="1366" height="698" alt="Image" src="https://github.com/user-attachments/assets/4809b27f-e79b-4327-be45-9a045ec72548" />
<img width="1366" height="617" alt="Image" src="https://github.com/user-attachments/assets/f5d58e4f-e585-46d2-82ac-24cbb2a4788f" />
<img width="1366" height="621" alt="Image" src="https://github.com/user-attachments/assets/2df7d144-4b05-4fd8-a3f5-7af4ea6ec4ae" />
<img width="1366" height="630" alt="Image" src="https://github.com/user-attachments/assets/8c61a72e-078d-45fc-836d-abfa49c3b659" />
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/9be8a07d-3b92-41e8-b419-1e185a2d53ca" />
<img width="1366" height="668" alt="Image" src="https://github.com/user-attachments/assets/22aef70d-7097-49db-88aa-395659c2766c" />
