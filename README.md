# Tran Thanh Tung
**Backend & Full-Stack Software Engineer**  
📍 Ho Chi Minh City, Vietnam | ✉️ [tranthanhtungttt10@gmail.com](mailto:tranthanhtungttt10@gmail.com)

> Software Engineer specializing in **Java / Spring Boot** and **React / TypeScript**. Experienced in designing both **Monolithic** and **Microservices** architectures, with a strong focus on high-concurrency financial transactions, data consistency, and local AI/RAG integration.

---

### 🏛️ Core Engineering Focus

* **System Architecture:** Designing maintainable Monolithic (Layered / Feature-driven) and Distributed Microservices systems (`Spring Cloud`, RESTful APIs, WebSocket).
* **High-Concurrency & Transactions:** Handling real-money transaction flows, ensuring strict **ACID** properties, resolving **race conditions** via pessimistic/optimistic database locking, and enforcing **idempotency** across payment webhooks.
* **Local AI & Real-Time Systems:** Building **RAG (Retrieval-Augmented Generation)** pipelines with locally hosted LLMs (`Llama` / `Ollama`), vector embeddings, and low-latency bidirectional communication via **WebSockets**.
* **Database & Security:** Relational schema modeling (`PostgreSQL`, `MS SQL Server`), ORM query optimization (solving N+1 issues in `JPA/Hibernate`), and stateless authentication (`OAuth2`, `JWT`).

---

### 🛠️ Technical Stack

| Layer | Technologies |
| :--- | :--- |
| **Backend** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=Spring-Security&logoColor=white) ![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=Hibernate&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white) |
| **Frontend** | ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) |
| **AI & Realtime** | ![Ollama](https://img.shields.io/badge/Ollama_/_Llama-000000?style=flat-square&logo=meta&logoColor=white) ![RAG](https://img.shields.io/badge/RAG_Pipeline-4B32C3?style=flat-square) ![WebSockets](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white) |
| **Data & DevOps** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) ![MS SQL Server](https://img.shields.io/badge/MS_SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

---

### 🚀 Key Engineering Projects

#### 🃏 [Online Poker Platform — Payment & Transaction Engine](https://github.com/MSS301-Project-G1/Poker-BE) *(Full-Stack)*
* **Tech Stack:** `Java`, `Spring Boot`, `React`, `PostgreSQL`, `PayOS`
* **Engineering Highlights:** 
  * Architected the end-to-end **real-money transaction** and virtual shop subsystem across both backend and frontend.
  * Eliminated **race conditions** during concurrent balance updates and item purchases using database-level locking and strict transactional isolation.
  * Implemented **idempotency keys** and webhook signature verification for payment gateway callbacks to prevent double-spending and duplicate top-ups.

#### 🏠 [HouseWiseAI — Intelligent Real Estate Platform](https://github.com/thanhtungse192400/HouseWiseAI) *(Full-Stack & AI)*
* **Tech Stack:** `TypeScript`, `React`, `WebSocket`, `Local LLM (Llama / Ollama)`, `RAG`
* **Engineering Highlights:**
  * Built full-stack CRUD workflows paired with a **real-time chat system** powered by **WebSockets** for instant user-agent communication.
  * Designed a local AI assistant using **Llama** and a **RAG (Retrieval-Augmented Generation)** architecture to query domain-specific property data without relying on external paid APIs.

#### ⚡ [EV Charging Station Management System](https://github.com/thanhtungse192400/EVchargingSystem) *(Frontend)*
* **Tech Stack:** `C#`, `JavaScript`, `Map UI Integration`
* **Engineering Highlights:**
  * Developed interactive **map-based UI** components for locating charging stations, viewing slot availability, and navigating core user workflows.
