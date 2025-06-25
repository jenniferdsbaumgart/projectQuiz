
# Project Quiz - Programming Quiz Game

This project is a programming quiz game built with React JS and TypeScript. It provides a fun way to test your programming knowledge through different stages of the game, including picking categories, answering questions, and showing tips for help.

## Project Overview

The game is structured into different stages:

    Start: Welcome screen that sets up the game.

    Category: The player selects a category for the quiz.

    Playing: The player answers questions from the selected category.

    End: The game ends, showing the player's score.

## Features

- Multiple Stages: The game progresses through different stages (Start, Category, Playing, and End).
- Dynamic Question Set: Questions are selected based on the category chosen by the user.
- Score Tracking: The game tracks the player's score.
- Answer Checking: The user can select an answer, and the game checks if it is correct.
- Help Option: The user can request a tip, which hides one incorrect option.
- Randomized Questions: The order of questions is randomized to keep the game interesting.
## Tech Stack

**React JS**: For building the user interface.
**TypeScript**: To ensure type safety and improve code quality.
**Context API**: To manage and share the state of the game across components.
**CSS**: For styling the app.
## Project Structure

- App.tsx: The main component that manages the game stages and renders different components based on the game state.
- context/quiz.tsx: Manages the game state and provides it to all components via the Context API.
- components/: Contains all the game components such as Welcome, PickCategory, Question, and GameOver.
- data/: Contains the question data that is used in the quiz.
- App.css: Contains the styles for the app.


## How the Game Works

1. Start: The user is greeted with a welcome message and can choose to start the game.
2. Category: The user selects a category of questions.
3. Playing: The user answers the questions. Each question shows options and allows selecting an answer.
4. End: After answering all questions, the user's score is shown.


## License

This project is licensed under the MIT License – see the LICENSE file for more details.
