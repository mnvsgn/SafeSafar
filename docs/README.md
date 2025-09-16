# 🛡️ SafeSafar

<div align="center">

![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Native](https://img.shields.io/badge/react_native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Blockchain](https://img.shields.io/badge/blockchain-%23000000.svg?style=for-the-badge&logo=ethereum&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## 📋 Table of Contents
- [🛡️ SafeSafar](#️-safesafar)
  - [📋 Table of Contents](#-table-of-contents)
  - [🚀 About](#-about)
  - [✨ Features](#-features)
  - [🏗️ Architecture](#️-architecture)
  - [📦 Installation](#-installation)
  - [🛠️ Usage](#️-usage)
  - [📂 Project Structure](#-project-structure)
  - [🤝 Contributing](#-contributing)

---

## 🚀 About

**SafeSafar** is a **smart tourist safety and security platform** built for  
**Smart India Hackathon 2025 (Problem Statement 25002)**.  

It enables **tourists to travel with confidence across India** using:  
✅ Blockchain-secured digital IDs  
✅ Real-time geo-fencing alerts  
✅ AI-powered anomaly detection  
✅ Panic-button emergency responses  
✅ Multilingual and accessible interfaces  

---

## ✨ Features

- 🔐 **Digital Tourist ID** — KYC-based onboarding secured by blockchain  
- 📱 **Tourist Dashboard** — Safety scores, itinerary & notifications  
- 🌍 **Geo-Fencing Alerts** — Warns when entering unsafe zones  
- 🚨 **Emergency Module** — Panic button with live SOS location sharing  
- 🤖 **AI/ML Anomaly Detection** — Flags unusual travel patterns  
- 👮 **Law Enforcement Dashboard** — Heatmaps & automated e-FIRs  
- 🗣️ **Multilingual Support** — 10+ Indian languages + voice accessibility  
- 🔒 **Data Privacy Engine** — End-to-end encryption & GDPR compliance  

---

## 🏗️ Architecture

```
Mobile App (React Native)  <-->  API Gateway (Node.js/Express)
|                           |
Geo-Fencing, Emergency, ID, AI Microservices
|                           |
Blockchain Ledger         Law Enforcement Dashboard (React.js)
```

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/SafeSafar.git

# Navigate to the project directory
cd SafeSafar

# Install dependencies
npm install
```

---

## 🛠️ Usage

```bash
# Start the development server
npm start

# Build for production
npm run build
```

---

## 📂 Project Structure

```
SafeSafar/
├── frontend/
│   ├── mobile/        # React Native app
│   ├── web/           # Web portal & dashboard
│
├── backend/
│   ├── auth-service/  
│   ├── digital-id-service/  
│   ├── geofencing-service/  
│   ├── emergency-service/  
│   ├── anomaly-ml-service/  
│   └── multilingual-service/
│
├── blockchain/        # Smart contracts (Solidity/Hyperledger)
├── ai-ml/             # ML models, pipelines
├── infra/             # Docker, K8s, CI/CD configs
├── docs/              # SRS, diagrams, API docs
└── README.md
```

---

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

<div align="center">

🌏 **SafeSafar — Travel Smart. Stay Safe.** ✈️  
Made with ❤️ by the SafeSafar Team

</div>