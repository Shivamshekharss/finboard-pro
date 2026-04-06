### 🏠 Dashboard Overview
![Dashboard](./client/public/dashboard.png)

### 📊 Analytics & Graphs
![Graphs](./client/public/graphs.png)

---

## 🚀 Live Demo

- 🌐 Frontend: https://finboard-pro-xi.vercel.app/  
- ⚙️ Backend API: https://finboard-pro-4.onrender.com/  

---

## 🚀 Tech Stack

### 🖥️ Frontend
- React + TypeScript (Vite)
- Material UI (MUI)
- Redux Toolkit Query
- Recharts (Data Visualization)

### ⚙️ Backend
- Node.js
- Express.js
- MongoDB + Mongoose

---

## 📁 Project Structure


finance-dashboard/
│
├── client/ # Frontend (React + Vite)
│
├── server/ # Backend (Node + Express)
│ ├── models/
│ ├── routes/
│ ├── data/
│ └── index.js
│
└── README.md


---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Shivamshekharss/finboard-pro.git
cd finboard-pro
2️⃣ Backend Setup
cd server
npm install

Create a .env file:

MONGO_URL=mongodb://127.0.0.1:27017/finance-dashboard
PORT=5000

Run backend:

npm start

Server runs at:
👉 http://localhost:5000

3️⃣ Frontend Setup
cd client
npm install

Create a .env file:

VITE_BASE_URL=http://localhost:5000

Run frontend:

npm run dev

Frontend runs at:
👉 http://localhost:5173

📊 Features
📈 KPI Analytics Dashboard
📦 Product Tracking System
💰 Transaction Management
📊 Interactive Charts & Graphs
⚡ Real-time API Integration
🎨 Fully Responsive UI
🔌 API Endpoints
KPI Data
GET /kpi/kpis
Products
GET /product/products
Transactions
GET /transaction/transactions
🧠 Notes
Database auto-seeds on first backend run
Ensure MongoDB is running locally
Frontend uses Redux Toolkit Query for API handling
Designed with scalability in mind
🛠️ Common Issues
❌ Cannot GET /kpi

✔ Ensure backend is running on port 5000
✔ Check .env file in server

❌ Empty UI Data

✔ Verify VITE_BASE_URL in frontend .env
✔ Ensure backend is running properly

🎯 Purpose

This project was built for:

Learning full-stack MERN development
Understanding dashboard UI design
Working with real-world API integration
Practicing modern frontend architecture
🌟 Future Improvements
🔐 User Authentication (JWT)
📅 Date-based filtering
📥 Export reports (CSV/PDF)
🌙 Dark mode support
🔔 Notifications system
📌 License

This project is open-source and created for learning purposes.

⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!

🚀 Made with dedication by Shivam Shekhar
