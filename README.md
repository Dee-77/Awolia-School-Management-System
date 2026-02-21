Awolia School Management System
Project Title

Awolia School Management System – Modern Digital School Management Platform

Simple Overview

A web-based platform designed to digitize and streamline school operations, providing role-based dashboards for administrators, teachers, and students.

Description

Awolia School Management System is a scalable and modern solution built with Next.js and MongoDB, aimed at simplifying school management.
It centralizes student management, teacher administration, attendance tracking, academic performance monitoring, and finance/fee management. The system ensures security, maintainability, and efficient performance for educational institutions.

Getting Started
Dependencies

Node.js (v18+)

npm

MongoDB (Optional: MySQL)

Tailwind CSS

JWT Authentication

OS: Windows 10 / Linux / macOS

Installing

Clone the repository:

git clone https://github.com/your-username/Awolia-School-Management-System.git
cd Awolia-School-Management-System

Install dependencies:

npm install

Create environment file .env.local in the root directory:

MONGODB_URI=
JWT_SECRET=
NEXT_PUBLIC_API_URL=

⚠ Do not commit your .env file to GitHub.

Executing Program

Start the development server:

npm run dev

Open your browser and navigate to:

http://localhost:3000

Log in using role-based credentials (Admin / Teacher / Student).

Help

Ensure MongoDB is running before starting the server.

If authentication fails, verify JWT_SECRET and database connection.

For common Next.js issues, run:

npm run build
npm start
Authors

Awolia School Management System Team

Contact: awolia@example.com

Version History

0.2

Bug fixes in authentication and dashboard routing

Performance optimizations in database queries

0.1

Initial Release

License

This project is licensed under the MIT License – see the LICENSE.md
 file for details.

Acknowledgments

Inspiration from modern school management platforms

Code snippets from:

awesome-readme

PurpleBooth

dbader

zenorocha

fvcproductions
