# Viral Social API

This project implements a Spring Boot microservice that manages posts, comments, and interactions using Redis for concurrency control.

Technologies Used:
- Spring Boot
- Redis
- PostgreSQL
- Docker

Features:
- Virality score calculation using Redis counters
- Bot reply guardrails
- Comment depth restriction
- Cooldown protection using Redis TTL
- Notification batching with scheduled tasks
