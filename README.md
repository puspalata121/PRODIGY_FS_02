# Employee Management System

The Employee Management System is a TypeScript-based web application designed for administrators to manage employee records effectively. It allows CRUD operations (Create, Read, Update, Delete) on employee data with authentication and validation mechanisms to ensure data security and integrity.

## Technology Stack

- **Frontend**: TypeScript, React.js, CSS
- **Backend**: Node.js, Express.js, MongoDB
- **Authentication**: JWT (JSON Web Tokens)

## Features

- **CRUD Operations**: Add, view, update, and delete employee records.
- **Authentication**: Secure login system using JWT tokens.
- **Validation**: Client-side and server-side validation to ensure data integrity.
- **Responsive UI**: User-friendly interface for easy navigation and interaction.

## Getting Started

### Prerequisites

- Node.js (version >= 12.0.0)
- npm or yarn
- MongoDB (running locally or cloud-based instance)

  Install backend dependencies:

bash
Copy code
npm install
Set up environment variables:

Create a .env file in the root directory and add the following:

plaintext
Copy code
PORT=3000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Replace your_mongodb_connection_string with your MongoDB URI and your_jwt_secret with a secret key for JWT.

Start the backend server:

bash
Copy code
npm start
Install frontend dependencies and start the frontend development server (in a separate terminal):

bash
Copy code
cd client
npm install
npm start
Open your browser and visit http://localhost:3000 to use the application.

API Documentation
Employees API
GET /api/employees: Get all employees.
GET /api/employees/
: Get a specific employee by ID.
POST /api/employees: Create a new employee.
PUT /api/employees/
: Update an employee by ID.
DELETE /api/employees/
: Delete an employee by ID





