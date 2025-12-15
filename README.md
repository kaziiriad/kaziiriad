# Hi there, I'm Sultan Mahmud 👋

## 🚀 Backend Engineer | Infrastructure Automation Specialist | Distributed Systems Architect

**Building production-grade distributed systems with automated AWS deployments, achieving sub-5ms response times at 1K+ concurrent users**

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
✅ **Performance Engineering** - Optimized systems achieving sub-5ms response times with 1K+ concurrent users  
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
⚡ Sub-5ms API Response Times Achieved
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
**High Complexity - Full Infrastructure Automation**

**High-performance URL shortener with dual database architecture and production K3s deployment**
- **Architected microservices** separating redirect service (read-heavy, **95% traffic**) from create service (write-heavy) with independent scaling capability and service-specific resource allocation.
- **Implemented Redis-first caching** with MongoDB fallback and Nginx proxy routing, targeting **sub-5ms redirect latency** for optimal user experience.
- **Optimized PostgreSQL operations** using atomic key acquisition with `SELECT FOR UPDATE SKIP LOCKED` for race-free distributed key allocation and parameterized bulk inserts.
- **Implemented comprehensive observability solution** using `OpenTelemetry` for distributed tracing with context propagation, integrated with `Tempo` for trace storage and `Grafana` for visualization to monitor system performance and debug issues across microservices.
- **Deployed production K3s cluster on AWS** using `Pulumi` IaC and `Ansible` with path-based Nginx routing, per-service rate limiting, and CI/CD pipeline via `GitHub Actions`.
- **Engineered fault-tolerant architecture** with `PgBouncer` connection pooling achieving **53% reduction** in database connection overhead, circuit breakers, and retry mechanisms ensuring high availability.
- **Implemented intelligent key pre-population system** using `Celery` workers to maintain a pool of unused short URL keys for instant URL creation without database latency.
- **Automated AWS infrastructure deployment** with VPC setup, security groups, bastion host access, and comprehensive monitoring via `Celery Flower` dashboard.

**Technical Deep Dive:** [Read my Medium articles](https://medium.com/@kazisultanmahmud/)


**Tech Stack:** `FastAPI` `Redis` `PostgreSQL` `MongoDB` `Celery` `Nginx` `Docker` `K3s` `Pulumi` `Ansible` `AWS` `OpenTelemetry` `Tempo` `Grafana` `PgBouncer` `GitHub Actions`

**Key Learnings:**
- Infrastructure as Code best practices
- Multi-server coordination and networking
- Security groups and VPC design
- Automated deployment pipelines
---

### 🔄 [K3s Custom Autoscaler](https://github.com/kaziiriad/k3s-autoscaler-prototype) 🥇
**Most Complex Infrastructure Project - Kubernetes-Centric Autoscaling**

**Prototype Kubernetes autoscaler that dynamically adds/removes worker nodes based on Prometheus metrics (Docker used for local testing only)**

- **Built advanced Kubernetes autoscaling prototype** using Python with atomic operations ensuring consistency across `K3s worker` nodes, `MongoDB` storage, and cluster state management.
- **Implemented comprehensive Kubernetes monitoring** with `Prometheus` metrics collection, `kube-state-metrics` for cluster state, `Node Exporter`, `AlertManager`, and custom metrics endpoints.
- **Engineered intelligent scaling logic** with configurable CPU/memory thresholds, pending pod detection, node readiness checks, and Redis-based cooldown management to prevent scaling thrashing.
- **Designed fault-tolerant Kubernetes architecture** with `Kubernetes API` integration for node lifecycle management, graceful pod eviction before node removal, and automatic rollback mechanisms.
- **Developed robust autoscaling API** using `FastAPI` with endpoints for manual scaling, health checks, real-time metrics visualization, and scaling event history tracking.
- **Created prototype environment** using Docker containers for local testing with K3s master/worker setup, configurable workloads, and comprehensive test scenarios.

**Production Migration Plans:**
- 🚀 **Technology Migration**: Rewrite core autoscaler in Go for better performance and native Kubernetes ecosystem integration
- ☁️ **Infrastructure Migration**: Deploy to AWS using Terraform for IaC with EC2 instances as K3s worker nodes (not containers)
- 🔧 **Enhanced Features**: Implement Kubernetes Cluster Autoscaler integration, custom metrics adapters, and multi-region cluster support
- 📊 **Enterprise Monitoring**: Integrate with AWS CloudWatch, enhance distributed tracing with Jaeger/OpenTelemetry, and implement advanced alerting

**Current Tech Stack (Prototype):** `K3s` `Kubernetes API` `Prometheus` `Grafana` `MongoDB` `Redis` `Python` `FastAPI` `Node Exporter` `AlertManager` `Docker (testing only)`
**Planned Production Stack:** `Go` `Terraform` `AWS EC2` `K3s` `CloudWatch` `Jaeger` `OpenTelemetry` `Kubernetes Cluster Autoscaler`

**Key Learnings:**
- Kubernetes-native autoscaling patterns and node lifecycle management
- Distributed systems monitoring and observability practices
- Atomic operations across multiple system layers
- Kubernetes API integration and cluster state management
- Production-ready infrastructure design for cloud environments
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
**Medium Complexity - Async Communication**

**Real-time notification system for multiple channels**
  - **Modern Backend:** Built with Python and FastAPI for high-performance, asynchronous API endpoints.
  - **Multi-Channel Delivery:** Supports sending notifications through various channels like Email, SMS, and Push Notifications.
  - **Asynchronous & Scalable:** Leverages Celery and RabbitMQ for background task processing, ensuring the system can handle high-volume loads without blocking.
  - **Robust Data Storage:** Uses PostgreSQL for reliable data persistence, managed with Alembic for smooth database migrations.
  - **Containerized Environment:** Fully containerized with Docker and Docker Compose for consistent development, testing, and deployment.
  - **Comprehensive Testing:** Includes a full suite of tests using pytest to ensure code quality and reliability.

**Tech Stack:** `FastAPI` `Celery` `PostgreSQL` `RabbitMQ` `Redis` `Alembic` `SQLAlchemy` `Docker` `Pytest`

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

### **Backend Developer Intern** @ Cooking Station
*June 2024 - August 2024 | Dhaka, Bangladesh*

🎯 **Delivered measurable business impact:**
- Designed RBAC dashboard for **200+ users** with real-time analytics
- Automated **40% of manual processes** through intelligent workflows
- Built production-ready meal scheduling system with cron jobs

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