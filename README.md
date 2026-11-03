# Nihal Kumar Sharma

**Backend Engineer** · Java · Distributed Systems · Event-Driven Architecture

I build backend systems where correctness under failure matters: message ordering, retries, idempotency, recovery, concurrency, and transactional consistency. Currently a Software Development Engineer at **Kaleris**, working on N4, a terminal operating system used by major container ports.

---

## Current Work: Kaleris (N4)

- Cut replica rebuild time from **~28 to ~11 minutes** for ~800K entities by parallelizing and batching state hydration and restart recovery.
- Hardened message ordering across **Kafka and ActiveMQ** at ~1.5M messages/day, reducing ordering-related data defects from **~7 to ~2 per quarter** without serializing processing.
- Reduced redundant downstream updates by **~25%** with per-transaction coalescing and post-commit event publishing.
- Cut manual data-repair tickets from **~11 to ~3 per month** using optimistic versioning, DLQ/redelivery, and compensating reconciliation.
- Built a minimum-commitment billing workflow across terminal operations and billing for ~150 vessel visits/month, from design review through UAT.

---

## Open Source Contributions

| Project | Pull Request | Contribution | Status |
|---|---|---|---|
| **Spring Tools** | [#2055](https://github.com/spring-projects/spring-tools/pull/2055) | Built type-based `@ModelAttribute` validation with configurable severity, JDT quick fixes, and VS Code support. 1,100+ lines, 86 tests. 5.5.0 milestone. | Merged |
| **Apache HertzBeat** | [#4458](https://github.com/apache/hertzbeat/pull/4458) | Fixed bulk pause failing past Tomcat's request-size limit by moving IDs to a JSON body across Angular and backend, with backward compatibility and 15 E2E tests. | Merged |
| **Keycloak** | [#53839](https://github.com/keycloak/keycloak/pull/53839) | Fixed SAML core null handling in `XMLTimeUtil`, where an error was created but never thrown. Regression tests added; 129 SAML Core tests passing. | Merged |
| **Spring Tools** | [#2049](https://github.com/spring-projects/spring-tools/pull/2049) | Fixed false-positive `@ModelAttribute` diagnostics that could silently change Spring MVC binding behavior. 5.5.0 milestone. | Merged |
| **Apache Fineract** | [#189](https://github.com/apache/fineract-loan-origination/pull/189) | Return HTTP 400 instead of 500 for invalid request payloads, with field-level validation errors and regression tests. | In review |

---

## Projects

### [FairDrop](https://github.com/nihalritgithub/fairdrop) — High-concurrency fair allocation platform

Java 21 / Spring Boot flash-sale allocation service with FIFO fairness and zero overselling via PostgreSQL row locking. Sustains **~800 requests/s at p99 ~150 ms** across 5,000 concurrent buyers. Transactional outbox to Kafka, idempotent consumers, DLQ, Redis rate limiting, 57 concurrency/integration tests, and Micrometer/Prometheus observability.

**[Code](https://github.com/nihalritgithub/fairdrop)** · **[Live Demo](https://fairdrop-dq3n.onrender.com)**

---

## Competitive Programming

| Platform | Achievement |
|---|---|
| LeetCode | Guardian |
| Codeforces | Candidate Master |
| AtCoder | Blue-rated |
| Meta Hacker Cup | Round 2 qualifier (2025) |

---

## Technical Stack

- **Languages:** Java, SQL, JavaScript, TypeScript, C++, Python
- **Backend:** Spring Boot, Spring Integration, Spring MVC, Hibernate/JPA, REST APIs
- **Messaging:** Apache Kafka, ActiveMQ/JMS, Transactional Outbox, Idempotent Consumers
- **Data:** PostgreSQL, SQL Server, Redis, Flyway
- **Infrastructure:** Docker, Kubernetes, Google Cloud (Professional Cloud Architect), Prometheus, Grafana

---

## Contact

[nsk99isc@gmail.com](mailto:nsk99isc@gmail.com) · [LinkedIn](https://www.linkedin.com/in/nihal-kumar-sharma-7b6063258)
