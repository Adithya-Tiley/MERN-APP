
Note.App – MERN Stack Note-Taking Web Application

A simple and beginner-friendly full-stack note-taking web application built using the MERN stack. Users can create an account, log in, add notes, view their saved notes, delete individual notes and manage their account.

This project was developed as a learning project to understand full-stack web development, frontend-backend integration, REST APIs and database operations.

Table of Contents

- "Features" (#features)
- "Screenshots" (#screenshots)
- "Tech Stack" (#tech-stack)
- "Project Structure" (#project-structure)
- "Prerequisites" (#prerequisites)
- "MongoDB Setup" (#mongodb-setup)
- "Installation and Setup" (#installation-and-setup)
- "Running the Application" (#running-the-application)
- "What I Learned" (#what-i-learned)
- "Future Improvements" (#future-improvements)
- "Project Credits" (#project-credits)

Features

- User Registration: Create a new account using a username, email and password.
- User Login: Sign in using existing account credentials.
- Add Notes: Create and save personal notes.
- View Notes: Display a list of previously saved notes.
- Delete Notes: Select and delete individual notes.
- Account Details: View account information.
- Logout: Log out of the application.
- Delete Account: Delete the registered account.
- Responsive Interface: Separate layouts for different screen sizes.

Frontend

- React.js
- JavaScript (JSX)
- Vite
- React Router DOM
- Framer Motion
- CSS3

Backend

- Node.js
- Express.js
- Mongoose
- CORS

Database

- MongoDB

Project Structure

MERN-APP/
│
├── backend/
│   ├── package.json
│   ├── package-lock.json
│   └── server.js
│
├── frontend/
│   └── react-app/
│       ├── public/
│       ├── src/
│       │   ├── assets/
│       │   ├── navigate/
│       │   │   ├── AccountPage.jsx
│       │   │   ├── HomePage.jsx
│       │   │   └── TodoList.jsx
│       │   ├── App.jsx
│       │   ├── App.css
│       │   ├── index.css
│       │   └── main.jsx
│       ├── package.json
│       └── vite.config.js
│
├── .gitignore
└── README.md

Prerequisites

Make sure you have the following installed:

- "Node.js" (https://nodejs.org/)
- npm (comes with Node.js)
- "MongoDB Community Server" (https://www.mongodb.com/try/download/community)
- "Visual Studio Code" (https://code.visualstudio.com/)

MongoDB Setup

This project currently uses a local MongoDB database.

1. Install MongoDB Community Server.
2. Start the MongoDB service.
3. Make sure MongoDB is running locally.
4. The application connects to the following database:

mongodb://127.0.0.1:27017/todoapp

The "todoapp" database and its collection are created automatically when the application first stores data.

Note: The MongoDB connection string is currently defined inside "backend/server.js". To use MongoDB Atlas, update the connection configuration accordingly.

Installation and Setup

1. Clone the repository

git clone https://github.com/Adithya-Tiley/MERN-APP.git

2. Navigate to the project directory

cd MERN-APP

3. Install backend dependencies

cd backend
npm install

4. Install frontend dependencies

Open another terminal:

cd frontend/react-app
npm install

Running the Application

You need two separate terminals to run the frontend and backend.

Start the Backend Server

Open the first terminal:

cd backend
node server.js

The backend server will run at:

http://localhost:5000

Start the Frontend Server

Open the second terminal:

cd frontend/react-app
npm run dev

Vite will provide a local development URL, usually:

http://localhost:5173

Open the URL in your browser to use the application.

What I Learned

Through this project, I gained practical experience with:

- Understanding the MERN stack architecture.
- Building user interfaces using React components.
- Managing application state using React Hooks.
- Implementing navigation using React Router.
- Creating backend APIs using Node.js and Express.js.
- Connecting a React frontend to a backend using Fetch API.
- Performing database operations using MongoDB and Mongoose.
- Understanding HTTP methods such as GET, POST, PUT and DELETE.
- Managing frontend and backend development environments.

Future Improvements

Some improvements planned for future versions:

- Implement secure password hashing and authentication.
- Add the ability to edit existing notes.
- Improve backend validation and error handling.
- Introduce proper session management.
- Add a search feature for notes.
- Deploy the application online.
- Move database configuration into environment variables.

Project Credits

This is a learning project based on the original MERN application by "Rayane-Nait-Saidi" (https://github.com/Rayane-Nait-Saidi/mern-first-app).

The source project is acknowledged here for attribution.

---

Developer: Adithya-Tiley
Project: MERN Stack Note-Taking Web Application
Repository: "MERN-APP" (https://github.com/Adithya-Tiley/MERN-APP)