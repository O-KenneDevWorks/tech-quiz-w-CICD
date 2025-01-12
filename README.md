# Tech-Quiz

This quiz application provides users with a dynamic quiz experience where they can answer a series of questions, view their score, and retry the quiz if desired. The backend API is built with Express and Node.js, connects to a MongoDB database to fetch quiz questions, and serves the data to a React frontend.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Testing with Cypress](#testing-with-cypress)
- [Demo Video](#demo-video)
- [License](#license)
- [Contact](#contact)

## Features
- Dynamic Question Fetching: Retrieves questions from MongoDB via an Express API.
- Score Tracking: Shows users their score upon completing the quiz.
- Retry Option: Restart the quiz to try again.
- Loading Indicator: Displays a spinner while questions are being fetched.
- Comprehensive Testing: Includes Cypress tests for both End-to-End and Component Testing.

## Technologies Used
- Frontend: React, CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Testing: Cypress

## Getting Started
### Prerequisites
Ensure you have the following installed:

- Node.js (v14 or above)
- MongoDB (local instance or MongoDB Atlas)
- npm (Node package manager)

### Installation
1. **Clone the Repository:**

```bash
git clone https://github.com/O-KenneDevWorks/tech-quiz-w-CICD.git
```

2. **Navigate to Project Directory:**

bash
cd Tech-Quiz

3. **Install Server and Client Dependencies:**

```bash
npm install
```

## Running the Application
### Development Mode

Run Backend and Frontend Together: From the project root, run:

```bash
npm run start:dev
```

This starts both the backend server and the frontend development server. The backend server will run on http://localhost:3001 and the frontend will run on http://localhost:3001 by default.

## Usage
- **Start the Quiz**: Click the "Start Quiz" button to begin.
- **Answer Questions**: Select the answer by clicking the respective button.
- **View Results**: Once all questions are answered, view your score and click "Take New Quiz" to retry.

## Environment Variables
Create a .env file in the root directory and add the following variables:

```plaintext
MONGO_URI=<Your MongoDB connection string>
```

- `MONGO_URI`: Connection URI for MongoDB.

## Testing with Cypress
This project includes Cypress tests for both End-to-End (E2E) and Component Testing.

1. **Start the Server**: Ensure the backend server is running before running tests.

2. **Run Tests with Cypress**:

### E2E Tests
To run only the E2E tests:

```bash
npm run test:e2e
```

### Component Tests
To run only the Component tests:

```bash
npm run test:component
```

### Run All Tests Sequentially
To run both E2E and Component tests sequentially, use:

```bash
npm run test:all
```

## Demo Video

You can watch a demo of the application and test suite [here](https://drive.google.com/file/d/1DKX95XDn9pEYlMdDBEmghcPMURLQYAxE/view).

## License
Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

## Contact Information
For any inquiries or collaborations, please reach out to:

**Owen Kenne**  
GitHub: [O-KenneDevWorks](https://github.com/O-KenneDevWorks)  
Email: okenne.devworks@gmail.com
