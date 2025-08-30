# MERN To-Do List App

A simple yet powerful **To-Do List Website** built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with **Bootstrap** for styling. This project teaches full-stack development from scratch, featuring complete CRUD functionality, REST API integration, and modern React updates (React 18 with `createRoot`).

---

##  Tech Stack

- **Frontend:** React.js, Axios, Bootstrap 5  
- **Backend:** Node.js, Express.js, MongoDB (local), Mongoose  
- **Others:** Nodemon (backend dev auto-reload), CORS, dotenv

---

##  Features

- Add new tasks with a title  
- View existing tasks  
- Edit tasks (mark as complete or update title)  
- Delete tasks  
- Clean, responsive UI using Bootstrap  
- Fully functional frontend-backend integration via REST API

---

##  Project Structure

mern-todo/
├── backend/
│ ├── models/
│ │ └── Todo.js
│ ├── routes/
│ │ └── todoRoutes.js
│ ├── .env
│ └── server.js
└── frontend/
├── src/
│ ├── components/
│ ├── api/ (optional)
│ └── App.js, index.js, etc.
└── package.json

---

##  Getting Started

### Prerequisites

- Node.js installed  
- MongoDB running locally or accessible via connection string  
- (Optional) Git, VS Code, Postman for API testing



### Setup Backend

Go to the backend folder:
cd mern-todo/backend
   
Install dependencies:
npm install

Create a .env file with the following:
MONGO_URI=mongodb://127.0.0.1:27017/todo_db    
PORT=5000

Start the server:
npx nodemon server.js

You should see:
✅ MongoDB Connected
🚀 Server running on port 5000

Setup Frontend
In a new terminal, navigate to the frontend:

cd ../frontend

Install frontend dependencies:
npm install

Run the React app:
npm start
