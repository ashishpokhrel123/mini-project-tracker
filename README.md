# **Mini Project Tracker App**

A simple MERN stack application for tracking projects and their tasks.

---

## **Features**

- **Create, read, update, and delete projects.**
- **Add tasks to projects** with status (Todo, In-progress, Done).
- **Update task status** via a dropdown.
- **View all tasks** for a specific project.
- **Real-time UI updates** without page reload.

---

## **Technologies Used**

- **MongoDB**: Database for storing projects and tasks.
- **Express.js**: Backend framework for API.
- **React**: Frontend library for UI.
- **Node.js**: Runtime environment.
- **Mongoose**: ODM for MongoDB.
- **Tailwind CSS**: Styling for frontend.

---

## **Setup Instructions**

### **Prerequisites**

Make sure you have the following installed:

- **Node.js** (v14 or higher)
- **MongoDB** (local or Atlas)
- **npm**

---

### **Backend Setup**

1. Navigate to the backend directory:

   ```bash
   cd Min-Project-Tracker/backend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the backend directory with the following content:

   ```
   MONGODB_URI=mongodb://localhost:27017/project-tracker
   PORT=5000
   ```

4. Start the backend server:
   ```bash
   npm start
   ```

---

### **Frontend Setup**

1. Navigate to the frontend directory:

   ```bash
   cd Min-Project-Tracker/frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the frontend development server:
   ```bash
   npm start
   ```

---

### **Running the Application**

1. Ensure MongoDB is running.
2. Start the backend server (runs on [http://localhost:5000](http://localhost:5000)).
3. Start the frontend server (runs on [http://localhost:3000](http://localhost:3000)).
4. Open [http://localhost:3000](http://localhost:3000) in your browser to use the app.

---

## **API Endpoints**

### **Projects:**

- **GET /api/projects**: List all projects.
- **POST /api/projects**: Create a project.
- **PUT /api/projects/:id**: Update a project.
- **DELETE /api/projects/:id**: Delete a project.

### **Tasks:**

- **GET /api/projects/:projectId/tasks**: List tasks for a project.
- **POST /api/projects/:projectId/tasks**: Create a task.
- **PUT /api/tasks/:id**: Update a task.
- **DELETE /api/tasks/:id**: Delete a task.

---

## **Folder Structure**

```bash
Min-Project-Tracker/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── .env
│   ├── server.js
│   └── package.json
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
└── README.md
```

---

## **Usage**

1. **Create a project** using the form on the homepage.
2. **Click a project** to view or add tasks.
3. **Update task status** using the dropdown.
4. **Edit or delete** projects/tasks as needed.

---
