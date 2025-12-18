# Node.js Express CRUD REST API

A simple REST API built using **Node.js** and **Express** that demonstrates basic **CRUD operations** (Create, Read, Update, Delete) on user data.

This project was built while learning backend development with Express and RESTful APIs.

---

## 🚀 Features
- Create a new user
- Get all users
- Get a user by ID
- Delete a user
- UUID-based unique user IDs
- Modular folder structure (routes & controllers)

---

## 🛠️ Tech Stack
- Node.js
- Express.js
- UUID
- Nodemon

---

## 📁 Project Structure

REST_API_PROJECT
│
├── controllers
│ └── users.js
│
├── routes
│ └── users.js
│
├── index.js
├── package.json
├── package-lock.json
└── README.md

---

## 📦 Installation & Setup

1. Clone the repository
git clone https://github.com/YogeshKankariya/node-express-crud-rest-api.git

2. Navigate to the project folder
cd node-express-crud-rest-api

3. Install dependencies
npm install

4. Start the server
npm start
Server will run on: http://localhost:5000

🔗 API Endpoints

Get all users  GET /users
Get user by ID  GET /users/:id
Create a user  POST /users
Body (JSON):  {
                "firstName": "Yogesh",
                "lastName": "Kankariya",
                "age": 18
              }
Delete a user  DELETE /users/:id

🧪 Testing
You can test all API endpoints using Postman.

📌 Notes
Data is stored in-memory, so it resets on server restart
This project is meant for learning purposes

✨ Future Improvements
1. Add PUT (update user)
2. Add MongoDB integration
3. Input validation
4. Error handling
5. Authentication

👨‍💻 Author
Yogesh Kankariya
Engineering Student | Learning Backend Development 🚀
