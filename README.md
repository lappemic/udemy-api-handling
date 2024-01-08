# Taco Recipe API Project

## Description

This project is a web application that allows users to select their favorite taco ingredient and receive a recipe. Built with Express.js and EJS templating, it demonstrates handling API calls and dynamic content rendering based on user input. The project uses a JSON dataset to simulate database interaction.

## Key Learnings

- **API Call Handling**: Learned to handle POST requests in Express.js, simulating API call behavior.
- **JSON Data Parsing**: Gained experience in parsing and manipulating JSON data in server-side JavaScript.
- **Dynamic Content Rendering**: Enhanced skills in using EJS to dynamically render HTML pages based on user input and server-side data.
- **Form Submission Handling**: Developed understanding of handling form submissions and extracting user input in Express.js.

## Installation

Clone the repository:

```bash
git clone https://github.com/lappemic/udemy-api-handling.git
cd udemy-api-handling
npm install
```

## Usage

Start the server:

```bash
node index.js
```

or with nodemon:

```bash
nodemon index.js
```

Visit `http://localhost:3000` in your browser. Choose your favorite taco ingredient to see the corresponding recipe.

## Project Structure

- `index.js`: Main server file configuring Express routes and handling POST requests.
- `views/index.ejs`: The EJS template for the main page, displaying the recipe selection form and the recipe details.
- `public/styles/main.css`: CSS file for styling the web application.
