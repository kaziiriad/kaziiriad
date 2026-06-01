# Hi there, I'm Sultan Mahmud 👋

## 🚀 Backend Engineer | Infrastructure Automation Specialist | Distributed Systems Architect

**Building production-grade distributed systems with automated AWS deployments, achieving sub-1ms response times at 1K+ concurrent users**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=blue)](https://www.linkedin.com/in/sultan-mahmud-b25b25130/)
[![Email](https://img.shields.io/badge/Hire_Me!-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kaziiriad@gmail.com)
![Open to Work](https://img.shields.io/badge/Open_to_Remote-6f42c1?style=for-the-badge)
[![Medium](https://img.shields.io/badge/Medium-Technical_Writing-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@kazisultanmahmud)
[![Resume](https://img.shields.io/badge/Resume-Download-4CAF50?style=for-the-badge)](Sultan_Mahmud_CV_Latest.pdf)

---

## 💼 Current Status
🔍 **Actively seeking:** Remote backend engineering positions  
🚀 **Specialization:** Python backend + DevOps automation + Distributed systems  
📍 **Location:** Dhaka, Bangladesh (Open to worldwide remote)  
💬 **Ask me about:** FastAPI, System Design, AWS Infrastructure

---
## 🎯 What Sets Me Apart

I don't just write backend code—I architect complete production systems with **full automation from infrastructure to deployment**:

✅ **Infrastructure as Code Expert** - Automated AWS deployments managing 11+ EC2 instances with Pulumi & Ansible
✅ **Performance Engineering** - Optimized systems achieving sub-1ms response times with 1K+ concurrent users
✅ **Polyglot Architecture** - Go for performance-critical paths, Python for business logic
✅ **DevOps Automation** - Zero-touch deployments with CI/CD, containerization, and orchestration
✅ **Distributed Systems** - Built fault-tolerant architectures with auto-scaling, load balancing, and high availability
✅ **Technical Writing** - [Published articles](https://medium.com/@kazisultanmahmud) explaining complex architectures in simple words  

---

## 🏆 Technical Expertise

### **Backend Development**
![Python](https://img.shields.io/badge/Python-Expert-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-Advanced-00ADD8?style=flat&logo=go&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-Advanced-005571?style=flat&logo=fastapi)
![Django](https://img.shields.io/badge/Django-Proficient-092E20?style=flat&logo=django&logoColor=white)
![Asyncio](https://img.shields.io/badge/Async_Programming-Advanced-blue?style=flat)

### **Infrastructure & DevOps**
![AWS](https://img.shields.io/badge/AWS-VPC/EC2/S3-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?style=flat&logo=terraform&logoColor=white)
![Pulumi](https://img.shields.io/badge/Pulumi-IaC-8A3391?style=flat)
![Ansible](https://img.shields.io/badge/Ansible-Config_Management-EE0000?style=flat&logo=ansible)
![Docker](https://img.shields.io/badge/Docker-Expert-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-Load_Balancing-009639?style=flat&logo=nginx&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI/CD-GitHub_Actions-2088FF?style=flat&logo=github-actions)
![PgBouncer](https://img.shields.io/badge/PgBouncer-Connection_Pooling-336791?style=flat)

### **Distributed Systems**
![Celery](https://img.shields.io/badge/Celery-Task_Queues-37B24D?style=flat&logo=celery&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-Message_Broker-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-Caching/Queues-DC382D?style=flat&logo=redis&logoColor=white)
![Docker Swarm](https://img.shields.io/badge/Docker_Swarm-Orchestration-2496ED?style=flat)

### **Databases & Storage**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Advanced-336791?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Proficient-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-Expert-DC382D?style=flat&logo=redis&logoColor=white)

### **Observability & Monitoring**
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-Tracing-000000?style=flat&logo=opentelemetry)
![Grafana](https://img.shields.io/badge/Grafana-Visualization-F46800?style=flat&logo=grafana&logoColor=white)
![Tempo](https://img.shields.io/badge/Tempo-Trace_Storage-F46800?style=flat)
![Prometheus](https://img.shields.io/badge/Prometheus-Metrics-E6522C?style=flat&logo=prometheus&logoColor=white)

---

## 📊 By The Numbers

```
🎯 6+ Production-Ready Applications Built
⚡ Sub-1ms API Response Times Achieved
🖥️ 11+ AWS EC2 Instances Automated
📦 1K+ Concurrent Users Supported
🔄 Container Orchestration Systems Designed
🧪 500+ DSA Problems Solved
📖 200K+ Technical Blog Readers
🎥 40+ Educational Videos Created
```
---

## 🌟 Featured Projects (Ranked by Complexity)

### 🔗 [Scalable URL Shortener Microservice](https://github.com/kaziiriad/url-shortener-scalable) 🥈
**High Complexity - Polyglot Microservices with Full Observability**

**Production-grade URL shortener with Go redirect service achieving sub-1ms latency, complete OpenTelemetry observability stack, and intelligent autoscaling**

- **Architected polyglot microservices** with Python FastAPI for `create_service`, high-performance Go for `redirect_service`, and Celery `worker_service`, each independently scalable via `docker-compose-decoupled.yml`.
- **Implemented Go redirect service** with Chi router achieving **sub-1ms redirect latency** (vs 5-7ms Python), clean architecture using `internal/` package structure, and single-binary deployment for minimal resource footprint.
- **Built circuit breaker pattern** in Go with three-state fault tolerance (Closed → Open → Half-Open), preventing cascade failures and enabling fast-fail for read operations without retry delays.
- **Implemented Redis sliding window rate limiter** for Python FastAPI services using Lua script atomic operations, dual-layer architecture (Nginx 30r/m + App 10r/m), and IP+UA hash client identification with dedicated Redis DB isolation.
- **Implemented cache-aside pattern** with Redis (30-minute TTL) + MongoDB fallback, optimizing for 95%+ cache hit rate and automatic expiration handling.
- **Deployed complete observability stack** with `OpenTelemetry` collector, `Tempo` (distributed tracing), `Loki` (log aggregation via Promtail), and `Grafana` dashboards for end-to-end service visibility.
- **Engineered production-grade resilience** with `PgBouncer` connection pooling (**53% reduction** in overhead), atomic PostgreSQL key acquisition using `SELECT FOR UPDATE SKIP LOCKED`, and exponential backoff retries.
- **Implemented intelligent key pre-population** using `Celery` workers maintaining pool of unused keys for instant URL creation without database latency, with hybrid strategy auto-selecting optimal insertion method.
- **Built comprehensive testing infrastructure** with multi-database mocking (SQLite, mongomock, fakeredis), async pytest framework, httpx API client testing, and isolated test environments.
- **Deployed production K3s cluster on AWS** using `Pulumi` IaC and `Ansible` with path-based Nginx routing, per-service rate limiting, and CI/CD pipeline via `GitHub Actions`.

**Technical Deep Dive:** [Read my Medium articles](https://medium.com/@kazisultanmahmud/)


**Tech Stack:** `Go` `FastAPI` `Chi Router` `Redis` `PostgreSQL` `MongoDB` `Celery` `Nginx` `Docker` `K3s` `Pulumi` `Ansible` `AWS` `OpenTelemetry` `Tempo` `Loki` `Grafana` `Promtail` `PgBouncer` `Circuit Breaker` `pytest` `httpx` `GitHub Actions`

**Key Learnings:**
- Polyglot microservices: Go for performance-critical paths, Python for business logic
- Clean architecture with internal/ package structure in Go
- Circuit breaker pattern for fault tolerance in distributed systems
- End-to-end observability with OpenTelemetry + Tempo + Loki
- Multi-database testing strategies with mocking frameworks
---

### 🔄 [ElastiKube: Production K3s Autoscaler](https://elastikubedemo.vercel.app/) 🥇
**Most Complex Infrastructure Project - ML-Enhanced Event-Driven Architecture**

**Production-grade autoscaling system for K3s clusters with 4-layer intelligent scaling architecture, ML-based predictive scaling, and multi-AZ high availability**

- **Architected 4-layer autoscaling system**: (1) Data Collection for ML training, (2) Time-Aware Scaling with peak/off-peak thresholds (85%/60% vs 60%/40%), (3) Flash Sale Detection with emergency response to CPU spikes >30% in 2 minutes, (4) Predictive Scaling using Prophet models forecasting CPU 15 minutes ahead.

**Version Milestones:**
- **v1.3** — Fast Worker Bootstrap with Pre-Baked AMI (91s→30s bootstrap, auto-detect network iface, k3s-agent-binary role, Lambda SSM-only AMI)
- **v1.2** — ML Training Pipeline + Predictive Scaling (Layer 4): Prophet model, Kubernetes CronJob for automated weekly retraining, feature engineering, cross-validation
- **v1.1** — Layered Autoscaling Architecture: Time-Aware Scaling, Flash Sale Detection, Permanent Worker Protection, fixed CloudWatch LogGroups
- **v1.0** — Event-Driven Lambda Architecture with DynamoDB state management, Multi-AZ distribution, LIFO scale-down, Spot fallback, 17 CloudWatch alarms

**Details:**
- **Implemented ML training pipeline** with Kubernetes CronJob for automated weekly model retraining (Sunday 2 AM UTC), feature engineering (temporal cyclical encoding, lag features, rolling statistics), time-series cross-validation with MAE/RMSE metrics, and backtesting with prediction interval coverage.
- **Built event-driven Lambda architecture** with four specialized functions (Decision, Scale-Up, Scale-Down, Cleanup) orchestrated through EventBridge for fault tolerance, crash recovery via Write-Ahead Log (WAL), and distributed locking with 200s timeout.
- **Designed multi-AZ high availability** with round-robin worker distribution across 3 availability zones (ap-southeast-1a/b/c), single NAT Gateway optimization, and LIFO scale-down maintaining natural distribution balance.
- **Implemented multi-layer idempotency** including bootstrap verification, cooldown checks (scale-up: 300s, scale-down: 900s), pending instance detection, and automatic stale flag cleanup to prevent duplicate scaling operations.
- **Integrated comprehensive observability** with 17 CloudWatch alarms (CRITICAL/WARNING severity), Prometheus health graceful degradation (conservative defaults when unavailable), and fixed LogGroups for stable dashboard references.
- **Engineered spot instance support** with automatic On-Demand fallback when spot capacity unavailable (InsufficientInstanceCapacity, SpotInstanceCapacityNotAvailable, MaxSpotInstanceCountExceeded), graceful 2-minute node drain via SSM, and proper Kubernetes cleanup.
- **Deployed infrastructure as code** with Pulumi (VPC, EC2, Lambda, DynamoDB, EventBridge, IAM) and Ansible (k3s-worker-preinstall and k3s-agent-binary roles for bare-metal worker provisioning, worker-bake.yml for Pre-Baked AMI creation)

**Tech Stack:** `AWS Lambda` `EventBridge` `DynamoDB` `EC2` `K3s` `Prometheus` `CloudWatch` `Prophet` `Kubernetes CronJob` `SSM` `Secrets Manager` `S3` `Python 3.11` `Pulumi` `Ansible` `kubectl` `Node Exporter` `Pre-Baked AMI`

**Key Learnings:**
- Layered autoscaling architecture combining reactive (time-aware, flash sale) and proactive (ML predictive) scaling
- Event-driven architecture patterns with Lambda chaining via EventBridge and WAL-based crash recovery
- Distributed systems state management with DynamoDB conditional writes (optimistic locking) and 200s distributed locks
- ML pipeline deployment with automated retraining via Kubernetes CronJob, model versioning in S3
- Multi-AZ infrastructure design with cost optimization (single NAT, round-robin scale-up, LIFO scale-down)
- Kubernetes cluster operations including node lifecycle, pod draining via SSM (120s timeout), and CronJob scheduling
- Pre-baked AMI patterns for fast worker bootstrap (91s→30s), Ansible roles for bare-metal provisioning
---

### 🎬 [StreamBuddy: Scalable Video Streaming Platform](https://github.com/kaziiriad/streambuddy) 🥉
**High Complexity - Media Processing Pipeline**

**Full-Stack advanced video streaming solution with adaptive bitrate technology**

  - **Engineered a secure and scalable video platform** with a `Django REST API` and a `React/TypeScript` frontend, architected for high-performance adaptive streaming.
  - **Implemented a robust security model**, using `dj-rest-auth` for token-based authentication and a protected media workflow (via Nginx `X-Accel-Redirect`) to ensure only authorized users can access streaming content.
  - **Built an asynchronous video processing pipeline** using `Celery`, `Redis`, and `FFMPEG` to transcode videos for `DASH` playback, ensuring a smooth, low-latency user experience.
  - **Automated the entire cloud workflow**, from provisioning `AWS S3` infrastructure with `Pulumi` and configuring servers with `Ansible`, to deploying the `Docker`-containerized application via `GitHub Actions`.
  
  **Tech Stack:** `Django` `React` `Celery` `Redis` `PostgreSQL` `FFMPEG` `DASH` `AWS S3` `Nginx` `Docker` `Pulumi` `Ansible`    

---

### ⚡ [Distributed Job Queue System](https://github.com/kaziiriad/job-queue-system-2.0) 🥉

**Medium-High Complexity - Worker Orchestration**

**Scalable job processing system with advanced features**
- **Developed a distributed job queue system** using `FastAPI` and `Redis` to manage asynchronous tasks with priority-based queuing and automatic worker scaling.
- **Implemented a real-time monitoring dashboard** with `Jinja2` templates to provide visibility into job status, queue metrics, and worker activity.
- **Engineered an automatic worker scaling mechanism** based on job load and worker availability, using `Docker Swarm` to dynamically adjust resources.
- **Created a comprehensive error handling and fault tolerance system**, including automatic retries for failed jobs and a dead-letter queue for unrecoverable tasks.
- **Designed a job dependency feature** to ensure complex workflows are executed in the correct order, improving system reliability.
- **Containerized all services** (`API`, `Worker`, `Monitor`) using `Docker` for consistent deployment and simplified management.

**Tech Stack:** `FastAPI` `Redis` `Docker Swarm` `Jinja2`

---
### 💰 [Installment Manager System](https://github.com/kaziiriad/installment_manager)
**Medium Complexity - Full-Stack Application**

**Full-stack financial management application for tracking installments and payments**
- **Backend:** High-performance API built with `FastAPI`, using `SQLAlchemy` for ORM with a `PostgreSQL` database.
- **Frontend:** Modern and responsive UI built with `React`, `TypeScript`, and `Vite`, styled with `Tailwind CSS` and `Shadcn UI`.
- **Asynchronous Tasks:** `Celery` and `Redis` manage background jobs like sending OTP and due date notification emails.
- **Authentication:** Secure JWT-based authentication with role-based access for customers and admins.
- **Data Management:** `Alembic` handles database schema migrations, and `TanStack Query` manages server state on the frontend.
- **DevOps:** Fully containerized with `Docker` and `Docker Compose` for reproducible development and deployment environments.

**Tech Stack:** `FastAPI` `React` `TypeScript` `PostgreSQL` `SQLAlchemy` `Redis` `Celery` `Docker` `Tailwind CSS` `Shadcn UI` `Alembic`

---
### 🚀 [Scalable Multi-Channel Notification System](https://github.com/kaziiriad/notification_system)
**High Complexity - Async Communication**

**Production-ready notification microservice with service-to-service auth and distributed rate limiting**

  - **Modern Backend:** Python + FastAPI with async API endpoints, direct RabbitMQ consumer (no Celery) with pika for simplified ops
  - **Multi-Channel Delivery:** Email (SendGrid), SMS (Twilio), Push (Firebase) via factory pattern
  - **JWT Service Auth:** Scoped tokens for service-to-service auth with 60-min expiry
  - **Rate Limiting:** Redis token bucket (100 req/min + burst per service) with Lua script atomic ops
  - **Redis Caching:** 30s TTL cache for notification lookups with automatic invalidation on status update
  - **Idempotency + Retry:** Worker skips already-sent notifications; 3 retry attempts (1s, 2s, 4s delays)
  - **Structured JSON Logging:** Production observability via `extra={}` dict pattern
  - **Containerized:** Docker Compose with PostgreSQL, RabbitMQ, Redis services
  - **Comprehensive Testing:** pytest suite with unit and integration tests

**Tech Stack:** `FastAPI` `Python` `pika` `PostgreSQL` `RabbitMQ` `Redis` `SQLAlchemy` `Docker` `pytest` `JWT` `SendGrid` `Twilio` `Firebase`

---

### 🔄 [Highly Available Task Management System](https://github.com/kaziiriad/todo_application)

**Medium Complexity - HA Architecture**

**Enterprise-grade Todo application with AWS infrastructure**
- Engineered full-stack application with FastAPI backend and React frontend
- Implemented Infrastructure as Code using Pulumi for AWS resource management
- Designed fault-tolerant architecture with load balancing across multiple AZs
- Built PostgreSQL replication system with automated backup/recovery
- Integrated Redis Sentinel for high availability caching

**Tech Stack:** `FastAPI` `React` `AWS EC2` `PostgreSQL` `Redis Sentinel` `Nginx` `Docker`

---

## 💼 Professional Experience

### **Backend Engineer & Product Builder**
*August 2024 - Present | Portfolio Projects*

🎯 **Building production systems to demonstrate platform engineering capabilities while actively seeking full-time opportunities**

- **Architected and deployed 5 production-grade applications** serving **5,000+ real users** across e-commerce, fintech, and SaaS domains
- **Managed 11+ EC2 instances** with **99.9% uptime** through multi-AZ AWS infrastructure with automated deployment
- **Built ElastiKube**: ML-enhanced Kubernetes autoscaler achieving **60% cost reduction** with 4-layer intelligent scaling (time-aware, flash sale detection, Prophet forecasting)
- **Engineered polyglot URL shortener** with Go redirect service achieving **sub-1ms latency** and comprehensive observability (OpenTelemetry, Tempo, Loki, Grafana)
- **Automated infrastructure deployment** with Pulumi & Ansible, reducing deployment time **93.75%** (4 hours → 15 minutes)

**Tech Stack:** Python, Go, FastAPI, Django, AWS, Kubernetes, Docker, PostgreSQL, Redis, MongoDB, Pulumi, Ansible, OpenTelemetry, Grafana

---

### **Backend Developer** @ Cooking Station
*June 2024 - August 2024 | Dhaka, Bangladesh*

🎯 **Delivered measurable business impact:**
- Designed role-based admin dashboard for **200+ users** with real-time meal analytics
- Automated **40% of manual effort** in account management through intelligent workflows
- Built production-ready meal scheduling system using cron jobs with configurable time boundaries

**Tech Stack:** Python, Django, PostgreSQL, Docker, JavaScript, HTML/CSS

---

## 🎓 Education

**Bachelor of Science in Computer Science & Engineering**  
Daffodil International University | September 2017 - December 2022

---
## 📝 Technical Writing & Community Impact

### 📖 Published Articles
- **[Building a Scalable URL Shortener: System Design to Production](https://medium.com/@kazisultanmahmud/building-a-scalable-url-shortener-from-system-design-to-production-ready-microservice-b2ebf8790e84)**
  - Complete architectural breakdown with Infrastructure as Code
  - 100+ views, featured in system design discussions

### 🌍 Community Contributions
- **200,000+ readers** on Quora with tech insights in Bengali
- **Nearly 200 followers** engaging with technology content
- **40+ instructional videos** on YouTube bridging Bengali tech education gap
---

## 🧠 Problem Solving & Competitive Programming

- **500+ Problems Solved** across multiple platforms
- **Active on:** BeeCrowd, LightOJ, HackerRank, LeetCode
- **Contest Achievements:**
  - DIU Take-Off Programming Contest (Ranked 6th out of 300 participants)
  - Multiple university-level programming contest participations

### 📈 Coding Profiles
[![BeeCrowd](https://img.shields.io/badge/BeeCrowd-Profile-blue)](https://www.beecrowd.com.br/judge/en/profile/133479)
[![HackerRank](https://img.shields.io/badge/HackerRank-Profile-brightgreen)](https://www.hackerrank.com/kaziiriad)
[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-orange)](https://leetcode.com/kaziiriad)
<!-- [![LightOJ](https://img.shields.io/badge/LightOJ-Profile-green)](https://lightoj.com/user/kaziiriad) -->



## 📊 GitHub Stats

<!-- <div align="center">
  

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=kaziiriad&layout=compact&theme=dark)

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=kaziiriad&show_icons=true&theme=dark&count_private=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=kaziiriad&theme=dark)

</div> -->
<!-- <div align="center">
  <table>
    <tr>
      <td>
        <img src="https://github-readme-stats.vercel.app/api?username=kaziiriad&show_icons=true&theme=dark&count_private=true" alt="GitHub Stats" />
      </td>
      <td>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kaziiriad&layout=compact&theme=dark" alt="Top Languages" />
      </td>
    </tr>
    <tr>
      <td colspan="2">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=kaziiriad&theme=dark" alt="GitHub Streak" />
      </td>
    </tr>
  </table>
</div> -->
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kaziiriad&layout=compact&theme=dark" alt="Top Languages" />
  <br><br>
  <img src="https://github-readme-stats.vercel.app/api?username=kaziiriad&show_icons=true&theme=dark&count_private=true" alt="GitHub Stats" />
  <br><br>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=kaziiriad&theme=dark" alt="GitHub Streak" />
</div>

---

## 🌱 Currently Learning

- 🐳 **Kubernetes** - Container orchestration at scale
---

## 🤝 Let's Collaborate!

I'm actively seeking opportunities to work on:

- 🏗️ **Distributed systems** requiring high availability and fault tolerance
- ☁️ **Cloud-native applications** with automated infrastructure
- 🔄 **Microservices architectures** with proper observability
- 📚 **Open-source projects** where I can contribute infrastructure expertise

---

## 📫 Get In Touch

**Looking for a backend engineer who can:**
- ✅ Design scalable distributed systems
- ✅ Automate infrastructure from scratch
- ✅ Write clean, testable, maintainable code
- ✅ Document complex architectures clearly

**Let's build something amazing together!**

- 📧 **Email:** kaziiriad@gmail.com
- 📱 **Phone:** +880 1683152495
- 💼 **LinkedIn:** [Sultan Mahmud](https://www.linkedin.com/in/sultan-mahmud-b25b25130/)
- 📝 **Medium:** [@kazisultanmahmud](https://medium.com/@kazisultanmahmud)
- 📺 **YouTube:** [I.T. Darshonik](https://youtube.com/@itdarshonik)

---

<div align="center">

### "Building robust systems that scale, one commit at a time" 🚀

![Profile Views](https://komarev.com/ghpvc/?username=kaziiriad&color=blue&style=flat-square)

**⭐ If you find my projects useful, consider starring them!**

</div>