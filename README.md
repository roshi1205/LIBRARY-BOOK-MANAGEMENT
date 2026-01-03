📚 Library Book Management System

A full-stack web application designed to manage library book records efficiently. This system supports complete CRUD (Create, Read, Update, Delete) operations with proper validation, business rules, and a clean user interface.

🚀 Features

Add new books with details such as title, author, category, year, and copies

View all books in a structured table

Filter books by category

Retrieve books published after a specific year

Increase or decrease available copies dynamically

Prevent negative stock values

Delete books only when available copies are zero

Real-time dashboard showing total books and total copies

Robust error handling and validation

🛠️ Tech Stack

Frontend

React (Vite)

HTML5, CSS3, JavaScript

Axios / Fetch API


Backend

Node.js

Express.js

MongoDB

Mongoose


Tools

Postman (API testing)

MongoDB Compass / Shell

Visual Studio Code

🧱 Project Architecture

Frontend: React-based UI with dashboard, forms, and tables

Backend: RESTful API built using Express.js

Database: MongoDB (libraryDB) with a books collection


Book Schema Fields

title

author

category

publishedYear

availableCopies


Validation ensures:

No negative values for available copies

Proper request body structure

🔄 CRUD Operations

Create

Add new books using POST requests


Read

Retrieve all books

Retrieve books by category

Retrieve books published after 2015


Update

Increase or decrease available copies

Update book category


Delete

Delete a book only if available copies are zero

⚠️ Error Handling

Book not found

Invalid or empty update requests

Prevent reducing stock below zero

Prevent deletion when copies are still available

📦 Installation & Setup

Prerequisites

Node.js

MongoDB

Git


Clone the Repository

git clone <your-github-repo-link>
cd library-book-management-system

Backend Setup

cd backend
npm install
npm start

Frontend Setup

cd frontend
npm install
npm run dev

🧪 Testing

API tested using Postman

Database queries verified using MongoDB Shell

UI validated through real-time frontend updates

🎓 Academic Details

Project Title: Library Book Management System

Institution: Velammal Institute of Technology

Department: B.Tech – Artificial Intelligence & Data Science

📌 Conclusion

This project demonstrates a complete MERN stack application with proper database design, RESTful API development, frontend-backend integration, and strong validation rules. It serves as a solid foundation for real-world library management systems and academic learning.
