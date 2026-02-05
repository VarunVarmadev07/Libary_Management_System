# Library Management System (MERN Stack)

A full‑stack **Library Management System** built using the **MERN stack** (MongoDB, Express.js, React, Node.js). This project demonstrates end‑to‑end CRUD operations with a clean frontend UI and RESTful backend APIs.

---

## 🚀 Features

* 📖 Add new books (Title & Author)
* 📋 View all available books
* 🗑️ Delete books
* 💾 Data persistence using MongoDB
* 🔗 REST API based architecture
* 🎨 Clean and minimal React UI

---

## 🛠️ Tech Stack

### Frontend

* React (Vite)
* Axios
* CSS

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

---

## 📂 Project Structure

```
root/
│
├── backend/
│   ├── controllers/
│   │   └── bookController.js
│   ├── models/
│   │   └── Book.js
│   ├── routes/
│   │   └── bookRoutes.js
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── AddBook.jsx
│   │   │   └── BookList.jsx
│   │   ├── services/
│   │   │   └── api.js
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation & Setup

### Prerequisites

* Node.js (v18+ recommended)
* MongoDB (running locally)

---

### 1️⃣ Clone the repository

```bash
git clone <your-repo-url>
cd library-management-system
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Start MongoDB (in a separate terminal):

```bash
mongod
```

Run backend server:

```bash
npm run dev
```

Backend runs at:

```
http://localhost:5000
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs at:

```
http://localhost:5173
```

---

## 🔗 API Endpoints

| Method | Endpoint       | Description    |
| ------ | -------------- | -------------- |
| GET    | /api/books     | Get all books  |
| POST   | /api/books     | Add a new book |
| DELETE | /api/books/:id | Delete a book  |

---

## 🧠 How It Works

* React frontend communicates with backend using Axios
* Express handles REST API requests
* MongoDB stores book data
* Mongoose manages database schema and queries

---

## 🧪 Sample Book Object

```json
{
  "_id": "65xxxx",
  "title": "Clean Code",
  "author": "Robert C. Martin"
}
```

---

## 📸 Screenshots (Optional)

* In this image you will see a basic LMS(Library management system) Where you can add and delete books
![Home Page](assets/images/home.png)
* In this image you can see how the book will added after giving the details of book and it's author name
![ Addbook Page](assets/images/addBook.png)
* In this image you can see after adding the book they will be shown in the book list. Also you can delete the book which you want to delete in the Book list
![ Deletebook Page](assets/images/deleteBook.png)



---

## 🎯 Learning Outcomes

* Understanding MERN stack architecture
* Frontend–Backend integration
* REST API development
* MongoDB setup and usage
* Debugging real‑world issues

---

## 📌 Future Enhancements

* ✏️ Edit / Update books
* 🔐 User authentication (JWT)
* 📚 Issue & return system
* 🔍 Search & filter books

---

## 👨‍💻 Author

T Varun Varma

---

## 📄 License

This project is open‑source and available for learning and educational purposes.

---

##  Note

When you download this project node modules will be removed, so before running the project, type npm i command in your cmd and the node modules will be installed

---


⭐ If you found this project useful, feel free to star the repository!

