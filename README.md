TaskManager: A Basic MERN CRUD Application

Objective

Develop a simple task management application using the MERN stack. The application demonstrates basic CRUD (Create, Read, Update, Delete) functionality for managing tasks.

Features

Functional Requirements

Task Features:

Create a task with a title and description.

View a list of all tasks.

Update a task’s title and description.

Delete tasks individually.

Backend:

Implement an Express.js server with the following API endpoints:

GET /tasks - Fetch all tasks.

POST /tasks - Create a new task.

PUT /tasks/:id - Update a specific task.

DELETE /tasks/:id - Delete a specific task.

Frontend:

Build a React application with the following features:

A form to add or update tasks.

A list view to display all tasks.

Options for each task to edit or delete it.

Display success/error messages after operations.

Database:

Use MongoDB to store tasks with the following schema:

{
  "title": "String",
  "description": "String",
  "isCompleted": "Boolean",
  "createdAt": "Date",
  "updatedAt": "Date"
}

Non-Functional Requirements

Ensure a clean code structure with separate folders for backend and frontend.

Follow MVC architecture for the backend.

Use environment variables to manage sensitive information like database connection strings.

Folder Structure

task-manager-mern/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── index.js
├── frontend/
│   ├── src/
│   └── public/
├── README.md
├── package.json (for root dependencies or separate for frontend and backend)
└── .gitignore

Deliverables

GitHub Repository:

Create a public repository named task-manager-mern.

Include setup instructions and screenshots of the app in the README.md.

README.md:

Clear instructions for:

Cloning the repository.

Installing dependencies for both backend and frontend.

Running the application locally.

Mention prerequisites (Node.js, MongoDB, etc.).

Working Code:

Fully functional CRUD operations implemented and tested.

Include sample data for demonstration purposes.

Prerequisites

Node.js

MongoDB

Setup Instructions

Clone the repository:

git clone https://github.com/your-username/task-manager-mern.git
cd task-manager-mern

Install Dependencies:

Backend:

cd backend
npm install

Frontend:

cd frontend
npm install

Set Environment Variables:

Create a .env file in the backend directory with the following variables:

MONGO_URI=your_mongo_connection_string
PORT=5000

Run the Application:

From the root directory, run the following command to start both backend and frontend:

npm run dev

Access the Application:

Open your browser and navigate to http://localhost:3000.

Suggested Development Plan

First 30 Minutes:

Set up the GitHub repository with the required folder structure.

Initialize package.json files for both frontend and backend.

Next 30 Minutes:

Implement the backend APIs using Express.js and connect to MongoDB.

Test the APIs using Postman or cURL.

Next 30 Minutes:

Develop the React frontend with forms and task list display.

Last 30 Minutes:

Integrate the frontend with the backend APIs.

Test the entire flow and push the code to the GitHub repository.

Bonus Features (If Time Permits)

Add basic styling with CSS or a UI library like Bootstrap.

Include pagination for task lists.

Add a filter to show completed/incomplete tasks.
