# 📈 Zerodha Clone — Full-Stack Stock Trading Platform

A production-ready full-stack stock trading platform inspired by **Zerodha**, built using the **MERN Stack**. Features a responsive landing page, interactive trading dashboard, real-time portfolio management, and MongoDB-powered data persistence.

![Tech Stack](https://img.shields.io/badge/Stack-MERN-green?style=flat-square) ![Node](https://img.shields.io/badge/Node.js-v20.x-brightgreen?style=flat-square) ![MongoDB](https://img.shields.io/badge/Database-MongoDB%20Atlas-green?style=flat-square) ![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

---

## 🚀 Features

- 📊 **Interactive Dashboard** — Holdings, Positions, Orders overview
- 📈 **Portfolio Management** — Track investments with real-time P&L
- ❤️ **Watchlist** — Monitor your favourite stocks
- 💰 **Buy & Sell Simulation** — Place market orders with live feedback
- 🔐 **User Authentication** — Secure login and signup flow
- 📉 **Market Overview** — Visual summary of market performance
- 📱 **Responsive Design** — Works seamlessly on all devices
- ⚡ **Fast Modern UI** — Built with React.js and Material UI

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js, Material UI, CSS3, Axios |
| Backend | Node.js, Express.js |
| Database | MongoDB Atlas, Mongoose |
| Dev Tools | Nodemon, dotenv, CORS |
| Version Control | Git & GitHub |

---

## 📂 Project Structure

```
Zerodha/
│
├── frontend/          # Landing page (React.js)
│   ├── public/
│   └── src/
│       ├── components/
│       └── landing_page/
│
├── dashboard/         # Trading dashboard (React.js)
│   ├── public/
│   └── src/
│       ├── components/
│       └── data/
│
└── backend/           # REST API (Node.js + Express)
    ├── model/
    ├── schemas/
    ├── index.js
    └── .env
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/KANHAIYASINGH337/Zerodha.git
cd Zerodha
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the `backend/` folder:

```env
MONGO_URL=mongodb+srv://<username>:<password>@cluster0.xxxxx.mongodb.net/zerodha?retryWrites=true&w=majority&appName=Cluster0
```

Start the backend server:

```bash
npm start
# Runs on http://localhost:3002
```

### 3. Frontend Setup

```bash
cd ../frontend
npm install
npm start
# Runs on http://localhost:3000
```

### 4. Dashboard Setup

```bash
cd ../dashboard
npm install
npm start
# Runs on http://localhost:3001
```

---

## 🔌 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/allHoldings` | Fetch all holdings |
| GET | `/allPositions` | Fetch all positions |
| POST | `/newOrder` | Place a new order |

---

## 🌍 Environment Variables

| Variable | Description |
|---|---|
| `MONGO_URL` | MongoDB Atlas connection string |

> ⚠️ Never commit your `.env` file. It is already added to `.gitignore`.

---

## 📸 Screenshots

> _Add screenshots here after deployment._

| Page | Preview |
|---|---|
| Landing Page | `localhost:3000` |
| Dashboard | `localhost:3001` |

---

## 🎯 Future Enhancements

- [ ] Live Stock Market API Integration
- [ ] Real-Time Price Updates (WebSockets)
- [ ] Candlestick Charts (Recharts / TradingView)
- [ ] Complete Order History
- [ ] Payment Gateway Integration
- [ ] AI-based Investment Suggestions
- [ ] Email Notifications
- [ ] Docker Deployment

---

## 👨‍💻 Author


**Kanhaiya Kumar Singh**
B.Tech — Information Technology | Haldia Institute of Technology

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on [GitHub](https://github.com/KANHAIYASINGH337/Zerodha)!
