# Expense Management (MERN Stack)

A full-stack expense tracker application built with MongoDB, Express.js, React, and Node.js (MERN). This app allows users to register, log in, and manage their expenses with analytics and a modern UI.

## Features
- User registration and login (authentication)
- Add, edit, and delete expenses
- View analytics and reports
- Responsive and modern UI (Ant Design)
- Secure password storage

## Tech Stack
- **Frontend:** React, Ant Design, Axios, React Router
- **Backend:** Node.js, Express.js, MongoDB, Mongoose
- **Authentication:** JWT (JSON Web Token)

## Getting Started

### Prerequisites
- Node.js and npm installed
- MongoDB database (local or cloud)

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/amanverma20/Expense-Management.git
   cd Expense-Management
   ```
2. **Install backend dependencies:**
   ```bash
   npm install
   ```
3. **Install frontend dependencies:**
   ```bash
   cd client
   npm install
   ```
4. **Set up environment variables:**
   - Create a `.env` file in the root with your MongoDB URI and any other secrets:
     ```env
     MONGO_URL=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

### Running the App
- **Backend:**
  ```bash
  npm start
  ```
- **Frontend:**
  ```bash
  cd client
  npm start
  ```

### Build for Production
- To build the React frontend for production:
  ```bash
  cd client
  npm run build
  ```

## Deployment
- You can deploy this app on platforms like Render, Vercel, or Heroku.
- For Render, connect your GitHub repo and set up a web service for the backend and a static site for the frontend (client/build).

## Folder Structure
```
Expense-Management/
├── client/           # React frontend
├── controllers/      # Express controllers
├── models/           # Mongoose models
├── routes/           # Express routes
├── config/           # DB config
├── server.js         # Express entry point
└── ...
```

## License
This project is licensed under the MIT License.
