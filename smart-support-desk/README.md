# Smart Support Desk

A support-ticket backend where users raise tickets and an AI assistant summarizes them, suggests a category, and answers questions from uploaded help documents.

## Tech stack

Java 21 · Spring Boot · Spring Data JPA · PostgreSQL · Spring Security (JWT) · Kafka · Redis · Spring AI (RAG with pgvector) · React + TypeScript · Docker · GitHub Actions · AWS

## Roadmap

- [x] Project skeleton (Spring Boot, Actuator, validation)
- [ ] Ticket entity and CRUD REST API
- [ ] Validation and global exception handling
- [ ] PostgreSQL with Spring Data JPA and Flyway
- [ ] Unit and integration tests
- [ ] Docker and docker-compose
- [ ] Pagination, sorting, Swagger docs
- [ ] AI ticket summary with Spring AI
- [ ] Kafka for async processing, Redis caching
- [ ] JWT authentication and roles
- [ ] RAG: answer questions from help docs (pgvector)
- [ ] GitHub Actions CI and AWS deployment
- [ ] React frontend

## Run locally

```bash
cd smart-support-desk
mvn spring-boot:run
# then open http://localhost:8080/actuator/health
```
