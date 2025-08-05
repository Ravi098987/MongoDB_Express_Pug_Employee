# 🧑‍💼 Employee Management System

A simple CRUD web application built using **Node.js**, **Express**, **MongoDB**, and **Pug**. This app allows users to manage employee records: create, view, update, and delete.

## 🚀 Features

- ➕ Add new employees
- 📋 View all employees
- 🖊️ Edit employee details
- ❌ Delete employees
- 🎨 Styled with CSS and rendered using Pug templates

## 🧰 Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose ODM)
- **Templating**: Pug
- **Styling**: CSS (located in `public/style.css`)

## 📁 Project Structure

```
📦 root/
├── models/
│   └── Employee.js         # Mongoose schema for Employee
├── public/
│   └── style.css           # Custom styling
├── views/                  # Pug templates for rendering UI
│   ├── edit.pug
│   ├── index.pug
│   ├── layout.pug
│   └── new.pug
├── server.js               # Express server and routing
├── package.json            # NPM configuration
└── package-lock.json       # Dependency tree
```

## 🛠️ Setup Instructions

### 1. 📦 Install Dependencies

```bash
npm install
```

### 2. 🌐 Set Up MongoDB

Ensure MongoDB is running locally or use a MongoDB Atlas connection string.

Example for local MongoDB (in `server.js`):

```js
mongoose.connect("mongodb://localhost:27017/your-db-name", {
  useNewUrlParser: true,
  useUnifiedTopology: true,
});
```

### 3. ▶️ Run the Application

```bash
node server.js
```

Then open your browser at: `http://localhost:3000`
