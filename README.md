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

Clone the repository

git clone https://github.com/andresmacielc/SpringBoot-React-API.git
cd SpringBoot-React-API

Run the backend

cd backend
mvn clean install
mvn spring-boot:run

Run the frontend

cd frontend
npm install
npm start

Access the app at http://localhost:3000 (frontend) and http://localhost:8080/api/... (backend).

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

2. ClimApp

ClimApp

Weather Notifier Web App built with JavaScript and OpenWeather API.

🚀 Features

Displays current weather and forecast for searched cities

Browser notifications on weather condition changes

User preferences stored in localStorage (language, default city)

Animated backgrounds matching weather conditions

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript (ES6+)

APIs: OpenWeatherMap

Animations: CSS and Canvas animations

📋 Prerequisites

Modern web browser (Chrome, Firefox, Edge)

API key from https://openweathermap.org/

⚙️ Installation

Clone the repository

git clone https://github.com/andresmacielc/climapp.git
cd climapp

Add your API key in config.js:

export const API_KEY = 'YOUR_OPENWEATHER_API_KEY';

Open index.html in your browser.

📁 Project Structure

climapp/
├── css/
├── js/
│   ├── app.js
│   └── notifications.js
├── images/
└── index.html

🤝 Contributing

Open an issue for suggestions or bugs

Submit a pull request for fixes or features

3. Express-Apollo-MongoDB

Express-Apollo-MongoDB

GraphQL API using Express, Apollo Server, and MongoDB/Mongoose.

🚀 Features

CRUD operations exposed via GraphQL schema

MongoDB ODM with Mongoose models

Input validation and error handling

Playground UI for interactive queries and mutations

🛠️ Tech Stack

Server: Node.js, Express

GraphQL: Apollo Server

Database: MongoDB, Mongoose

Auth (optional): JWT, bcrypt

📋 Prerequisites

Node.js 14+

MongoDB (local or Atlas)

⚙️ Installation

Clone the repo

git clone https://github.com/andresmacielc/express-apollo-mongodb.git
cd express-apollo-mongodb

Install dependencies

npm install

Configure environment in .env:

MONGODB_URI=your_mongodb_uri
PORT=4000

Start the server

npm start

Open GraphQL Playground at http://localhost:4000/graphql

📁 Project Structure

express-apollo-mongodb/
├── src/
│   ├── models/
│   ├── resolvers/
│   └── schema.graphql
├── .env
├── index.js
└── package.json

🤝 Contributing

Contributions welcome via PRs or issues.

4. Next.js Project

Next.js Project

Starter template for a Next.js application with authentication and API routes.

🚀 Features

Next.js App Router

Authentication with NextAuth.js

API routes under /pages/api

Tailwind CSS for styling

Layout components and dynamic routing

🛠️ Tech Stack

Framework: Next.js 13+ (App Router)

Auth: NextAuth.js

Styling: Tailwind CSS

Data: Prisma/GraphQL (optional)

📋 Prerequisites

Node.js 16+

⚙️ Installation

Clone and install

git clone https://github.com/andresmacielc/nextjs-project.git
cd nextjs-project
npm install

Configure environment in .env.local:

NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_secret

Run development server

npm run dev

Access at http://localhost:3000

🤝 Contributing

Feel free to open issues or submit PRs.

5. MEVN-Typescript

MEVN-Typescript

Full-stack application using MongoDB, Express, Vue 3, Node.js with TypeScript.

🚀 Features

REST API backend with Node.js & Express

Frontend built in Vue 3 with Composition API

Type safety across server and client

MongoDB integration via Mongoose

🛠️ Tech Stack

Backend: Node.js, Express, TypeScript

Frontend: Vue 3, TypeScript, Vue Router, Vuex/Pinia

Database: MongoDB

📋 Prerequisites

Node.js 14+

MongoDB instance

⚙️ Installation

Clone repo

git clone https://github.com/andresmacielc/mevn-typescript.git
cd mevn-typescript

Install dependencies

cd server && npm install
cd ../client && npm install

Setup .env in server/:

MONGODB_URI=your_uri
PORT=5000

Run both

In server folder

npm run dev

In client folder

npm run serve

🤝 Contributing

Open an issue or submit a PR.

6. Node.js REST API with PostgreSQL (TypeScript)

Node.js REST API with PostgreSQL (TypeScript)

RESTful API built in Node.js with TypeScript and PostgreSQL database.

🚀 Features

CRUD endpoints using Express

Type safety with TypeScript

Database migrations with TypeORM or Knex

Environment-driven configuration

🛠️ Tech Stack

Server: Node.js, Express, TypeScript

ORM: TypeORM or Knex.js

Database: PostgreSQL

📋 Prerequisites

Node.js 14+

PostgreSQL database

⚙️ Installation

Clone

git clone https://github.com/andresmacielc/nodejs-restapi-postgres-ts.git
cd nodejs-restapi-postgres-ts

Install

npm install

Config .env

DB_HOST=localhost
DB_PORT=5432
DB_USER=user
DB_PASS=pass
DB_NAME=your_db

Run migrations (if any)

npm run typeorm migration:run

Start server

npm run dev

🤝 Contributing

Pull requests and issues welcome.

7. NodeMongo

NodeMongo

Simple Node.js backend using MongoDB and Mongoose.

🚀 Features

REST endpoints with Express

Data modeling with Mongoose schemas

Basic CRUD for a sample resource

🛠️ Tech Stack

Backend: Node.js, Express

Database: MongoDB, Mongoose

📋 Prerequisites

Node.js 14+

MongoDB server or Atlas account

⚙️ Installation

Clone this repo

git clone https://github.com/andresmacielc/nodemongo.git
cd nodemongo

Install dependencies

npm install

Configure .env:

MONGODB_URI=your_mongo_uri

Start

npm start

🤝 Contributing

Feel free to file issues or PRs.


