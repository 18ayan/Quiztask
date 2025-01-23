# Quiztask App

Quiztask is a dynamic and interactive quiz application built with ReactJS, TailwindCSS, and Axios. It provides users with an engaging quiz experience, featuring a timer, easy navigation between questions, and detailed performance reports. Questions are fetched in real-time from the OpenDB API, ensuring a diverse and up-to-date quiz database.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **User Authentication:** Secure credential system to start the quiz.
- **Timer:** Real-time countdown to keep track of quiz duration.
- **Question Navigation:** Easily navigate between different questions.
- **Dynamic Questions:** Questions are fetched from the OpenDB API.
- **Detailed Reports:** Comprehensive performance analysis at the end of the quiz.
- **Responsive Design:** Optimized for various devices using TailwindCSS.

## Demo

![Quiztask Demo](path_to_demo_screenshot_or_gif)

## Technologies Used

- **ReactJS:** Frontend library for building user interfaces.
- **TailwindCSS:** Utility-first CSS framework for styling.
- **Axios:** Promise-based HTTP client for API requests.
- **OpenDB API:** Source of quiz questions.

## Installation

Follow these steps to set up the Quiztask app locally:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/18ayan/Quiztask.git
   cd quizmaster
   ```

2. **Install Dependencies:**

   Ensure you have [Node.js](https://nodejs.org/) installed. Then, install the necessary packages:

   ```bash
   npm install
   ```


3. **Start the Development Server:**

   ```bash
   npm start
   ```

   The app will run on `http://localhost:3000`.

## Usage

1. **Start the Quiz:**
   - Open the application in your browser.
   - Enter your credentials to begin the quiz.

2. **During the Quiz:**
   - A timer will count down the remaining time.
   - Navigate between questions using the provided controls.
   - Answer the questions as they appear.

3. **After the Quiz:**
   - View a detailed report of your performance, including scores and correct answers.

## API Reference

The QuizMaster app utilizes the [OpenDB API](https://opendb.api/) to fetch quiz questions.

### Endpoints

- **Fetch Questions:**

  ```http
  GET https://opendb.api/questions
  ```

  **Parameters:**

  - `category` (optional): Filter questions by category.
  - `difficulty` (optional): Set the difficulty level.

  **Response:**

  ```json
  {
    "questions": [
      {
        "id": 1,
        "question": "What is the capital of France?",
        "options": ["Paris", "Berlin", "Rome", "Madrid"],
        "answer": "Paris"
      },
      ...
    ]
  }
  ```

## Contact

For any inquiries or feedback, please contact:

- **Email:** md18ayan@gmail.com
- **GitHub:** [yourusername](https://github.com/18ayan)

