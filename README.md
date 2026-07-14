# Wan Jan For David Purba

Backend Performance & Reliability Consultant  
Java / Spring Boot / MySQL / Amazon RDS / AWS

I help engineering teams reduce backend latency, optimize expensive MySQL/RDS queries, modernize Java/Spring Boot services, and improve production observability.

Recent work includes reducing endpoint P90 latency from 2.35s to 72.5ms, cutting authentication database lookups by 94.8%, and leading production query audits across critical banking systems.

## What I Work On

- Java and Spring Boot backend performance audits
- MySQL and Amazon RDS slow query optimization
- Microservices modernization and CVE remediation planning
- Production observability with Grafana, CloudWatch, and OpenTelemetry
- RabbitMQ-based asynchronous workflows
- Caching strategy and invalidation design with Caffeine Cache
- Multi-repository analysis and AI-assisted engineering workflows

## Selected Results

- Reduced onboarding confirmation endpoint latency from 2.35s to 72.5ms at P90 and from 1.75s to 62.5ms at P50.
- Designed distributed Caffeine caching with RabbitMQ fanout invalidation, reaching a 95.5% cache-hit ratio.
- Reduced authentication database lookups per request by 94.8% and lowered average authentication latency by 30.5% without increasing 5xx errors.
- Led production performance audits using MySQL Performance Schema, AWS CloudWatch, OpenTelemetry, and Grafana.
- Identified five database queries consuming approximately 544 database-hours over a 32.5-day window.
- Built local orchestration tooling for interdependent Spring Boot services using Python TUI and reverse proxy patterns.

## Consulting Packages

### Backend Performance Audit

Short engagement to identify expensive endpoints, slow queries, inefficient data access, and missing observability signals.

Deliverables:

- Bottleneck summary
- Slow query candidates
- EXPLAIN analysis
- Index and query rewrite recommendations
- Deployment risk notes
- Before/after validation plan

### MySQL/RDS Query Optimization

Focused optimization for high-impact queries in production systems.

Deliverables:

- Digest or query fingerprint analysis
- Cardinality and index review
- Query rewrite proposal
- Before/after EXPLAIN comparison
- Rollout and rollback checklist

### Spring Boot Modernization

Practical modernization path for legacy services.

Deliverables:

- Dependency and CVE review
- Java/Spring Boot upgrade path
- Connection-pool and resilience review
- Observability checklist
- Phased rollout plan

## Suggested Public Repositories

These are the repositories I plan to build or polish as public proof-of-work:

- `spring-boot-performance-lab` - demo app for endpoint latency, caching, query tuning, and observability.
- `mysql-rds-query-audit-playbook` - repeatable checklist for slow query investigation and EXPLAIN analysis.
- `rabbitmq-cache-invalidation-demo` - fanout invalidation pattern for multi-instance Spring Boot services.
- `backend-modernization-checklist` - practical modernization checklist for Java/Spring Boot systems.
  
## Contact

- LinkedIn: https://www.linkedin.com/in/wan-jan-purba-294409132/
- GitHub: https://github.com/janpurba
- Email: janpurba8@gmail.com
