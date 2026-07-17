<div align="center">

# Sultan Mahmud

**Backend & DevOps/Platform Engineer** — Distributed Systems · Kubernetes · AWS · Polyglot Microservices

*I design backend systems end-to-end — and I automate the infrastructure that runs them.*

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sultan-mahmud-b25b25130/)
[![Email](https://img.shields.io/badge/Email-Hire_Me!-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kaziiriad@gmail.com)
[![Medium](https://img.shields.io/badge/Medium-Read-12100E?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@kazisultanmahmud)
![Remote](https://img.shields.io/badge/Open_to-Worldwide_Remote-6f42c1?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Backend_·_DevOps_·_Platform-2ea44f?style=flat-square)

</div>

---

## 🟢 Open to Worldwide Remote — Backend / DevOps / Platform Roles

> Built and operated 5 production systems on multi-AZ AWS with full IaC + observability.
> Currently leading ElastiKube (ML-driven K8s autoscaling) and TesseraKt (managed K8s SaaS).

---

## 📊 Headline Metrics

```
⚡ 1.53ms     Go redirect P95 — 2–7× faster than Python baseline
💰 60%         AWS cost reduction via ML-driven K3s autoscaling
📈 99.82%      Cache hit rate · 1,000+ RPS · 0% errors (Snipl production)
🟢 99.9%       Uptime across multi-AZ deployments
🖥️  11+        EC2 instances automated across 3 AZs
🔄 4-layer     Autoscaling architecture (time-aware · flash-sale · Prophet ML · reactive HPA)
📦 1K+         Concurrent users load-tested
🛢️  73         Public repos · 11 years shipping code
```

---

## 🛠️ Tech Stack

**Languages** · `Python` · `Go` · `TypeScript` · `SQL` · `Bash`
**Backend** · `FastAPI` · `Django` · `Django REST` · `Gin` · `Chi` · `Asynq` · `Celery`
**Frontend** · `React` · `Vite` · `Tailwind` · `shadcn/ui`
**Data** · `PostgreSQL` · `Redis` · `MongoDB` · `RabbitMQ` · `PgBouncer`
**Cloud & Infra** · `AWS (EC2 · Lambda · VPC · EventBridge · S3 · CloudWatch · IAM)` · `K3s · Kubernetes` · `Docker · Nginx`
**IaC & Automation** · `Pulumi` · `Terraform` · `Ansible` · `GitHub Actions` · `Docker Swarm`
**Observability** · `OpenTelemetry` · `Grafana` · `Tempo` · `Loki` · `Prometheus` · `CloudWatch`
**Practices** · `Microservices` · `Distributed Systems` · `GitOps` · `Blue/Green` · `Fault Tolerance`

---

## 🏆 Featured Projects

> Pick the order based on what you're optimizing for — ElastiKube first if you lead with
> DevOps/platform depth, Snipl first if you lead with backend performance.

### ⚙️ [ElastiKube](https://github.com/kaziiriad/elastikube) — ML-driven K3s autoscaler on AWS
**60% AWS cost reduction** through a 4-layer scaling architecture: time-aware policies, flash-sale detector, Prophet ML forecasting, and reactive HPA — coordinated via event-driven Lambdas and DynamoDB state.
- Multi-AZ round-robin worker placement, DynamoDB distributed locks, WAL crash recovery
- Spot instances with automatic On-Demand fallback; 17 CloudWatch alarms
- Stack: `AWS Lambda · EventBridge · DynamoDB · EC2 · Prometheus · K3s · CloudWatch`

### 🚀 [Snipl — Scalable URL Shortener](https://github.com/kaziiriad/url-shortener-scalable)
**Polyglot microservices** with a Go Chi redirect service hitting **P95 1.53ms / 99.82% cache hit / 1,000+ RPS** — 2–7× faster than the Python baseline. Live on Render + Cloudflare.
- Hybrid Go + Python stack (Go Asynq workers alt to Celery); Redis cache-aside, MongoDB projection (~60% payload cut)
- PostgreSQL `FOR UPDATE SKIP LOCKED` advisory locks; PgBouncer pool; full OTel + Tempo/Loki/Grafana
- Stack: `Go · Python · FastAPI · Chi · Asynq · Redis · PostgreSQL · MongoDB · OTel · Pulumi · Ansible`

### 🎬 [StreamBuddy](https://github.com/kaziiriad/streambuddy) — DASH video streaming platform
Django REST + Celery pipeline transcoding **480p → 4K DASH** with ~70% size reduction. Token-secured media via **Nginx `X-Accel-Redirect`** + tiered throttling (anon/auth/upload/stream).
- End-to-end CI/CD: GitHub Actions → Pulumi → Ansible
- Stack: `Django · Celery · FFmpeg · AWS S3 · Nginx · Pulumi`

### 🔔 [Notification System](https://github.com/kaziiriad/notification_system) — Multi-channel async microservice
Email/SMS/Push via SendGrid, Twilio, FCM. **Direct `pika` consumer** (no Celery), idempotent worker, exponential backoff (1s/2s/4s).
- JWT scoped service-to-service auth; Redis token-bucket rate limiting (100 req/min + 20 burst); 30s cache-aside
- Stack: `FastAPI · RabbitMQ · pika · PostgreSQL · Redis · JWT`

### 📦 [Distributed Job Queue 2.0](https://github.com/kaziiriad/job-queue-system-2.0)
Four-service split (API · Worker · Monitor · Redis) with **priority queues**, **dependency DAG**, auto-scaling by load-per-worker via Docker Swarm, dead-letter queue, and a real-time web dashboard.
- Interactive stress harness (light / medium / heavy / dependency / priority / custom)
- Stack: `FastAPI · Redis · Docker Swarm · Jinja2`

### 💳 [Installment Manager](https://github.com/kaziiriad/installment_manager) — Full-stack fintech
Customer + admin dashboards with OTP-verified auth, dynamic installment calculator, and weekly/monthly/all-time financial reports.
- Stack: `React · Vite · TypeScript · Tailwind · shadcn/ui · FastAPI · PostgreSQL · Redis · Celery · Alembic`

### ✅ [HA Todo Application](https://github.com/kaziiriad/todo_application) — Multi-AZ on AWS
PostgreSQL replication with automated backup/recovery, Redis Sentinel for HA caching, Nginx LB, full Pulumi IaC across two AZs.

---

## 📂 More Projects

| Project | What it shows |
|---|---|
| Cloud Migration System *(private)* | Multi-account AWS discovery + dependency-ordered migration via Celery; full rollback on failure; LocalStack dev; provider-based namespaces (AWS/Azure/GCP) |
| [Job Queue 1.0](https://github.com/kaziiriad/job-queue-system) | First iteration of the distributed job queue |
| [Project Ideas & Roadmaps](https://github.com/kaziiriad/project-ideas-and-roadmaps) | Curated learning roadmaps (3★) |

---

## 🧭 Currently Building

**TesseraKt** — managed Kubernetes SaaS in Go + Python.
Cluster lifecycle automation (provision, upgrade, observability bootstrap) in progress. *(Coming soon — repo will land under kaziiriad/ shortly.)*

---

## 💼 Experience

**Full-Stack Developer (Contract) — Independent Practice** *(Mar 2026 – Present, Remote)*
Solo contractor building a CRM for an Australian NDIS provider — participant onboarding wizard, NDIS plan/funding tracking, staff roster, timesheets, e-signature capture, PDF generation. I own architecture, data model, UX direction, and backend; coding agent is used only for routine UI scaffolding, which I review and own end-to-end.
- Backend: Django 5.2 + DRF split across 8 apps (`users · roles · teams · staff · roster · timesheets · participants · core`) — custom `RolePermission` with permission substitutions, `{data, error}` response envelope, camelCase wire, services pattern with `transaction.atomic + select_for_update`, integer PKs for system / UUID PKs for domain models
- Frontend: Vite + React 18 + TS + Tailwind + shadcn/ui + Radix + TanStack Query — feature folders (`form-builder · roster · teams · permissions`)
Stack: `Django 5.2 · DRF · SQLite → PostgreSQL · Vite · React 18 · TypeScript · Tailwind · shadcn/ui · TanStack Query`.

**Backend Engineer & Product Builder** *(Remote, Aug 2024 – Present)*
Designing and operating 5 production-grade backend systems across messaging, async pipelines, video, and infrastructure. Acting solo architect/operator: IaC, deployment, observability, incident response.
- Shipped systems across multi-AZ AWS with full IaC + observability stack
- Replaced manual provisioning with one-command Pulumi + Ansible deploys
- Built ElastiKube K8s autoscaler: **60% AWS cost reduction** with ML predictive scaling

**Backend Developer @ Cooking Station** *(Jun 2024 – Aug 2024, Dhaka)*
Role-based admin dashboard for 200+ users, automating 40% of manual account workflows. Cron-based scheduling system.
Stack: `Django · MySQL · Docker`.

---

## 🎓 Education

- **B.Sc. Computer Science & Engineering** — Daffodil International University (2017–2022)
- **System Design & Backend Engineering with AWS** — Poridhi (Intensive production engineering: 100+ hands-on labs in K8s, AWS, distributed systems)

---

## ✍️ Writing & Community

- 📝 [Building a Scalable URL Shortener: System Design to Production](https://medium.com/@kazisultanmahmud/building-a-scalable-url-shortener-from-system-design-to-production-ready-microservice-b2ebf8790e84)
- 📺 [I.T. Darshonik YouTube](https://youtube.com/@itdarshonik) — 40+ Bengali tech videos
- 🌍 Quora Bengali tech blog — 200K+ readers

---

## 📫 Get In Touch

Looking for an engineer who can **own infrastructure end-to-end**, ship polyglot microservices, and automate from commit to production?

📧 **Email:** kaziiriad@gmail.com
💼 **LinkedIn:** [Sultan Mahmud](https://www.linkedin.com/in/sultan-mahmud-b25b25130/)
📝 **Blog:** [Medium](https://medium.com/@kazisultanmahmud)
📺 **YouTube:** [I.T. Darshonik](https://youtube.com/@itdarshonik)

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kaziiriad&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=kaziiriad&theme=tokyonight&hide_border=true" alt="Streak stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kaziiriad&layout=compact&theme=tokyonight&hide_border=true&count_private=true" alt="Top languages" />
</p>

---

<div align="center">

### *"Building robust systems that scale, one commit at a time."*

![Profile views](https://komarev.com/ghpvc/?username=kaziiriad&color=blue&style=flat-square)

**⭐ If you find my projects useful, consider starring them!**

</div>