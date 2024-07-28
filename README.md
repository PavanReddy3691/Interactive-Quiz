Project Description: Interactive Quiz

This interactive quiz project is a single-page web application designed to test students' knowledge across different subjects and grade levels. It incorporates HTML, CSS, and JavaScript to create a user-friendly, dynamic quiz environment. The quiz allows students from classes 1 to 5 to answer a series of questions and receive immediate feedback on their performance.

Key Features:
User Form:

Purpose: To collect the student's name and class.
Components: A form that includes text input for the student's name and a dropdown menu to select the class (from 1 to 5).
Functionality: On submission, the quiz for the selected class is displayed.

Quiz Content:

Structure: The quiz data is structured in an object where each class has a set of categories, each containing a series of questions and their respective answer choices.
Questions: Each class has 3 questions that cover different topics like Geography, Math, History, and Science.

Timer:

Purpose: To limit the time students have to complete the quiz, adding an element of time-based challenge.
Functionality: The timer starts at 60 seconds and counts down. When the timer reaches zero, the quiz automatically submits and displays the results.

Result Display:

Feedback: After submitting the quiz, the results show the number of correct answers out of the total questions.

Visual Cues: Correct answers are highlighted in green, and incorrect answers are highlighted in red, providing immediate visual feedback.

Reset Button:

Purpose: To allow students to retake the quiz.
Functionality: Resets the timer, clears previous answers, and redisplays the questions for the selected class.
