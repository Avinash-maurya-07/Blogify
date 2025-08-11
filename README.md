# Blogify 📝

**Blogify** is a simple blogging web application where users can register, log in, create, edit, and delete blog posts. It uses modern web technologies like **Node.js**, **Express**, **MongoDB**, and **EJS**.

## 🚀 Features

- ✅ User authentication using cookies
- ✍️ Create, edit, and delete blog posts
- 🔐 Secure user sessions
- 📄 View all blog posts on the homepage
- 🖼️ Clean and responsive UI with EJS templating
- 🗃️ MongoDB integration for data persistence

## 📁 Project Structure

Blogify/
│
├── models/ # Mongoose models (Blog, User)

├── routes/ # Express routes for user and blog

├── middlewares/ # Authentication middleware

├── public/ # Static files (CSS, images)

├── views/ # EJS templates

├── .gitignore

├── .env # Environment variables

├── app.js # Main application file

└── README.md

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB + Mongoose
- EJS (templating engine)
- dotenv (for environment variables)
- cookie-parser (for handling cookies)

## 🔧 Installation

1. **Clone the repository**

```bash
git clone https://github.com/Avinash-maurya-07/Blogify.git
cd Blogify
Install dependencies
npm install

Create a .env file
PORT=8000
MONGO_URL=your_mongodb_connection_string
Replace your_mongodb_connection_string with your actual MongoDB connection URL.

Run the app
npm start

Then open your browser and go to http://localhost:8000.
