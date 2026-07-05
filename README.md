<div align="center">

# Sultan Mahmud

**Backend · DevOps & Platform Engineer** | Distributed Systems · Kubernetes · AWS · Polyglot Microservices

*I design backend systems end-to-end — and I automate the infrastructure that runs them.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/sultan-mahmud-b25b25130/)
[![Email](https://img.shields.io/badge/Email-Hire_Me!-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kaziiriad@gmail.com)
[![Medium](https://img.shields.io/badge/Medium-Read-12100E?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@kazisultanmahmud)
![Remote](https://img.shields.io/badge/Open_to-Remote-6f42c1?style=flat-square)

</div>

---

## 👋 Who I Am

Backend Engineer with DevOps & Platform depth from **Dhaka, Bangladesh**, open to **worldwide remote** roles. I design backend systems end-to-end — async messaging, distributed workers, polyglot microservices, video pipelines — and I run them on production Kubernetes and multi-AZ AWS with full automation from commit to production.

**My focus areas:**
- ☁️ **AWS infrastructure** (EC2, Lambda, VPC, EventBridge, IAM, CloudWatch)
- 🚀 **Kubernetes & Platform engineering** (K3s, autoscaling, observability)
- 🛠️ **Infrastructure-as-Code** (Pulumi, Terraform, Ansible)
- 🐍 **Polyglot backends** (Go for hot paths, Python for business logic)
- 📊 **Observability** (OpenTelemetry, Grafana, Tempo, Loki, Prometheus)

---

## 📊 By The Numbers

```
⚡ 1.53ms     Go P95 redirect latency (vs 2-11ms Python baseline)
💰 60%         cost reduction on AWS via intelligent autoscaling
🖥️  11+        EC2 instances automated across 3 availability zones
📈 99.9%       uptime on multi-AZ production deployments
🔄 4-layer     autoscaling architecture (reactive + ML predictive)
📦 1K+         concurrent users supported in load-tested systems
🎯 500+        DSA problems solved
📖 200K+       readers on Quora in Bengali
```

---

## 🏆 What I've Built

- [**ElastiKube**](https://elastikubedemo.vercel.app/) — ML-enhanced K3s autoscaler on AWS
  - **60% cost reduction**, 4-layer scaling (time-aware, flash-sale detector, Prophet ML forecast, reactive HPA)
  - Event-driven Lambdas + DynamoDB distributed locks + WAL crash recovery, multi-AZ round-robin
  - 17 CloudWatch alarms, spot instances with automatic On-Demand fallback
- [**Snipl (URL Shortener)**](https://github.com/kaziiriad/url-shortener-scalable) — polyglot microservices (Go Chi + Python FastAPI), live on Render + Cloudflare
  - **P95 1.53ms** Go redirect latency, **1,000+ RPS**, **99.82% cache hit rate**, **0% errors**
  - Redis cache-aside (30-min TTL), PostgreSQL `FOR UPDATE SKIP LOCKED` advisory locks, MongoDB projection (~60% payload cut)
  - Full OpenTelemetry stack (Tempo, Loki, Grafana), Celery key pre-population, Nginx load balancing + rate limiting
- [**StreamBuddy**](https://github.com/kaziiriad/streambuddy) — DASH video streaming with FFMPEG transcoding pipeline
  - Multi-resolution transcoding (480p → 4K) producing 4-second DASH segments, ~70% size reduction
  - **Nginx `X-Accel-Redirect`** for token-secured media, custom throttle tiers (anon/auth/upload/stream)
  - Django REST + Celery + AWS S3, full CI/CD via GitHub Actions + Pulumi + Ansible
- [**Notification System**](https://github.com/kaziiriad/notification_system) — async multi-channel microservice (Email/SMS/Push)
  - JWT scoped service-to-service auth, Redis token-bucket rate limiting (100 req/min + 20 burst)
  - Direct `pika` consumer (no Celery), retry with exponential backoff (1s/2s/4s), idempotent worker
  - Redis cache-aside (30s TTL), structured JSON logging, custom exception hierarchy
- [**Job Queue**](https://github.com/kaziiriad/job-queue-system-2.0) — distributed worker orchestration
  - Four-service split (API / Worker / Monitor / Redis), priority queues + dependency DAG
  - Automatic worker auto-scaling by load-per-worker via Docker Swarm, dead-letter queue semantics
  - Real-time web dashboard, stress-test harness (light/medium/heavy/dependency/priority/custom)
- [**Installment Manager**](https://github.com/kaziiriad/innovative_internship_test) — full-stack fintech app
  - FastAPI + PostgreSQL/SQLAlchemy backend, React + TypeScript + Tailwind + Shadcn UI frontend
  - JWT RBAC for customer/admin, Celery + Redis for OTP/email background jobs, Alembic migrations
- [**HA Todo Application**](https://github.com/kaziiriad/todo_application) — high-availability task manager on AWS
  - Multi-AZ architecture, PostgreSQL replication with automated backup/recovery
  - Redis Sentinel for HA caching, Pulumi IaC, Nginx load balancing

📌 **Detailed writeups live in each repo's README — I keep this page scannable.**

> 🔧 **Currently building:** [**TesseraKt**](https://github.com/kaziiriad) — managed Kubernetes SaaS platform (Go + Python). Cluster lifecycle automation in progress.

---

## 🛠️ Tech Stack

**Languages:** Python, Go, JavaScript/TypeScript, SQL \
**Frameworks:** FastAPI, Django, Gin, React, Vite \
**Cloud & Infra:** AWS (EC2, Lambda, VPC, EventBridge, S3, CloudWatch, IAM), Kubernetes (K3s), Docker, Nginx, PgBouncer \
**IaC & Automation:** Pulumi, Ansible, GitHub Actions, Docker Compose \
**Observability:** OpenTelemetry, Grafana, Tempo, Loki, Prometheus, CloudWatch \
**Data:** PostgreSQL, Redis, MongoDB, Celery, RabbitMQ \
**Practices:** Microservices, distributed systems, fault tolerance, GitOps, blue/green deploys

---

## 💼 Experience

**Full-Stack Developer (Contract) — Independent Practice** *(Mar 2026 – Present, Remote)* \
Building a Customer Relationship Management platform for Australia's NDIS providers — participant management, plan utilization, service booking, invoicing. Solo contractor. I own architecture, data model, UX direction, and backend scoping end-to-end. Coding agent for routine UI only — I review and own every shipped line. \
Stack: React, Vite, TypeScript, Tailwind, shadcn/ui; FastAPI + PostgreSQL (scoped).

**Backend Engineer & Product Builder** *(Remote, August 2024 – Present)* \
Designing, deploying, and operating 5 production-grade backend systems across messaging, async pipelines, video, and infrastructure. Acting as solo architect and operator — IaC, deployment, observability, and incident response.

- Shipped systems across multi-AZ AWS with full IaC + observability stack
- Replaced manual provisioning with one-command Pulumi + Ansible deploys
- Built ElastiKube K8s autoscaler: **60% AWS cost reduction** with ML predictive scaling

**Selected systems:** [ElastiKube](https://elastikubedemo.vercel.app/) · [Snipl](https://github.com/kaziiriad/url-shortener-scalable) · [StreamBuddy](https://github.com/kaziiriad/streambuddy) · [Notification](https://github.com/kaziiriad/notification_system) · [Job Queue](https://github.com/kaziiriad/job-queue-system-2.0) · [Installment Manager](https://github.com/kaziiriad/innovative_internship_test) · [HA Todo](https://github.com/kaziiriad/todo_application)

**Backend Developer @ Cooking Station** *(Jun 2024 – Aug 2024, Dhaka)* \
Built role-based admin dashboard for 200+ users, automating 40% of manual account workflows. Implemented cron-based scheduling system. \
Stack: Django, MySQL, Docker.

---

## 🎓 Education

**B.Sc. Computer Science & Engineering** — Daffodil International University (2017–2022)

**System Design & Backend Engineering with AWS** — Poridhi (Intensive production engineering program: 100+ hands-on labs in K8s, AWS, distributed systems)

---

## ✍️ Writing & Community

- 📝 [Building a Scalable URL Shortener: System Design to Production](https://medium.com/@kazisultanmahmud/building-a-scalable-url-shortener-from-system-design-to-production-ready-microservice-b2ebf8790e84)
- 📺 [I.T. Darshonik YouTube](https://youtube.com/@itdarshonik) — 40+ Bengali tech videos
- 🌍 Quora Bengali tech blog — 200K+ readers

---

## 📫 Get In Touch

Looking for a DevOps / Platform / Backend Engineer who can **own infrastructure end-to-end**, ship polyglot microservices, and automate from commit to production?

📧 **Email:** kaziiriad@gmail.com \
💼 **LinkedIn:** [Sultan Mahmud](https://www.linkedin.com/in/sultan-mahmud-b25b25130/) \
 **Blog:** [Medium](https://medium.com/@kazisultanmahmud) \
📺 **YouTube:** [I.T. Darshonik](https://youtube.com/@itdarshonik)

---

<div align="center">

### "Building robust systems that scale, one commit at a time" 🚀

![Profile Views](https://komarev.com/ghpvc/?username=kaziiriad&color=blue&style=flat-square)

**⭐ If you find my projects useful, consider starring them!**
</div>
