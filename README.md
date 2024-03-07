# Country Capitals Quiz

This project is a simple quiz application where users can test their knowledge of country capitals. The application is built using Node.js and Express for the backend, and PostgreSQL for storing country-capital pairs.

## Features

- Users can input the capital of a given country for a quiz.
- The application validates user input against the correct capital stored in the database.
- Feedback is provided to the user indicating whether their answer is correct or not.
- Scores are tracked as users answer questions, with the final score displayed at the end of the quiz.
## Setup

1. Clone the repository:

git clone https://github.com/meanmachine889/capital-quiz.git


Copy code

2. Install dependencies:

npm install

3. Set up PostgreSQL:
   - Install PostgreSQL on your system if not already installed.
   - Create a new database named `country_capitals`.
   - Import the provided SQL dump file `country_capitals.sql` to populate the database.

4. Configure database connection:
   - Open `config.js` and update the database connection parameters as needed.

5. Run the application:

nodemon index.js
