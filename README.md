# 🎸 Band Name Generator
Developed as part of Angela Yu's Complete Web Development Bootcamp, this project transitions from basic logic to a functional web application. It demonstrates how to handle server-side requests, use middleware, and render dynamic content using EJS.

## 🛠️ Features
Middleware Integration: Utilizes body-parser to capture and process user input from the frontend.

Express Server: A backend built with Node.js and Express to handle GET and POST requests.

Responsive Design: Styled with CSS to provide a clean, modern "rockstar" interface.

## 🏗️ Technologies Used
Node.js: JavaScript runtime environment.

Express.js: Web framework for the server.

EJS: Templating engine for generating dynamic HTML.

Body-Parser: Middleware for parsing incoming request bodies.

HTML/CSS: For structure and styling.

## 🚦 Getting Started
Prerequisites
Node.js installed on your machine.

A package manager like npm (comes with Node).

## Installation
Clone the repository:

Bash
```
git clone https://github.com/yourusername/band-name-generator-web.git
```
Navigate to the project folder:

Bash
```
cd band-name-generator-web
```
Install dependencies:

Bash
```
npm install
```
Start the server:

Bash
```
node index.js
```
(Or nodemon index.js if you have nodemon installed)

View the app:
Open your browser and go to http://localhost:3000.

📖 How It Works
The server renders the initial index.ejs page via a GET request.

The server receives a POST request, processes the data through custom middleware, and combines the strings.

The server re-renders index.ejs, passing the new "Band Name" variable back to the frontend to be displayed.

📝 License
This project is part of the App Brewery's Web Development curriculum. Feel free to use it for practice and personal portfolio building!
