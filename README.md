---

# SpringBoot-React-API

> Full-Stack CRUD Application combining a Spring Boot RESTful backend with a React frontend.

![Status Badge](https://img.shields.io/badge/status-finished-green) ![Version](https://img.shields.io/badge/version-1.0.0-blue)

---

## 📖 Índice

1. [Descripción](#descripción)
2. [Características](#-características)
3. [Tecnologías](#-tecnologías)
4. [Instalación](#-instalación)
5. [Uso](#-uso)
6. [Estructura de Proyecto](#-estructura-de-proyecto)
7. [Contribuir](#-contribuir)
8. [Licencia](#-licencia)

---

## 📄 Descripción

Aplicación full-stack que integra un backend en Spring Boot con un frontend en React para operaciones CRUD.

## 🚀 Características

- CRUD operations for managing data via REST endpoints
- Frontend built with React, React Router, and Axios
- Backend using Spring Boot, Spring Data JPA, and H2/PostgreSQL
- CORS configuration to enable frontend–backend communication
- Exception handling and validation on the server side

## 🛠️ Tecnologías

- **Backend:** Java, Spring Boot, Spring Web, Spring Data JPA, Hibernate
- **Frontend:** React, React Router, Axios, Bootstrap/Tailwind CSS
- **BD:** H2 (in-memory) or PostgreSQL

## ⚙️ Instalación

```bash
# Clonar el repositorio
 git clone https://github.com/andresmacielc/SpringBoot-React-API.git
 cd SpringBoot-React-API

# Backend\ n cd backend && mvn clean install && mvn spring-boot:run

# Frontend\ n cd frontend && npm install && npm start

```
## 🚨 Uso

Accede al frontend en http://localhost:3000

Las APIs están en http://localhost:8080

## 📁 Estructura de Proyecto

SpringBoot-React-API/
├── backend/           # Spring Boot application
│   ├── src/main/java/...
│   └── pom.xml
└── frontend/          # React application
    ├── src/
    └── package.json

## 🤝 Contribuir

### Fork

Crear rama: git checkout -b feature/xyz

Commit: git commit -m "feat: Add xyz"

Push: git push origin feature/xyz

Abrir Pull Request

## 📝 Licencia

MIT License. Ver LICENSE.

