# Backend Development Curriculum

This 10-week curriculum is designed to teach backend development using JavaScript, TypeScript, Node.js, Express.js, MongoDB, PostgreSQL, and a capstone project. Each week includes learning objectives, key topics, and hands-on projects to reinforce concepts.

## Week 1–2: JavaScript

### Learning Objectives
- Master core JavaScript for backend development
- Understand asynchronous patterns and the event loop
- Manipulate data structures and handle I/O

### Key Topics

#### Core Syntax & Constructs
- Variables: `let`, `const`
- Primitive and reference types
- Control flow: `if/else`, `switch`, loops

#### Functions & Scope
- Function declarations vs. expressions
- Arrow functions
- Closures, IIFE, hoisting

#### Objects & Arrays
- Prototypal inheritance
- Object methods
- Array utilities: `map`, `filter`, `reduce`, destructuring

#### Asynchronous JavaScript
- Callbacks, Promises, `async/await`
- Error handling patterns

#### Modules & Tooling
- ES modules (`import/export`) vs. CommonJS (`require`)
- Overview of bundlers and transpilers (Webpack, Rollup)

#### Node.js Interop
- Built-in Node modules: `fs`, `path`
- EventEmitter basics

### Hands-On Projects
- **CLI Utility**: Build a file-system explorer using `fs` and Promises
- **Data Transformer**: Read JSON, transform data, and write output

---

## Week 3: TypeScript

### Learning Objectives
- Introduce static typing to JavaScript projects
- Leverage TypeScript to catch errors at compile time
- Configure and integrate TypeScript in Node environments

### Key Topics

#### Setup & Configuration
- `tsconfig.json`, compiler options, strict mode
- `ts-node` vs. compiling to JavaScript

#### Primitive & Complex Types
- Primitives, arrays, tuples, enums
- Interfaces vs. type aliases

#### Functions & Generics
- Typed function signatures
- Optional/default parameters
- Generics for functions, interfaces, classes

#### Advanced Types
- Unions, intersections, type guards
- Mapped and conditional types

#### Module Resolution
- `esModuleInterop`, ambient declarations (`.d.ts`)
- Working with third-party JavaScript libraries

### Hands-On Projects
- **Typed Utility Library**: Implement generic functions (e.g., `merge`, `pluck`)
- **TS CLI Tool**: Build and run a command-line parser

---

## Week 4–5: Node.js

### Learning Objectives
- Understand Node.js runtime and architecture
- Handle file, network, and process I/O

### Key Topics

#### Node Architecture
- Single-threaded event loop, non-blocking I/O
- Process management, environment variables

#### Built-in Modules
- `fs`, `path`, `os`, `crypto`, `stream`
- Working with Buffers

#### Event-Driven Patterns
- EventEmitter, custom events
- Streams: readable, writable, transform

#### Error Handling & Debugging
- Synchronous vs. asynchronous errors
- Debugging with built-in inspector

#### Project Structure
- Modularization, folder conventions
- `package.json` scripts and npm workflows

### Hands-On Projects
- **Static File Server**: Serve files over HTTP without Express
- **Log Processor**: Read large logs via streams and summarize

---

## Week 6: Express.js

### Learning Objectives
- Build RESTful APIs using Express.js
- Implement middleware, routing, and error handling
- Secure and document APIs

### Key Topics

#### Getting Started
- Creating an Express app
- Routing basics: `req`, `res`, routing methods

#### Middleware
- Built-in vs. third-party (e.g., `body-parser`, CORS)
- Writing custom middleware

#### Error Handling
- Centralized error handlers
- Validating input with Joi or `express-validator`

#### API Design
- REST conventions, status codes, pagination
- Query parameters, URL parameters, request bodies

#### Security & Performance
- Helmet, rate limiting, input sanitization
- Compression, caching headers

#### API Documentation
- Swagger/OpenAPI integration

### Hands-On Projects
- **Blog API**: Implement CRUD routes for posts and comments with validation
- **Auth Service**: Create register/login endpoints using JSON Web Tokens

---

## Week 7: MongoDB

### Learning Objectives
- Model and query JSON-style document data
- Use Mongoose for schema definitions and validation
- Perform aggregation and indexing for performance

### Key Topics

#### NoSQL Fundamentals
- Document vs. relational models
- Collections, documents, BSON

#### CRUD Operations
- Mongoose schemas, models, and queries
- Validation, middleware (pre/post hooks)

#### Indexing & Performance
- Single vs. compound indexes
- Explain plans and query optimization

#### Aggregation Framework
- Pipeline stages: `$match`, `$group`, `$project`
- Faceted searches

#### Transactions & Replication
- Multi-document transactions
- Replica sets overview

### Hands-On Projects
- **User Auth with Profiles**: Store users and sessions, hash passwords
- **Analytics Dashboard**: Aggregate user actions by day

---

## Week 8: PostgreSQL

### Learning Objectives
- Design normalized relational schemas
- Write complex SQL queries and use transactions
- Interface Node apps with PostgreSQL

### Key Topics

#### Relational Theory & Setup
- Tables, primary/foreign keys, normalization
- Installing PostgreSQL, `psql` basics

#### SQL Syntax
- `SELECT`, JOINs, subqueries, CTEs
- `INSERT`, `UPDATE`, `DELETE`, UPSERT

#### Advanced Features
- Indexing strategies, `EXPLAIN ANALYZE`
- Views, materialized views, functions, triggers

#### Transactions & Concurrency
- ACID properties, isolation levels
- Locks and deadlock handling

#### Node Integration
- Using `pg` or ORMs (TypeORM/Sequelize)
- Connection pooling

### Hands-On Projects
- **Order-Product Schema**: Implement relations and transactions
- **Reporting Service**: Generate sales reports with CTEs

---

## Weeks 9–10: Capstone Project

### Objective
Build a production-grade backend with the following features:
- Node.js + Express REST API
- TypeScript for full type safety
- Authentication (JWT or OAuth)
- Data layer using MongoDB or PostgreSQL with transactions
- Validation, error handling, and logging
- API documentation with Swagger
- Deployment to Heroku, AWS, or Docker container

### Deliverables
- A fully functional backend application
- Comprehensive API documentation
- Deployed application with setup instructions
