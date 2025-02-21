# MERN Employee Salary Management

## Employee Payroll System

### Overview
 (Employee Payroll System) is an advanced system designed to help companies efficiently manage employee payroll processes. It automates crucial payroll tasks, such as salary calculation, attendance processing, and wage distribution.

In , all employee data, including personal details, positions, and salary levels, are stored centrally. Each month, the system retrieves attendance records and calculates salaries based on key factors such as working hours, leave, overtime, and deductions.

---
## Table of Contents

- [Configuration and Setup](#configuration-and-setup)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
  - [Frontend](#frontend)
  - [Backend](#backend)
  - [Database](#database)
- [📸 Screenshots](#screenshots)
- [Meet the Team](#meet-the-team)
- [Author](#author)
- [License](#license)

---

## Configuration and Setup

To run this project locally, follow these steps:

1. **Clone or Download** the repository.
2. **Open the project** in your preferred code editor.
3. **Open the terminal** (For VS Code: Terminal → New Terminal).
4. **Run the Frontend and Backend on separate terminals**:

### Frontend Setup
```sh
cd Frontend
npm install  # Install dependencies
npm run dev  # Start the Frontend server
```

### Backend Setup
1. Create a MySQL database.
2. Configure environment variables in a `.env` file:

```sh
# --- .env ---
APP_PORT=5000
SESS_SECRET=your_secret_key
```

3. Start the backend:

```sh
cd Backend
npm install  # Install dependencies
npm start    # Start the Backend server
```

---

## Key Features
- **Admin Dashboard:**
  - Add, edit, and remove employees
  - Manage employee positions
  - Configure salary deductions
  - Process attendance records
  - Generate payroll reports
  - Print payslips
  - Manage user authentication
- **Employee Portal:**
  - Secure login
  - View salary details
  - Print salary reports
- **Other Features:**
  - Responsive UI
  - 404 Error Page
  - Secure authentication and encryption

---

## Technologies Used

### Frontend
- [React JS](https://www.npmjs.com/package/react)
- [React Hooks](https://reactjs.org/docs/hooks-intro.html)
- [React Router Dom](https://www.npmjs.com/package/react-router-dom)
- [Axios](https://www.npmjs.com/package/axios)
- [Tailwind CSS](https://tailwindcss.com/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [Framer Motion](https://www.framer.com/motion/)
- [SweetAlert2](https://sweetalert2.github.io/)
- [React to Print](https://www.npmjs.com/package/react-to-print)

### Backend
- [Node.js](https://nodejs.org/en/)
- [Express.js](https://www.npmjs.com/package/express)
- [MySQL2](https://www.npmjs.com/package/mysql2)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [Bcrypt.js](https://www.npmjs.com/package/bcryptjs)
- [JWT (Jsonwebtoken)](https://www.npmjs.com/package/jsonwebtoken)
- [Cookie Parser](https://www.npmjs.com/package/cookie-parser)
- [Nodemon](https://www.npmjs.com/package/nodemon)
- [Argon2](https://www.npmjs.com/package/argon2)

### Database
- [MySQL](https://www.mysql.com/)

---





## License

**MIT License**

```txt
MIT License

Copyright (c) 2022 Gilbert Hutapea

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

Enjoy using **Employee Payroll System**! 🚀
