# TaskManager: A Basic MERN CRUD Application

## Objective
Develop a simple task management application using the MERN stack. The application demonstrates basic CRUD (Create, Read, Update, Delete) functionality for managing tasks.

---

## Features

### Functional Requirements
1. **Task Features**:
   - Create a task with a title and description.
   - View a list of all tasks.
   - Update a task’s title and description.
   - Delete tasks individually.

2. **Backend**:
   - Implement an Express.js server with the following API endpoints:
     - `GET /tasks` - Fetch all tasks.
     - `POST /tasks` - Create a new task.
     - `PUT /tasks/:id` - Update a specific task.
     - `DELETE /tasks/:id` - Delete a specific task.

3. **Frontend**:
   - Build a React application with the following features:
     - A form to add or update tasks.
     - A list view to display all tasks.
     - Options for each task to edit or delete it.
   - Display success/error messages after operations.

4. **Database**:
   - Use MongoDB to store tasks with the following schema:
     ```json
     {
       "title": "String",
       "description": "String",
       "isCompleted": "Boolean",
       "createdAt": "Date",
       "updatedAt": "Date"
     }
     ```

### Non-Functional Requirements
- Ensure a clean code structure with separate folders for backend and frontend.
- Follow MVC architecture for the backend.
- Use environment variables to manage sensitive information like database connection strings.

---

## Folder Structure

```
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
```

---

## Deliverables

1. **GitHub Repository**:
   - Create a public repository named `task-manager-mern`.
   - Include setup instructions and screenshots of the app in the `README.md`.

2. **README.md**:
   - Clear instructions for:
     - Cloning the repository.
     - Installing dependencies for both backend and frontend.
     - Running the application locally.
   - Mention prerequisites (Node.js, MongoDB, etc.).

3. **Working Code**:
   - Fully functional CRUD operations implemented and tested.
   - Include sample data for demonstration purposes.

---

## Prerequisites
- Node.js
- MongoDB

---

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/NamrataDhingra/TaskManager_Namrata
   cd task-manager-mern
   ```

2. **Install Dependencies:**
   - Backend:
     ```bash
     cd backend
     npm install
     ```
   - Frontend:
     ```bash
     cd frontend
     npm install
     ```

3. **Set Environment Variables:**
   - Create a `.env` file in the `backend` directory with the following variables:
     ```env
     MONGO_URI=your_mongo_connection_string
     PORT=5000
     ```

4. **Run the Application:**
   - From the root directory, run the following command to start both backend and frontend:
     ```bash
     npm run dev
     ```

5. **Access the Application:**
   - Open your browser and navigate to `http://localhost:3000`.

---


