# 🧠 React Quiz Web App

This project is a simple and interactive React-based quiz web application. It allows users to test their knowledge through a series of questions, providing immediate feedback on their answers. The application leverages a fake API created with `json-server` to simulate a backend, making it easy to set up and run locally.

<br>

---

## ✨ Features

- **Interactive Quiz Interface**: Engage with questions and select answers.
- **Instant Feedback**: See if your answer is correct or incorrect immediately.
- **Score Tracking**: Keep track of your performance throughout the quiz.
- **Dynamic Content**: Questions are fetched from a local JSON server.
- **Responsive Design**: Enjoy a seamless experience on various devices.

<br>

---

## 🛠️ Technologies Used

For this project, the core technologies are:
<br>

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
<br>
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/)
[![JSON Server](https://img.shields.io/badge/json--server-333333?style=for-the-badge&logo=json&logoColor=white)](https://github.com/typicode/json-server)

<br>

---

## 🚀 Getting Started

Follow these steps to get the project up and running on your local machine.

### Prerequisites

- Make sure you have **Node.js** and **npm** installed on your system. You can download Node.js (which includes npm) from [nodejs.org](https://nodejs.org/en/download/).

### Installation

1.  Clone the repository and navigate into the project folder:

    ```bash
    git clone [your-repository-url]
    cd [your-project-folder]
    ```

2.  Install the necessary dependencies:
    ```bash
    npm install
    ```

### Running the Application

1.  **Start the Fake API Server** 🗄️

    - In your terminal, run the following command to start the fake API that serves the quiz questions. This server will typically run on `http://localhost:8000`. Keep this terminal running.

    ```bash
    npm run server
    ```

2.  **Start the React App** ⚛️
    - Open a **new terminal window** and run the following command to launch the React development server. This will open the application in your browser at `http://localhost:3000`.
    ```bash
    npm start
    ```

<br>

---

## 🎮 Usage

Once the application is running, you can:

- View the quiz questions presented.
- Select an answer for each question.
- Receive immediate feedback on whether your answer is correct.
- See your final score at the end of the quiz.
