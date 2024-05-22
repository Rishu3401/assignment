Demo Credentials

website link :[website link](https://rishuassignment.netlify.app).

Email: demo@gmail.com

Password:password123

Demo Credentials
You can use the above credentials to access the demo version of the application:
These credentials are for demonstration purposes only and may not reflect actual user data. Please refrain from using personal information when testing the application.

Snapshot 
![Screenshot (1)](https://github.com/Rishu3401/assignment/assets/93258944/fe15f9ed-604d-48b2-b4ab-ed2593dc50b6)
![Screenshot (2)](https://github.com/Rishu3401/assignment/assets/93258944/4b6f048a-7154-45b2-97ab-0d52bd39d635)
![Screenshot (3)](https://github.com/Rishu3401/assignment/assets/93258944/00440cc7-4ef6-4cf9-b84e-123e7275e9bd)


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
