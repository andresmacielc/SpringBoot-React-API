SpringBoot-React-API

Full-Stack CRUD Application combining a Spring Boot RESTful backend with a React frontend.

🚀 Features

CRUD operations for managing data via REST endpoints

Frontend built with React, React Router, and Axios

Backend using Spring Boot, Spring Data JPA, and H2/PostgreSQL

CORS configuration to enable frontend–backend communication

Exception handling and validation on the server side

🛠️ Tech Stack

Backend: Java, Spring Boot, Spring Web, Spring Data JPA, Hibernate

Frontend: React, React Router, Axios, Bootstrap/Tailwind CSS

Database: H2 (in-memory) or PostgreSQL

Build Tools: Maven (backend), npm/Yarn (frontend)

📋 Prerequisites

Java 11 or higher

Maven 3.6+

Node.js 14+ and npm (or Yarn)

(Optional) PostgreSQL if you switch to a persistent database

⚙️ Installation

1.Clone the repository

git clone https://github.com/andresmacielc/SpringBoot-React-API.git
cd SpringBoot-React-API

2.Run the backend

cd backend
mvn clean install
mvn spring-boot:run

3.Run the frontend

cd frontend
npm install
npm start

4.Access the app at http://localhost:3000 (frontend) and http://localhost:8080/api/... (backend).
📁 Project Structure

SpringBoot-React-API/
├── backend/           # Spring Boot application
│   ├── src/main/java/...
│   └── pom.xml
└── frontend/          # React application
    ├── src/
    └── package.json

🤝 Contributing

Fork the repo

Create a feature branch (git checkout -b feature/xyz)

Commit your changes (git commit -m "feat: Add xyz")

Push to branch (git push origin feature/xyz)

Open a Pull Request
