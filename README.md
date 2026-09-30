# Employee Management System

A command-line content management system for viewing and managing a company's departments, roles and employees, backed by a MySQL database.

**Demo video:** https://watch.screencastify.com/v/qSCVkxB3qPQvZPAY0EPP

## Features

- View all employees, departments and roles
- View employees by department or by manager
- Add and remove employees and departments
- Add roles and update an employee's role or manager
- Results shown as formatted tables in the terminal

## Built With

Node.js · Inquirer · MySQL (mysql2) · console.table

## Getting Started

**Prerequisites:** Node.js and MySQL

```bash
git clone https://github.com/Archils/Employee-Management-System.git
cd Employee-Management-System
npm install
```

1. Create and seed the database:
   ```bash
   mysql -u root -p < db/employeeTrack_db.sql
   mysql -u root -p < db/seeds.sql
   ```
2. Update the MySQL username and password in `db/connection.js` to match your local setup.
3. Start the app:
   ```bash
   npm start
   ```

## Screenshots

![Screenshot](images/sql-demo-01.png)

![Screenshot](images/sql-video-thumbnail.png)

## Author

**Archils Oburu**
- GitHub: [@Archils](https://github.com/Archils)
- Email: oburuarchils@gmail.com
