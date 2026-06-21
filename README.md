# Ankit Kumar

**Senior Backend Engineer** · Node.js · Distributed Systems · Cloud

Senior Backend Engineer with 3+ years building scalable SaaS platforms, cybersecurity awareness solutions, virtual lab environments, and high-volume messaging systems. Focused on reliability, scalability, and automation.

[LinkedIn](https://linkedin.com/in/akbhuker) · [GitHub](https://github.com/akbhuker) · [Email](mailto:akbhuker49@gmail.com)

---

## Skills

| | |
|---|---|
| **Languages** | JavaScript, TypeScript, Python, Go |
| **Backend** | Node.js, Express.js, Fastify, REST APIs, BullMQ |
| **Databases** | MongoDB, PostgreSQL, Redis |
| **Cloud & DevOps** | AWS (S3, EC2), Docker, Nginx, GitHub Actions, Prometheus |

---

## Experience

**Senior Software Developer** — Wissenhive E-Learning · _Apr 2025 – Present_

- Architected a multi-tenant cybersecurity awareness & training platform for enterprise customers.
- Built a distributed asynchronous campaign engine with BullMQ and Redis — idempotent workers handling 100K+ events/hour with automated retries and no duplicate notifications.
- Developed high-concurrency tracking and telemetry pipelines for phishing simulations.
- Built SCORM content lifecycle management with versioning, validation, and automated integrity verification.

**Software Developer** — DreamBig IT Solutions · _Mar 2023 – Apr 2025_

- Designed decoupled, event-driven backend architectures for on-demand provisioning of isolated virtual lab environments.
- Built RESTful APIs and backend modules powering LMS, assessment, and lab management systems.
- Implemented CI/CD pipelines with GitHub Actions, AWS CodeDeploy, and Docker.

---

## Projects

**[Guardrail — Distributed Rate Limiter](https://github.com/akbhuker/rate-limiter)** · Node.js, TypeScript, Redis (Lua), Express

High-throughput rate limiter implementing 4 algorithms (sliding-window, token-bucket) as atomic Redis Lua scripts — verified exact admission across 500 concurrent requests at ~33K checks/sec. Dynamic per-tier limits with `X-RateLimit-*` headers and Prometheus metrics. [Live demo](https://guardrail-y843.onrender.com)

**[Pulse — Real-Time Event Analytics Engine](https://github.com/akbhuker)** · Node.js, TypeScript, MongoDB, Express

Self-serve analytics computing funnels, retention, sessionization, and rolling z-score anomaly detection entirely in MongoDB aggregation pipelines, with a live dashboard via change streams, a rules-based alerting engine (webhook + SSE), and pre-aggregated rollups via `$merge`.

---

## Education

**B.Tech, Computer Science** — Gurugram University · 2018 – 2022
