# MERN Todo App

The **MERN Todo App** is a full-stack web application designed to help users effectively manage their todo lists. This project demonstrates the integration of React (frontend) and Express (backend) in a single application. Users can create, update, and delete tasks easily, with a sleek and responsive interface that includes dark mode for a comfortable user experience.

---

## Features

- **Create Todos**: Add new tasks with titles and descriptions.
- **Edit Todos**: Modify existing tasks seamlessly.
- **Delete Todos**: Remove tasks you no longer need.
- **Dark Mode**: Toggle between light and dark modes for better visibility and comfort.

---

## Tech Stack

### **Frontend**
- **React**: Used to build the interactive user interface.
- **Material-UI**: Provides pre-styled components for a modern design.

### **Backend**
- **Express.js**: Lightweight framework to build the RESTful API.
- **Node.js**: Runtime environment to execute JavaScript on the server.

### **Database**
- None: This version of the app does not persist data; todos are stored temporarily in memory.

---

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

Before you begin, ensure you have the following installed on your machine:
- **Node.js**: [Download here](https://nodejs.org/)
- **npm**: Comes bundled with Node.js.

### Installation

1. **Clone the Repository**  
   Open your terminal and run:
   ```bash
   git clone https://github.com/codescalper/mern-todo.git
   cd mern-todo
2. **Install Dependencies**
Navigate to the server folder and install its dependencies:
cd server
npm install
Then, navigate to the client folder and install its dependencies:
cd ../client
npm install

### Usage
1. **Start the Server**
To run the backend, navigate to the server folder and start the server:
   cd server
   npm start
The backend will be available at:
http://localhost:3000

2. **Start the Client**
To run the frontend, navigate to the client folder and start the development server:
   cd ../client
   npm start
The frontend will be available at:
http://localhost:5173

### Project Structure
todo/
├── server/        # Express.js backend
│   ├── index.js   # Entry point for the backend
│   ├── routes/    # API routes
│   └── middleware/ # Middleware for handling requests
├── client/        # React frontend
│   ├── src/       # React source files
│   │   ├── components/  # Reusable UI components
│   │   ├── pages/       # Page-level components
│   │   └── App.js       # Main app component
│   └── public/    # Static assets
└── README.md      # Project documentation



