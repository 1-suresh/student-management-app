# Student CRUD App (Node.js + Express + MongoDB + Pug)

A full-stack web application to manage student records using Node.js, Express, MongoDB, and Pug as the templating engine.

## 🚀 Features

- Create, Read, Update, and Delete (CRUD) student records
- Simple UI built with Pug template engine
- MongoDB for storing student data
- Express server with RESTful routing

## 🛠️ Tech Stack

- **Backend**: Node.js, Express
- **Frontend**: Pug (template engine), HTML, CSS
- **Database**: MongoDB (via Mongoose)

## 📷 Screenshot
<img width="1868" height="801" alt="Screenshot 2025-08-06 212225" src="https://github.com/user-attachments/assets/b2adaec2-7702-4ba5-b880-0560e1c9db6a" />
<br />
<br />
<img width="1625" height="672" alt="Screenshot 2025-08-06 212240" src="https://github.com/user-attachments/assets/e939b969-3d8b-4b15-b6d2-256301ee175f" />

## 📁 Project Structure

student-crud-node-express/<br />
├── models/<br />
│ └── Student.js # Mongoose schema<br />
├── public/<br />
│ └── style.css # Static CSS<br />
├── views/<br />
│ ├── index.pug # Student list page<br />
│ ├── new.pug # Add student form<br />
│ ├── edit.pug # Edit student form<br />
│ └── layout.pug # Shared layout<br />
├── server.js # Main Express server<br />
├── package.json<br />
└── README.md<br />

## 📦 Installation

Make sure you have Node.js and MongoDB installed.

git clone https://github.com/your-username/student-crud-node-express.git
cd student-crud-node-express
npm install

## ⚙️ Usage
1. Start MongoDB (make sure it's running on mongodb://localhost:27017/studentDB)

2. Run the server: npm start

3. Open your browser and visit:
👉 http://localhost:3000

## ✍️ Screens
Home page: 
+ Lists all students
+ Add new student
+ Edit existing student
+ Delete a student

## 📄 License
This project is licensed under the ISC License.

## 🙌 Author
Suresh Datt Joshi
