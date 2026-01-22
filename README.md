# 💫 About Me:
### Hi there 👋, I'm Thanh Ngo

I am a software engineering student passionate about **Backend Development** and **System Architecture**. I also have strong capabilities in **Frontend Engineering**, allowing me to build complete end-to-end solutions. My goal is to build high-performance, scalable microservices systems, especially in the FinTech and Banking sectors.

- 🔭 I’m currently working on: **A High-Performance Distributed Microservices Platform**.
- 🌱 I’m currently learning: **DevOps practices** (Docker/K8s), **System Optimization**, and **Advanced Java Core**.
- 👯 I’m looking to collaborate on: Open source Java/Spring Boot projects.
- ⚡ Fun fact: I love diving deep into how databases and operating systems work under the hood!

---

## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/nct.sv) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thanh-ngo-08374024b) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:ngocongthanhsg0812@gmail.com)

---

## 🛠 Tech Stack & Skills

### 🚀 Languages & Backend Frameworks
* ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) **Java:** Specialized in **Spring Boot** (Spring Security, Spring Data JPA) for building robust, enterprise-grade systems.
* ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) **Golang:** Leveraged for high-performance services and handling high-concurrency workloads.
* ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=F7DF1E) **TypeScript/JS:** Developing server-side applications with a focus on asynchronous programming and type safety.
* ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) **Python:** Utilized for data processing tasks and supporting AI/ML Engineering workflows.

### 🏗 Architecture & Design Patterns (Main Focus)
* **Architectural Styles:** Proficient in **Distributed Microservices** and traditional Monolithic architectures.
* **Design Patterns:** Applying **Clean Architecture**, **Domain-Driven Design (DDD)**, and the **State Pattern**.
* **Distributed Systems:** Implementing **Saga Patterns** and **CQRS** for data consistency.

### 📨 Messaging & Integration
* ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka) **Event-Driven Architecture:** Utilizing **Apache Kafka** for resilient communication.
* **API Protocols:** Designing and optimizing system communication via **RESTful APIs** and **gRPC**.

### 💾 Databases & Caching
* ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) **Relational DB:** Expertise in schema design and query optimization.
* ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) **Caching:** Implementing **Redis** for high-speed data retrieval and session management.

### ☁️ DevOps & Infrastructure
* ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) **Containerization:** Packaging apps with **Docker** and managing clusters with **Kubernetes (K8s)**.
* ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) **CI/CD:** Streamlining deployment pipelines using **GitHub Actions**.
* ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) **System Admin:** Proficient in **Linux** environments and shell scripting.

### 🎨 Frontend & Interface
* ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next.js](https://img.shields.io/badge/next.js-000?style=for-the-badge&logo=nextdotjs&logoColor=white) **Frameworks:** Building modern, responsive UIs with **React** and **Next.js**.
* ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) **Styling:** Delivering optimized UI/UX experiences using **TailwindCSS**.
---

# 🏆 My Projects
### *RestaurantSystem: High-Performance Distributed Microservices Platform*

> **Quick Link:** [📂 View Source Code on GitHub](https://github.com/Thanhngo0812/MicroserviceProject.git)

![Java](https://img.shields.io/badge/Java-17%2B-ed8b00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.0-6db33f?style=for-the-badge&logo=spring&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Enabled-2496ed?style=for-the-badge&logo=docker&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-Event_Driven-231f20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium-CDC-blue?style=for-the-badge)

### 📖 Executive Summary
**RestaurantSystem** is a proof-of-concept for a **Distributed Transaction Processing System** built on a Microservices architecture.

Designed with scalability and fault tolerance in mind, this project solves the challenges of data consistency in distributed systems using **Event-Driven Architecture** and **Change Data Capture (CDC)** patterns. These are the same architectural principles used in core banking and high-frequency trading systems to ensure zero data loss.

### 🏗️ System Architecture & CDC Flow
The system follows the **Database-per-Service** pattern, implementing **Debezium** to capture row-level changes from Database Binlogs and stream them to Kafka.

![System Architecture Diagram](https://res.cloudinary.com/dfcb3zzw9/image/upload/v1767682557/Bi%E1%BB%83u_%C4%91%E1%BB%93_kh%C3%B4ng_c%C3%B3_ti%C3%AAu_%C4%91%E1%BB%81.drawio_2_av0pas.png)

### 🚀 Key Features (Banking-Grade Focus)
* **Transactional Integrity:** Implemented **SAGA Pattern (Choreography)** to ensure data consistency across `Order` and `Payment` services.
* **Fault Tolerance:** **Circuit Breaker** implementation (Resilience4j) to prevent cascading failures.
* **Real-time Monitoring:** Integrated Dashboard to visualize Heap Memory, Thread Pools, and Request Latency.
* **Security First:** Centralized Authentication via API Gateway using JWT.
* **Event-Driven Backbone (CDC & Kafka):** Utilized **Debezium** to capture DB changes and stream them to **Kafka**, acting as the core asynchronous mechanism for multiple business workflows. This eliminates service coupling and solves the **Dual-Write problem** efficiently. 
---
[![](https://visitcount.itsvg.in/api?id=ThanhNgo0812&icon=0&color=0)](https://visitcount.itsvg.in)
