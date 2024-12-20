# Task Manager

A simple task manager application built with MongoDB, Express.js, React, and Node.js (MERN stack). This application enables users to create, view, update, and delete tasks, providing an easy way to manage daily activities.

---

## Features

- **Create Task:** Add a task with a title, description, and completion status.
- **View Tasks:** Display all tasks in a list.
- **Update Task:** Edit task details, such as title, description, or completion status.
- **Delete Task:** Remove tasks individually.

---

## Technology Stack

- **Frontend:** React.js
- **Backend:** Express.js (Node.js)
- **Database:** MongoDB
- **Other Tools:** Axios, Mongoose

---

## Prerequisites

Make sure you have the following installed on your system:

1. **Node.js** (v14 or higher) - [Download Node.js](https://nodejs.org/)
2. **MongoDB** (local or cloud setup) - [Download MongoDB](https://www.mongodb.com/try/download/community)

---

## Getting Started

Follow these steps to run the application locally:

### 1. Clone the Repository

```bash
git clone https://github.com/NamrataDhingra/TaskManager_Namrata
cd task-manager
```
### Install Dependencies

### Backend Dependencies
Navigate to the backend directory and install the required packages:
```
cd backend
npm install
```

Frontend Dependencies
Navigate to the frontend directory and install the required packages:

```

cd ../frontend
npm install
```
Start MongoDB
Ensure MongoDB is running. Use the following command if MongoDB is installed locally:
.env (Optional)
- If you are using a cloud database or want to use custom environment variables, create a .env file in the backend directory and add the following:
```bash
MONGODB_URI=your_mongodb_connection_string
```

Start the Backend Server
Navigate to the backend directory and start the server:

```
cd backend
npm start
```
for frontend
```
cd ../frontend
npm start
```

The frontend will run at 
```
http://localhost:3000
```

Port Conflict: If ports 3000 is already in use, update the configuration: For the backend, change the PORT in the .env file. For the frontend, update the proxy setting in frontend/package.json. MongoDB Connection Issues: Ensure that MongoDB is running locally or that your connection string in .env is correct.
