Task Management Application

A simple task management application built with React for the frontend and Node.js/Express for the backend. This application demonstrates basic CRUD (Create, Read, Update, Delete) operations with task data.

Table of Contents :

  1. Features
  2. Tech Stack
  3. Installation
  4. Usage
  5. API Endpoints
  
1. Features : 
  Create Task: Add new tasks with a title and description.
  Read Tasks: View all tasks in a list format.
  Update Task: Edit the title and description of an existing task.
  Delete Task: Remove a task from the list.
2. Tech Stack :
  Frontend: React, Axios
  Backend: Node.js, Express
  Database: SQLite or MongoDB (choose one based on preference)
3. Installation :
  Prerequisites
    Node.js and npm installed
    SQLite or MongoDB (if using MongoDB, you’ll also need MongoDB Compass or MongoDB Atlas)

  Clone the repository
    git clone https://github.com/yourusername/task-manager.git
    cd task-manager
    
  3.1 Backend Setup :

    Navigate to the backend folder:
    cd backend
    Install dependencies:
    
    npm install
    Start the backend server:
    
    npm start
    Server will be running on http://localhost:5000
    
  3.2 Frontend Setup :

    Open a new terminal, navigate to the frontend folder:
    
    cd ../frontend
    Install dependencies:
    
    npm install
    Start the frontend application:
    
    npm start
    Frontend will be running on http://localhost:3000

4. Usage :
    Open http://localhost:3000 in your browser.
    Add, view, edit, and delete tasks using the simple task manager interface.
   
5. API Endpoints
    Base URL
    http://localhost:5000/api/tasks
    
    Method	Endpoint	Description
    GET	/	Get all tasks
    POST	/	Create a new task
    PUT	/:id	Update a specific task
    DELETE	/:id	Delete a specific task
    Example JSON Body for POST/PUT
  
    {
      "title": "Sample Task",
      "description": "This is a sample task description."
    }
