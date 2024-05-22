Demo Credentials

website link :[website link](https://rishuassignment.netlify.app).

Email: demo@gmail.com

Password:password123

Demo Credentials
You can use the above credentials to access the demo version of the application:
These credentials are for demonstration purposes only and may not reflect actual user data. Please refrain from using personal information when testing the application.


 Overview
This project is a web application built with React.js for the frontend and Node.js with Express.js for the backend. MongoDB is used as the database, and JSON Web Tokens (JWT) are implemented for authorization and validation. Bootstrap and custom CSS are used for styling the frontend.

 Features
- Frontend: React.js, Bootstrap, CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Authorization & Validation: JWT (JSON Web Tokens)

 Frontend Setup

1. Navigate to the frontend directory:
   cd frontend
2. Install the required dependencies:
   npm install
3. Start the frontend server:
   npm start

Backend Setup

1. Navigate to the backend directory:
   cd backend
2. Install the required dependencies:
   npm install
  
3. Start the backend server:
   npm start
Running the Application

1. Make sure both frontend and backend servers are running:
   - Frontend: `npm start` in the `frontend` directory
   - Backend: `npm start` in the `backend` directory
2. Open your web browser and navigate to:
   http://localhost:3000
Configuration
Ensure you have the necessary environment variables set up for your backend. Create a `.env` file in the `backend` directory with the following variables:
MONGO_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>
Replace `<your-mongodb-uri>` and `<your-jwt-secret>` with your actual MongoDB connection string and JWT secret.
