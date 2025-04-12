# Quiz Application

A full-stack quiz application built with Express.js and EJS templating engine.

## Features

| Feature | Contributer(s) |
|-------------------------------------|-----|
| User Authentication (Login/Signup) | Hamza |
| Random quiz questions with timer | Anthony, Hamza |
| Multiple-choice questions with visual feedback | Anthony, Hamza, Arun, Justin |
| Score tracking and history | Hamza, Justin |
| Responsive design with modern CSS | Hamza, Justin |

## Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: HTML, CSS, JavaScript
- **Templating**: EJS
- **Data Storage**: Local JSON files

## Installation

1. Clone the repository
2. Install dependencies:
```
npm install
```
3. Start the development server:
```
npm run dev
```
4. Open your browser and navigate to `http://localhost:3000`

## User Instructions

### Authentication
- Register with a username and password
- Login with your credentials

### Taking a Quiz
1. After logging in, set your preferred timer duration
2. Answer each question before the timer runs out
3. Receive immediate feedback on your answers (✅ correct, ❌ incorrect)
4. View your final score and question review at the end
5. Check your score history in the "My Scores" section

## Project Structure

- `server.js` - Main application entry point
- `routes/` - Express route handlers
- `views/` - EJS templates
- `public/` - Static assets (CSS, client-side JavaScript)
- `data/` - JSON data files (users.json, questions.json)
- `utils/` - Utility functions

## Development

Run the development server with auto-restart on file changes:
```
npm run dev
```

## Production

Start the production server:
```
npm start
```
