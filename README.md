Student Task Manager

A full-stack web application designed to help students organize, manage, and track their daily tasks easily.

Features

- Add new tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as completed
- Undo completed tasks
- Automatically save tasks
- User-friendly interface
- Persistent task storage using a JSON file

Technologies Used

Frontend:

- React.js
- JavaScript
- HTML
- CSS

Backend:

- Node.js
- Express.js
- REST API

Storage:

- JSON file storage

Project Structure

- "frontend/" – React frontend application
- "backend/" – Node.js and Express backend
- "README.md" – Project documentation
- ".gitignore" – Files excluded from Git

How to Run the Project

1. Clone the Repository

git clone YOUR_GITHUB_REPOSITORY_URL

2. Start the Backend

cd backend
npm install
node server.js

Backend runs at: "http://localhost:5000"

3. Start the Frontend

Open another terminal:

cd frontend
npm install
npm run dev

Open the local URL displayed in the terminal.

API Endpoints

Method| Endpoint| Purpose
GET| "/api/tasks"| Get all tasks
POST| "/api/tasks"| Add a task
PUT| "/api/tasks/:id"| Update a task
DELETE| "/api/tasks/:id"| Delete a task

Project Objective

The objective of this project is to provide students with a simple and effective application to organize their daily activities and improve task management.

Future Improvements

- User authentication
- Database integration
- Task deadlines and reminders
- Task priority management

Author

Developed as a Full Stack Web Development Project.
