# Full-Stack-Interactive-Quiz-Application
This project involves building an interactive quiz application using a combination of powerful technologies, React for the frontend, Spring Boot for the backend, and MySQL for the database
## Features

- Select a technology and quiz from the available options.
- Answer multiple-choice questions for the selected quiz.
- Submit the quiz and view the results.

## Installation

1. Clone the repository
2. Navigate to the frontend directory: `cd quiz-app-frontend`
3. Install the dependencies: `npm install`
  

## Usage

1. Start the React development server: `npm start`
2. Open your browser and visit `http://localhost:3000` to access the Quiz App frontend.

## Configuration

The Quiz App frontend requires the backend API to be running. By default, it expects the backend to be running at `http://localhost:8080`. If your backend is running at a different address, you can update the API endpoint in the `src/api/apiConfig.js` file.

```javascript
// src/api/apiConfig.js

const BASE_URL = "http://localhost:8080/api"; // Update this URL if needed

export default BASE_URL;
```
