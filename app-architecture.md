# App Architecture

Integration patterns, API design, and code structure.

Section page: [App Architecture in Production: Integration Patterns, Code Design, and Data Access](https://www.glukhov.org/app-architecture/)

[Index of all sections](README.md)

## Integration patterns

- [Chat Platforms as System Interfaces in Modern Systems](https://www.glukhov.org/app-architecture/integration-patterns/chat-platforms-as-system-interfaces/) — Explore how Slack and Discord act as system interfaces for alerting workflows and human in the loop control in modern distributed architectures.
- [Circuit Breaker Pattern in Go: Stop Cascading Failures](https://www.glukhov.org/app-architecture/integration-patterns/circuit-breaker-pattern-in-go/) — Implement the circuit breaker pattern in Go with gobreaker, context timeouts, retries, fallbacks, and production-ready configuration for microservices.
- [Dead Letter Queues: Handling Poison Messages in Distributed Systems](https://www.glukhov.org/app-architecture/integration-patterns/dead-letter-queues/) — A practical guide to dead-letter queues: catching poison messages, choosing retry vs discard policies, and designing safe replay strategies.
- [Discord Integration Pattern for Alerts and Control Loops](https://www.glukhov.org/app-architecture/integration-patterns/discord/) — Deep dive on Discord webhooks and bots for alerts, approvals, and human-in-the-loop control. Go and Python examples, security, idempotency, and routing.
- [Go Microservices for AI/ML Orchestration](https://www.glukhov.org/app-architecture/integration-patterns/go-microservices-for-ai-ml-orchestration-patterns/) — Explore proven patterns for building scalable AI/ML orchestration systems using Go microservices. Learn event-driven architectures, workflow engines, and best practices for production deployments.
- [Idempotency in Distributed Systems That Actually Works](https://www.glukhov.org/app-architecture/integration-patterns/idempotency-in-distributed-systems/) — Idempotency is not an HTTP trick. Learn how to stop duplicate writes, replayed messages, and double charges across APIs, queues, webhooks, and workflows.
- [Implementing Telegram Bot in Python and Javascript with deployment to AWS](https://www.glukhov.org/app-architecture/integration-patterns/implementing-telegram-bot-python-javascript/) — Step-by-step instructions on how to create a Telegram Bot in Python and Javascript with deployment to AWS
- [Implementing Workflow Applications with Temporal in Go: A Complete Guide](https://www.glukhov.org/app-architecture/integration-patterns/workflow-applications-temporal-in-go/) — Learn how to implement workflow applications with Temporal in Go using the official Temporal Go SDK.
- [Saga Pattern in Distributed Transactions - With Examples in Go](https://www.glukhov.org/app-architecture/integration-patterns/saga-transactions-in-microservices/) — Complete guide to Saga pattern implementation in Go for microservices. Learn orchestration vs choreography, compensation strategies, idempotency, event sourcing, and best practices with practical examples.
- [Selfhosted integration systems comparison](https://www.glukhov.org/app-architecture/integration-patterns/selfhosted-integration/) — Overview of DIY Selfhosted Integration systems - huginn, nodered and others
- [Slack Integration Patterns for Alerts and Workflows](https://www.glukhov.org/app-architecture/integration-patterns/slack/) — Deep dive on Slack webhooks and apps for alerts, approvals, and workflow automation. Block Kit buttons, signature verification, Go and Python examples.
- [Transactional Outbox Pattern in Go with PostgreSQL](https://www.glukhov.org/app-architecture/integration-patterns/transactional-outbox-pattern-go/) — Stop losing events between your database and message broker. Learn the transactional outbox pattern in Go with PostgreSQL, FOR UPDATE SKIP LOCKED, and a polling relay.

## APIs

- [Adding Swagger to Go API](https://www.glukhov.org/app-architecture/api-architecture/adding-swagger-to-api-in-go/) — Learn to generate and serve OpenAPI documentation with swaggo, integrate Swagger UI in Gin/Echo/Fiber apps, and follow best practices for Go API documentation.
- [Building REST APIs in Go: Complete Guide](https://www.glukhov.org/app-architecture/api-architecture/implementing-api-in-go/) — A comprehensive guide to implementing RESTful APIs in Go, covering standard library approaches, frameworks, authentication, testing patterns, and production-ready best practices for scalable backend services.
- [FastAPI: Modern High-Performance Python Web Framework](https://www.glukhov.org/app-architecture/api-architecture/api-in-python-with-fastapi/) — Comprehensive guide to FastAPI—a modern, fast Python web framework for building APIs with automatic documentation, type validation, async support, and production-ready features for scalable applications.
- [Go Web Frameworks in 2026: net/http, chi, Gin, Echo, Fiber Compared](https://www.glukhov.org/app-architecture/api-architecture/go-web-frameworks-stdlib-chi-gin-echo-fiber/) — Benchmarked 2026 comparison of Go HTTP stacks: net/http ServeMux, chi, Gin, Echo, and Fiber - routing, allocations, the fasthttp tradeoff, and how to choose.

## Code structure

- [Bounding Concurrency in Go: errgroup, Worker Pools, and Backpressure](https://www.glukhov.org/app-architecture/code-architecture/bounding-concurrency-in-go/) — Bound Go concurrency: errgroup.SetLimit, semaphore channels, worker pools, and bounded queues - with the goroutine leak that survives errgroup.Wait.
- [Dependency Injection in Go: Patterns & Best Practices](https://www.glukhov.org/app-architecture/code-architecture/dependency-injection-in-go/) — Master dependency injection in Go with constructor injection, interfaces, DI frameworks like Wire and Dig, and best practices for testable, maintainable code.
- [Dependency Injection: a Python Way](https://www.glukhov.org/app-architecture/code-architecture/dependency-injection-in-python/) — Master dependency injection in Python with constructor injection, DI frameworks, protocols, and best practices for testable, maintainable code.
- [Go context.Context Done Right: Cancellation, Timeouts, and Values](https://www.glukhov.org/app-architecture/code-architecture/go-context-cancellation-timeouts/) — Master Go context for cancellation, timeouts, and request-scoped values. Covers HTTP handlers, database calls, background workers, goroutine leaks, and graceful shutdown.
- [Go Error Handling Architecture: Boundaries and Patterns](https://www.glukhov.org/app-architecture/code-architecture/go-error-handling-architecture/) — Learn Go error handling architecture with wrapping, sentinel errors, custom types, errors.Is, errors.As, API boundaries, logging, and production patterns.
- [Go Generics: Use Cases and Patterns](https://www.glukhov.org/app-architecture/code-architecture/generics-in-go/) — Explore Go generics with practical use cases, common patterns, and best practices. Learn how to write type-safe, reusable code in Go 1.18+.
- [Go Project Structure: Practices & Patterns](https://www.glukhov.org/app-architecture/code-architecture/go-project-structure/) — Master Go project layouts with proven patterns from flat structures to hexagonal architecture. Learn when to use cmd/, internal/, pkg/ and avoid common pitfalls.
- [Implementing CQRS in Go: A Practical Guide to Scalable Architecture](https://www.glukhov.org/app-architecture/code-architecture/implementing-cqrs-in-go/) — Learn how to implement the CQRS pattern in Go.
- [Python Design Patterns for Clean Architecture](https://www.glukhov.org/app-architecture/code-architecture/python-design-patterns-for-clean-architecture/) — Master SOLID principles, dependency injection, and layered architecture in Python. Learn repository pattern, hexagonal architecture, and domain-driven design for maintainable, testable, and scalable applications.

## Data access

- [Comparing Go ORMs for PostgreSQL: GORM vs Ent vs Bun vs sqlc](https://www.glukhov.org/app-architecture/data-access/comparing-go-orms-gorm-ent-bun-sqlc/) — Go ORMs for PostgreSQL comparison: GORM vs Ent vs Bun vs sqlc - with code examples

## Testing

- [Go Unit Testing: Structure & Best Practices](https://www.glukhov.org/app-architecture/testing-architecture/unit-testing-in-go/) — Master Go unit testing with built-in testing package, table-driven tests, mocks, coverage analysis, and industry best practices for robust Go applications.
- [Keeping Specs, Tests, And Code In Sync In AI Development](https://www.glukhov.org/app-architecture/testing-architecture/specs-tests-code-traceability-ai-development/) — Learn how to build requirement-to-test-to-code traceability for AI-assisted development, catch spec drift early, and enforce it with CI gates and PR checklists.
- [Parallel Table-Driven Tests in Go](https://www.glukhov.org/app-architecture/testing-architecture/parallel-table-driven-tests-in-go/) — Parallel execution of table-driven tests in Go: Learn best practices, avoid race conditions, and optimize test performance with t.Parallel() and subtests.
- [Testing Concurrent Go Code with synctest](https://www.glukhov.org/app-architecture/testing-architecture/testing-concurrent-go-code-synctest/) — Learn how Go testing/synctest makes concurrent tests faster and more reliable with fake time, isolated bubbles, Wait, and deterministic async behavior.
- [Unit Testing in Python](https://www.glukhov.org/app-architecture/testing-architecture/unit-testing-in-python/) — Comprehensive guide to unit testing in Python covering pytest, unittest, TDD practices, mocking, fixtures, and best practices for writing maintainable tests with real-world examples and code coverage strategies.

## Documentation and specs

- [Decision Records for AI-Driven Software Development](https://www.glukhov.org/app-architecture/documentation/decision-records-ai-driven-development/) — Learn how ADRs, PDRs, and DDRs preserve intent, guide AI coding agents, and keep architecture, product, and design decisions close to code.
- [Spec-Driven Development Workflow From Requirements to Code](https://www.glukhov.org/app-architecture/documentation/spec-driven-development-workflow/) — A practical five-phase spec-driven workflow for teams and AI agents. Cover requirements, design, task breakdown, implementation slices, and validation before you ship.
- [What Is Spec-Driven Development? The Spec as Source of Truth](https://www.glukhov.org/app-architecture/documentation/what-is-spec-driven-development/) — SDD makes the specification the source of truth for AI coding. Learn the core workflow, how it differs from TDD and BDD, and the real costs and benefits.

## Security

- [Architectural Patterns for Securing Data: At Rest, In Transit, and At Runtime](https://www.glukhov.org/app-architecture/security/securing-data-at-rest-in-transit-runtime/) — A guide to securing data at rest, in transit, and at runtime using modern architectural patterns. Learn about TDE, TLS 1.3, mTLS, RASP, service meshes, AI-driven threat detection, and quantum-resistant cryptography.
- [Zero-Knowledge Architecture: Privacy by Design](https://www.glukhov.org/app-architecture/security/zero-knowledge-architecture/) — Explore zero-knowledge architecture principles, zero-knowledge proofs, and privacy-preserving systems. Learn how ZKPs enable secure authentication, blockchain privacy, and confidential computation.

## Multi-tenancy

- [Multi-Tenancy Database Patterns with examples in Go](https://www.glukhov.org/app-architecture/multitenancy/multi-tenant-database-patterns/) — Explore shared database, separate schema, and database-per-tenant patterns for multi-tenant apps. Learn trade-offs, security, and when to use each approach - with examples in Go
