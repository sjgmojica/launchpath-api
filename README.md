# 🚀 LaunchPath API

> Backend service for **LaunchPath**, an AI-powered career development platform that helps users discover career paths, assess their skills, receive personalized learning roadmaps, and prepare for their next job opportunity.

---

## 📌 Overview

LaunchPath API provides the backend services for the LaunchPath platform. It exposes RESTful APIs for authentication, user management, career exploration, AI-powered recommendations, learning roadmaps, job opportunities, and assessments.

This project is built with scalability, maintainability, and testability in mind using modern backend development practices.

---

## 🛠 Tech Stack

| Category       | Technology                         |
| -------------- | ---------------------------------- |
| Framework      | NestJS                             |
| Language       | TypeScript                         |
| Database       | PostgreSQL                         |
| ORM            | Prisma                             |
| Authentication | JWT                                |
| Validation     | class-validator, class-transformer |
| Testing        | Jest, Supertest                    |
| Documentation  | Swagger/OpenAPI                    |
| Linting        | ESLint                             |
| Formatting     | Prettier                           |
| Git Hooks      | Husky, lint-staged                 |
| Environment    | @nestjs/config                     |

---

## 📁 Planned Project Structure

```text
src/
├── modules/
│   ├── auth/
│   ├── users/
│   ├── careers/
│   ├── roadmaps/
│   ├── skills/
│   ├── assessments/
│   ├── jobs/
│   └── ai/
│
├── infrastructure/
│   ├── prisma/
│   └── logger/
│
├── shared/
│   ├── decorators/
│   ├── dto/
│   ├── filters/
│   ├── guards/
│   ├── interceptors/
│   ├── middleware/
│   ├── pipes/
│   └── utils/
│
├── config/
│
├── app.module.ts
└── main.ts
```

---

## 🧪 Testing Strategy

LaunchPath follows a layered testing approach.

### Unit Tests

* Service layer
* Controller layer
* Utility functions
* Guards
* Pipes

### End-to-End (E2E) Tests

Critical API workflows will be tested using Supertest, including:

* Authentication
* User management
* Career recommendations
* Roadmaps
* Assessments
* Jobs

Testing is integrated into the development workflow, with all tests expected to pass before merging changes.

---

## 🏗 Development Roadmap

### Phase 1

* Project bootstrap
* Project architecture
* Prisma setup
* PostgreSQL connection
* Environment configuration
* Swagger
* ESLint & Prettier
* Husky
* Testing configuration

### Phase 2

* Authentication
* User management

### Phase 3

* Careers
* Skills
* Roadmaps
* Assessments
* Jobs

### Phase 4

* AI-powered recommendations
* Resume analysis
* AI chat assistant

### Phase 5

* Docker
* CI/CD with GitHub Actions
* Monitoring
* Production deployment

---

## 🎯 Project Goals

* Build a scalable backend using NestJS.
* Apply clean architecture and modular design.
* Maintain high code quality with automated testing.
* Demonstrate production-ready software engineering practices.
* Serve as the backend for the LaunchPath web application.

---

## 📄 License

This project is licensed under the MIT License.
