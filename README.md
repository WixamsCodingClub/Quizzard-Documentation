# Quizzard Documentation

Welcome documentation for the Quizzard app being built across multiple repositories within the Wixams Coding Club.

Quizzard is a quiz app being built on different platforms to help people in the club learn how to program. Currently apps are being built on the following platforms, the repositories will be added here in due course:

* Android
* iOS
* Flutter

The Quizzard app is very simple, it's a quiz game where the user is asked a series of multi-choice questions and after completing the game they are shown their score. 

When the app launches the user is shown a Welcome screen which includes a button to start the quiz. The questions are obtained from a public API available on the internet and displayed in turn to the user on the Question screen. Once all the questions have been answered the user’s score is displayed on the Results screen. From there the user can choose to start a new quiz. By default the API returns 10 questions so for the basic version of the app the quiz contains 10 questions.

## Functionality
There are three screens which make up the core functionality of Quizzard, each are discussed below:

* Welcome screen
* Question screen
* Results screen

### Welcome Screen
The Welcome screen is the first screen displayed to the user when the application launches. It includes some information to welcome the user into the app, and a button to let them start a new quiz.

Requirements:
1. Displays the app name 'Quizzard'.
2. Shows a welcome message" "Welcome to Quizzard, please tap the Start New button to start".
3. Displays a 'New Quiz' button.
4. When the 'New Quiz' button is tapped the Quaetion screen show be displayed with the first question.

### Question Screen
The Question screen is a reusable screen which displays each of the questions in turn and allows the user to select their preferred answer. The user is shown the question and available answers, they choose an answer and the app displays whether they got the question right or not. A 'Next Question' button is enabled when the answer has been selected which takes the user to the next question. When all questions have been answered the 'Finish Quiz' button takes to the Results screen.

Requirements:
1. The question number and total number of questions is displayed, e.g. "1/10"
2. The question is displayed.
3. Buttons are shown for each of the available answers, normally 4.
4. A 'Next Question' button is displayed for all except the last question. This button is disabled until the question has been answered.
5. A 'Finish Quiz' button is displayed for the last question. This button is disabled until the question has been answered.
6. When the user selects an answer the screen displays whether the user got the answer right or not, showing the correct answer if they got it wrong.
7. When the user taps the 'Next Question' button the next question is displayed.
8. When the user taps the 'Finish Quiz' button the Results screen is displayed.

> [!NOTE]
> The Question screen can be used in one of two ways. The screen can be updated with each new question, or a new instance of the screen loaded for each question.

### Results Screen
The Results screen shows the user how well they did in the quiz and displays a button which returns the user to the Welcome screen.

Requirements:
1. The user's score is displayed to them including:
	1. Number of questions
	2. Correct answers
	3. Score as a percentage
2. A 'End Quiz' button is displayed.
3. When the user taps the 'End Quiz' button they are returned to the Welcome screen from where they can start a new quiz.

## Extra optional functionality 


## User Interface


## Assets


## Dependencies
The app obtains its question data from The Trivia API, which is free for non commercial use:

[The Trivia API](https://the-trivia-api.com)

The `questions` endpoint returns a random set of questions:

https://the-trivia-api.com/v2/questions

Parameters can be included to define things like the number of questions or the categories but it can be used with its default options. For example 10 questions are returned across all categories and difficulties.

## Architecture
The architecture used is dependant on the platform and technology used. It is defined in each of the repositories for this project.
