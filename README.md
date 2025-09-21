# Hi there, I'm Sultan Mahmud 👋

## 🚀 Backend Developer | Python Specialist | Distributed Systems Enthusiast

**Building scalable cloud systems with Python, AWS, and Docker**

Currently seeking remote backend roles & freelance projects

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=blue)](https://www.linkedin.com/in/sultan-mahmud-b25b25130/)
[![Email](https://img.shields.io/badge/Hire_Me!-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kaziiriad@gmail.com)
![Open to Work](https://img.shields.io/badge/Open_to_Remote-6f42c1?style=for-the-badge)
[![Upwork](https://img.shields.io/badge/UpWork-Freelance-6FDA44?style=for-the-badge&logo=Upwork&logoColor=green)](https://www.upwork.com/freelancers/~01018d7f165a0de159)
[![Resume](https://img.shields.io/badge/Resume-Download-4CAF50?style=for-the-badge)](https://docs.google.com/document/d/1eiou6NCl408uRhqx-_GazGj_YBPiKtliEkBcOPL95iI/edit?tab=t.0)

## 💼 Current Status

- 🔍 **Open to:** Remote backend positions & freelance projects
- 🚀 **Focus:** Python development with cloud infrastructure (AWS/Docker)
---
## 🏆 Core Competencies

### 💻 Backend Development
![Python](https://img.shields.io/badge/Python-Expert-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-Pro-005571?style=flat&logo=fastapi)
![Django](https://img.shields.io/badge/Django-Intermediate-092E20?style=flat&logo=django&logoColor=white)


### ☁️ Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-EC2/S3/ASG-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-Load_Balancer-009639?style=flat&logo=nginx&logoColor=white)

![RabbitMQ](https://img.shields.io/badge/RabbitMQ-Message_Broker-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-Task_Queues-37B24D?style=flat&logo=celery&logoColor=white)
![IaC](https://img.shields.io/badge/Infrastructure_as_Code-Pulumi/Ansible-EE0000?style=flat)

### 🗄️ Data Management
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-336791?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-Caching/Queues-DC382D?style=flat&logo=redis&logoColor=white)
---


## 🌟 Featured Projects

### 🔗 [Scalable URL Shortener Microservice](https://github.com/kaziiriad/url-shortener-scalable)
**High-performance URL shortener with dual database architecture and AWS infrastructure**
- **Engineered a scalable microservice** using `FastAPI` with `Redis` caching for lightning-fast redirects and `PostgreSQL` for key management alongside `MongoDB` for URL storage.
- **Implemented intelligent key pre-population system** using `Celery` workers to maintain a pool of unused short URL keys for instant URL creation without database latency.
- **Built comprehensive load balancing solution** with `Nginx` featuring rate limiting, caching, and traffic distribution across multiple application instances for high availability.
- **Automated AWS infrastructure deployment** using `Pulumi` for Infrastructure as Code and `Ansible` for configuration management, including VPC setup, security groups, and bastion host access.
- **Designed fault-tolerant architecture** with background task processing, automated cleanup jobs, and comprehensive monitoring via `Celery Flower` dashboard.
- **Implemented comprehensive testing framework** using `pytest` with mocking for unit/integration tests and `Docker Compose` for multi-service orchestration.

**Tech Stack:** `FastAPI` `Redis` `PostgreSQL` `MongoDB` `Celery` `Nginx` `Docker` `Pulumi` `Ansible` `AWS`

### 💰 [Installment Manager System](https://github.com/kaziiriad/installment_manager)
**Full-stack financial management application for tracking installments and payments**
- **Backend:** High-performance API built with `FastAPI`, using `SQLAlchemy` for ORM with a `PostgreSQL` database.
- **Frontend:** Modern and responsive UI built with `React`, `TypeScript`, and `Vite`, styled with `Tailwind CSS` and `Shadcn UI`.
- **Asynchronous Tasks:** `Celery` and `Redis` manage background jobs like sending OTP and due date notification emails.
- **Authentication:** Secure JWT-based authentication with role-based access for customers and admins.
- **Data Management:** `Alembic` handles database schema migrations, and `TanStack Query` manages server state on the frontend.
- **DevOps:** Fully containerized with `Docker` and `Docker Compose` for reproducible development and deployment environments.

**Tech Stack:** `FastAPI` `React` `TypeScript` `PostgreSQL` `SQLAlchemy` `Redis` `Celery` `Docker` `Tailwind CSS` `Shadcn UI` `Alembic`

### 🚀 [Scalable Multi-Channel Notification System](https://github.com/kaziiriad/notification_system)
**Real-time notification system for multiple channels**
  - **Modern Backend:** Built with Python and FastAPI for high-performance, asynchronous API endpoints.
  - **Multi-Channel Delivery:** Supports sending notifications through various channels like Email, SMS, and Push Notifications.
  - **Asynchronous & Scalable:** Leverages Celery and RabbitMQ for background task processing, ensuring the system can handle high-volume loads without blocking.
  - **Robust Data Storage:** Uses PostgreSQL for reliable data persistence, managed with Alembic for smooth database migrations.
  - **Containerized Environment:** Fully containerized with Docker and Docker Compose for consistent development, testing, and deployment.
  - **Comprehensive Testing:** Includes a full suite of tests using pytest to ensure code quality and reliability.

**Tech Stack:** `FastAPI` `Celery` `PostgreSQL` `RabbitMQ` `Redis` `Alembic` `SQLAlchemy` `Docker` `Pytest`

### 🎬 [StreamBuddy: Scalable Video Streaming Platform](https://github.com/kaziiriad/streambuddy)
**Full-Stack advanced video streaming solution with adaptive bitrate technology**

  - **Engineered a secure and scalable video platform** with a `Django REST API` and a `React/TypeScript` frontend, architected for high-performance adaptive streaming.
  - **Implemented a robust security model**, using `dj-rest-auth` for token-based authentication and a protected media workflow (via Nginx `X-Accel-Redirect`) to ensure only authorized users can access streaming content.
  - **Built an asynchronous video processing pipeline** using `Celery`, `Redis`, and `FFMPEG` to transcode videos for `DASH` playback, ensuring a smooth, low-latency user experience.
  - **Automated the entire cloud workflow**, from provisioning `AWS S3` infrastructure with `Pulumi` and configuring servers with `Ansible`, to deploying the `Docker`-containerized application via `GitHub Actions`.
  
  **Tech Stack:** `Django` `React` `Celery` `Redis` `PostgreSQL` `FFMPEG` `DASH` `AWS S3` `Nginx` `Docker` `Pulumi` `Ansible`    

### 🔄 [Highly Available Task Management System](https://github.com/kaziiriad/todo_application)
**Enterprise-grade Todo application with AWS infrastructure**
- Engineered full-stack application with FastAPI backend and React frontend
- Implemented Infrastructure as Code using Pulumi for AWS resource management
- Designed fault-tolerant architecture with load balancing across multiple AZs
- Built PostgreSQL replication system with automated backup/recovery
- Integrated Redis Sentinel for high availability caching

**Tech Stack:** `FastAPI` `React` `AWS EC2` `PostgreSQL` `Redis Sentinel` `Nginx` `Docker`

### ⚡ [Distributed Job Queue System](https://github.com/kaziiriad/job-queue-system-2.0)
**Scalable job processing system with advanced features**
- **Developed a distributed job queue system** using `FastAPI` and `Redis` to manage asynchronous tasks with priority-based queuing and automatic worker scaling.
- **Implemented a real-time monitoring dashboard** with `Jinja2` templates to provide visibility into job status, queue metrics, and worker activity.
- **Engineered an automatic worker scaling mechanism** based on job load and worker availability, using `Docker Swarm` to dynamically adjust resources.
- **Created a comprehensive error handling and fault tolerance system**, including automatic retries for failed jobs and a dead-letter queue for unrecoverable tasks.
- **Designed a job dependency feature** to ensure complex workflows are executed in the correct order, improving system reliability.
- **Containerized all services** (`API`, `Worker`, `Monitor`) using `Docker` for consistent deployment and simplified management.

**Tech Stack:** `FastAPI` `Redis` `Docker Swarm` `Jinja2`


---

## 💼 Professional Experience

**Backend Developer Intern** @ Cooking Station *(June 2024 - August 2024)*  
✅ Designed RBAC dashboard for **200+ users**  
✅ Automated 40% of manual account processes  
✅ Built real-time meal analytics system


---

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

---

## 📝 Content Creation & Community

### 📖 Technical Writing
- **200,000+ readers** on Quora with tech insights in Bengali
- **Nearly 200 followers** engaging with technology content
- Topics: Technology, Programming, System Design

### 🎥 YouTube Channel: "I.T. Darshonik"
- **40+ instructional videos** in Bengali
- Bridging the language gap in tech education
- Focus on making technology accessible to Bengali-speaking developers

---

## 🎯 What I'm Currently Working On

- 🔭 Building more scalable microservices architectures
- 🌱 Learning advanced cloud-native patterns and Kubernetes
- 👯 Looking to collaborate on open-source backend projects
- 💬 Ask me about **Python, Django, FastAPI, AWS, System Design**

---

## 📫 Let's Connect!

Let's build something amazing together! Whether you're looking for a backend developer to join your team or need help with a complex Python project, I'm here to help.

**I'm actively seeking:**  
🚀 Remote backend engineering roles  
💼 Complex Python/AWS freelance projects  

- 📧 **Email:** kaziiriad@gmail.com
- 📱 **Phone:** +880 1683152495
- 🌍 **Location:** Dhaka, Bangladesh


<div align="center">

### "Building robust systems that scale, one commit at a time" 🚀

![Profile Views](https://komarev.com/ghpvc/?username=kaziiriad&color=blue&style=flat-square)

</div>