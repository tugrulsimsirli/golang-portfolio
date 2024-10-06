# Projects and Task List

These projects are designed to showcase backend development skills with Golang and apply various software architectures. Each project is developed using specific technologies and architectural approaches.

## 1. [Pastebin Clone](https://github.com/tugrulsimsirli/pastebin-clone)

**Objective**: Develop a simple backend application where users can share text or code snippets.

**Technologies**: Gin or Echo, Gorm, PostgreSQL/MongoDB

**Architecture**: Layered Architecture and Repository Pattern

**Tasks**:
- [x] Implement user authentication using JWT.
- [x] Allow users to create text or code snippets.
- [x] Display created text or code snippets.
- [x] Enable users to update existing text or code snippets.
- [x] Allow users to delete text or code snippets.
- [x] Collect view statistics for shared text or code snippets.
- [x] Document the project thoroughly.

## 2. Financial Transactions Tracking Application

**Objective**: Develop an application where users can track their income and expenses.

**Technologies**: Gin or Echo, Gorm, PostgreSQL

**Architecture**: Domain-Driven Design (DDD) and Repository Pattern

**Tasks**:
- [ ] Implement user authentication using JWT.
- [ ] Allow users to create income and expense entries.
- [ ] Display, update, and delete income and expense entries.
- [ ] Generate reports for income and expenses.
- [ ] Apply Domain-Driven Design principles.
- [ ] Document the project thoroughly.

## 3. News Aggregator and Analysis Application

**Objective**: Develop an application that collects data from various news sources (RSS feeds, news APIs), processes and analyzes this data. Users can track news based on specific topics or keywords and analyze these news items.

**Technologies**: Golang, OAuth (for source access), MongoDB, Docker, Natural Language Processing (NLP) libraries

**Architecture**: Clean Architecture and CQRS (Command Query Responsibility Segregation)

**Tasks**:
- [ ] Implement user authentication using JWT.
- [ ] Fetch data from various news sources (RSS feeds and news APIs).
- [ ] Analyze news content using Natural Language Processing (NLP) techniques (sentiment analysis, topic modeling, etc.).
- [ ] Store collected and processed data in MongoDB.
- [ ] Enable users to filter and track news based on specific topics or keywords.
- [ ] Implement API rate limiting and manage access to news sources.
- [ ] Document the project thoroughly.

## 4. Real-Time Chat Application

**Objective**: Develop a chat application with real-time messaging capabilities.

**Technologies**: Gin or Echo, Redis (or PostgreSQL), WebSocket

**Architecture**: Event-Driven Architecture and Microservices

**Tasks**:
- [ ] Implement user authentication using JWT.
- [ ] Provide WebSocket support for real-time messaging.
- [ ] Manage and store message history.
- [ ] Use Event-Driven Architecture to enhance system efficiency.
- [ ] Document the project thoroughly.

## 5. Small-Scale Product Management System

**Purpose**: A simple e-commerce product management system using microservices architecture.

**Technologies**: Golang, Gin or Echo, PostgreSQL/MongoDB, Docker, gRPC or REST

**Architecture**: Microservices Architecture

**Microservices**:
- **Product Service**:
  - [ ] Define product model (name, description, category, price, etc.)
  - [ ] Implement CRUD operations
  - [ ] Containerize using Docker

- **Category Service**:
  - [ ] Define category model (name, description, etc.)
  - [ ] Implement CRUD operations
  - [ ] Containerize using Docker

- **Stock Management Service**:
  - [ ] Define stock model (product ID, stock quantity, etc.)
  - [ ] Implement stock management operations
  - [ ] Containerize using Docker

- **Pricing Service**:
  - [ ] Define pricing model (product ID, price, etc.)
  - [ ] Implement pricing management operations
  - [ ] Containerize using Docker

**Tasks**:
- [ ] Microservices intercommunication using REST API or gRPC
- [ ] API Gateway setup (e.g., Traefik or Nginx)
- [ ] Documentation
