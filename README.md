# The React Quiz

The React Quiz is build with React with emphasis on using the `useReducer` Hook for learning purposes.

This quiz includes 15 React questions with an interactive UI.

## Features

- **Timer** based on number of questions (30 secs per question)
  - If timer runs out, quiz is placed in `finished` state
- **Progress Bar** is displayed as you interact with quiz
- **Points** are awarded for each questions (points vary by question)
- **Highscore** is calculated at the completion of the quiz
- **Restart** button at the end of the quiz to try again and beat your highscore

## Getting Started

### Installation

1. Clone Repo
2. Install all the NPM Packages, run:
   `npm install`

Questions are loaded from [questions.json](src/data/questions.json) file and fetched through a json server that acts as an API

3. To start json server, run: `npm run server`
   - To view json server API, open browser at http://localhost:8000/questions
4. Run _The React Quiz_ application, run: `npm start`
   - open browser at http://localhost:3000
