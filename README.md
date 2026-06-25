# LaunchPath API

A scalable NestJS REST API for LaunchPath, a platform designed to help individuals plan, track, and achieve their education, migration, career, and financial goals through a centralized and structured workflow.

LaunchPath provides tools for goal planning, migration tracking, financial planning, document management, university applications, visa workflows, certification tracking, and career development.

---

## Overview

Many life-changing goals—such as studying abroad, migrating to another country, advancing a career, or earning certifications—require managing multiple processes across different systems.

LaunchPath brings these workflows together into a single platform that helps users:

* Define and track personal goals
* Plan migration and relocation journeys
* Manage university applications
* Track visa and immigration processes
* Organize important documents
* Monitor certification progress
* Create career development roadmaps
* Track job applications and opportunities
* Manage financial plans and savings goals

This repository contains the backend services, business logic, authentication, database access, and integrations that power the LaunchPath platform.

---

## Tech Stack

### Backend

* NestJS
* TypeScript
* Node.js

### Database

* PostgreSQL
* Prisma ORM

### Authentication

* JWT
* bcrypt

### Testing

* Vitest
* Supertest

### DevOps

* Docker
* GitHub Actions

---

## Architecture

The project follows a feature-based modular architecture.

```text
src/
├── modules/
│   ├── auth/
│   ├── users/
│   ├── careers/
│   ├── roadmaps/
│   └── jobs/
│
├── infrastructure/
│   └── prisma/
│
├── shared/
│
└── config/
```

### Core Modules

| Module         | Responsibility                           |
| -------------- | ---------------------------------------- |
| Auth           | Authentication and authorization         |
| Users          | User profiles and preferences            |
| Careers        | Career planning and recommendations      |
| Roadmaps       | Goal and learning roadmap management     |
| Jobs           | Job application tracking                 |
| Future Modules | Migration, Finance, Documents, Education |

---

## Project Status

### Current Phase

* [x] Project Planning
* [x] Architecture Design
* [ ] NestJS Setup
* [ ] Prisma Setup
* [ ] Authentication Module
* [ ] User Module
* [ ] Careers Module
* [ ] Roadmaps Module
* [ ] Jobs Module
* [ ] CI/CD Pipeline
* [ ] Production Deployment

---

## Development Setup

### Prerequisites

* Node.js 22+
* Docker
* PostgreSQL

### Install Dependencies

```bash
npm install
```

### Start Database

```bash
docker compose up -d
```

### Run Migrations

```bash
npx prisma migrate dev
```

### Start Development Server

```bash
npm run start:dev
```

---

## Testing

### Unit Tests

```bash
npm run test
```

### Coverage

```bash
npm run test:coverage
```

### End-to-End Tests

```bash
npm run test:e2e
```

---

## Product Roadmap

### Phase 1

* Authentication
* User Management
* Career Planning
* Roadmaps
* Job Tracking

### Phase 2

* Migration Planning
* Visa Workflow Tracking
* University Applications
* Certification Tracking

### Phase 3

* Financial Planning
* Document Management
* Notifications and Reminders
* AI-Powered Recommendations

---

## License

This project is currently under active development.
