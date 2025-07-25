# 🧠 Coding Plateform

**Coding Plateform** is an interactive environment where users can practice and showcase their coding skills. Built with modern web technologies, it offers real‑time code execution, competitive arenas, and engaging leaderboards to elevate learning.


## 🎯 Features

- 🧪 **Coding Playground**: Write and execute code instantly with custom input.  
- ⚔️ **Coding Arena**: Compete in timed challenges with friends or globally.  
- 🔥 **Battleground Mode**: Real-time code battles with live scoring and ranks.  
- 🧬 **Live Leaderboards**: See who’s topping the charts in real time using WebSockets.  
- 🛡️ **Semaphore System**: Smart request management for safe concurrent code executions.  
- 🐳 **Dockerized**: Smooth setup and deployment with Docker support.  

---

## 🛠️ Technology Stack

- **Frontend**: React, Tailwind CSS, Material UI  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Real-Time**: Socket.IO  
- **Concurrency Management**: Semaphore  
- **Deployment**: Docker, Nodemon  

---

## 🏗️ Architecture Overview

This project is structured into:

- `frontend/`: React SPA with live interactions  
- `backend/`: Express APIs and real-time WebSocket logic  
- `judge0/`: Code execution engine interfaced via API  
- `docker/`: Dockerfile and docker-compose for production builds  
- `.env`: Configurable environment variables for secure and flexible deployment  

---

## ⚙️ Installation

### Prerequisites

- Node.js (v14 or newer)  
- npm  
- MongoDB running locally or remotely  
- Docker (optional but recommended)  

### Clone the Repo

```bash
git clone https://github.com/ShivamMishra2002/Coding_Plateform.git
cd Coding_Plateform
```


### Backend Setup
```
cd backend
npm install
```

### Frontend Setup
```
cd frontend
npm install
npm start
```

