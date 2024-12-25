# Task Management Application

This project is a React-based Task Management Application that includes user authentication and task management functionalities. It leverages React Router for navigation, protected routes for secure access, and integrates with a backend API for user and task data.

## Features

### Authentication
- **Sign Up**: Register new users.
- **Login**: Authenticate existing users using email and password.
- **Protected Routes**: Ensure secure access to certain pages using JWT tokens.

### Task Management
- **View Tasks**: Fetch and display tasks from the backend.
- **Add Task**: Create new tasks with fields like name, description, status, priority, and due date.
- **Edit Task**: Modify task details.
- **Delete Task**: Remove tasks from the list.
- **Filter Tasks**: Filter tasks based on their status.

## Technologies Used

- **Frontend**:
  - React
  - React Router DOM
  - React Icons
  - js-cookie
  - ThreeDots (Loader Spinner)

- **Backend**:
  - API endpoints for user authentication and task management (e.g., `/login`, `/register`, `/tasks`).

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the application:

   ```bash
   npm start
   ```

## File Structure

- **App.js**: Main application component with routing logic.
- **components**:
  - **Login.js**: Handles user login.
  - **SignUp.js**: Manages user registration.
  - **Task.js**: Main task management component.
  - **ProtectedRoute.js**: Component for securing routes.
- **index.css**: Application styling.

## API Endpoints

- **POST /login**: User authentication.
- **POST /register**: User registration.
- **GET /tasks**: Fetch all tasks.
- **POST /tasks**: Add a new task.
- **PUT /task/:id**: Update an existing task.
- **DELETE /task/:id**: Delete a task.

## Usage

1. **Authentication**:
   - Sign up as a new user or log in as an existing user.
   - Upon successful login, a JWT token is stored in cookies.

2. **Task Management**:
   - View tasks categorized by status.
   - Add, edit, or delete tasks as needed.
   - Use filters to organize tasks by status.



## Deployment

The application can be deployed using any hosting platform supporting React (e.g., Vercel, Netlify). Ensure the backend API is deployed and accessible.

