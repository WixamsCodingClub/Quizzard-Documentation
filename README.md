# Quizzard Documentation

Welcome documentation for the Quizzard app being built across multiple repositories within the Wixams Coding Club.

Quizzard is a quiz app being built on different platforms to help people in the club learn how to program. Currently apps are being built on the following platforms, the repositories will be added here in due course:

* Android
* iOS
* Flutter

The Quizzard app is very simple, it's a quiz game where the user is asked a series of multi-choice questions and after completing the game they are shown their score. 

When the app launches the user is shown a Welcome screen which includes a button to start the quiz. The questions are obtained from a public API available on the internet and displayed in turn to the user on the Question screen. Once all the questions have been answered the user’s score is displayed on the Results screen. From there the user can choose to start a new quiz. 


## Functionality
There are three screens which make up the core functionality of Quizzard, each are discussed below:

* Welcome screen
* Question screen
* Results screen


## Extra optional functionality 


## User Interface


## Assets


## Dependencies
The app obtains its question data from The Trivia API, which is free for non commercial use:

[The Trivia API](https://the-trivia-api.com]

The 'questions' endpoint returns a random set of questions:

'https://the-trivia-api.com/v2/questions'

Parameters can be included to define things like the number of questions or the categories but it can be used with its default options. For example 10 questions are returned across all categories and difficulties.


## Architecture
