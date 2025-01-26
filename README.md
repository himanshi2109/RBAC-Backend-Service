# RBAC-Backend-Service
This project implements two independent backend services using Node.js, Express, and TypeScript with role-based access control (RBAC). A shared MongoDB cluster supports secure data sharing. The User Backend manages user-specific operations, while the Admin Backend handles administrative tasks, ensuring secure cross-backend communication via JWT.

## Features
- Role Management: Define roles (e.g., Admin, User, Manager) with specific permissions.

- Permission Assignment: Assign read, write, delete, and other permissions to roles.

- Access Control: Restrict access based on roles and permissions.

- Audit Logs: Keep track of user actions and permission changes for security audits.

## Installation
### Pre- requisites
- Node.js (or your chosen backend framework)
- A database (e.g., PostgreSQL, MySQL, MongoDB)
- JWT for authentication

## Testing the API
You can test the API using tools like Postman or Insomnia. Make sure to include the JWT token in the Authorization header of your requests.

## Configuration
### Required Environment Variables
- DB_HOST: Database host (e.g., localhost)
- DB_PORT: Database port (e.g., 5432)
- DB_USER: Database user
- DB_PASSWORD: Database password
- JWT_SECRET_KEY: Secret key for signing JWT tokens
- PORT: The port the service should run on (default: 3000)
