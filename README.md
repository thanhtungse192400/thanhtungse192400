# Tran Thanh Tung
**Backend & Full-Stack Software Engineer**  
📍 Ho Chi Minh City, Vietnam | ✉️ [tranthanhtungttt10@gmail.com](mailto:tranthanhtungttt10@gmail.com)

> Software Engineer specializing in **Java / Spring Boot** and **React / TypeScript**. Experienced in architecting **Monolithic** and **Event-Driven Microservices** ecosystems, focusing on high-concurrency financial transactions, distributed caching, message queuing, and local AI/RAG pipelines.

---

### 🏛️ Core Engineering & Architecture Focus

* **Microservices & Distributed Systems:** Designing scalable architectures with `Spring Cloud`, asynchronous event-driven communication via **RabbitMQ**, distributed caching with **Redis**, and S3-compatible object storage using **MinIO**, fully containerized with **Docker**.
* **High-Concurrency & Financial Integrity:** Engineering real-money transaction workflows with strict **ACID** compliance, resolving **race conditions** via pessimistic/optimistic locking, and enforcing **idempotency** across payment webhooks and distributed services.
* **Local AI & Real-Time Systems:** Building **RAG (Retrieval-Augmented Generation)** pipelines powered by locally hosted LLMs (`Llama` / `Ollama`) and vector embeddings, paired with low-latency **WebSocket** communication.
* **Database & Security:** Relational schema design (`PostgreSQL`, `MS SQL Server`), ORM query optimization (resolving N+1 issues in `JPA/Hibernate`), and stateless authentication (`OAuth2`, `JWT`).

---

### 🛠️ Technical Stack

| Layer | Technologies |
| :--- | :--- |
| **Backend & Core** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=Spring-Security&logoColor=white) ![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=Hibernate&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white) |
| **Microservices & Infra** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) ![Redis](https://img.shields.io/badge/Redis_Cache-DC382D?style=flat-square&logo=redis&logoColor=white) ![MinIO](https://img.shields.io/badge/MinIO_S3-C72E49?style=flat-square&logo=minio&logoColor=white) |
| **Databases** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![MS SQL Server](https://img.shields.io/badge/MS_SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white) |
| **Frontend** | ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) |
| **AI & Real-Time** | ![Ollama](https://img.shields.io/badge/Ollama_/_Llama-000000?style=flat-square&logo=meta&logoColor=white) ![RAG](https://img.shields.io/badge/RAG_Pipeline-4B32C3?style=flat-square) ![WebSockets](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white) |

---

### 🚀 Key Engineering Projects

#### 🃏 [Online Poker Platform — Transaction Engine & Microservices](https://github.com/MSS301-Project-G1/Poker-BE) *(Full-Stack)*
* **Tech Stack:** `Java`, `Spring Boot`, `React`, `PostgreSQL`, `Redis`, `RabbitMQ`, `MinIO (S3)`, `Docker`, `PayOS`
* **Engineering Highlights:** 
  * Architected the end-to-end **real-money transaction** and virtual shop subsystem across backend and frontend.
  * Eliminated **race conditions** during concurrent balance mutations and item purchases using database locking and transactional isolation.
  * Enforced **idempotency** and webhook signature verification for payment callbacks to prevent double-spending and duplicate top-ups.
  * Integrated **Redis** for high-speed caching/state management, **RabbitMQ** for asynchronous event processing, and **MinIO S3** for managing custom digital assets (card skins, avatar frames).

#### 🏠 [HouseWiseAI — Intelligent Real Estate Platform](https://github.com/thanhtungse192400/HouseWiseAI) *(Full-Stack & AI)*
* **Tech Stack:** `TypeScript`, `React`, `WebSocket`, `Local LLM (Llama / Ollama)`, `RAG`
* **Engineering Highlights:**
  * Built full-stack CRUD workflows integrated with a low-latency **WebSocket real-time chat system** for instant user-agent communication.
  * Engineered a local AI assistant using **Llama** and a **RAG (Retrieval-Augmented Generation)** pipeline to query domain-specific property data locally.

#### ⚡ [EV Charging Station Management System](https://github.com/thanhtungse192400/EVchargingSystem) *(Frontend)*
* **Tech Stack:** `C#`, `JavaScript`, `Map UI Integration`
* **Engineering Highlights:**
  * Developed interactive **map-based UI** components for locating charging stations, viewing real-time slot availability, and navigating user booking workflows.
