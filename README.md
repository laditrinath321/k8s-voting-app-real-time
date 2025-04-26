# k8s-voting-app-real-time
🚀 𝗘𝗻𝗴𝗶𝗻𝗲𝗲𝗿𝗶𝗻𝗴 𝗥𝗲𝗮𝗹-𝗧𝗶𝗺𝗲 𝗜𝗺𝗽𝗮𝗰𝘁: 𝗩𝗼𝘁𝗶𝗻𝗴 𝗦𝘆𝘀𝘁𝗲𝗺 𝗿𝗲𝗶𝗺𝗮𝗴𝗶𝗻𝗲𝗱 𝘄𝗶𝘁𝗵 𝗞𝘂𝗯𝗲𝗿𝗻𝗲𝘁𝗲𝘀 ☁️


# 🚀 Real-Time Voting App on Kubernetes

A fully containerized, real-time, auto-scaling voting system designed to handle high-concurrency, built with **Kubernetes**, **Docker**, **Redis**, **PostgreSQL**, and **microservices architecture**.  

---

## 📚 Project Architecture

### Voting App - Kubernetes Architecture

![Voting App Architecture](https://raw.githubusercontent.com/your-username/your-repo/main/assets/voting-app-architecture.jpeg)

> 🛠 Voting App consists of microservices deployed as individual pods on Kubernetes:
> - **Voting App (Python)** — captures votes
> - **Result App (Node.js)** — displays results
> - **Redis** — acts as in-memory cache
> - **PostgreSQL** — stores persistent votes
> - **Worker Service (.NET Core)** — syncs data from Redis to PostgreSQL


---

## 🛠️ Tech Stack

- ☸️ Kubernetes
- 🐳 Docker
- 🐍 Python (Voting Service)
- 📊 Node.js (Result Service)
- 🔧 .NET Core (Worker Service)
- 🚀 Redis (In-Memory DB)
- 🐘 PostgreSQL (Persistent Storage)

---

## 🚦 Features

✅ **Microservices-based Design**  
✅ **Real-time Vote Capturing**  
✅ **Zero-Downtime Deployments**  
✅ **Horizontal Auto-Scaling**  
✅ **In-Memory Caching (Redis)**  
✅ **Persistent Storage (PostgreSQL)**  
✅ **Kubernetes YAML-based Deployment**

---

## 🚀 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/your-username/k8s-voting-app-real-time.git
cd k8s-voting-app-real-time

# Deploy all services to Kubernetes
kubectl apply -f k8s-manifests/
