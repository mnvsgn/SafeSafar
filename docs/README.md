# 🛡️ SafeSafar 

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/mnvsgn/SafeSafar?style=for-the-badge)](https://github.com/mnvsgn/SafeSafar/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/mnvsgn/SafeSafar?style=for-the-badge)](https://github.com/mnvsgn/SafeSafar/network/members)
[![GitHub issues](https://img.shields.io/github/issues/mnvsgn/SafeSafar?style=for-the-badge)](https://github.com/mnvsgn/SafeSafar/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/mnvsgn/SafeSafar?style=for-the-badge)](https://github.com/mnvsgn/SafeSafar/pulls)
[![GitHub last commit](https://img.shields.io/github/last-commit/mnvsgn/SafeSafar?style=for-the-badge)](https://github.com/mnvsgn/SafeSafar/commits)
[![GitHub license](https://img.shields.io/github/license/mnvsgn/SafeSafar?style=for-the-badge)](https://github.com/mnvsgn/SafeSafar/blob/main/LICENSE)

**A smart tourist safety and security platform for Smart India Hackathon 2025**

---

### 🛠️ **Tech Stack**

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Native](https://img.shields.io/badge/react_native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Blockchain](https://img.shields.io/badge/blockchain-%23000000.svg?style=for-the-badge&logo=ethereum&logoColor=white)

</div>

---

## 📋 Table of Contents

- [🚀 About](#-about)
- [✨ Features](#-features)
- [🏗️ Architecture](#️-architecture)
- [📦 Installation](#-installation)
- [🛠️ Usage](#️-usage)
- [📂 Project Structure](#-project-structure)
- [🤝 Contributing](#-contributing)

---

## 🚀 About

> **SafeSafar** is a comprehensive tourist safety platform designed for **Smart India Hackathon 2025 (Problem Statement 25002)**

### 🎯 **Mission**
Enable tourists to travel with confidence across India through cutting-edge technology and real-time safety solutions.

### 🔑 **Core Technologies**
- 🔗 **Blockchain-secured digital IDs**
- 📍 **Real-time geo-fencing alerts**
- 🤖 **AI-powered anomaly detection**
- 🚨 **Emergency response system**
- 🌐 **Multilingual accessibility**

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🔐 **Security & Identity**
- **Digital Tourist ID** — KYC-based blockchain onboarding
- **Data Privacy Engine** — End-to-end encryption
- **GDPR Compliance** — Secure data handling

</td>
<td width="50%">

### 📱 **User Experience**
- **Tourist Dashboard** — Safety scores & itinerary
- **Multilingual Support** — 10+ Indian languages
- **Voice Accessibility** — Audio navigation

</td>
</tr>
<tr>
<td width="50%">

### 🌍 **Location Services**
- **Geo-Fencing Alerts** — Unsafe zone warnings
- **Live Location Tracking** — Real-time positioning
- **Route Optimization** — Safe travel suggestions

</td>
<td width="50%">

### 🚨 **Emergency Response**
- **Panic Button** — Instant SOS alerts
- **Live Location Sharing** — Emergency coordination
- **Automated e-FIRs** — Quick incident reporting

</td>
</tr>
</table>

### 🤖 **AI/ML Capabilities**
- **Anomaly Detection** — Unusual pattern recognition
- **Risk Assessment** — Predictive safety scoring
- **Behavior Analysis** — Travel pattern insights

### 👮 **Law Enforcement Tools**
- **Interactive Heatmaps** — Crime pattern visualization
- **Real-time Dashboards** — Incident monitoring
- **Automated Reporting** — Streamlined documentation

---

## 🏗️ Architecture

```mermaid
graph TB
    subgraph "Client Layer"
        MA[Mobile App<br/>React Native]
        WD[Web Dashboard<br/>React.js]
        LE[Law Enforcement<br/>Portal]
    end
    
    subgraph "API Gateway"
        AG[API Gateway<br/>Load Balancer<br/>Rate Limiting]
    end
    
    subgraph "Microservices"
        AS[Auth Service]
        DIS[Digital ID Service]
        GS[Geo-fencing Service]
        ES[Emergency Service]
        AML[AI/ML Service]
        MS[Multilingual Service]
        NS[Notification Service]
    end
    
    subgraph "Data Layer"
        BC[Blockchain<br/>Hyperledger Fabric]
        MDB[(MongoDB<br/>User Data)]
        RDS[(Redis<br/>Cache)]
        ES_DB[(Elasticsearch<br/>Analytics)]
    end
    
    subgraph "External APIs"
        GM[Google Maps API]
        WA[Weather API]
        SMS[SMS Gateway]
        PUSH[Push Notifications]
    end
    
    MA --> AG
    WD --> AG
    LE --> AG
    AG --> AS
    AG --> DIS
    AG --> GS
    AG --> ES
    AG --> AML
    AG --> MS
    AG --> NS
    
    AS --> MDB
    DIS --> BC
    GS --> MDB
    ES --> MDB
    AML --> ES_DB
    MS --> RDS
    
    GS --> GM
    ES --> SMS
    NS --> PUSH
    AML --> WA
```

---

## 📦 Installation

### **Prerequisites**
- Node.js (v16+)
- MongoDB
- Redis
- Docker (optional)

### **Quick Start**

```bash
# Clone the repository
git clone https://github.com/mnvsgn/SafeSafar.git
cd SafeSafar

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env

# Start the development environment
npm run dev
```

### **Docker Setup**

```bash
# Build and run with Docker Compose
docker-compose up --build
```

---

## 🛠️ Usage

### **Development Commands**

```bash
# Start development server
npm start

# Run tests
npm test

# Build for production
npm run build

# Lint code
npm run lint

# Format code
npm run format
```

### **Environment Configuration**

| Variable | Description | Required |
|----------|-------------|----------|
| `PORT` | Server port | ✅ |
| `MONGODB_URI` | Database connection | ✅ |
| `REDIS_URL` | Cache connection | ✅ |
| `JWT_SECRET` | Authentication key | ✅ |
| `BLOCKCHAIN_RPC` | Blockchain endpoint | ✅ |

---

## 📂 Project Structure

```
SafeSafar/
├── 📱 frontend/
│   ├── mobile/              # React Native app
│   │   ├── src/
│   │   ├── components/
│   │   └── screens/
│   └── web/                 # Web portal & dashboard
│       ├── src/
│       └── public/
│
├── ⚡ backend/
│   ├── auth-service/        # Authentication & authorization
│   ├── digital-id-service/  # Blockchain identity management
│   ├── geofencing-service/  # Location-based services
│   ├── emergency-service/   # SOS & incident handling
│   ├── anomaly-ml-service/  # AI/ML analytics
│   └── multilingual-service/ # Language processing
│
├── ⛓️ blockchain/           # Smart contracts
│   ├── contracts/
│   └── migrations/
│
├── 🤖 ai-ml/               # Machine learning models
│   ├── models/
│   ├── datasets/
│   └── pipelines/
│
├── 🐳 infra/               # Infrastructure
│   ├── docker/
│   ├── kubernetes/
│   └── ci-cd/
│
├── 📚 docs/                # Documentation
│   ├── api/
│   ├── architecture/
│   └── user-guides/
│
└── 📄 README.md
```

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### **Getting Started**

1. **Fork** the project
2. **Clone** your fork
   ```bash
   git clone https://github.com/your-username/SafeSafar.git
   ```
3. **Create** a feature branch
   ```bash
   git checkout -b feature/amazing-feature
   ```
4. **Commit** your changes
   ```bash
   git commit -m 'Add some amazing feature'
   ```
5. **Push** to the branch
   ```bash
   git push origin feature/amazing-feature
   ```
6. **Open** a Pull Request

### **Development Guidelines**

- Follow the existing code style
- Write tests for new features
- Update documentation as needed
- Ensure all tests pass before submitting

### **Issue Reporting**

Found a bug? Have a feature request? [Open an issue](https://github.com/mnvsgn/SafeSafar/issues) and we'll address it promptly.

---

<div align="center">

### 🌏 **SafeSafar — Safe. Smart. Safar.** ✈️

**Made with ❤️ by the SafeSafar Team**

---

**© 2025 SafeSafar Team. All rights reserved.**

</div>