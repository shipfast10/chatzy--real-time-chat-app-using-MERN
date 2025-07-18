# MERN Stack Project: [fullstack chat app]

> A full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js).

## 🛠 Tech Stack

- _Frontend:_ React.js, Tailwind CSS
- _Backend:_ Node.js, Express.js
- _Database:_ MongoDB (with Mongoose ODM)
- _Authentication:_ JWT

## 📦 Features

- User registration and authentication
- Secure JWT-based login system
- CRUD operations for [your core resource, e.g., posts, tasks, products]
- Responsive UI
- RESTful APIs
- Error handling and form validation

### Project Structure
```bash

/backend       -> Express server & API routes  
/frontend      -> React frontend  
/lib           -> DB and socket setup  
/routes        -> Auth & message handling  

🔧 Setup Instructions

```bash
1. Clone the repo

git clone https://github.com/shipfast10/chatzy--real-time-chat-app-using-MERN.git

2. Set up environment files

Create .env files in both /backend and /frontend with required keys:

# .env (backend)
PORT=5001
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret
CLOUDINARY_CLOUD_NAME=your_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret

3.Install dependencies and build
npm run build
Start the app

4. npm start



