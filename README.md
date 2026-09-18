# Hi, I'm Amaan Lari 👋

Backend Software Engineer focused on distributed systems and event-driven architecture — Java, Spring Boot, and Kafka are where I spend most of my time.

---

## What I Work On

Backend APIs, asynchronous processing, concurrency, data modeling, caching, and the system-design tradeoffs that come with building services meant to run under real load — not just pass a demo.

---

## Engineering Experience

**Solvei8 — Software Engineer** (Apr 2025 – Feb 2026)
Backend for Tracki8, a Manufacturing Execution System supporting **60+ global factories** and **150,000+ users**. Refactored a core production module to support multi-color, variable-size cartons; built a combo-packing feature from scratch (Scala/Play Framework, Slick ORM, MongoDB aggregation pipelines, optimistic concurrency control); built an RFID bulk-scanning engine with a versioned tag lifecycle state machine to prevent collisions under high concurrency; contributed to Kafka-based event streaming for manufacturing analytics; exposed real-time WIP state across services for floor-level traceability.

**Viral Fission — Software Developer** (Jul 2024 – Dec 2024)
Designed a distributed notification pipeline for **150K+ users**, proposing a Redis + Kafka architecture across In-App, SMS, and Email channels targeting **1M+ daily updates**, with retry and dead-letter handling built in. Benchmarked Kafka vs. AWS SQS to inform a scaling roadmap. Built the company's public website and CMS (Angular + Spring Boot) with standardized, unit-tested exception handling.

**Currently:** Software Engineer at LTIMindtree.

---

## Featured Projects

### [Blogger Hub](https://github.com/amaanlari/blogger-hub)
**Live:** [blogger-hub.amaanlari.me](https://blogger-hub.amaanlari.me)

My first publicly deployed full-stack project — a blogging platform, currently a monolith. JWT + OTP authentication, refresh-token rotation, role-based access control (Admin/Free/Premium feature gates), a Kafka-based asynchronous notification pipeline, and MongoDB with compound indexes for query performance. Frontend and backend are both deployed and publicly reachable.

This is a working v1, not a finished product — some backend APIs exist ahead of their frontend integration. Next up: image upload to blob storage, Markdown-rendered images, and a smoother OTP flow.

### [Razorpay](https://github.com/amaanlari/razorpay) — *In Development*
A Razorpay-inspired payment platform, currently built as a monolith. The explicit goal here is the architectural evolution itself: decompose into clear domain boundaries, then move toward microservices with event-driven communication between them. Documenting that process as I go.

### [Oppia](https://github.com/amaanlari/oppia) — Open Source
Contributed to translatable-content tooling on the Oppia learning platform: automated parts of the content-creation workflow, added test coverage, removed obsolete feature flags, and migrated components to the Angular router.

---

## Current Focus

Java, Spring Boot, Apache Kafka, system design, and pushing Blogger Hub and the Razorpay clone further toward proper service decomposition. Increasingly interested in how AI fits into backend systems, not just as a feature but as infrastructure.

---

## Tech Stack

**Backend:** Java, Spring Boot, Spring Security, Scala, Play Framework
**Messaging & Distributed Systems:** Apache Kafka, Redis
**Databases:** MongoDB, PostgreSQL, MySQL
**Cloud & DevOps:** Docker, AWS, Azure, Jenkins, CI/CD
**Frontend:** React, Angular
**Other:** Python, Kotlin

---

<!-- ## Technical Writing

Coming soon.

---
-->
## Connect

**Portfolio:** [amaanlari.me](https://amaanlari.me)
**LinkedIn:** [linkedin.com/in/amaanlari](https://linkedin.com/in/amaanlari)
**GitHub:** [github.com/amaanlari](https://github.com/amaanlari)
