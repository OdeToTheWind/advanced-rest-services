# Advanced REST Services Mastery

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

[![License](https://img.shields.io/github/license/OdeToTheWind/advanced-rest-services)](LICENSE)
[![Stars](https://img.shields.io/github/stars/OdeToTheWind/advanced-rest-services?style=social)](https://github.com/OdeToTheWind/advanced-rest-services)
[![Last Commit](https://img.shields.io/github/last-commit/OdeToTheWind/advanced-rest-services)](https://github.com/OdeToTheWind/advanced-rest-services)

**Repository**: https://github.com/OdeToTheWind/advanced-rest-services.git

---

## Overview

**Advanced REST Services** is a comprehensive, progressive learning repository designed to master building production-grade RESTful APIs using **Node.js** and **Express.js**.

This project follows a structured 100-demo roadmap that takes you from basic HTTP servers to full-fledged, scalable, real-world microservices architectures. Every demo is self-contained, well-documented, and follows industry best practices for clean architecture, security, performance, and maintainability.

Whether you're a beginner looking to build your first API or an experienced developer aiming to **outperform** in backend interviews and production systems, this repository provides hands-on, incremental learning with clear progression.

---

## Why This Repository?

- **Progressive Learning Path**: 100 carefully curated demos across 4 levels (Beginner → Intermediate → Advanced → Real-World).
- **Production-Ready Practices**: Implements Node.js best practices including layered architecture, error handling, logging, testing, and security.
- **Complete Documentation**: Individual progress docs for every demo + architecture diagrams.
- **Real-World Focus**: Final 25 demos are complete applications ready for portfolio or production inspiration.
- **Outperform Mindset**: Built to help you gain deep expertise and confidence in designing scalable REST services.

By completing all 100 demos, you will have mastered Express.js ecosystem tools, database integration, authentication patterns, performance optimization, deployment strategies, and enterprise-grade API design.

---

## Project Structure

```bash
advanced-rest-services/
├── .github/
│   └── workflows/                  # CI/CD pipelines (GitHub Actions)
├── docs/
│   ├── progress/                   # Detailed per-demo documentation (demo_XX.md)
│   └── architecture/               # High-level diagrams and design decisions
├── demos/
│   ├── beginner/                   # 01–25: Core REST fundamentals
│   ├── intermediate/               # 26–50: Databases, auth, validation
│   ├── advanced/                   # 51–75: Scalability, queues, microservices
│   └── real-world/                 # 76–100: Complete production applications
├── shared/                         # Reusable utilities, middlewares, config
├── package.json                    # Root workspaces configuration
├── .gitignore
├── README.md
└── LICENSE
```
## Daily Progress

Track your 100-day journey to master advanced REST services. Update this table daily as you complete each demo.

| Day | Project / Topic                                      | Level          | Status       | Key Learnings / Deliverables |
|-----|------------------------------------------------------|----------------|--------------|---------------------------------------------------------------------------------------------|
| 01  | 01-hello-world                                       | Beginner       | ⏳ Planned   | Express server setup, basic GET route, res.send(), npm init -y |
| 02  | 02-basic-routing                                     | Beginner       | ⏳ Planned   | Multiple HTTP methods, route definitions, req.params, req.query |
| 03  | 03-rest-crud-array                                   | Beginner       | ⏳ Planned   | In-memory CRUD operations using JavaScript array |
| 04  | 04-json-body-parsing                                 | Beginner       | ⏳ Planned   | express.json() middleware, handling JSON requests |
| 05  | 05-route-parameters                                  | Beginner       | ⏳ Planned   | Dynamic routes with :id, accessing req.params |
| 06  | 06-query-parameters                                  | Beginner       | ⏳ Planned   | Filtering data using req.query |
| 07  | 07-postman-testing                                   | Beginner       | ⏳ Planned   | API testing with Postman, collections & environments |
| 08  | 08-status-codes                                      | Beginner       | ⏳ Planned   | Proper usage of HTTP status codes (200, 201, 400, 404, 500) |
| 09  | 09-error-handling-basic                              | Beginner       | ⏳ Planned   | Simple try-catch and error responses |
| 10  | 10-morgan-logging                                    | Beginner       | ⏳ Planned   | Request logging with morgan middleware |
| 11  | 11-cors-basic                                        | Beginner       | ⏳ Planned   | Enabling CORS for frontend access |
| 12  | 12-dotenv-config                                     | Beginner       | ⏳ Planned   | Environment variables using dotenv |
| 13  | 13-basic-validation                                  | Beginner       | ⏳ Planned   | Manual validation for required fields |
| 14  | 14-file-upload-basic                                 | Beginner       | ⏳ Planned   | Single file upload using multer |
| 15  | 15-static-files                                      | Beginner       | ⏳ Planned   | Serving static files with express.static() |
| 16  | 16-middleware-order                                  | Beginner       | ⏳ Planned   | Understanding middleware execution order |
| 17  | 17-helmet-security-basic                             | Beginner       | ⏳ Planned   | Basic security headers with helmet |
| 18  | 18-rate-limiting-basic                               | Beginner       | ⏳ Planned   | Basic rate limiting with express-rate-limit |
| 19  | 19-paginated-response                                | Beginner       | ⏳ Planned   | Simple pagination using limit and page query params |
| 20  | 20-response-formatter                                | Beginner       | ⏳ Planned   | Consistent API response structure |
| 21  | 21-basic-auth-middleware                             | Beginner       | ⏳ Planned   | Custom middleware for basic authentication |
| 22  | 22-health-check-route                                | Beginner       | ⏳ Planned   | /health endpoint for monitoring |
| 23  | 23-versioning-basic                                  | Beginner       | ⏳ Planned   | Basic API versioning (/api/v1/) |
| 24  | 24-async-routes                                      | Beginner       | ⏳ Planned   | Using async/await in Express routes |
| 25  | 25-project-structure-basic                           | Beginner       | ⏳ Planned   | Organizing code into routes + controllers |
| 26  | 26-mongodb-connection                                | Intermediate   | ⏳ Planned   | MongoDB connection with Mongoose, schemas & models |
| 27  | 27-mongoose-crud                                     | Intermediate   | ⏳ Planned   | Full CRUD operations with MongoDB |
| 28  | 28-express-validator                                 | Intermediate   | ⏳ Planned   | Robust input validation using express-validator |
| 29  | 29-jwt-authentication                                | Intermediate   | ⏳ Planned   | User registration & login with JWT + bcrypt |
| 30  | 30-protected-routes                                  | Intermediate   | ⏳ Planned   | JWT-based route protection middleware |
| 31  | 31-role-based-access                                 | Intermediate   | ⏳ Planned   | Admin vs User role-based authorization |
| 32  | 32-refresh-tokens                                    | Intermediate   | ⏳ Planned   | Refresh token implementation with httpOnly cookies |
| 33  | 33-multer-file-upload                                | Intermediate   | ⏳ Planned   | Multiple file uploads with image validation |
| 34  | 34-email-service                                     | Intermediate   | ⏳ Planned   | Sending emails using nodemailer |
| 35  | 35-pagination-sorting-filtering                      | Intermediate   | ⏳ Planned   | Advanced query features with Mongoose |
| 36  | 36-soft-delete                                       | Intermediate   | ⏳ Planned   | Soft delete pattern with deletedAt field |
| 37  | 37-api-documentation-swagger                         | Intermediate   | ⏳ Planned   | Auto-generated API docs with Swagger |
| 38  | 38-winston-logging                                   | Intermediate   | ⏳ Planned   | Structured logging with Winston |
| 39  | 39-compression-gzip                                  | Intermediate   | ⏳ Planned   | Response compression middleware |
| 40  | 40-cors-advanced                                     | Intermediate   | ⏳ Planned   | Whitelisted origins and advanced CORS config |
| 41  | 41-rate-limiting-advanced                            | Intermediate   | ⏳ Planned   | Per-user and IP-based rate limiting |
| 42  | 42-cache-middleware                                  | Intermediate   | ⏳ Planned   | In-memory caching for frequent endpoints |
| 43  | 43-request-id                                        | Intermediate   | ⏳ Planned   | Unique request ID for tracing |
| 44  | 44-input-sanitization                                | Intermediate   | ⏳ Planned   | Preventing NoSQL injection and XSS |
| 45  | 45-error-handling-global                             | Intermediate   | ⏳ Planned   | Centralized error handling middleware |
| 46  | 46-async-error-wrapper                               | Intermediate   | ⏳ Planned   | Global async error handler utility |
| 47  | 47-seed-database                                     | Intermediate   | ⏳ Planned   | Database seeder script |
| 48  | 48-environment-config                                | Intermediate   | ⏳ Planned   | Multi-environment configuration |
| 49  | 49-unit-testing-jest                                 | Intermediate   | ⏳ Planned   | Unit testing routes and controllers with Jest |
| 50  | 50-integration-testing                               | Intermediate   | ⏳ Planned   | Full integration tests with supertest |
| 51  | 51-clean-architecture                                | Advanced       | ⏳ Planned   | Layered architecture and dependency injection |
| 52  | 52-event-driven-architecture                         | Advanced       | ⏳ Planned   | EventEmitter and event-driven design |
| 53  | 53-microservices-communication                       | Advanced       | ⏳ Planned   | REST + gRPC between services |
| 54  | 54-graphql-hybrid                                    | Advanced       | ⏳ Planned   | Combining REST and GraphQL in one app |
| 55  | 55-websocket-real-time                               | Advanced       | ⏳ Planned   | Real-time features with Socket.io |
| 56  | 56-redis-caching-advanced                            | Advanced       | ⏳ Planned   | Advanced Redis caching and invalidation |
| 57  | 57-rabbitmq-message-queue                            | Advanced       | ⏳ Planned   | Background processing with RabbitMQ |
| 58  | 58-docker-containerization                           | Advanced       | ⏳ Planned   | Dockerfile and docker-compose setup |
| 59  | 59-kubernetes-readiness                              | Advanced       | ⏳ Planned   | Liveness and readiness probes |
| 60  | 60-rate-limiting-redis                               | Advanced       | ⏳ Planned   | Distributed rate limiting with Redis |
| 61  | 61-oauth2-google-github                              | Advanced       | ⏳ Planned   | Social login with Passport.js |
| 62  | 62-openid-connect                                    | Advanced       | ⏳ Planned   | Full OIDC implementation |
| 63  | 63-api-gateway-pattern                               | Advanced       | ⏳ Planned   | Simple API Gateway with routing |
| 64  | 64-circuit-breaker                                   | Advanced       | ⏳ Planned   | Resilience patterns with circuit breaker |
| 65  | 65-bulk-operations                                   | Advanced       | ⏳ Planned   | Bulk create/update with transactions |
| 66  | 66-database-transactions                             | Advanced       | ⏳ Planned   | ACID transactions in Mongoose |
| 67  | 67-search-elasticsearch                              | Advanced       | ⏳ Planned   | Full-text search integration |
| 68  | 68-file-upload-s3                                    | Advanced       | ⏳ Planned   | AWS S3 uploads with presigned URLs |
| 69  | 69-webhook-implementation                            | Advanced       | ⏳ Planned   | Secure webhook handling with signature verification |
| 70  | 70-background-jobs-bullmq                            | Advanced       | ⏳ Planned   | BullMQ queues with retries and dashboard |
| 71  | 71-graphql-subscriptions                             | Advanced       | ⏳ Planned   | Real-time subscriptions |
| 72  | 72-server-sent-events                                | Advanced       | ⏳ Planned   | SSE for live notifications |
| 73  | 73-multi-tenant-saas                                 | Advanced       | ⏳ Planned   | Multi-tenant architecture patterns |
| 74  | 74-feature-flags                                     | Advanced       | ⏳ Planned   | Feature flag implementation |
| 75  | 75-performance-monitoring                            | Advanced       | ⏳ Planned   | Prometheus metrics and monitoring |
| 76  | 76-ecommerce-api                                     | Real-World     | ⏳ Planned   | Products, cart, orders, Stripe payments |
| 77  | 77-blogging-platform-api                             | Real-World     | ⏳ Planned   | Posts, comments, likes, SEO features |
| 78  | 78-social-media-api                                  | Real-World     | ⏳ Planned   | Feed, followers, real-time notifications |
| 79  | 79-task-management-api                               | Real-World     | ⏳ Planned   | Projects, tasks, permissions |
| 80  | 80-online-learning-platform                          | Real-World     | ⏳ Planned   | Courses, lessons, progress tracking |
| 81  | 81-hotel-booking-api                                 | Real-World     | ⏳ Planned   | Rooms, bookings, availability calendar |
| 82  | 82-ride-sharing-api                                  | Real-World     | ⏳ Planned   | Drivers, rides, real-time location |
| 83  | 83-finance-expense-tracker                           | Real-World     | ⏳ Planned   | Transactions, budgets, reports |
| 84  | 84-job-board-api                                     | Real-World     | ⏳ Planned   | Jobs, applications, resume upload |
| 85  | 85-fitness-tracker-api                               | Real-World     | ⏳ Planned   | Workouts, goals, analytics |
| 86  | 86-real-estate-api                                   | Real-World     | ⏳ Planned   | Properties, advanced filters |
| 87  | 87-event-management-api                              | Real-World     | ⏳ Planned   | Events, tickets, seating |
| 88  | 88-healthcare-appointment-api                        | Real-World     | ⏳ Planned   | Doctors, patients, slots |
| 89  | 89-inventory-management                              | Real-World     | ⏳ Planned   | Stock, suppliers, alerts |
| 90  | 90-crm-api                                           | Real-World     | ⏳ Planned   | Leads, deals, pipeline |
| 91  | 91-restaurant-pos-api                                | Real-World     | ⏳ Planned   | Menu, orders, kitchen display |
| 92  | 92-library-management                                | Real-World     | ⏳ Planned   | Books, borrowing, fines |
| 93  | 93-ticket-support-system                             | Real-World     | ⏳ Planned   | Tickets, SLA, escalation |
| 94  | 94-multi-vendor-ecommerce                            | Real-World     | ⏳ Planned   | Sellers, commissions, payouts |
| 95  | 95-news-portal-api                                   | Real-World     | ⏳ Planned   | Articles, trending, comments |
| 96  | 96-project-management-tool                           | Real-World     | ⏳ Planned   | Teams, sprints, issues |
| 97  | 97-video-streaming-api                               | Real-World     | ⏳ Planned   | Video upload, transcoding patterns |
| 98  | 98-banking-api-sandbox                               | Real-World     | ⏳ Planned   | Accounts, transfers (demo) |
| 99  | 99-ai-powered-api                                    | Real-World     | ⏳ Planned   | OpenAI integration, moderation |
| 100 | 100-full-microservices-ecommerce                     | Real-World     | ⏳ Planned   | Distributed services, API Gateway, RabbitMQ |

## Table of Progress

| Level          | Demos | Focus                                              | Status         |
|----------------|-------|----------------------------------------------------|----------------|
| **Beginner**   | 1–25  | Core REST concepts, basic Express, HTTP handling   | ⏳ Planned     |
| **Intermediate**| 26–50 | Databases, authentication, validation, testing     | ⏳ Planned     |
| **Advanced**   | 51–75 | Scalability, queues, caching, resilience patterns  | ⏳ Planned     |
| **Real-World** | 76–100| Complete production applications & microservices   | ⏳ Planned     |

**Total Demos**: 100  
**Goal**: Master REST API development from fundamentals to enterprise level.

Detailed per-demo docs → [docs/progress/](docs/progress/)

## Backend Tech Stack & Deployment Strategy

### Core Technologies
- **Runtime**: Node.js (ESM - type: "module")
- **Framework**: Express.js
- **Database**: MongoDB with Mongoose ODM
- **Authentication**: JWT, Refresh Tokens, OAuth2, Passport.js
- **Validation**: express-validator + sanitization
- **Logging**: Winston + Morgan
- **Caching & Queues**: Redis, BullMQ, RabbitMQ
- **Testing**: Jest + Supertest + mongodb-memory-server
- **Documentation**: Swagger / OpenAPI
- **Security**: Helmet, CORS, rate-limiter-flexible, crypto

### Deployment Strategy
- **Containerization**: Docker (multi-stage builds) + docker-compose
- **Orchestration**: Kubernetes-ready (liveness/readiness probes)
- **CI/CD**: GitHub Actions workflows
- **Monitoring**: Prometheus + custom metrics
- **Cloud Ready**: AWS S3, environment-specific configs
- **Scalability**: Horizontal scaling, API Gateway pattern, circuit breakers

## Key Features

- Consistent JSON response formatting with success/error structure
- Global error handling with custom error classes
- Layered/Clean Architecture in advanced demos
- Comprehensive input validation & sanitization
- JWT authentication + Refresh Token rotation + Role-based access control
- Rate limiting, CORS, Helmet security headers
- Structured logging and request tracing (unique request ID)
- Advanced pagination, filtering, sorting and soft delete
- File uploads (local + AWS S3 with presigned URLs)
- Background job processing with queues
- Real-time features (WebSocket, SSE, GraphQL subscriptions)
- API documentation with Swagger
- Full unit + integration test coverage
- Dockerized and production-ready setup
- Multi-tenant and feature-flag patterns in advanced demos

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/OdeToTheWind/advanced-rest-services.git
   cd advanced-rest-services
   ```

2. **Install root dependencies**
   ```bash
   npm install
   ```

3. **Navigate to any demo and install its dependencies**
   ```bash
   cd demos/beginner/01-hello-world
   npm install
   ```

4. **Run the demo**
   ```bash
   npm run dev
   ```

5. **Document your progress**   
   - Update the Daily Progress table above
   - Create detailed notes in `docs/progress/demo_XX.md`
 
**Tip**: Each demo folder is independent. Start from Day 01 and proceed sequentially to build strong foundations.


---

## Contributing

Contributions are highly welcome! This repository is built to help developers **outperform** in backend development.

### How to Contribute
1. Fork the repository
2. Create a new branch for your feature/fix (`git checkout -b feature/demo-improvement`)
3. Follow the existing demo folder structure and documentation style
4. Add or update demos with proper `package.json`, code comments, and progress docs
5. Commit your changes with clear messages
6. Open a Pull Request with detailed description

Please ensure all new demos maintain consistency in structure and include:
- Clear learning objectives
- Proper error handling
- Swagger documentation (where applicable)
- Tests (for intermediate+ levels)

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

Feel free to use the code for personal learning, portfolio projects, or commercial purposes.
  
