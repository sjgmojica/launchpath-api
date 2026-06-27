# 🚀 LaunchPath API

A scalable **NestJS REST API** for **LaunchPath**, a platform designed to help individuals plan, track, and achieve their education, migration, career, and financial goals through a centralized and structured workflow.

LaunchPath provides tools for goal planning, migration tracking, financial planning, document management, university applications, visa workflows, certification tracking, career development, and AI-powered guidance.

> **Project Status:** 🚧 In Development

---

## 📖 Overview

LaunchPath API is the backend service that powers the LaunchPath platform. It exposes RESTful APIs for managing users, goals, education planning, migration workflows, financial planning, career development, document management, and AI-powered recommendations.

The project is built with scalability, maintainability, security, and automated testing in mind using modern backend development practices.

---

## ✨ Planned Features

### Core Platform

* 👤 User Management
* 🎯 Goal Planning
* 🎓 Education Planning
* 🌏 Migration Planning
* 💰 Financial Planning
* 📁 Document Management

### Career Development

* 💼 Career Planning
* 📜 Certification Tracking
* 🗺️ Learning Roadmaps
* 📊 Skill Assessments
* 💼 Job Tracking

### Migration & Education

* 🏫 University Applications
* 🛂 Visa Workflow Tracking
* 📄 Requirements Checklist

### AI Features

* 🤖 AI Assistant
* 🎯 Personalized Recommendations
* 📄 Resume Analysis
* 🗺️ AI-Generated Roadmaps

---

## 🛠️ Tech Stack

| Category           | Technology                          |
| ------------------ | ----------------------------------- |
| Framework          | NestJS                              |
| Language           | TypeScript                          |
| Database           | PostgreSQL                          |
| ORM                | Prisma                              |
| Authentication     | JWT                                 |
| Validation         | class-validator + class-transformer |
| API Documentation  | Swagger (OpenAPI)                   |
| Unit Testing       | Jest                                |
| End-to-End Testing | Jest + Supertest                    |
| Linting            | ESLint                              |
| Formatting         | Prettier                            |
| Git Hooks          | Husky + lint-staged                 |
| Package Manager    | npm                                 |
| Runtime            | Node.js 22 LTS                      |

---

## 📁 Planned Project Structure

```text
src/
├── modules/
│   ├── auth/
│   ├── users/
│   ├── goals/
│   ├── education/
│   ├── migration/
│   ├── finance/
│   ├── documents/
│   ├── careers/
│   ├── certifications/
│   ├── roadmaps/
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

## 🚀 Getting Started

See **SETUP.md** for complete installation and project setup instructions.

---

## 🧪 Testing

LaunchPath follows a comprehensive testing strategy.

* ✅ Unit Tests (Jest)
* ✅ End-to-End Tests (Jest + Supertest)

Every feature should include automated tests before it is merged.

---

## 🗺️ Development Roadmap

### Phase 1 — Foundation

* NestJS project setup
* PostgreSQL
* Prisma ORM
* Swagger
* Global validation
* Testing configuration
* Project architecture

### Phase 2 — Authentication

* User registration
* Login
* JWT authentication
* Role-based authorization

### Phase 3 — Core Modules

* Goals
* Education
* Migration
* Finance
* Documents

### Phase 4 — Career Platform

* Careers
* Roadmaps
* Certifications
* Assessments
* Jobs

### Phase 5 — AI Features

* AI Assistant
* Recommendations
* Resume Analysis
* AI Roadmap Generator

### Phase 6 — Production Readiness

* Docker
* CI/CD
* Monitoring
* Deployment

---

## 📚 Documentation

Additional project documentation will be available in:

* `SETUP.md` – Project setup guide
* `DEVELOPMENT.md` – Development workflow and coding standards
* `docs/` – Architecture, testing strategy, and technical documentation

---

## 📄 License

This project is licensed under the MIT License.
