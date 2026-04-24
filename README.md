# 📘 Experiment 10: CRUD Operations using Node.js and Express.js

## 🎯 Objective

The objective of this experiment is to build RESTful APIs using Node.js and Express.js to perform CRUD (Create, Read, Update, Delete) operations on a database. MongoDB is used as the backend database, and APIs are tested using Postman.

---

## 💻 Technologies Used

* Node.js
* Express.js
* MongoDB
* Mongoose
* Postman
* CORS

---

## 📁 Project Structure

```
experiment10/
│
├── server.js
├── models/
│     └── Student.js
├── routes/
│     └── studentRoutes.js
├── package.json
```

---

## ⚙️ Installation Steps

1. Create project folder:

```
mkdir experiment10
cd experiment10
```

2. Initialize Node.js:

```
npm init -y
```

3. Install dependencies:

```
npm install express mongoose cors nodemon
```

---

## 🔌 MongoDB Connection

MongoDB is connected using Mongoose with the following URL:

```
mongodb://127.0.0.1:27017/collegeDB
```

---

## 🚀 Running the Project

1. Start MongoDB:

```
net start MongoDB
```

2. Run the server:

```
npx nodemon server.js
```

Server will run on:

```
http://localhost:5000
```

---

## 🧪 API Endpoints

### ➤ Create Record

* Method: POST
* URL: `/api/students`
* Body:

```
{
  "name": "Vaish",
  "email": "vaish@gmail.com",
  "course": "CSE"
}
```

---

### ➤ Read All Records

* Method: GET
* URL: `/api/students`

---

### ➤ Read Single Record

* Method: GET
* URL: `/api/students/:id`

---

### ➤ Update Record

* Method: PUT
* URL: `/api/students/:id`

---

### ➤ Delete Record

* Method: DELETE
* URL: `/api/students/:id`

---

## 📸 Output

* Successfully connected to MongoDB
  <img width="1717" height="916" alt="ChatGPT Image Apr 24, 2026, 05_39_48 PM" src="https://github.com/user-attachments/assets/99b25e41-2b9d-4228-b64f-2df6b90bc319" />

* Records inserted, fetched, updated, and deleted
<img width="1358" height="964" alt="Screenshot 2026-04-24 171352" src="https://github.com/user-attachments/assets/75158bba-fc60-4fbd-a9ae-f063b4167535" />
<img width="1352" height="960" alt="Screenshot 2026-04-24 172030" src="https://github.com/user-attachments/assets/82b11245-f8d4-4653-ae97-9dc7b0534145" />
<img width="1360" height="952" alt="Screenshot 2026-04-24 171916" src="https://github.com/user-attachments/assets/d8f6ceb1-c361-41fb-b558-03c3797acf73" />
<img width="1347" height="595" alt="Screenshot 2026-04-24 171751" src="https://github.com/user-attachments/assets/bbfc92d2-08d1-431e-832c-e510286604fd" />
<img width="1369" height="958" alt="Screenshot 2026-04-24 171445" src="https://github.com/user-attachments/assets/fb81dfc2-cedd-4ad9-ba54-88185a95fee7" />

* APIs tested using Postman
* Data stored in MongoDB database

---

## 🧠 Conclusion

This experiment demonstrates how to build a backend using Node.js and Express.js and perform CRUD operations using MongoDB. It helps in understanding REST API development, routing, and database integration.

---

## 📌 Key Learnings

* Understanding of REST APIs
* Working with Express routing
* Using Mongoose for database operations
* Performing CRUD operations
* Testing APIs using Postman

---
