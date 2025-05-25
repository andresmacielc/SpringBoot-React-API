# SpringBoot-React-API

## 📄 Descripción

Proyecto de ejemplo que integra un **API REST** implementado con Spring Boot (Java) en el backend y una **SPA** construida con React en el frontend.

## 🚀 Tecnologías

* Backend: Spring Boot, Spring Web, Spring Data JPA, H2/PostgreSQL
* Frontend: React, Axios, React Router
* Build Tools: Maven (backend), npm/yarn (frontend)

## 🛠️ Características

* CRUD completo de recursos a través de endpoints REST
* Comunicación cliente-servidor usando JSON
* Ejemplo de autenticación básica (opcional)
* Configuración de base de datos en memoria o relacional

## 🚀 Requisitos previos

* Java 11 o superior
* Maven 3+
* Node.js 14+ y npm/yarn

## ⚙️ Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/andresmacielc/SpringBoot-React-API.git
   cd SpringBoot-React-API
   ```
2. Inicia el backend:

   ```bash
   cd backend
   mvn spring-boot:run
   ```
3. Inicia el frontend en otra terminal:

   ```bash
   cd frontend
   npm install   # o yarn install
   npm start     # o yarn start
   ```
4. Accede a la aplicación en `http://localhost:3000` y a la API en `http://localhost:8080/api`

## ⚙️ Configuración

* Variables de entorno en `backend/src/main/resources/application.properties`:

  ```properties
  spring.datasource.url=jdbc:h2:mem:testdb
  spring.datasource.username=sa
  spring.datasource.password=
  ```
* Frontend: ajusta la URL base de la API en `frontend/src/config.js`

📁 **Estructura de Proyecto**

SpringBoot-React-API/
├── backend/ # Spring Boot application
│ ├── src/
│ │ └── main/
│ │ └── java/...
│ └── pom.xml
└── frontend/ # React application
├── src/
└── package.json

## 🚨 Uso

* Navega y crea, edita o elimina recursos desde la interfaz React.
* Consulta manualmente los endpoints con Postman o curl:

  ```bash
  curl http://localhost:8080/api/items
  ```

## 🤝 Contribuciones

1. Haz un Fork del repositorio.
2. Crea una rama (`git checkout -b feature/nueva-funcion`).
3. Realiza tus cambios y commitea (`git commit -m "Add nueva función"`).
4. Envía un Pull Request.

## 📝 Licencia

Este proyecto está bajo la licencia MIT.
