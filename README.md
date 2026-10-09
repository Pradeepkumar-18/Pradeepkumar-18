<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg">
  <img alt="Pradeep Kumar S, full-stack developer" src="./assets/header-light.svg">
</picture>

### Hi, I'm Pradeep.

I'm a full-stack developer at **Skillmine Technology**, where I own the backend of an AI-powered **Document Management System** used in production every day.
My work sits where backend engineering meets AI: OCR and LLM pipelines, event-driven services on **Kafka** and **Redis**, and data models that stay fast as they grow.
Right now I'm going deep on **Java, Spring Boot and distributed systems** by building a microservices e-commerce platform from scratch.

<sub>📍 Sivakasi, Tamil Nadu · Open to roles in **Bengaluru**</sub>

---

### Impact so far

| | |
|---|---|
| **~80% faster** | Cut document processing from **1 min 30 s to 20 s** per document with an OCR + Gemini + LangChain pipeline |
| **300–500 docs/day** | Processed by the Document Management System backend I own end to end, built for 500 users |
| **Automated releases** | Set up automated deployment for the project, removing the manual release steps |
| **1.5+ years** | Shipping production backend systems for enterprise clients |

---

### Experience

**Junior Software Developer** · Skillmine Technology  
<sub>July 2025 – Present</sub>

- **Own the complete backend** of the Document Management System (NestJS, TypeScript, MongoDB), from data model to deployment.
- Built an **AI document pipeline** (OCR → Gemini → LangChain) for invoice processing and compliance checks, cutting processing time by about 80%.
- Designed **event-driven processing** on Apache Kafka and Redis for asynchronous, high-throughput workflows.
- **Redesigned indexes and decoupled the data model**, which made the slow queries noticeably faster.
- Integrated **multiple cloud storage providers** with real-time usage monitoring, and built a smart web scraper that keeps reference data up to date automatically.
- Prototyped an **AI-agent system that takes an app from a single prompt to a deployed build**.
- Mentor a junior developer on backend development and engineering practice.

**Software Developer Trainee** · Skillmine Technology  
<sub>Jan 2025 – July 2025</sub>

- Built **role-based access control** and **credit management** modules for a Student Management System using REST APIs and a relational data model.

---

### Now · October 2026

- Building a **scalable e-commerce order & inventory platform** in Java 17 and Spring Boot
- Practising **system design** in depth: HLD/LLD, caching strategies and concurrency control
- Looking for **backend or full-stack roles in Bengaluru**

---

### Featured projects

**Scalable E-commerce Order & Inventory Platform** · <sub>In progress</sub>  
<sub>Java 17 · Spring Boot · Spring Cloud Gateway · JPA/Hibernate · PostgreSQL · Redis · Kafka · Docker · Kubernetes · AWS</sub>

Five microservices (Product, Inventory, Order, Payment, Notification) behind Spring Cloud Gateway, with service discovery, load balancing and rate limiting built for flash-sale traffic.

- **No overselling under load:** Redis distributed locks plus JPA optimistic locking, verified with JMeter load tests
- **Saga-based checkout:** the order → payment → inventory flow runs on Kafka events, and failed payments roll back through compensating transactions
- **Fast catalogue reads:** a cache-aside strategy on Redis, with entries expiring by TTL
- Strategy, Factory and Observer patterns; services containerised and deployed to Kubernetes on AWS EC2

**Personalized AI Agent Platform with RAG & MCP**  
<sub>React · NestJS · MongoDB · Gemini · LangChain · MCP · Vector DB</sub>

Agents with their own knowledge bases, conversational memory and tool access, so answers draw on the user's own context.

- A full **RAG pipeline**: ingestion → embeddings → vector store → semantic search
- **MCP-based tool calling** and external API integrations, orchestrated behind secure backend services

**Multi-Agent Coding Platform** · [Code](https://github.com/Pradeepkumar-18/Multi-agent-coding-platform)  
<sub>NestJS · LangGraph · TypeScript</sub>

A LangGraph pipeline (Manager → Planner → Developer → Reviewer → Finalizer) that turns a coding request into reviewed code. All five agents share one strongly typed state, and the run ends with a review score and a list of risks.

**Staywise: Hotel Booking & Operations Platform** · [Code](https://github.com/Pradeepkumar-18/hotel-Management)  
<sub>NestJS · React · MongoDB replica set</sub>

A modular monolith that guarantees **zero overbooking across multi-night stays**, keeps the server as the single source of truth, and records an end-to-end audit trail.

<details>
<summary><b>More things I've built</b></summary>
<br>

- **[Agent Skills](https://github.com/Pradeepkumar-18/Agent-Skills-Md)**: reusable `SKILL.md` packages for Claude Code, Codex CLI and Gemini CLI that keep React + Tailwind codebases consistent
- **Cadence**: a personal habits, tasks, goals and budget tracker (React, NestJS, MongoDB, Docker), deployed as a single-port monolith
- **[Canvas Builder](https://github.com/Pradeepkumar-18/canvas-builder)**: a drag-and-drop page canvas in React and dnd-kit. [Live](https://canvas-builder-beta.vercel.app)

</details>

---

### Toolbox

**Backend**  `Java 17` `Spring Boot` `Spring Cloud Gateway` `Spring Data JPA` `Hibernate` `Node.js` `NestJS` `REST APIs` `Microservices`  
**Frontend**  `TypeScript` `JavaScript` `React` `Remix` `Tailwind CSS` `HTML5` `CSS3`  
**Data**  `PostgreSQL` `MongoDB` `Redis` `Indexing & query optimisation` `Data modelling`  
**Messaging**  `Apache Kafka` `Event-driven architecture` `Saga pattern`  
**Cloud & DevOps**  `Docker` `Kubernetes` `AWS EC2` `CI/CD` `Git`  
**AI & LLM**  `LangChain` `LangGraph` `Gemini API` `RAG` `MCP` `Vector databases` `AI agents` `OCR`  
**Practice**  `System design (HLD/LLD)` `Design patterns` `DSA` `Concurrency control` `JMeter` `Swagger` `Agile/Scrum`

---

### Education

**B.E. Electronics and Communication Engineering** · Ramco Institute of Technology, Rajapalayam  
<sub>2024 · CGPA 7.95</sub>

---

### Let's talk

Hiring for backend or full-stack work, or building something with AI agents? I'd like to hear about it.

[LinkedIn](https://linkedin.com/in/pradeepkumar1803) · [Email](mailto:pradeepkumar18003@gmail.com) · [Portfolio](https://pradeep-portfolio-murex-tau.vercel.app)
