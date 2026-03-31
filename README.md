
# ✈️ Yuvi Airlines - Full Stack Flight Booking App

A full-stack airline booking application built using **React (Vite)** for frontend and **Node.js + Express + MongoDB** for backend.

---

## 🚀 Features

### 👤 User Features
- View all available flights
- Book flights
- View bookings
- Secure authentication (Protected Routes)
- Online payment flow

### 🛠️ Admin Features
- Admin login
- Admin dashboard
- Manage flights and bookings

---

## 🧑‍💻 Tech Stack

### Frontend
- React.js (Vite)
- React Router DOM
- Axios
- Bootstrap

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- Bcrypt

---
## 📁 Project Structure
yuvi-airlines/
│
├── backend/
│ ├── config/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── index.js
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── routes/
│ │ ├── layouts/
│ │ └── main.jsx
│ └── package.json
│
└── README.md


---

## ⚙️ Environment Variables

Create a `.env` file inside **backend/**:

```env
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/yuviairlines?retryWrites=true&w=majority
PORT=5000
JWT_SECRET=your_secret_key

---------------

▶️ Running Locally
1️⃣ Clone the repository
git clone https://github.com/your-username/yuvi-airlines.git
cd yuvi-airlines

2️⃣ Backend Setup
cd backend
npm install
npm start
3️⃣ Frontend Setup
cd frontend
npm install
npm run dev

🗄️ MongoDB Setup
Create cluster in MongoDB Atlas
Create Database User

Add IP:

0.0.0.0/0

Copy connection string and replace:

<db_password>




📌 Future Enhancements
Payment gateway integration
Seat selection
Email notifications
Ticket download (PDF)
👩‍💻 Author

Mouneswari Pentakota

Frontend Developer (React.js)
3+ years experience

⭐ If you like this project

Give it a ⭐ on GitHub 😊

```md
This project demonstrates real-world experience in building scalable full-stack applications with authentication, role-based access, and REST API integration.

