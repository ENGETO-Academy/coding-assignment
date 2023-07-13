## Task Assignment: Assessment Test Environment Creation

### Objective:
> The candidate is required to create an assessment test environment using React, Node.js, Docker, and integrate OpenAI for generating questions. The environment should allow users to take a timed test, save their answers to a database, and display their test results at the end.

### Requirements:
Use React to build a user interface for the assessment test environment. The UI should include a timer, question display area, answer input area, and a submit button.
1. Implement a Node.js backend that handles the API requests from the React front-end using GraphQL / gRPC.
1. Implement a database (e.g., MySQL, PostgreSQL, or any other suitable database) to store the questions, answers, and user results.
1. Create list of 5-10 questions with 4 answers that would be server to the user and store it in DB.
1. Users should be able to select answers to the questions displayed and submit their responses.
1. Store the user's answers in the database.
1. Calculate and display the user's test results at the end of the test, showing the number of correct and incorrect answers.
1. Implement appropriate error handling and validation throughout the application (where applicable).
1. Utilize Docker to containerize the application.
1. BONUS: Ensure the application is responsive, user-friendly, and follows best practices for code quality and organization.
1. BONUS:Integrate OpenAI to generate 10 questions based on the provided input data. The questions should be fetched from OpenAI's API and displayed to the user.
1. BONUS: If the student had fails in certain areas (e.g. conditions in Python), provide some qualitative feedback and what should the person focus more = where the student failed.
1. BONUS: Create either unit tests with Jest or E2E tests with cypress.io

Additional information
1. Feel free to deploy the application on Vercel.app
1. We’d like to see your development process, so feel free to commit a lot with descriptive information about code changes (= don’t squash commits)

### Design requirements:
* [https://www.figma.com/file/AaPcx1f7Q1EOA1gkAXjAVZ/Task-for-developer?type=design&node-id=0-1&mode=design&t=SHerj8pgeQqWolOf-0 ](https://www.figma.com/file/AaPcx1f7Q1EOA1gkAXjAVZ/Task-for-developer?type=design&node-id=0-1&mode=design)

### Deliverables:
The candidate should provide the following:
1. Source code for the React front-end, Node.js backend, and any other necessary components.
1. A brief explanation of the technologies and libraries chosen and the reasoning behind those choices in README file

Please note that the above task assignment is a high-level overview, and you may need to provide additional details, specifications, or requirements based on your specific needs and project environment.
