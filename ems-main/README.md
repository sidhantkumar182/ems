# Employee Management System (EMS)

## Overview

Employee Management System (EMS) is a full-stack web application designed to simplify employee record management within an organization. The system enables administrators to perform CRUD (Create, Read, Update, Delete) operations on employee data through an intuitive and responsive interface.

## Features

* Add new employees
* View employee details
* Update employee information
* Delete employee records
* Search and manage employees efficiently
* Responsive user interface
* Real-time data updates
* Secure backend architecture

## Tech Stack

### Frontend

* React.js
* HTML5
* CSS3
* Bootstrap
* JavaScript (ES6+)

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Tools

* Git
* GitHub
* VS Code

## Project Structure

```bash
EMS/
│
├── client/                 # React Frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/                 # Node.js Backend
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   ├── config/
│   └── server.js
│
└── README.md
```

## Installation and Setup

### Clone the Repository

```bash
git clone https://github.com/sidhantkumar182/ems.git
cd ems
```

### Backend Setup

```bash
cd server
npm install
```

Create a `.env` file and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

Start the backend server:

```bash
npm start
```

### Frontend Setup

```bash
cd client
npm install
npm start
```

The application will run at:

```bash
http://localhost:3000
```

## API Endpoints

| Method | Endpoint       | Description        |
| ------ | -------------- | ------------------ |
| GET    | /employees     | Get all employees  |
| GET    | /employees/:id | Get employee by ID |
| POST   | /employees     | Add employee       |
| PUT    | /employees/:id | Update employee    |
| DELETE | /employees/:id | Delete employee    |

## Screenshots

Add project screenshots here:

* Dashboard
* Employee List
* Add Employee Page
* Update Employee Page

## Future Enhancements

* Employee authentication and authorization
* Role-based access control
* Attendance management
* Payroll management
* Employee performance tracking
* Dashboard analytics

## Learning Outcomes

Through this project, I gained practical experience in:

* Building full-stack web applications
* Developing RESTful APIs
* Database integration using MongoDB
* State management in React
* Backend development with Express.js
* Version control using Git and GitHub

## Author

**Sidhant Kumar**

GitHub: https://github.com/sidhantkumar182

---

If you found this project useful, feel free to star the repository.
