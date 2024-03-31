# Quiz App

This is a quiz app built using the MERN (MongoDB, Express.js, React.js, Node.js) stack.

## Features

- User authentication and authorization
- Create, edit, and delete quizzes
- Take quizzes and view results
- Leaderboard to track top scorers
- Admin panel to manage quizzes and users

## Technologies Used

- MongoDB: Database for storing quiz data and user information
- Express.js: Backend framework for handling API requests
- React.js: Frontend library for building the user interface
- Node.js: JavaScript runtime environment for running the server
- Redux: State management library for React.js
- Bootstrap: CSS framework for styling the app

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB installed and running

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/quiz-app.git
    ```

2. Install the dependencies:

    ```bash
    cd quiz-app
    npm install
    ```

3. Set up the environment variables:

    - Create a `.env` file in the root directory
    - Add the following variables:

      ```plaintext
      MONGODB_URI=your-mongodb-uri
      JWT_SECRET=your-jwt-secret
      ```

4. Start the development server:

    ```bash
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000` to access the app.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).