# World Capital Quiz

A web application that quizzes users on world capitals. This project is built with Node.js, Express, PostgreSQL, and EJS for templating.

## Features

- Presents random country names and expects their capitals.
- Tracks the user's correct answers and updates the score in real-time.

## Technologies Used

- **Node.js** and **Express**: For building the server and handling routes.
- **PostgreSQL**: Used as the database to store country and capital information.
- **EJS**: Templating engine for rendering dynamic HTML.
- **body-parser**: Middleware to parse form data.
- **dotenv** (recommended): For managing sensitive database credentials in environment variables.

## Setup and Installation

1. **Clone the repository:**
```
git clone https://github.com/paridhi3/World-Capital-Quiz.git   
cd World-Capital-Quiz
```

2. **Install dependencies:**

```
npm install
```

3. **Configure Environment Variables:**

- Create a .env file in the root of the project and add your PostgreSQL database credentials:
```
DB_USER=yourUsername
DB_HOST=localhost
DB_DATABASE=world
DB_PASSWORD=yourPassword
DB_PORT=5432
```
- Ensure .env is listed in .gitignore to keep it private.

4. **Create Database and Table:** Create a PostgreSQL database named `world`.<br>
Add a capitals table with columns for country and capital data.

5. **Run the Application:**
```
node index.js
```
The app will be available at `http://localhost:3000`.