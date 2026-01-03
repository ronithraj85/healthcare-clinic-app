# Healthcare App - API

This is the backend service for the Healthcare App. It provides secure authentication, role-based access, and REST APIs for managing users and healthcare data.

## 🚀 Features
- JWT authentication with role-based access
- User registration and login endpoints
- Secure CRUD APIs for healthcare data
- PostgreSQL database integration
- Kafka-ready architecture for event-driven extensions

## 🛠 Tech Stack
- Java + Spring Boot
- PostgreSQL
- JWT Authentication
- Kafka (future integration)
- Docker (optional for deployment)

## ⚙️ Setup Instructions
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/healthcare-api.git
2. Configure environment variables in application.properties:
   spring.datasource.url
   spring.datasource.username
   spring.datasource.password
   jwt.secret
   
3.  Run the app:   
   bash
   ./mvnw spring-boot:run
   API will be available at http://localhost:8080.
   
