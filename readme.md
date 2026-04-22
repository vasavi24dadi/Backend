# Backend Developer Assignment

## Features
- User Registration & Login (JWT Authentication)
- Role-Based Access (User/Admin)
- Task CRUD APIs
- MongoDB Database Integration
- Basic Frontend for API Testing

## Tech Stack
- Node.js
- Express.js
- MongoDB
- HTML, JavaScript

## Setup Instructions
1. Clone the repository
2. Go to backend folder:
   cd backend
3. Install dependencies:
   npm install
4. Add .env file:
   MONGO_URI=your_mongo_uri
   JWT_SECRET=secret123
5. Run server:
   node server.js

## API Endpoints
- POST /api/auth/register
- POST /api/auth/login
- GET /api/tasks
- POST /api/tasks
- PUT /api/tasks/:id
- DELETE /api/tasks/:id

## Scalability Notes
- Modular architecture for easy scaling
- Can be extended to microservices
- Redis caching can be added
- Load balancing can be implemented